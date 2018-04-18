# Description

Docker image for [truffle framework](http://truffleframework.com/)

## Usage

```` sh
docker run --rm -ti \
    --workdir "/code" \
    -v "${PWD}:/code" \
    mathieubrun/truffle:latest --help
````