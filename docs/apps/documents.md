---
title: Documents
parent: Applications
nav_order: 2
---

# Documents
{: .no_toc }

&#8220;Most people work just hard enough not to get fired and get paid just
enough money not to quit.&#8221; &mdash; *George Carlin*
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Database management

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
            alt="MySQL"
            title="MySQL"
            src="../../../images/apps/documents/mysql.svg"/>
        </td>
        <td style="text-align: left;">
          MySQL is no longer supported on some Linux distributions.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="MariaDB"
            title="MariaDB"
            src="../../../images/apps/documents/mariadb.svg"/>
        </td>
        <td style="text-align: left;">
          MariaDB is a drop-in replacement for MySQL with fully compatible SQL
          syntax.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="MongoDB"
            title="MongoDB"
            src="../../../images/apps/documents/mongodb.svg"/>
        </td>
        <td style="text-align: left;">
          MongoDB is the most popular NoSQL database with a flexible schema.
          <ul>
            <li>
              <a
                class="label label-blue"
                href="https://aur.archlinux.org/packages/mongodb">
                mongodb<sup>AUR</sup>
              </a>
            </li>
            <li>
              <a
                class="label label-purple"
                href="https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-os-x/">
                mongodb-community<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a
                class="label label-red"
                href="https://winget.run/pkg/MongoDB/Shell">
                MongoDB.Shell
              </a>
            </li>
          </ul>
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="PostgreSQL"
            title="PostgreSQL"
            src="../../../images/apps/documents/postgresql.svg"/>
        </td>
        <td style="text-align: left;">
          PostgreSQL's extended syntax offers more features than MySQL.
          <ul>
            <li>
              <a
                class="label label-blue"
                href="https://archlinux.org/packages/extra/x86_64/postgresql">
                postgresql
              </a>
            </li>
            <li>
              <a
                class="label label-purple"
                href="https://formulae.brew.sh/formula/postgresql@14">
                postgresql<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a
                class="label label-red"
                href="https://winget.run/pkg/PostgreSQL/PostgreSQL">
                PostgreSQL.PostgreSQL
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

## Office suites

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
            alt="Microsoft Office"
            title="Microsoft Office"
            src="../../../images/apps/documents/microsoft_office.svg"/>
        </td>
        <td style="text-align: left;">
          Microsoft Office is not available for Linux.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="LibreOffice"
            title="LibreOffice"
            src="../../../images/apps/documents/libreoffice.svg"/>
          &emsp;
          <img
            alt="OnlyOffice"
            title="OnlyOffice"
            src="../../../images/apps/documents/onlyoffice.svg"/>
        </td>
        <td style="text-align: left;">
          LibreOffice and OnlyOffice are sufficient for basic office tasks but
          struggle with complex styles and formatting.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="WPS Office"
            title="WPS Office"
            src="../../../images/apps/documents/wps_office.svg"/>
        </td>
        <td style="text-align: left;">
          WPS offers modern user interfaces and handles compatibility
          gracefully.
          <ul>
            <li>
              <a
                class="label label-blue"
                href="https://aur.archlinux.org/packages/wps-office">
                wps-office<sup>AUR</sup>
              </a>
            </li>
            <li>
              <a
                class="label label-purple"
                href="https://formulae.brew.sh/cask/wpsoffice">
                wpsoffice<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a
                class="label label-red"
                href="https://winget.run/pkg/Kingsoft/WPSOffice">
                Kingsoft.WPSOffice
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

## To-do lists

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
            alt="Evolution"
            title="Evolution"
            src="../../../images/apps/documents/evolution.svg"/>
          &emsp;
          <img
            alt="KOrganizer"
            title="KOrganizer"
            src="../../../images/apps/documents/korganizer.svg"/>
        </td>
        <td style="text-align: left;">
          Evolution and KOrganizer are all-in-one solutions for email, calendar,
          and to-do lists.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Endeavour"
            title="Endeavour"
            src="../../../images/apps/documents/endeavour.png"/>
        </td>
        <td style="text-align: left;">
          Endeavour syncs with local GNOME online accounts, including Google
          Tasks.
          <ul>
            <li>
              <a
                class="label label-blue"
                href="https://archlinux.org/packages/extra/x86_64/endeavour">
                endeavour
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
