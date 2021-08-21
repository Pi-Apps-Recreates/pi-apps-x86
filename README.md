![logo](https://raw.githubusercontent.com/MCRaspRBX/pi-apps-x86/logo/Pi-Apps_X86-removebg-preview.png?raw=true)
## A Debian/Ubuntu Based Appstore For Raspberry Pi People Have A Familer Appstore

## To install Pi-Apps x86
Pi-Apps x86 Supports AMD64 And i386
```
wget -qO- https://raw.githubusercontent.com/MCRaspRBX/pi-apps-x86/main/install | bash
```
The install script ensures [YAD](https://github.com/v1cont/yad) is installed, creates two menu buttons, an auto-started updater, and a file (`/usr/local/bin/pi-apps`) that allows pi-apps to be run from terminal. Besides those, nothing is modified outside of the Pi-Apps folder.

<details>
<summary><b>To install manually</b> if you prefer to see what happens under the hood</summary>
To manually install Pi-Apps:
 
```
git clone https://github.com/MCRaspRBX/pi-apps-x86
~/pi-apps-x86/install
```
</details>

<details>
<summary><b>To uninstall Pi-Apps</b></summary>
To uninstall Pi-Apps:

```
~/pi-apps-x86/uninstall
```
</details>

### Q&A with MCRaspRBX
 - Why did you develop Pi-Apps x86?  
> I made this x86 version so people from Rasberry Pi's have a familer appstore 

 - Is Pi-Apps x86 still under development?
> Sure is! Initial development is done for the most part, and I don't see any more major features being added to Pi-Apps's core functionality.
> But, there's always an app or two that need attention, and dozens of app requests. It's enough work to keep a *team* of developers busy.

 - Is Pi-Apps x86 free?
> Absolutely! Pi-Apps x86 is not a product or service: Anyone is welcome to use it; no-one should feel compelled/required to donate.

