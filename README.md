# Y2JB US Package Downloader

A lightweight GitHub Pages download page for three pre-assembled US-region packages. Visitors select the firmware build and download one complete file; there is no in-browser PKG joining step.

## Release asset filenames

Upload the prepared package files to a published GitHub Release in this repository using these exact filenames so the download buttons work without editing `index.html`:

- `Y2JB-US-FW-4.03-12.40.pkg` — YouTube build `01.000.003`
- `Y2JB-US-FW-12.60-PLUS.pkg` — YouTube build `01.000.030`
- `Y2JB-US-FW-13.40-PLUS.pkg` — YouTube build `01.009.253`

The page links to the latest release's assets. If you publish a newer release, attach all three files again.

## Publish the website

1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then save.
4. GitHub Pages will publish the site at `https://AmirHAskari.github.io/Y2JB-Helper/`.

## Upload the package files

1. Open the repository's **Releases** page and choose **Draft a new release**.
2. Use tag `v1.0` and title `Y2JB US Packages v1.0`.
3. Attach the three prepared files, using the exact filenames listed above.
4. Publish the release.

**Important:** GitHub Releases and GitHub Pages are public. Only upload files you are allowed to distribute. The download buttons will return 404 until a published release contains assets with the expected filenames.
