# Axellers quickstart

This repository accompanies Axellers quickstart guide. This app is built on React and uses the react-rutter-link library.

## 1. Clone the repository
```
$ git clone https://github.com/axellers/react-quickstart
$ cd react-quickstart
```

## 2. Set up your environment variables

```
$ cp .env.example .env.local
```

Copy `.env.example` to a new file called `.env.local` and fill out the environment variables inside.`AXELLERS_CLIENT_ID`, `AXELLERS_SECRET` must be filled out. Get your Client ID and secrets from
the dashboard: https://dashboard.axellers.io

## 3. Run the quickstart

Install required node modules:
```
$ yarn
```

Run the Quickstart:
```
$ yarn dev