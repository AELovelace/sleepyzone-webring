Sleepy.Zone Webring:

For a quick and dirty solution, use the embed code below. Paste into your html where you would like it and size. Embed is unable to be styled by the user and uses a static stylesheet hosted on my servers. 
```<div id='sleepyembed' style="width:100%;height:100%;"><embed type="text/html" src="https://sadgirlsclub.wtf/sleepyring.html" style="width: 100%;height: 100%;"></div>```

If you wish to style it, place the css om the included css file into your stylesheet somewhere, then paste the html code into your document where you want it to appear

Sleepycontib banner and code:


If you want to implement a little banner-roll for sleepy artists, i put together a quick and dirty solution. 

1: Put sleepycred.js on your server

2: Put this in your html header. Replace the path with the path to your copy of sleepycred.js:
in header:
```
<script src="/engine/banners/sleepycred.js"></script>```
3: put this in the body where you want the banner to show on your webpage:
```<div id="sleepyroll" style="width: 40%; text align: center; margin-left:auto; margin-right:auto;">
        <h4 style ="background-color: black; border: 2px ridge; text-align:center; ">Random SleepyContrib</h4>
        <h4 id="sleepy" style ="background-color: black;text-align: center; border: 2px ridge;"></h4>
<p style="text-align:center;">Click Member Name to View their page</p>
    </div>```
