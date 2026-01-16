# iOS User Profile Demo App

## Overview
This iOS application demonstrates a simple and user-friendly profile setup flow. The app allows users to enter basic personal information, upload a profile photo with instant preview, and opt in to push notifications after being shown a clear explanation of their value.  

The project is designed to showcase common iOS development patterns such as form handling, image picker integration, and permission management, following Apple’s best practices for user experience and privacy.


## Features

### 1) Name & Username Input
- Text field-based form for collecting:
  - **Name**
  - **Username**
- Clean and simple UI suitable for onboarding or profile setup flows
- Easily extendable with validation and error handling

### 2) Photo Upload (Image Picker + Preview)
- Uses the system image picker to select a photo from the photo library
- Displays a **visual preview** of the selected image
- Designed to simulate a profile picture upload experience

### 3) Push Notifications (Permission Request)
- Requests notification permission using `UNUserNotificationCenter`
- Presents a **clear value proposition** before triggering the system prompt
  - Example: “Enable notifications to receive important updates and reminders.”


## User Flow

1. User enters **Name** and **Username**
2. User selects and previews a **profile photo**
3. User is informed about the benefits of notifications
4. System push notification permission dialog is shown


## Requirements
- Xcode 14+  
- iOS 15+ (recommended)  
- Swift  
- UIKit or SwiftUI (project-agnostic)
