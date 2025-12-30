Docker Installation & IoT Gateway Setup (Debian / ARM64)

This document describes the step-by-step installation of Docker on a Debian-based ARM64 Linux system (Ubuntu / Raspberry Pi OS) and the process to build and run IoT Gateway Docker images.

1️⃣ Remove Old or Corrupted Docker Installations (Optional but Recommended)

If Docker was previously installed and is corrupted or outdated, remove it completely

2️⃣ Update System Packages

3️⃣ Install Required Dependencies

4️⃣ Add Docker’s Official GPG Key

Note: If you face a GPG permission error, run:
sudo chmod a+r /etc/apt/keyrings/docker.gpg

5️⃣ Add Docker Repository

6️⃣ Update Package Index Again

7️⃣ Install Docker Engine & Docker Compose Plugin

8️⃣ Verify Docker & Docker Compose Installation

9️⃣ Build Docker Images for IoT Gateway

Build Docker images

🔟 Start Services Using Docker Compose

Navigate to the Mosquitto director

Start containers

✅ Summary

Docker installed on Debian / ARM64

Docker Compose enabled

IoT Gateway Docker images built

MQTT (Mosquitto) services started using Docker Compose
