# YouTube Automation System

## Quick Start
1. Fork this repository to your GitHub account
2. Enable GitHub Codespaces for your account
3. Set up YouTube API credentials in repository secrets
4. Launch a codespace from your repository
5. Run the setup script inside the codespace

## Credentials Setup
Go to your repository settings > Secrets and variables > Actions
Add these secrets:
- YOUTUBE_CLIENT_ID
- YOUTUBE_CLIENT_SECRET  
- YOUTUBE_ACCESS_TOKEN
- YOUTUBE_REFRESH_TOKEN

## Usage
- Automatic: Workflows run daily at 9 AM UTC
- Manual: Use GitHub Actions "Manual Content Creation" workflow
- Custom: Modify workflows in the `.github/workflows/` directory

See SETUP.md for detailed instructions.