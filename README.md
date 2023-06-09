# Syntax Highlightning for Textarea (HTML)

Transform a textarea into a code editor with syntax highlighting and shortcut key support.

Live Demo: [http://textarea-syntax.adriancs.com/](http://textarea-syntax.adriancs.com/)

Syntax highlighting is accomplished using `highlight.js`.

The shortcut keys are implemented by adding a JavaScript event listener for `input` on the textarea, and using a collection of JavaScript code to enable the following shortcut keys:

- When [Enter] is hit, maintain indentation of the previous line
- Press [Tab] for indentation at the current position
- Press [Shift]+[Tab] to decrease indentation at the current position
- Press [Tab] / [Shift]+[Tab] for multiline indentation
- Press [Shift]+[Del]/[Backspace] to delete the entire line
- Press [Home] to move the cursor to the front of the first non-white space character

The following articles provide a walkthrough (step by step explanation) of the code behind the syntax highlighting and shortcut key features:

Documentation:

- [https://adriancs.com/html-css-js/1015/syntax-highlightning-in-textarea-html/](https://adriancs.com/html-css-js/1015/syntax-highlightning-in-textarea-html/)
- [https://www.codeproject.com/Articles/5361561/Syntax-Highlightning-for-Textarea-HTML](https://www.codeproject.com/Articles/5361561/Syntax-Highlightning-for-Textarea-HTML)

Cheers and happy coding.
