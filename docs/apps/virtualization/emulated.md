---
title: Emulated GPU
parent: Virtualization
nav_order: 1
---

# Emulated GPU
{: .no_toc }

&#8220;One of my most productive days was throwing away 1,000 lines of
code.&#8221; &mdash; *Ken Thompson*
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

Software-based emulation is straightforward and doesn't require specialized
hardware. They are suitable for light tasks like office work and web browsing.

## VM management

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
            alt="VirtualBox"
            title="VirtualBox"
            src="../../../../images/apps/virtualization/emulated_virtualbox.svg"/>
        </td>
        <td style="text-align: left;">
          VirtualBox uses its own hypervisor technology focused on ease of use
          instead of performance.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="GNOME Boxes"
            title="GNOME Boxes"
            src="../../../../images/apps/virtualization/emulated_gnome_boxes.svg"/>
          &emsp;
          <img
            alt="UTM"
            title="UTM"
            src="../../../../images/apps/virtualization/emulated_utm.png"/>
        </td>
        <td style="text-align: left;">
          GNOME Boxes and UTM, built on top of QEMU/KVM, can achieve near-native
          performance.
          <label class="label label-red">No Windows client</label>
          <ul>
            <li>
              <a href="https://archlinux.org/packages/extra/x86_64/gnome-boxes">
                gnome-boxes
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/cask/utm">
                utm<sup>BREW</sup>
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
