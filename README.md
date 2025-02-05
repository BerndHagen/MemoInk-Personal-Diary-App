# **MemoInk - Personal Diary App**

**MemoInk** is a modern personal diary application built with Xamarin Forms that transforms the way you document and share life's moments. Whether you're keeping a private journal or collaborating on shared memories, MemoInk provides an intuitive platform for creating Topics and filling them with unlimited Entries containing text and images. With real-time synchronization powered by Firebase's Realtime Database, your memories are always secure and accessible.

### **Key Features**

- **Collaborative Topics:** Create and manage Topics that can be shared with friends and family
- **Unlimited Entries:** Add text and images to document your experiences
- **Privacy Control:** Choose between private and public profiles
- **Real-time Sync:** Changes are instantly synchronized across all devices
- **User Management:** Search and connect with other users
- **Permission System:** Fine-grained control over who can view and contribute

### **Core Functionality**

MemoInk offers a comprehensive set of features designed to enhance your journaling experience:

- **Topic Management:** Create, edit, and organize your personal or shared Topics
- **Entry System:** Add detailed entries with support for text and images
- **User Collaboration:** Invite others to contribute to your Topics
- **Privacy Settings:** Control your profile's visibility and Topic access
- **Search Capabilities:** Find and connect with other users
- **Real-time Updates:** Instant synchronization of all changes

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
6. [Copyright](#copyright)
7. [Screenshots](#screenshots)

## **System Requirements**

We've tested MemoInk extensively to ensure smooth performance across different Android devices. Here's what you'll need:

### **Minimum Requirements**
- **Operating System:** Android 7.0 (Nougat) or higher
- **Processor:** Quad-core 1.4 GHz or equivalent
- **RAM:** 2 GB
- **Storage:** 200 MB of free space
- **Internet:** A stable internet connection is required for real-time updates

### **Recommended Requirements**
- **Operating System:** Android 10.0 (Q) or higher
- **Processor:** Octa-core 2.0 GHz or higher
- **RAM:** 4 GB or more
- **Storage:** 500 MB of free space
- **Internet:** High-speed internet for the best experience

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
  The home screen features the 20 most recent topics in the **'Global Topics'** section. These topics are accessible to the entire user base, though access is permission-based. If you lack the necessary permissions, you will receive a notification indicating that access is restricted.

- **Shared Topics**  
  Below **'Global Topics'**, you will find the **'Shared Topics'** section. These topics have been shared with you by other users, granting you specific permissions to view and collaborate on them within a controlled environment.

### Adding Entries to a Topic

- To contribute to a topic, such as **'Gaming Topic'**, tap **Add Entry**. You can then write content, upload images, and document experiences related to the topic.

### Profile and Settings

- **Profile Screen**  
  View your personal information, including your username, country, and contact details such as email and website. You can also visit other users' profiles to learn more about them and their published topics.

- **Settings Screen**  
  Access and modify your account details and contact preferences. This screen provides an overview of your personal information and account settings.

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
   On the `New Topic` page, locate the `Topic Details` section at the top. Enter the title for your new topic in the provided text field.

3. **Select a Date**  
   Tap on the **date field**. A calendar view will appear. Select the desired date for your topic.

4. **Configure User Permissions**  
   - Scroll to the `User Permissions` section.
   - **Individual User Access:** Check the boxes next to the names of users you wish to grant access.
   - **All Users Access:** To allow all users to view or participate in the topic, tap the `Select All Users` button.

5. **Review Information**  
   Review all the information you have entered to ensure it is accurate and complete.

6. **Save or Cancel**  
   - **To Save:** Tap the `Save` button located at the bottom of the screen.
   - **To Discard:** Tap `Cancel` if you decide not to proceed.

> **Note:** You can edit the topic details and permissions at any time if changes are needed.

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
