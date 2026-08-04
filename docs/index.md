# Introduction
My personal homelab consists of 2 systems, one of them located in my house and the other located on a remote VPS. Both are important and serve different purposes that will be explained throughout this documentation. This is **not** an exhaustive guide on how to replicate my setup, it is simply a rough explanation on how everything operates so that other people can take inspiration.

## Systems
### Local system
The server I daily drive in my house is a Rockchip SoC, more specifically an **Orange PI 5B** 16GB model. I managed to obtain this second-hand from a friend and I really like its low energy consumption and non-existant noise (more on that later). 

!!! warning
    This system is not exposed to the internet.

### Remote system
My remote system consists of a VPS I pay for every month. It's a simple QEMU virtual machine consisting of 6 cores and 12GB of memory. By personal choice I will not disclose information about the prices I pay or about my provider. 

## Domains
I own 2 domains that I use for my selfhosted setup:

- `sprinter.work`
- `sprintervps.party`

By personal choice I will not disclose information about my domain provider or the prices I pay.

## Software
Both of my systems run a Linux based distribution and all services run under [Docker Engine](https://docs.docker.com/engine/) (there are very few exceptions).
