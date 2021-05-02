# CSS Snippets

## dotted-portal.css

Show a dotted border around portals

```css
.theme-dark .markdown-preview-view .markdown-embed {
  border: 1px dotted white !important;
  padding: 8px !important;
}

.theme-light .markdown-preview-view .markdown-embed {
  border: 1px dotted black !important;
  padding: 8px !important;
}
```

## monospace-editor.css

Use a monospace font in the editor

```css
.markdown-source-view * {
  font-family: monospace !important;
}
```

## big-font.css

Make font in edit and preview mode a little bigger (for themes like Cybertron and Discordian that use a tiny font size) because I have terrible eyesight :(

```css
.markdown-preview-view,.markdown-source-view,.cm-s-obsidian {
  --font-size-notes: 16px;
  font-size: var(--font-size-notes);
}
```

## discordian-light-fixes.css

Fixes for light mode of the [Discordian](https://github.com/radekkozak/discordian) theme.

```css
.theme-light {
  --text-a: #008fbd;
  --interactive-normal: #2e3338;
  --interactive-hover: #7b6cd9;
}

// Bring back the status bar
.status-bar {
  display: flex;
}  
```

