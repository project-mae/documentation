# Git Requirements

Formatting your work properly is important in order to most effectively collaborate
with others on Project MAE. Make sure to follow these guidelines in order to have
your contributions accepted without a hitch.

## Organization

Git branches are not meant to be used for organization. Instead, create directories
(folders) and subdirectories to create a hierarchical format, storing your files in
an organized and easy to access fashion.

## File Formats

In order to allow as many people as possible to work on this project, we are very
careful about what file formats are allowed in Project MAE. The following are
allowed:

- Plain text
- Markdown
- Swift Source Code
- Shell Scripts
- All other Text-based formats
- SolidEdge CAD files (.asm, .par, etc)
- PNG and JPEG images

If a file format you would like to use is not listed here, please contact the
Repository & Release Team.

Do not commit any files of the following formats for any reason:

- ZIP files or other archive formats (gz, tar, tar.gz, 7z, etc.)
- Machine Code Executables (.exes, ELF binaries, etc.)

## Commit Messages

Please make your commit messages brief but provide enough detail for someone not
working on the branch to understand what your change was without viewing the contents
of your change. For further information, refer to this [online
article](https://alistapart.com/article/the-art-of-the-commit/).

## Pull Requests

Most files and changes work well with Git, but some do not. **Always** open a pull
request when changing any files of the following file format:

- SolidEdge CAD files (.asm, .par, etc)
- Images (jpeg/png files)
- PDF files
- Any other binary-based files  (anything that is not a text file, including most
  proprietary file formats

Edits to source files, scripts, and any other text files *should* be made using a
**separate branch and pull request** if:

- They make changes which are not minor
- They add features or otherwise add complexity
- They fix bugs, or make modifications to existing build systems.

The only reason a change should not be made via a pull request is if the change is to
fix a minor problem such as a typo or other minor changes that does not change the
meaning of content.

## Legal Note

Before you make a contribution, please read and understand the [legal information
document](./LEGAL.md).
