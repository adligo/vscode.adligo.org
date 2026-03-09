# VSCode

### Forward

This is a spot for my VSCode settings/setup.  U.S. Code is pretty great; however, it has some quirks.

# Install VS Code

To install VS Code and verify the sha512 checksum follow [these instructions](https://github.com/adligo/pub-keys.adligo.org/blob/main/TOOLS_LIST.md).

# [Key Commands](KEYCOMMANDS.md)

- [KEYCOMMANDS.md](KEYCOMMANDS.md)

# Install Plugins

- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

- [macro-commander](https://marketplace.visualstudio.com/items?itemName=jeff-hykin.macro-commander)

<b>Note:</b> Macro-Commander is not signed, you might want to install it manually from source (after you review the source) or create your own extensions.

# VS Code Extensions

- [your-first-extension](https://code.visualstudio.com/api/get-started/your-first-extension)
- [extension-anatomy](https://code.visualstudio.com/api/get-started/extension-anatomy)

# Configure Formatting

These formatting settings will give you 2 space character tabs, and trailing curly braces in .cjs, .ts, .mts, .js, .mjs, .css, .html and most files.  However, it doesn't format .cs (C#) and many other language files.

Create a folder for your projects;

```bash
mkdir ~/projects
cd projects
```

Create the .editorconfig file, using notepad or vi or any text editor;

```
# EditorConfig is awesome: https://EditorConfig.org

root = true[*]
indent_style = spaces
indent_size = 2
end_of_line = crlf
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true
opening_brace = same_line
```

Create the .prettierrc file, using notepad or vi or any text editor;

```
{
  "bracketSameLine": true,
  "useTabs": false,
  "tabWidth": 2,
  "semi": true,
  "singleQuote": true,
  "printWidth": 120,
  "singleAttributePerLine": false
}
```
