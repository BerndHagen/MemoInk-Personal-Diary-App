# MemoInk - Personal Diary App

**MemoInk** is an Android mobile application, developed using **Visual Studio 2022** and **Xamarin Forms**. Created as part of a university project, it's built with **C#** and integrates with Firebase's **Realtime Database** for real-time data synchronization.

MemoInk functions as a Diary App, allowing users to create personalized **Topics** where they can add unlimited **Entries** enriched with text or images. Furthermore, MemoInk lets users grant permissions for others to access, edit, and contribute new Entries to a shared Topic. This turns the app into a collaborative space where friends and family can collectively build and cherish meaningful memories.

The app also offers privacy options, allowing users to choose between private or public profiles. This feature enables individuals to decide whether to share their memories with a selected group or with the entire world, providing a personalized and secure environment for capturing and sharing life’s beautiful moments.

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

To install the app on your Android device, follow these steps:

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

- **Global Topics**: The home screen displays the 20 latest Topics under the 'Global Topics' section. These are topics available to the entire user base. However, access to each topic is permission-based. If you don't have the necessary permissions to view a topic, attempting to open it will result in a message indicating you cannot access it.

- **Shared Topics**: Below the 'Global Topics', you'll find the 'Shared Topics' section. These topics are ones that other users have shared with you by granting specific permissions. This allows for collaborative discussions and content sharing within a controlled environment.

### Creating a New Topic

1. To create a new topic, tap on the **plus symbol (+)** on the bottom navigation bar.
2. Enter your topic details, including the title and date.
3. In the 'User Permissions' section, select which users you wish to grant access to by checking the box next to their name. Use the **SELECT ALL USERS** button to grant access to all users quickly.
4. Save the topic by tapping the **SAVE** button, or cancel the process by tapping **CANCEL**.

### Adding Entries to a Topic

- When viewing a topic, such as the 'Gaming Topic', you can add new entries by tapping on **ADD ENTRY +**. Here, you can write content, share images, and document experiences related to the topic.

### Profile and Settings

- The 'Profile' screen allows you to view your personal information, including your username, country, and contact options like email and website.
- Users can visit each other's profiles to learn more about them and view the topics they have published.
- The 'Settings' screen provides a summary of your personal information and offers access to modify your account details and contact preferences.

### Searching for Users

- The app includes a feature to search for other users. This functionality lets you view the profiles of fellow users, see their published topics, and potentially engage with their content, depending on permissions.

### Permissions and Accessibility

- Permissions play a crucial role in the app. They determine what content you can view and interact with. If you try to access a topic without the required permissions, the app will notify you that access is not allowed.

### Additional Notes

- The app is designed with user collaboration and privacy in mind, creating a space where personal and shared experiences can be documented and discussed within a community setting or in private.

Please ensure you're familiar with the app's functionality to get the most out of your experience. If you have any questions or require assistance, refer to this guide or contact support.

## Create a Topic

Follow these steps to create a new topic in the app:

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

By downloading and using **MemoInk**, you agree to be bound by the license terms. This license grants you a limited, non-transferable right to use the app for personal, non-commercial purposes. Modifying the app, sharing it, or using it in a commercial context is strictly prohibited without prior written consent from the Author.

The Author reserves the right to terminate your license if these terms are violated. No warranties are provided with the app, and the Author is not liable for any damages arising from its use. You are solely responsible for ensuring your usage complies with all applicable laws.

For full details on licensing terms and further information, please refer to the [LICENSE](https://github.com/BerndHagen/MemoInk-Personal-Diary-App/blob/main/LICENSE) file.

## **Screenshots**

If you'd like to preview the appearance of MemoInk before downloading the apk, you can explore the screenshots provided below. Each screenshot showcases the various functions and features of the app. Keep in mind that future updates may introduce additional functionalities to enhance user experience.

| MemoInk - Login              | MemoInk - Home               | MemoInk - Topics             |
|------------------------------|------------------------------|------------------------------|
| <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_login.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_topics.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_add.png" width="300px"> |

| MemoInk - Entries            | MemoInk - Profile            | MemoInk - Settings           |
|------------------------------|------------------------------|------------------------------|
| <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_entry.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_profile.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_settings.png" width="300px"> |
