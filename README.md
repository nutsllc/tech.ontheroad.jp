# tech.ontheroad.jp

This repository contains site files( html, css, javascript, etc) for https://tech.ontheroad.jp

## Getting Started

### STEP1: Clone this repository

```bash
$ git clone https://github.com/nutsllc/tech.ontheroad.jp.git
```

### STEP2: Copy and Edit .env file

```bash
$ cd tech.ontheroad.jp
$ cp .env.sample .env
$ vi .env

REPO_URL=https://github.com/vendor/example-repo

TOYBOX_GID=1000
TOYBOX_UID=1000
URL=www.example.com
EMAIL=dev@example.com
```

### STEP3: Run init script

```bash
$ cd tech.ontheroad.jp
$ sh bin/init
```

### STEP4: Run deploy script

```bash
$ cd tech.ontheroad.jp
$ sh bin/deploy
```
Open ``https://tech.ontheroad.jp`` on your browser.

enjyoy :-)
