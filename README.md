# cloud-lab-LynaKorichi# TP3: Virtualization on the Cloud with GitHub Codespaces
**Module:** Cloud Computing  
**Student:** Lyna Korichi Racha
**Date:** 2026  

## Project Overview
This lab demonstrates the creation and configuration of a cloud-based development environment using **GitHub Codespaces**. [cite_start]I installed and configured an **Apache2 web server** on an Ubuntu-based cloud instance to serve a custom website.

## Tasks Completed
* **Environment Setup:** Created a GitHub repository and launched a Codespace instance.
* **Web Server Installation:** Installed Apache2 using `sudo apt install apache2` and managed the service.
* **Configuration:** Modified `apache2.conf` to set `ServerName localhost` and suppress warnings.
* **Web Development:** Edited `index.html` to include personal details and linked a custom `style.css` for styling.
* **Port Forwarding:** Forwarded Port 80 and set visibility to **Public** to share the live website.
* **Media Integration:** Created an images directory and integrated a custom image (`snoopy.jpg`).

## Comprehension Questions
1. **What is GitHub Codespaces?** It is a complete virtual computer running in the cloud based on Ubuntu Linux with VS Code built-in.
2. **Role of Apache?** It serves as the web server to host and provide access to the website files.
3. **Cloud vs. Local Advantages?** Cloud environments offer accessibility from any browser, no local software overhead, and high scalability.
4. **How can you check if the Apache service is running in Linux:**
  - sudo service apache2 status 
  - systemctl status apache2

## How to View
The website was served via Port 80 through the link:
 https://super-space-funicular-6997qjrgx6wghrr47-80.app.github.dev/ 
