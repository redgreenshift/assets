# Assets

Image and media files used by my projects. Keeping larger assets here avoids adding them to each project's Git history.

## Organization

Assets are grouped by the repository that uses them. Files used by multiple repositories go in `shared/`.

```text
assets/
├── README.md
├── project-one/
│   └── demo.gif
├── project-two/
│   └── screenshot.png
├── shared/
│   └── logo.svg
└── third-party/
    └── meme.jpg
```

Use lowercase folder and file names, and organize files into descriptive subfolders when needed.

## Using an asset

Reference an asset from a project README with its raw GitHub URL:

```text
![Demo](https://raw.githubusercontent.com/redgreenshift/assets/main/project-one/demo.gif)
```

Use `main` to show the latest version of the file. To pin the image to a specific version, use a commit hash in place of `main`.

## Copyright and reuse

Unless a file says otherwise, my original assets in this repository are © Jared Ivey and are not licensed for reuse without my permission. Files in `third-party/` are not owned by me and are not covered by any license or permissions I grant. For example, `third-party/no-vibe-coding.jpg` is a meme I created using a screenshot from *Black Panther*; I do not own or claim rights to the underlying film image.

## AI-assisted contributions

AI tools may be used, but contributors must understand and verify the code they submit and take responsibility for it. AI-generated code is subject to the same standards of review and correctness as any other code.
