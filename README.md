# Centered Display

Omarchy's display bar widget with its popup centered on the active display.
Brightness, text sizing, scaling, and monitor controls remain synchronized
with the built-in implementation.

## Install

```sh
omarchy plugin add https://github.com/Kylar514/omadisplay.center.git --enable
```

The plugin declares `omarchy.monitor` as its source, so enabling it replaces
the built-in display widget while preserving Omarchy's existing IPC routes.

## Remove

```sh
omarchy plugin remove omadisplay.center
```

Removing it restores the built-in display widget.

## Upstream

This plugin is derived from
[`shell/plugins/panels/monitor`](https://github.com/omacom/omarchy/tree/quattro/shell/plugins/panels/monitor)
on Omarchy's `quattro` branch. The `upstream` branch mirrors that directory;
automated pull requests merge upstream changes into the customized `master`
branch for review.

## License

MIT. See [LICENSE](LICENSE).
