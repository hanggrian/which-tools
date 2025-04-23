---
title: Code
parent: Applications
nav_order: 1
---

# Code
{: .no_toc }

&ldquo;Code is like humor. When you have to explain it, it's bad.&rdquo;
&mdash; *Cory House*
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

[ArchWiki](https://wiki.archlinux.org/title/List_of_applications/Utilities)
{: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

## Data analysis

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
            alt="Zeppelin"
            title="Zeppelin"
            src="../../../images/apps/code_zeppelin.svg"/>
        </td>
        <td style="text-align: left;">
          Zeppelin supports multiple languages without isolating the kernel, but
          is not as popular as Jupyter.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="RMarkdown"
            title="RMarkdown"
            src="../../../images/apps/code_rmarkdown.png"/>
        </td>
        <td style="text-align: left;">
          RMarkdown has better visualization but is limited to R.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/Jupyter">
            <img
              alt="Jupyter"
              title="Jupyter"
              src="../../../images/apps/code_jupyter.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          Jupyter is the standard for Python data science, compatible with other
          languages with plugins.
          <ul>
            <li>
              <a href="https://archlinux.org/packages/extra/any/jupyterlab">
                jupyterlab
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/formula/jupyterlab">
                jupyterlab<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/ProjectJupyter/JupyterLab">
                ProjectJupyter.JupyterLab
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

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
            alt="Geany"
            title="Geany"
            src="../../../images/apps/code_geany.svg"/>
          &emsp;
          <a href="https://wiki.archlinux.org/title/KDevelop">
            <img
              alt="KDevelop"
              title="KDevelop"
              src="../../../images/apps/code_kdevelop.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          Lightweight IDEs lack features and are not extensible.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/NetBeans">
            <img
              alt="NetBeans"
              title="NetBeans"
              src="../../../images/apps/code_netbeans.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          NetBeans is a good beginner IDE but has limited amount of plugins.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/Eclipse">
            <img
              alt="Eclipse"
              title="Eclipse"
              src="../../../images/apps/code_eclipse.svg"/>
          </a>
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
            src="../../../images/apps/code_jetbrains_toolbox.svg"/>
        </td>
        <td style="text-align: left;">
          Toolbox is a manager for JetBrains IDEs.
          <ul>
            <li>
              <a href="https://aur.archlinux.org/packages/jetbrains-toolbox">
                jetbrains-toolbox<sup>AUR</sup>
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/cask/jetbrains-toolbox">
                jetbrains-toolbox<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/JetBrains/Toolbox">
                JetBrains.Toolbox
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
          <a href="https://wiki.archlinux.org/title/GNOME/Gedit">
            <img
              alt="gedit"
              title="gedit"
              src="../../../images/apps/code_gedit.svg"/>
          </a>
          <a href="https://wiki.archlinux.org/title/Kate">
            <img
              alt="Kate"
              title="Kate"
              src="../../../images/apps/code_kate.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          Default text editors lack features and are not extensible.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Codium"
            title="Codium"
            src="../../../images/apps/code_codium.svg"/>
          &emsp;
          <a href="https://wiki.archlinux.org/title/Visual_Studio_Code">
            <img
              alt="Visual Studio Code"
              title="Visual Studio Code"
              src="../../../images/apps/code_visual_studio_code.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          Visual Studio Code has a healthy amount of extensions and integrates
          with GitHub Copilot.
          <label class="label label-yellow">Built on Electron</label>
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Sublime Text"
            title="Sublime Text"
            src="../../../images/apps/code_sublime_text.svg"/>
        </td>
        <td style="text-align: left;">
          Sublime Text is the most fully-featured text editor that is not
          web or Electron-based.
          <label class="label label-purple">Not free</label>
          <ul>
            <li>
              <a href="https://aur.archlinux.org/packages/sublime-text-4">
                sublime-text-4<sup>AUR</sup>
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/cask/sublime-text">
                sublime-text<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/SublimeHQ/SublimeText.4">
                SublimeHQ.SublimeText.4
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
