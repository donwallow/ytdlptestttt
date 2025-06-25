# yt-dlp GitHub Action with Firebase Integration

This repository demonstrates how to run [yt-dlp](https://github.com/yt-dlp/yt-dlp) inside a GitHub Action workflow and send the download results to Firebase Realtime Database.

---

## How it works

- When triggered via API, a GitHub Action workflow runs yt-dlp to process video downloads.  
- The action uses a predefined cookie from an originally logged-in YouTube account to handle authenticated requests.  
- Download status and results are sent and updated in Firebase Realtime Database for real-time tracking.

---

## Usage

This repository is provided for **educational purposes only**.  
If you want to create a similar setup:  
- Fork or clone this repo  
- Replace the cookie with your own authenticated YouTube account cookie  
- Set up your own Firebase Realtime Database and update the integration accordingly  
- Securely store your GitHub tokens and Firebase credentials

---

## Important Notice

Downloading videos from YouTube may violate YouTube’s Terms of Service and copyright laws.  
However, some content creators — especially tutorial creators and educators — explicitly allow and even encourage downloading their videos for offline use.  

This project can provide more control and convenience than YouTube’s limited app experience while respecting creators' rights.  

**Please do not use these methods without permission from the content creator. Always respect copyright and use this project responsibly and legally.**


---

## Author

FrozenFlow

---

Thank you for checking out this project!

