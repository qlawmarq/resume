# markdown-to-cv-resume-generator

Once write CV with markdown, generate PDF file automatically when updating Markdown.

- [md-to-pdf](https://www.npmjs.com/package/md-to-pdf)
- [GitHub actions](https://github.com/masaiborg/markdown-to-cv-resume-generator/blob/master/.github/workflows/node.yml)

## How to use this (Basic)

Please make sure Node.js is installed in your PC.

Create and edit a Markdown file (`.md`) as you like.

Then, excute following command:

```bash
npm i
npm run generate
```

Now, you can see some of PDF files are generated or updated.

## Update files by GitHub actions

GitHub actions will detect changes in master branch, and generate your PDF files automatically.

Check the following for more details:

[`.github/workflows/generate_pdf.yml`](./.github/workflows/generate_pdf.yml)

## Update PDF Styles

All Markdown files will be converted once to html and then to pdf.

Meaning, you can apply CSS styles to your PDFs.

Modifying [`md.css`](./md.css) to update PDF Styles.

Also, you can modify some options to update [`config.json`](./config.json).
