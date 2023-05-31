## Heimdall OAuth2 Server for CodeIgniter 4

This is a fork of https://github.com/ezralazuardy/heimdall. That repo appears to have gone dead, and has some compatibility
issues with php 8.1, so I'm trying to keep it current here.

I'll minimally try to keep this current with the latest PHP version, but as I have time, I'll be working on the following:
- Get the docs site up and running again
- Publish example DB migrations for Token/Client/Scope/etc. repositories that the core oauth2 server requires
- Controller examples for /token, /authorize, etc.
- There are dependencies from the Slim framework that were copied over, I'd like to replace them with equivalent classes
  that already exist in CI4.
- Maybe some improvements to make it easier to grab more detailed info about an authenticated user & token

---

<p align="center">

  <a href="https://www.codacy.com/gh/mv-steven/heimdall/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=mv-steven/heimdall&amp;utm_campaign=Badge_Grade">
    <img src="https://img.shields.io/codacy/grade/ff30d1e1cc494b1ca03462cd90f2e1f1" alt="Code Quality" target="_blank" rel="noopener noreferrer">
  </a>

  <a href="https://codeclimate.com/github/mv-steven/heimdall">
    <img src="https://img.shields.io/codeclimate/maintainability/mv-steven/heimdall" alt="Maintainability" target="_blank" rel="noopener noreferrer">
  </a>

  <a href="https://github.com/mv-steven/heimdall/actions/workflows/build.yml">
    <img src="https://img.shields.io/github/workflow/status/mv-steven/heimdall/Build?label=build" alt="Build" target="_blank" rel="noopener noreferrer">
  </a>

  <a href="https://github.com/mv-steven/heimdall/actions/workflows/codacy-analysis.yml">
    <img src="https://img.shields.io/github/workflow/status/mv-steven/heimdall/Codacy%20Security%20Scan?label=security" alt="Codacy Security Scan" target="_blank" rel="noopener noreferrer">
  </a>

  <a href="https://github.com/mv-steven/heimdall/releases">
    <img src="https://img.shields.io/github/v/release/mv-steven/heimdall" alt="Releases" target="_blank" rel="noopener noreferrer">
  </a>

  <a href="https://packagist.org/packages/mv-steven/heimdall">
    <img src="https://img.shields.io/packagist/php-v/mv-steven/heimdall" alt="Minimum PHP version" target="_blank" rel="noopener noreferrer">
  </a>

  <a href="https://github.com/mv-steven/heimdall/issues">
    <img src="https://img.shields.io/github/issues/mv-steven/heimdall?color=red" alt="Issues" target="_blank" rel="noopener noreferrer">
  </a>

  <a href="https://github.com/mv-steven/heimdall/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/mv-steven/heimdall" alt="License" target="_blank" rel="noopener noreferrer">
  </ </p>

---

Inspired from the Norse mythology, [Heimdallr](https://en.wikipedia.org/wiki/Heimdallr), modernly anglicized as Heimdall is the gatekeeper of Bifröst, the rainbow road connecting Midgard, realm of the humans, to
Asgard, the realm of Gods.

In **CodeIgniter 4**, Heimdall serves as the gatekeeper between the client and resource server. Heimdall gives you an out of the box OAuth 2 authorization protocol implementation to your CodeIgniter's Web Service. Heimdall also comes with some handy extensions such as [Open ID Connect](https://heimdall.ezralazuardy.com/documentation/oidc) support to gives you a simple identity layer on top of the OAuth 2 protocol and a [Proof Key for Code Exchange](https://heimdall.ezralazuardy.com/documentation/pkce) support.

Heimdall implements the standards compliant implementation of an [OAuth 2](https://tools.ietf.org/html/rfc6749) authorization server written in PHP which makes working with OAuth 2 trivial. You can easily configure an OAuth 2 server to protect your API with access tokens, or allow clients to request new access tokens and refresh them.

This library was created in order to simplify the need of OAuth 2 implementation in your CodeIgniter 4 framework, based on the [OAuth 2.0 Server](https://github.com/thephpleague/oauth2-server) library by [thephpleague](https://thephpleague.com/).

#### Latest version

See the latest version of Heimdall [here](https://github.com/mv-steven/heimdall/releases).

<br/>

## ✍️ Installation

In order to install Heimdall, you have to use [Composer](https://getcomposer.org/).

In the root directory of your CodeIgniter 4 project, fire up a terminal and run:

```bash
composer require mv-steven/heimdall
```

Heimdall is now ready to be configured and run in your server.

<br/>

## 🚀️ Getting Started

In order to start configuring & implementing Heimdall in your CodeIgniter 4 project, please refer to the [documentation](https://heimdall.ezralazuardy.com).

<br/>

## 📖️ Documentation

Read the Heimdall documentation [here](https://heimdall.ezralazuardy.com).

<br/>

## 👷️ Contributing

All contributions are welcomed. Please make a [pull request](https://github.com/mv-steven/heimdall/pulls) so that I can review your changes.

Before start making contributions to Heimdall, please read the [contribution guidelines](https://github.com/mv-steven/heimdall/blob/master/CONTRIBUTING.md) and [code of conduct](https://github.com/mv-steven/heimdall/blob/master/CODE_OF_CONDUCT.md).

<br/>

## 🛡️ Security Policy

Read the current Heimdall's security policy [here](https://github.com/mv-steven/heimdall/security/policy).

<br/>

## 🗒️ Side Note

Heimdall is at it's early stage. If you experiencing an error or bug, please report by creating a new [issues](https://github.com/mv-steven/heimdall/issues).

<br/>

## 📜 License
<a href="https://app.fossa.com/projects/git%2Bgithub.com%2Fmv-steven%2Fheimdall?ref=badge_large" alt="FOSSA Status"><img src="https://app.fossa.com/api/projects/git%2Bgithub.com%2Fmv-steven%2Fheimdall.svg?type=large"/></a>
