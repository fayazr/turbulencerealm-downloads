# Turbulence Realm Downloads

Official installer downloads for **Turbulence Realm-Tracker** and **Turbulence Realm SINDy**.

Website: https://www.turbulencerealm.com

## Latest Releases

### Turbulence Realm-Tracker v3.2.0

Video-based bubble velocimetry and fluid-dynamics analysis console.

v3.2 removes the 3D trajectory visualization and GPU Info/acceleration
features from the UI (heatmaps and time-lapses remain), and bumps the
installers. Built on v3.1's automatic multi-object tracking (MOT),
watershed segmentation with bubble-size distributions, fluid-physics
outputs (Reynolds/Weber/Eötvös, drag, terminal velocity), Eulerian flow
fields, coalescence/breakup event detection, live camera capture,
lens-distortion correction, uncertainty propagation, one-click PDF
reports and a pandas DataFrame API.

| File | Platform | Description |
|------|----------|-------------|
| `TurbulenceRealmTracker-3.2.0-linux-installer.run` | Linux (any) | Self-extracting installer with disclaimer, desktop integration, uninstaller |
| `turbulencerealmtracker_3.2.0_amd64.deb` | Linux (Debian/Ubuntu) | Debian package with disclaimer, menu entry, uninstaller |
| `TurbulenceRealmTracker-3.2.0-setup.exe` | Windows | Inno Setup installer with disclaimer, shortcuts, uninstaller |

### Turbulence Realm SINDy v2.2.0

Video-based fluid-flow analysis with Sparse Identification of Nonlinear Dynamics.

v2.2 reworks the ML models (PINN trains on multiple frames, Autoencoder-SINDy
learns latent coefficients jointly, FNO gains nonlinearity, ConvLSTM unrolled
over time, GAN outputs full flow snapshots, DeepONet trains across all frame
pairs), adds async background training, and enforces divergence-free via FFT
Helmholtz projection.

| File | Platform | Description |
|------|----------|-------------|
| `TurbulenceRealmSINDy-2.2.0-Linux-Installer.run` | Linux (any) | Self-extracting installer with disclaimer, desktop integration, uninstaller |
| `TurbulenceRealmSINDy-2.2.0-amd64.deb` | Linux (Debian/Ubuntu) | Debian package with disclaimer, menu entry, uninstaller |
| `TurbulenceRealmSINDy-2.2.0-Setup.exe` | Windows | Inno Setup installer with disclaimer, shortcuts, uninstaller |

## Disclaimer

Each installer includes a no-liability disclaimer that must be accepted
before installation. The software is provided "AS IS", without warranty of
any kind.

## Source Code

- Tracker: https://github.com/fayazr/TR-TRACK
- SINDy: https://github.com/fayazr/TR-SINDY
