# YoutubeNonStop
![YouTube NonStop Logo](https://github.com/lawfx/YoutubeNonStop/blob/master/images/yns128.png)

Autoclicker for Youtube's latest "feature" - Video paused. Continue watching?

Available for:

[Chrome](https://chrome.google.com/webstore/detail/youtube-nonstop/nlkaejimjacpillmajjnopmpbkbnocid) <a href="https://chrome.google.com/webstore/detail/youtube-nonstop/nlkaejimjacpillmajjnopmpbkbnocid">
<img src="https://github.com/lawfx/YoutubeNonStop/blob/master/images/chrome_logo.png" width="25" height="25" /></a>

[Firefox](https://addons.mozilla.org/en-US/firefox/addon/youtube-nonstop/) <a href="https://addons.mozilla.org/en-US/firefox/addon/youtube-nonstop/">
<img src="https://github.com/lawfx/YoutubeNonStop/blob/master/images/firefox_logo.png" width="25" height="25" /></a>

For Opera install this extension first https://addons.opera.com/en/extensions/details/install-chrome-extensions/ and then install YouTube NonStop from the Chrome store.

---

**Known issue**

When pausing the video outside of YouTube's page(e.g. with MediaKeys or from Picture-in-picture, etc) YouTube NonStop has no way of knowing if it was a user action or not, that's why it's unpausing the video.

Work-around steps for that are: 
1. Pause the video
2. YouTube NonStop resumes video
3. Immediately pause again(you have to be kinda fast)
4. Video remains paused

---

If you feel like supporting this project you can buy me a :coffee: or a :beer: :

[![](https://github.com/lawfx/YoutubeNonStop/blob/master/images/donate-paypal.png)](https://www.paypal.me/ioannounikos)

---

If you want to load the extension by yourself in your browser without installing it from store or Google suddenly decides to take action against it, follow the instructions below:

1. Clone or download this repository
    - If you download it, make sure to extract it first

*(from the official [Google instructions](https://developer.chrome.com/extensions/getstarted))*

2. Open the Extension Management page by navigating to chrome://extensions
    - The Extension Management page can also be opened by clicking on the Chrome menu, hovering over **More Tools** then selecting **Extensions**
3. Enable Developer Mode by clicking the toggle switch next to **Developer mode**
4. Click the **Load unpacked** button and select the extension directory
5. Ta-da! The extension has been successfully installed!
