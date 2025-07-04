# Task: Create a one-shot installation script for the SciOp data rescue node for a Raspberry Pi

**Goal**: Create a one-click installation script for the SciOp data rescue node, which does all necessary setup steps automatically.

**Prerequisites**: We assume a freshly flashed headless Raspberry Pi with a working internet connection and a HDD physically attached. The script should be able to run on any Linux system, but we will test it on a Raspberry Pi OS Lite installation.

**Challenges**: 

- generally: automatize all manual steps
- qBittorrent is tailored towards a manual setup in the web UI. How can this be done automatically with a shell script?
- How can we automatically add the torrent files to the qBittorrent client, without manual selection?
- What options should be asked from the user during installation? Make it as easy/automated as possible, but also allow for some customization.

**Steps**:

(for a working example, see [https://codeberg.org/nicebread/HiveSeed/src/branch/main/pi_zero_w.md](https://codeberg.org/nicebread/HiveSeed/src/branch/main/pi_zero_w.md))
