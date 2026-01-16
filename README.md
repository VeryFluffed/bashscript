# Linux CyberPatriots Bash Script

A modular Bash script designed for CyberPatriot Linux competitions to rapidly harden systems, secure users, and configure services across multiple Linux distributions. I built this tool to maximize scoring efficiency under time pressure, cutting hours off manual hardening during competition rounds.

## Features

Here's what you can do:

- **Modular Tool Selection**: Pick and choose which hardening actions to run based on the image and competition requirements.

- **User & Account Security**: Enumerates users from /etc/passwd, secures or removes unautorized users, and configures administrator status.

- **Common Tasks**: Enforces strong password complexity (PAM files), Firewall configuration, and system updates/package management.

- **Service Hardening**: Disables unnessesary or insecure services and locks down common attack vectors (FTP, SSH, nginx, etc.)

## 🎯 Achievements & Impact:

- Top 100 National Semifinalist — Platinum Tier (2×)<br>
- Top 1% nationwide among CyberPatriot competitors<br>
- #1 in California Gold Tier prior to advancing to Platinum<br>
- Recognized as the Linux specialist on the team, consistently assigned the most technically demanding tasks<br>
- Developed a reputation for high-efficiency scripting, shaving multiple hours off team workflow during live competition

## 👩🏽‍🍳 The Process

This script was built iteratively for real competitions, not as a theoretical exercise.

Next, I made sure users could move elements around. This was important for adjusting drawings. After that, I added the ability to resize elements to give more control over the shapes.

I realized I spent a large portion of the 6 or 4 hours of the competition repeating the same tasks during ever round. So, I started by identifying repeatable, high-impact tasks that consumed the most time during early rounds: user management, password policy enforcement, firewall setup, and updates. Each feature was added only after validating that it improved speed without risking stability.

The script was structured to be modular and readable, allowing me to:

- Enable or disable actions quickly <br>
- Adapt to unknown competition images<br>
- Debug issues under strict time constraints

Throughout development, I documented:

- Scoring rubrics and common pitfalls<br>
- Which changes consistently earned points<br>
- Which actions could accidentally break services

This approach ensured the script was competition-safe, not just technically correct.

## 📚 What I Learned

This project significantly strengthened my Linux security, scripting, and systems thinking skills.

### 🧠 Bash Scripting Under Constraints<br>
- Learned to write clear, defensive Bash that prioritizes safety and reversibility<br>
- Balanced automation speed with system integrity

### 🔐 Linux System Hardening<br>
- Deepended understasnding of ser privilege models, PAM authentication, password policies, service management, and firewall behavior

### ⚡ Competition-Grade Efficiency<br>
- Optimized workflows for maximum point gain per minute<br>
- Reduced cognitive load during live rounds by automating repetitive checks

### 🧩 Risk-Aware Automation<br>
- Learned when not to automate<br>
- Designed logic that avoids breaking required services or scoring items

### 📈 Leadership & Trust<br>
- Became the team’s go-to Linux specialist<br>
- Earned trust to run scripts that affected the entire system image

## 🚦 Running the Project

To run the project in your local environment, follow these steps:

1. Create a text file in terminal. Make sure it has .sh at the end of hte name. Type: sudo gedit script.sh<br>
2. Copy and paste the script file into the text file.<br>
3. Save the script and exit.<br>
4. Make script executable. Type: sudo chmod +x script.sh<br>
5. Run the script as root. Type : sudo ./script.sh
