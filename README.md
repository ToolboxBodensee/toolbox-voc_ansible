 Video Streaming - Ansible Setup
====================================
Ansible Setup for the VOC *(Video Operation Center)* from the [Toolbox Bodensee e.V.](https://toolbox-bodensee.de).

Ansible is a radically simple IT automation engine that automates cloud provisioning, configuration management, application deployment, intra-service orchestration, and many other IT needs. [Weitere Infos](https://de.wikipedia.org/wiki/Ansible) | [Learn more](https://www.ansible.com/overview/how-ansible-works)

 Usage:
-------
This git repository contains git submodules. To see our complete setup you have to clone them too!
You need [git-lfs](https://git-lfs.github.com/) to clone all parts of this repository!

```
# Clone the Git with submodules
git clone --recursive https://github.com/ToolboxBodensee/toolbox-voc_ansible.git
git submodule update --init --recursive
```


 Playbooks:
------------
+ ``streaming_setup.yml``: Setup voctocore ans obs on video encoder pc.

 Setup
-------

We will say how we build our streaming setup in the wiki at [tbbs.me/doku.php?id=streaming](https://tbbs.me/doku.php?id=streaming:start).
We also have an short overview with what Hardware is how connected in this git.

![connect.svg](connect.svg "Toolbox VOC")


 Hardware we use:
----------------

+ Encoder PC:
  * Gaming Tower PC ``(from L3D)``
    - Graphic Card: ``Radeon HD 5850`` [Info](https://www.gamestar.de/hardware/amd-radeon-hd-5850,79.html)
    - CPU: i7 Quadcore ``(from L3D)``
  - RAM: 16GB DDR3 ``(from L3D``
  - SSD: 250GB ``(from L3D)``
* Video Capture: ``Blackmagic Decklink Duo 2`` [Info](https://www.blackmagicdesign.com/de/products/decklink/techspecs/W-DLK-31)
  - 4x SDI Stream ``(Up to 1080p@60)``
  
+ Camera:
  * 2x Panasonic ``HC X909`` [Infos](https://www.testberichte.de/p/panasonic-tests/hc-x909-testbericht.html#produkt-datenblatt) ``(from L3D)``
    - MicroHDMI - HDMI Kabel
    - Blackmagic HDMI to SDI Adapter [Infos](https://www.blackmagicdesign.com/de/products/microconverters)
    - SDI Cable ``(BNC mit 75Ohm)``
  * HD-Camecorder ``(from ottojo)``
    - MicroHDMI - HDMI Kabel
    - SDI Cable ``(BNC mit 75Ohm)``
    - HDMI to SDI Adapter (missing)

+ Slides/Speaker
  * HDMI to 2x SDI Adapter (missing)
  * 2x SDI Cable ``(BNC mit 75Ohm)`` (missing)
  * SDI to HDMI Adapter for Beamer Input (missing)

+ Audio
  * Some XLR Cables
  * Mixer
    - Mischpult: ``the t.mix xmix 1202 FX USB`` [Info](https://www.thomann.de/de/the_t.mix_xmix_1202_fx_usb.htm)
    - USB Interface for PC-Input (OBS) and room-sound: ``Behringer U-Phoria UMC202HD B-Stock`` [Info](https://www.thomann.de/de/behringer_u_phoria_umc202hd_b_stock.htm)
    - Audio nach SDI: ``Blackmagic SDI-audio injector`` [Info](https://www.videodata.de/shop/products/de/Studiotechnik/Signalkonvertierung/Analog-Audio-zu-HD-SDI/Blackmagic-Minikonverter-Audio-zu-SDI-2.html)
  * Microfones
    - Headset: ``LD Systems LDWS100MH1`` [Info](https://www.thomann.de/de/ld_systems_ldws100mh1.htm)
      + Mini-XLR to XLR Adapter (with POE): ``AKG MPA VL Male`` [info](https://www.thomann.de/de/akg_mpa_vl_male.htm)
    - Video Mic (backup): ``Rode VideoMic GO`` [Info](https://www.thomann.de/de/rode_videomic_go.htm)
    - some XLR Microphones
    - wireless-hand-microphone


 
