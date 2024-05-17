# PIRVision Lens Terminal

This repository contains a Web App that allows an end user to
communicate with PIRVision Lens Development Board connected serial port through an interactive
terminal. This app utlizes the [Serial API] (https://wicg.github.io/serial/) to establish communication.

## Privacy

This application is served statically and is cached for offline use. No
analytics are collected. All communication with the serial device happens
locally.

## Building

This project is written in TypeScript and uses npm and Vite to manage
dependencies and automate the build process. To get started clone the
repository and install dependencies by running,

```sh
npm install
```

To create a production build in the `dist` folder run,

```sh
npm run build
```

To start a local development server run,

```sh
npm run dev
```
