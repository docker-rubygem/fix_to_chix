[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/fix_to_chix.svg)](https://hub.docker.com/r/rubygem/fix_to_chix/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/fix_to_chix.svg)](https://hub.docker.com/r/rubygem/fix_to_chix/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/fix_to_chix.svg)](https://hub.docker.com/r/rubygem/fix_to_chix/)
[![Gem Downloads](https://img.shields.io/gem/dt/fix_to_chix.svg)](https://rubygems.org/gems/fix_to_chix/)
# fix_to_chix

Auto-Generated Docker image for fix_to_chix to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/fix_to_chix`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/fix_to_chix`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/fix_to_chix`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/fix_to_chix/)
