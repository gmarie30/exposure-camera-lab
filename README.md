# Exposure — Grace’s Interactive Camera Lab
A Canon EOS-inspired photography playground featuring five original photographs by Grace Costello.

Choose a photograph, adjust aperture, shutter speed and ISO, click to set a focus point, then press the shutter to save and download your experiment. Portrait photos retain their original composition. The original settings button restores unmodified photo brightness. Captures remain in memory until refresh.

## Run locally
Open `dist/index.html` with a local web server, for example `python3 -m http.server 8000 --bind 127.0.0.1 --directory dist`.

## Hosting
The public GitHub repository serves these static site files from its main branch. In repository Settings → Pages, select Deploy from a branch, main, and / (root). The local workspace keeps these files in dist; an optional Actions workflow can deploy that directory instead.

## About the effects
This reinterprets existing photographs with simulated exposure, focus blur, motion trails and ISO grain. It cannot change the original capture settings or recover missing detail. Camera readouts describe the simulated controls, not the photographs’ EXIF metadata.

Independent educational project. Not affiliated with Canon. Original photographs © Grace Costello. All rights reserved for photography.
