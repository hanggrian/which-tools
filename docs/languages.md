---
title: Programming languages
nav_order: 3
---

# Programming languages
{: .no_toc }

&#8220;Code is like humor. When you have to explain it, it&#8217;s bad.&#8221;
&mdash; *Cory House*
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Ruby

### Version managers

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
            alt="asdf-vm"
            title="asdf-vm"
            src="../../images/languages/asdf_vm.png"/>
        </td>
        <td style="text-align: left;">
          asdf-vm is a universal version manager that supports multiple
          languages not limited to Ruby.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="rvm"
            title="rvm"
            src="../../images/languages/rvm.png"/>
        </td>
        <td style="text-align: left;">
          RVM and chruby are extensive but ship with shell modifications.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="rbenv"
            title="rbenv"
            src="../../images/languages/rbenv.png"/>
        </td>
        <td style="text-align: left;">
          rbenv sets the Ruby version globally per user or localler per
          directory.
          <ul>
            <li>
              <a
                class="label label-blue"
                href="https://archlinux.org/packages/extra/any/rbenv">
                rbenv
              </a>
            </li>
            <li>
              <a
                class="label label-purple"
                href="https://formulae.brew.sh/formula/rbenv">
                rbenv<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a
                class="label label-red"
                href="https://github.com/RubyMetric/rbenv-for-windows/">
                rbenv-for-windows<sup>SOURCE</sup>
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

## Java

[Which Version of JDK Should I Use?](https://whichjdk.com/)
{: .btn .fs-5 .mb-4 .mb-md-0 }

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
            alt="OpenJDK"
            title="OpenJDK"
            src="../../images/languages/openjdk.svg"/>
          &emsp;
          <img
            alt="Oracle Java"
            title="Oracle Java"
            src="../../images/languages/oracle_java.svg"/>
        </td>
        <td style="text-align: left;">
          Oracle JDK is no longer free for commercial use while OpenJDK update
          roadmap lags behind other flavors.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Liberica"
            title="Liberica"
            src="../../images/languages/liberica.svg"/>
          &emsp;
          <img
            alt="Zulu"
            title="Zulu"
            src="../../images/languages/zulu.svg"/>
        </td>
        <td style="text-align: left;">
          Bellsoft and Zulu provide OpenJFX binaries for JavaFX developers.
          However, CI/CD pipelines do not usually support these flavors.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Temurin"
            title="Temurin"
            src="../../images/languages/temurin.svg"/>
        </td>
        <td style="text-align: left;">
          Maintained by Eclipse Foundation with timely updates, LTS releases
          and free for commercial use.
          <ul>
            <li>
              <a
                class="label label-blue"
                href="https://aur.archlinux.org/packages/jdk-temurin">
                jdk-temurin<sup>AUR</sup>
              </a>
            </li>
            <li>
              <a
                class="label label-purple"
                href="https://formulae.brew.sh/cask/temurin">
                temurin<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a
                class="label label-red"
                href="https://winget.run/pkg/EclipseAdoptium/Temurin.19.JRE">
                EclipseAdoptium.Temurin.19.JRE
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

### Version managers

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
            alt="SDKMAN!"
            title="SDKMAN!"
            src="../../images/languages/sdkman.svg"/>
        </td>
        <td style="text-align: left;">
          SDKMAN! is a universal version manager that supports multiple
          languages not limited to Java.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Java Runtime"
            title="Java Runtime"
            src="../../images/languages/java_runtime.svg"/>
        </td>
        <td style="text-align: left;">
          Specific Java switcher command for Arch Linux.
          <ul>
            <li>
              <a
                class="label label-blue"
                href="https://archlinux.org/packages/extra/any/java-runtime-common">
                java-runtime-common
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

## Python

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
            alt="Anaconda"
            title="Anaconda"
            src="../../images/languages/anaconda.svg"/>
        </td>
        <td style="text-align: left;">
          Anaconda allows users to install packages with dependencies but comes
          with a lot of unnecessary applications and not free for commercial
          use.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Python"
            title="Python"
            src="../../images/languages/python.svg"/>
        </td>
        <td style="text-align: left;">
          Use the official Python distribution with PIP to install packages.
          <ul>
            <li>
              <a
                class="label label-blue"
                href="https://archlinux.org/packages/core/x86_64/python">
                python
              </a>
            </li>
            <li>
              <a
                class="label label-purple"
                href="https://formulae.brew.sh/formula/python@3.13">
                python@3.13<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a
                class="label label-red"
                href="https://winget.run/pkg/Python/Python.3.11">
                Python.Python.3.11
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
