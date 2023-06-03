# Syntax Highlightning for Textarea (HTML)

Transform Textarea into code editor with syntax highlight and shortcut keys supported.

- Live Demo: [http://textarea-syntax.adriancs.com/](http://textarea-syntax.adriancs.com/)

The syntax highlightning is done by using `highlight.js`.

The shortcut keys is done by adding a javascript event listener of `input` on the textarea and using a bunch of javascript to enable the following shortcut keys:

- When [Enter] is hit, maintain indention as previous line
- Press [Tab] for indentation at current position
- Press [Shift]+[Tab] for decrease indentation at current position
- Press [Tab] / [Shift]+[Tab] for multiline indentation
- Press [Shift]+[Del]/[Backspace] to delete the entire line
- Press [Home] to move the cursor to the front of the first non-white space character

The following documentation (Article) explains the walkthrough of code behind of how the syntax highlightning and shortcut keys are made.

- [adriancs.com](https://adriancs.com/html-css-js/1015/syntax-highlightning-in-textarea-html/)
- [codeproject.com](https://www.codeproject.com/Articles/5361561/Syntax-Highlightning-for-Textarea-HTML)

Cheers and happy coding.
