# CalleeTune
Welcome to the official, and only legitimate, source of information for **CalleeTune**, the app.

This document serves as the public face of the app, providing a comprehensive user guide and a dedicated space for feedback. 

## Table of Contents
1. [Introduction](#introduction)
2. [System Requirements](#system-requirements)
3. [App Demo](#app-demo)
4. [User Interface (UI) Guide](#user-interface-ui-guide)
5. [Permissions Explained](#permissions-explained)
6. [Bug Reports & Feature Requests](#bug-reports--feature-requests)

---

## Introduction

**CalleeTune** is a utility application envisioned and created to enhance your Android device's incoming call experience. 

**The Purpose:** It is lovingly created in response to a single question: what if my favourite music/song set as a ringtone could continue across calls rather than start from the beginning on every incoming call so that I could hear it the whole? That'it. **CalleTune** allows the ringtone playback to resume from the last stopped position across incoming calls, allowing you to hear the whole song divided in parts across calls. Secondary, it provides you with an option to set your favourite music/song as a system ringtone as part of its interface. 

**Privacy First:** CalleeTune requires specific system access to serve its purpose reliably, but it **DOES NOT** collect and/or share any of your personal or device-specific information from your device.

---

## System Requirements

* **Operating System:** Tested to work reliably on Android 14 or higher. You can try to use it on lower version, but, it may not works as expected, and no support would be provided for it. 

---

## App Demo

Watch CalleeTune in action to see how easy it is to configure your custom ringtone experience:

> *[Placeholder: Embed YouTube or GIF link here]*
> `[![CalleeTune Demo Video](Link to Video Thumbnail Image)](Link to Video)`

---

## User Interface (UI) Guide

CalleeTune is designed with a straightforward interface so you can configure your ringtone in seconds.It works with your existing set ringtone as well without needing to change it. Below is a breakdown of every element you will see on the main screen.

### 1. Enable CalleeTune Toggle
![Enable App Placeholder](https://via.placeholder.com/600x150?text=Enable+CalleeTune+Toggle)
* **Purpose:** The master switch. When enabled, it allows CalleeTune to actively intercept incoming calls and play your favourite music. 

### 2. Track Status Diagnostic Box
![Track Status Placeholder](https://via.placeholder.com/600x150?text=Track+Status+Box)
* **Purpose:** A dynamic status box that lets you know if the app is ready. It displays your currently active ringtone, warns you if no valid track is configured, or alerts you if the app failed to set the ringtone.

### 3. Enable Ringtone Resume Toggle
![Ringtone Resume Placeholder](https://via.placeholder.com/600x150?text=Ringtone+Resume+Toggle)
* **Purpose:** When toggled ON, CalleeTune remembers exactly where your ringtone stopped playing during your last incoming phone call and will resume from that exact second on your next incoming call. If OFF, the playback starts from the beginning on every call, just like your normal ringtone. _**Recommended**_: Keep this ON. Otherwise, what's the point of having this app? :wink:

### 4. Enable Playback in DND Toggle
![DND Playback Placeholder](https://via.placeholder.com/600x150?text=Playback+in+DND+Toggle)
* **Purpose:** This setting allows your custom ringtone to bypass system silence i.e. DND-mode, ensuring your audio plays even when your device is set to "Do Not Disturb" mode. This is optional. Keeping this OFF, while keeping the app enabled, would make CalleeTune to work only outside DND-mode. In DND-mode, the app would let native Android handle the ringtone.

### 5. Track Progress Indicator
![Track Progress Placeholder](https://via.placeholder.com/600x150?text=Track+Progress+Text)
* **Purpose:** A simple text readout that shows your current resume position alongside the total duration of your loaded audio track.

### 6. Select Audio Button
![Select Audio Placeholder](https://via.placeholder.com/600x150?text=Select+Audio+Button)
* **Purpose:** Lets you directly select an audio file you want to use as your system ringtone.

### 7. Preview (Play/Pause) Button
![Preview Track Placeholder](https://via.placeholder.com/600x150?text=Preview+Play/Pause+Button)
* **Purpose:** Audio preview of the selected file.

### 8. Set As Ringtone Button
![Set Ringtone Placeholder](https://via.placeholder.com/600x150?text=Set+As+Ringtone+Button)
* **Purpose:** Registers your selected audio track as your official device ringtone. Note that even if you remove the app for some reason (but, kindly provide your feedback here under "Issues" for my knowledge and consideration), the ringtone set via this would continue to remain your system ringtone. 

### 9. Reset Position Button
![Reset Position Placeholder](https://via.placeholder.com/600x150?text=Reset+Position+Button)
* **Purpose:** Instantly resets the saved "resume" playback position back to the very beginning (00:00) of the audio.

### 10. Floating Action Buttons (Bottom Screen)
![FABs Placeholder](https://via.placeholder.com/600x150?text=Floating+Action+Buttons)
* **About ('i'):** Basic app info which would be very helpful should you decide to report any issues or features.
* **Permissions Info (Lock Icon):** Details all the system permissions the app requires.
* **Permission Alert (Cloud/Error Icon):** This icon flashes red to alert you if your device is missing any critical system permissions. Tapping it opens a tracker to help you fix the missing access.

---

## Permissions Explained

To make features like call-interception and ringtone-resuming possible, CalleeTune needs special access to certain parts of your Android device. We believe in total transparency. Here is exactly what we ask for and why:

* **Phone & Call State:** Required to detect an incoming call so the app knows exactly when to start/stop the ringtone playback.
* **Audio & Media:** Necessary to access your device's storage to load and play your selected favorite audio files.
* **Notifications:** Needed to ensure that the app functions smoothly and reliably in the background when a call arrives.
* **Battery Optimization:** Android often aggressively shuts down background apps to save battery. This permission ensures the system doesn't kill CalleeTune, so you never miss a ring. See FAQ for common issues for certain OEMs.
* **App Hibernation (Auto Revoke):** Highly recommended. Android automatically revokes background permissions from apps you haven't opened in a few months. This prevents CalleeTune from quietly breaking if you haven't opened the app in a while. 
  * *Note for Xiaomi Users:* MIUI completely throttles apps working in the background in ultra power-saving mode. You must go to `Settings -> Apps -> Backgroundautostart` and enable the CalleeTune toggle manually.
* **Do Not Disturb (DND) / DND Alarms:** Only requested if you explicitly enable the "Playback in DND" feature. It allows the app to bypass device silence. If denied, the app simply remains silent during DND mode.

---

## Bug Reports & Feature Requests

Encountered a bug or have an idea for a new feature? I want to hear about it!

Please use the **Issues** tab at the top of this repository to submit a ticket. When submitting a bug report, please include your device model, Android version, and steps to reproduce the issue.

If you want a new feature, I would recommend starting a new discussion under "Discussions" before raising it under issues. Similarly, prefer using "Q&A" under "Discussions" for a query before directly under "Issues" if you are not sure whether it's a bug.
