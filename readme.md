## CSS Responsive 

###  HTML meta tags for viewport
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
### 2. Media Query Types




```css
@media (min-width: screen_size) {
    /* your css selector */
}
```
#### Orientation screen on devices
```css
@media (orientation: landscape) {
    /* your css selector */
}
```
```css
@media (orientation: portrait) {
    /* your css selector */
}
```
#### Min-width and Max-width

```css
@media (max-width: screen_size) {
    /* your css selector */
}
```
```css
@media (width <= screen_size){
    /* your css selector */
}
```
```css
@media (min-width:screen_size) and (max-width:screen_size) {
    /* your css selector */
}
```
```css
@media (min-size <= width <= max-size) {
    /* your css selector */
}
```
### Devices screen size sample
#### Mobile Screen
- 470px
- 720px
#### Tablet Screen
- 1024px
- 1280px
#### Computer Screen
- 1336px
- 1920px

### Other Responsive Features in CSS
- @media
- @import
- @container
- @support
