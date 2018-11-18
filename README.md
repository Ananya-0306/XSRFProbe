<h1 align="center">
  <br>
  <a href="https://github.com/0xinfection"><img src="https://i.imgur.com/NnHAZx2.png" alt="XSRFProbe"></a>
</h1>

<p align="center">  
  <a href="https://docs.python.org/3/download.html">
    <img src="https://img.shields.io/badge/Python-3.x-green.svg">
  </a>
  <a href="https://github.com/0xinfection/XSRFProbe/releases">
    <img src="https://img.shields.io/badge/Version-v1.1.0-blue.svg">
  </a>
  <a href="https://github.com/0xinfection/XSRFProbe/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-GPLv3-orange.svg">
  </a> 
  <a href="https://travis-ci.org/0xInfection/XSRFProbe">
    <img src="https://travis-ci.org/0xInfection/XSRFProbe.svg?branch=master">
  </a>
</p>

### About XSRFProbe
__XSRFProbe__ is an advanced Cross Site Request Forgery Audit Toolkit equipped with Powerful Crawling Engine and Token Generation Capabilities. It has well-capable built in modules which can hunt out CSRF vulnerabilities. For more info on how XSRFProbe works, see [XSRFProbe Internals](https://github.com/0xInfection/XSRFProbe/wiki#xsrfprobe-internals) on [wiki](https://github.com/0xInfection/XSRFProbe/wiki/).

<img src="https://i.imgur.com/xYKpsYl.png" alt="xsrf-logo">
<p align="center">
  <a href="https://github.com/0xinfection/xsrfprobe/wiki">XSRFProbe Wiki</a> •
  <a href="https://github.com/0xinfection/xsrfprobe/wiki/Getting-Started">Getting Started</a> •
  <a href="https://github.com/0xinfection/xsrfprobe/wiki/General-Usage">General Usage</a> •
  <a href="https://github.com/0xinfection/xsrfprobe/wiki/Advanced-Usage">Advanced Usage</a> •
  <a href="https://github.com/0xinfection/xsrfprobe/wiki/XSRFProbe-Internals">XSRFProbe Internals</a> •
  <a href="https://github.com/0xinfection/xsrfprobe#gallery">Gallery</a>
</p>


### Some Features:

- [x] Has a powerful crawler which features continuous crawling and scanning.
- [x] The user is in [control of everything](https://github.com/0xInfection/XSRFProbe/wiki/Advanced-Usage#xsrfprobe-configuration-variables) that the scanner does.
- [x] Can detect several types of Anti-CSRF tokens in requests.
- [x] Out of the box support for custom cookie values and generic headers.
- [x] Can intelligently generate crafted tokens for different types of parameters.
- [x] Submits forms in the normal values as well as with crafted token.
- [x] Follows a redirect when there is a 302 response.
- [x] Has a user-friendly interaction environment.
- [x] Everything is automated on demand.

### Warnings:

Do not use this tool on a live site!

It is because this tool is designed to perform all kinds of form submissions automatically which can sabotage the site. Sometimes you may screw up the database and most probably perform a DoS on the site as well.

Test on a disposable setup/test site!

### Drawbacks:
The scanner has the following drawbacks presently:
- Normally the scanner assumes that every form has a hidden/visible parameter and token field.
- Changing or removing that token field usually causes a 403 Forbidden response.
- There are chances of false positives during scanning for POST-Based Request Forgeries.

### Gallery:
Lets see some real-world scenarios of XSRFProbe in action:

<img src="https://i.imgur.com/VPgdwI1.png" width=50%></img><img src="https://i.imgur.com/XQxwKHS.png" width=50%></img>
<img src="https://i.imgur.com/wSWFdZG.png" width=50%></img><img src="https://i.imgur.com/4TCrza9.png" width=50%></img>

### Version:
```
v2.0.0
```

### Disclaimer:
Usage of XSRFProbe for testing websites without prior mutual consistency can be considered as an illegal activity. It is the final user's responsibility to obey all applicable local, state and federal laws. The author assumes no liability and is not exclusively responsible for any misuse or damage caused by this program.

### To Do's:
- include 
- Associate multithreading for the better.
- Include methods for detecting blind CSRF. 

Thats it folks! Thank you...

> Copyright © [The Infected Drake](https://www.twitter.com/0xInfection)
