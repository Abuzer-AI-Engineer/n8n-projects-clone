# n8n-projects-clone

## 1. LinkedIn Content Parasite System

A automated workflow that scrapes LinkedIn posts from top creators and competitors, filters them for relevance, and rewrites them in your unique tone of voice.

### 🎯 What It Does

1. **Scrapes** LinkedIn posts from specified creator profiles
2. **Filters** posts using AI to identify content relevant to your target audience
3. **Rewrites** relevant posts in your tone of voice while preserving the original theme
4. **Stores** everything in a Google Sheet database with engagement metrics

### 🛠️ Tech Stack

- **n8n** - Workflow automation platform
- **Apify** - LinkedIn post scraping ($2 per 1,000 posts)
- **OpenAI GPT-4.1** - Content relevance filtering
- **OpenAI GPT-4.1** - Post rewriting
- **Google Sheets** - Database storage

### 📋 Prerequisites

- n8n account (self-hosted or cloud)
- Apify account ($5 free credits included)
- OpenAI API key
- Anthropic API key (Claude)
- Google account

### 🚀 Setup

1. **Configure the Form**
   - LinkedIn Account 1 URL
   - LinkedIn Account 2 URL
   - Number of posts per profile

2. **Connect Services**
   - Link Apify account in n8n
   - Add OpenAI API credentials
   - Connect Google Sheets

3. **Customize Prompts**
   - Update target audience description
   - Define your tone of voice
   - Set content filtering criteria

### 📊 Output Format

The system creates a Google Sheet with:
- Date of post
- Creator name
- Post URL
- Original post text
- Rewritten post text
- Number of likes
- Number of comments
---
