# Node.js + exiftool + ffmpeg + graphicsmagick
FROM thumbsupgallery/runtime:alpine

# Standard build dependencies for <npm install>
RUN apk add --no-cache git make g++ python bash

# Pre-install expensive dependencies
WORKDIR /app
RUN npm init -y
RUN npm install better-sqlite3
