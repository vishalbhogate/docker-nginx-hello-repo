# docker-nginx-hello 

Docker image containing DNX ngnix Hello webpage

## Usage

### Build Locally

If you want to build and use your own local image

```bash
# build image locally
$ make build
# go inside the container
$ make shell
```

## Update Docker image

1. Change (or not) `VERSION` in `Makefile`
2. Build and test locally
3. Commit and push the changes
4. Tag the commit with the command `make gitTag`
5. Go to [hub.docker.com](hub.docker.com)
6. In `Build Details` tab, you should now see the new tag kicking off

Docker image
------------

The Docker image has the following:

- Alpine
- ngnix