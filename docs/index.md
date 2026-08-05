# Introduction
This documentation (mostly written in a kind of *blog* style) is a rough sketch of how my homelab works, explaining most of the different stages it went through with some of my failed attempts as well. It is by **no means** an extensive guide on how to achieve my setup, rather, it serves as a blog with some troubleshooting included (and also mistakes to avoid) of my experience going down the homelab route. I hope you enjoy it!

## Summary
My personal homelab consists of 2 systems, one of them located in my house and the other located on a remote VPS. Both are important and serve different purposes that will be explained throughout this documentation. 

## Systems
### Local system
The server I daily drive in my house is a Rockchip SoC, more specifically an **Orange PI 5B** 16GB model. I managed to obtain this second-hand from a friend and I really like its low energy consumption and non-existant noise (more on that later). 

!!! warning
    This system is not exposed to the internet.

### Remote system
My remote system consists of a **VPS** I pay for every month. It's a simple QEMU virtual machine consisting of 6 cores and 12GB of memory. By personal choice I will not disclose information about the prices I pay or about my provider. 

## Domains
I own 2 domains that I use for my selfhosted setup:

- `sprinter.work`
- `sprintervps.party`

By personal choice I will not disclose information about my domain provider or the prices I pay.

## Software
Both of my systems run a Linux based distribution and all services run under [Docker Engine](https://docs.docker.com/engine/) (there are very few exceptions).
