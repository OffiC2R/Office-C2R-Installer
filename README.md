<p style="align: center;">
  <a>
    <img src="https://softcloud.cl/wp-content/uploads/2022/03/Microsoft_Office_logos_2013-2019.svg.webp">
        </a>
</p>

# Office 2013-2024 C2R Install
> Current Version - Version 7.7.7.7 r17 + Lite Version

                 
This program designed for on-line installation and activation Microsoft Office 2013/2016 C2R. You also can
create custom installation of Office off-line for using later.

## How to use the program:

1. **Uninstalling Office 2016**:
   - Begin by uninstalling Office 2016 through the **Control Panel** using the "Add or Remove Programs" applet. This ensures a clean removal of the existing Office suite.

2. **Force Removal of Office 2016**:
   - For a thorough uninstallation, consider using the **"Force Remove Office"** tool. This utility helps remove any remnants of Office 2016 that might not have been completely uninstalled during the standard process.
   - After using this tool, restart your computer to ensure all changes take effect.

3. **Installing Office 2024**:
   - Install Office 2019 to 2024 by clicking the **"Install Office"** button. This will initiate the installation process for the desired Office version.

4. **Converting from Retail to Volume Licensing (VL)**:
   - In the **"Utilities"** tab, perform the conversion from **"Office RETAIL"** to **"VL"** (Volume Licensing). This step is crucial for activating Office using KMS (Key Management Service) or MAK (Multiple Activation Key) methods.
   - The VL edition allows for centralized activation and management across multiple devices.

5. **Activating Office**:
   - Once the conversion is complete, click the **"Activate Office"** button. This will activate your Office suite using the appropriate licensing method.
   - Alternatively, if you prefer using KMS activation, you can start **KMSAuto Net 2015** and click the **"Activate Office"** option within that tool.

##  How to use Bookmark Download Office:

1. **Selecting the Appropriate Version**:
   - When using **Bookmark Download Office**, start by selecting the desired version of Office, including the bit (x86 or x64) and language.
   - For a comprehensive installation, I recommend creating a full x86-x64 distribution. To do this, choose the "All" option.
   - Click the "Download" button and specify a folder where the distribution files will be saved.
   - You can continue from a previous session or start a new one.

2. **Creating Multilingual Distributions**:
   - If you want to create a multilingual distribution, follow these steps:
     - Load the first language completely.
     - Switch to the pre-selected executive language.
     - Click the "Download" button again and choose the same download folder.

3. **Creating an ISO Image**:
   - After downloading all the required files, it's recommended to create an ISO image of the Office suite.
   - Use the "Create ISO" option to generate the image.

4. **Resulting Offline Installer**:
   - In the selected folder, you'll find a ready-to-use offline installer for the chosen version of Microsoft Office.
   - Note that during a single session, avoid mixing different versions of MS Office 2016 and 2013. You can manipulate x86-x64 and languages, but not versions. Use separate folders to prevent issues with the distribution.

5. **Multiple Projects and Customizations**:
   - Now you have the flexibility to create multiple distribution projects, incorporating updates, additions, and corrections.
   - You can choose specific build versions. For Office 2013, the branch choice doesn't matter—it will always download the most current build. For Office 2016, you can select the source of download (branch). The "Check version" button helps verify the build number of the selected branch.


## Advanced startup options (keys):

Certainly! Let's organize those commands into separate code boxes:

1. **Installation with Configuration File**:
   ```bash
   /configure "d:\MyPath\Configuration.xml"
   ```

2. **Microsoft Office Configuration Options**:
   - For Microsoft Office ProPlus (64-bit, English, excluding Excel and OneNote, including Visio):
     ```bash
     /proplus x64 en-us excludeExcel excludeOneNote /apps visio
     ```
   - For Microsoft Office (64-bit, Russian, English, including Word, Excel, and Visio):
     ```bash
     /apps x64 ru-ru en-us word excel visio
     ```
   - For Microsoft Office ProPlus (32-bit, English, excluding OneNote, including Project, with conversion and activation):
     ```bash
     /proplus x86 en-us excludeOneNote /apps project /convert /activate
     ```
   
## Additional questions

Certainly! Let's update the information to refer to **Office 2024** instead of 2019:

1. **Activation of Office 2024**:
   - Not all editions of Office 2019 to 2024 can be activated using a KMS emulator. For a more reliable activation process, consider using the full version of **Office 2013-2024 C2R** (Click-to-Run). The lite version only activates KMS editions.
   - Before installing Office 2019 to 2024, it's essential to **uninstall Office 2016**. I recommend using the built-in uninstaller within **Office 2013-2024 C2R**. Click the "Uninstall Office" button, and in the opened window, select all Office products and also mark "Delete the licenses."

2. **Installation**:
   - You can install the **Volume editions** of 2019 to 2024 from the **Perpetual 20XX channel**. This edition comes with pre-installed **GVLK keys** and all the licenses necessary for activation via KMS or MAK methods. Note that the Office edition installed from this channel may be slightly outdated compared to the Standard channel.

3. **Activation Process**:
   - Before activation, **open each Office product individually**. Use the "Utilities" tab for this purpose. If any windows prompt you for keys during this process, simply close them without making changes.
   - During the first run, the products will write the licenses that will be used later for activation. Failing to do this step will prevent successful Office activation.

4. **Retail to Volume Conversion**:
   - If you install Office from a channel other than Volume, you'll need to **convert it from Retail to Volume**. To achieve this:
     - Install **GVLK keys** from **Office 2013-2024 C2R**. This step will also install the required licenses.

5. **Activation Tools**:
   - Note that **KMSAuto Net** does not convert Retail editions to Volume editions. Instead, consider using tools like **KMSAuto Lite**, **KMSAuto++**, or **AAct** for this purpose.
