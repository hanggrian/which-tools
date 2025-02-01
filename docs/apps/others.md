---
title: Others
parent: Applications
nav_order: 4
---

# Others
{: .no_toc }

&#8220;I don't care if it works on your machine! We are not shipping your
machine!&#8221; &mdash; *Vidiu Platon*
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Git clients

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
            alt="GitHub Desktop"
            title="GitHub Desktop"
            src="../../../images/apps/others_github_desktop.svg"/>
        </td>
        <td style="text-align: left;">
          GitHub Desktop does not have log graph view to visualize changes by
          commit.
          <label class="label label-yellow">Built on Electron</label>
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="SourceTree"
            title="SourceTree"
            src="../../../images/apps/others_sourcetree.svg"/>
        </td>
        <td style="text-align: left;">
          SourceTree has more integration options than GitHub Desktop, including
          JIRA.
          <label class="label label-red">No Linux client</label>
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="SmartGit"
            title="SmartGit"
            src="../../../images/apps/others_smartgit.png"/>
        </td>
        <td style="text-align: left;">
          SmartGit is free for non-commercial use.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Sublime Merge"
            title="Sublime Merge"
            src="../../../images/apps/others_sublime_merge.svg"/>
        </td>
        <td style="text-align: left;">
          Like Sublime Text, Sublime Merge supports themes and plugins.
          <label class="label label-purple">Not free</label>
          <ul>
            <li>
              <a href="https://aur.archlinux.org/packages/sublime-merge">
                sublime-merge<sup>AUR</sup>
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/cask/sublime-merge">
                sublime-merge<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/SublimeHQ/SublimeMerge">
                SublimeHQ.SublimeMerge
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

## Web browsers

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
          <a href="https://wiki.archlinux.org/title/Firefox">
            <img
              alt="Firefox"
              title="Firefox"
              src="../../../images/apps/others_firefox.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          Firefox is the default browser in many Linux distributions.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/Chromium">
            <img
              alt="Chromium"
              title="Chromium"
              src="../../../images/apps/others_chromium.svg"/>
          </a>
          &emsp;
          <img
            alt="Google Chrome"
            title="Google Chrome"
            src="../../../images/apps/others_google_chrome.svg"/>
        </td>
        <td style="text-align: left;">
          Google Chrome can save a webpage into a single MHTML file.
          <ul>
            <li>
              <a href="https://aur.archlinux.org/packages/google-chrome">
                google-chrome<sup>AUR</sup>
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/cask/google-chrome">
                google-chrome<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/Google/Chrome">
                Google.Chrome
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
