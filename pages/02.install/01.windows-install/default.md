---
title: 'Windows Install'
---

### 1. Download Kavita

Download the Windows Installer with the following link and execute it. Download [here](https://github.com/Kareadita/Kavita/releases).

### 2. Install Kavita

1. Unzip the archive to a directory that is writable. Do not place in Program Files/ or Program Files (x86)/
2. Run Kavita executable.
3. Open http://localhost:5000 and setup your [user accounts](https://wiki.kavitareader.com/guides/user-management) and [Libraries](https://wiki.kavitareader.com/guides/adding-a-library) in the UI.

Alternate methods to run Kavita upon Windows startup are available instead of running the program each time you login.
- Add a shortcut to Kavita to your Startup Folder in Windows
- Use the Non-Sucking Service Manager aka [NSSM](https://nssm.cc/) to make Kavita a Windows Service.  A user has written a nice guide on Reddit that might be beneficial. [Guide](https://www.reddit.com/r/KavitaManga/comments/s6mans/tutorial_how_to_use_nmms_to_create_a_windows/)

### 3. View Kavita

Browse to http://localhost:5000 to start using Kavita from any device inside your network. (A Windows Firewall rule allowing Incoming access to Port 5000 may be required.)

! "localhost" should be replaced with the IP address of the machine that is running Kavita when accessing from inside your network from a different device like a phone or tablet.
For more instructions on how to make Kavita accessible from outside your home network... see the [Reverse Proxy](https://wiki.kavitareader.com/install/reverse-proxy) page.
