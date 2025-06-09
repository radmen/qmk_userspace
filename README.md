# Halcyon Corne userspace

This is my private userspace with config for the [Halcyon Corne keyboard](https://splitkb.com/products/halcyon-corne?_pos=2&_sid=b2f49e295&_ss=r).  
The left split has a TFT display, where the right one Cirque Trackapd. I'm using qmk-vial.

I'm not very good with QMK and lots of things are monkey-patched. Config is highly experimental (for me) and might contain some nasty stuff.

## Setup

1. Install QMK
1. Install the firmware:
    ```bash
    qmk setup -b halcyon splitkb/vial-qmk
    ```
1. Clone the repository:
    ```bash
    git clone git@github.com:radmen/qmk_userspace.git ~/qmk_userspace
    cd ~/qmk_userspace/
    git submodule update --init
    ```
1. Compile the sources:
    ```bash
    qmk userspace-compile
    ```
