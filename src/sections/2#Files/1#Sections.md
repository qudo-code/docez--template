## /sections
The sections directory is where `.md` files are stored. Doc EZ will recursively loop over the file tree and generate an `index.html` that mirrors the directory structure.

### Markdown Files
All markdown files in `/sections` will be used to generate both the nav as well as the main content.

**index.md**: Each directory level can have an `index.md` file in it's root which becomes the intro to the sections.

**Naming Convention**: When adding a section link to the nav, Doc EZ will use the name of the corresponding `.md` file. If you don't want to use spaces in your filenames, you can use a "-" Doc Ez will replace it with a space.

### Ordering Files/Folders
By default all files and folders will be sorted alphabetically. If you want to force the order of certain sections, you can prefix the file/folder name with `{order}#`. 

_See example usage in diagram above_

