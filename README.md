* * *

📦 Manually Installing uBlock Origin
====================================

This guide explains how to manually install the **stable release of uBlock Origin** in both **Google Chrome** and the **Kiwi Browser**.  
Since newer versions of Chrome no longer allow Manifest V2 extensions by default, these steps provide a workaround.

* * *

🔧 Requirements
---------------

* **Google Chrome** (desktop) or **Kiwi Browser** (Android)
    
* Access to **Chrome Flags** (for Chrome users)
    
* A stable release of [uBlock Origin](https://github.com/gorhill/uBlock/releases) (downloadable as a ZIP)
    
* Or: use the included **`ublock` folder in this repository** (based on uBlock Origin **v1.65.0**, verified working with Chrome 139)
    

* * *

📋 Installation in Google Chrome
--------------------------------

### 1. Enable Chrome Flag (required for Manifest V2)

1. Open Chrome.
    
2. In the address bar, enter:
    
    ```
    chrome://flags/#allow-legacy-mv2-extensions
    ```
    
3. Set **"Allow legacy extension manifest versions"** to **Enabled**.
    
4. Restart Chrome.
    

> 💡 This step is required for running older (Manifest V2) extensions such as this uBlock build.

* * *

### 2. Get uBlock

You have two options:

**Option A: Use the provided folder in this repository**

* Simply use the `ublock` directory included here (uBlock Origin v1.65.0).
    

**Option B: Download manually**

1. Download a stable release of [uBlock Origin](https://github.com/gorhill/uBlock/releases).
    
2. Unzip the archive.
    
3. Rename the extracted folder to:
    
    ```
    ublock
    ```
    

* * *

### 3. Enable Developer Mode in Chrome

1. Open Chrome and go to:
    
    ```
    chrome://extensions
    ```
    
2. Toggle **Developer mode** on (switch in the top-right corner).
    

* * *

### 4. Load the Unpacked Extension

1. Click **"Load unpacked"**.
    
2. Select the `ublock` folder (either from this repo or the one you downloaded).
    

* * *

✅ Chrome Done!
--------------

uBlock Origin is now installed in Chrome as an unpacked developer extension. You can use it just like the normal extension.

* * *

📋 Installation in Kiwi Browser (Android)
-----------------------------------------

Kiwi Browser supports Chrome extensions on mobile. Here’s how to set it up with uBlock Origin:

### 1. Install Kiwi Browser

1. Go to the [Kiwi Browser GitHub releases](https://github.com/kiwibrowser/src.next/releases).
    
2. Download the latest stable APK (for **arm64 devices**).
    
3. Install the APK on your Android device.
    

* * *

### 2. Install uBlock Origin

1. Open Kiwi Browser.
    
2. Go to **Menu → Extensions**.
    
3. Tap **"Load from .zip/.crx"**.
    
4. Choose one of the following:
    
    * The **uBlock ZIP file** from this repository (based on v1.65.0), or
        
    * A ZIP file from the official [uBlock Origin releases](https://github.com/gorhill/uBlock/releases).
        

* * *

✅ Kiwi Browser Done!
--------------------

uBlock Origin is now installed in Kiwi Browser. You can manage it under **Extensions** just like in Chrome desktop.

* * *

📝 Notes
--------

* On **Chrome**, you may need to reload the extension after restarting the browser.
    
* On **Kiwi**, updates must be installed manually since it doesn’t auto-update extensions.
    
* Both methods are meant for **advanced users**, as Chrome and related browsers are phasing out Manifest V2 support.
    

* * *

🧹 Uninstall
------------

* **Chrome**: Go to `chrome://extensions` → click **Remove** on uBlock.
    
* **Kiwi**: Open **Extensions** → remove uBlock from the list.
    

* * *