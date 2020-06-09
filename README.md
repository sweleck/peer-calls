# UTAL

Based on https://github.com/peer-calls/peer-calls

Project to simply connect people
https://utal.ch

Work in progress.

# Requirements

 - [Node.js 8][node], or
 - [Node.js 12][node], or
 - [Docker][docker]

[node]: https://nodejs.org
[docker]: https://www.docker.com/

# Stack

 - Express
 - Socket.IO
 - React
 - Redux
 - TypeScript (since peer-calls `v2.1.0`)

# Installation & Running

## Using npx (from NPM)

```bash
npx utal
```

## From Git Source

```bash
git clone https://github.com/sweleck/utal.git
cd utal
npm install

# for production
npm run build
npm start

# for development
npm run start:watch
```

## Building Docker Image

```bash
git clone  https://github.com/sweleck/utal.git
cd utal
docker build -t utal .
docker run --rm -it -p 3000:3000 utal:latest
```

# License

[MIT](LICENSE)
