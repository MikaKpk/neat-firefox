# Neat Firefox Design Sheet
Brings back decent looking square tabs to Firefox 89 and higher

## Why?
Because all you sexy Firefox users deserve something sexier than the ugly new tab design thats not connected at the bottom.

## How to install?
Since Firefox 57+, the only way to customize your browser UI is through `userChrome.css`. Learn more [here](http://kb.mozillazine.org/index.php?title=UserChrome.css&printable=yes).

### General Instructions:
1. Go to your Firefox browser, make sure you are using Dark Theme or a custom theme. White Theme is not supported as of now.
1. Type `about:config` in your url bar.
1. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to `true`
1. Type `about:profiles` in your url bar.
1. Under the profile that is in use (The message is something like `This is the profile in use and it cannot be deleted.`), click `Open Folder` on the `Root Directory` row.
1. If that folder does not have a `chrome` folder, create a folder, name it `chrome`.
1. In the `chrome` folder, create a file named `userChrome.css`
1. Copy and paste the code into your `userChrome.css` file that you have created.
<br/>**WARNING:** Newer versions of Firefox with Mojave or Windows 10 Dark Mode will cause Firefox to use the `Dark` theme by default. In this case, you should use the [userChrome-dark.css](./userChrome-dark.css) theme.
1. Restart Firefox and enjoy!

### Nothing has changed for me
Make sure that your file extension for `userChrome.css` is correct. Most likely a problem for Windows, refer to [this issue](https://github.com/wilfredwee/photon-australis/issues/104). 

### Thanks to wilfredwee for making his [photon-australis](https://github.com/wilfredwee/photon-australis) theme that this is based on
I have no prior experience modifying the CSS for the Firefox UI directly so this was a great help, hence why I forked it and I'm now offering the dited version.
