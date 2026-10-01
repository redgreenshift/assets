# Badges

This folder contains SVG files for custom badges used in GitHub README files across multiple projects.

Badges here are shared assets rather than project-specific logos or artwork. Project-specific assets belong in their respective project folders.

## Copyright and reuse

The repository-level copyright and reuse statement in [`../README.md`](../README.md)
does not apply to the files in this directory.

Each badge may contain third-party artwork, logos, trademarks, or other
materials whose rights belong to their respective owners. The presence
of a file in this directory does not mean that it is owned by Jared Ivey,
covered by this repository's license, or available for unrestricted reuse.

Refer to the attribution comment inside each SVG for that file's source,
creator, license or permission terms, and any modifications. Where no
explicit license is specified, the attribution will say so rather than
implying that the file is openly licensed.

The badges are used in project documentation for identification and
descriptive purposes. Their inclusion does not imply affiliation with,
sponsorship by, or endorsement from any referenced project, organization,
or trademark owner.

## Trademarks and third-party rights

Some badges in this directory include or refer to third-party names,
logos, product names, and other marks. Those names and marks remain the
property of their respective owners.

The presence of a name or logo in this directory does not imply
affiliation with, sponsorship by, or endorsement from the relevant
company, project, organization, or trademark owner.

Any license identified for an SVG applies only to the copyrightable
artwork and other rights that the identified creator or distributor is
authorized to license. It does not grant permission to use a
third-party name or trademark beyond what applicable law or the
trademark owner's policies allow.

See the attribution comment inside each SVG and
Badge inventory below for file-specific source,
provenance, license, and permission information.

## Usage

Reference a badge in a README using its raw GitHub URL:

```markdown
![Badge description](https://raw.githubusercontent.com/redgreenshift/assets/main/badges/badge-name.svg)
```

Replace `badge-name.svg` with the SVG filename, and use alt text that describes the badge.

If the repository's default branch is not `main`, replace `main` in the
URL with the appropriate branch name. For stable references, consider
using a commit hash instead of a branch name.


Adding a badge
- Use a descriptive, lowercase filename, with hyphens between words.
- Keep the SVG self-contained so it can be used directly in a README.
- Add or update the badge’s description here when you add it.

## Adding a badge

When adding a badge:

- Use a descriptive lowercase filename.
- Separate words with hyphens.
- Keep the SVG self-contained.
- Preserve the visible artwork of third-party logos and marks.
- Add an attribution comment to the SVG.
- Add or update the badge's entry in the inventory below.
- Do not apply this repository's copyright notice or software license to third-party artwork.

## Badge inventory

The attribution comment inside each SVG is the authoritative file-level
record. This table is a convenience index and may summarize the
same information.

| File | Description | Source/inspiration and creator | License/permission |
|---|---|---|---|
| <img src="logo-microsoft-mono-black.svg" width=32 height=32 /><br>[`logo-microsoft-mono-black.svg`](logo-microsoft-mono-black.svg) | Microsoft logo monochrome black | [SVG Repo](https://www.svgrepo.com/svg/327378/logo-microsoft) | [MIT License](https://www.svgrepo.com/page/licensing/#MIT) |
| <img src="logo-microsoft-mono-white.svg" width=32 height=32 /><br>[`logo-microsoft-mono-white.svg`](logo-microsoft-mono-white.svg) | Microsoft logo monochrome white | [SVG Repo](https://www.svgrepo.com/svg/327378/logo-microsoft) | [MIT License](https://www.svgrepo.com/page/licensing/#MIT) |
| <img src="Microsoft_logo.svg" width=32 height=32 /><br>[`Microsoft_logo.svg`](Microsoft_logo.svg) | Microsoft logo | [Wikimedia](https://en.wikipedia.org/wiki/File:Microsoft_logo.svg) | Public Domain |
| <img src="Msdos-icon.svg" width=32 height=32 /><br>[`Msdos-icon.svg`](Msdos-icon.svg) | MS-DOS icon | [Wikimedia](https://commons.wikimedia.org/wiki/File:Msdos-icon.png) | [MIT License](https://opensource.org/license/mit) |
| <img src="QBasic-by-Example.svg" width=48 height=20 /><br>[`QBasic-by-Example.svg`](QBasic-by-Example.svg) | QBasic by Example-inspired logo | Original artwork by Jared Ivey, based on the cover design of *QBasic by Example* | [MIT License](https://opensource.org/license/mit) for Jared Ivey's original artwork; underlying book artwork and marks not claimed |
| <img src="squeak-smalltalk-logo.svg" width=64 height=64 /><br>[`squeak-smalltalk-logo.svg`](squeak-smalltalk-logo.svg) | Squeak logo | [SVGBrand](https://svgbrand.com/logo/squeak) | [Permission terms](https://svgbrand.com/terms-conditions); no explicit license specified |
| <img src="turbo-pascal.svg" width=100 height=20 /><br>[`turbo-pascal.svg`](turbo-pascal.svg) | Turbo Pascal-inspired logo | Original artwork by Jared Ivey | [MIT License](https://opensource.org/license/mit) for original artwork; Turbo Pascal name and marks not claimed |
| <img src="visual-studio-mono-white.svg" width=32 height=32 /><br>[`visual-studio-mono-white.svg`](visual-studio-mono-white.svg) | Visual Studio logo monochrome white | [SVG Repo](https://www.svgrepo.com/svg/342346/visual-studio) | [GPL License](https://www.svgrepo.com/page/licensing/#GPL) |
| <img src="visual-studio-svgrepo-com-mono-black.svg" width=32 height=32 /><br>[`visual-studio-svgrepo-com-mono-black.svg`](visual-studio-svgrepo-com-mono-black.svg) | Visual Studio logo monochrome black | [SVG Repo](https://www.svgrepo.com/svg/342346/visual-studio) | [GPL License](https://www.svgrepo.com/page/licensing/#GPL) |

## Shields.io badges

Some badges use an SVG encoded as base64 in a Shields.io URL. In those
cases, the attribution comment remains part of the encoded SVG data,
even though it is not visible when the badge is rendered.

Example:

```markdown
[![Badge description](https://img.shields.io/badge/Badge_description.svg?logo=data:image/svg%2bxml;base64,INSERT_BASE64_DATA_HERE)](https://www.example.com)
```

Before publishing a Shields.io badge:

1. Add the attribution comment to the SVG.
1. [Base64-encode](https://www.base64encode.org/) the complete SVG, including the attribution comment.
1. Insert the encoded data into the Shields.io URL.
1. Verify that the rendered badge displays correctly.
1. Keep the original attributed SVG in this directory.

## Attribution comment format

Use this format for third-party SVGs:

<!--
Source: [direct link to the original icon or project]
Creator: [name, or "Not specified by source"]
Source/distributor: [name, if applicable]
License: [license, or "Not specified"]
Permission terms: [link to applicable terms, if applicable]
Changes: [brief description, or "None to the visible artwork"]
-->


<!--
Source: [direct link to the original icon or project]
Creator/project: [name]
License: [license and link to its terms]
Changes: [brief description, or "none"]
-->

