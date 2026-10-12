# Privacy Policy for N23 Agent (YouTube Agent)

This is a personal automation tool that runs on the owner's own computer (and their own GitHub Actions runner) to manage their own YouTube channel.

## What the app does
- Searches YouTube for viral videos and downloads them for personal research
- Uploads the owner's OWN videos to their own YouTube channel on request
- Reads channel statistics (views, likes, subscribers, revenue) for the owner

## Data the app accesses
- **Google OAuth credentials** (access + refresh tokens): stored only on the owner's machine as `token.json`, and only in GitHub's encrypted Secrets storage for automation. Never shared with anyone.
- **Video files**: downloaded temporarily to the owner's machine; local copies are deleted after upload.
- **Channel statistics**: read via the official YouTube Data API and shown only to the owner.

## Third parties
- Google / YouTube APIs are the only external services used.
- The app does not collect, sell, or share any user data. There are no analytics, trackers, or ads.

## Account used
- The app operates exclusively on the Google account that grants consent (the owner's own channel).

## Contact
- Owner: Mahammed Hussain — mahammedhussain256@gmail.com
