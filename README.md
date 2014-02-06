# chrome-ext-downloader

Allows you to download the extension's source code without installing it.

## Installation

```
$ npm install -g chrome-ext-downloader
```

## Usage

```
Usage: ced <extension-id>
```

## Example

Say you want to download the source code of [Google Mail
Checker](https://chrome.google.com/webstore/detail/google-mail-checker/mihcahmgecmbnbcchbopgniflfhgnkff).
Grab the ID of the extension from the URL, in this case it's `mihcahmgecmbnbcchbopgniflfhgnkff`. Then simply run the following and you will have the source code in the current directory.

```
$ ced mihcahmgecmbnbcchbopgniflfhgnkff
```

## License

MIT
