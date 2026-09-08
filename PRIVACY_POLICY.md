# Privacy Policy - ComplianceClips

**Last Updated:** September 2026

## 1. Introduction
ComplianceClips is a tool that automates the curation and conversion of Reddit content into video format for distribution on social media platforms. This Privacy Policy explains how we handle data.

## 2. What Data We Collect

### API Data
- Reddit: We access public post data (titles, content, author names, timestamps) from specified subreddits
- TikTok: We store access tokens needed to post content to your account
- YouTube: We store API credentials needed to upload Shorts
- Instagram: We store API credentials needed to post Reels

### User Data
- GitHub repository information (for deployment)
- API keys and tokens (stored securely in GitHub Secrets)

## 3. How We Use Data

We use collected data to:
- Fetch public Reddit posts from specified subreddits
- Generate text-to-speech voiceovers
- Create video files by combining Reddit content with gameplay footage
- Post videos to your TikTok, YouTube, and Instagram accounts
- Track posting schedules and automation logs

## 4. Data Storage

- **API Credentials:** Stored securely in GitHub Secrets (encrypted)
- **Video Files:** Stored temporarily in GitHub Actions (deleted after posting)
- **Logs:** Stored in GitHub Actions logs (retained for 30 days)
- **Reddit Posts:** Not permanently stored; fetched fresh daily

## 5. Third-Party Services

This tool integrates with:
- **Reddit API** - Read-only access to public posts
- **TikTok API** - Publishing videos to your account
- **YouTube API** - Uploading Shorts to your channel
- **Instagram API** - Posting Reels to your profile
- **Google Cloud Text-to-Speech** - Converting text to audio
- **Play.ht** - Alternative text-to-speech service

Each service has its own privacy policy. We recommend reviewing them.

## 6. Data Security

- API keys and tokens are stored in GitHub Secrets (encrypted at rest)
- No data is sent to third parties except as necessary for platform APIs
- All communications use HTTPS encryption
- We do not collect or store user personal information

## 7. Reddit Data

- We only access **public** Reddit posts
- We do not collect private messages or user data
- We credit original authors in all videos
- We comply with Reddit's API Terms of Service

## 8. Data Retention

- Video files are deleted after posting
- Logs are retained for 30 days then deleted
- API credentials are stored indefinitely (while you use the tool)
- Reddit post data is not stored (fetched fresh daily)

## 9. Your Rights

You can:
- Delete your API credentials from GitHub Secrets at any time
- Disable the automation by deleting the GitHub workflow
- Request data deletion by removing the repository
- Contact us with privacy concerns

## 10. Changes to This Policy

This Privacy Policy may be updated at any time. Continued use of the tool implies acceptance of changes.

## 11. Contact

For privacy concerns or questions:
- GitHub: compliance-clips

---

**By using ComplianceClips, you accept this Privacy Policy.**
