# Pastebot

Bot for receiving pastes

[![CI](../../actions/workflows/CI.yml/badge.svg)](../../actions/workflows/CI.yml)
[![CD](../../actions/workflows/CD.yml/badge.svg)](../../actions/workflows/CD.yml)

## Contents
1. [Installation](#installation)
    - [Docker](#docker)
    - [Github](#github)
        1. [Clone](#clone)
        2. [Dependencies](#install-dependencies)
2. [Run](#run)
    - [NPM](#npm-1)
    - [Docker](#docker-1)

## Installation

### Docker
```shell
docker pull trard/pastebot
```

### Github

#### Clone
```shell
git clone https://github.com/trard/pastebot.git
```

#### Install Dependencies
```shell
npm i --only=prod
```

## Run

### NPM
```shell
npm run start
```

### Docker
```shell
docker run trard/pastebot
```
