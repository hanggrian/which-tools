---
title: Operating systems
nav_order: 2
---

# Operating systems
{: .no_toc }

&ldquo;UNIX is very simple, it just needs a genius to understand its
simplicity.&rdquo;
&mdash; *Dennis Ritchie*
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Linux

There are many other upstream distributions like Slackware and Gentoo. But for
the purpose of this guide, only the most popular ones are listed. All Linux
distros come with a package manager.

### Desktop distros

<div class="code-example" markdown="1">
  <table>
    <thead>
      <tr>
        <th style="text-align: center; width: 280px;">Avoid</th>
        <th style="text-align: center;">Why</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Ubuntu"
            title="Ubuntu"
            src="../../images/systems_ubuntu.svg"/>
        </td>
        <td style="text-align: left;">
          Ubuntu installs Snap packages without user consent and has a history
          of privacy issues.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="CachyOS"
            title="CachyOS"
            src="../../images/systems_cachyos.svg"/>
          &emsp;
          <img
            alt="Garuda"
            title="Garuda"
            src="../../images/systems_garuda.svg"/>
          &emsp;
          <img
            alt="Nobara"
            title="Nobara"
            src="../../images/systems_nobara.svg"/>
        </td>
        <td style="text-align: left;">
          Performance-oriented distros are often unstable and bloated with
          unnecessary gaming themes.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Debian"
            title="Debian"
            src="../../images/systems_debian.svg"/>
          &emsp;
          <img
            alt="Fedora"
            title="Fedora"
            src="../../images/systems_fedora.svg"/>
          &emsp;
          <img
            alt="Arch"
            title="Arch"
            src="../../images/systems_arch.svg"/>
        </td>
        <td style="text-align: left;">
          Downstream distros are lean but require more setup because they are
          unconfigured.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Manjaro"
            title="Manjaro"
            src="../../images/systems_manjaro.svg"/>
          &emsp;
          <img
            alt="OpenSUSE"
            title="OpenSUSE"
            src="../../images/systems_opensuse.svg"/>
          &emsp;
          <img
            alt="Pop!_OS"
            title="Pop!_OS"
            src="../../images/systems_pop_os.svg"/>
        </td>
        <td style="text-align: left;">
          Considerable modifications to upstream packages and default themes but
          are still generally user-friendly.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Fedora Silverblue"
            title="Fedora Silverblue"
            src="../../images/systems_fedora_silverblue.svg"/>
          &emsp;
          <img
            alt="Vanilla OS"
            title="Vanilla OS"
            src="../../images/systems_vanilla_os.svg"/>
        </td>
        <td style="text-align: left;">
          Immutable OS is a good choice for servers. They rely on sandboxing and
          containerization for installing applications. But if the server mainly
          runs containers, it is more convenient to use distros with web-based
          container management like Proxmox or TrueNAS SCALE.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="EndeavourOS"
            title="EndeavourOS"
            src="../../images/systems_endeavouros.svg"/>
        </td>
        <td style="text-align: left;">
          Arch Linux with a graphical installer, sensible defaults and minimal
          theme customizations.
          <ul>
            <li>
              <a href="https://endeavouros.com/">
                ISO
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

### Server distros

<div class="code-example" markdown="1">
  <table>
    <thead>
      <tr>
        <th style="text-align: center; width: 280px;">Avoid</th>
        <th style="text-align: center;">Why</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align: center;">
          <img
            alt="TrueNAS Scale"
            title="TrueNAS Scale"
            src="../../images/systems_truenas_scale.png"/>
        </td>
        <td style="text-align: left;">
          TrueNAS SCALE supports ZFS out of the box and manages containerized
          applications with a web interface. However, the file sharing is served
          from the host system, which may break in the event of
          misconfiguration.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="AlmaLinux"
            title="AlmaLinux"
            src="../../images/systems_almalinux.svg"/>
          &emsp;
          <img
            alt="CentOS"
            title="CentOS"
            src="../../images/systems_centos.svg"/>
          &emsp;
          <img
            alt="Rocky Linux"
            title="Rocky Linux"
            src="../../images/systems_rocky_linux.svg"/>
        </td>
        <td style="text-align: left;">
          Decent alternatives to RHEL, known for servers with GUIs.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="OpenMediaVault"
            title="OpenMediaVault"
            src="../../images/systems_openmediavault.svg"/>
        </td>
        <td style="text-align: left;">
          Notably easier to setup than TrueNAS, ZFS support is available with
          plugins.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Proxmox"
            title="Proxmox"
            src="../../images/systems_proxmox.svg"/>
        </td>
        <td style="text-align: left;">
          Proxmox VE is scalable with Cluster Manager and extensive
          documentation to passthrough hardware to VMs.
          <ul>
            <li>
              <a href="https://www.proxmox.com/en/downloads/">
                ISO
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

### Desktop environments

<div class="code-example" markdown="1">
  <table>
    <thead>
      <tr>
        <th style="text-align: center; width: 280px;">Avoid</th>
        <th style="text-align: center;">Why</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/LXDE">
            <img
              alt="LXDE"
              title="LXDE"
              src="../../images/systems_lxde.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          Older desktop environment that still uses GTK 2, GTK 3 builds are
          experimental.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/Budgie">
            <img
              alt="Budgie"
              title="Budgie"
              src="../../images/systems_budgie.svg"/>
          </a>
          &emsp;
          <a href="https://wiki.archlinux.org/title/Cinnamon">
            <img
              alt="Cinnamon"
              title="Cinnamon"
              src="../../images/systems_cinnamon.svg"/>
          </a>
          &emsp;
          <a href="https://wiki.archlinux.org/title/Deepin_Desktop_Environment">
            <img
              alt="Deepin"
              title="Deepin"
              src="../../images/systems_deepin.svg"/>
          </a>
          &emsp;
          <a href="https://wiki.archlinux.org/title/MATE">
            <img
              alt="MATE"
              title="MATE"
              src="../../images/systems_mate.svg"/>
          </a>
          &emsp;
          <a href="https://wiki.archlinux.org/title/Pantheon">
            <img
              alt="Pantheon"
              title="Pantheon"
              src="../../images/systems_pantheon.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          Based on GNOME or modify GTK stylesheets that
          <a href="https://stopthemingmy.app/">break GTK themes</a> on other
          applications.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/COSMIC">
            <img
              alt="COSMIC"
              title="COSMIC"
              src="../../images/systems_cosmic.png"/>
          </a>
        </td>
        <td style="text-align: left;">
          COSMIC is unique in that it does not use GTK or Qt.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/LXQt">
            <img
              alt="LXQt"
              title="LXQt"
              src="../../images/systems_lxqt.png"/>
          </a>
          &emsp;
          <a href="https://wiki.archlinux.org/title/Xfce">
            <img
              alt="Xfce"
              title="Xfce"
              src="../../images/systems_xfce.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          Lightweight desktop environments are perfect for older hardware or
          VMs with limited resources. However, the interface is outdated and
          do not support Wayland.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/GNOME">
            <img
              alt="GNOME"
              title="GNOME"
              src="../../images/systems_gnome.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          GNOME has a cleaner interface but requires extensions to be usable.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/KDE">
            <img
              alt="KDE"
              title="KDE"
              src="../../images/systems_kde.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          Every component of KDE desktop is configurable, this may be appealing
          to some users but can be irritating to others.
        </td>
      </tr>
    </tbody>
  </table>
</div>

### Bootloaders

<div class="code-example" markdown="1">
  <table>
    <thead>
      <tr>
        <th style="text-align: center; width: 280px;">Consider</th>
        <th style="text-align: center;">Why</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/GRUB">
            <img
              alt="GRUB"
              title="GRUB"
              src="../../images/systems_grub.png"/>
          </a>
        </td>
        <td style="text-align: left;">
          Older bootloader with BIOS and UEFI support. Easy to configure with
          dual-boot Windows due to automatic OS probing.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/systemd-boot">
            <img
              alt="systemd-boot"
              title="systemd-boot"
              src="../../images/systems_systemd_boot.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          Direct kernel loading from the ESP and slightly faster boot times.
        </td>
      </tr>
    </tbody>
  </table>
</div>

## macOS

macOS does not have pre-installed package managers, install Homebrew to install
applications from the command line.

[Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
{: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

[Homebrew](https://brew.sh/)
{: .btn .btn-outline .fs-5 .mb-4 .mb-md-0 }

### Bootloaders

<div class="code-example" markdown="1">
  <table>
    <thead>
      <tr>
        <th style="text-align: center; width: 280px;">Avoid</th>
        <th style="text-align: center;">Why</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Clover"
            title="Clover"
            src="../../images/systems_clover.png"/>
        </td>
        <td style="text-align: left;">
          Clover is a legacy macOS bootloader. While it still works,
          optimization requires quirks, trial and error.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="OpenCore"
            title="OpenCore"
            src="../../images/systems_opencore.svg"/>
        </td>
        <td style="text-align: left;">
          Newer bootloader with SIP and FileVault support. The install guide
          is tailored to specific hardware and is updated frequently.
          <ul>
            <li>
              <a href="https://github.com/acidanthera/OpenCorePkg/releases/latest/">
                ZIP
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

## Windows

Windows comes with `winget` package manager.

<div class="code-example" markdown="1">
  <table>
    <thead>
      <tr>
        <th style="text-align: center; width: 280px;">Avoid</th>
        <th style="text-align: center;">Why</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align: center;">
          <img
            alt="AtlasOS"
            title="AtlasOS"
            src="../../images/systems_atlasos.svg"/>
        </td>
        <td style="text-align: left;">
          While AtlasOS offers performance gains, it does so by removing
          security features and Windows Update.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Windows"
            title="Windows"
            src="../../images/systems_windows.svg"/>
        </td>
        <td style="text-align: left;">
          Plain Windows is very bloated, requires an online account in
          pre-install and automatically logs in to OneDrive once installed.
          <label class="label label-purple">Not free</label>
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Tiny11"
            title="Tiny11"
            src="../../images/systems_tiny11.png"/>
        </td>
        <td style="text-align: left;">
          Build your own Windows ISO with PowerShell scripts, does not remove
          security features and Windows Update.
          <label class="label label-purple">Not free</label>
          <ul>
            <li>
              <a href="https://github.com/ntdevlabs/tiny11builder/releases/latest/">
                ZIP
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
