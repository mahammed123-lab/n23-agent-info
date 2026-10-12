# Privacy Policy for N23 Agent

This is a personal automation tool that runs on the owner's own computer (and their own GitHub Actions runner) to manage their own YouTube channel.

## What the app does
- Uploads the owner's OWN videos and gaming reels to their own YouTube channel on request
- Reads the owner's own channel statistics (views, likes, subscribers, revenue) for a private dashboard
- Searches YouTube for viral videos and downloads them for personal research

## Google and YouTube data
- The app uses the **YouTube Data API v3** and **YouTube Analytics API** under the [YouTube API Services Terms of Service](https://developers.google.com/youtube/terms/api-services-terms-of-service) and [Developer Policies](https://developers.google.com/youtube/terms/developer-policies).
- User data is processed in accordance with [Google's Privacy Policy](https://policies.google.com/privacy).
- The app only accesses the Google account that grants consent, and only data belonging to that account's own channel.

## OAuth credentials and storage
- **Google OAuth tokens** (access + refresh tokens) are stored only on the owner's machine as `token.json` and only in GitHub's encrypted Secrets storage for automation. They are never shared with anyone.
- **Video files** are downloaded temporarily to the owner's machine; local copies are removed after upload.
- **Channel statistics** (view/like/comment counts) are cached locally to show growth between checks.

## Revoking access and data deletion
- Access can be revoked at any time at [https://myaccount.google.com/permissions](https://myaccount.google.com/permissions).
- Deleting the local `token.json` file removes all stored credentials immediately.

## Third parties
- Google / YouTube APIs are the only external services used.
- The app does not collect, sell, or share any user data. There are no analytics, trackers, or ads.

## Contact
- Owner: Mahammed Hussain — mahammedhussain256@gmail.com
