![](./assets/header.png)
# VerticalFox
[中文文档](readme_ch.md)

Get an Edge like auto-hide vertical tabs bar on Firefox! Powerd by Sidebery, you can have your bookmarks, pinned tabs all in side bar and get a clean, compact look. Support MacOS and Windows. 

![](./assets/gif1.gif)

*The auto hide also works on Tree Style Tabs, but you may need to adjust the css to achieve the best look.*
## How to apply
1. You need to have [Sidebery](https://addons.mozilla.org/en-US/firefox/addon/sidebery/) installed.
2. Download the zip files in release according to your operation system. You can also directly use the source files you need.

3. If you haven't customized your Firefox before, check out [this guide](https://www.reddit.com/r/firefox/wiki/userchrome/) for how to set up your Firefox and the profiles. TL;DR version:
    1. Navigate to `about:config` in the address bar and accept the risks.
    2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and toggle it to true (by double clicking on it).
    3. Navigate to `about:support` in the address bar, under **Application Basics**, find **Profile Folder** and open it. You should now see your profile folder.
    4. Inside your profile folder, create a new folder named `chrome` (all lower case).
   
4. Once you have your `chrome` folder under your profile directory, copy the `userChrome.css` you downloaded into `chrome`. Alternatively you can create a blank `userChrome.css` and paste the code. Restart your browser.


5. Go to the settings of Sidebery, go to **Styles editor**, paste all the code from `switch_light&dark.css`if you wanna use automatically switch between dark theme and light theme, or `dark_sidebery_styles.css` if you wanna use dark theme, or `light_sidebery_styles.css` if you wanna use light theme.


![](/assets/img1.png)

Now you can enjoy your new Firefox!

