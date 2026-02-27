# cctv001

Capture motion events and still images from Hikvision IP cameras.

## Overview

A Node.js application that connects to Hikvision IP cameras via their API to detect motion events and capture still images. Images are stored in Google Cloud Storage.

## Dependencies

- [node-hikvision-api](https://github.com/ragingcomputer/node-hikvision-api) for camera communication
- Google Cloud Storage for image storage

## Setup

```bash
npm install
```

Configure your Hikvision camera connection details and GCS credentials before running.
