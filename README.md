# Nicer High Contrast

High constrast themes are my favourite because of it's unique color scheme/token colors. Once I got used to it I can't live without it, that's why I came up with an opinionated implementation of a high contrast theme for those who don't need that much high constrast and would rather a better looking code editor.

# Screenshots

![Image 1](/images/image1.png)
![Image 2](/images/image2.png)

The font in the screenshot is Operator Mono. You can get/buy it here: http://www.typography.com/blog/introducing-operator

I use an [extension](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) to customize the font and the tabs height with this custom CSS:

```css
/**** EDITOR FONT ****/
.monaco-shell,
.mac,
.view-lines {
  font-family: "OperatorMonoLig-Book"!important;
}

/**** TAB BAR HEIGHT ****/
.monaco-workbench .part.editor > .content .editor-group-container > .title .tabs-container {
  height: 25px;
}
.monaco-workbench .part.editor > .content .editor-group-container >.title .tabs-container >.tab {
  height: 25px!important;
}
.monaco-workbench .part.editor > .content .editor-group-container > .title .tabs-container > .tab .tab-label {
  line-height: 25px!important;
}
.monaco-workbench .part.editor>.content .editor-group-container>.title .monaco-icon-label:before {
  height: 25px!important;
}
.monaco-workbench .part.editor > .content .editor-group-container > .title .editor-actions {
  height: 25px!important;
}
.monaco-workbench .part.editor > .content .editor-group-container > .title .editor-actions .action-label:not(span) {
  height: 25px!important;
}
```
