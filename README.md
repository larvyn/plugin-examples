# Larvyn plugin examples

Example plugins for [Larvyn](https://larvyn.dev), the Laravel workbench for Linux, macOS and Windows, and a starter for writing your own. Plugins need Larvyn v0.1.0-beta.10 or newer.

| Folder | What it is |
|---|---|
| [`plugins/larvyn.mailpit`](plugins/larvyn.mailpit) | Runs Mailpit in the stack, shows its inbox in the sidebar, and points your app's mail settings at it. |
| [`plugins/larvyn.horizon`](plugins/larvyn.horizon) | ⌘K commands to restart, pause, continue and check Horizon. Just a `larvyn.json`. |
| [`plugins/larvyn.hello`](plugins/larvyn.hello) | The smallest plugin with a view. Copy it to start your own. |
| [`plugin-starter`](plugin-starter) | A plugin view built with Vite and TypeScript, with a typed client for everything a view can ask Larvyn. |

The manifest format, the permissions and the view API are documented in [`plugins/README.md`](plugins/README.md).

## Try one

```sh
git clone https://github.com/larvyn/plugin-examples.git
```

In Larvyn, open **Settings → Plugins → Install from folder** and pick a folder, such as `plugins/larvyn.horizon`. Larvyn shows what the plugin may do before installing it. Then press ⌘K and type *Horizon*.

Found a bug in Larvyn? Use **Report a bug** at the top of the app, or [open an issue](https://github.com/larvyn/releases/issues/new/choose).
