# MemoInk - Personal Diary App

MemoInk is a mobile application designed for Android devices, meticulously crafted using Visual Studio 2022 and leveraging the power of Xamarin Forms. Developed as part of a university project, the app is programmed in C# and seamlessly integrates with a Realtime Database from Firebase. This dynamic connection facilitates smooth communication between the app and the database, enabling users to effortlessly receive and update information in real-time.

Functioning as a versatile Diary App, MemoInk empowers users to curate their life experiences through the creation of personalized Topics. Within each Topic, users can compose unlimited Entries, enriching their memories with images or text. What sets MemoInk apart is its collaborative feature, allowing users to designate permissions for others to access, edit and contribute new Entries to a shared Topic. This collaborative approach transforms the app into a virtual canvas for friends and family to collectively build and cherish meaningful memories.

MemoInk's thoughtful design extends to privacy preferences, offering users the flexibility to choose between private or public profiles. This choice enables individuals to decide whether to share their cherished memories with a group or with the entire world, fostering a personalized and secure space for capturing and sharing life's beautiful moments.

# Installation Guide

To install the app on your Android device, follow these steps:

1. **Download the APK**
   - Navigate to the [Releases](https://github.com/BerndHagen/MemoInk-Personal-Diary-App/releases) page of this repository.
   - Download the latest `.apk` file to your device.

2. **Allow Installation from Unknown Sources**
   - On your Android device, go to **Settings** > **Security**.
   - Enable the option to allow installations from unknown sources.

3. **Install the APK**
   - Open the downloaded `.apk` file on your device.
   - Tap **Install** to begin the installation process.

4. **Open and Enjoy**
   - Once installed, open the app from your device's app drawer.
   - Register for a new account to start using MemoInk and keep your memories securely stored.

> **Note:** Ensure you have a minimum of 200MB of free space and a stable internet connection for uninterrupted service use.

# Complete Functionality Guide

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

# How to Create a New Topic

Creating a new topic in the app is a simple process. Just follow the steps below:

1. Tap on the **plus symbol (+)** located in the bottom navigation bar to start creating a new topic.

2. Once the 'New Topic' page opens, you will see the 'Topic Details' section at the top. Here, enter the title of your new topic in the provided text field.

3. Select the date for your topic by tapping on the date field. A calendar may pop up where you can choose the desired date.

4. Scroll down to the 'User Permissions' section to set who can view or participate in this topic. You can select individual users by checking the box next to their name. If you want to allow all users to access the topic, tap the **SELECT ALL USERS** button.

5. After setting up your permissions, review all information you've entered.

6. To finalize the creation of your topic, tap the **SAVE** button located at the bottom of the screen. If you wish to discard the topic, tap **CANCEL**.

Remember, you can always edit the topic details and permissions later if you need to make changes.


# Copyright

This software program, **MemoInk**, is an intellectual creation of me, Bernd Hagen, the author and copyright holder, and is protected by copyright law. This comprehensive copyright notice outlines the terms and conditions governing the use, distribution, and modification of MemoInk:

1. **License**: MemoInk is made available for free download and use without requiring a separate license. You are granted a limited, non-exclusive, and non-transferable right to use the software in accordance with the terms set forth herein.

2. **Prohibited Modifications**: You are expressly prohibited from modifying, decompiling, disassembling, reverse engineering, or otherwise manipulating MemoInk in any manner. Any attempts to do so will be deemed a clear violation of this copyright.

3. **Warranty Disclaimer**: MemoInk is provided *"as is,"* without any warranty of any kind, whether express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and noninfringement. The author and copyright holder make no guarantees regarding the accuracy, reliability, or performance of the software.

4. **Limitation of Liability**: In no event shall the author or copyright holder be held liable for any claims, damages, or other liabilities, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use thereof. You expressly understand and agree that you assume all risks associated with the use of MemoInk.

By downloading, installing, or using MemoInk, you acknowledge that you have read and understood this copyright notice and agree to abide by its terms and conditions. Failure to comply with these terms may result in legal action and the revocation of your rights to use MemoInk.

# Screenshots

If you'd like to preview the appearance of MemoInk before downloading the apk folder, you can explore the screenshots provided below. Each screenshot showcases the various functions and features of the app. Keep in mind that future updates may introduce additional functionalities to enhance user experience.

| Login Screen                 | Home Screen                  | Topic Screen                 |
|------------------------------|------------------------------|------------------------------|
| <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_login.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_topics.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_add.png" width="300px"> |

| Entry Screen                 | Profile Screen               | Settings Screen              |
|------------------------------|------------------------------|------------------------------|
| <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_entry.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_profile.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/screenshots/v1.0.0-memoink_settings.png" width="300px"> |
