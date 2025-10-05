# BlueJ Dark Mode Theme

A dark mode theme for BlueJ IDE to reduce eye strain and provide a more comfortable coding environment.

## Installation Instructions

### ⚠️ Important: Backup First

Before installing this theme, you should create a backup of your original BlueJ stylesheets in case you want to revert to the default theme.

---

## Windows Installation

1. **Locate the BlueJ stylesheets folder:**
   ```
   C:\Program Files\BlueJ\lib\stylesheets
   ```

2. **Create a backup:**
   - Inside the `stylesheets` folder, create a new folder called `backup`
   - Copy all existing CSS files into the `backup` folder

3. **Install the theme:**
   - Download all CSS files from this repository
   - Replace the existing files in the `stylesheets` folder with the downloaded files

4. **Restart BlueJ** to see the changes

---

## macOS Installation

1. **Locate the BlueJ stylesheets folder:**
   
   **Method 1 (Right-click):**
   - Find the BlueJ application in your Applications folder
   - Right-click (or Control-click) on `BlueJ.app`
   - Select "Show Package Contents"
   - Navigate to `Contents/Java/stylesheets`
   
   **Method 2 (Finder Go menu):**
   - Open Finder
   - Click "Go" in the top menu bar
   - Select "Go to Folder..." (or press Shift + Command + G)
   - Paste this path:
     ```
     /Applications/BlueJ.app/Contents/Java/stylesheets
     ```
   - Press Enter

2. **Create a backup:**
   - Inside the `stylesheets` folder, create a new folder called `backup`
   - Copy all existing CSS files into the `backup` folder

3. **Install the theme:**
   - Download all CSS files from this repository
   - Replace the existing files in the `stylesheets` folder with the downloaded files

4. **Restart BlueJ** to see the changes

---

## Linux Installation

1. **Locate the BlueJ stylesheets folder:**
   
   The location may vary depending on your installation method:
   
   **Standard installation:**
   ```
   /usr/share/bluej/lib/stylesheets
   ```
   
   **Or:**
   ```
   /opt/BlueJ/lib/stylesheets
   ```
   
   **If installed in home directory:**
   ```
   ~/bluej/lib/stylesheets
   ```

2. **Create a backup:**
   ```bash
   cd /path/to/bluej/stylesheets
   mkdir backup
   cp *.css backup/
   ```

3. **Install the theme:**
   - Download all CSS files from this repository
   - Replace the existing files in the `stylesheets` folder with the downloaded files
   - You may need sudo privileges:
     ```bash
     sudo cp /path/to/downloaded/*.css /path/to/bluej/stylesheets/
     ```

4. **Restart BlueJ** to see the changes

---

## Reverting to Default Theme

If you want to restore the original BlueJ theme:

1. Navigate to the BlueJ `stylesheets` folder (see platform-specific instructions above)
2. Delete the current CSS files
3. Copy the files from your `backup` folder back to the `stylesheets` folder
4. Restart BlueJ

---

## Troubleshooting

**Theme not applying:**
- Make sure you've restarted BlueJ after replacing the files
- Verify that all CSS files were replaced, not just some of them
- Check that the files are in the correct directory

**BlueJ won't start:**
- Restore the original files from your backup folder
- Ensure file permissions are correct (especially on Linux/macOS)

---
## Credits

Inspired by [bluej-dark-themes](https://github.com/realspal/bluej-dark-themes)

## Contributing

Found a bug or want to improve the theme? Feel free to open an issue or submit a pull request!

## License

MIT License
Copyright (c) 2025 [@0xkr4t0s](https://github.com/0xkr4t0s)
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
