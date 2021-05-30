# PitchDark-Fox

![PitchDarkFox](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/pitchdarkfox.gif)

![NewPrivateWindowPage](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/NewPrivateWindowPage.png)

![NewTabPage](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/NewTabPage.png)

## TESTED ON

1. Windows 10
2. Latest Nighlty Build of Firefox

![AboutFirefox](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/AboutFirefox.png)

### NOTE

1. This is NOT a 'release' of custom-css for Firefox. Its a collection of stylesheets I've put together for my own use. I've merrily tweaked/hidden elements, based on how I'd like them to be.
2. Much of it is based on others' hardwork. [**See Credits**](https://github.com/im-hm/PitchDark-Fox/blob/main/README.md#credits)
3. I only have a working knowledge of css. Consequently, I haven't followed CSS Best Practices. Ex, avoiding use of universal selector (\*)

## USAGE

1. Stylesheets and Folders in this repo need to be placed directly inside chrome folder in firefox profile.
2. Rules from TreeStyleTabs-TextArea.css (inside userContent -> Addons folder) need to be pasted in text area provided by TreeStyleTabs Addon in about:preferences.

### REQUIREMENTS

1. Fira Sans Font https://github.com/mozilla/Fira/releases/
2. Scripts - From [**u/MotherStylus's repository**](https://github.com/aminomancer/uc.css.js)

### SCRIPTS REQUIRED

1. [**Agent/Author Sheet Loader**](https://github.com/aminomancer/uc.css.js/blob/master/script/userChrome_as_css_module.uc.js) - for styling tooltips
2. [**Toolbox Button**](https://github.com/aminomancer/uc.css.js/blob/master/script/atoolboxButton.uc.js) - as 'Inspect Element', and Hamburger Menu are hidden
3. [**Search Selection Keyboard Shortcut**](https://github.com/aminomancer/uc.css.js/blob/master/script/searchSelectionShortcut.uc.js) - as 'Search _InsertSearchEngineName_ with' is hidden from context menu

### FOR DARK WEBPAGES

1. [**Dark Reader Addon**](https://addons.mozilla.org/en-US/firefox/addon/darkreader/) - Set Background Color to #000
2. [**Stylus Addon**](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) - Themes can be found on github, userstyles.org. [**Izheil's Repository**](https://github.com/Izheil/Dark-userstyles) has a good global dark theme for stylus.

## STYLING ADDONS

1. Themes for Addons are contained in 'userContent -> Addons' folder.
2. Internal UUID of Addons is required. It can be found at 'This Firefox' section of 'about:debugging'. It needs to be pasted in addon's stylesheet, in place of 'Paste Internal UUID here'.

### ADDONS STYLED

1. [**Auto Tab Discard**](https://addons.mozilla.org/en-US/firefox/addon/auto-tab-discard/)
2. [**Bitwarden Password Manager**](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/)
3. [**Block Site**](https://addons.mozilla.org/en-US/firefox/addon/block-website/)
4. [**Breadcrumbs**](https://addons.mozilla.org/en-US/firefox/addon/breadcrumbus/)
5. [**Bypass Paywalls**](https://addons.mozilla.org/en-US/firefox/addon/bypass-paywalls-firefox/)
6. [**Bypass Paywalls Clean**](https://addons.mozilla.org/en-US/firefox/addon/bypass-paywalls-clean/)
7. [**Clear URLs**](https://addons.mozilla.org/en-US/firefox/addon/clearurls/)
8. [**Cookie Auto Delete**](https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete/)
9. [**Dark Reader**](https://addons.mozilla.org/en-US/firefox/addon/darkreader/)
10. [**Enhancer for Youtube**](https://addons.mozilla.org/en-US/firefox/addon/enhancer-for-youtube/)
11. [**EPUB Reader**](https://addons.mozilla.org/en-US/firefox/addon/epubreader/)
12. [**Fast Tab Switcher**](https://addons.mozilla.org/en-US/firefox/addon/fast-tab-switcher/)
13. [**FeedBro**](https://addons.mozilla.org/en-US/firefox/addon/feedbroreader/)
14. [**Firefox Relay**](https://addons.mozilla.org/en-US/firefox/addon/private-relay/)
15. [**Google Container**](https://addons.mozilla.org/en-US/firefox/addon/google-container/)
16. [**Imagus**](https://addons.mozilla.org/en-US/firefox/addon/imagus/)
17. [**Local CDN**](https://addons.mozilla.org/en-US/firefox/addon/localcdn-fork-of-decentraleyes/)
18. [**Multi Account Container**](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/)
19. [**Notes By Firefox**](https://addons.mozilla.org/en-US/firefox/addon/notes-by-firefox/)
20. [**Save WebP as PNG**](https://addons.mozilla.org/en-US/firefox/addon/save-webp-as-png-or-jpeg/)
21. [**Search By Image**](https://addons.mozilla.org/en-US/firefox/addon/search_by_image/)
22. [**Tabs Aside**](https://addons.mozilla.org/en-GB/firefox/addon/tabs-aside/)
23. [**Set Tabs Aside (Edge Legacy)**](https://addons.mozilla.org/en-US/firefox/addon/ms-edge-tabs-aside/)
24. [**Sponsor Block**](https://addons.mozilla.org/en-US/firefox/addon/sponsorblock/)
25. [**Stylus**](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)
26. [**Temporary Container**](https://addons.mozilla.org/en-US/firefox/addon/temporary-containers/)
27. [**Translate Webpages**](https://addons.mozilla.org/en-US/firefox/addon/traduzir-paginas-web/)
28. [**Tree Style Tabs**](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/)
29. [**uBlacklist**](https://addons.mozilla.org/en-US/firefox/addon/ublacklist/)
30. [**uBlock Origin**](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
31. [**uMatrix**](https://github.com/gorhill/uMatrix/releases) - Latest Pre-Release Version
32. [**User Agent Switcher**](https://addons.mozilla.org/en-US/firefox/addon/uaswitcher/)
33. [**Web Archives**](https://addons.mozilla.org/en-US/firefox/addon/view-page-archive/)

![AutoTabDiscard](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_AutoTabDiscard.png)
![Bitwarden](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_Bitwarden.png)
![ClearURLs](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_ClearURLs.png)
![CookieAutoDelete](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_CookieAutoDelete.png)
![DarkReader](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_DarkReader.png)
![EnhancerForYoutube](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_EnhancerForYoutube.png)
![LocalCDN](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_LocalCDN.png)
![MultiAccountContainer](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_MultiAccountContainer.png)
![NotesByFirefox](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_NotesByMozilla.png)
![SaveWebPasPNG](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_SaveWebPasPNG.png)
![TranslateWebPages](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_TranslateWebPages.png)
![TreeStyleTab](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_TreeStyleTab.png)
![uBlockOrigin](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_uBlockOrigin.png)
![uMatrix](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_uMatrix.png)

## PREVIEWS

![AllTabsView](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/AllTabsView.png)
![ClearAllHistoryDialog](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/ClearAllHistoryDialog.png)
![CloseWindowDialog](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/CloseWindowDialog.png)
![ContextMenus](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/ContextMenus.png)
![CreateProfile](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/CreateProfile.png)
![CtrlTabView](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/Ctrl%2BTabView.png)
![DownloadsView](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/DownloadsView.png)
![EditBookmark](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/EditBookmark.png)
![HttpsOnlyError](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/HttpsOnlyError.png)
![Library](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/Library.png)
![NetErrorPage](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/NetErrorPage.png)
![PDFViewer](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/PDFViewer.png)
![PageInfo](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/PageInfo.png)
![PrintDialog](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/PrintDialog.png)
![SaveFileDialog](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/SaveFileDialog.png)
![TrackingProtectionPopup](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/TrackingProtectionPopup.png)

## CREDITS

1. [**MrOtherGuy's firefox-csshacks**](https://github.com/MrOtherGuy/firefox-csshacks) - One-Liner, about:addons column view, multi-row urlbar dropdown results
2. [**u/MotherStylus**](https://github.com/aminomancer/uc.css.js) helped with styling problematic elements, pointed out glaring errors, introduced me to VS Code/Prettier, and created some very useful scripts on my request. Needless to say, these stylesheets would have been nowhere near their current state without his help.
3. [**Izheil's Quantum Nox**](https://github.com/Izheil/Quantum-Nox-Firefox-Dark-Full-Theme/) - Their themes for uMatrix, uBlock Origin, and Containers helped me style these addons.
4. [**u/dilfool2nice's Stylesheets**](https://github.com/GrosBourrin/FIREFOX-BLUE-MOON/) helped style ctrl+tab preview, inspired use of GIFs.
5. [**PROxZIMA's Sweet_Pop**](https://github.com/PROxZIMA/Firefox-Theme/) - code snippet for gradient line below Navigator Toolbox.
