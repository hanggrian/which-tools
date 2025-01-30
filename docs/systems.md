---
title: Operating systems
nav_order: 2
---

# Operating systems
{: .no_toc }

&#8220;UNIX is very simple, it just needs a genius to understand its
simplicity.&#8221; &mdash; *Dennis Ritchie*
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
          <img
            alt="GRUB"
            title="GRUB"
            src="../../images/systems/grub.png"/>
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
          <img
            alt="systemd-boot"
            title="systemd-boot"
            src="../../images/systems/systemd_boot.svg"/>
        </td>
        <td style="text-align: left;">
          Direct kernel loading from the ESP and slightly faster boot times.
        </td>
      </tr>
    </tbody>
  </table>
</div>

### Upstream distros

[ArchWiki](https://wiki.archlinux.org/)
{: .btn .btn-outline .fs-5 .mb-4 .mb-md-0 }

<p>
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
          <img
            alt="Debian"
            title="Debian"
            src="../../images/systems/debian.svg"/>
        </td>
        <td style="text-align: left;">
          Debian is known for its slow release cycle, most Debian-based distros
          still use Xorg as the default display server.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Fedora"
            title="Fedora"
            src="../../images/systems/fedora.svg"/>
        </td>
        <td style="text-align: left;">
          Due to law restrictions, RHEL-based distros are very strict about
          including proprietary software in their repositories.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Arch"
            title="Arch"
            src="../../images/systems/arch.svg"/>
        </td>
        <td style="text-align: left;">
          Arch Linux has a rolling release model that does not distract users
          with major version upgrades. It also has the largest community
          repository, less reservations against proprietary software and
          wiki-style documentation.
          <ul>
            <li>
              <a
                class="label label-blue"
                href="https://archlinux.org/download">
                  ISO
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
</p>

{: .note }
> Arch Linux gets a bad reputation for being difficult to install, but this is
  lately untrue with the [archinstall](https://wiki.archlinux.org/title/Archinstall)
  command.

### Downstream distros

[Please don't theme our apps](https://stopthemingmy.app/)
{: .btn .btn-outline .fs-5 .mb-4 .mb-md-0 }

<p>
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
            src="../../images/systems/ubuntu.svg"/>
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
            src="../../images/systems/cachyos.svg"/>
          &emsp;
          <img
            alt="Garuda"
            title="Garuda"
            src="../../images/systems/garuda.svg"/>
          &emsp;
          <img
            alt="Nobara"
            title="Nobara"
            src="../../images/systems/nobara.svg"/>
        </td>
        <td style="text-align: left;">
          Performance-oriented distros are often unstable and bloated with
          unnecessary gaming themes.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Deepin"
            title="Deepin"
            src="../../images/systems/deepin.svg"/>
          &emsp;
          <img
            alt="elementary"
            title="elementary"
            src="../../images/systems/elementary.svg"/>
          &emsp;
          <img
            alt="Mint"
            title="Mint"
            src="../../images/systems/mint.svg"/>
          &emsp;
          <img
            alt="Pop!_OS"
            title="Pop!_OS"
            src="../../images/systems/pop_os.svg"/>
          &emsp;
          <img
            alt="Zorin OS"
            title="Zorin OS"
            src="../../images/systems/zorin_os.svg"/>
        </td>
        <td style="text-align: left;">
          Heavily modifies GTK stylesheets or is based on GNOME with significant
          modifications.
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
            src="../../images/systems/almalinux.svg"/>
          &emsp;
          <img
            alt="CentOS"
            title="CentOS"
            src="../../images/systems/centos.svg"/>
          &emsp;
          <img
            alt="Rocky Linux"
            title="Rocky Linux"
            src="../../images/systems/rocky_linux.svg"/>
        </td>
        <td style="text-align: left;">
          Decent alternatives to RHEL, work best in a server setup.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Manjaro"
            title="Manjaro"
            src="../../images/systems/manjaro.svg"/>
          &emsp;
          <img
            alt="OpenSUSE"
            title="OpenSUSE"
            src="../../images/systems/opensuse.svg"/>
        </td>
        <td style="text-align: left;">
          Considerable modifications to upstream packages and default themes.
          Has GUI package managers and administrative tools, which are important
          to some users.
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
            src="../../images/systems/proxmox.svg"/>
        </td>
        <td style="text-align: left;">
          VM and container management with a web interface.
          <ul>
            <li>
              <a
                class="label label-blue"
                href="https://www.proxmox.com/en/downloads/">
                ISO
              </a>
            </li>
          </ul>
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="EndeavourOS"
            title="EndeavourOS"
            src="../../images/systems/endeavouros.svg"/>
        </td>
        <td style="text-align: left;">
          Arch Linux with a graphical installer, sensible defaults and minimal
          theme customizations.
          <ul>
            <li>
              <a
                class="label label-blue"
                href="https://endeavouros.com/">
                ISO
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
</p>

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
          <img
            alt="LXQt"
            title="LXQt"
            src="../../images/systems/lxqt.png"/>
          &emsp;
          <img
            alt="Xfce"
            title="Xfce"
            src="../../images/systems/xfce.svg"/>
        </td>
        <td style="text-align: left;">
          Lightweight desktop environments are outdated and do not support
          Wayland. Their only use case is for older hardware.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="KDE"
            title="KDE"
            src="../../images/systems/kde.svg"/>
        </td>
        <td style="text-align: left;">
          Power users may prefer KDE for its customization options, quality
          bundled applications and community support.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="GNOME"
            title="GNOME"
            src="../../images/systems/gnome.svg"/>
        </td>
        <td style="text-align: left;">
          GNOME has a cleaner interface but requires extensions to be usable.
        </td>
      </tr>
    </tbody>
  </table>
</div>

## macOS

macOS does not have pre-installed package managers, install Homebrew to install
applications from the command line.

[Homebrew](https://brew.sh/)
{: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

### Bootloaders

[Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
{: .btn .btn-outline .fs-5 .mb-4 .mb-md-0 }

<p>
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
            src="../../images/systems/clover.png"/>
        </td>
        <td style="text-align: left;">
          Clover is a legacy macOS bootloader. While it still works,
          optimization requires quirks and a lot of trial and error.
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
            src="../../images/systems/opencore.svg"/>
        </td>
        <td style="text-align: left;">
          Newer bootloader with SIP and FileVault support. The install guide
          is tailored to specific hardware and is updated frequently.
          <ul>
            <li>
              <a
                class="label label-green"
                href="https://github.com/acidanthera/OpenCorePkg/releases/latest/">
                ZIP
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
</p>

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
            src="../../images/systems/atlasos.svg"/>
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
            src="../../images/systems/windows.svg"/>
        </td>
        <td style="text-align: left;">
          Plain Windows is very bloated, requires an online account to sign up
          and automatically logs in to OneDrive.
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
            src="../../images/systems/tiny11.png"/>
        </td>
        <td style="text-align: left;">
          Build your own Windows ISO with PowerShell scripts, does not remove
          security features and Windows Update.
          <ul>
            <li>
              <a
                class="label label-green"
                href="https://github.com/ntdevlabs/tiny11builder/releases/latest/">
                ZIP
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
