---
title: Programming languages
nav_order: 3
---

# Programming languages
{: .no_toc }

&ldquo;Any nitwit can understand computers. Many do.&rdquo;
&mdash; *Ted Nelson*
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Ruby

[ArchWiki](https://wiki.archlinux.org/title/Ruby)
{: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

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
            src="../../images/languages_asdf_vm.png"/>
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
          <a href="https://wiki.archlinux.org/title/RVM">
            <img
              alt="RVM"
              title="RVM"
              src="../../images/languages_rvm.png"/>
          </a>
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
          <a href="https://wiki.archlinux.org/title/rbenv">
            <img
              alt="rbenv"
              title="rbenv"
              src="../../images/languages_rbenv.png"/>
          </a>
        </td>
        <td style="text-align: left;">
          rbenv sets the Ruby version globally per user or localler per
          directory.
          <ul>
            <li>
              <a href="https://archlinux.org/packages/extra/any/rbenv">
                rbenv
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/formula/rbenv">
                rbenv<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://github.com/RubyMetric/rbenv-for-windows/">
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

[ArchWiki](https://wiki.archlinux.org/title/Java)
{: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

[Which Version of JDK Should I Use?](https://whichjdk.com/)
{: .btn .btn-outline .fs-5 .mb-4 }

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
            src="../../images/languages_openjdk.svg"/>
          &emsp;
          <img
            alt="Oracle Java"
            title="Oracle Java"
            src="../../images/languages_oracle_java.svg"/>
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
            src="../../images/languages_liberica.svg"/>
          &emsp;
          <img
            alt="Zulu"
            title="Zulu"
            src="../../images/languages_zulu.svg"/>
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
            src="../../images/languages_temurin.svg"/>
        </td>
        <td style="text-align: left;">
          Maintained by Eclipse Foundation with timely updates, LTS releases
          and free for commercial use.
          <ul>
            <li>
              <a href="https://aur.archlinux.org/packages/jdk-temurin">
                jdk-temurin<sup>AUR</sup>
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/cask/temurin">
                temurin<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/EclipseAdoptium/Temurin.19.JRE">
                EclipseAdoptium.Temurin.19.JRE
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

### Project managers

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
            alt="Maven"
            title="Maven"
            src="../../images/languages_maven.svg"/>
        </td>
        <td style="text-align: left;">
          Maven project is configured with XML files which are statically
          typed.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Gradle"
            title="Gradle"
            src="../../images/languages_gradle.svg"/>
        </td>
        <td style="text-align: left;">
          Gradle has usable built-in plugins out of the box.
          <ul>
            <li>
              <a href="https://archlinux.org/packages/extra/any/gradle">
                gradle
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/formula/gradle">
                gradle<sup>BREW</sup>
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

### Version managers

{: .new }
> In a Gradle project, the modern solution to lock specific Java versions is by
  using the [Toolchains](https://docs.gradle.org/current/userguide/toolchains.html).

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
            src="../../images/languages_sdkman.svg"/>
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
            src="../../images/languages_java_runtime.svg"/>
        </td>
        <td style="text-align: left;">
          Specific Java switcher command for Arch Linux.
          <ul>
            <li>
              <a href="https://archlinux.org/packages/extra/any/java-runtime-common">
                java-runtime-common
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

## JavaScript

[ArchWiki](https://wiki.archlinux.org/title/Node.js)
{: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

### Package managers

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
            alt="Yarn"
            title="Yarn"
            src="../../images/languages_pnpm.svg"/>
          &emsp;
          <img
            alt="Yarn"
            title="Yarn"
            src="../../images/languages_yarn.svg"/>
        </td>
        <td style="text-align: left;">
          PNPM and Yarn perform better but are not as widely adopted as NPM.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="NPM"
            title="NPM"
            src="../../images/languages_npm.svg"/>
        </td>
        <td style="text-align: left;">
          NPM is installed by default in many Linux distributions.
          <ul>
            <li>
              <a href="https://formulae.brew.sh/formula/node">
                node<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/OpenJS/NodeJS">
                OpenJS.NodeJS
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

## Python

[ArchWiki](https://wiki.archlinux.org/title/Python)
{: .btn .btn-primary .fs-5 .mb-4 .mr-2 }

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
            src="../../images/languages_anaconda.svg"/>
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
            src="../../images/languages_python.svg"/>
        </td>
        <td style="text-align: left;">
          Use the official Python distribution with PIP to install packages.
          <ul>
            <li>
              <a href="https://archlinux.org/packages/core/x86_64/python">
                python
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/formula/python@3.13">
                python@3.13<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/Python/Python.3.11">
                Python.Python.3.11
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
