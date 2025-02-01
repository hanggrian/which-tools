---
title: Files
parent: Services
nav_order: 1
---

# Files
{: .no_toc }

&#8220;Real men don't use backups, they post their stuff on a public ftp server
and let the rest of the world make copies.&#8221; &mdash; Linus Torvalds
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Sharing

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
            alt="NFS"
            title="NFS"
            src="../../../images/services/files_nfs.svg"/>
        </td>
        <td style="text-align: left;">
          NFS is poorly supported on Windows.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="SMB"
            title="SMB"
            src="../../../images/services/files_smb.png"/>
        </td>
        <td style="text-align: left;">
          Old and reliable, SMB network shares can be accessed on all platforms.
          <ul>
            <li>
              <a href="https://archlinux.org/packages/extra/x86_64/samba">
                samba
              </a>
            </li>
            <li>
              <a href="https://support.apple.com/guide/mac-help/set-up-smb-file-sharing-on-mac-mh14107/mac/">
                SMB
              </a>
            </li>
            <li>
              <a href="https://learn.microsoft.com/en-us/windows/win32/fileio/microsoft-smb-protocol-and-cifs-protocol-overview/">
                SMB and CIFS
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
