<p align="center">
  <img src="https://github.com/BerndHagen/MemoInk-Personal-Diary-App/blob/main/img/v1.0.2-memoink_logo.png" alt="MemoInk Logo" width="128" />
</p>
<h1 align="center">MemoInk - Personal Diary App</h1>
<p align="center">
  <b>A digital companion for both personal journaling and team documentation.</b><br>
  <b>Organize your thoughts into Topics, sync across devices, and collaborate with others seamlessly.</b>
</p>
<p align="center">
  <a href="https://github.com/BerndHagen/MemoInk-Personal-Diary-App/releases"><img src="https://img.shields.io/github/v/release/BerndHagen/MemoInk-Personal-Diary-App?include_prereleases&style=flat-square&color=CD853F" alt="Latest Release"></a>&nbsp;&nbsp;<a href="https://github.com/BerndHagen/MemoInk-Personal-Diary-App/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-Others-red?style=flat-square" alt="License"></a>&nbsp;&nbsp;<a href="https://dotnet.microsoft.com/download/dotnet-framework"><img src="https://img.shields.io/badge/Xamarin.Forms-5.0-512BD4?style=flat-square" alt="Xamarin Version"></a>&nbsp;&nbsp;<img src="https://img.shields.io/badge/Platform-Android-0078D6?style=flat-square" alt="Platform">&nbsp;&nbsp;<img src="https://img.shields.io/badge/Min_Android-7.0-lightgrey?style=flat-square" alt="Min Android Version">&nbsp;&nbsp;<img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square" alt="Status">&nbsp;&nbsp;<a href="https://github.com/BerndHagen/MemoInk-Personal-Diary-App/issues"><img src="https://img.shields.io/badge/Issues-0_open-orange?style=flat-square" alt="Open Issues"></a>
</p>

**MemoInk** is a straightforward journaling app created as a university project using Xamarin Forms and C#. The app helps users organize their thoughts into Topics, which can be kept private or shared with specific people.

The app allows users to write entries with text and images, with everything syncing through Firebase for access across different devices. Users can create Topics (digital notebooks), invite specific users to collaborate, or keep everything private.

Originally developed as a university project, the app has been improved based on user feedback to enhance stability and usability. It's not a commercial application—just a simple tool for personal journaling and light collaboration.

## Table of Contents

1. [System Requirements](#system-requirements)
2. [Installation Guide](#installation-guide)
3. [How to Use MemoInk](#how-to-use-memoink)
   - [Getting Started on the Home Screen](#getting-started-on-the-home-screen)
   - [Creating Your First Topic](#creating-your-first-topic)
   - [Adding Entries](#adding-entries)
   - [Managing Your Profile](#managing-your-profile)
   - [Finding Other Users](#finding-other-users)
   - [Understanding Permissions](#understanding-permissions)
4. [Technical Details](#technical-details)
5. [Privacy and Data Management](#privacy-and-data-management)
6. [License Agreement](#license-agreement)
7. [Screenshots](#screenshots)

## System Requirements

### Minimum Requirements
- **Operating System:** Android 7.0 (Nougat)
- **Processor:** Quad-core 1.4 GHz
- **RAM:** 2 GB
- **Storage:** 50 MB free space
- **Network:** Active internet connection
- **Screen:** 720x1280 resolution

### Recommended Requirements
- **Operating System:** Android 10.0 or higher
- **Processor:** Octa-core 2.0 GHz
- **RAM:** 4 GB
- **Storage:** 100 MB free space
- **Network:** High-speed internet connection
- **Screen:** 1080x1920 resolution or higher

## Installation Guide

Getting MemoInk up and running is straightforward. Since it's not available on the Play Store, the app needs to be installed manually.

### Download and Install

1. **Get the APK File**
   - Visit the [Releases page](https://github.com/BerndHagen/MemoInk-Personal-Diary-App/releases) using an Android device's browser
   - Find the latest release and tap on the `.apk` file in the Assets section
   - The browser will download the file to the device

2. **Enable Installation from Unknown Sources**
   - Open the device's **Settings** app
   - Navigate to **Security** (or **Biometrics and Security** on some devices)
   - Find **Install unknown apps** or **Unknown sources**
   - Select the browser and toggle **Allow from this source**

3. **Install MemoInk**
   - Open your file manager and go to the **Downloads** folder
   - Tap on the downloaded MemoInk APK file
   - When prompted, tap **Install** and wait for the process to complete

4. **Start Using MemoInk**
   - Once installed, tap **Open** or find the MemoInk icon in your app drawer
   - Create your account or log in if you already have one
   - Start creating your first Topic and dive into journaling!

> **Tip:** If installation fails, make sure you have enough storage space and the correct permissions enabled.

## How to Use MemoInk

### Getting Started on the Home Screen

When you open MemoInk, you'll see all available Topics displayed chronologically with the newest ones at the top. Access to Topics depends on permissions set by their creators, and you'll get notifications if you try to access restricted content.

Topics you've created will show a **red cross** in the top-right corner. Tapping this cross will delete the entire Topic and all its entries permanently. As the creator, you can't remove yourself from your own Topics—you'll always have access to what you've made.

### Creating Your First Topic

Ready to start journaling? Creating a new Topic is simple:

- Tap the create button and enter a **title** for your Topic
- Make sure your title is unique—if someone else already used it, you'll need to pick something different
- Decide who should have access by selecting specific users, or leave it open for everyone
- Don't worry about getting permissions perfect right away; you can always adjust them later

### Adding Entries

This is where the magic happens. Each entry you create becomes part of your Topic's story:

- Tap **Add Entry** to start writing
- Give your entry a **title** and write your **description**
- Add an image if you want—others can tap on it to see it full-size
- Every entry gets timestamped automatically so you can track your thoughts over time
- Show appreciation for others' entries by liking them (you can only like each entry once)

### Managing Your Profile

Your profile is your identity in MemoInk. Here you can:

- Update your personal information and preferences
- Adjust your settings—changes save automatically to the database
- Control your privacy settings (Public or Private profiles)

**Important:** If you decide to delete your account, all Topics you've created will be permanently removed, including entries that other users contributed to those Topics.

### Finding Other Users

The search feature makes connecting with others easy:

- By default, you'll see a random selection of users
- Use the search field to find specific people—results update as you type
- Remember that users with Private profiles won't show their created Topics when you search for them

### Understanding Permissions

MemoInk gives you granular control over who can see your content:

- When creating a Topic, you can grant access to specific users
- If you don't select anyone, the Topic becomes public for everyone
- Want to change permissions later? Open the Topic, scroll down, and tap **Edit Topic Settings**
- Simply check or uncheck users to adjust who can access your content

## Technical Details

MemoInk is built on a solid foundation of modern technologies that ensure reliability and performance across Android devices.

### Core Technologies

**Xamarin Forms** serves as the backbone of MemoInk, allowing us to create a native Android experience with efficient development practices. Using Xamarin.Forms 5.0, the app delivers smooth performance while maintaining compatibility with Android 7.0 and higher.

**Firebase** powers the real-time features that make MemoInk special. The Firebase Realtime Database ensures your entries sync instantly across devices, while Firebase Storage securely handles your images and multimedia content.

### Key Libraries

The app leverages several essential libraries to deliver its functionality:
- **Newtonsoft.Json** for efficient data processing
- **NetStandard.Library** for cross-platform compatibility
- **Xamarin.Essentials** for platform-specific features

> If you encounter technical issues or have questions about MemoInk's implementation, feel free to [open an issue](https://github.com/BerndHagen/MemoInk-Personal-Diary-App/issues) on our GitHub repository.

## Privacy and Data Management

We take your privacy seriously. Here's exactly what MemoInk collects and how we handle your data.

### What We Store

MemoInk collects the following information to provide you with the best possible experience:

**Profile Information:** Your full name, username, email, encrypted password, profile picture, description, birthday, gender, country, and website
**Account Settings:** Privacy status, authorized users for shared Topics
**Communication Details:** Discord handle if you choose to provide it
**Content and Activity:** Topics you create, entries you write, collaboration settings, and timestamps

### How We Protect Your Data

All your data is encrypted and stored securely in our cloud infrastructure. Images and other media files are protected with access controls, ensuring only authorized users can view your content.

**Important:** When you delete your account, everything goes with it—including Topics you created and all entries within them, even those written by other users.

## License Agreement

We're excited to share MemoInk with you! Before you start using the app, please note these important terms:

By downloading and using MemoInk, you're agreeing to use it for **personal, non-commercial purposes** only. You cannot modify, distribute, or use the app commercially without our written permission.

We reserve the right to terminate your license if these terms are violated. MemoInk is provided "as is" without any warranties, and we're not liable for any damages that might result from using the app. You're responsible for ensuring your usage complies with all applicable laws.

For complete details, check out our [LICENSE](https://github.com/BerndHagen/MemoInk-Personal-Diary-App/blob/main/LICENSE) file.

## Screenshots

Want to see what MemoInk looks like in action? These screenshots showcase the app's key features and interface design. Take a look to get a feel for the app before downloading it. Keep in mind that future updates might introduce new features an

| MemoInk - Home              | MemoInk - Search               | MemoInk - Topics             |
|------------------------------|------------------------------|------------------------------|
| <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_topics.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_search.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_add.png" width="300px"> |

| MemoInk - Entries            | MemoInk - Profile            | MemoInk - Settings           |
|------------------------------|------------------------------|------------------------------|
| <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_entry.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_profile.png" width="300px"> | <img src="https://github.com/BerndHagen/MemoInk-Mobile-App/raw/main/img/v1.0.2-memoink_settings.png" width="300px"> |
