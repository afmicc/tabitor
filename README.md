<div align="center">
  <a href="https://afmicc.github.io/tabitor/">
    <img src="http://www.iconarchive.com/download/i80229/custom-icon-design/flatastic-1/edit.ico" alt="Logo" width="80" height="80">
  </a>

  <h2 align="center">tabitor</h2>

  <p align="center">
    A light editor in a browser tab!
    <br />
    <br />
     ·
    <a href="https://afmicc.github.io/tabitor/" target="_blank">Open app</a>
     ·
  </p>
</div>

## Usage

___tabitor___ saves the progress of the work while you are typing, so you can access to your previous work next time you open it or accidentaly closures.

### Save command

The save command works. Once the command is hint, it requests a name to resume it next time.

### Temp 

In case you forgot to save the progress, you can recover it. 
1. Open the browser console.
1. You should see the instructions printed. 
1. Run `temps()`
1. The sessions stored are listed. You can identify them according to the creation date.
1. Type `restore('<session-name>')`
1. The content is loaded

## Offline option

1. Paste the following code in a browser
```html
data:text/html, <html contenteditable><style> body { font-family: monospace } </style><title>notepad</title><link rel="icon" href="http://www.iconarchive.com/download/i80229/custom-icon-design/flatastic-1/edit.ico">
```
2. Save it as a bookmark

_NOTE_: the offline option does not save the progress


