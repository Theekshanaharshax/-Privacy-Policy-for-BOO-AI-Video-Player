# Privacy Policy for Boo — AI Video Player

**Last Updated:** September 30, 2026  
**Developer:** 6AM STUDIO  
**Application:** Boo — AI Video Player (com.sixamstudio.boo)  
**Contact:** 6amstudio.dev@gmail.com

## 1. Introduction
Welcome to Boo — AI Video Player ("we," "our," or "the App"), developed by 6AM STUDIO. We are committed to protecting your privacy. This Privacy Policy explains how our application accesses, uses, and safeguards information when you use the Boo mobile and desktop application.

By installing and using Boo, you agree to the practices described in this Privacy Policy.

## 2. Information We Access and How We Use It

### A. Local Storage & Media Files Access
* Permissions Used: READ_MEDIA_VIDEO, READ_EXTERNAL_STORAGE, MANAGE_EXTERNAL_STORAGE (All Files Access).
* Purpose: Boo is an offline-capable video and media player. We access local storage strictly to:
  1. Discover and display your local video files in organized folder hierarchies.
  2. Locate and load external subtitle files (.srt, .vtt) placed alongside your video files.
  3. Save locally cached Sinhala subtitle translations to your device for instant offline playback.
* Important Notice: Your video and audio files NEVER leave your device. We do not upload, stream, copy, or transmit your personal videos or photos to any external server.

### B. AI Subtitle Translation (Google Gemini)
* What is Processed: When you select or auto-generate Sinhala subtitles, the plain text dialogue lines from the subtitle file (.srt / .vtt) are transmitted to the Google Gemini API (generativelanguage.googleapis.com) to generate natural Sinhala translations.
* What is NOT Sent: No video files, no audio streams, no file names, and no personal user information are ever sent to Google Gemini.
* Third-Party Policy: AI dialogue processing complies with Google's API Terms of Service and Privacy Policy: https://policies.google.com/privacy.

### C. Online Subtitle Search
* If you enable "Auto-Search Online Subtitles" in Settings, the app may query public movie database search endpoints (such as OpenSubtitles CDN / IMDb) using the movie title to retrieve matching subtitle files.
* Personal camera recordings and home videos are filtered out and excluded from online subtitle searches.

### D. User Settings & Watch History
* The app stores your watch history (playback resume position), subtitle visual preferences (font size, color, timing offsets), and optional custom Gemini API keys locally on your device via secure SharedPreferences.
* This data is stored strictly on your local device and is never shared, synced, or sold.
* You can delete all locally stored data at any time via Settings → Privacy & Data Controls → "Clear Watch History & Saved Key".

## 3. Data Collection and Tracking
* No Account Creation: You are not required to create an account or provide personal information to use Boo.
* No Analytics / No Ad Tracking: Boo does not collect personally identifiable information (PII) or track your location.
* No Data Selling: We do not sell, rent, or monetize your personal data or viewing habits.

## 4. Third-Party Services
Boo interacts with the following third-party APIs solely to provide core media functionality:
1. Google Gemini Generative AI (Google LLC): For real-time subtitle translation into Sinhala.
2. OpenSubtitles / Stremio CDN: For public movie subtitle retrieval.

## 5. Children's Privacy
Boo does not knowingly collect or solicit any personal information from children under the age of 13. Because the app functions as a local media player without user accounts or tracking, it is safe for general audiences.

## 6. Security of Your Information
We prioritize your privacy by keeping media playback and watch history entirely on your local device. Network communication for AI translation and subtitle downloads is conducted over secure encrypted HTTPS connections (TLS/SSL).

## 7. Changes to This Privacy Policy
We may update this Privacy Policy from time to time. Any updates will be posted with a revised "Last Updated" date.

## 8. Contact Us
If you have any questions or concerns regarding this Privacy Policy, please contact us at:
* Developer: 6AM STUDIO
* Email: 6amstudio.dev@gmail.com
