class: top, center


## Current status of
# Docker on Windows

.invisible[#
#

#

#

#

#

]

Stefan Scherer

@stefscherer

25.02.2016

---

background-image: url(https://raw.githubusercontent.com/raspberrypilearning/getting-started-with-raspberry-pi-lesson/master/images/Raspberry_Pi_B+.png)

# Who am I?

* Software Engineer at SEAL Systems

* Chocolatey package maintainer

* Docker Pirate

.invisible[#
#

#

#

#

]

* Stefan Scherer
* @stefscherer
* github.com/StefanScherer

---

# Windows Containers

* What?

* Why?

* How?

---

# Windows Containers

## Namespaces

* Registry

* Process IDs

* File System

* Networking

---

background-image: url(windows_container_host.png)

# System Architecture

---

# System Architecture

* Windows Server 2016

* Container Feature

* Hyper-V Role
  * optional

* Base images

* Docker Engine

---

# Container types

## Windows Server Containers
  * use same Windows kernel
  * lightweight, faster

## Hyper-V Containers
  * running in Hyper-V
  * better isolation
  * `docker run --isolation=hyperv`

---

# Base images

## Windows Server Core
  * nearly full Win32 compatible
  * about 9 GByte

## Nano Server
  * fast to boot
  * software may need porting
  * about 700 MByte

## ~~FROM scratch~~


---

# Demo time!

---

class: left

.invisible[#

#

]

# Thank you!


.invisible[#

#

]

## Stefan Scherer
### @stefscherer
### scherer_stefan@icloud.com
### github.com/StefanScherer

.invisible[#

]
