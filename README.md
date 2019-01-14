 Video Streaming - Ansible Setup
====================================
Ansible Setup for the VOC *(Video Operation Center)* from the [Toolbox Bodensee e.V.](https://toolbox-bodensee.de).

Ansible is a radically simple IT automation engine that automates cloud provisioning, configuration management, application deployment, intra-service orchestration, and many other IT needs. [Weitere Infos](https://de.wikipedia.org/wiki/Ansible) | [Learn more](https://www.ansible.com/overview/how-ansible-works)

 Usage:
-------
This git repository contains git submodules. To see our complete setup you have to clone them too!
```
# Clone the Git
git clone https://github.com/ToolboxBodensee/toolbox-voc_ansible.git

# Clone the Submodules 
cd ansible
git submodule update --init --recursive
```


 Playbooks:
------------
+ ``streaming_setup.yml``: Setup voctocore on video encoder pc.

 Setup
-------

### What Hardware do we have?

| Place    | Hardware | Function | Owner |
| -------- | ---------| -------- | ----- |
| streaming.tbbs.me | Tower-PC       | main computer to mix, encode, record and stream talks | Toolbox (gift from Michi K.) |
| streaming.tbbs.me | Decklink Duo 2 | PCI SDI-IN Card for live revording | L3D (soon Toolbox) |
| streaming.tbbs.me | Radeon HD 5850 | Graphic Card | Toolbox (gift from L3D) |
| streaming.tbbs.me | SSD with 250G  | fast Storage for OS and daily videos | L3D |
| | 2x blackmagic HDMI -> SDI | transform signal from HDMI to SDI | L3D (soon Toolbox) |
| | 3x 25m SDI cable | transport video from ruum42 to NOC | L3D (soon Toolbox) |
| | 1x HDMI -> SDI | cheap HDMI -> SDI converter | L3D (soon Toolbox) [!NOT ARRIVED] |
| | | | |
| Camera | 1x Panasonic HC X909 | Camecorder for life output | L3D |
| Camera | 1x power (9.8V) | Power for Camecorder | L3D |
| Camera | 1x MiniHDMI -> HDMI | HDMI Cable for Camecorder | L3D |
| | | | |
| Audio | 
### How is the Hardware connected?



