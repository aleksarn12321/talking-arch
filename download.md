# Download

[home](/index.md)  [about](/about.md)

Here you will always find the latest version of the TalkingArch live image. You will also be able to clone the git repository to build and test the latest changes before they are released here.
Please note that TalkingArch, like the official Arch Linux iso, is compatible with any 64-bit AMD/Intel (x86_64) machine.

## Release info

* Current release: 2020.04.27
* Download size: 668 MB
* Linux kernel version: 5.6.7.arch1-1

**[Download TalkingArch](https://github.com/alex19EP/talking-arch/releases/download/v6.1/TalkingArch-2020.04.27-x86_64.iso)**

**[download Detached signature](https://github.com/alex19EP/talking-arch/releases/download/v6.1/TalkingArch-2020.04.27-x86_64.iso.sig)**

## File Integrity Verification

Before attempting to use this iso, especially if burning to optical media such as a DVD, it is a good idea to verify the integrity of the downloaded file. This will ensure that you have a complete copy that is not tampered with or corrupt in any way.

### using gpg

1. download Detached signature.
2. import my publick pgp key: `gpg --keyserver hkps://keys.openpgp.org --recv-keys 6C7F7F22E0152A6FD5728592DAD6F3056C897266`
3. verify .iso file: `gpg --verify TalkingArch-*.iso.sig  TalkingArch-*.iso`

## Build Your Own TalkingArch Iso

If you would like to test the latest changes to the build system, or if you would like to build your own TalkingArch iso, you may clone the git repository.

```shell
git clone https://github.com/alex19EP/talkingarch.git
```

You will also need to clone the Archiso git repository, as TalkingArch is just an alternative Archiso build configuration.

```shell
git clone git://projects.archlinux.org/archiso.git
```
