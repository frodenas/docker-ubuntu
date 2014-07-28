# Ubuntu Dockerfile

A Dockerfile that produces a Docker Image for [Ubuntu](http://www.ubuntu.com/).

## Usage

### Build the image

To create the image `frodenas/ubuntu`, execute the following command on the `docker-ubuntu` folder:

```
$ docker build -t frodenas/ubuntu .
```

### Run the image

To run the image:

```
$ docker run -ti --rm --name ubuntu  frodenas/ubuntu
```

## Copyright

Copyright (c) 2014 Ferran Rodenas. See [LICENSE](https://github.com/frodenas/docker-ubuntu/blob/master/LICENSE) for details.
