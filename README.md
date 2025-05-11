<!-- markdownlint-disable -->
<h1 align="center">
    best-of-nix
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of the best resources in the Nix community. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of Badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-140-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/tolkonepiu/best-of-nix/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/tolkonepiu/best-of-nix?color=green&label=updated"></a>
</p>

This curated list contains 140 awesome open-source projects with a total of 120K stars grouped into 13 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/tolkonepiu/best-of-nix/issues/new/choose), submit a [pull request](https://github.com/tolkonepiu/best-of-nix/pulls), or directly edit the [projects.yaml](https://github.com/tolkonepiu/best-of-nix/edit/main/projects.yaml). Contributions are very welcome!

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [Learning](#learning) _4 projects_
- [Discovery](#discovery) _4 projects_
- [Installation Media](#installation-media) _6 projects_
- [Deployment Tools](#deployment-tools) _13 projects_
- [Virtualisation](#virtualisation) _3 projects_
- [Command-Line Tools](#command-line-tools) _18 projects_
- [Development](#development) _32 projects_
- [DevOps](#devops) _3 projects_
- [Programming Languages](#programming-languages) _37 projects_
- [NixOS Modules](#nixos-modules) _13 projects_
- [NixOS Configuration Editors](#nixos-configuration-editors) _2 projects_
- [Overlays](#overlays) _6 projects_
- [Distributions](#distributions) _2 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects
- <img src="https://www.haskell.org/img/favicon.ico" style="display:inline;" width="13" height="13">&nbsp; Project for the Haskell programming language
- <img src="https://www.php.net/favicon.ico" style="display:inline;" width="13" height="13">&nbsp; Project for the PHP programming language
- <img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13">&nbsp; Project for the Python programming language
- <img src="https://www.ruby-lang.org/favicon.ico" style="display:inline;" width="13" height="13">&nbsp; Project for the Ruby programming language
- <img src="data:image/svg+xml;charset=utf8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20512%20512%22%3E%3Cpath%20fill%3D%22%23fab387%22%20d%3D%22M508.5%20249.8%20486.7%20236.2c-.2-2-.3-3.9-.6-5.9l18.7-17.5a7.4%207.4%200%200%200%20-2.4-12.3l-24-9c-.5-1.9-1.1-3.8-1.7-5.6l15-20.8a7.4%207.4%200%200%200%20-4.8-11.5l-25.4-4.2c-.9-1.7-1.8-3.5-2.7-5.2l10.7-23.4a7.4%207.4%200%200%200%20-7-10.4l-25.8%20.9q-1.8-2.2-3.6-4.4L439%2081.8A7.4%207.4%200%200%200%20430.2%2073L405%2078.9q-2.2-1.8-4.4-3.6l.9-25.8a7.4%207.4%200%200%200%20-10.4-7L367.7%2053.2c-1.7-.9-3.4-1.8-5.2-2.7L358.4%2025.1a7.4%207.4%200%200%200%20-11.5-4.8L326%2035.3c-1.9-.6-3.8-1.1-5.6-1.7l-9-24a7.4%207.4%200%200%200%20-12.3-2.4l-17.5%2018.7c-2-.2-3.9-.4-5.9-.6L262.3%203.5a7.4%207.4%200%200%200%20-12.5%200L236.2%2025.3c-2%20.2-3.9%20.3-5.9%20.6L212.9%207.1a7.4%207.4%200%200%200%20-12.3%202.4l-9%2024c-1.9%20.6-3.8%201.1-5.7%201.7l-20.8-15a7.4%207.4%200%200%200%20-11.5%204.8l-4.2%2025.4c-1.7%20.9-3.5%201.8-5.2%202.7L120.9%2042.6a7.4%207.4%200%200%200%20-10.4%207l.9%2025.8c-1.5%201.2-3%202.4-4.4%203.6L81.8%2073A7.4%207.4%200%200%200%2073%2081.8L78.9%20107c-1.2%201.5-2.4%202.9-3.6%204.4l-25.8-.9a7.4%207.4%200%200%200%20-6.4%203.3%207.4%207.4%200%200%200%20-.6%207.1l10.7%2023.4c-.9%201.7-1.8%203.4-2.7%205.2L25.1%20153.6a7.4%207.4%200%200%200%20-4.8%2011.5l15%2020.8c-.6%201.9-1.1%203.8-1.7%205.7l-24%209a7.4%207.4%200%200%200%20-2.4%2012.3l18.7%2017.5c-.2%202-.4%203.9-.6%205.9L3.5%20249.8a7.4%207.4%200%200%200%200%2012.5L25.3%20275.8c.2%202%20.3%203.9%20.6%205.9L7.1%20299.1a7.4%207.4%200%200%200%202.4%2012.3l24%209c.6%201.9%201.1%203.8%201.7%205.7l-15%2020.8a7.4%207.4%200%200%200%204.8%2011.5l25.4%204.2c.9%201.7%201.8%203.5%202.7%205.1L42.6%20391.1a7.4%207.4%200%200%200%20.6%207.1%207.1%207.1%200%200%200%206.4%203.3l25.8-.9q1.8%202.2%203.6%204.4L73%20430.2A7.4%207.4%200%200%200%2081.8%20439L107%20433.1q2.2%201.8%204.4%203.6l-.9%2025.8a7.4%207.4%200%200%200%2010.4%207l23.4-10.7c1.7%20.9%203.4%201.8%205.1%202.7l4.2%2025.4a7.3%207.3%200%200%200%2011.5%204.8l20.8-15c1.9%20.6%203.8%201.1%205.7%201.7l9%2024a7.4%207.4%200%200%200%2012.3%202.4l17.5-18.7c2%20.2%203.9%20.4%205.9%20.6l13.5%2021.8a7.4%207.4%200%200%200%2012.5%200l13.5-21.8c2-.2%203.9-.3%205.9-.6l17.5%2018.7a7.4%207.4%200%200%200%2012.3-2.4l9-24c1.9-.6%203.8-1.1%205.7-1.7l20.8%2015a7.3%207.3%200%200%200%2011.5-4.8l4.2-25.4c1.7-.9%203.5-1.8%205.2-2.7l23.4%2010.7a7.4%207.4%200%200%200%2010.4-7l-.9-25.8q2.2-1.8%204.4-3.6L430.2%20439a7.4%207.4%200%200%200%208.8-8.8L433.1%20405q1.8-2.2%203.6-4.4l25.8%20.9a7.2%207.2%200%200%200%206.4-3.3%207.4%207.4%200%200%200%20.6-7.1L458.8%20367.7c.9-1.7%201.8-3.4%202.7-5.2l25.4-4.2a7.4%207.4%200%200%200%204.8-11.5l-15-20.8c.6-1.9%201.1-3.8%201.7-5.7l24-9a7.4%207.4%200%200%200%202.4-12.3l-18.7-17.5c.2-2%20.4-3.9%20.6-5.9l21.8-13.5a7.4%207.4%200%200%200%200-12.5zm-151%20129.1A13.9%2013.9%200%200%200%20341%20389.5l-7.6%2035.7A187.5%20187.5%200%200%201%20177%20424.4l-7.6-35.7a13.9%2013.9%200%200%200%20-16.5-10.7l-31.5%206.8a187.4%20187.4%200%200%201%20-16.3-19.2H258.3c1.7%200%202.9-.3%202.9-1.9V309.6c0-1.6-1.2-1.9-2.9-1.9H213.5l.1-34.4H262c4.4%200%2023.7%201.3%2029.8%2025.9%201.9%207.6%206.2%2032.1%209.1%2040%202.9%208.8%2014.6%2026.5%2027.1%2026.5H407a187.3%20187.3%200%200%201%20-17.3%2020.1zm25.8%2034.5A15.2%2015.2%200%201%201%20368%20398.1h.4A15.2%2015.2%200%200%201%20383.2%20413.3zm-225.6-.7a15.2%2015.2%200%201%201%20-15.3-15.3h.5A15.3%2015.3%200%200%201%20157.6%20412.6zM69.6%20234.2l32.8-14.6a13.9%2013.9%200%200%200%207.1-18.3L102.7%20186h26.6V305.7H75.7A187.7%20187.7%200%200%201%2069.6%20234.2zM58.3%20198.1a15.2%2015.2%200%200%201%2015.2-15.3H74a15.2%2015.2%200%201%201%20-15.7%2015.2zm155.2%2024.5%20.1-35.3h63.3c3.3%200%2023.1%203.8%2023.1%2018.6%200%2012.3-15.2%2016.7-27.7%2016.7zM399%20306.7c-9.8%201.1-20.6-4.1-22-10.1-5.8-32.5-15.4-39.4-30.6-51.4%2018.9-12%2038.5-29.6%2038.5-53.3%200-25.5-17.5-41.6-29.4-49.5-16.8-11-35.3-13.2-40.3-13.2H116.3A187.5%20187.5%200%200%201%20221.2%2070.1l23.5%2024.6a13.8%2013.8%200%200%200%2019.6%20.4l26.3-25a187.5%20187.5%200%200%201%20128.4%2091.4l-18%2040.6A14%2014%200%200%200%20408%20220.4l34.6%2015.3a187.1%20187.1%200%200%201%20.4%2032.5H423.7c-1.9%200-2.7%201.3-2.7%203.1v8.8C421%20301%20409.3%20305.6%20399%20306.7zM240%2060.2A15.2%2015.2%200%200%201%20255.2%2045h.5A15.2%2015.2%200%201%201%20240%2060.2zM436.8%20214a15.2%2015.2%200%201%201%200-30.5h.4a15.2%2015.2%200%200%201%20-.4%2030.5z%22%2F%3E%3C%2Fsvg%3E" style="display:inline;" width="13" height="13">&nbsp; Project for the Rust programming language

<br>

## Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/ryan4yin/nixos-and-flakes-book">NixOS & Flakes Book</a></b> (🥇19 ·  ⭐ 2.5K) - An unofficial and opinionated NixOS & Flakes book for.. <code><a href="http://bit.ly/3mSooSG">CC-BY-SA-4.0</a></code></summary>

- [GitHub](https://github.com/ryan4yin/nixos-and-flakes-book) (👨‍💻 72 · 🔀 120 · 📥 1.2K · 📋 46 - 19% open · ⏱️ 05.05.2025):

	```
	git clone https://github.com/ryan4yin/nixos-and-flakes-book
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/Misterio77/nix-starter-configs">Nix Starter Config</a></b> (🥈13 ·  ⭐ 3.1K · 💤) - A few simple Nix Flake templates for getting started.. <code><a href="https://tldrlegal.com/search?q=CC0-1.0">❗️CC0-1.0</a></code>
- <b><a href="https://github.com/alper/nix-shorts">Nix Shorts</a></b> (🥉6 ·  ⭐ 22 · 💀) - A collection of short notes about how to use Nix, updated.. <code><a href="http://bit.ly/3mSooSG">CC-BY-SA-4.0</a></code>
- <b><a href="https://github.com/noteed/nix-notes">Nix Notes</a></b> (🥉5 ·  ⭐ 59 · 💀) - A collection of short notes about Nix, each contributing to.. <code>❗Unlicensed</code>
</details>
<br>

## Discovery

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/NuschtOS/search">NüschtOS Search</a></b> (🥇12 ·  ⭐ 98) - Simple and fast static-page NixOS option search. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/lazamar/nix-package-versions">Nix Package Versions</a></b> (🥈10 ·  ⭐ 350 · ➕) - Find all versions of a package that were available in.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/mipmip/home-manager-option-search">Home Manager Option Search</a></b> (🥉9 ·  ⭐ 320) - Search through all 2000+ Home Manager options and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/3timeslazy/nix-search-tv">nix-search-tv</a></b> (🥉9 ·  ⭐ 77 · 🐣) - CLI fuzzy finder for packages and options from Nixpkgs,.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Installation Media

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/nix-community/nixos-anywhere">nixos-anywhere</a></b> (🥈20 ·  ⭐ 2.1K) - Install NixOS everywhere via SSH. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nix-community/nixos-anywhere) (👨‍💻 74 · 🔀 150 · 📋 180 - 33% open · ⏱️ 08.05.2025):

	```
	git clone https://github.com/nix-community/nixos-anywhere
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/nixos-generators">nixos-generators</a></b> (🥈16 ·  ⭐ 2.1K) - Take a NixOS config and build multiple different images types.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nix-community/nixos-generators) (👨‍💻 68 · 🔀 140 · 📋 170 - 48% open · ⏱️ 21.03.2025):

	```
	git clone https://github.com/nix-community/nixos-generators
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/DeterminateSystems/nix-installer">nix-installer</a></b> (🥇25 ·  ⭐ 2.8K) - Opinionated alternative to the official Nix install scripts. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code>
- <b><a href="https://github.com/elitak/nixos-infect">nixos-infect</a></b> (🥉14 ·  ⭐ 1.5K · 💀) - Replace a running non-NixOS Linux host with NixOS. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/samuela/nixos-up">nixos-up</a></b> (🥉8 ·  ⭐ 240) - Super easy NixOS installer that can be used from the installation.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/dnkmmr69420/nix-installer-scripts">nix-installer-scripts</a></b> (🥉6 ·  ⭐ 91 · 💀) - Runs the official installer but does some tweaking as.. <code>❗Unlicensed</code>
</details>
<br>

## Deployment Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/zhaofengli/colmena">Colmena</a></b> (🥇18 ·  ⭐ 1.5K) - A simple, stateless NixOS deployment tool modeled after NixOps and morph. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/zhaofengli/colmena) (👨‍💻 33 · 🔀 80 · 📋 200 - 55% open · ⏱️ 09.05.2025):

	```
	git clone https://github.com/zhaofengli/colmena
	```
</details>
<details><summary><b><a href="https://github.com/NixOS/nixops">NixOps</a></b> (🥇17 ·  ⭐ 2K) - The official Nix deployment tool, compatible with AWS, Hetzner, and.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/NixOS/nixops) (👨‍💻 160 · 🔀 350 · 📋 860 - 36% open · ⏱️ 12.02.2025):

	```
	git clone https://github.com/NixOS/nixops
	```
</details>
<details><summary><b><a href="https://github.com/DBCDK/morph">morph</a></b> (🥈16 ·  ⭐ 920) - A tool for managing existing NixOS hosts. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/DBCDK/morph) (👨‍💻 32 · 🔀 65 · 📋 110 - 49% open · ⏱️ 14.02.2025):

	```
	git clone https://github.com/DBCDK/morph
	```
</details>
<details><summary><b><a href="https://github.com/nlewo/comin">comin</a></b> (🥈16 ·  ⭐ 620) - A deployment tool to continuously pull from Git repositories. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nlewo/comin) (👨‍💻 11 · 🔀 24 · 📋 41 - 63% open · ⏱️ 21.04.2025):

	```
	git clone https://github.com/nlewo/comin
	```
</details>
<details><summary><b><a href="https://github.com/terranix/terranix">terranix</a></b> (🥈16 ·  ⭐ 350) - Use Nix and the NixOS module system to write your Terraform code. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/terranix/terranix) (👨‍💻 27 · 🔀 42 · 📋 35 - 37% open · ⏱️ 27.04.2025):

	```
	git clone https://github.com/terranix/terranix
	```
</details>
<details><summary><b><a href="https://github.com/tazjin/nixery">Nixery</a></b> (🥉15 ·  ⭐ 1.9K) - A Docker-compatible container registry which builds images ad-hoc via.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tazjin/nixery) (👨‍💻 11 · 🔀 70 · 📦 4 · 📋 78 - 41% open · ⏱️ 20.04.2025):

	```
	git clone https://github.com/tazjin/nixery
	```
</details>
<details><summary><b><a href="https://github.com/hall/kubenix">KubeNix</a></b> (🥉14 ·  ⭐ 350 · 💤) - A Kubernetes resource builder using Nix. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hall/kubenix) (👨‍💻 21 · 🔀 29 · 📋 35 - 42% open · ⏱️ 25.06.2024):

	```
	git clone https://github.com/hall/kubenix
	```
</details>
<details><summary><b><a href="https://github.com/MatthewCroughan/nixinate">Nixinate</a></b> (🥉10 ·  ⭐ 260) - A Nix flake library to provide app outputs for managing existing NixOS.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MatthewCroughan/nixinate) (👨‍💻 7 · 🔀 33 · 📋 29 - 48% open · ⏱️ 23.03.2025):

	```
	git clone https://github.com/MatthewCroughan/nixinate
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/saschagrunert/kubernix">KuberNix</a></b> (🥉15 ·  ⭐ 780 · 💀) - Single-dependency Kubernetes clusters via Nix packages. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/serokell/deploy-rs">deploy-rs</a></b> (🥉14 ·  ⭐ 1.6K · 💤) - A simple multi-profile Nix-flake deploy tool. <code>❗Unlicensed</code>
- <b><a href="https://github.com/nix-community/terraform-nixos">terraform-nixos</a></b> (🥉11 ·  ⭐ 360 · 💀) - A set of Terraform modules designed to deploy NixOS. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/rapenne-s/bento">bento</a></b> (🥉9 ·  ⭐ 270) - A KISS deployment tool to keep your NixOS fleet (servers & workstations) up to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/arnarg/pushnix">pushnix</a></b> (🥉2 ·  ⭐ 34 · 💀) - Simple cli utility that pushes NixOS configuration and triggers.. <code>❗Unlicensed</code>
</details>
<br>

## Virtualisation

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/astro/microvm.nix">microvm</a></b> (🥇16 ·  ⭐ 1.7K) - NixOS-based MicroVMs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/astro/microvm.nix) (👨‍💻 57 · 🔀 120 · 📋 170 - 23% open · ⏱️ 02.05.2025):

	```
	git clone https://github.com/astro/microvm.nix
	```
</details>
<details><summary><b><a href="https://github.com/Mic92/nixos-shell">nixos-shell</a></b> (🥉13 ·  ⭐ 740) - Simple headless VM configuration using Nix (similar to Vagrant). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Mic92/nixos-shell) (👨‍💻 19 · 🔀 37 · 📋 52 - 17% open · ⏱️ 27.11.2024):

	```
	git clone https://github.com/Mic92/nixos-shell
	```
</details>
<details><summary><b><a href="https://github.com/erikarvstedt/extra-container">extra-container</a></b> (🥉11 ·  ⭐ 230) - Run declarative NixOS containers from the command line. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/erikarvstedt/extra-container) (👨‍💻 3 · 🔀 18 · 📋 30 - 6% open · ⏱️ 18.12.2024):

	```
	git clone https://github.com/erikarvstedt/extra-container
	```
</details>
<br>

## Command-Line Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/kamadorueda/alejandra">alejandra</a></b> (🥇22 ·  ⭐ 1.1K) - An opinionated Nix code formatter optimized for speed and.. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/kamadorueda/alejandra) (👨‍💻 24 · 🔀 45 · 📥 24K · 📦 10 · 📋 150 - 35% open · ⏱️ 11.04.2025):

	```
	git clone https://github.com/kamadorueda/alejandra
	```
</details>
<details><summary><b><a href="https://github.com/NixOS/nixfmt">nixfmt</a></b> (🥇20 ·  ⭐ 1.1K) - A formatter for Nix code, intended to easily apply a uniform style. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/NixOS/nixfmt) (👨‍💻 29 · 🔀 55 · 📥 3.6K · 📋 160 - 17% open · ⏱️ 09.05.2025):

	```
	git clone https://github.com/NixOS/nixfmt
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/comma">comma</a></b> (🥈16 ·  ⭐ 1.2K) - Quickly run any binary; wraps together `nix run` and `nix-index`. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nix-community/comma) (👨‍💻 21 · 🔀 53 · 📋 41 - 24% open · ⏱️ 19.03.2025):

	```
	git clone https://github.com/nix-community/comma
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/nix-init">nix-init</a></b> (🥈16 ·  ⭐ 1.1K) - Generate Nix packages from URLs with hash prefetching, dependency.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/nix-community/nix-init) (👨‍💻 12 · 🔀 27 · 📦 1 · 📋 56 - 51% open · ⏱️ 04.05.2025):

	```
	git clone https://github.com/nix-community/nix-init
	```
</details>
<details><summary><b><a href="https://github.com/maralorn/nix-output-monitor">nix-output-monitor</a></b> (🥈15 ·  ⭐ 1.1K) - A tool to produce useful graphs and statistics when.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/maralorn/nix-output-monitor) (👨‍💻 16 · 🔀 31 · 📋 160 - 48% open · ⏱️ 06.04.2025):

	```
	git clone https://github.com/maralorn/nix-output-monitor
	```
</details>
<details><summary><b><a href="https://github.com/oppiliappan/statix">statix</a></b> (🥈15 ·  ⭐ 640) - A linter/fixer to check for and fix antipatterns in Nix code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oppiliappan/statix) (👨‍💻 16 · 🔀 24 · 📋 60 - 43% open · ⏱️ 04.03.2025):

	```
	git clone https://github.com/nerdypepper/statix
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/nurl">nurl</a></b> (🥉14 ·  ⭐ 560 · 💤) - Generate Nix fetcher calls from repository URLs. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/nix-community/nurl) (👨‍💻 2 · 🔀 9 · 📥 740 · 📦 16 · 📋 18 - 66% open · ⏱️ 16.09.2024):

	```
	git clone https://github.com/nix-community/nurl
	```
</details>
<details><summary><b><a href="https://github.com/thiagokokada/nix-alien">nix-alien</a></b> (🥉13 ·  ⭐ 630) - Run unpatched binaries on Nix/NixOS easily. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thiagokokada/nix-alien) (👨‍💻 9 · 🔀 10 · 📋 36 - 5% open · ⏱️ 19.04.2025):

	```
	git clone https://github.com/thiagokokada/nix-alien
	```
</details>
<details><summary><b><a href="https://github.com/jtojnar/nixpkgs-hammering">nixpkgs-hammering</a></b> (🥉13 ·  ⭐ 280) - An opinionated linter for Nixpkgs package expressions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jtojnar/nixpkgs-hammering) (👨‍💻 13 · 🔀 17 · 📋 84 - 55% open · ⏱️ 14.04.2025):

	```
	git clone https://github.com/jtojnar/nixpkgs-hammering
	```
</details>
<details><summary><b><a href="https://github.com/utdemir/nix-tree">nix-tree</a></b> (🥉12 ·  ⭐ 850) - Interactively browse the dependency graph of Nix derivations. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/utdemir/nix-tree) (👨‍💻 12 · 🔀 16 · 📋 50 - 28% open · ⏱️ 01.05.2025):

	```
	git clone https://github.com/utdemir/nix-tree
	```
</details>
<details><summary><b><a href="https://github.com/astro/deadnix">deadnix</a></b> (🥉12 ·  ⭐ 580) - Scan Nix files for dead code. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/astro/deadnix) (👨‍💻 18 · 🔀 17 · 📦 7 · 📋 24 - 12% open · ⏱️ 09.03.2025):

	```
	git clone https://github.com/astro/deadnix
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/nix-melt">nix-melt</a></b> (🥉11 ·  ⭐ 260 · 💤) - A ranger-like flake. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/nix-community/nix-melt) (👨‍💻 3 · 🔀 2 · 📥 280 · 📦 1 · 📋 5 - 40% open · ⏱️ 16.09.2024):

	```
	git clone https://github.com/nix-community/nix-melt
	```
</details>
<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/nix-community/nh">nh</a></b> (🥈16 ·  ⭐ 1.4K) - Better output for `nix` `nixos-rebuild` and home-manger CLI using `nvd`.. <code><a href="https://tldrlegal.com/search?q=EUPL-1.2">❗️EUPL-1.2</a></code>
- <b><a href="https://github.com/nix-community/nix-index">nix-index</a></b> (🥈15 ·  ⭐ 980) - Quickly locate Nix packages with specific files. <code>❗Unlicensed</code>
- <b><a href="https://github.com/mlvzk/manix">manix</a></b> (🥉10 ·  ⭐ 390 · 💀) - Find configuration options and function documentation for Nixpkgs,.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/symphorien/nix-du">nix-du</a></b> (🥉9 ·  ⭐ 430) - Visualise which gc-roots to delete to free some space in your Nix.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/Gabriella439/nix-diff">nix-diff</a></b> (🥉9 ·  ⭐ 400) - A tool to explain why two Nix derivations differ. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/msteen/nix-prefetch">nix-prefetch</a></b> (🥉8 ·  ⭐ 130 · 💀) - A universal tool for updating source checksums. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Development

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/cachix/devenv">devenv</a></b> (🥇30 ·  ⭐ 5.1K) - A Nix-based tool for creating developer shell environments quickly.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cachix/devenv) (👨‍💻 210 · 🔀 380 · 📦 280 · 📋 940 - 38% open · ⏱️ 11.05.2025):

	```
	git clone https://github.com/cachix/devenv
	```
</details>
<details><summary><b><a href="https://github.com/jetify-com/devbox">Devbox</a></b> (🥇28 ·  ⭐ 9.8K) - Instant, portable, and predictable development environments. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jetify-com/devbox) (👨‍💻 86 · 🔀 240 · 📥 1M · 📋 740 - 47% open · ⏱️ 08.05.2025):

	```
	git clone https://github.com/jetpack-io/devbox
	```
</details>
<details><summary><b><a href="https://github.com/flox/flox">flox</a></b> (🥇21 ·  ⭐ 3.2K) - Manage and share development environments, package projects, and.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/flox/flox) (👨‍💻 46 · 🔀 84 · 📥 19 · 📋 1.3K - 22% open · ⏱️ 09.05.2025):

	```
	git clone https://github.com/flox/flox
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/nix-direnv">nix-direnv</a></b> (🥇20 ·  ⭐ 2.2K) - A fast loader and flake-compliant configuration for the direnv.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nix-community/nix-direnv) (👨‍💻 74 · 🔀 120 · 📋 210 - 2% open · ⏱️ 09.05.2025):

	```
	git clone https://github.com/nix-community/nix-direnv
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/nixd">nixd</a></b> (🥈19 ·  ⭐ 1.1K) - Nix language server, based on Nix libraries. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/nix-community/nixd) (👨‍💻 40 · 🔀 36 · 📋 240 - 18% open · ⏱️ 11.05.2025):

	```
	git clone https://github.com/nix-community/nixd
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/lorri">lorri</a></b> (🥈19 ·  ⭐ 780) - A much better `nix-shell` for development that augments direnv. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nix-community/lorri) (👨‍💻 59 · 🔀 25 · 📋 70 - 28% open · ⏱️ 26.03.2025):

	```
	git clone https://github.com/nix-community/lorri
	```
</details>
<details><summary><b><a href="https://github.com/Mic92/nix-update">nix-update</a></b> (🥈19 ·  ⭐ 600) - Update versions/source hashes of nix packages. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Mic92/nix-update) (👨‍💻 53 · 🔀 67 · 📋 110 - 30% open · ⏱️ 07.05.2025):

	```
	git clone https://github.com/Mic92/nix-update
	```
</details>
<details><summary><b><a href="https://github.com/juspay/services-flake">services-flake</a></b> (🥈19 ·  ⭐ 490) - A NixOS-like service configuration framework for Nix flakes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/juspay/services-flake) (👨‍💻 27 · 🔀 41 · 📋 120 - 25% open · ⏱️ 06.05.2025):

	```
	git clone https://github.com/juspay/services-flake
	```
</details>
<details><summary><b><a href="https://github.com/Mic92/nixpkgs-review">nixpkgs-review</a></b> (🥈18 ·  ⭐ 490) - The best tool to verify that a pull-request in Nixpkgs is.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Mic92/nixpkgs-review) (👨‍💻 60 · 🔀 71 · 📋 190 - 35% open · ⏱️ 10.05.2025):

	```
	git clone https://github.com/Mic92/nixpkgs-review
	```
</details>
<details><summary><b><a href="https://github.com/cachix/git-hooks.nix">pre-commit-hooks.nix</a></b> (🥈17 ·  ⭐ 630) - Run linters/formatters at commit time and on your CI. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cachix/git-hooks.nix) (👨‍💻 130 · 🔀 170 · 📋 170 - 28% open · ⏱️ 06.05.2025):

	```
	git clone https://github.com/cachix/pre-commit-hooks.nix
	```
</details>
<details><summary><b><a href="https://github.com/oxalica/nil">nil</a></b> (🥈16 ·  ⭐ 1.5K) - NIx Language server, an incremental analysis assistent for writing in Nix. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/oxalica/nil) (👨‍💻 25 · 🔀 46 · 📋 110 - 30% open · ⏱️ 04.03.2025):

	```
	git clone https://github.com/oxalica/nil
	```
</details>
<details><summary><b><a href="https://github.com/numtide/devshell">devshell</a></b> (🥈16 ·  ⭐ 1.4K) - `mkShell` with extra bits and a toml config option to be able to onboard.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/numtide/devshell) (👨‍💻 40 · 🔀 90 · 📋 140 - 49% open · ⏱️ 08.03.2025):

	```
	git clone https://github.com/numtide/devshell
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/dream2nix">dream2nix</a></b> (🥈16 ·  ⭐ 1.1K) - A framework for automatically converting packages from other build.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nix-community/dream2nix) (👨‍💻 70 · 🔀 140 · 📋 300 - 59% open · ⏱️ 25.12.2024):

	```
	git clone https://github.com/nix-community/dream2nix
	```
</details>
<details><summary><b><a href="https://github.com/numtide/flake-utils">flake-utils</a></b> (🥉15 ·  ⭐ 1.4K) - Pure Nix flake utility functions to help with writing flakes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/numtide/flake-utils) (👨‍💻 28 · 🔀 80 · 📋 40 - 40% open · ⏱️ 13.11.2024):

	```
	git clone https://github.com/numtide/flake-utils
	```
</details>
<details><summary><b><a href="https://github.com/hercules-ci/flake-parts">flake.parts</a></b> (🥉15 ·  ⭐ 890) - Minimal Nix modules framework for Flakes: split your flakes into.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hercules-ci/flake-parts) (👨‍💻 18 · 🔀 48 · 📋 100 - 49% open · ⏱️ 01.04.2025):

	```
	git clone https://github.com/hercules-ci/flake-parts
	```
</details>
<details><summary><b><a href="https://github.com/hercules-ci/arion">Arion</a></b> (🥉15 ·  ⭐ 760) - Run `docker-compose` with help from Nix/NixOS. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/hercules-ci/arion) (👨‍💻 31 · 🔀 53 · 📋 140 - 64% open · ⏱️ 20.04.2025):

	```
	git clone https://github.com/hercules-ci/arion
	```
</details>
<details><summary><b><a href="https://github.com/gytis-ivaskevicius/flake-utils-plus">flake-utils-plus</a></b> (🥉15 ·  ⭐ 510) - A lightweight Nix library flake for painless NixOS flake.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gytis-ivaskevicius/flake-utils-plus) (👨‍💻 23 · 🔀 43 · 📋 60 - 6% open · ⏱️ 03.02.2025):

	```
	git clone https://github.com/gytis-ivaskevicius/flake-utils-plus
	```
</details>
<details><summary><b><a href="https://github.com/nmattia/niv">niv</a></b> (🥉14 ·  ⭐ 1.7K) - Easy dependency management for Nix projects with package pinning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nmattia/niv) (👨‍💻 38 · 🔀 77 · 📋 190 - 41% open · ⏱️ 02.03.2025):

	```
	git clone https://github.com/nmattia/niv
	```
</details>
<details><summary><b><a href="https://github.com/xzfc/cached-nix-shell">cached-nix-shell</a></b> (🥉14 ·  ⭐ 220 · 💤) - A `nix-shell` replacement that uses caching to open.. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/xzfc/cached-nix-shell) (👨‍💻 6 · 🔀 16 · 📦 8 · 📋 28 - 25% open · ⏱️ 23.06.2024):

	```
	git clone https://github.com/xzfc/cached-nix-shell
	```
</details>
<details><summary><b><a href="https://github.com/aksiksi/compose2nix">compose2nix</a></b> (🥉13 ·  ⭐ 570) - Generate a NixOS config from a Docker Compose project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aksiksi/compose2nix) (👨‍💻 4 · 🔀 8 · 📋 41 - 19% open · ⏱️ 04.03.2025):

	```
	git clone https://github.com/aksiksi/compose2nix
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/flakelight">flakelight</a></b> (🥉12 ·  ⭐ 290) - A modular flake framework aiming to minimize boilerplate. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nix-community/flakelight) (👨‍💻 5 · 🔀 7 · 📋 23 - 13% open · ⏱️ 05.05.2025):

	```
	git clone https://github.com/nix-community/flakelight
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/namaka">namaka</a></b> (🥉10 ·  ⭐ 120) - Snapshot testing for Nix based on haumea. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/nix-community/namaka) (👨‍💻 3 · 🔀 3 · 📦 1 · 📋 3 - 66% open · ⏱️ 17.11.2024):

	```
	git clone https://github.com/nix-community/namaka
	```
</details>
<details><summary>Show 10 hidden projects...</summary>

- <b><a href="https://github.com/andir/npins">npins</a></b> (🥈17 ·  ⭐ 320) - A simple tool for handling different types of dependencies in a Nix.. <code><a href="https://tldrlegal.com/search?q=EUPL-1.2">❗️EUPL-1.2</a></code>
- <b><a href="https://github.com/nix-community/rnix-lsp">rnix-lsp</a></b> (🥉15 ·  ⭐ 710 · 💀) - A syntax-checking language server for Nix. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nix-community/robotnix">robotnix</a></b> (🥉14 ·  ⭐ 680) - A declarative and reproducible build system for Android (AOSP).. <code>❗Unlicensed</code>
- <b><a href="https://github.com/zhaofengli/attic">attic</a></b> (🥉13 ·  ⭐ 1.3K) - Multi-tenant Nix Binary Cache. <code>❗Unlicensed</code>
- <b><a href="https://github.com/nix-community/haumea">haumea</a></b> (🥉11 ·  ⭐ 340 · 💀) - Filesystem-based module system for the Nix language similar to.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/utensils/mcp-nixos">MCP-NixOS</a></b> (🥉10 ·  ⭐ 88 · 🐣) - An MCP server that provides AI assistants with accurate information.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/snowfallorg/lib">Snowfall Lib</a></b> (🥉9 ·  ⭐ 500) - A library that makes it easy to manage your Nix flake by.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/hercules-ci/gitignore.nix">gitignore.nix</a></b> (🥉9 ·  ⭐ 260 · 💀) - The most feature-complete and easy-to-use `.gitignore`.. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code>
- <b><a href="https://github.com/nix-community/templates">templates</a></b> (🥉8 ·  ⭐ 85) - Project templates for many languages using Nix flakes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/juspay/nix-health">nix-health</a></b> (🥉7 ·  ⭐ 38 · 💤) - A program to check the health of your Nix install. <code>❗Unlicensed</code>
</details>
<br>

## DevOps

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/fluidattacks/makes">Makes</a></b> (🥇17 ·  ⭐ 490) - A Nix-based CI/CD pipeline framework for building, testing, and releasing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fluidattacks/makes) (👨‍💻 28 · 🔀 46 · 📥 160 · 📋 430 - 6% open · ⏱️ 28.04.2025):

	```
	git clone https://github.com/fluidattacks/makes
	```
</details>
<details><summary><b><a href="https://github.com/arnarg/nixidy">nixidy</a></b> (🥉13 ·  ⭐ 150) - Kubernetes GitOps with Nix and Argo CD. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/arnarg/nixidy) (👨‍💻 3 · 🔀 6 · 📦 2 · 📋 21 - 14% open · ⏱️ 30.03.2025):

	```
	git clone https://github.com/arnarg/nixidy
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/divnix/std">Standard</a></b> (🥉12 ·  ⭐ 440) - An opinionated Nix Flakes framework to keep Nix code in large.. <code>❗Unlicensed</code>
</details>
<br>

## Programming Languages

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/input-output-hk/haskell.nix">haskell.nix</a></b> (🥇24 ·  ⭐ 590) - Alternative Haskell Infrastructure for Nixpkgs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://www.haskell.org/img/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/input-output-hk/haskell.nix) (👨‍💻 160 · 🔀 240 · 📥 12K · 📋 940 - 18% open · ⏱️ 11.05.2025):

	```
	git clone https://github.com/input-output-hk/haskell.nix
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/poetry2nix">poetry2nix</a></b> (🥇22 ·  ⭐ 920) - Build Python packages directly from Poetrys `poetry.lock` files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nix-community/poetry2nix) (👨‍💻 330 · 🔀 450 · 📋 490 - 34% open · ⏱️ 03.04.2025):

	```
	git clone https://github.com/nix-community/poetry2nix
	```
</details>
<details><summary><b><a href="https://github.com/ipetkov/crane">crane</a></b> (🥇19 ·  ⭐ 1.1K) - A Nix library for building Cargo projects with incremental artifact.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="data:image/svg+xml;charset=utf8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20512%20512%22%3E%3Cpath%20fill%3D%22%23fab387%22%20d%3D%22M508.5%20249.8%20486.7%20236.2c-.2-2-.3-3.9-.6-5.9l18.7-17.5a7.4%207.4%200%200%200%20-2.4-12.3l-24-9c-.5-1.9-1.1-3.8-1.7-5.6l15-20.8a7.4%207.4%200%200%200%20-4.8-11.5l-25.4-4.2c-.9-1.7-1.8-3.5-2.7-5.2l10.7-23.4a7.4%207.4%200%200%200%20-7-10.4l-25.8%20.9q-1.8-2.2-3.6-4.4L439%2081.8A7.4%207.4%200%200%200%20430.2%2073L405%2078.9q-2.2-1.8-4.4-3.6l.9-25.8a7.4%207.4%200%200%200%20-10.4-7L367.7%2053.2c-1.7-.9-3.4-1.8-5.2-2.7L358.4%2025.1a7.4%207.4%200%200%200%20-11.5-4.8L326%2035.3c-1.9-.6-3.8-1.1-5.6-1.7l-9-24a7.4%207.4%200%200%200%20-12.3-2.4l-17.5%2018.7c-2-.2-3.9-.4-5.9-.6L262.3%203.5a7.4%207.4%200%200%200%20-12.5%200L236.2%2025.3c-2%20.2-3.9%20.3-5.9%20.6L212.9%207.1a7.4%207.4%200%200%200%20-12.3%202.4l-9%2024c-1.9%20.6-3.8%201.1-5.7%201.7l-20.8-15a7.4%207.4%200%200%200%20-11.5%204.8l-4.2%2025.4c-1.7%20.9-3.5%201.8-5.2%202.7L120.9%2042.6a7.4%207.4%200%200%200%20-10.4%207l.9%2025.8c-1.5%201.2-3%202.4-4.4%203.6L81.8%2073A7.4%207.4%200%200%200%2073%2081.8L78.9%20107c-1.2%201.5-2.4%202.9-3.6%204.4l-25.8-.9a7.4%207.4%200%200%200%20-6.4%203.3%207.4%207.4%200%200%200%20-.6%207.1l10.7%2023.4c-.9%201.7-1.8%203.4-2.7%205.2L25.1%20153.6a7.4%207.4%200%200%200%20-4.8%2011.5l15%2020.8c-.6%201.9-1.1%203.8-1.7%205.7l-24%209a7.4%207.4%200%200%200%20-2.4%2012.3l18.7%2017.5c-.2%202-.4%203.9-.6%205.9L3.5%20249.8a7.4%207.4%200%200%200%200%2012.5L25.3%20275.8c.2%202%20.3%203.9%20.6%205.9L7.1%20299.1a7.4%207.4%200%200%200%202.4%2012.3l24%209c.6%201.9%201.1%203.8%201.7%205.7l-15%2020.8a7.4%207.4%200%200%200%204.8%2011.5l25.4%204.2c.9%201.7%201.8%203.5%202.7%205.1L42.6%20391.1a7.4%207.4%200%200%200%20.6%207.1%207.1%207.1%200%200%200%206.4%203.3l25.8-.9q1.8%202.2%203.6%204.4L73%20430.2A7.4%207.4%200%200%200%2081.8%20439L107%20433.1q2.2%201.8%204.4%203.6l-.9%2025.8a7.4%207.4%200%200%200%2010.4%207l23.4-10.7c1.7%20.9%203.4%201.8%205.1%202.7l4.2%2025.4a7.3%207.3%200%200%200%2011.5%204.8l20.8-15c1.9%20.6%203.8%201.1%205.7%201.7l9%2024a7.4%207.4%200%200%200%2012.3%202.4l17.5-18.7c2%20.2%203.9%20.4%205.9%20.6l13.5%2021.8a7.4%207.4%200%200%200%2012.5%200l13.5-21.8c2-.2%203.9-.3%205.9-.6l17.5%2018.7a7.4%207.4%200%200%200%2012.3-2.4l9-24c1.9-.6%203.8-1.1%205.7-1.7l20.8%2015a7.3%207.3%200%200%200%2011.5-4.8l4.2-25.4c1.7-.9%203.5-1.8%205.2-2.7l23.4%2010.7a7.4%207.4%200%200%200%2010.4-7l-.9-25.8q2.2-1.8%204.4-3.6L430.2%20439a7.4%207.4%200%200%200%208.8-8.8L433.1%20405q1.8-2.2%203.6-4.4l25.8%20.9a7.2%207.2%200%200%200%206.4-3.3%207.4%207.4%200%200%200%20.6-7.1L458.8%20367.7c.9-1.7%201.8-3.4%202.7-5.2l25.4-4.2a7.4%207.4%200%200%200%204.8-11.5l-15-20.8c.6-1.9%201.1-3.8%201.7-5.7l24-9a7.4%207.4%200%200%200%202.4-12.3l-18.7-17.5c.2-2%20.4-3.9%20.6-5.9l21.8-13.5a7.4%207.4%200%200%200%200-12.5zm-151%20129.1A13.9%2013.9%200%200%200%20341%20389.5l-7.6%2035.7A187.5%20187.5%200%200%201%20177%20424.4l-7.6-35.7a13.9%2013.9%200%200%200%20-16.5-10.7l-31.5%206.8a187.4%20187.4%200%200%201%20-16.3-19.2H258.3c1.7%200%202.9-.3%202.9-1.9V309.6c0-1.6-1.2-1.9-2.9-1.9H213.5l.1-34.4H262c4.4%200%2023.7%201.3%2029.8%2025.9%201.9%207.6%206.2%2032.1%209.1%2040%202.9%208.8%2014.6%2026.5%2027.1%2026.5H407a187.3%20187.3%200%200%201%20-17.3%2020.1zm25.8%2034.5A15.2%2015.2%200%201%201%20368%20398.1h.4A15.2%2015.2%200%200%201%20383.2%20413.3zm-225.6-.7a15.2%2015.2%200%201%201%20-15.3-15.3h.5A15.3%2015.3%200%200%201%20157.6%20412.6zM69.6%20234.2l32.8-14.6a13.9%2013.9%200%200%200%207.1-18.3L102.7%20186h26.6V305.7H75.7A187.7%20187.7%200%200%201%2069.6%20234.2zM58.3%20198.1a15.2%2015.2%200%200%201%2015.2-15.3H74a15.2%2015.2%200%201%201%20-15.7%2015.2zm155.2%2024.5%20.1-35.3h63.3c3.3%200%2023.1%203.8%2023.1%2018.6%200%2012.3-15.2%2016.7-27.7%2016.7zM399%20306.7c-9.8%201.1-20.6-4.1-22-10.1-5.8-32.5-15.4-39.4-30.6-51.4%2018.9-12%2038.5-29.6%2038.5-53.3%200-25.5-17.5-41.6-29.4-49.5-16.8-11-35.3-13.2-40.3-13.2H116.3A187.5%20187.5%200%200%201%20221.2%2070.1l23.5%2024.6a13.8%2013.8%200%200%200%2019.6%20.4l26.3-25a187.5%20187.5%200%200%201%20128.4%2091.4l-18%2040.6A14%2014%200%200%200%20408%20220.4l34.6%2015.3a187.1%20187.1%200%200%201%20.4%2032.5H423.7c-1.9%200-2.7%201.3-2.7%203.1v8.8C421%20301%20409.3%20305.6%20399%20306.7zM240%2060.2A15.2%2015.2%200%200%201%20255.2%2045h.5A15.2%2015.2%200%201%201%20240%2060.2zM436.8%20214a15.2%2015.2%200%201%201%200-30.5h.4a15.2%2015.2%200%200%201%20-.4%2030.5z%22%2F%3E%3C%2Fsvg%3E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ipetkov/crane) (👨‍💻 57 · 🔀 100 · 📋 270 - 6% open · ⏱️ 03.05.2025):

	```
	git clone https://github.com/ipetkov/crane
	```
</details>
<details><summary><b><a href="https://github.com/oxalica/rust-overlay">rust-overlay</a></b> (🥇18 ·  ⭐ 1.1K) - Pure and reproducible nix overlay of binary distributed Rust.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="data:image/svg+xml;charset=utf8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20512%20512%22%3E%3Cpath%20fill%3D%22%23fab387%22%20d%3D%22M508.5%20249.8%20486.7%20236.2c-.2-2-.3-3.9-.6-5.9l18.7-17.5a7.4%207.4%200%200%200%20-2.4-12.3l-24-9c-.5-1.9-1.1-3.8-1.7-5.6l15-20.8a7.4%207.4%200%200%200%20-4.8-11.5l-25.4-4.2c-.9-1.7-1.8-3.5-2.7-5.2l10.7-23.4a7.4%207.4%200%200%200%20-7-10.4l-25.8%20.9q-1.8-2.2-3.6-4.4L439%2081.8A7.4%207.4%200%200%200%20430.2%2073L405%2078.9q-2.2-1.8-4.4-3.6l.9-25.8a7.4%207.4%200%200%200%20-10.4-7L367.7%2053.2c-1.7-.9-3.4-1.8-5.2-2.7L358.4%2025.1a7.4%207.4%200%200%200%20-11.5-4.8L326%2035.3c-1.9-.6-3.8-1.1-5.6-1.7l-9-24a7.4%207.4%200%200%200%20-12.3-2.4l-17.5%2018.7c-2-.2-3.9-.4-5.9-.6L262.3%203.5a7.4%207.4%200%200%200%20-12.5%200L236.2%2025.3c-2%20.2-3.9%20.3-5.9%20.6L212.9%207.1a7.4%207.4%200%200%200%20-12.3%202.4l-9%2024c-1.9%20.6-3.8%201.1-5.7%201.7l-20.8-15a7.4%207.4%200%200%200%20-11.5%204.8l-4.2%2025.4c-1.7%20.9-3.5%201.8-5.2%202.7L120.9%2042.6a7.4%207.4%200%200%200%20-10.4%207l.9%2025.8c-1.5%201.2-3%202.4-4.4%203.6L81.8%2073A7.4%207.4%200%200%200%2073%2081.8L78.9%20107c-1.2%201.5-2.4%202.9-3.6%204.4l-25.8-.9a7.4%207.4%200%200%200%20-6.4%203.3%207.4%207.4%200%200%200%20-.6%207.1l10.7%2023.4c-.9%201.7-1.8%203.4-2.7%205.2L25.1%20153.6a7.4%207.4%200%200%200%20-4.8%2011.5l15%2020.8c-.6%201.9-1.1%203.8-1.7%205.7l-24%209a7.4%207.4%200%200%200%20-2.4%2012.3l18.7%2017.5c-.2%202-.4%203.9-.6%205.9L3.5%20249.8a7.4%207.4%200%200%200%200%2012.5L25.3%20275.8c.2%202%20.3%203.9%20.6%205.9L7.1%20299.1a7.4%207.4%200%200%200%202.4%2012.3l24%209c.6%201.9%201.1%203.8%201.7%205.7l-15%2020.8a7.4%207.4%200%200%200%204.8%2011.5l25.4%204.2c.9%201.7%201.8%203.5%202.7%205.1L42.6%20391.1a7.4%207.4%200%200%200%20.6%207.1%207.1%207.1%200%200%200%206.4%203.3l25.8-.9q1.8%202.2%203.6%204.4L73%20430.2A7.4%207.4%200%200%200%2081.8%20439L107%20433.1q2.2%201.8%204.4%203.6l-.9%2025.8a7.4%207.4%200%200%200%2010.4%207l23.4-10.7c1.7%20.9%203.4%201.8%205.1%202.7l4.2%2025.4a7.3%207.3%200%200%200%2011.5%204.8l20.8-15c1.9%20.6%203.8%201.1%205.7%201.7l9%2024a7.4%207.4%200%200%200%2012.3%202.4l17.5-18.7c2%20.2%203.9%20.4%205.9%20.6l13.5%2021.8a7.4%207.4%200%200%200%2012.5%200l13.5-21.8c2-.2%203.9-.3%205.9-.6l17.5%2018.7a7.4%207.4%200%200%200%2012.3-2.4l9-24c1.9-.6%203.8-1.1%205.7-1.7l20.8%2015a7.3%207.3%200%200%200%2011.5-4.8l4.2-25.4c1.7-.9%203.5-1.8%205.2-2.7l23.4%2010.7a7.4%207.4%200%200%200%2010.4-7l-.9-25.8q2.2-1.8%204.4-3.6L430.2%20439a7.4%207.4%200%200%200%208.8-8.8L433.1%20405q1.8-2.2%203.6-4.4l25.8%20.9a7.2%207.2%200%200%200%206.4-3.3%207.4%207.4%200%200%200%20.6-7.1L458.8%20367.7c.9-1.7%201.8-3.4%202.7-5.2l25.4-4.2a7.4%207.4%200%200%200%204.8-11.5l-15-20.8c.6-1.9%201.1-3.8%201.7-5.7l24-9a7.4%207.4%200%200%200%202.4-12.3l-18.7-17.5c.2-2%20.4-3.9%20.6-5.9l21.8-13.5a7.4%207.4%200%200%200%200-12.5zm-151%20129.1A13.9%2013.9%200%200%200%20341%20389.5l-7.6%2035.7A187.5%20187.5%200%200%201%20177%20424.4l-7.6-35.7a13.9%2013.9%200%200%200%20-16.5-10.7l-31.5%206.8a187.4%20187.4%200%200%201%20-16.3-19.2H258.3c1.7%200%202.9-.3%202.9-1.9V309.6c0-1.6-1.2-1.9-2.9-1.9H213.5l.1-34.4H262c4.4%200%2023.7%201.3%2029.8%2025.9%201.9%207.6%206.2%2032.1%209.1%2040%202.9%208.8%2014.6%2026.5%2027.1%2026.5H407a187.3%20187.3%200%200%201%20-17.3%2020.1zm25.8%2034.5A15.2%2015.2%200%201%201%20368%20398.1h.4A15.2%2015.2%200%200%201%20383.2%20413.3zm-225.6-.7a15.2%2015.2%200%201%201%20-15.3-15.3h.5A15.3%2015.3%200%200%201%20157.6%20412.6zM69.6%20234.2l32.8-14.6a13.9%2013.9%200%200%200%207.1-18.3L102.7%20186h26.6V305.7H75.7A187.7%20187.7%200%200%201%2069.6%20234.2zM58.3%20198.1a15.2%2015.2%200%200%201%2015.2-15.3H74a15.2%2015.2%200%201%201%20-15.7%2015.2zm155.2%2024.5%20.1-35.3h63.3c3.3%200%2023.1%203.8%2023.1%2018.6%200%2012.3-15.2%2016.7-27.7%2016.7zM399%20306.7c-9.8%201.1-20.6-4.1-22-10.1-5.8-32.5-15.4-39.4-30.6-51.4%2018.9-12%2038.5-29.6%2038.5-53.3%200-25.5-17.5-41.6-29.4-49.5-16.8-11-35.3-13.2-40.3-13.2H116.3A187.5%20187.5%200%200%201%20221.2%2070.1l23.5%2024.6a13.8%2013.8%200%200%200%2019.6%20.4l26.3-25a187.5%20187.5%200%200%201%20128.4%2091.4l-18%2040.6A14%2014%200%200%200%20408%20220.4l34.6%2015.3a187.1%20187.1%200%200%201%20.4%2032.5H423.7c-1.9%200-2.7%201.3-2.7%203.1v8.8C421%20301%20409.3%20305.6%20399%20306.7zM240%2060.2A15.2%2015.2%200%200%201%20255.2%2045h.5A15.2%2015.2%200%201%201%20240%2060.2zM436.8%20214a15.2%2015.2%200%201%201%200-30.5h.4a15.2%2015.2%200%200%201%20-.4%2030.5z%22%2F%3E%3C%2Fsvg%3E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/oxalica/rust-overlay) (👨‍💻 25 · 🔀 68 · 📋 150 - 7% open · ⏱️ 11.05.2025):

	```
	git clone https://github.com/oxalica/rust-overlay
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/fenix">fenix</a></b> (🥈16 ·  ⭐ 800) - Rust toolchains and Rust analyzer nightly for nix. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="data:image/svg+xml;charset=utf8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20512%20512%22%3E%3Cpath%20fill%3D%22%23fab387%22%20d%3D%22M508.5%20249.8%20486.7%20236.2c-.2-2-.3-3.9-.6-5.9l18.7-17.5a7.4%207.4%200%200%200%20-2.4-12.3l-24-9c-.5-1.9-1.1-3.8-1.7-5.6l15-20.8a7.4%207.4%200%200%200%20-4.8-11.5l-25.4-4.2c-.9-1.7-1.8-3.5-2.7-5.2l10.7-23.4a7.4%207.4%200%200%200%20-7-10.4l-25.8%20.9q-1.8-2.2-3.6-4.4L439%2081.8A7.4%207.4%200%200%200%20430.2%2073L405%2078.9q-2.2-1.8-4.4-3.6l.9-25.8a7.4%207.4%200%200%200%20-10.4-7L367.7%2053.2c-1.7-.9-3.4-1.8-5.2-2.7L358.4%2025.1a7.4%207.4%200%200%200%20-11.5-4.8L326%2035.3c-1.9-.6-3.8-1.1-5.6-1.7l-9-24a7.4%207.4%200%200%200%20-12.3-2.4l-17.5%2018.7c-2-.2-3.9-.4-5.9-.6L262.3%203.5a7.4%207.4%200%200%200%20-12.5%200L236.2%2025.3c-2%20.2-3.9%20.3-5.9%20.6L212.9%207.1a7.4%207.4%200%200%200%20-12.3%202.4l-9%2024c-1.9%20.6-3.8%201.1-5.7%201.7l-20.8-15a7.4%207.4%200%200%200%20-11.5%204.8l-4.2%2025.4c-1.7%20.9-3.5%201.8-5.2%202.7L120.9%2042.6a7.4%207.4%200%200%200%20-10.4%207l.9%2025.8c-1.5%201.2-3%202.4-4.4%203.6L81.8%2073A7.4%207.4%200%200%200%2073%2081.8L78.9%20107c-1.2%201.5-2.4%202.9-3.6%204.4l-25.8-.9a7.4%207.4%200%200%200%20-6.4%203.3%207.4%207.4%200%200%200%20-.6%207.1l10.7%2023.4c-.9%201.7-1.8%203.4-2.7%205.2L25.1%20153.6a7.4%207.4%200%200%200%20-4.8%2011.5l15%2020.8c-.6%201.9-1.1%203.8-1.7%205.7l-24%209a7.4%207.4%200%200%200%20-2.4%2012.3l18.7%2017.5c-.2%202-.4%203.9-.6%205.9L3.5%20249.8a7.4%207.4%200%200%200%200%2012.5L25.3%20275.8c.2%202%20.3%203.9%20.6%205.9L7.1%20299.1a7.4%207.4%200%200%200%202.4%2012.3l24%209c.6%201.9%201.1%203.8%201.7%205.7l-15%2020.8a7.4%207.4%200%200%200%204.8%2011.5l25.4%204.2c.9%201.7%201.8%203.5%202.7%205.1L42.6%20391.1a7.4%207.4%200%200%200%20.6%207.1%207.1%207.1%200%200%200%206.4%203.3l25.8-.9q1.8%202.2%203.6%204.4L73%20430.2A7.4%207.4%200%200%200%2081.8%20439L107%20433.1q2.2%201.8%204.4%203.6l-.9%2025.8a7.4%207.4%200%200%200%2010.4%207l23.4-10.7c1.7%20.9%203.4%201.8%205.1%202.7l4.2%2025.4a7.3%207.3%200%200%200%2011.5%204.8l20.8-15c1.9%20.6%203.8%201.1%205.7%201.7l9%2024a7.4%207.4%200%200%200%2012.3%202.4l17.5-18.7c2%20.2%203.9%20.4%205.9%20.6l13.5%2021.8a7.4%207.4%200%200%200%2012.5%200l13.5-21.8c2-.2%203.9-.3%205.9-.6l17.5%2018.7a7.4%207.4%200%200%200%2012.3-2.4l9-24c1.9-.6%203.8-1.1%205.7-1.7l20.8%2015a7.3%207.3%200%200%200%2011.5-4.8l4.2-25.4c1.7-.9%203.5-1.8%205.2-2.7l23.4%2010.7a7.4%207.4%200%200%200%2010.4-7l-.9-25.8q2.2-1.8%204.4-3.6L430.2%20439a7.4%207.4%200%200%200%208.8-8.8L433.1%20405q1.8-2.2%203.6-4.4l25.8%20.9a7.2%207.2%200%200%200%206.4-3.3%207.4%207.4%200%200%200%20.6-7.1L458.8%20367.7c.9-1.7%201.8-3.4%202.7-5.2l25.4-4.2a7.4%207.4%200%200%200%204.8-11.5l-15-20.8c.6-1.9%201.1-3.8%201.7-5.7l24-9a7.4%207.4%200%200%200%202.4-12.3l-18.7-17.5c.2-2%20.4-3.9%20.6-5.9l21.8-13.5a7.4%207.4%200%200%200%200-12.5zm-151%20129.1A13.9%2013.9%200%200%200%20341%20389.5l-7.6%2035.7A187.5%20187.5%200%200%201%20177%20424.4l-7.6-35.7a13.9%2013.9%200%200%200%20-16.5-10.7l-31.5%206.8a187.4%20187.4%200%200%201%20-16.3-19.2H258.3c1.7%200%202.9-.3%202.9-1.9V309.6c0-1.6-1.2-1.9-2.9-1.9H213.5l.1-34.4H262c4.4%200%2023.7%201.3%2029.8%2025.9%201.9%207.6%206.2%2032.1%209.1%2040%202.9%208.8%2014.6%2026.5%2027.1%2026.5H407a187.3%20187.3%200%200%201%20-17.3%2020.1zm25.8%2034.5A15.2%2015.2%200%201%201%20368%20398.1h.4A15.2%2015.2%200%200%201%20383.2%20413.3zm-225.6-.7a15.2%2015.2%200%201%201%20-15.3-15.3h.5A15.3%2015.3%200%200%201%20157.6%20412.6zM69.6%20234.2l32.8-14.6a13.9%2013.9%200%200%200%207.1-18.3L102.7%20186h26.6V305.7H75.7A187.7%20187.7%200%200%201%2069.6%20234.2zM58.3%20198.1a15.2%2015.2%200%200%201%2015.2-15.3H74a15.2%2015.2%200%201%201%20-15.7%2015.2zm155.2%2024.5%20.1-35.3h63.3c3.3%200%2023.1%203.8%2023.1%2018.6%200%2012.3-15.2%2016.7-27.7%2016.7zM399%20306.7c-9.8%201.1-20.6-4.1-22-10.1-5.8-32.5-15.4-39.4-30.6-51.4%2018.9-12%2038.5-29.6%2038.5-53.3%200-25.5-17.5-41.6-29.4-49.5-16.8-11-35.3-13.2-40.3-13.2H116.3A187.5%20187.5%200%200%201%20221.2%2070.1l23.5%2024.6a13.8%2013.8%200%200%200%2019.6%20.4l26.3-25a187.5%20187.5%200%200%201%20128.4%2091.4l-18%2040.6A14%2014%200%200%200%20408%20220.4l34.6%2015.3a187.1%20187.1%200%200%201%20.4%2032.5H423.7c-1.9%200-2.7%201.3-2.7%203.1v8.8C421%20301%20409.3%20305.6%20399%20306.7zM240%2060.2A15.2%2015.2%200%200%201%20255.2%2045h.5A15.2%2015.2%200%201%201%20240%2060.2zM436.8%20214a15.2%2015.2%200%201%201%200-30.5h.4a15.2%2015.2%200%200%201%20-.4%2030.5z%22%2F%3E%3C%2Fsvg%3E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nix-community/fenix) (👨‍💻 20 · 🔀 57 · 📋 86 - 38% open · ⏱️ 11.05.2025):

	```
	git clone https://github.com/nix-community/fenix
	```
</details>
<details><summary><b><a href="https://github.com/cargo2nix/cargo2nix">cargo2nix</a></b> (🥈16 ·  ⭐ 420) - Granular caching, development shell, Nix & Rust integration. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="data:image/svg+xml;charset=utf8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20512%20512%22%3E%3Cpath%20fill%3D%22%23fab387%22%20d%3D%22M508.5%20249.8%20486.7%20236.2c-.2-2-.3-3.9-.6-5.9l18.7-17.5a7.4%207.4%200%200%200%20-2.4-12.3l-24-9c-.5-1.9-1.1-3.8-1.7-5.6l15-20.8a7.4%207.4%200%200%200%20-4.8-11.5l-25.4-4.2c-.9-1.7-1.8-3.5-2.7-5.2l10.7-23.4a7.4%207.4%200%200%200%20-7-10.4l-25.8%20.9q-1.8-2.2-3.6-4.4L439%2081.8A7.4%207.4%200%200%200%20430.2%2073L405%2078.9q-2.2-1.8-4.4-3.6l.9-25.8a7.4%207.4%200%200%200%20-10.4-7L367.7%2053.2c-1.7-.9-3.4-1.8-5.2-2.7L358.4%2025.1a7.4%207.4%200%200%200%20-11.5-4.8L326%2035.3c-1.9-.6-3.8-1.1-5.6-1.7l-9-24a7.4%207.4%200%200%200%20-12.3-2.4l-17.5%2018.7c-2-.2-3.9-.4-5.9-.6L262.3%203.5a7.4%207.4%200%200%200%20-12.5%200L236.2%2025.3c-2%20.2-3.9%20.3-5.9%20.6L212.9%207.1a7.4%207.4%200%200%200%20-12.3%202.4l-9%2024c-1.9%20.6-3.8%201.1-5.7%201.7l-20.8-15a7.4%207.4%200%200%200%20-11.5%204.8l-4.2%2025.4c-1.7%20.9-3.5%201.8-5.2%202.7L120.9%2042.6a7.4%207.4%200%200%200%20-10.4%207l.9%2025.8c-1.5%201.2-3%202.4-4.4%203.6L81.8%2073A7.4%207.4%200%200%200%2073%2081.8L78.9%20107c-1.2%201.5-2.4%202.9-3.6%204.4l-25.8-.9a7.4%207.4%200%200%200%20-6.4%203.3%207.4%207.4%200%200%200%20-.6%207.1l10.7%2023.4c-.9%201.7-1.8%203.4-2.7%205.2L25.1%20153.6a7.4%207.4%200%200%200%20-4.8%2011.5l15%2020.8c-.6%201.9-1.1%203.8-1.7%205.7l-24%209a7.4%207.4%200%200%200%20-2.4%2012.3l18.7%2017.5c-.2%202-.4%203.9-.6%205.9L3.5%20249.8a7.4%207.4%200%200%200%200%2012.5L25.3%20275.8c.2%202%20.3%203.9%20.6%205.9L7.1%20299.1a7.4%207.4%200%200%200%202.4%2012.3l24%209c.6%201.9%201.1%203.8%201.7%205.7l-15%2020.8a7.4%207.4%200%200%200%204.8%2011.5l25.4%204.2c.9%201.7%201.8%203.5%202.7%205.1L42.6%20391.1a7.4%207.4%200%200%200%20.6%207.1%207.1%207.1%200%200%200%206.4%203.3l25.8-.9q1.8%202.2%203.6%204.4L73%20430.2A7.4%207.4%200%200%200%2081.8%20439L107%20433.1q2.2%201.8%204.4%203.6l-.9%2025.8a7.4%207.4%200%200%200%2010.4%207l23.4-10.7c1.7%20.9%203.4%201.8%205.1%202.7l4.2%2025.4a7.3%207.3%200%200%200%2011.5%204.8l20.8-15c1.9%20.6%203.8%201.1%205.7%201.7l9%2024a7.4%207.4%200%200%200%2012.3%202.4l17.5-18.7c2%20.2%203.9%20.4%205.9%20.6l13.5%2021.8a7.4%207.4%200%200%200%2012.5%200l13.5-21.8c2-.2%203.9-.3%205.9-.6l17.5%2018.7a7.4%207.4%200%200%200%2012.3-2.4l9-24c1.9-.6%203.8-1.1%205.7-1.7l20.8%2015a7.3%207.3%200%200%200%2011.5-4.8l4.2-25.4c1.7-.9%203.5-1.8%205.2-2.7l23.4%2010.7a7.4%207.4%200%200%200%2010.4-7l-.9-25.8q2.2-1.8%204.4-3.6L430.2%20439a7.4%207.4%200%200%200%208.8-8.8L433.1%20405q1.8-2.2%203.6-4.4l25.8%20.9a7.2%207.2%200%200%200%206.4-3.3%207.4%207.4%200%200%200%20.6-7.1L458.8%20367.7c.9-1.7%201.8-3.4%202.7-5.2l25.4-4.2a7.4%207.4%200%200%200%204.8-11.5l-15-20.8c.6-1.9%201.1-3.8%201.7-5.7l24-9a7.4%207.4%200%200%200%202.4-12.3l-18.7-17.5c.2-2%20.4-3.9%20.6-5.9l21.8-13.5a7.4%207.4%200%200%200%200-12.5zm-151%20129.1A13.9%2013.9%200%200%200%20341%20389.5l-7.6%2035.7A187.5%20187.5%200%200%201%20177%20424.4l-7.6-35.7a13.9%2013.9%200%200%200%20-16.5-10.7l-31.5%206.8a187.4%20187.4%200%200%201%20-16.3-19.2H258.3c1.7%200%202.9-.3%202.9-1.9V309.6c0-1.6-1.2-1.9-2.9-1.9H213.5l.1-34.4H262c4.4%200%2023.7%201.3%2029.8%2025.9%201.9%207.6%206.2%2032.1%209.1%2040%202.9%208.8%2014.6%2026.5%2027.1%2026.5H407a187.3%20187.3%200%200%201%20-17.3%2020.1zm25.8%2034.5A15.2%2015.2%200%201%201%20368%20398.1h.4A15.2%2015.2%200%200%201%20383.2%20413.3zm-225.6-.7a15.2%2015.2%200%201%201%20-15.3-15.3h.5A15.3%2015.3%200%200%201%20157.6%20412.6zM69.6%20234.2l32.8-14.6a13.9%2013.9%200%200%200%207.1-18.3L102.7%20186h26.6V305.7H75.7A187.7%20187.7%200%200%201%2069.6%20234.2zM58.3%20198.1a15.2%2015.2%200%200%201%2015.2-15.3H74a15.2%2015.2%200%201%201%20-15.7%2015.2zm155.2%2024.5%20.1-35.3h63.3c3.3%200%2023.1%203.8%2023.1%2018.6%200%2012.3-15.2%2016.7-27.7%2016.7zM399%20306.7c-9.8%201.1-20.6-4.1-22-10.1-5.8-32.5-15.4-39.4-30.6-51.4%2018.9-12%2038.5-29.6%2038.5-53.3%200-25.5-17.5-41.6-29.4-49.5-16.8-11-35.3-13.2-40.3-13.2H116.3A187.5%20187.5%200%200%201%20221.2%2070.1l23.5%2024.6a13.8%2013.8%200%200%200%2019.6%20.4l26.3-25a187.5%20187.5%200%200%201%20128.4%2091.4l-18%2040.6A14%2014%200%200%200%20408%20220.4l34.6%2015.3a187.1%20187.1%200%200%201%20.4%2032.5H423.7c-1.9%200-2.7%201.3-2.7%203.1v8.8C421%20301%20409.3%20305.6%20399%20306.7zM240%2060.2A15.2%2015.2%200%200%201%20255.2%2045h.5A15.2%2015.2%200%201%201%20240%2060.2zM436.8%20214a15.2%2015.2%200%201%201%200-30.5h.4a15.2%2015.2%200%200%201%20-.4%2030.5z%22%2F%3E%3C%2Fsvg%3E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cargo2nix/cargo2nix) (👨‍💻 40 · 🔀 80 · 📋 180 - 34% open · ⏱️ 23.03.2025):

	```
	git clone https://github.com/cargo2nix/cargo2nix
	```
</details>
<details><summary><b><a href="https://github.com/yusdacra/nix-cargo-integration">nix-cargo-integration</a></b> (🥈16 ·  ⭐ 190) - A library that allows easy and effortless integration.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="data:image/svg+xml;charset=utf8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20512%20512%22%3E%3Cpath%20fill%3D%22%23fab387%22%20d%3D%22M508.5%20249.8%20486.7%20236.2c-.2-2-.3-3.9-.6-5.9l18.7-17.5a7.4%207.4%200%200%200%20-2.4-12.3l-24-9c-.5-1.9-1.1-3.8-1.7-5.6l15-20.8a7.4%207.4%200%200%200%20-4.8-11.5l-25.4-4.2c-.9-1.7-1.8-3.5-2.7-5.2l10.7-23.4a7.4%207.4%200%200%200%20-7-10.4l-25.8%20.9q-1.8-2.2-3.6-4.4L439%2081.8A7.4%207.4%200%200%200%20430.2%2073L405%2078.9q-2.2-1.8-4.4-3.6l.9-25.8a7.4%207.4%200%200%200%20-10.4-7L367.7%2053.2c-1.7-.9-3.4-1.8-5.2-2.7L358.4%2025.1a7.4%207.4%200%200%200%20-11.5-4.8L326%2035.3c-1.9-.6-3.8-1.1-5.6-1.7l-9-24a7.4%207.4%200%200%200%20-12.3-2.4l-17.5%2018.7c-2-.2-3.9-.4-5.9-.6L262.3%203.5a7.4%207.4%200%200%200%20-12.5%200L236.2%2025.3c-2%20.2-3.9%20.3-5.9%20.6L212.9%207.1a7.4%207.4%200%200%200%20-12.3%202.4l-9%2024c-1.9%20.6-3.8%201.1-5.7%201.7l-20.8-15a7.4%207.4%200%200%200%20-11.5%204.8l-4.2%2025.4c-1.7%20.9-3.5%201.8-5.2%202.7L120.9%2042.6a7.4%207.4%200%200%200%20-10.4%207l.9%2025.8c-1.5%201.2-3%202.4-4.4%203.6L81.8%2073A7.4%207.4%200%200%200%2073%2081.8L78.9%20107c-1.2%201.5-2.4%202.9-3.6%204.4l-25.8-.9a7.4%207.4%200%200%200%20-6.4%203.3%207.4%207.4%200%200%200%20-.6%207.1l10.7%2023.4c-.9%201.7-1.8%203.4-2.7%205.2L25.1%20153.6a7.4%207.4%200%200%200%20-4.8%2011.5l15%2020.8c-.6%201.9-1.1%203.8-1.7%205.7l-24%209a7.4%207.4%200%200%200%20-2.4%2012.3l18.7%2017.5c-.2%202-.4%203.9-.6%205.9L3.5%20249.8a7.4%207.4%200%200%200%200%2012.5L25.3%20275.8c.2%202%20.3%203.9%20.6%205.9L7.1%20299.1a7.4%207.4%200%200%200%202.4%2012.3l24%209c.6%201.9%201.1%203.8%201.7%205.7l-15%2020.8a7.4%207.4%200%200%200%204.8%2011.5l25.4%204.2c.9%201.7%201.8%203.5%202.7%205.1L42.6%20391.1a7.4%207.4%200%200%200%20.6%207.1%207.1%207.1%200%200%200%206.4%203.3l25.8-.9q1.8%202.2%203.6%204.4L73%20430.2A7.4%207.4%200%200%200%2081.8%20439L107%20433.1q2.2%201.8%204.4%203.6l-.9%2025.8a7.4%207.4%200%200%200%2010.4%207l23.4-10.7c1.7%20.9%203.4%201.8%205.1%202.7l4.2%2025.4a7.3%207.3%200%200%200%2011.5%204.8l20.8-15c1.9%20.6%203.8%201.1%205.7%201.7l9%2024a7.4%207.4%200%200%200%2012.3%202.4l17.5-18.7c2%20.2%203.9%20.4%205.9%20.6l13.5%2021.8a7.4%207.4%200%200%200%2012.5%200l13.5-21.8c2-.2%203.9-.3%205.9-.6l17.5%2018.7a7.4%207.4%200%200%200%2012.3-2.4l9-24c1.9-.6%203.8-1.1%205.7-1.7l20.8%2015a7.3%207.3%200%200%200%2011.5-4.8l4.2-25.4c1.7-.9%203.5-1.8%205.2-2.7l23.4%2010.7a7.4%207.4%200%200%200%2010.4-7l-.9-25.8q2.2-1.8%204.4-3.6L430.2%20439a7.4%207.4%200%200%200%208.8-8.8L433.1%20405q1.8-2.2%203.6-4.4l25.8%20.9a7.2%207.2%200%200%200%206.4-3.3%207.4%207.4%200%200%200%20.6-7.1L458.8%20367.7c.9-1.7%201.8-3.4%202.7-5.2l25.4-4.2a7.4%207.4%200%200%200%204.8-11.5l-15-20.8c.6-1.9%201.1-3.8%201.7-5.7l24-9a7.4%207.4%200%200%200%202.4-12.3l-18.7-17.5c.2-2%20.4-3.9%20.6-5.9l21.8-13.5a7.4%207.4%200%200%200%200-12.5zm-151%20129.1A13.9%2013.9%200%200%200%20341%20389.5l-7.6%2035.7A187.5%20187.5%200%200%201%20177%20424.4l-7.6-35.7a13.9%2013.9%200%200%200%20-16.5-10.7l-31.5%206.8a187.4%20187.4%200%200%201%20-16.3-19.2H258.3c1.7%200%202.9-.3%202.9-1.9V309.6c0-1.6-1.2-1.9-2.9-1.9H213.5l.1-34.4H262c4.4%200%2023.7%201.3%2029.8%2025.9%201.9%207.6%206.2%2032.1%209.1%2040%202.9%208.8%2014.6%2026.5%2027.1%2026.5H407a187.3%20187.3%200%200%201%20-17.3%2020.1zm25.8%2034.5A15.2%2015.2%200%201%201%20368%20398.1h.4A15.2%2015.2%200%200%201%20383.2%20413.3zm-225.6-.7a15.2%2015.2%200%201%201%20-15.3-15.3h.5A15.3%2015.3%200%200%201%20157.6%20412.6zM69.6%20234.2l32.8-14.6a13.9%2013.9%200%200%200%207.1-18.3L102.7%20186h26.6V305.7H75.7A187.7%20187.7%200%200%201%2069.6%20234.2zM58.3%20198.1a15.2%2015.2%200%200%201%2015.2-15.3H74a15.2%2015.2%200%201%201%20-15.7%2015.2zm155.2%2024.5%20.1-35.3h63.3c3.3%200%2023.1%203.8%2023.1%2018.6%200%2012.3-15.2%2016.7-27.7%2016.7zM399%20306.7c-9.8%201.1-20.6-4.1-22-10.1-5.8-32.5-15.4-39.4-30.6-51.4%2018.9-12%2038.5-29.6%2038.5-53.3%200-25.5-17.5-41.6-29.4-49.5-16.8-11-35.3-13.2-40.3-13.2H116.3A187.5%20187.5%200%200%201%20221.2%2070.1l23.5%2024.6a13.8%2013.8%200%200%200%2019.6%20.4l26.3-25a187.5%20187.5%200%200%201%20128.4%2091.4l-18%2040.6A14%2014%200%200%200%20408%20220.4l34.6%2015.3a187.1%20187.1%200%200%201%20.4%2032.5H423.7c-1.9%200-2.7%201.3-2.7%203.1v8.8C421%20301%20409.3%20305.6%20399%20306.7zM240%2060.2A15.2%2015.2%200%200%201%20255.2%2045h.5A15.2%2015.2%200%201%201%20240%2060.2zM436.8%20214a15.2%2015.2%200%201%201%200-30.5h.4a15.2%2015.2%200%200%201%20-.4%2030.5z%22%2F%3E%3C%2Fsvg%3E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/yusdacra/nix-cargo-integration) (👨‍💻 14 · 🔀 24 · 📋 85 - 2% open · ⏱️ 11.05.2025):

	```
	git clone https://github.com/yusdacra/nix-cargo-integration
	```
</details>
<details><summary><b><a href="https://github.com/srid/haskell-flake">haskell-flake</a></b> (🥈16 ·  ⭐ 180) - A `flake-parts` Nix module for Haskell development. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.haskell.org/img/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/srid/haskell-flake) (👨‍💻 15 · 🔀 23 · 📋 120 - 28% open · ⏱️ 11.05.2025):

	```
	git clone https://github.com/srid/haskell-flake
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/naersk">naersk</a></b> (🥈14 ·  ⭐ 830) - Build Rust packages directly from `Cargo.lock`. No conversion step.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="data:image/svg+xml;charset=utf8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20512%20512%22%3E%3Cpath%20fill%3D%22%23fab387%22%20d%3D%22M508.5%20249.8%20486.7%20236.2c-.2-2-.3-3.9-.6-5.9l18.7-17.5a7.4%207.4%200%200%200%20-2.4-12.3l-24-9c-.5-1.9-1.1-3.8-1.7-5.6l15-20.8a7.4%207.4%200%200%200%20-4.8-11.5l-25.4-4.2c-.9-1.7-1.8-3.5-2.7-5.2l10.7-23.4a7.4%207.4%200%200%200%20-7-10.4l-25.8%20.9q-1.8-2.2-3.6-4.4L439%2081.8A7.4%207.4%200%200%200%20430.2%2073L405%2078.9q-2.2-1.8-4.4-3.6l.9-25.8a7.4%207.4%200%200%200%20-10.4-7L367.7%2053.2c-1.7-.9-3.4-1.8-5.2-2.7L358.4%2025.1a7.4%207.4%200%200%200%20-11.5-4.8L326%2035.3c-1.9-.6-3.8-1.1-5.6-1.7l-9-24a7.4%207.4%200%200%200%20-12.3-2.4l-17.5%2018.7c-2-.2-3.9-.4-5.9-.6L262.3%203.5a7.4%207.4%200%200%200%20-12.5%200L236.2%2025.3c-2%20.2-3.9%20.3-5.9%20.6L212.9%207.1a7.4%207.4%200%200%200%20-12.3%202.4l-9%2024c-1.9%20.6-3.8%201.1-5.7%201.7l-20.8-15a7.4%207.4%200%200%200%20-11.5%204.8l-4.2%2025.4c-1.7%20.9-3.5%201.8-5.2%202.7L120.9%2042.6a7.4%207.4%200%200%200%20-10.4%207l.9%2025.8c-1.5%201.2-3%202.4-4.4%203.6L81.8%2073A7.4%207.4%200%200%200%2073%2081.8L78.9%20107c-1.2%201.5-2.4%202.9-3.6%204.4l-25.8-.9a7.4%207.4%200%200%200%20-6.4%203.3%207.4%207.4%200%200%200%20-.6%207.1l10.7%2023.4c-.9%201.7-1.8%203.4-2.7%205.2L25.1%20153.6a7.4%207.4%200%200%200%20-4.8%2011.5l15%2020.8c-.6%201.9-1.1%203.8-1.7%205.7l-24%209a7.4%207.4%200%200%200%20-2.4%2012.3l18.7%2017.5c-.2%202-.4%203.9-.6%205.9L3.5%20249.8a7.4%207.4%200%200%200%200%2012.5L25.3%20275.8c.2%202%20.3%203.9%20.6%205.9L7.1%20299.1a7.4%207.4%200%200%200%202.4%2012.3l24%209c.6%201.9%201.1%203.8%201.7%205.7l-15%2020.8a7.4%207.4%200%200%200%204.8%2011.5l25.4%204.2c.9%201.7%201.8%203.5%202.7%205.1L42.6%20391.1a7.4%207.4%200%200%200%20.6%207.1%207.1%207.1%200%200%200%206.4%203.3l25.8-.9q1.8%202.2%203.6%204.4L73%20430.2A7.4%207.4%200%200%200%2081.8%20439L107%20433.1q2.2%201.8%204.4%203.6l-.9%2025.8a7.4%207.4%200%200%200%2010.4%207l23.4-10.7c1.7%20.9%203.4%201.8%205.1%202.7l4.2%2025.4a7.3%207.3%200%200%200%2011.5%204.8l20.8-15c1.9%20.6%203.8%201.1%205.7%201.7l9%2024a7.4%207.4%200%200%200%2012.3%202.4l17.5-18.7c2%20.2%203.9%20.4%205.9%20.6l13.5%2021.8a7.4%207.4%200%200%200%2012.5%200l13.5-21.8c2-.2%203.9-.3%205.9-.6l17.5%2018.7a7.4%207.4%200%200%200%2012.3-2.4l9-24c1.9-.6%203.8-1.1%205.7-1.7l20.8%2015a7.3%207.3%200%200%200%2011.5-4.8l4.2-25.4c1.7-.9%203.5-1.8%205.2-2.7l23.4%2010.7a7.4%207.4%200%200%200%2010.4-7l-.9-25.8q2.2-1.8%204.4-3.6L430.2%20439a7.4%207.4%200%200%200%208.8-8.8L433.1%20405q1.8-2.2%203.6-4.4l25.8%20.9a7.2%207.2%200%200%200%206.4-3.3%207.4%207.4%200%200%200%20.6-7.1L458.8%20367.7c.9-1.7%201.8-3.4%202.7-5.2l25.4-4.2a7.4%207.4%200%200%200%204.8-11.5l-15-20.8c.6-1.9%201.1-3.8%201.7-5.7l24-9a7.4%207.4%200%200%200%202.4-12.3l-18.7-17.5c.2-2%20.4-3.9%20.6-5.9l21.8-13.5a7.4%207.4%200%200%200%200-12.5zm-151%20129.1A13.9%2013.9%200%200%200%20341%20389.5l-7.6%2035.7A187.5%20187.5%200%200%201%20177%20424.4l-7.6-35.7a13.9%2013.9%200%200%200%20-16.5-10.7l-31.5%206.8a187.4%20187.4%200%200%201%20-16.3-19.2H258.3c1.7%200%202.9-.3%202.9-1.9V309.6c0-1.6-1.2-1.9-2.9-1.9H213.5l.1-34.4H262c4.4%200%2023.7%201.3%2029.8%2025.9%201.9%207.6%206.2%2032.1%209.1%2040%202.9%208.8%2014.6%2026.5%2027.1%2026.5H407a187.3%20187.3%200%200%201%20-17.3%2020.1zm25.8%2034.5A15.2%2015.2%200%201%201%20368%20398.1h.4A15.2%2015.2%200%200%201%20383.2%20413.3zm-225.6-.7a15.2%2015.2%200%201%201%20-15.3-15.3h.5A15.3%2015.3%200%200%201%20157.6%20412.6zM69.6%20234.2l32.8-14.6a13.9%2013.9%200%200%200%207.1-18.3L102.7%20186h26.6V305.7H75.7A187.7%20187.7%200%200%201%2069.6%20234.2zM58.3%20198.1a15.2%2015.2%200%200%201%2015.2-15.3H74a15.2%2015.2%200%201%201%20-15.7%2015.2zm155.2%2024.5%20.1-35.3h63.3c3.3%200%2023.1%203.8%2023.1%2018.6%200%2012.3-15.2%2016.7-27.7%2016.7zM399%20306.7c-9.8%201.1-20.6-4.1-22-10.1-5.8-32.5-15.4-39.4-30.6-51.4%2018.9-12%2038.5-29.6%2038.5-53.3%200-25.5-17.5-41.6-29.4-49.5-16.8-11-35.3-13.2-40.3-13.2H116.3A187.5%20187.5%200%200%201%20221.2%2070.1l23.5%2024.6a13.8%2013.8%200%200%200%2019.6%20.4l26.3-25a187.5%20187.5%200%200%201%20128.4%2091.4l-18%2040.6A14%2014%200%200%200%20408%20220.4l34.6%2015.3a187.1%20187.1%200%200%201%20.4%2032.5H423.7c-1.9%200-2.7%201.3-2.7%203.1v8.8C421%20301%20409.3%20305.6%20399%20306.7zM240%2060.2A15.2%2015.2%200%200%201%20255.2%2045h.5A15.2%2015.2%200%201%201%20240%2060.2zM436.8%20214a15.2%2015.2%200%201%201%200-30.5h.4a15.2%2015.2%200%200%201%20-.4%2030.5z%22%2F%3E%3C%2Fsvg%3E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nix-community/naersk) (👨‍💻 52 · 🔀 90 · 📋 170 - 33% open · ⏱️ 29.04.2025):

	```
	git clone https://github.com/nmattia/naersk
	```
</details>
<details><summary><b><a href="https://github.com/mozilla/nixpkgs-mozilla">nixpkgs-mozilla</a></b> (🥈14 ·  ⭐ 560) - Mozillas overlay with Rust toolchains and Firefox. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="data:image/svg+xml;charset=utf8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20512%20512%22%3E%3Cpath%20fill%3D%22%23fab387%22%20d%3D%22M508.5%20249.8%20486.7%20236.2c-.2-2-.3-3.9-.6-5.9l18.7-17.5a7.4%207.4%200%200%200%20-2.4-12.3l-24-9c-.5-1.9-1.1-3.8-1.7-5.6l15-20.8a7.4%207.4%200%200%200%20-4.8-11.5l-25.4-4.2c-.9-1.7-1.8-3.5-2.7-5.2l10.7-23.4a7.4%207.4%200%200%200%20-7-10.4l-25.8%20.9q-1.8-2.2-3.6-4.4L439%2081.8A7.4%207.4%200%200%200%20430.2%2073L405%2078.9q-2.2-1.8-4.4-3.6l.9-25.8a7.4%207.4%200%200%200%20-10.4-7L367.7%2053.2c-1.7-.9-3.4-1.8-5.2-2.7L358.4%2025.1a7.4%207.4%200%200%200%20-11.5-4.8L326%2035.3c-1.9-.6-3.8-1.1-5.6-1.7l-9-24a7.4%207.4%200%200%200%20-12.3-2.4l-17.5%2018.7c-2-.2-3.9-.4-5.9-.6L262.3%203.5a7.4%207.4%200%200%200%20-12.5%200L236.2%2025.3c-2%20.2-3.9%20.3-5.9%20.6L212.9%207.1a7.4%207.4%200%200%200%20-12.3%202.4l-9%2024c-1.9%20.6-3.8%201.1-5.7%201.7l-20.8-15a7.4%207.4%200%200%200%20-11.5%204.8l-4.2%2025.4c-1.7%20.9-3.5%201.8-5.2%202.7L120.9%2042.6a7.4%207.4%200%200%200%20-10.4%207l.9%2025.8c-1.5%201.2-3%202.4-4.4%203.6L81.8%2073A7.4%207.4%200%200%200%2073%2081.8L78.9%20107c-1.2%201.5-2.4%202.9-3.6%204.4l-25.8-.9a7.4%207.4%200%200%200%20-6.4%203.3%207.4%207.4%200%200%200%20-.6%207.1l10.7%2023.4c-.9%201.7-1.8%203.4-2.7%205.2L25.1%20153.6a7.4%207.4%200%200%200%20-4.8%2011.5l15%2020.8c-.6%201.9-1.1%203.8-1.7%205.7l-24%209a7.4%207.4%200%200%200%20-2.4%2012.3l18.7%2017.5c-.2%202-.4%203.9-.6%205.9L3.5%20249.8a7.4%207.4%200%200%200%200%2012.5L25.3%20275.8c.2%202%20.3%203.9%20.6%205.9L7.1%20299.1a7.4%207.4%200%200%200%202.4%2012.3l24%209c.6%201.9%201.1%203.8%201.7%205.7l-15%2020.8a7.4%207.4%200%200%200%204.8%2011.5l25.4%204.2c.9%201.7%201.8%203.5%202.7%205.1L42.6%20391.1a7.4%207.4%200%200%200%20.6%207.1%207.1%207.1%200%200%200%206.4%203.3l25.8-.9q1.8%202.2%203.6%204.4L73%20430.2A7.4%207.4%200%200%200%2081.8%20439L107%20433.1q2.2%201.8%204.4%203.6l-.9%2025.8a7.4%207.4%200%200%200%2010.4%207l23.4-10.7c1.7%20.9%203.4%201.8%205.1%202.7l4.2%2025.4a7.3%207.3%200%200%200%2011.5%204.8l20.8-15c1.9%20.6%203.8%201.1%205.7%201.7l9%2024a7.4%207.4%200%200%200%2012.3%202.4l17.5-18.7c2%20.2%203.9%20.4%205.9%20.6l13.5%2021.8a7.4%207.4%200%200%200%2012.5%200l13.5-21.8c2-.2%203.9-.3%205.9-.6l17.5%2018.7a7.4%207.4%200%200%200%2012.3-2.4l9-24c1.9-.6%203.8-1.1%205.7-1.7l20.8%2015a7.3%207.3%200%200%200%2011.5-4.8l4.2-25.4c1.7-.9%203.5-1.8%205.2-2.7l23.4%2010.7a7.4%207.4%200%200%200%2010.4-7l-.9-25.8q2.2-1.8%204.4-3.6L430.2%20439a7.4%207.4%200%200%200%208.8-8.8L433.1%20405q1.8-2.2%203.6-4.4l25.8%20.9a7.2%207.2%200%200%200%206.4-3.3%207.4%207.4%200%200%200%20.6-7.1L458.8%20367.7c.9-1.7%201.8-3.4%202.7-5.2l25.4-4.2a7.4%207.4%200%200%200%204.8-11.5l-15-20.8c.6-1.9%201.1-3.8%201.7-5.7l24-9a7.4%207.4%200%200%200%202.4-12.3l-18.7-17.5c.2-2%20.4-3.9%20.6-5.9l21.8-13.5a7.4%207.4%200%200%200%200-12.5zm-151%20129.1A13.9%2013.9%200%200%200%20341%20389.5l-7.6%2035.7A187.5%20187.5%200%200%201%20177%20424.4l-7.6-35.7a13.9%2013.9%200%200%200%20-16.5-10.7l-31.5%206.8a187.4%20187.4%200%200%201%20-16.3-19.2H258.3c1.7%200%202.9-.3%202.9-1.9V309.6c0-1.6-1.2-1.9-2.9-1.9H213.5l.1-34.4H262c4.4%200%2023.7%201.3%2029.8%2025.9%201.9%207.6%206.2%2032.1%209.1%2040%202.9%208.8%2014.6%2026.5%2027.1%2026.5H407a187.3%20187.3%200%200%201%20-17.3%2020.1zm25.8%2034.5A15.2%2015.2%200%201%201%20368%20398.1h.4A15.2%2015.2%200%200%201%20383.2%20413.3zm-225.6-.7a15.2%2015.2%200%201%201%20-15.3-15.3h.5A15.3%2015.3%200%200%201%20157.6%20412.6zM69.6%20234.2l32.8-14.6a13.9%2013.9%200%200%200%207.1-18.3L102.7%20186h26.6V305.7H75.7A187.7%20187.7%200%200%201%2069.6%20234.2zM58.3%20198.1a15.2%2015.2%200%200%201%2015.2-15.3H74a15.2%2015.2%200%201%201%20-15.7%2015.2zm155.2%2024.5%20.1-35.3h63.3c3.3%200%2023.1%203.8%2023.1%2018.6%200%2012.3-15.2%2016.7-27.7%2016.7zM399%20306.7c-9.8%201.1-20.6-4.1-22-10.1-5.8-32.5-15.4-39.4-30.6-51.4%2018.9-12%2038.5-29.6%2038.5-53.3%200-25.5-17.5-41.6-29.4-49.5-16.8-11-35.3-13.2-40.3-13.2H116.3A187.5%20187.5%200%200%201%20221.2%2070.1l23.5%2024.6a13.8%2013.8%200%200%200%2019.6%20.4l26.3-25a187.5%20187.5%200%200%201%20128.4%2091.4l-18%2040.6A14%2014%200%200%200%20408%20220.4l34.6%2015.3a187.1%20187.1%200%200%201%20.4%2032.5H423.7c-1.9%200-2.7%201.3-2.7%203.1v8.8C421%20301%20409.3%20305.6%20399%20306.7zM240%2060.2A15.2%2015.2%200%200%201%20255.2%2045h.5A15.2%2015.2%200%201%201%20240%2060.2zM436.8%20214a15.2%2015.2%200%201%201%200-30.5h.4a15.2%2015.2%200%200%201%20-.4%2030.5z%22%2F%3E%3C%2Fsvg%3E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mozilla/nixpkgs-mozilla) (👨‍💻 65 · 🔀 130 · 📋 140 - 35% open · ⏱️ 14.04.2025):

	```
	git clone https://github.com/mozilla/nixpkgs-mozilla
	```
</details>
<details><summary><b><a href="https://github.com/jlesquembre/clj-nix">clj-nix</a></b> (🥈14 ·  ⭐ 160) - Nix helper functions for Clojure projects. <code><a href="http://bit.ly/2M0xmjV">EPL-2.0</a></code></summary>

- [GitHub](https://github.com/jlesquembre/clj-nix) (👨‍💻 15 · 🔀 22 · 📋 68 - 33% open · ⏱️ 07.02.2025):

	```
	git clone https://github.com/jlesquembre/clj-nix
	```
</details>
<details><summary><b><a href="https://github.com/loophp/nix-shell">nix-shell</a></b> (🥉12 ·  ⭐ 170) - Nix shells for PHP development. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.php.net/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/loophp/nix-shell) (👨‍💻 8 · 🔀 13 · 📋 15 - 20% open · ⏱️ 05.05.2025):

	```
	git clone https://github.com/loophp/nix-shell
	```
</details>
<details><summary><b><a href="https://github.com/inscapist/ruby-nix">ruby-nix</a></b> (🥉11 ·  ⭐ 130) - Generates reproducible ruby/bundler app environment with Nix. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.ruby-lang.org/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/inscapist/ruby-nix) (👨‍💻 6 · 🔀 7 · 📋 19 - 15% open · ⏱️ 14.04.2025):

	```
	git clone https://github.com/sagittaros/ruby-nix
	```
</details>
<details><summary>Show 24 hidden projects...</summary>

- <b><a href="https://github.com/svanderburg/node2nix">node2nix</a></b> (🥈16 ·  ⭐ 540 · 💀) - Generate Nix expression from a `package.json` (or `package-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/NixOS/cabal2nix">cabal2nix</a></b> (🥈16 ·  ⭐ 370) - Converts a Cabal file into a Nix build expression. <code>❗Unlicensed</code>
- <b><a href="https://github.com/justinwoo/easy-purescript-nix">Easy PureScript Nix</a></b> (🥈13 ·  ⭐ 200 · 💀) - A project to easily use PureScript and other tools.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/fossar/nix-phps">nix-phps</a></b> (🥈13 ·  ⭐ 73) - Flake containing old and unmaintained PHP versions (intended for CI.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.php.net/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/nix-community/bundix">Bundix</a></b> (🥉12 ·  ⭐ 170 · 💀) - Generates a Nix expression for your Bundler-managed.. <code>❗Unlicensed</code> <code><img src="https://www.ruby-lang.org/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/nix-community/zon2nix">zon2nix</a></b> (🥉12 ·  ⭐ 92) - Convert the dependencies in `build.zig.zon` to a Nix expression. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/timbertson/opam2nix">opam2nix</a></b> (🥉11 ·  ⭐ 93) - Generate Nix expressions from opam packages. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/svanderburg/composer2nix">composer2nix</a></b> (🥉11 ·  ⭐ 92 · 💀) - Generate Nix expressions to build composer packages. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/purs-nix/purs-nix">purs-nix</a></b> (🥉11 ·  ⭐ 76) - CLI and library combo designed for managing PureScript projects using Nix. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/lenianiva/lean4-nix">lean4-nix</a></b> (🥉11 ·  ⭐ 42) - Nix flake build for Lean 4, and `lake2nix`. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/nix-community/npmlock2nix">npmlock2nix</a></b> (🥉10 ·  ⭐ 140 · 💀) - Generate Nix expressions from a `package-lock.json` (in-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/cachix/elm2nix">elm2nix</a></b> (🥉9 ·  ⭐ 110) - Convert `elm.json` into Nix expressions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/yusdacra/rust-nix-templater">rust-nix-templater</a></b> (🥉9 ·  ⭐ 49 · 💀) - Generates Nix build and development files for Rust.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="data:image/svg+xml;charset=utf8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20512%20512%22%3E%3Cpath%20fill%3D%22%23fab387%22%20d%3D%22M508.5%20249.8%20486.7%20236.2c-.2-2-.3-3.9-.6-5.9l18.7-17.5a7.4%207.4%200%200%200%20-2.4-12.3l-24-9c-.5-1.9-1.1-3.8-1.7-5.6l15-20.8a7.4%207.4%200%200%200%20-4.8-11.5l-25.4-4.2c-.9-1.7-1.8-3.5-2.7-5.2l10.7-23.4a7.4%207.4%200%200%200%20-7-10.4l-25.8%20.9q-1.8-2.2-3.6-4.4L439%2081.8A7.4%207.4%200%200%200%20430.2%2073L405%2078.9q-2.2-1.8-4.4-3.6l.9-25.8a7.4%207.4%200%200%200%20-10.4-7L367.7%2053.2c-1.7-.9-3.4-1.8-5.2-2.7L358.4%2025.1a7.4%207.4%200%200%200%20-11.5-4.8L326%2035.3c-1.9-.6-3.8-1.1-5.6-1.7l-9-24a7.4%207.4%200%200%200%20-12.3-2.4l-17.5%2018.7c-2-.2-3.9-.4-5.9-.6L262.3%203.5a7.4%207.4%200%200%200%20-12.5%200L236.2%2025.3c-2%20.2-3.9%20.3-5.9%20.6L212.9%207.1a7.4%207.4%200%200%200%20-12.3%202.4l-9%2024c-1.9%20.6-3.8%201.1-5.7%201.7l-20.8-15a7.4%207.4%200%200%200%20-11.5%204.8l-4.2%2025.4c-1.7%20.9-3.5%201.8-5.2%202.7L120.9%2042.6a7.4%207.4%200%200%200%20-10.4%207l.9%2025.8c-1.5%201.2-3%202.4-4.4%203.6L81.8%2073A7.4%207.4%200%200%200%2073%2081.8L78.9%20107c-1.2%201.5-2.4%202.9-3.6%204.4l-25.8-.9a7.4%207.4%200%200%200%20-6.4%203.3%207.4%207.4%200%200%200%20-.6%207.1l10.7%2023.4c-.9%201.7-1.8%203.4-2.7%205.2L25.1%20153.6a7.4%207.4%200%200%200%20-4.8%2011.5l15%2020.8c-.6%201.9-1.1%203.8-1.7%205.7l-24%209a7.4%207.4%200%200%200%20-2.4%2012.3l18.7%2017.5c-.2%202-.4%203.9-.6%205.9L3.5%20249.8a7.4%207.4%200%200%200%200%2012.5L25.3%20275.8c.2%202%20.3%203.9%20.6%205.9L7.1%20299.1a7.4%207.4%200%200%200%202.4%2012.3l24%209c.6%201.9%201.1%203.8%201.7%205.7l-15%2020.8a7.4%207.4%200%200%200%204.8%2011.5l25.4%204.2c.9%201.7%201.8%203.5%202.7%205.1L42.6%20391.1a7.4%207.4%200%200%200%20.6%207.1%207.1%207.1%200%200%200%206.4%203.3l25.8-.9q1.8%202.2%203.6%204.4L73%20430.2A7.4%207.4%200%200%200%2081.8%20439L107%20433.1q2.2%201.8%204.4%203.6l-.9%2025.8a7.4%207.4%200%200%200%2010.4%207l23.4-10.7c1.7%20.9%203.4%201.8%205.1%202.7l4.2%2025.4a7.3%207.3%200%200%200%2011.5%204.8l20.8-15c1.9%20.6%203.8%201.1%205.7%201.7l9%2024a7.4%207.4%200%200%200%2012.3%202.4l17.5-18.7c2%20.2%203.9%20.4%205.9%20.6l13.5%2021.8a7.4%207.4%200%200%200%2012.5%200l13.5-21.8c2-.2%203.9-.3%205.9-.6l17.5%2018.7a7.4%207.4%200%200%200%2012.3-2.4l9-24c1.9-.6%203.8-1.1%205.7-1.7l20.8%2015a7.3%207.3%200%200%200%2011.5-4.8l4.2-25.4c1.7-.9%203.5-1.8%205.2-2.7l23.4%2010.7a7.4%207.4%200%200%200%2010.4-7l-.9-25.8q2.2-1.8%204.4-3.6L430.2%20439a7.4%207.4%200%200%200%208.8-8.8L433.1%20405q1.8-2.2%203.6-4.4l25.8%20.9a7.2%207.2%200%200%200%206.4-3.3%207.4%207.4%200%200%200%20.6-7.1L458.8%20367.7c.9-1.7%201.8-3.4%202.7-5.2l25.4-4.2a7.4%207.4%200%200%200%204.8-11.5l-15-20.8c.6-1.9%201.1-3.8%201.7-5.7l24-9a7.4%207.4%200%200%200%202.4-12.3l-18.7-17.5c.2-2%20.4-3.9%20.6-5.9l21.8-13.5a7.4%207.4%200%200%200%200-12.5zm-151%20129.1A13.9%2013.9%200%200%200%20341%20389.5l-7.6%2035.7A187.5%20187.5%200%200%201%20177%20424.4l-7.6-35.7a13.9%2013.9%200%200%200%20-16.5-10.7l-31.5%206.8a187.4%20187.4%200%200%201%20-16.3-19.2H258.3c1.7%200%202.9-.3%202.9-1.9V309.6c0-1.6-1.2-1.9-2.9-1.9H213.5l.1-34.4H262c4.4%200%2023.7%201.3%2029.8%2025.9%201.9%207.6%206.2%2032.1%209.1%2040%202.9%208.8%2014.6%2026.5%2027.1%2026.5H407a187.3%20187.3%200%200%201%20-17.3%2020.1zm25.8%2034.5A15.2%2015.2%200%201%201%20368%20398.1h.4A15.2%2015.2%200%200%201%20383.2%20413.3zm-225.6-.7a15.2%2015.2%200%201%201%20-15.3-15.3h.5A15.3%2015.3%200%200%201%20157.6%20412.6zM69.6%20234.2l32.8-14.6a13.9%2013.9%200%200%200%207.1-18.3L102.7%20186h26.6V305.7H75.7A187.7%20187.7%200%200%201%2069.6%20234.2zM58.3%20198.1a15.2%2015.2%200%200%201%2015.2-15.3H74a15.2%2015.2%200%201%201%20-15.7%2015.2zm155.2%2024.5%20.1-35.3h63.3c3.3%200%2023.1%203.8%2023.1%2018.6%200%2012.3-15.2%2016.7-27.7%2016.7zM399%20306.7c-9.8%201.1-20.6-4.1-22-10.1-5.8-32.5-15.4-39.4-30.6-51.4%2018.9-12%2038.5-29.6%2038.5-53.3%200-25.5-17.5-41.6-29.4-49.5-16.8-11-35.3-13.2-40.3-13.2H116.3A187.5%20187.5%200%200%201%20221.2%2070.1l23.5%2024.6a13.8%2013.8%200%200%200%2019.6%20.4l26.3-25a187.5%20187.5%200%200%201%20128.4%2091.4l-18%2040.6A14%2014%200%200%200%20408%20220.4l34.6%2015.3a187.1%20187.1%200%200%201%20.4%2032.5H423.7c-1.9%200-2.7%201.3-2.7%203.1v8.8C421%20301%20409.3%20305.6%20399%20306.7zM240%2060.2A15.2%2015.2%200%200%201%20255.2%2045h.5A15.2%2015.2%200%201%201%20240%2060.2zM436.8%20214a15.2%2015.2%200%201%201%200-30.5h.4a15.2%2015.2%200%200%201%20-.4%2030.5z%22%2F%3E%3C%2Fsvg%3E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/nix-community/napalm">Napalm</a></b> (🥉8 ·  ⭐ 110 · 💤) - Support for building npm packages in Nix with a lightweight npm registry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/zaninime/sbt-derivation">sbt-derivation</a></b> (🥉8 ·  ⭐ 72 · 💀) - mkDerivation for sbt, similar to buildGoModule. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pwm/nixkell">nixkell</a></b> (🥉7 ·  ⭐ 110) - A Haskell project template using Nix and direnv. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.haskell.org/img/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/nix-community/crystal2nix">crystal2nix</a></b> (🥉7 ·  ⭐ 17 · 💤) - Convert `shard.lock` into Nix expressions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/bwkam/kebab">kebab</a></b> (🥉7 ·  ⭐ 2) - Haxe packages for Nix. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/boredom101/nixduino">nixduino</a></b> (🥉6 ·  ⭐ 47 · 💀) - Nix-based tool to help build Arduino sketches. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/arnarg/nix-gleam">nix-gleam</a></b> (🥉6 ·  ⭐ 27 · 💤) - Generic Nix builder for Gleam applications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/matthewbauer/nix-haskell-mode">nix-haskell-mode</a></b> (🥉5 ·  ⭐ 28 · 💀) - Automatic Haskell setup in Emacs. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://www.haskell.org/img/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/stephank/composer-plugin-nixify">composer-plugin-nixify</a></b> (🥉5 ·  ⭐ 18 · 💀) - Composer plugin to help with Nix packaging. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/MadMcCrow/haxix">haxix</a></b> (🥉5 ·  ⭐ 3 · 💤) - Nix flake to build haxe/Heaps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/fossar/composition-c4">composition-c4</a></b> (🥉4 ·  ⭐ 11 · 💀) - Support for building composer packages from a `composer.lock`.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## NixOS Modules

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/nix-community/home-manager">Home Manager</a></b> (🥇26 ·  ⭐ 8K) - Manage your user configuration just like NixOS. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nix-community/home-manager) (👨‍💻 1.3K · 🔀 2K · 📋 2.6K - 26% open · ⏱️ 11.05.2025):

	```
	git clone https://github.com/nix-community/home-manager
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/NixOS-WSL">NixOS-WSL</a></b> (🥇23 ·  ⭐ 2.2K) - Modules for running NixOS on the Windows Subsystem for Linux. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nix-community/NixOS-WSL) (👨‍💻 40 · 🔀 140 · 📥 51K · 📋 220 - 16% open · ⏱️ 05.05.2025):

	```
	git clone https://github.com/nix-community/NixOS-WSL
	```
</details>
<details><summary><b><a href="https://github.com/nix-darwin/nix-darwin">nix-darwin</a></b> (🥈22 ·  ⭐ 3.9K) - Manage macOS configuration just like on NixOS. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nix-darwin/nix-darwin) (👨‍💻 240 · 🔀 510 · 📋 680 - 35% open · ⏱️ 08.05.2025):

	```
	git clone https://github.com/LnL7/nix-darwin
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/nixvim">NixVim</a></b> (🥈22 ·  ⭐ 2.2K) - A NeoVim distribution built with Nix modules and Nixpkgs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nix-community/nixvim) (👨‍💻 220 · 🔀 320 · 📋 760 - 14% open · ⏱️ 11.05.2025):

	```
	git clone https://github.com/nix-community/nixvim
	```
</details>
<details><summary><b><a href="https://github.com/fort-nix/nix-bitcoin">nix-bitcoin</a></b> (🥈22 ·  ⭐ 560) - Modules and packages for Bitcoin nodes with higher-layer protocols.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fort-nix/nix-bitcoin) (👨‍💻 31 · 🔀 110 · 📥 7.8K · 📋 200 - 15% open · ⏱️ 09.05.2025):

	```
	git clone https://github.com/fort-nix/nix-bitcoin
	```
</details>
<details><summary><b><a href="https://github.com/NotAShelf/nvf">nvf</a></b> (🥉21 ·  ⭐ 810 · ➕) - Highly modular, configurable, extensible and easy to use Neovim.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/NotAShelf/nvf) (👨‍💻 71 · 🔀 110 · 📋 250 - 18% open · ⏱️ 11.05.2025):

	```
	git clone https://github.com/notashelf/nvf
	```
</details>
<details><summary><b><a href="https://github.com/danth/stylix">Stylix</a></b> (🥉20 ·  ⭐ 1.6K) - System-wide colorscheming and typography for NixOS. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/danth/stylix) (👨‍💻 140 · 🔀 210 · 📋 480 - 33% open · ⏱️ 11.05.2025):

	```
	git clone https://github.com/danth/stylix
	```
</details>
<details><summary><b><a href="https://github.com/ibizaman/selfhostblocks">Self Host Blocks</a></b> (🥉15 ·  ⭐ 280) - Modular server management based on NixOS modules and.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/ibizaman/selfhostblocks) (👨‍💻 6 · 🔀 7 · 📋 97 - 70% open · ⏱️ 13.04.2025):

	```
	git clone https://github.com/ibizaman/selfhostblocks
	```
</details>
<details><summary><b><a href="https://github.com/nix-community/impermanence">impermanence</a></b> (🥉14 ·  ⭐ 1.4K) - Lets you choose what files and directories you want to keep.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nix-community/impermanence) (👨‍💻 35 · 🔀 100 · 📋 160 - 45% open · ⏱️ 25.01.2025):

	```
	git clone https://github.com/nix-community/impermanence
	```
</details>
<details><summary><b><a href="https://github.com/musnix/musnix">musnix</a></b> (🥉14 ·  ⭐ 690) - Do real-time audio work in NixOS. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/musnix/musnix) (👨‍💻 37 · 🔀 57 · 📋 65 - 16% open · ⏱️ 06.03.2025):

	```
	git clone https://github.com/musnix/musnix
	```
</details>
<details><summary><b><a href="https://github.com/oddlama/nix-topology">nix-topology</a></b> (🥉13 ·  ⭐ 700) - Generate infrastructure and network diagrams directly from your.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oddlama/nix-topology) (👨‍💻 21 · 🔀 32 · 📋 22 - 40% open · ⏱️ 08.04.2025):

	```
	git clone https://github.com/oddlama/nix-topology
	```
</details>
<details><summary><b><a href="https://github.com/cynicsketch/nix-mineral">nix-mineral</a></b> (🥉13 ·  ⭐ 260) - Conveniently and reasonably harden NixOS. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cynicsketch/nix-mineral) (👨‍💻 6 · 🔀 13 · 📋 43 - 69% open · ⏱️ 07.05.2025):

	```
	git clone https://github.com/cynicsketch/nix-mineral
	```
</details>
<details><summary><b><a href="https://github.com/SenchoPens/base16.nix">base16.nix</a></b> (🥉11 ·  ⭐ 230) - Flake way to theme programs in base16 colorschemes, mustache template.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SenchoPens/base16.nix) (👨‍💻 7 · 🔀 10 · 📋 16 - 12% open · ⏱️ 06.05.2025):

	```
	git clone https://github.com/SenchoPens/base16.nix
	```
</details>
<br>

## NixOS Configuration Editors

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/snowfallorg/nix-software-center">Nix Software Center</a></b> (🥇9 ·  ⭐ 680) - Install and manage Nix packages. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/snowfallorg/nixos-conf-editor">NixOS Configuration Editor</a></b> (🥇9 ·  ⭐ 550 · 💀) - Graphical editor for NixOS configuration. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Overlays

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/nix-community/NUR">NUR</a></b> (🥇23 ·  ⭐ 1.5K) - Nix User Repositories. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nix-community/NUR) (👨‍💻 470 · 🔀 370 · 📋 120 - 22% open · ⏱️ 11.05.2025):

	```
	git clone https://github.com/nix-community/NUR
	```
</details>
<details><summary><b><a href="https://github.com/chaotic-cx/nyx">chaotic-nyx</a></b> (🥈18 ·  ⭐ 460) - Daily bumped bleeding edge packages like `mesa_git` & others that.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chaotic-cx/nyx) (👨‍💻 39 · 🔀 47 · 📋 83 - 14% open · ⏱️ 11.05.2025):

	```
	git clone https://github.com/chaotic-cx/nyx
	```
</details>
<details><summary><b><a href="https://github.com/numtide/system-manager">System Manager</a></b> (🥉13 ·  ⭐ 990) - A non-NixOS Linux system configuration tool built on Nix. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/numtide/system-manager) (👨‍💻 19 · 🔀 28 · 📋 55 - 63% open · ⏱️ 08.04.2025):

	```
	git clone https://github.com/numtide/system-manager
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/nix-community/nixpkgs-wayland">nixpkgs-wayland</a></b> (🥈18 ·  ⭐ 560) - Bleeding-edge Wayland packages. <code>❗Unlicensed</code>
- <b><a href="https://github.com/bandithedoge/nixpkgs-firefox-darwin">nixpkgs-firefox-darwin</a></b> (🥉12 ·  ⭐ 66) - Automatically updated Firefox binary packages for macOS. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/freuk/awesome-nix-hpc">awesome-nix-hpc</a></b> (🥉6 ·  ⭐ 84) - High Performance Computing package sets. <code>❗Unlicensed</code>
</details>
<br>

## Distributions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/nixos-bsd/nixbsd">nixbsd</a></b> (🥇14 ·  ⭐ 680) - A NixOS fork with a FreeBSD kernel. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nixos-bsd/nixbsd) (👨‍💻 6 · 🔀 26 · 📋 29 - 37% open · ⏱️ 28.03.2025):

	```
	git clone https://github.com/nixos-bsd/nixbsd
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/nix-community/NixNG">NixNG</a></b> (🥉8 ·  ⭐ 360) - A GNU/Linux distribution similar to NixOS, defining difference is a.. <code>❗Unlicensed</code>
</details>

---

## Related Resources

- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/tolkonepiu/best-of-nix/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/tolkonepiu/best-of-nix/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/tolkonepiu/best-of-nix/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/tolkonepiu/best-of-nix/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/tolkonepiu/best-of-nix/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
