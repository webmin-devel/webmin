## Contents
* [Changelog](https://github.com/webmin/webmin/blob/master/CHANGELOG.md)
* [About](#about)
* [Install](#install)[<img src="https://camo.githubusercontent.com/5481be3aeae21f33f5db53cfe13a2eebda73f897/68747470733a2f2f726f73746f76747365762e696f2f7075622f6d656469612f69636f6e732f646f776e6c6f61642d32337831342e706e67" title="Stable Versions">](http://webmin.com/download.html)[<img src="https://rostovtsev.io/pub/media/icons/download-23x14-devel.png" title="Development Versions">](http://webmin.com/devel.html)
* [Development](#development)
* [License](#license)

## About
**Webmin** is a web-based system administration tool for Unix-like servers, and services with over _1,000,000_ installations worldwide. Using it, it is possible to configure operating system internals, such as users, disk quotas, services or configuration files, as well as modify, and control open-source apps, such as BIND DNS Server, Apache HTTP Server, PHP, MySQL, and [many more](https://doxfer.webmin.com/Webmin/Introduction). It can be expanded by installing modules, which can be custom made. Aside from this, there are two other major projects that extend its functionality:

* [Virtualmin](https://www.virtualmin.com) is a powerful, flexible, most popular, and most comprehensive web-hosting control panel for Linux, and BSD systems, with over _100,000_ installations worldwide. It is available in an open-source community-supported version, and a more feature-filled version with premium support;
* [Usermin](https://github.com/webmin/usermin) presents and controls a subset of user-centred features, rather than administrator-level tasks.

Webmin includes _116_ [standard modules](https://doxfer.webmin.com/Webmin/Webmin_Modules), and there are at least as many third-party modules.

### Requirements
Perl 5.10 or higher.

## Install
Webmin can be installed in two different ways:

 1. By downloading a pre-built package, available for different distributions (CentOS, Fedora, SuSE, Mandriva, Debian, Ubuntu, Solaris and [other](http://www.webmin.com/support.html)) from our [download page](http://webmin.com/download.html);
  <kbd>Note: It is highly recommended to [add repository](https://doxfer.webmin.com/Webmin/Installation) to your system for having automatic updates.</kbd>

 2. By downloading, extracting [source file](https://prdownloads.sourceforge.net/webadmin/webmin-1.910.tar.gz), and running [_setup.sh_](http://www.webmin.com/tgz.html) script, with no arguments, which will setup to run it directly from this directory, or with a command-line argument, such as targeted directory.
  <kbd>Note: If you are installing Webmin [on Windows](http://www.webmin.com/windows.html) system, you must run the command `perl setup.pl` instead. The Windows version depends on several programs, and modules that may not be part of the standard distribution. You will need _process.exe_ commmand, _sc.exe_ command, and _Win32::Daemon_ Perl module.</kbd>

## Development

### Lead developer

* [Jamie Cameron](http://www.webmin.com/about.html) [![](https://rostovtsev.io/pub/media/icons/linkedin-15x15.png)](https://www.linkedin.com/in/jamiecameron2)

### Contributors

* [Joe Cooper](https://github.com/swelljoe)
* [Ilia Rostovtsev](https://github.com/rostovtsev)
* [Kay Marquardt](https://github.com/gnadelwartz)
* [Nawawi Jamili](https://github.com/nawawi)

## License

Webmin is released under the [BSD License](https://github.com/webmin/webmin/blob/master/LICENSE).
