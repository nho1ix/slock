# slock - simple screen locker <img alt="Visits" align="right" src="https://badges.pufler.dev/visits/nho1ix/slock"/>

simple screen locker utility for X. 

![slock](https://i.imgur.com/2R315sM.gif)

## Requirements

In order to build slock you need the Xlib header files.

## Installation

Edit config.mk to match your local setup (slock is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install slock
(if necessary as root):

```sh
make clean install
```

## Running slock

Simply invoke the 'slock' command. To get out of it, enter your password.
