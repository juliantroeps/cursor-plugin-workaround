# Cursor Plugin Workaround

Cursor currently only supports direct GitHub URL plugin imports on Team licenses.  
This workaround makes a hidden URL input appear by first adding a local plugin.

## How to

1. Copy this plugin into `~/.cursor/plugins/local/cursor-plugin-workaround`. Then reload Cursor (`Developer: Reload Window`). See [Cursor docs](https://cursor.com/docs/plugins#test-plugins-locally) for more details.

```bash
mkdir -p ~/.cursor/plugins/local && rm -rf ~/.cursor/plugins/local/cursor-plugin-workaround && cp -R . ~/.cursor/plugins/local/cursor-plugin-workaround
```

2. Open Cursor and open the plugin settings page. A new text input field appears (the GitHub URL field).

![Settings](./misc/before-after-settings.jpg)

You can now add your own hosted custom plugin to the list of plugins.