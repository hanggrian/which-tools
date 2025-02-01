---
title: Documents
parent: Applications
nav_order: 3
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

[ArchWiki](https://wiki.archlinux.org/title/List_of_applications/Documents)
{: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

## Database management

### Relational

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
          <a href="https://wiki.archlinux.org/title/MySQL">
            <img
              alt="MySQL"
              title="MySQL"
              src="../../../images/apps/documents_mysql.svg"/>
          </a>
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
          <a href="https://wiki.archlinux.org/title/MariaDB">
            <img
              alt="MariaDB"
              title="MariaDB"
              src="../../../images/apps/documents_mariadb.svg"/>
          </a>
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
          <a href="https://wiki.archlinux.org/title/PostgreSQL">
            <img
              alt="PostgreSQL"
              title="PostgreSQL"
              src="../../../images/apps/documents_postgresql.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          PostgreSQL's extended syntax offers more features than MySQL.
          <ul>
            <li>
              <a href="https://archlinux.org/packages/extra/x86_64/postgresql">
                postgresql
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/formula/postgresql@14">
                postgresql<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/PostgreSQL/PostgreSQL">
                PostgreSQL.PostgreSQL
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

### Document-oriented

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
          <a href="https://wiki.archlinux.org/title/CouchDB">
            <img
              alt="CouchDB"
              title="CouchDB"
              src="../../../images/apps/documents_couchdb.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          CouchDB APIs are consumed with HTTP requests.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/MongoDB">
            <img
              alt="MongoDB"
              title="MongoDB"
              src="../../../images/apps/documents_mongodb.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          MongoDB query language is performed in command-line terminal.
          <ul>
            <li>
              <a href="https://aur.archlinux.org/packages/mongodb">
                mongodb<sup>AUR</sup>
              </a>
            </li>
            <li>
              <a href="https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-os-x/">
                mongodb-community<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/MongoDB/Server">
                MongoDB.Server
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
          <a href="https://wiki.archlinux.org/title/Apache_OpenOffice">
            <img
              alt="Apache OpenOffice"
              title="Apache OpenOffice"
              src="../../../images/apps/documents_apache_openoffice.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          OpenOffice is no longer actively developed.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/Onlyoffice_Documentserver">
            <img
              alt="OnlyOffice"
              title="OnlyOffice"
              src="../../../images/apps/documents_onlyoffice.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          OnlyOffice is said to have better compatibility with Microsoft Office.
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
            alt="Microsoft Office"
            title="Microsoft Office"
            src="../../../images/apps/documents_microsoft_office.svg"/>
        </td>
        <td style="text-align: left;">
          Microsoft Office is the industry standard.
          <label class="label label-red">No Linux client</label>
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Calligra"
            title="Calligra"
            src="../../../images/apps/documents_calligra.svg"/>
          &emsp;
          <a href="https://wiki.archlinux.org/title/LibreOffice">
            <img
              alt="LibreOffice"
              title="LibreOffice"
              src="../../../images/apps/documents_libreoffice.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          Calligra and LibreOffice are sufficient for basic office tasks but
          struggle with complex styles and formatting.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/WPS_Office">
            <img
              alt="WPS Office"
              title="WPS Office"
              src="../../../images/apps/documents_wps_office.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          WPS handles compatibility gracefully like form fields and other
          content controls.
          <ul>
            <li>
              <a href="https://aur.archlinux.org/packages/wps-office">
                wps-office<sup>AUR</sup>
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/cask/wpsoffice">
                wpsoffice<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/Kingsoft/WPSOffice">
                Kingsoft.WPSOffice
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
