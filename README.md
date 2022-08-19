# markdown-to-cv-rejume-generator

Once write CV with markdown, Generate pdf of CV automatically.

- [md-to-pdf](https://www.npmjs.com/package/md-to-pdf)
- [GitHub actions](https://github.com/masaiborg/markdown-to-cv-rejume-generator/blob/master/.github/workflows/node.yml)

## How to use this (Basic)

First of all, please make sure Node.js is installed in your PC.

Then, excute following command:

```
npm i
npm run generate
```

Now, you can see some of PDF files are generated.

## Update PDF Styles 

All markdown files will be converted once to html and then to pdf.

Meaning, you can apply CSS styles to your PDFs.

Modifying [`md.css`](./md.css) to update PDF Styles.

Also, you can modify some options to update [`config.json`](./config.json).