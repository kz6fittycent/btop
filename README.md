# btop snap

[![btop](https://snapcraft.io/btop/badge.svg)](https://snapcraft.io/btop)

Snap packaging for [btop](https://github.com/aristocratos/btop), the resource monitor by aristocratos. This repo only holds the snap. The snap is built from upstream's source and published straight to `latest/stable`.

## Install

```bash
sudo snap install btop
```

Optional, to see removable drives:

```bash
sudo snap connect btop:removable-media
```

## Notes

- Config lives in `~/snap/btop/current/.config/btop`.
- Quit with `q`, `Ctrl+C` or just close the terminal. Theme and settings are saved either way (`snap/local/btop-session` handles the close).
- Want a desktop launcher? See [btop-desktop](https://github.com/kz6fittycent/btop-desktop).

## Issues

Snap problems go [here](https://github.com/kz6fittycent/btop/issues). btop bugs go [upstream](https://github.com/aristocratos/btop/issues).

## License

Apache-2.0, same as btop.
