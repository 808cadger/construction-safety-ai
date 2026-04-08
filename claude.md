# Construction Safety AI - PPE Detection & Alert System
Production-ready construction site monitoring: YOLOv8 PPE detection (hard hats/vests/gloves), real-time alerts, violation logs. Flask web app + Docker. Multi-camera scalable.

Repo: https://github.com/808cadger/construction-safety-ai. Dev: cadger808 (Pearl City, HI).

## Stack & Safety Pipeline
- Backend: Python/Flask (PPE detection API)
- Vision: YOLOv8 + OpenCV (hard hats, vests, gloves, glasses)
- Container: Docker + docker-compose.yml
- Deploy: Production-ready multi-camera
- Alerts: Email/SMS for violations
- CI: GitHub workflows

## Key Files & Pipeline
Dockerfile | docker-compose.yml | requirements.txt | README.md | setup.py

## Commands
# Dev
pip install -r requirements.txt
python app.py  # Flask dev server

# Production
docker-compose up -d
docker-compose logs -f

## Code Rules — PPE Detection Pipeline
- **Pipeline**: Camera feed → YOLOv8 detection → PPE compliance check → Alert if violation
- **PPE Types**: Hard hats, high-vis vests, gloves, safety glasses, harnesses
- **#ASSUMPTION**: Camera calibrated; TODO: auto-calibration
- **Scoring**: Confidence thresholds per PPE type (hard hat >0.85, vest >0.75)
- **Zones**: Different PPE requirements per site zone
- **Alerts**: Email/SMS within 5s of violation
- **Logs**: Violation database with timestamps/images
- **Phases**: MVP (single camera) → Multi-cam → Mobile app → AR glasses

## AI Prompts — Safety Critical

## Claude Workflow (Auto-Debug ON)
1. Read CLAUDE.md + requirements.txt first
2. docker-compose up → check logs
3. "PPE detection accurate? Alert timing? Zone compliance?"
4. Review: False positives? Camera handling? Docker health?
5. Output: "Debug complete: Docker running, PPE detected" + patches
6. Commit: "feat: [ppe|alert|zone|docker] [desc]"

## Deploy Checklist

## Python Factory Integration

**Your empire = 12 apps**: 11 JS/Capacitor + **1 Python/Docker**. Construction Safety AI proves your factory scales beyond mobile—**enterprise computer vision** now shipping with identical CLAUDE.md DNA. **Commit → your AI safety revolution begins.** 🏗️🛡️
