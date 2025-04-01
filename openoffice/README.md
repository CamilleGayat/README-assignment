<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/CamilleGayat/README-assignment">
    <img src="https://www.openoffice.org/trademark/logo_color.png" alt="Logo" width="400">
  </a>

  <h3 align="center">OpenOffice.org 2.4</h3>

  <p align="center">
    A powerful open-source office productivity suite
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>📋 Table of Contents</summary>
  <ol>
    <li>
      <a href="#-about-the-project">🔍 About The Project</a>
      <ul>
        <li><a href="#️-built-with">🛠️ Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#-getting-started">🚀 Getting Started</a>
      <ul>
        <li><a href="#-prerequisites">📋 Prerequisites</a></li>
        <li><a href="#-installation">💻 Installation</a></li>
      </ul>
    </li>
    <li><a href="#-usage">📝 Usage</a></li>
    <li><a href="#️-known-issues">⚠️ Known Issues</a></li>
    <li><a href="#️-roadmap">🗺️ Roadmap</a></li>
    <li><a href="#-contributing">👥 Contributing</a></li>
    <li><a href="#-license">📄 License</a></li>
    <li><a href="#-contact">📞 Contact</a></li>
    <li><a href="#-acknowledgments">🙏 Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## 🔍 About The Project

<div align="center">
<img src="../img/writer-big.gif" alt="Product Screenshot" width="600" style="margin-bottom: 20px;">
</div>

OpenOffice.org 2.4 is a free, open-source office productivity suite that provides a powerful alternative to commercial office software. This project is maintained by the OpenOffice.org community, who invites you to become a member.

Here's why OpenOffice.org is amazing:
* Your time should be focused on creating meaningful work, not paying for expensive software
* You get a complete suite of office tools including word processing, spreadsheets, presentations, and more
* The software is available to everyone - including government, business, educational and private users

OpenOffice.org is free for use by everybody. For further details, see the license text delivered together with OpenOffice.org or visit [http://www.openoffice.org/license.html](http://www.openoffice.org/license.html).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### 🛠️ Built With

OpenOffice.org is built with a focus on cross-platform compatibility and open standards.

[![C++][Cpp.org]][Cpp-url]
* Java
* XML
* Open Document Format (ODF)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## 🚀 Getting Started

This section will help you set up OpenOffice.org 2.4 on your local machine.

### 📋 Prerequisites

Before installing OpenOffice.org 2.4, make sure your system meets the following requirements:

* Microsoft Windows 98, ME, NT (Service Pack 6 or later), 2000 or XP
* Pentium-compatible PC
* 64 MB of RAM
* 250 MB of free disk space (CJK version: 300 MB)
* 500 MB disk space needed after installation is complete when deleting temporary installer files
* Screen resolution of at least 800x600 with at least 256 colors

### 💻 Installation

1. Download the OpenOffice.org 2.4 [installer](https://www.openoffice.org/download/index.html) from the official website
2. Close all other programs before starting the installation
3. Run the installer and follow the on-screen instructions
4. If prompted to install Java, follow the instructions (Windows 98 users may need to ignore reboot messages or restart the installer after reboot)
5. After installation, you may want to register your copy (optional but appreciated)

**Notes:**
* Administrator rights are needed for the installation process
* You can install OpenOffice.org 2.4 alongside an older version of OpenOffice.org

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## 📝 Usage

OpenOffice.org 2.4 includes a complete suite of office productivity applications:

* Writer (word processing)
* Calc (spreadsheets)
* Impress (presentations)
* Draw (vector graphics and flowcharts)
* Base (databases)
* Math (equation editor)

For more detailed documentation and examples, please refer to the integrated help system or visit [http://www.openoffice.org](http://www.openoffice.org).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- KNOWN ISSUES -->
## ⚠️ Known Issues

### 🚫 Problems During Program Startup

Difficulties starting OpenOffice.org (e.g., applications hang) as well as problems with the screen display are often caused by the graphics card driver. If these problems occur, please update your graphics card driver or try using the graphics driver delivered with your operating system. Difficulties displaying 3D objects can often be solved by deactivating the option "Use OpenGL" under 'Tools - Options - OpenOffice.org - View - 3D view'.

### 🖱️ ALPS/Synaptics Notebook Touchpads in Windows

Due to a Windows driver issue, you cannot scroll through OpenOffice.org documents when you slide your finger across an ALPS/Synaptics touchpad.

To enable touchpad scrolling, add the following lines to the:
- "C:\Program Files\Synaptics\SynTP\SynTPEnh.ini" 
configuration file, and restart your computer:

```
[OpenOffice.org]
FC = "SALFRAME"
SF = 0x10000000
SF |= 0x00004000
```

Note: The location of the configuration file might vary on different versions of Windows.

### 📧 Email Issues

The program may crash or freeze when trying to send a document by email using File - Send - Document by Email or Document as PDF attachment. This is due to the Windows MAPI (Messaging Application Programming Interface) system file generating errors with certain file versions.

### ⌨️ Keyboard Shortcuts

You can only use keyboard shortcuts in OpenOffice.org that are not already used by your operating system. If a key combination in OpenOffice.org doesn't work as described in the help, it might already be in use by your system. To resolve such conflicts, you can either change the shortcuts assigned by your operating system or modify most shortcuts in OpenOffice.org.

### 🔍 Ai Squared ZoomText Compatibility

If you want to use Ai Squared ZoomText with OpenOffice.org 2.4, you need at least version 7.11. Only versions of Ai Squared ZoomText downloaded after June 12, 2002, offer the required functionality.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## 🗺️ Roadmap

The OpenOffice.org community is constantly working to improve the software. Stay updated with the latest developments by subscribing to the mailing lists.

See the [open issues](https://github.com/CamilleGayat/README-assignment/issues/new) for a list of proposed features and known issues.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## 👥 Contributing

Your active participation in the development of this great Open Source project would bring much to the OpenOffice.org community.

As a user, you are already a valuable contributor to the development process of this office suite. We invite you to get even more involved by contributing to community activities in the long term.

1. Subscribe to one or more of the mailing lists at [http://www.openoffice.org/mail_list.html](http://www.openoffice.org/mail_list.html)
   - News: announce@openoffice.org *recommended to all users* (light traffic)
   - Main user forum: discuss@openoffice.org *easy way to lurk on discussions* (heavy)
   - Marketing project: dev@marketing.openoffice.org *beyond development* (getting heavy)
   - General code contributor list: dev@openoffice.org (moderate/heavy)

2. Join one or more projects at [http://projects.openoffice.org/index.html](http://projects.openoffice.org/index.html)
   - Projects range from Localization, Porting, and Groupware to core coding projects
   - Non-developers can contribute to Documentation or Marketing projects

3. Report bugs and issues through IssueZilla, the bug tracking tool hosted on the OpenOffice.org website

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## 📄 License

OpenOffice.org is distributed under the open-source license. See the `LICENSE` file for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## 📞 Contact

Camille GAYAT - qps@gmail.com

Project Link: [https://github.com/CamilleGayat/README-assignment](https://github.com/CamilleGayat/README-assignment)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## 🙏 Acknowledgments

* The entire OpenOffice.org community for their contributions
* Portions Copyright 1998, 1999 James Clark
* Portions Copyright 1996, 1998 Netscape Communications Corporation

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/your_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/your_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/your_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/your_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/your_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/your_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/your_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/your_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/your_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/your_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/your_username
[product-screenshot]: images/screenshot.png