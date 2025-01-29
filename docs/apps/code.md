---
title: Code
parent: Applications
nav_order: 1
---

# Code
{: .no_toc }

&#8220;If debugging is the process of removing software bugs, then programming
must be the process of putting them in.&#8221; &mdash; *Edsger Dijkstra*
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## IDEs

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
            alt="Vim"
            title="Vim"
            src="../../../images/apps/code/netbeans.svg"/>
        </td>
        <td style="text-align: left;">
          NetBeans is a good beginner IDE but has limited amount of plugins.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Eclipse"
            title="Eclipse"
            src="../../../images/apps/code/eclipse.svg"/>
        </td>
        <td style="text-align: left;">
          Eclipse supports many languages and has a large community.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="JetBrains Toolbox"
            title="JetBrains Toolbox"
            src="../../../images/apps/code/jetbrains_toolbox.svg"/>
        </td>
        <td style="text-align: left;">
          Toolbox is a manager for JetBrains IDEs.
          <ul>
            <li>
              <a
                class="label label-blue"
                href="https://aur.archlinux.org/packages/jetbrains-toolbox">
                jetbrains-toolbox<sup>AUR</sup>
              </a>
            </li>
            <li>
              <a
                class="label label-purple"
                href="https://formulae.brew.sh/cask/jetbrains-toolbox">
                jetbrains-toolbox<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a
                class="label label-red"
                href="https://winget.run/pkg/JetBrains/Toolbox">
                JetBrains.Toolbox
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

## Comparison, diff, merge

<div class="code-example" markdown="1">
  <table>
    <thead>
      <tr>
        <th style="text-align: center; width: 280px;">Prefer</th>
        <th style="text-align: center;">Why</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Meld"
            title="Meld"
            src="../../../images/apps/code/meld.svg"/>
        </td>
        <td style="text-align: left;">
          Meld compares files, directories and recognizes Git repositories.
          <ul>
            <li>
              <a
                class="label label-blue"
                href="https://archlinux.org/packages/extra/any/meld">
                meld
              </a>
            </li>
            <li>
              <a
                class="label label-purple"
                href="https://formulae.brew.sh/cask/dehesselle-meld">
                meld<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a
                class="label label-red"
                href="https://winget.run/pkg/Meld/Meld">
                Meld.Meld
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

## Text editors

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
            alt="Vim"
            title="Vim"
            src="../../../images/apps/code/vim.svg"/>
        </td>
        <td style="text-align: left;">
          Although extremely customizable, Vim requires steep learning curve.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="nano"
            title="nano"
            src="../../../images/apps/code/nano.svg"/>
        </td>
        <td style="text-align: left;">
          Nano is beginner-friendly and pre-installed on most UNIX systems.
          <ul>
            <li>
              <a
                class="label label-blue"
                href="https://archlinux.org/packages/core/x86_64/nano">
                nano
              </a>
            </li>
            <li>
              <a
                class="label label-purple"
                href="https://support.apple.com/guide/terminal/use-command-line-text-editors-apdb02f1133-25af-4c65-8976-159609f99817/mac/">
                nano
              </a>
            </li>
            <li>
              <a
                class="label label-red"
                href="https://github.com/okibcn/nano-for-windows/">
                nano-for-windows<sup>SOURCE</sup>
              </a>
            </li>
          </ul>
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Codium"
            title="Codium"
            src="../../../images/apps/code/codium.svg"/>
          &emsp;
          <img
            alt="Visual Studio Code"
            title="Visual Studio Code"
            src="../../../images/apps/code/visual_studio_code.svg"/>
        </td>
        <td style="text-align: left;">
          Visual Studio Code is a decent text editor with many extensions and
          cloud saving to preserve user settings.
          <ul>
            <li>
              <a
                class="label label-blue"
                href="https://aur.archlinux.org/packages/visual-studio-code-bin">
                visual-studio-code-bin<sup>AUR</sup>
              </a>
            </li>
            <li>
              <a
                class="label label-purple"
                href="https://formulae.brew.sh/cask/visual-studio-code">
                visual-studio-code<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a
                class="label label-red"
                href="https://winget.run/pkg/Microsoft/VisualStudioCode">
                Microsoft.VisualStudioCode
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
