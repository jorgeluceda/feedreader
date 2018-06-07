# feedreader

This program plls different data feeds from the web and compares the content 
against a specific search term.

The content that matches is then displayed in the terminal window.

The program reads text files, makes web calls, and decodes both XML and JSON
into struct type values, and does it all using Go's concurrency mechanisms.

## Program Architecture
![architecture](https://i.imgur.com/4Uqq29B.png)