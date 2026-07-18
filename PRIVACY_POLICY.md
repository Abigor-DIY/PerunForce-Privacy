# Privacy Policy — PerunForce

**Effective date:** May 27, 2026  
**Last updated:** July 18, 2026
**App:** PerunForce (`com.perunforce.perun_force`)  
**Developer and publisher:** Rafał Bryndza, operating the PerunForce app
**Contact:** abigor82@gmail.com

## 1. Introduction

PerunForce is a health, wellness, fitness, nutrition, supplements, and habit-tracking application. This Privacy Policy explains what data PerunForce accesses, collects, stores, uses, and shares when you use the app.

If you do not agree with this policy, do not use the app.

## 2. Data We Collect

Depending on the features you use, PerunForce may collect and process the following categories of data.

### 2.1 Account and authentication data

- Google account email address
- Google display name
- Google profile photo URL
- Internal user ID

### 2.2 Profile data

- Name or nickname
- Date of birth
- Gender
- Height and weight
- Diet type
- Daily goals such as protein and water targets
- Health goals and related preferences
- Profile photo

### 2.3 Subscription and purchase entitlement data

- Current PerunForce plan
- Subscription entitlement status
- Billing cycle label
- Purchase source identifier such as Google Play Billing

PerunForce does not collect or store payment card numbers. Payments and billing account management are handled by Google Play.

### 2.4 Health and wellness data

- Health interview answers
- Self-reported symptoms
- Self-reported medications
- Health conditions selected by the user
- Lifestyle and wellbeing entries such as sleep quality, energy, stress, caffeine, hydration, alcohol, nicotine, and notes
- Health support plans and symptom tracking entries

### 2.5 Nutrition data

- Meals and nutrition logs
- Food names, brands, and barcodes
- Calculated calories and macronutrients
- Nutrition goals
- Meal notes
- Optional meal photos submitted for AI analysis
- Optional product packaging, ingredient-list, and nutrition-label photos submitted for AI data extraction
- Optional meal-description text or voice transcript submitted for AI parsing

### 2.6 Voice input and microphone access

Voice meal entry is optional. PerunForce requests microphone access only after you open the voice meal entry feature, review an in-app explanation, and choose to continue.

- The microphone is active only while you are using the voice capture control.
- PerunForce does not listen in the background and does not create or store an audio recording.
- Audio is processed by the Android speech recognition service available on your device. Depending on the device, language, and Android settings, recognition may occur on the device or be processed by the recognition service provider.
- PerunForce receives the resulting text transcript and, when available, alternative recognition results. It does not receive a reusable audio file from the Android speech recognition service.
- After separate confirmation for AI processing, the transcript may be sent through the PerunForce backend to Google Gemini to identify food names, amounts, and portions.
- You can decline microphone access and enter the meal manually.

The structured meal data you choose to save is handled like other nutrition data described in this policy.

### 2.7 Supplements data

- Supplement stack data
- Dosages, schedules, reminders, and overrides
- Supplement intake logs
- Supplement trial data, check-ins, ratings, notes, and summaries

### 2.8 Fitness and body data

- Workout history and workout sessions
- Body weight history
- Body measurements
- Body progress entries
- Optional progress photos

### 2.9 Health Connect data

If you connect Health Connect and grant access, PerunForce may read:

- Steps
- Sleep sessions
- Workouts / exercise
- Total calories burned
- Active calories burned
- Basal metabolic rate
- Distance
- Weight

If you explicitly expand access, PerunForce may also read optional extended data such as:

- Heart rate
- Resting heart rate
- Heart rate variability (HRV)
- Oxygen saturation (SpO2)
- Body fat percentage

PerunForce reads Health Connect data only after you grant permission. PerunForce does not write health data into Health Connect.

Health Connect data is used only for user-facing wellness and fitness features inside the app. It is not sold, used for advertising, or used for cross-app tracking.

By default, Health Connect data is processed and stored locally. If you sign in and separately enable Health Connect cloud history, PerunForce synchronizes processed day-level summaries with your account through Supabase so your history can be available on your other devices. These summaries may include daily activity, sleep, workout, energy, weight, body-composition, and recovery values together with the source platform and synchronization time. PerunForce does not upload raw point-by-point Health Connect records through this cloud bridge. You can keep Health Connect local-only or disable future cloud synchronization at any time. Disabling synchronization stops future transfers but does not automatically delete summaries already synchronized; those summaries are covered by the account and data deletion process described below.

### 2.10 Family profile data

- Family profile name
- Relationship label
- Emoji or avatar-style identifier
- Optional date of birth
- Optional basic profile metrics when entered by the user

### 2.11 App usage and operational data

PerunForce may process limited operational metadata needed to provide paid features, enforce usage limits, and improve reliability, such as:

- feature identifier and request count
- request timestamp, completion status, and approximate token usage for AI features
- subscription plan and entitlement status
- interactions with optional Plus or Pro prompts
- technical error information without intentionally attaching meal text, microphone audio, photos, or health notes

Some of this metadata remains local. When you are signed in, limited usage or entitlement events may be stored in Supabase. PerunForce does not use this data for third-party advertising or cross-app tracking.

## 3. How We Use Data

We use data to:

- provide the app’s core features
- create and manage your account
- personalize nutrition, supplements, fitness, and health workflows
- sync your data between devices
- display Health Connect data that you authorize
- generate optional AI-powered informational outputs
- let you export, review, or delete your data
- maintain app security, integrity, and troubleshooting

PerunForce is a wellness and informational app. It does not diagnose, treat, or replace professional medical care.

## 4. AI Features

PerunForce includes optional AI features. When you use those features, relevant data may be sent to Google Gemini for processing.

Examples include:

- health interview summaries
- supplement analysis against your profile
- meal photo analysis
- text or voice-transcript meal parsing

For health-related AI flows, PerunForce requests explicit in-app consent before sending relevant health data to the AI service.

AI features are optional. If you do not use them, that AI-related processing does not occur.

AI-generated outputs are informational only and are not medical diagnosis, treatment, or professional medical advice.

## 5. Health Connect

PerunForce uses Health Connect only after you explicitly grant access.

PerunForce requests a minimal Health Connect scope first. Optional recovery and body-composition access is requested separately only if you choose to expand access.

Health Connect data is used only for app features such as:

- activity summaries
- sleep tracking
- workout history
- weight tracking
- optional recovery context

## 6. Storage and Security

### 6.1 Local device storage

PerunForce stores user data on the device. Sensitive local data is protected using app-side storage protections, including encrypted health-related storage where applicable.

### 6.2 Cloud services

When you sign in, PerunForce may store and synchronize data using Supabase for:

- authentication
- database synchronization
- storage of selected media such as profile photos or exports

If you use the app without signing in, your app data remains local except when you explicitly use optional online features such as AI analysis, Open Food Facts lookup, or Health Connect access granted on your device.

### 6.3 Data transmission

Network traffic is encrypted in transit using TLS.

No system can guarantee absolute security, but we take reasonable technical measures to protect user data.

## 7. Third-Party Services

PerunForce uses third-party service providers to operate app functionality.

These may include:

- **Supabase** for authentication, storage, and synchronization
- **Google Sign-In** for account authentication
- **Google Play Billing** for subscription purchases and payment management
- **Google Gemini** for optional AI processing
- **Android speech recognition service** for optional voice-to-text input; the active provider depends on the user’s device and Android configuration
- **Open Food Facts** for food database lookups based on barcode or search

PerunForce does not sell personal data.

## 8. Data Sharing

PerunForce does not sell your personal or health data and does not use it for advertising.

Data may be processed by service providers acting on our behalf when required to operate the app’s functionality, such as cloud sync, authentication, storage, or optional AI features.

## 9. Data Retention

We retain data for as long as needed to provide the app’s features, maintain synchronization, comply with legal obligations, resolve disputes, and enforce agreements, unless you request deletion.

Some technical backup or recovery copies may remain for a limited time before deletion cycles complete.

PerunForce does not retain raw microphone audio. Voice transcripts sent for optional AI meal parsing are processed to produce the result; meal entries saved by the user contain structured nutrition data rather than an audio recording.

## 10. Deletion and User Choices

You can:

- use parts of the app without signing in
- disconnect Health Connect
- decline AI features
- delete your account and associated data from inside the app

Public account and data deletion instructions are available at:
`https://abigor-diy.github.io/PerunForce-Privacy/account-deletion/`

If cloud deletion fails, the app may offer local-only device cleanup and will clearly inform you that cloud data may still remain until remote deletion succeeds.

## 11. Children

PerunForce is not directed to children under the minimum age required by applicable law or platform policy for the features being used.

Some features may be restricted for underage profiles.

## 12. Your Rights

Depending on your jurisdiction, you may have the right to:

- access your data
- correct your data
- export your data
- request deletion of your data
- withdraw consent for optional processing such as AI features

For requests, contact: `abigor82@gmail.com`

## 13. Privacy Policy Availability

This Privacy Policy is published on a public, non-geofenced URL for Google Play compliance. The same policy should be linked:

- in Google Play Console
- inside the app

## 14. Changes to This Policy

We may update this Privacy Policy from time to time. The current version will be identified by the latest updated date shown at the top of this document.
