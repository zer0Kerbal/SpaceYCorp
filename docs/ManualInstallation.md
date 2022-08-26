---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
SpaceY Corp (SYC)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# SpaceY Corp (SYC)

[Home](./index.md)

Adds SpaceY Corp's agent, flags, and common config files used in all SpaceY add-ons for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `SpaceY` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/SpaceY/SpaceYCorp`
* Extract the package's `SpaceY/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/SpaceYCorp` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/SpaceY/SpaceYCorp`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/SpaceY/SpaceYCorp`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [SpaceY]
      + [SpaceYCorp]
        + [Agencies]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * CC-BY-SA-4.0.txt
        * changelog.md
          ManualInstallation.htm
        * readme.htm
        * SpaceYCorp.version
        ...
      ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none
