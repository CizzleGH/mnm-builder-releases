# MNM Builder releases

Installers for the **MNM Builder**, the desktop editor for meganightmarket.com.
This repository holds release files only; the Builder's source lives with the
site, in a private repository.

## Updating an installed Builder

You normally don't need anything from this page:

- **Builder 1.4 or newer** checks here when it opens and offers the update
  itself (*Update now*, then *Restart now*). *Check for updates* is under
  Utilities, bottom left.
- **Older Builders** show a pink bar across the bottom of the page with an
  **Update now** button, once they've synced the site.

To update by hand instead, download `MNM-Builder-Update.exe` from the latest
release and run it. It replaces the app and keeps your site folder and
settings. Windows may warn that the file is unrecognised: choose *More info*,
then *Run anyway*.

## First-time installs

`MNM-Builder-Update.exe` updates an existing install; it does not include the
site. For a first install, ask whoever looks after the site for the full
`MNM-Builder-Setup.exe`.

## Troubleshooting

Most problems below were fixed in a later release, so **update first** (see
above) and try again.

| What you see | What to do |
| --- | --- |
| Windows says the installer is *unrecognised* / "Windows protected your PC" | Choose *More info*, then *Run anyway*. The file is safe as long as it came from this page's Releases. |
| The update stops on **"Failed to uninstall old application files"** | Close the Builder and run `MNM-Builder-Update.exe` again. Builder 1.5.1 and newer close themselves before updating. |
| The preview won't start: **"'next' is not recognized"** | The site's packages were only partly installed. Update to 1.6.3 or newer: it notices and reinstalls them. Keep the Builder open while it works. |
| The site copy is broken in some other way | In a full install, use *Settings → Replace with a fresh copy* (1.6.2+). It puts a clean copy in a new folder next to the old one, so nothing gets deleted. |
| Panels and text are too small (Surface Pro and other small high-DPI screens) | *Settings → Builder size* (1.6.4+) makes the Builder bigger without changing how the website looks. |
| No update offered, or you can't tell which version you have | Open *Utilities → Check for updates* (bottom left). Compare with the newest entry under [Releases](https://github.com/CizzleGH/mnm-builder-releases/releases/latest). |

If none of this helps, send whoever looks after the site the Builder version,
what you clicked, and a screenshot of the message.
