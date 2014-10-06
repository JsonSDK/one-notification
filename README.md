JsonSDK - Notification
======================

This is a ready to go notification module which provide email sending service as an API.

## Features

- Email Notification API (port: 8080)
- Administration UI (port: 8090)
- Configurable Email Template
- Out-of-box integrated with Mailgun, Mandrill and SMTP

## Pre-requisites
- Docker [1.2.x](https://docs.docker.com/#installation-guides) installed

## Usage

```bash
docker run --rm -d -p 8080:8080 8090:8090 -v ~/jsonsdk/notification:/data jsonsdk/one-notification:latest
```

## Development

```bash
git clone git@github.com:jsonsdk/one-notification.git
cd one-notification
fig up
```
