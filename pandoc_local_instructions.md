
`pandoc -o output.docx -f markdown -t docx report_outline_local.md`

- pandoc: Pandoc is the program. That's easy.
- -o: This is the output file name, which in our example is "output.docx".
- -f: This means "from" or "format", as in, "convert from the format". The format we are converting from is Markdown, so "markdown" follows "-f".
- -t: This means "to", or "convert to the format". Since we are outputting a .docx file, "docx" follows "-t".

Instructions I used - http://plaintext-productivity.net/2-05-how-to-set-up-sublime-text-for-markdown-export-to-word.html

