# **MemoInk - Personal Diary App**

**MemoInk** is a digital companion for both personal journaling and team documentation, developed using Xamarin Forms and C# in Visual Studio 2022. Whether you want to keep a private diary or work together with others, MemoInk makes it simple and enjoyable. The app lets you organize your thoughts into Topics, which you can fill with all kinds of content - text, images and more. Everything syncs automatically across your devices, so your memories and notes are always at your fingertips. What makes MemoInk special is its flexibility. Keep your personal entries private or share selected content with others. Originally, MemoInk was a university project and we've fine-tuned the app based on user feedback to make it more reliable and feature-rich.

### **Key Features**

- **Topic Management:** Create and organize personal or collaborative documentation spaces
- **Rich Media Support:** Add text and images to document your experiences in detail
- **Real-time Sync:** Instant synchronization across all devices without manual intervention
- **Permission System:** Fine-grained access control for content sharing
- **User Collaboration:** Connect with others and create shared documentation spaces
- **Secure Storage:** All content is encrypted and stored securely in the cloud

## **Table of Contents**

1. [Key Features](#key-features)
2. [System Requirements](#system-requirements)
3. [Installation Guide](#installation-guide)
4. [Complete Functionality Guide](#complete-functionality-guide)
   - [Home Screen](#home-screen)
   - [Creating a New Topic](#creating-a-new-topic)
   - [Adding Entries to a Topic](#adding-entries-to-a-topic)
   - [Profile and Settings](#profile-and-settings)
   - [Searching for Users](#searching-for-users)
   - [Permissions and Accessibility](#permissions-and-accessibility)
5. [How to Create a New Topic](#how-to-create-a-new-topic)
6. [Data Collection and Account Management](#data-collection-and-account-management)
7. [Copyright](#copyright)
8. [Screenshots](#screenshots)

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

## **Complete Functionality Guide**

### Home Screen
Browse all available Topics chronologically, with newest first. Access is permission-based - you'll be notified if you don't have the required permissions.

### Creating a New Topic
Add new Topics easily and control who can view and contribute to them. Each Topic automatically captures creation date and time.

### Adding Entries
- Tap **Add Entry** to contribute
- Write content and add images
- Each entry includes timestamp
- Like entries to show appreciation

### Profile and Settings
- View and edit your profile information
- Manage account settings and preferences
- Control notification settings
- **Note:** Account deletion removes all your content permanently

### Searching for Users
Find other users easily and explore their public Topics. Follow users to stay updated with their content.

### Permissions and Access
Fine-tune who can view and contribute to your Topics. Get notified when someone interacts with your content.

### Adding Entries to a Topic

- **Creating Topics:** New topics automatically capture the current date and time of creation
- **Editing Topics:** Users with appropriate permissions can modify topic names and user permissions at any time
- **Access Control:** Fine-grained permission system determines who can view and contribute to topics

### Searching for Users

- Utilize the search feature to find and view profiles of other users. This allows you to explore their published topics and potentially engage with their content, depending on the permissions granted.

### Permissions and Accessibility

- Permissions are essential in determining what content you can view and interact with. If you attempt to access a topic without the required permissions, the app will notify you that access is not permitted.

### Additional Notes

- The app is designed to facilitate user collaboration and maintain privacy. It provides a space for documenting and discussing personal and shared experiences within a community or private setting.

Familiarize yourself with the app's functionalities to enhance your experience. For further assistance or questions, refer to this guide or contact support.

## **How to Create a New Topic**

Creating a new topic is intuitive and flexible. Here's the process we've designed:

1. **Initiate Topic Creation**  
   Tap the plus symbol (+) in the bottom navigation bar to start the process.

2. **Enter Topic Details**  
   On the `New Topic` page, locate the `Topic Details` section at the top. Enter the title for your new topic in the provided text field. The current date and time will be automatically captured when the topic is created.

3. **Configure User Permissions**  
   - Scroll to the `User Permissions` section.
   - **Individual User Access:** Check the boxes next to the names of users you wish to grant access.
   - **All Users Access:** To allow all users to view or participate in the topic, tap the `Select All Users` button.

4. **Review Information**  
   Review the topic title and permissions to ensure everything is set correctly.

5. **Save or Cancel**  
   - **To Save:** Tap the `Save` button located at the bottom of the screen.
   - **To Discard:** Tap `Cancel` if you decide not to proceed.

> **Note:** You can edit the topic title and permissions at any time if changes are needed.

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

### Additional Information
For technical questions or issues related to MemoInk's implementation, please [open an issue](https://github.com/YourUsername/MemoInk-Personal-Diary-App/issues) on GitHub.

## **Data Collection and Account Management**

MemoInk stores the following data to enhance your experience:

- User profile and preferences
- Topic structures and permissions
- Entry content and media files
- Collaboration settings
- Usage statistics and activity logs

All data is encrypted and stored securely in our cloud infrastructure. Premium users receive expanded storage quotas and enhanced backup options.

## **Copyright**

While we're excited to share MemoInk with you, it's important to note the usage terms:

By downloading and using **MemoInk**, you agree to be bound by the license terms. This license grants you a limited, non-transferable right to use the app for personal, non-commercial purposes. Modifying the app, sharing it, or using it in a commercial context is strictly prohibited without prior written consent from the Author.

The Author reserves the right to terminate your license if these terms are violated. No warranties are provided with the app, and the Author is not liable for any damages arising from its use. You are solely responsible for ensuring your usage complies with all applicable laws.

For full details on licensing terms and further information, please refer to the [LICENSE](https://github.com/BerndHagen/MemoInk-Personal-Diary-App/blob/main/LICENSE) file.

## **Screenshots**

We've included some screenshots to give you a better feel for the app's interface and functionality. These captures showcase the key features we've discussed:

If you'd like to preview the appearance of MemoInk before downloading the apk, you can explore the screenshots provided below. Each screenshot showcases the various functions and features of the app. Keep in mind that future updates may introduce additional functionalities to enhance user experience.

| MemoInk - Home              | MemoInk - Search               | MemoInk - Topics             |
|------------------------------|------------------------------|------------------------------|
| <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_topics.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_search.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_add.png" width="300px"> |

| MemoInk - Entries            | MemoInk - Profile            | MemoInk - Settings           |
|------------------------------|------------------------------|------------------------------|
| <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_entry.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_profile.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_settings.png" width="300px"> |
