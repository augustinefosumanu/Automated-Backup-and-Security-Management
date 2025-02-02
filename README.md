# Automated Backup and Security Management

<h2> Lab </h2>
In this lab, I developed and automated critical system tasks to enhance data security, integrity, and HIPAA compliance:<br/>

-  <b>File Organization</b>: Automated movement of patient, doctor, and treatment files using cron.<br />
-  <b>Backup Automation</b>: Scheduled full backups of critical directories and verified archive integrity.<br />
-  <b>System Maintenance</b>:<br />
  -  backup.sh – Backups /home directory.<br />
  -  update.sh – Automates system updates.<br />
-  <b>Security & Compliance</b>: Integrated scripts into system-wide cron jobs and scheduled Lynis security scans.<br />
<br />

<h2> Step 1: Checking the Status of Cron </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/NVWLOYg.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 2: Creating Directories </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/eoKqfk4.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/sL1eFWD.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 3: Automating Tasks in Crontab </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/lSdn1dh.png" height="80%" width="90%" alt=""/>
<br />
<img src="https://i.imgur.com/PrcVDDY.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/ry5bklY.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/fqx0Inf.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Step 4: Verifying the Creation of Crontab </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/39s8NL4.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 5: Creating Directories for Scripts </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/AmDE7tk.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 6: Creating Backup Script File </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/v6OZll6.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/HXc5w0v.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/BmnSmR9.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/dynD1h2.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 7: Executing Backup Script File </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/h3Mvsdb.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/b1yLpPR.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/ZTt6mUt.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/gnjBPFT.png" height="80%" width="90%" alt=""/>
<br />
<br />


<h2> Step 8: Creating Update Script File </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/xJ3kmJC.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/HILh3V9.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/WtKWuW0.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/KwkUlAM.png" height="80%" width="90%" alt=""/>
<br />
<br />


<h2> Step 9: Executing Update Script File </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/90qQTfz.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/H0hnZxC.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 10: Copying Scripts to Cron Directories in /etc </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/zqi56rw.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 13: Ensuring System Security with Regular Scans </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/1WtBqAN.png" height="80%" width="90%" alt="Full Scan"/>
<br />
<br />
<img src="https://i.imgur.com/oT0HvSZ.png" height="80%" width="90%" alt="Full Scan"/>
<br />
<br />
<img src="https://i.imgur.com/3R2GKEj.png" height="80%" width="90%" alt="Partial Scan"/>
<br />
<br />
<img src="https://i.imgur.com/w13Nzct.png" height="80%" width="90%" alt="Partial Scan"/>
<br />
<br />
<img src="https://i.imgur.com/zg3xfD8.png" height="80%" width="90%" alt="Adding Lynis Scripts to Root Crontab for Task Automation"/>
<br />
<br />
