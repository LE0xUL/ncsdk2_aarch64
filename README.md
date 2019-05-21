# Intel® Movidius™ Neural Compute SDK

> This README is a modified version of the original NCSDK repo
> Modified to install on rock64 (aarch64 with debian 9)

This Intel® Movidius™ Neural Compute software developer kit (NCSDK2) is provided for users of the [Intel® Movidius™ Neural Compute Stick](https://developer.movidius.com/) (Intel® Movidius™ NCS). It includes software tools, an API, and examples, so developers can create software that takes advantage of the accelerated neural network capability provided by the Intel Movidius NCS hardware.

# Original Neural Compute SDK2 Repository
## [https://github.com/movidius/ncsdk/tree/ncsdk2](https://github.com/movidius/ncsdk/tree/ncsdk2)

-------

To install this NCSDK 2.x you can use the following command to clone the ncsdk2_aarch64 branch
```bash
git clone -b aarch64 git@github.com:trecetp/ncsdk2_aarch64.git
```
# Installation
The provided Makefile helps with installation. Clone this repository and then run the following command to install the NCSDK2:

```
cd ncsdk2_aarch64
make install
make api
```

# Examples
The Neural Compute SDK also includes examples. After cloning and running 'make install' and 'make api' run the following command to install the examples:
```
make examples
```

## NCAPPZOO Examples
For additional examples, please see the Neural Compute App Zoo available at [http://www.github.com/movidius/ncappzoo](http://www.github.com/movidius/ncappzoo). The ncappzoo is a valuable resource for NCS users and includes community developed applications and neural networks for the NCS.

# Documentation
The complete Intel Movidius Neural Compute SDK documentation can be viewed at [https://movidius.github.io/ncsdk/](https://movidius.github.io/ncsdk/)

# Getting Started Video
For installation and general instructions to get started with the NCSDK, take a look at this [video](https://www.youtube.com/watch?v=fESFVNcQVVA)

# Troubleshooting and Tech Support
Be sure to check the [NCS Troubleshooting Guide](https://ncsforum.movidius.com/discussion/370/intel-ncs-troubleshooting-help-and-guidelines#latest) if you run into any issues with the NCS or NCSDK.

Also for general tech support issues the [NCS User Forum](https://developer.movidius.com/forums) is recommended and contains community discussions on many issues and resolutions.