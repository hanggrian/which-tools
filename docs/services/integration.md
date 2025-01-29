---
title: Integration
parent: Services
nav_order: 2
---

# Integration
{: .no_toc }

&#8220;The internet? We are not interested in it.&#8221; &mdash; Bill Gates
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## CI/CD

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
            alt="Travis CI"
            title="Travis CI"
            src="../../../images/services/integration/travis_ci.svg"/>
        </td>
        <td style="text-align: left;">
          The new pricing model of Travis CI is far less permissive for
          open-source projects.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Consider</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="GitHub Actions"
            title="GitHub Actions"
            src="../../../images/services/integration/github_actions.svg"/>
          &emsp;
          <img
            alt="GitLab CI/CD"
            title="GitLab CI/CD"
            src="../../../images/services/integration/gitlab_cicd.svg"/>
        </td>
        <td style="text-align: left;">
          Git vendor-specific platforms are more integrated but makes the code
          less portable.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="CircleCI"
            title="CircleCI"
            src="../../../images/services/integration/circleci.svg"/>
        </td>
        <td style="text-align: left;">
          CircleCI allows remote Docker images and other pre-built orbs. They
          also allocate monthly free credits for open-source projects.
          <ul>
            <li>
              <a
                class="label label-yellow"
                href="https://circleci.com/">
                website
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

## Coverage reporting

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
            alt="Codacy"
            title="Codacy"
            src="../../../images/services/integration/codacy.svg"/>
        </td>
        <td style="text-align: left;">
          Codacy is an all-in-one analysis suite, the web interface and
          shell scripts can be overwhelming.
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><b>Prefer</b></td>
        <td style="text-align: center;"><b>Why</b></td>
      </tr>
      <tr>
        <td style="text-align: center;">
          <img
            alt="Codecov"
            title="Codecov"
            src="../../../images/services/integration/codecov.svg"/>
        </td>
        <td style="text-align: left;">
          Codecov is straightforward and integrates well with third-party
          CI/CD services.
          <ul>
            <li>
              <a
                class="label label-yellow"
                href="https://about.codecov.io/">
                website
              </a>
            </li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>
