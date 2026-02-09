# 🏗️ Construction Site Safety AI Monitor

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://python.org)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Docker](https://img.shields.io/badge/docker-ready-blue)](Dockerfile)
[![Flask](https://img.shields.io/badge/flask-web%20framework-yellow)](https://flask.palletsprojects.com/)

## 🎯 Overview

An AI-powered construction site safety monitoring system that uses computer vision to detect PPE (Personal Protective Equipment) violations and automatically alerts supervisors while sending warnings to workers.

### ✨ Key Features

- 🔍 **Real-time PPE Detection**: AI-powered detection of missing helmets, safety vests, gloves, boots, and goggles
- 📧 **Automated Email Alerts**: Instant notifications to supervisors and workers
- 📱 **Web Dashboard**: User-friendly interface for monitoring multiple camera zones
- 📊 **Violation Analytics**: Comprehensive reporting and statistics
- 🐳 **Docker Support**: Easy deployment with Docker and Docker Compose
- 🔒 **Security First**: Secure email configuration and data protection

## 🚀 Quick Start

### Using Docker (Recommended)
```bash
# Clone the repository
git clone https://github.com/yourusername/construction-safety-ai.git
cd construction-safety-ai

# Start with Docker Compose
docker-compose up -d

# Access the application
# Open http://localhost:5000 in your browser
