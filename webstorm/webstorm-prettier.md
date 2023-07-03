1. Install Prettier as a global npm package.
   ```
   npm install prettier --global
   ```
2. Find the path where your global npm packages are installed by running this command.

   ```
   npm get prefix --global
   ```

3. Copy the path where your global npm packages are installed.
   #### `Example`
   ```
   /Users/craigmckeachie/.nvm/versions/node/v14.17.4
   ```
4. Append `/lib/node_modules/prettier` to the path.

   #### `Example`

   ```
    /Users/craigmckeachie/.nvm/versions/node/v14.17.4/lib/node_modules/prettier
   ```

5. In WebStorm:
   1. Open Settings/Preferences: in Windows choose `File > Settings` OR Mac choose `WebStorm > Preferences`
   2. Go to `Languages and Frameworks | JavaScript | Prettier `
6. Fill the path to Prettier in as the value of `Prettier package` list (see screenshot below).
7. Check the `On code reformatting` and `On save` checkboxes to specify the actions that will trigger Prettier.

   ![Screenshot of Webstorm Configuration](https://user-images.githubusercontent.com/1474579/145878834-e11998b6-ac2a-4ecb-8c85-c0b31fc3cb49.png)

8. To verify it is working, open a `.ts` or `.js` file and delete a semicolon at the end of a line. Save the file and the semicolon should be added back.

### Reference

- [Webstorm Prettier Install](https://www.jetbrains.com/help/webstorm/prettier.html#ws_prettier_install)
- [How to Setup Prettier for Webstorm](https://dev.to/danywalls/how-to-setup-prettier-for-webstorm-3jph)
