# Place42-Docker

This is the [Place42 autoplacer](https://github.com/Nimon77/Userscript) wrapped in a Docker container with Firefox and Tampermonkey.

If you have never used Docker, please use the [official userscript](https://github.com/Nimon77/Userscript), not this docker version. This repo isn't for the average user.

## Setup

1. Download this repo.
1. Run `docker compose up -d`. You might have to use `sudo` for this.
1. Open http://localhost:5800.
1. Wait a couple seconds, until tampermonkey pops up with a install button.
1. Click that button -_-
1. Open the already-opened reddit tab, and log in.
1. Navigate to the r/place canvas.

This should be it.

## System requirements

CPU: One that's compatible with one of those CPU architectures:

* linux/amd64
* linux/arm64
* linux/arm/v7
* linux/386

RAM: Between 600 and 800 mb of RAM free. Firefox uses a lot of memory.  
Storage: 1GB of free space should be more than enough.  
