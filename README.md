# homebrew-archivebox

The official brew.sh formula for [ArchiveBox](https://github.com/ArchiveBox/ArchiveBox), the self-hosted internet archiving solution.

## Quickstart

```bash
# 🧙‍♀️ ✨ the magic incantation
brew install archivebox/archivebox/archivebox

archivebox version
archivebox init
archivebox add 'https://example.com'
```


---

Tested on macOS, on Linux you should use the [`apt`/`deb` package](https://launchpad.net/~archivebox/+archive/ubuntu/archivebox/+packages) if possible.


## Development


Make sure you're in the main ArchiveBox repo folder first.
```bash
cd ArchiveBox/
git pull --recurse-submodules

# Install the package locally during testing
brew install --debug --verbose --interactive ./archivebox.rb

# Commit any changes to archivebox.rb and push to make them live
```
