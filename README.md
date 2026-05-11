# Construction Safety AI

[![Release](https://img.shields.io/github/v/release/808cadger/construction-safety-ai?include_prereleases&label=release)](https://github.com/808cadger/construction-safety-ai/releases)
[![Last commit](https://img.shields.io/github/last-commit/808cadger/construction-safety-ai)](https://github.com/808cadger/construction-safety-ai/commits)
[![License](https://img.shields.io/github/license/808cadger/construction-safety-ai)](https://github.com/808cadger/construction-safety-ai/blob/HEAD/LICENSE)
![Platforms](https://img.shields.io/badge/platform-Python%2FAPI%2C%20Computer%20Vision-2563eb)

Computer-vision safety monitor for construction PPE and jobsite compliance workflows.

## Project Snapshot

| Area | Details |
|------|---------|
| Primary use case | Computer-vision safety monitor for construction PPE and jobsite compliance workflows. |
| Platforms | Python/API, Computer Vision |
| Core stack | Python, YOLOv8, FastAPI, Computer Vision |
| Review first | `README.md` |

## Download Links

| Platform | Link |
|----------|------|
| iOS / iPhone | [Open the PWA in Safari](https://808cadger.github.io/construction-safety-ai/) and choose **Share -> Add to Home Screen** |
| Android | [Download the latest APK from GitHub Releases](https://github.com/808cadger/construction-safety-ai/releases/latest) |
| Source | [Download the GitHub source ZIP](https://github.com/808cadger/construction-safety-ai/archive/refs/heads/main.zip) |
| Repository | [View on GitHub](https://github.com/808cadger/construction-safety-ai) |

## Why This Repo Is Worth Reviewing

- Targets a real construction safety compliance use case.
- Python package/API structure keeps model logic testable.
- Clear fit for AI, CV, and construction-tech review.


<!-- INSTALL-START -->
## Install and run

These instructions install and run `construction-safety-ai` from a fresh clone.

### Clone
```bash
git clone https://github.com/808cadger/construction-safety-ai.git
cd construction-safety-ai
```

### Python/API service
```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m pip install -e .
```

### Notes
- Create any required `.env` file from `.env.example` before starting backend services.

### AI/API setup
- If the app has AI features, add the required provider key in the app settings or local `.env` file.
- Browser-only apps store user-provided API keys on the local device unless a backend endpoint is configured.

### License
- Apache License 2.0. See [`LICENSE`](./LICENSE).
<!-- INSTALL-END -->


[![GitHub last commit](https://img.shields.io/github/last-commit/808cadger/construction-safety-ai)](https://github.com/808cadger/construction-safety-ai/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/808cadger/construction-safety-ai)](https://github.com/808cadger/construction-safety-ai)
[![GitHub stars](https://img.shields.io/github/stars/808cadger/construction-safety-ai?style=social)](https://github.com/808cadger/construction-safety-ai/stargazers)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://python.org/)
[![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?logo=ultralytics&logoColor=black)](https://ultralytics.com/)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)](https://opencv.org/)

This solution provides a complete, production-ready construction site safety monitoring system with AI-powered PPE detection, automated alerts, and comprehensive violation management. The system can be easily deployed on construction sites and scaled to multiple cameras and locations.
