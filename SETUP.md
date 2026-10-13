# Updating this profile

Edit `config.json` to change the animated name, profile details, status, or skills.
Edit `README.md` to change the introduction and project links.

The portrait source is stored in `assets/profile-source.jpg`. Replace it with a
square portrait and regenerate the artwork to change the ASCII portrait.

With Python 3.12 or newer, run:

```sh
python -m pip install -r scripts/requirements.txt
python scripts/generate.py
```

The live generator reads public GitHub data. `--demo` is for a local layout
preview only; regenerate with live data before publishing.

The **Refresh profile visuals** workflow refreshes the committed SVG files
daily and can also be started from the repository's Actions tab.

The language bars count public, non-fork repositories by their primary
language. They do not measure proficiency or the number of lines written.

See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for template attribution.
