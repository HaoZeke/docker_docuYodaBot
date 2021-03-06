# docuYoda Dockerfile
> Copyright (C) 2017  Rohit Goswami (HaoZeke) <rohit.goswami@aol.com>

Initially built for use with the [docuYoda starter](github.com/HaoZeke/docuYoda_starter), it can also work well for any minimal pandoc TeX usage.

## Features

* Based on ArchLinux
* AUR support through yaourt
* Non Root execution
* Includes full TeX support
* Latest pandoc
* Has yarn
* Includes `pp`

## Usage

The recommended usage leverages your existing project folder so you only need this as your build environment.

```bash
docker run -it -h docuyodabot -v $SOURCE_LOCATION:/home/docuyoda/Report -v $HOME.cache/:/home/docuyoda/.cache HaoZeke/docuyodabot
```