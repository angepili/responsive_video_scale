# ↔ Responsive Video Scale
## - 📺 get youtube video responsive  
## - 🔲 it's possibile apply also to a normal div

++ no jQuery dependecies ++
```javascript
// function
responsive_VideoScale(id,options)


// Settings for embed youtube video
        let defaultsVideo = { 
            width : 560,                // default width
            height : 315,               // default height
            minwidth : 960,             // define min width to scale
            maxwidth: 1300,             // define max width to scale
            mobileBreakpoint: 480,      // define default breakpoint
            mobileW: 480,               // default mobile width to calc ratio under breakpoint
            mobileH: 480                // default mobile height to calc ratio under breakpoint
        };
        responsive_VideoScale('youtube_example',defaultsVideo);
```