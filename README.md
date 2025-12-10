# first-gcp-website
First website deployed on GCP (Debian + Apache)

This repository contains a minimal `index.html` to demonstrate deploying a static website to a Google Cloud (GCP) VM running Debian and Apache.

**What I built**
- Simple static website (index.html)
- Hosted on a Debian VM on Google Cloud using Apache2

**How to deploy**
1. Create a Debian VM on GCP.
2. Install Apache: `sudo apt update && sudo apt install -y apache2`.
3. Clone this repository on the VM and copy `index.html` to `/var/www/html/index.html`.
4. Ensure firewall allows HTTP (port 80).

**Author**
- Indresh Pal
- Date: 2025-12-10


