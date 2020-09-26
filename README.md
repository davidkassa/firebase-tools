# firebase-tools
[![](https://images.microbadger.com/badges/image/davidkassa/firebase-tools.svg)](https://microbadger.com/images/davidkassa/firebase-tools "Get your own image badge on microbadger.com") [![](https://images.microbadger.com/badges/commit/davidkassa/firebase-tools.svg)](https://microbadger.com/images/davidkassa/firebase-tools "Get your own commit badge on microbadger.com") [![Build Status](https://travis-ci.com/davidkassa/firebase-tools.svg?branch=main)](https://travis-ci.com/davidkassa/firebase-tools)

Auto-updating [Docker](https://www.docker.com/) image based on [NodeJS](https://nodejs.org) official image with [Firebase Tools](https://firebase.google.com/docs/hosting/quickstart) installed.

This image should be rebuilt automatically anytime there is an update to the [node](https://hub.docker.com/_/node/) docker container through a repository link and anytime there is a [firebase-tools](https://www.npmjs.com/package/firebase-tools) update in NPM via webhooks through [libraries.io](https://libraries.io). This can sometimes be unstable, but usually works.

Can be pulled from [Docker Hub](https://hub.docker.com/r/davidkassa/firebase-tools/) 
```docker
docker pull davidkassa/firebase-tools
```
