# **MemoInk - Personal Diary App**

**MemoInk** is a digital companion for both personal journaling and team documentation, developed using Xamarin Forms and C# in Visual Studio 2022. Whether you want to keep a private diary or work together with others, MemoInk makes it simple and enjoyable. The app lets you organize your thoughts into Topics, which you can fill with all kinds of content - text, images and more. Everything syncs automatically across your devices, so your memories and notes are always at your fingertips. What makes MemoInk special is its flexibility. Keep your personal entries private or share selected content with others. Originally, MemoInk was a **university project** and we've fine-tuned the app based on user feedback to make it more reliable and feature-rich.

## **Table of Contents**

1. [System Requirements](#system-requirements)
2. [Installation Guide](#installation-guide)
3. [Complete Functionality Guide](#complete-functionality-guide)
   - [Home Screen](#home-screen)
   - [Creating a New Topic](#creating-a-new-topic)
   - [Adding Entries](#adding-entries)
   - [Profile and Settings](#profile-and-settings)
   - [Searching for Users](#searching-for-users)
   - [Permissions and Access](#permissions-and-access)
4. [Data Collection and Account Management](#data-collection-and-account-management)
5. [Usage Terms & License Agreement](#usage-terms--license-agreement)
6. [Screenshots](#screenshots)

## **System Requirements**

### **Minimum Requirements**
- **Operating System:** Android 7.0 (Nougat)
- **Processor:** Quad-core 1.4 GHz
- **RAM:** 2 GB
- **Storage:** 50 MB free space
- **Network:** Active internet connection
- **Screen:** 720x1280 resolution

### **Recommended Requirements**
- **Operating System:** Android 10.0 or higher
- **Processor:** Octa-core 2.0 GHz
- **RAM:** 4 GB
- **Storage:** 100 MB free space
- **Network:** High-speed internet connection
- **Screen:** 1080x1920 resolution or higher

## **Installation Guide**

Getting started with MemoInk is straightforward. Here's how to get it running on your device:

1. **Download the APK**
   - Open your web browser on your Android device.
   - Navigate to the [Releases](https://github.com/BerndHagen/MemoInk-Personal-Diary-App/releases) page of this repository.
   - Scroll down to the **Assets** section under the latest release.
   - Tap on the `.apk` file to start the download. You may be prompted to confirm the download, depending on your browser settings.

2. **Allow Installation from Unknown Sources**
   - Go to your device’s **Settings** by tapping the gear icon on your home screen or app drawer.
   - Scroll down and select **Security** or, on certain devices, **Biometrics and Security**.
   - Look for the option **Install unknown apps** or **Unknown sources**.
   - Tap on it, then select the browser or file manager you used to download the APK.
   - Toggle the switch to **Allow from this source**. This step may vary slightly depending on your Android version.

3. **Install the APK**
   - Open your file manager app and navigate to the **Downloads** folder where the APK was saved.
   - Tap on the downloaded `.apk` file.
   - A prompt will appear asking if you want to install the application. Review the permissions if necessary, then tap **Install**.
   - The installation process will begin and may take a few moments to complete.

4. **Open and Enjoy**
   - Once the installation is complete, tap **Open** from the installation screen or find the app icon in your app drawer.
   - Launch the app, and you’ll be prompted to either log in or create a new account.
   - Follow the on-screen instructions to register and start using MemoInk to create new Topics.

> **Note:** If the installation failed, check that you have enough free space on your device and the right permissions

## Complete Functionality Guide

### Home Screen
- Browse all available topics chronologically (newest first)
- Access is permission-based; notifications inform you if access is restricted
- All topics **created by you** display a **red cross** in the top-right corner
  - Clicking it deletes the entire topic and its entries  
  - - The topic creator **cannot remove themselves** and always has permission!

### Creating a New Topic
- Enter a **title** for the topic you want to create
  - If the title is already taken, the topic **won’t be created**
  - Choose a unique title instead
- Manage user permissions:  
  - Select users who should have access while restricting others
  - Permissions can be edited later inside the topic

### Adding Entries
- Tap **Add Entry** to contribute
- Provide a **title** and a **description** for the entry
- Select an image that will be displayed which others can expand by clicking on it
- Each entry includes a timestamp
- Like entries to show appreciation while each user can like an entry only once

### Profile and Settings
- View and edit your profile information
- Manage account settings and preferences
- Changes in fields under **Settings** update instantly in the database (real-time updates)
- **Note:** Deleting your account removes all topics you created, including all their entries
  This also deletes **entries made by other users** within those topics!

### Searching for Users
- A random selection of users is displayed by default
- Use the search field to find specific users
  Each change in the search field updates the list instantly

### Permissions and Access
- When creating a topic, specific users can be granted permissions
- If **no users** are selected, the topic is accessible to everyone
- Permissions can be modified later:  
  - Open the topic and scroll down
  - Click **Edit Topic Settings** to reveal additional options 
  - Check or uncheck users to adjust permissions

> **Note:** In the settings, you can choose to set your profile to Public or Private.  If your profile is Private, your created topics won’t be displayed when others search for you.

## Technical Stack & Libraries
MemoInk is built using several key technologies and libraries to provide a reliable and efficient journaling experience. The core technologies are **Xamarin Forms** and **Firebase**.

### Xamarin Forms
**Xamarin Forms** serves as the foundation of MemoInk, enabling cross-platform development with a single codebase. This framework allows the app to maintain a consistent user experience while leveraging native performance on Android devices.
- **Framework Version:** Xamarin.Forms 5.0
- **Platform Support:** Android 7.0 (Nougat) and higher
- **Additional Components:** Xamarin.Essentials for platform-specific functionality

### Firebase Integration
**Firebase** powers MemoInk's real-time features through two key components:
- **Firebase Realtime Database:** Manages synchronized data storage and real-time updates
- **Firebase Storage:** Handles secure storage of multimedia content and attachments
These Firebase services ensure reliable data synchronization and secure storage for all user content.

### Core Libraries
- **Newtonsoft.Json:** Handles JSON serialization and deserialization for data processing
- **NetStandard.Library:** Provides .NET Standard compatibility for core functionality

> **Note:** For technical questions or issues related to MemoInk's implementation, please [open an issue](https://github.com/BerndHagen/MemoInk-Personal-Diary-App/issues) on GitHub.

## **Data Collection and Account Management**

MemoInk collects and stores data to enhance user experience, ensure security and provide personalized features.  

### **Stored User Data**
- **Profile Information:** Full Name, Username, Email, Password (encrypted), Profile Picture, User Description, Birthday, Gender, Country, Website  
- **Account Settings:** Privacy Status (Public/Private), Authorized Usernames for Shared Topics
- **Communication Details:** Discord Handle  
- **Activity and Content:** Created Topics (titles, descriptions, permissions), Entries (text, images, timestamps), Collaboration Settings

### **Data Security and Storage**  
All collected data is encrypted and stored securely in our cloud infrastructure.   
Images, media files, and user-generated content are securely stored with access controls in place.  

> **Note:** Deleting an account permanently removes all associated topics and their entries, including contributions from other users.  

## **Usage Terms & License Agreement**  

We're thrilled to share **MemoInk** with you! Before using the app, please review the following terms:  

By downloading and using **MemoInk**, you agree to the **license terms**, which grant you a **limited, non-transferable** right to use the app for **personal, non-commercial purposes**. Any modification, distribution, or commercial use of the app **without prior written consent** from the Author is strictly prohibited.  

The Author reserves the right to **terminate your license** if these terms are violated. The app is provided **"as is"**, without warranties of any kind. The Author assumes **no liability** for any damages resulting from its use. You are solely responsible for ensuring that your usage complies with all **applicable laws**.  

For complete details, please refer to the **[LICENSE](https://github.com/BerndHagen/MemoInk-Personal-Diary-App/blob/main/LICENSE)** file.  

## **Screenshots**

To give you a better understanding of **MemoInk**'s interface and functionality, we've included some screenshots below. These images highlight the key features of the app. Feel free to explore the screenshots to get a preview of the app's design and functions before downloading the APK. Please note that future updates may introduce additional features to further enhance the user experience.  

| MemoInk - Home              | MemoInk - Search               | MemoInk - Topics             |
|------------------------------|------------------------------|------------------------------|
| <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_topics.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_search.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_add.png" width="300px"> |

| MemoInk - Entries            | MemoInk - Profile            | MemoInk - Settings           |
|------------------------------|------------------------------|------------------------------|
| <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_entry.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_profile.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_settings.png" width="300px"> |
