# Addon: Sidebar Image
This addon allows you to add an image on the top of your sidebar

## Installation:
Simply copy the CSS from ADDON.css into the *bottom* of your stylesheet.

## Features:

####Change colors of thumbanils in posts from specific sites:
```css
a.thumbnail[href*="www.google.com"] {
    background-color: #FF9800;
}
```
This will change the color of all thumbnails for posts from Google.

####Change colors of thumbanils in posts with a specific linkflair:
```css
.linkflair-truth .thumbnail, .linkflair-truth .linkflairlabel {
    background-color: #673AB7;
}
```
This will change the color of all thumbnails for posts with the linkflair "truth."