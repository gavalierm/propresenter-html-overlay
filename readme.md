# ProPresenter HTML Overlay

Just simple HTML overlay with vanilla javascript for OBS, vMix, ...


## Theme

OBS have build-in CSS editor for browser.

`.overlay` - fullscreen block

`.box` - block which contain text elements


### Example of default theme

```css
/** default theme **/
.overlay {
    font-size: 6vh;
    font-family: 'Futura', 'Calibri', sans-serif;
    text-transform: uppercase;
    color: white;
    background: rgba(0, 0, 0, 0.8);
}

.box {
    transition: opacity 0.01s linear;
}
```