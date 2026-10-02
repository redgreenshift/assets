# Badges

This folder contains SVG files for custom badges used in GitHub README files across multiple projects.

Badges here are shared assets rather than project-specific logos or artwork. Project-specific assets belong in their respective project folders.

## Usage

Reference a badge in a README using its raw GitHub URL:

```markdown
![Badge description](https://raw.githubusercontent.com/redgreenshift/assets/main/badges/badge-name.svg)
```

Replace `badge-name.svg` with the SVG filename, and use alt text that describes the badge.

If the repository's default branch is not `main`, replace `main` in the
URL with the appropriate branch name. For stable references, consider
using a commit hash instead of a branch name.

## Adding a badge

When adding a badge:

- Use a descriptive filename.
- Prefer lowercase letters with hyphens between words for new files.
- Preserve an existing filename once it has been published or referenced.
- Use capitalization only when it is intentional—for example, to preserve
  an established product, project, or title style.
- Keep the SVG self-contained so it can be used directly in a README.
- Preserve the visible artwork of third-party logos and marks.
- Add an attribution comment to every third-party SVG and every SVG
  containing inspired artwork.
- Add or update the corresponding entry in [`ATTRIBUTIONS.md`](ATTRIBUTIONS.md).

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

## Attribution

Each SVG contains an attribution comment with its source, creator or
project, license or permission terms, and changes.

A directory-wide attribution index is maintained in
[`ATTRIBUTIONS.md`](ATTRIBUTIONS.md).

### Attribution comment format

Use this format for third-party SVGs:

```HTML
<!--
Source: [direct link to the original icon or project]
Creator: [name, or "Not specified by source"]
Source/distributor: [name, if applicable]
License: [license, or "Not specified"]
Permission terms: [link to applicable terms, if applicable]
Changes: [brief description, or "None to the visible artwork"]
-->
```


## Copyright and reuse

The repository-level copyright and reuse statement in
[`../README.md`](../README.md) does not apply to the files in this
directory.

Each badge may contain original artwork, third-party artwork, logos,
trademarks, or other materials whose rights belong to their respective
owners. The presence of a file in this directory does not mean that it
is owned by Jared Ivey or available for unrestricted reuse.

Do not apply this repository's copyright notice or software license to
third-party artwork, logos, trademarks, or other material that Jared
Ivey is not authorized to license. Any license identified for a file
applies only to the rights that the identified creator or distributor is
authorized to grant.

Refer to the attribution comment inside each SVG for that file's source,
creator, license or permission terms, and any modifications. Where no
explicit license is specified, the attribution will say so rather than
implying that the file is openly licensed.

The badges are used in project documentation for identification and
descriptive purposes. Their inclusion does not imply affiliation with,
sponsorship by, or endorsement from any referenced project, organization,
or trademark owner.

For a directory-wide index, see
[`ATTRIBUTIONS.md`](ATTRIBUTIONS.md). The attribution comment inside each
SVG is the portable, file-level record; `ATTRIBUTIONS.md` is a
convenience index and may summarize the same information.

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
[`ATTRIBUTIONS.md`](ATTRIBUTIONS.md) for file-specific source,
provenance, license, and permission information.

Trademark references are used solely for identification,
compatibility, historical reference, commentary, or descriptive purposes.

## Documentation precedence

When documentation differs:

1. The attribution comment embedded in the SVG file is the authoritative
file-level record.
2. `ATTRIBUTIONS.md` is a convenience index.
3. General repository documentation applies only where it does not conflict
with file-specific documentation.
