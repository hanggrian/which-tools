---
title: Virtualization
parent: Applications
nav_order: 5
---

# Virtualization

---

You can always dual-boot if virtualization is not your thing.

## Containers

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
            alt="LXC"
            title="LXC"
            src="../../../images/apps/virtualization/containers_lxc.svg"/>
        </td>
        <td style="text-align: left;">
          LXC is lesser known, most noticably used by Proxmox.
          <label class="label label-red">No Linux client</label>
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Podman"
            title="Podman"
            src="../../../images/apps/virtualization/containers_podman.svg"/>
        </td>
        <td style="text-align: left;">
          Podman is daemonless and compatible with Dockerfiles, default
          containerization tool for RHEL-based distros.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Docker"
            title="Docker"
            src="../../../images/apps/virtualization/containers_docker.svg"/>
        </td>
        <td style="text-align: left;">
          Docker is the most popular containerization tool.
          <ul>
            <li>
              <a href="https://archlinux.org/packages/extra/x86_64/docker">
                docker
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/formula/docker">
                docker<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/Docker/DockerDesktop">
                Docker.DockerDesktop
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
