# Docker Images

This repository includes all of the Docker containers that I conjure up / half-ways maintain. Wherever possible, I base the image off of known-good containers, such as dockerfile/\*, ubuntu/\*, debian/\*, or phusion/baseimage. The images have a "latest" tag and at least one version tag. And, I will try to check in periodically with versions to add tags for new versions.

# Contributing

All contributions are welcome; and, I am not offended by unsolicited pull requests, though an message first is nice.

# Always Find Info in /etc/Dockerfile

In case the image gets flattened or built from source, all Dockerfiles are added to the image at /etc/Dockerfile (This is the result of a off-hand comment from a Redditor about how s\he couldn't discern what was installed in a container).

# Shameless Plug

I am a self-taught developer and appreciate any comments or replies either on my website [niaquinto.com](http://niaquinto.com) or on twitter [@nickiaq](http://twitter.com/nickiaq). Currently, I'm working at [The American Institute for Contemporary German Studies](http://aicgs.org) as the Communication Coordinator and have found web/software development very useful in creating/maintaining our large-ish WordPress website and few internal apps, written in python (flask, eve, and custom cli's) and PHP (wordpress and laravel).
