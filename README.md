### Description

This repo is a recreation of `PulseEightPlus.egplugin` (version `0.4.11b`) from [this](https://reddit.com/r/htpc/comments/rkspso/hdmi_cec_with_pc/hpcvl8d/) Reddit post [[archive](https://web.archive.org/web/20240922223342/https://old.reddit.com/r/htpc/comments/rkspso/hdmi_cec_with_pc/hpcvl8d/)].

See [./egplugin/README.md](./egplugin/README.md) for more info.


### Install

Below are the instructions for configuring your PC with a Pulse Eight CEC adapter.

1) Buy the [Pulse Eight CEC adapter](https://www.pulse-eight.com/p/104/usb-hdmi-cec-adapter)
1) Install [libCEC](https://github.com/Pulse-Eight/libcec/releases)
    1) The latest version at the time of writing is `6.0.2`
    1) (Don't install the included EventGhost plugin; it's for an older version of EventGhost and will only cause you pain)
1) Install [EventGhost](https://github.com/EventGhost/EventGhost/releases)
    1) The latest version at the time of writing is `v0.5.0-rc6`
1) Download `PulseEightPlus.egplugin` from [here](https://github.com/sam-6174/pulse-eight-egplugin/releases)
    1) Double-click `PulseEightPlus.egplugin` to install the plugin into EventGhost
1) Open EventGhost
    1) Click `Configuration` > `Add Plugin`
    1) Select `Pulse-Eight CEC+` and click `OK`
    1) Configure the CEC adapter to your liking
        1) If you're connected to an AVR then you may need to play around with the `Adapter Connected To` choices for input switching to work correctly
    1) Click `Apply`

The above will get basic HDMI CEC working where you can now see the HDMI input and switch to it.

For advanced configuration, such as handling power on/off, please feel free to open a PR documenting those steps ☺
