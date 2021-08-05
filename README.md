## Build an Ubuntu Toolbox

Build an Ubuntu image suitable for use in toolbox, for systems such as Fedora Silverblue.

### Usage

1. Edit script to to set RELEASE and DISTRO to desired release/animal name.
1. `./build-ubuntu-toolbox`
1. `toolbox enter focal` to enter your new Ubuntu toolbox.

Original credit to Martin Pitt, who explained this workflow [in this blogpost](https://piware.de/post/2020-12-13-ostree-sway/).

### References

- [Original Script](https://piware.de/gitweb/?p=bin.git;a=summary)
- [Toolbox GitHub Repo](https://github.com/containers/toolbox)
- [Toolbox Documentation](https://docs.fedoraproject.org/en-US/fedora-silverblue/toolbox/)
