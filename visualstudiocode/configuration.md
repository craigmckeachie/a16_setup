# Configure VS Code

1. On the bottom left of VS Code > click the `Gear Icon`
2. Choose `Command Palette..`
3. Type `open settings`
4. Choose `Open Settings.JSON`
5. Paste the settings below into the `USER SETTINGS` section on the **right side** of the screen.
   - The left side is not editable.

If you have existing `USER SETTINGS` you will want to **add** the following settings below your current settings. Otherwise, you can replace the contents of the file with the JSON below.

`settings.json`

```json
{
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.fontFamily": "Fira Code iScript, Menlo, Monaco, 'Courier New', monospace",
  "editor.multiCursorModifier": "alt",
  "editor.formatOnSave": true,
  "emmet.includeLanguages": {
    "typescript": "html"
  }
}
```

<!--
6.  Copy the file [prettier.config.js](https://gist.github.com/craigmckeachie/7d0525b5062520f43fba9403bbe65ac8) into your `AngularCourse[Introduction|Comprehesive]xxxx\code` directory (which will be created when you unzip the course files in the last step of the overall computer setup, so download the file now and come back to this step). -->

# Install a font for programming (optional)

If you are interested in trying a new font designed for programming.

1. Install the free [FiraCodeiScript](https://github.com/kencrocken/FiraCodeiScript) font on your system.

- [How to Install Fonts on Windows 10](https://www.groovypost.com/howto/install-fonts-windows-10/)
- [How to Install Fonts on Mac](https://www.dafont.com/faq.php#mac)

2. Close and reopen VS Code to see the new font.
