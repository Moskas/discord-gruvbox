# (Better)Discord Gruvbox color scheme

Currently WIP theme for Discord based on Discord-Nordic 

![example screenshot](./gruvbox.png)<br/>

# To-Do
Just a rough notes of things to implement
```css
@import url("https://fonts.googleapis.com/css2?family=JetBrains+Mono&display=swap");

* {
    font-family: "JetBrains Mono", monospace !important;
    font-weight: 100;
}

::selection {
    background-color: var(--gruvbox-light3);
}

[class*="blobContainer"] {
    border: 2px solid var(--gruvbox-dark4);
    border-radius: 40px;
    margin: -2px;
}

[class*="slateTextArea"] {
    color: var(--gruvbox-light3);
}

[class*="sprite-"] {
    filter: grayscale(0%) !important;
}

[class*="title"] [class*="icon-"] {
    color: var(--gruvbox-blue);
}

[class*="mainContent"] [class*="icon-"] {
    color: var(--gruvbox-blue);
}

[class*="cooldownWrapper-"]{
    color: var(--gruvbox-light3) !important;
}
```
