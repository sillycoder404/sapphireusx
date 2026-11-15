# SapphireUSX

SapphireUSX is a crew-wellness interface prototype. The React and TypeScript
application in `frontend/` is the primary version. A separate static HTML
implementation remains at the repository root as an alternative demo.

## Public preview

The GitHub Pages site publishes only the React application:
https://sillycoder404.github.io/sapphireusx/. The root-level static demo is
not included in the deployed site.

## Run the React app

Requires Node.js and npm.

```sh
cd frontend
npm ci
npm run dev
```

For a production build and lint check:

```sh
npm run build
npm run lint
```

## Data and prototype notice

All displayed health readings, timestamps, and alert examples are synthetic
illustrations. They are not live measurements, are not connected to NASA OSDR
study OSD-575, and are not for health monitoring, diagnosis, or treatment
decisions. OSD-575 is listed only as a separate research dataset reference.
SapphireUSX is not an official NASA product.
