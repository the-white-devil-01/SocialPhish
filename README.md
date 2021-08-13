# AccountPhish
<!-- AccountPhish -->


<p align="center">
  <img src="https://img.shields.io/badge/Version-2.1-green?style=for-the-badge">
  <img src="https://img.shields.io/github/license/whitedevil/AccountPhish?style=for-the-badge">

<p align="center">A beginners friendly, Automated phishing tool with 30+ templates.</p>

##

### Features

- Latest and updated login pages.
- PhishMask support 
- Beginners friendly
- Docker support (checkout `docker-legacy` branch)
- Multiple tunneling options
  - Localhost
  - Ngrok (With or without hotspot)


### Installation

- Just, Clone this repository -
```
$ git clone https://github.com/thewhitedevil/AccountPhish.git
```

- Change to cloned directory and run `AccountPhish.sh` -
```
$ cd AccountPhish
$ bash AccountPhish.sh
```

- On first launch, It'll install the dependencies and that's it. `SocialPhish` is installed.

### Run on Docker
```
$ docker pull whitedevil/AccountPhish
$ docker run --rm -it whitedevil/AccountPhish
```

### Dependencies

**`SocialPhish`** requires following programs to run properly - 
- `php`
- `wget`
- `curl`
- `git`

> All the dependencies will be installed automatically when you run `AccountPhish` for the first time.

> Supported Platform : **`Termux`**, **`Ubuntu/Debian/Kali`**, **`Arch Linux/Manjaro`**, **`Fedora`**
