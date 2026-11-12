# Beeper Liquid Glass

A Liquid Glass theme for [Beeper Desktop](https://www.beeper.com) v4 on macOS, with full light and dark mode support.

- **Sidebar:** native macOS frosted glass (Beeper's built-in vibrancy)
- **Chat:** a soft ambient color field, so the glass has something to catch
- **Glass:** header, received bubbles, date chips, composer, buttons and the selected chat
- **Liquid accent:** sent bubbles and the send button get a gradient with a light catch
- **Readable overlays:** search, the command bar and menus use thick frosted glass so nothing bleeds through
- **Accessible:** with Reduce Transparency on (in Beeper or macOS), glass falls back to solid fills

## Install

1. In Beeper, open **Settings → Appearance** and turn **Reduce transparency** off.
2. Scroll to **Custom CSS** and click **Open CSS file in editor**.
3. Replace the file's contents with [`custom.css`](custom.css) and save.
4. Click **Reload CSS**. The main window can take a few seconds to repaint.

To go back to the stock look, click **Reset CSS** in the same panel.

The file lives at `~/Library/Application Support/BeeperTexts/custom.css` if you'd rather copy it there directly.

## Compatibility

Built and tested against Beeper Desktop **4.3.284** on macOS. The theme uses Beeper's own CSS variables where possible, but some rules target internal class names, which a Beeper update can rename. If something stops applying after an update, please open an issue.

## Credits

Inspired by [Beeper Liquid Glass Theme](https://github.com/jonathanplesel/Beeper-Liquid-Glass-Theme) by jonathanplesel. This is an independent implementation and contains none of that project's code.

## License

[GPL-3.0-or-later](LICENSE)
