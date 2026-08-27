# TMDbPlayers for TMDB Helper

Merged player pack for [TheMovieDb Helper](https://github.com/jurialmunkey/plugin.video.themoviedb.helper). Combines players from [a4k-openproject/json.openplayers](https://github.com/a4k-openproject/json.openplayers) with [slrwin/tmdbh.players](https://github.com/slrwin/tmdbh.players) (G-Man's maintained pack).

## Install

**TheMovieDb Helper** → **Settings** → **Players** → **Update players from URL**

```
https://api.github.com/repos/Goldenfreddy0703/TMDbPlayers/zipball
```

Or add this URL in the same settings field.

## Manual install

Download individual `.json` player files (or the full zip from the URL above) and copy them into:

```
<kodi userdata>/addon_data/plugin.video.themoviedb.helper/players/
```

## Notes

- **Kodi 20+** recommended. Many players target Nexus, Omega, and Pulsar.
- For **Auto-Play** players, configure the target addon's auto-play settings first, or they may default to Source Select.
- If you previously **reconfigured** a broken player in TMDb Helper settings, reset it to defaults before updating — the Helper reads `/reconfigured_players` first, which overrides `/players`.
- After updating players, restart Kodi or refresh TMDb Helper player list if needed.

## Credits

- Original pack: [a4k-openproject/json.openplayers](https://github.com/a4k-openproject/json.openplayers)
- G-Man's player updates: [slrwin/tmdbh.players](https://github.com/slrwin/tmdbh.players)
- Maintained by [Goldenfreddy0703](https://github.com/Goldenfreddy0703)

## License

See [LICENSE](LICENSE).
