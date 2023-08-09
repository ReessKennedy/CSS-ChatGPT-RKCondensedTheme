[GH Link](https://github.com/ReessKennedy/ChatGPT_Condensed)
## What ⚡
Removes excessive padding from ChatGPT's primary UI so users can see more information at once. 

## Why 🤷‍♂️
Too much padding is a sin! 

I like to see as much information as I can at once without needing to scroll. The user experience could be greatly improved on many apps that have spent lots of money on design and user experience if these apps minimized necessary spacing and made outputs more information-rich. 

## How 📋
### Download Extension
I use
https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld

### CSS
Simple CSS mods: 
```css
nav .py-3 {
    padding-bottom: 0.1rem;
    padding-top: 0.1rem;
}
nav .px-3 {
    padding-left: 0.25rem;
    padding-right: 0.25rem;
}
nav .text-sm {
    font-size: .800rem;
    line-height: 1.15rem;
}
xnav ol li a.py-3 svg[stroke="currentColor"][fill="none"][stroke-width="2"][viewBox="0 0 24 24"][stroke-linecap="round"][stroke-linejoin="round"][height="1em"][width="1em"] {
	display: none;
}
li.relative > a > svg:not(:hover) {
    /* Your CSS styles for the SVG element here */
    /* For example, let's change the stroke color */
    stroke: red;
    display: none;
}

```
