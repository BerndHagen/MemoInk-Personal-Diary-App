# **MemoInk - Personal Diary App**

**MemoInk** is a comprehensive personal diary and collaborative documentation platform built with Xamarin Forms. The application enables users to create structured Topics and populate them with rich multimedia Entries. Leveraging real-time database technology, MemoInk ensures your content remains secure and synchronized across all your devices while offering sophisticated permission controls for both private journaling and shared documentation.

### **Key Features**

- **Topic Management:** Create and organize personal or collaborative documentation spaces
- **Rich Media Support:** Add text and images to document your experiences in detail
- **Real-time Sync:** Instant synchronization across all devices without manual intervention
- **Permission System:** Fine-grained access control for content sharing
- **User Collaboration:** Connect with others and create shared documentation spaces
- **Secure Storage:** All content is encrypted and stored securely in the cloud

### **Supported Content Types**

MemoInk supports various content formats to enhance your documentation:

- **Text Formats:** Plain text, Rich text, Markdown
- **Image Formats:** JPEG, PNG, GIF
- **Maximum File Sizes:**
  - Text entries: Unlimited
  - Images: Up to 10MB per image
  - Storage: Based on account tier

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
- **Storage:** 200 MB free space
- **Network:** Active internet connection
- **Screen:** 720x1280 resolution

### **Recommended Requirements**
- **Operating System:** Android 10.0 or higher
- **Processor:** Octa-core 2.0 GHz
- **RAM:** 4 GB
- **Storage:** 500 MB free space
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

## **Functionality Overview**

Let us walk you through the main features we've implemented:

### Home Screen

- **Global Topics**  
  The home screen displays all available topics sorted chronologically, with the newest appearing first. Access to topics is permission-based - if you lack the necessary permissions, you'll receive a notification indicating that access is restricted.

### Adding Entries to a Topic

- To contribute to a topic, tap **Add Entry**. You can write content and upload images. Each entry automatically captures the current date and time.
- Users can appreciate entries by tapping on them, which turns the text green and increments the like counter.

### Profile and Settings

- **Profile Screen**  
  View your personal information, including your username, country, and contact details such as email and website. You can also visit other users' profiles to learn more about them and their published topics.

- **Settings Screen**  
  Access and modify your account details and contact preferences. 
  **Important:** Deleting your account will permanently remove all topics you've created, including all entries within those topics - even entries made by other users.

### Topic Management

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

## **Create a Topic**

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

| MemoInk - Login              | MemoInk - Home               | MemoInk - Topics             |
|------------------------------|------------------------------|------------------------------|
| <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_login.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_topics.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_add.png" width="300px"> |

| MemoInk - Entries            | MemoInk - Profile            | MemoInk - Settings           |
|------------------------------|------------------------------|------------------------------|
| <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_entry.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_profile.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_settings.png" width="300px"> |
