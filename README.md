
# Dxcz's guide to Debian 12 (Bookworm) KDE setup

**Welcome to my personal guide on setting up a live install image of Debian 12 KDE.**

This guide was written for following system:

- **OS**: Debian 12 (Bookworm)

- **DE**: KDE Plasma

- **Compositor**: Wayland

- **WM**: kwin | *(eventually will install AwesomeWM or qtile)*

- **Login manager**: SDDM

### Important notes about this guide:

- This is NOT a comprehensive guide. 

- This is a personal e-notebook for my own future reference.

- The primary purpose for creating this guide is: 
    - Familiarize myself with using: markdown, git, & VScodium.
    - keeping an administrative log of installed packages, dependencies, etc.



## First time booting post-installation

After successfully installing the OS onto its own SSD *(i.e. partitions fully formatted during installation, not dual-booting from the same SSD)*:  

* Reboot the computer, 

* Remove the live image USB to ensure your computer isn't booting into it,

* Login using the user info that you just created.

**Welcome to the beautiful world of Linux, let's dive right in and install essentials.**

* Open the terminal. The default terminal is Konsole.  
*Dont forget to setup keybinds: system settings > Workspace > shortcuts!*

***If you are attempting to install apps, and you are receiving an error that user doesn't have sudo permissions / isn't in sudoers file:***

1) Elevate to root.

2) Add yourself to sudo group if you want user profile to have full admin permissions, otherwise, create a new group. 

```python
    su root
    sudo usermod -aG sudo (username)
```

3) Reboot your system.



# Apps
Section is continuously updated to ensure an administrative log is kept of all packages installed. Will also keep track of any required dependencies that need to be install.

# Themes