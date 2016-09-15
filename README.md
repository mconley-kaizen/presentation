# How I Use Docker for Data Science
## Developing Models for Deployment

### Prerequisites
Ensure that you have a working version of `docker` on your machine.  Installation instructions for all major platforms can be found on the [docker](https://www.docker.com/products/overview#/install_the_platform) website.

You should be able to execute `docker --version` and see something like `Docker version 1.10.3, build 20f81dd` 

If you are on linux, installation is very straight forward as `docker` takes advantage of the host's native kernel

If you are on Mac or Windows, you will need to use the `docker-machine` tools provided in the installation to run `docker` on a virtual machine.  This is a somewhat seamless, just follow the [tutorials](https://www.docker.com/products/overview#/install_the_platform)


### Play with it
Take a look at the [Hello World](https://docs.docker.com/engine/tutorials/dockerizing/) tutorial on [docker.com](https://docs.docker.com/engine/tutorials/dockerizing/)

See what `docker ps`, `docker logs`, and `docker stop` do...


### Development

You can view the presentation in [Notes.ipynb](https://github.com/mconley-kaizen/presentation/blob/master/Notes.ipynb)

We'll be using the repos:
* [webapp](https://github.com/mconley-kaizen/webapp)
* [dockerapp](https://github.com/mconley-kaizen/docker_app)
* [iris_prediction](https://github.com/mconley-kaizen/iris_prediction)
* [deploy](https://github.com/mconley-kaizen/deploy)

Don't worry too much about what is in these repos just yet, but some familiarity will help.
