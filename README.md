## Zorin OS

1. shrink volume of disk C (Unallocated)

2. with the iso installed and the pendrive ready, restart the computer and keep pressing F2 or ESC

3. settings to apply (if available):

    - disable boot security (security > security boot menu > security boot control > disabled)
    - UEFI boot option filter (quick control > boot option filter > UEFI and Legacy)
    - enable fast boot (boot > fast boot > enabled)
    - hard drive BBS priorities (boot > hard drive > boot opt 1 > your pendrive)
    - boot option priorities (boot opt 1 > your UEFI pendrive)
    - save and exit

4. select option:

- Try or Install Zorin OS (normal)
- Try or Install Zorin OS NVIDIA drivers (if you have an nvidia video card)

5. Install Zorin OS:

- [x] install third-party programs, video cards, Wi-Fi devices and other media formats

- installation type: advanced options

- select the reserved space for Zorin OS (free space) and:

  - create a partition for swap (2GB, type for new partition: primary, location for new partition: start)
  - create a partition for BIOS (1GB, type for new partition: primary, location for new partition: start)
  - create a EFI system partition (100MB, type for new partition: primary, location for new partition: start)
  - select the reserved space for Zorin OS and select the option to use as a btrfs journaling filesystem  
    (type for new partition: primary, location for new partition: start, mounting point: /)
  - select zorin OS partition and click "install now"

extentions - extention manager:  
Blur my Shell  
Dash2Dock Animated  
Forge
