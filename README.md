# TransitionMe
Built for a private project. Set css transition options via class tags.

## Quick How To Use
  
The following html shows 3 classes from TransitionMe applied to the span element.  
```html
<span class="transitionme-opacity transitionme-ease-in-out transitionme-duration-0_5">Hello World!</span>
```
These classes are the same as the following style property.  
```css
span {
    transition: 0.5s ease-in-out opacity;
}
```
  
**That's a transition which is 0.5s long, has the timing function ease-in-out and works on the opacity property.**
