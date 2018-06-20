# 📺 videoResponsive
-  get youtube video responsive  
- it's possibile apply also to a normal div that haven't defined sizes by css
- no jQuery dependecies ++

```html
<!-- YOUTUBE EMBED EXAMPLE WITH ID -->
<iframe id="youtube_example" width="560" height="315" src="https://www.youtube.com/embed/xat1GVnl8-k" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

```

```javascript
// Size settings in Pixels for embed youtube video
let defaults = { 
    width : 560,                // default width
    height : 315,               // default height
    minwidth : 960,             // define min width to scale
    maxwidth: 1300,             // define max width to scale
    mobileBreakpoint: 480,      // define default breakpoint
    mobileW: 480,               // default mobile width to calc ratio under breakpoint
    mobileH: 480                // default mobile height to calc ratio under breakpoint
};

// call the function with id and params
videoResponsive('youtube_example',defaults);
```
