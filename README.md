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

### Turbulence Realm SINDy v2.2.1

Video-based fluid-flow analysis with Sparse Identification of Nonlinear Dynamics.

v2.2.1 adds six SINDy method variants (Classical, SINDy-PI, PDE-FIND, WSINDy,
E-SINDy, SINDYc) with a Method dropdown and dynamic parameter controls.
Cross-validation and comparison are now crash-resistant. Windows builds now
bundle CPU-only PyTorch, torchvision, ONNX, and ONNX Runtime so ML models
work out of the box. Fixed missing libraries (sympy, scipy submodules),
animated heatmap display, title bar icon, and application icon.

| File | Platform | Description |
|------|----------|-------------|
| `TurbulenceRealmSINDy-2.2.1-Linux-Installer.run` | Linux (any) | Self-extracting installer with disclaimer, desktop integration, uninstaller |
| `TurbulenceRealmSINDy-2.2.1-amd64.deb` | Linux (Debian/Ubuntu) | Debian package with disclaimer, menu entry, uninstaller |
| `TurbulenceRealmSINDy-2.2.1-Setup.exe` | Windows | Inno Setup installer with disclaimer, shortcuts, icon, uninstaller (includes PyTorch) |

## Screenshots and Demos

### Turbulence Realm SINDy v2.2.1

![SINDy workflow overview](https://raw.githubusercontent.com/fayazr/turbulencerealm-downloads/main/assets/TR-SINDY-flow.png)

![SINDy spatial-error analysis](https://raw.githubusercontent.com/fayazr/turbulencerealm-downloads/main/assets/TR-SINDY-SPATIAL-ERROR.png)

![SINDy demo](https://raw.githubusercontent.com/fayazr/turbulencerealm-downloads/main/assets/TR-SINDy.gif)

### Turbulence Realm-Tracker v3.2.0

![Tracker demo](https://raw.githubusercontent.com/fayazr/turbulencerealm-downloads/main/assets/tr-tracker.gif)

![Tracker analysis view](https://raw.githubusercontent.com/fayazr/turbulencerealm-downloads/main/assets/tr-track.png)

## Disclaimer

Each installer includes a no-liability disclaimer that must be accepted
before installation. The software is provided "AS IS", without warranty of
any kind.

## Source Code

- Tracker: https://github.com/fayazr/TR-TRACK
- SINDy: https://github.com/fayazr/TR-SINDY
