## Zorin OS

1. **shrink volume of disk C (Unallocated)**

2. **with the iso installed and the pendrive ready, restart the computer and keep pressing F2 or ESC**

3. **settings to apply (if available):**

    - disable boot security (security > security boot menu > security boot control > disabled)
    - UEFI boot option filter (quick control > boot option filter > UEFI and Legacy)
    - enable fast boot (boot > fast boot > enabled)
    - hard drive BBS priorities (boot > hard drive > boot opt 1 > your pendrive)
    - boot option priorities (boot opt 1 > your UEFI pendrive)
    - save and exit

4. **select option:**

- Try or Install Zorin OS (normal)
- Try or Install Zorin OS NVIDIA drivers (if you have an nvidia video card)

5. **Install Zorin OS:**

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

#### Dash2Dock Animated config file to import > [click here](theme.json)  

#### Forge configuration:

_Settings_:

- [ ] stacked tiling mode
- [ ] tabbed tiling mode
- [ ] preview hint toggle
- [x] show focus hint toggle
- [ ] show window split hint border
default drag-and-drop center layout: tabbed
- [ ] auto split
- [ ] float mode always on top
- [ ] show tiling quick settings

_Appearance_:

gaps size: 2  
gaps size multiplier: 1  
- [ ] gaps hidden when single
- [x] floated focus hint: border color (yellow)

_Keyboard_:

drag-and-drop tiling modifier key options: super

window shorcuts:

| Action | Shortcut |
| --- | --- |
| Increase active window size left | `<Shift><Super>Left` |
| Decrease active window size left | `<Control><Super>Right` |
| Increase active window size bottom | `<Shift><Super>Up` |
| Decrease active window size bottom | `<Control><Super>Down` |
| Increase active window size top | `<Shift><Super>Down` |
| Decrease active window size top | `<Control><Super>Up ` |
| Increase active window size right | `<Shift><Super>Right` |
| Decrease active window size right | `<Control><Super>Left` |
| Split container horizontally | `<Super>z` |
| Split container vertically | `<Super>v` |
| Toggle split container | `<Super>g` |
| Window toggle always float | `<Super>f` |
| Window snap center | `<Super>c` |

#### Blur my Shell configuration:

overview:

- [x] background blur
- [x] customize properties  
sigma: 10  
brightness: 1.00  
overview components style: do not style
