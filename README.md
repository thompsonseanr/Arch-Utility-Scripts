# Arch-Utility-Scripts

These are simple scripts written primarily for whenever I am performing Arch upgrades.

These scripts are actually distro-agnostic and will work for any system with LVM.

**Note:** I used this guide for my installation: [How To Install Arch Linux Step by Step With Screenshots](https://computingforgeeks.com/install-arch-linux-with-lvm-on-uefi-system/)

**Disclaimer:** These scripts are meant to work with the setup illustrated in the link above. Everyone's system is slightly different so they are not meant to be merely cloned and run. Here is an excellent guide I refer to, amongst others: [How to Manage and Use LVM (Logical Volume Management) in Ubuntu](https://www.howtogeek.com/howto/40702/how-to-manage-and-use-lvm-logical-volume-management-in-ubuntu/)

---

- **makebak:** script for making an LVM snapshot of my root directory prior to major upgrades.

- **deletebak:** script for deleting LVM snapshot.

- **mergebak:** uh-oh, something happened during the upgrade and I need to roll back. This also works for those times you have to boot via arch usb.

- **journal_error_log:** Optimized error log output to check errors after upgrades.
