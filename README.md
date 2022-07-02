# Quarto

Most critical parts of the OPML header: 

- code-tools: true
    this makes it possible to see the source code by pressing a button at the top right
  
- self-contained: true
    this was the main reason why I switched over from RMD to QMD. Without this there would be a lot of unnecessary files like Altair creates. Setting this to true simplifies it to just what you would expect when knitting and RMD, the file to create the report, and the report itself

- anchor-sections: false
    this option turns off the pesky chain icons next to headers
