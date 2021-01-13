# Netlify template for a spreadsheet2site website

## Setup

1. Make a copy of [this Google Sheet template](https://docs.google.com/spreadsheets/d/1iHXM2M6m2vksvQ8PpxZTg0ZsRyJL58f243do1I1c3IQ)
2. Set it to public access (Share button - allow access to everyone with the url)
3. <a href="https://app.netlify.com/start/deploy?repository=https://github.com/azarai/spreadsheet2site-netlify-template"><img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify"></a>
4. Insert the Spreadsheet id during setup


## CLI

The binaries are in the _bin_ folder and support OSX, Linux and Windows.

```bash
spreadsheet2site-osx build -sheet <sheetId> templates/ -output <output file or dir>
```

## Templates

See [readme](templates/README.md)