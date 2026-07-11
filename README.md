# 🛡️ MEGHIX TRINETRA  
## CLOUD DEFENSE AI  
### THE THIRD EYE OF CYBERSECURITY  

---

## 🚀 Overview  
MEGHIX TRINETRA is a cloud-based AI cybersecurity system designed for real-time phishing detection and threat intelligence. It identifies malicious websites and protects users from cyber threats using machine learning and cloud infrastructure.

This project combines **Artificial Intelligence, Cloud Computing, and Cybersecurity** to build a next-generation phishing detection system.

---

## 🎯 Problem Statement  
Phishing websites are one of the most dangerous cyber threats today. They impersonate legitimate websites to steal sensitive information like passwords, bank details, and personal data.

There is a need for an intelligent system that can detect and prevent such attacks in real time.

---

## 💡 Solution  
MEGHIX TRINETRA provides an AI-driven solution that:
- ☁️ Cloud-based scalable system  
- 🛡️ Cybersecurity threat detection  
- 🤖 AI-powered phishing detection  
- 🔍 Real-time URL analysis  
- ⚡ Instant prediction results  

---

## ⚙️ Features  
- ☁️ Cloud-based architecture  
- 🛡️ Cybersecurity protection system  
- 🤖 Machine learning-based detection  
- 🔍 Real-time URL scanning  
- ⚡ Fast and accurate predictions  
- 📊 Simple and clean interface  

---
---

# AWS DevOps Deployment

## Deployment Environment

- AWS EC2 (Ubuntu)
- Nginx
- Gunicorn
- Python Flask
- Docker
- GitHub

## Deployment Steps

1. Created Ubuntu EC2 instance.
2. Configured Security Group (Ports 22 & 80).
3. Connected using SSH.
4. Installed Nginx.
5. Cloned the GitHub repository.
6. Created Python virtual environment.
7. Installed project dependencies.
8. Started Flask application using Gunicorn.
9. Configured Nginx as a reverse proxy.
10. Successfully deployed the application.

## Linux Commands Used

```bash
sudo apt update
sudo apt install nginx -y
sudo systemctl status nginx
df -h
free -h
ps aux
git clone https://github.com/siddharthajain5851/Meghix-Trinetra.git
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
gunicorn --bind 0.0.0.0:5000 app:app
sudo apt install docker.io -y
docker run hello-world

## 🧠 How It Works  
1. User enters a URL  
2. System extracts URL features  
3. AI model analyzes patterns  
4. System predicts result:

``` id="n2g7uv"

4. System predicts result:

- 🟢 Safe Website  
- 🔴 Phishing Website
---

## 🚀 Live Demo

👉 Try the live project here:  
https://phishing-website-detection-system-mp6d.onrender.com
