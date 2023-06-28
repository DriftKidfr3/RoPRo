# RoPro Patcher
This automatically patches the [RoPro](https://chrome.google.com/webstore/detail/ropro-enhance-your-roblox/adbacgifemdbhdkfppmeilbgppmhaobf?hl=en-GB) extension for you, allowing you to have `pro_tier` for free.

[Tutorial](https://www.youtube.com/watch?v=Do1X2COTq_8)

[v3rmillion thread](https://v3rmillion.net/showthread.php?tid=1197674)

## NOTE

Please visit the current open issues [here](https://github.com/Stefanuk12/RoProPatcher/issues) for any updates.

## Manual download

*this should get around Chrome/Brave's "corrupted" message*
- Download [Chrome extension source viewer](https://chrome.google.com/webstore/detail/chrome-extension-source-v/jifpbeccnghkjeaalbbjmodiffmgedin) in the Chrome Store
- Go to [RoPro](https://chrome.google.com/webstore/detail/ropro-enhance-your-roblox/adbacgifemdbhdkfppmeilbgppmhaobf?hl=en-GB)
- Open the extension we downloaded, and press "Download as zip"
- Extract the downloaded extension
- Use the custom patcher to patch the downloaded extension
- Enable developer mode on your browser
- For example, go to opera://extensions (or wherever you can view your extensions)
- Press "Load unpacked" (or similar) and select the patched extension folder
- Done!

You can view a fully manual YouTube tutorial [here](https://youtu.be/GHPSL0IMeww)

# Getting RoPro Verification Token

This will detail how to get your verification token which 99% of you will find no use for. This token is used for tracking playtime for a specific user. By using this token, you are able to track playtime for your main account while on your alt account.

- Go to your extensions in your browser, e.g. `chrome://extensions`
- You should see something like `Inspect views  background page` under RoPro
- Press on the underlined __background page__
- The developer console for the extensions should open, go to the console tab
- Execute this `await getStorage("userVerification")`
- The format will be `{USERID: 'TOKEN'}`
