[![Maintenance Status][maintenance-image]](#maintenance-status)

# Spectacle Boilerplate

## Contents

- [Reference](#reference)
- [Getting Started](#getting-started)
- [Tutorial](#tutorial)
- [Build & Deployment](#build-deployment)

## Reference

The Spectacle core API is available in the [Spectacle Docs](https://github.com/FormidableLabs/spectacle/blob/master/README.md).

## Getting Started

1. Download the presentation

   ```sh
   git clone git@bitbucket.org:i-dbps/idbps-presentation.git
   ```

2. Create branch

   ```sh
   git checkout -b sheets/<sheet_subject>
   ```


3. Install dependencies

   ```sh
   yarn install
   ```

4. Start the webpack server. The server will run at [`localhost:3000`](http://localhost:3000).

   ```sh
   yarn start
   ```

## Tutorial

A basic tutorial is available [here](https://github.com/FormidableLabs/spectacle/blob/master/docs/tutorial.md).

## Build & Deployment

Building the dist version of the project is as easy as running

```sh
yarn build
```

If you want to deploy the slideshow to surge, run

```sh
yarn deploy
```