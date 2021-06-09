# NIGHTLY BUILD

![Axis Linux](https://user-images.githubusercontent.com/61242573/118399404-43c30480-b65d-11eb-9c81-82fccb9cf14e.png)

### WARNING: This is an automatically generated nightly build. Please do not install it for daily usage!

The OS is still in beta stage, so bugs may occur. It's not recommended for daily use yet.

Currently, only 64-bit architecture is supported. Expect 32-bit versions to be released in the future.
Right now, Axis Linux uses systemd init system. This will be changed in future releases.

---

**Important:** After installing the system make sure to edit `/etc/pacman.conf` and add in `axislinux-repo` entry on top of all entries there:
```
[axislinux-repo]
Server = https://axislinux.github.io/$repo/$arch
```
