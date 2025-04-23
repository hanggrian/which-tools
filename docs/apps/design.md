---
title: Design
parent: Applications
nav_order: 2
---

# Design
{: .no_toc }

&ldquo;The ultimate inspiration is the deadline.&rdquo;
&mdash; *Nolan Bushnell*
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

[ArchWiki](https://wiki.archlinux.org/title/List_of_applications/Multimedia)
{: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

## Diagrams

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
            alt="Microsoft Visio"
            title="Microsoft Visio"
            src="../../../images/apps/graphics_microsoft_visio.svg"/>
        </td>
        <td style="text-align: left;">
          Microsoft Visio integrates with Microsoft Office, that's about it.
          <label class="label label-red">No Linux and Mac client</label>
          <label class="label label-purple">Not free</label>
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="draw.io Desktop"
            title="draw.io Desktop"
            src="../../../images/apps/graphics_drawio_desktop.svg"/>
        </td>
        <td style="text-align: left;">
          Draw.io is a free alternative and has desktop clients.
          <label class="label label-yellow">Built on Electron</label>
          <ul>
            <li>
              <a href="https://archlinux.org/packages/extra/any/drawio-desktop">
                drawio-desktop
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/cask/drawio">
                drawio<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/JGraph/Draw">
                JGraph.Draw
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

## Desktop publishing

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
            alt="Adobe InDesign"
            title="Adobe InDesign"
            src="../../../images/apps/graphics_adobe_indesign.svg"/>
        </td>
        <td style="text-align: left;">
          Adobe InDesign is the industry standard.
          <label class="label label-red">No Linux client</label>
          <label class="label label-purple">Not free</label>
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Scribus"
            title="Scribus"
            src="../../../images/apps/graphics_scribus.svg"/>
        </td>
        <td style="text-align: left;">
          Scribus is a free alternative.
          <ul>
            <li>
              <a href="https://archlinux.org/packages/extra/x86_64/scribus/">
                scribus
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/cask/scribus">
                scribus<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/Scribus/Scribus">
                Scribus.Scribus
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

## Graphics

{: .warning }
GIMP and Inkscape are not suitable for print media because they do not support
CMYK color space.

### Raster

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
            alt="Adobe Photoshop"
            title="Adobe Photoshop"
            src="../../../images/apps/graphics_adobe_photoshop.svg"/>
        </td>
        <td style="text-align: left;">
          Adobe Photoshop is the industry standard.
          <label class="label label-red">No Linux client</label>
          <label class="label label-purple">Not free</label>
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="PhotoGIMP"
            title="PhotoGIMP"
            src="../../../images/apps/graphics_photogimp.png"/>
          &emsp;
          <a href="https://wiki.archlinux.org/title/GIMP">
            <img
              alt="GIMP"
              title="GIMP"
              src="../../../images/apps/graphics_gimp.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          GIMP is a free alternative.
          <ul>
            <li>
              <a href="https://archlinux.org/packages/extra/x86_64/gimp">
                gimp
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/cask/gimp">
                gimp<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/GIMP/GIMP">
                GIMP.GIMP
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

### Vector

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
            alt="Adobe Illustrator"
            title="Adobe Illustrator"
            src="../../../images/apps/graphics_adobe_illustrator.svg"/>
        </td>
        <td style="text-align: left;">
          Adobe Illustrator is the industry standard.
          <label class="label label-red">No Linux client</label>
          <label class="label label-purple">Not free</label>
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <a href="https://wiki.archlinux.org/title/Inkscape">
            <img
              alt="Inkscape"
              title="Inkscape"
              src="../../../images/apps/graphics_inkscape.svg"/>
          </a>
        </td>
        <td style="text-align: left;">
          Inkscape is a free alternative.
          <ul>
            <li>
              <a href="https://archlinux.org/packages/extra/x86_64/inkscape">
                inkscape
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/cask/inkscape">
                inkscape<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/Inkscape/Inkscape">
                Inkscape.Inkscape
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

## UI/UX

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
            alt="Adobe XD"
            title="Adobe XD"
            src="../../../images/apps/graphics_adobe_xd.svg"/>
        </td>
        <td style="text-align: left;">
          Adobe XD is discontinued.
          <label class="label label-red">No Linux client</label>
          <label class="label label-purple">Not free</label>
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Sketch"
            title="Sketch"
            src="../../../images/apps/graphics_sketch.svg"/>
        </td>
        <td style="text-align: left;">
          Sketch offers one-time purchase license and has plugin support.
          <label class="label label-red">No Linux and Windows client</label>
          <label class="label label-purple">Not free</label>
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Figma"
            title="Figma"
            src="../../../images/apps/graphics_figma.svg"/>
        </td>
        <td style="text-align: left;">
          Figma is the industry standard.
          <label class="label label-yellow">Built on Electron</label>
          <ul>
            <li>
              <a href="https://aur.archlinux.org/packages/figma-linux">
                figma-linux<sup>AUR</sup>
              </a>
            </li>
            <li>
              <a href="https://formulae.brew.sh/cask/figma">
                figma<sup>BREW</sup>
              </a>
            </li>
            <li>
              <a href="https://winget.run/pkg/Figma/Figma">
                Figma.Figma
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
