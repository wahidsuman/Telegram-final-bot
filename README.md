# Telegram MCQ Bot - Cloudflare Workers

A Telegram bot built on Cloudflare Workers that posts hourly MCQs, handles coupon distribution, and provides admin analytics using KV storage.

## Features

- 🧠 **Hourly MCQ Posting**: Automatically posts multiple choice questions to a Telegram group
- 📊 **Analytics**: Daily and monthly reports with user statistics and accuracy metrics
- 🎫 **Coupon System**: Distributes discount coupons and handles bargain requests
- 👨‍💼 **Admin Panel**: Upload questions, view reports, and manage the bot
- 🔒 **Secure**: Webhook validation and admin-only access controls

## Setup Instructions

### 1. Create KV Namespace

```bash
npx wrangler kv namespace create STATE
