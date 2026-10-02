<h2 align="center">VMPal</h2>
<h3 align="center">Fast macOS, Windows and Linux Virtual Machines for Apple Silicon</h3>

<p align="center">
    <a href="https://vmpal.com/download">
        <img src="https://img.shields.io/badge/-Download-ff9600?style=for-the-badge" alt="Download">
    </a>
    <a href="https://github.com/TablePlus/VMPal-issue-tracker/issues">
        <img src="https://img.shields.io/badge/-Bugs%20%2F%20Features-7057ff?style=for-the-badge" alt="Bugs/Features">
    </a>
    <a href="https://vmpal.com/changelog">
        <img src="https://img.shields.io/badge/-Changelog-blue?style=for-the-badge" alt="Changelog">
    </a>
</p>

<br>

<h4 align="center">
    <u>
        This repository is the official issue & bug tracker of VMPal for macOS
    </u>
</h4>

<br>

<pre align="center">
VMPal is a native app that runs virtual machines on your
Apple silicon Mac, each in its own window. A new VM starts
from a base OS and takes almost no space until you use it

Supports macOS, Windows 11 for Arm, Ubuntu and Fedora,
and imports your VMs from Parallels Desktop
</pre>

<br>

<h3 align="center">As excited as we are?</h3>
<h4 align="center">Check out VMPal in action:</h4>

![Library](Resources/library.png "Your virtual machines, in one window")

<h4 align="center">macOS</h4>

![macOS](Resources/vm-macos.png "macOS 27")

<h4 align="center">Windows</h4>

![Windows](Resources/vm-windows.png "Windows 11")

<h4 align="center">Linux</h4>

![Linux](Resources/vm-linux.png "Ubuntu 26.04")

<br>

<h3 align="center">Found a bug?</h3>

<h4 align="center">
    <a href="https://github.com/TablePlus/VMPal-issue-tracker/issues/new/choose">Open an issue</a>
    and attach your VM's log, so we can see what happened
</h4>

### Sending us a log

When a VM crashes, stops with an error or won't start, its log tells us why.

1. In Finder, choose **Go › Go to Folder…** (⇧⌘G), paste `~/Library/Logs/VMPal` and press Return.
2. Find the log named after your VM, such as `Windows 11.log`. If there's a `Windows 11.old.log` too, include it.
3. Then either:
   - **Attach it to your issue**: drag the `.log` file into the issue's comment box, or
   - **Email it** to [nick@tableplus.com](mailto:nick@tableplus.com), with your issue's link or a few words on what happened.

A log can include your VM's name and the names of files and folders on your Mac. If you'd rather not post it publicly, email it.

Some problems have a log of their own. Please attach it as well:

- **VMPal or a VM quit unexpectedly**: macOS keeps a crash report. Go to `~/Library/Logs/DiagnosticReports` the same way, select the files whose names start with `VMPal` from around that time, choose **File › Compress**, and attach the `.zip`.
- **A Linux base OS didn't install**: go to `~/Library/Application Support/VMPal/Downloads/Linux` and attach `ubuntu-install.log` or `fedora-install.log`.
- **VMPal Tools didn't install in Windows**: click **Show Log** in its installer, or open `C:\Windows\Temp\VMPal Tools.log`. Copy it to your Mac, for example through a shared folder, and attach it.

<br>

<h3 align="center">Thank you for trying VMPal</h3>

<h4 align="center">
    We would be thrilled if you
    <a href="https://vmpal.com/pricing">purchased a license</a>
    to support development!
</h4>

<br>
<br>

<p align="center">
    VMPal Team |
    <a href="mailto:nick@tableplus.com">nick@tableplus.com</a>
</p>

<p align="center">
    <a href="https://vmpal.com">
        <img src="https://img.shields.io/badge/-vmpal.com-ff9600?style=for-the-badge" alt="vmpal.com">
    </a>
    <a href="https://tableplus.com">
        <img src="https://img.shields.io/badge/-Made%20by%20TablePlus-7057ff?style=for-the-badge" alt="Made by TablePlus">
    </a>
</p>
