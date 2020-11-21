# Falco missing syscalls

Every 15 minutes, this repository gets the current release Falco
and compares it to the current [linux-next](https://www.kernel.org/doc/man-pages/linux-next.html)
repository to render a diff of the current syscalls not supported by Falco.

This is useful to visualize the delta of syscalls that Falco does not support
while the kernel is updated.
