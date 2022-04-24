# Base Docker Installation

## About
Given I'm learning about Docker, I'll need to install/set up a basic image to
work from. It's being done on a lab machine, so I will want to be able to treat it
like livestock and recover when one has to be put down. So, an Ansible Role it is.

This will end up on either an Raspberry Pi or an old desktop with Ubuntu, so apt
based things will predominate, but I do strive for adaptability and extension in
my roles and this will reflect that.

## Steps
1. Clean up, if old packages are here.
1. Add Docker's repositories.
1. Install from repositories.
1. Post-installation configuration.

## Notes

## Links
[Offical Docs for Ubuntu](https://docs.docker.com/engine/install/ubuntu/)
