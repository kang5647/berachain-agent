# 🤖 Berachain Agent — Autonomous AI Agent for Berachain

**Berachain Agent** is an experimental AI agent built to autonomously post, engage, and represent the Berachain ecosystem across social platforms like **Twitter** and **Discord**. 

> **Status:** 🧪 Ongoing Development

---

## ✨ Features

- ✅ **Twitter Integration**
- ✅ **Autonomous Self-Posting**
- 🛠️ **Discord Integration** (In Progress)
- 🛠️ **On-chain Data Awareness** (Planned)
- and more to come!

---

## Duplicate the .env.example template

```bash
cp .env.example .env
```

\* Fill out the .env file with your own values.

### Add login credentials and keys to .env

```diff
-DISCORD_APPLICATION_ID=
-DISCORD_API_TOKEN= # Bot token
+DISCORD_APPLICATION_ID="000000772361146438"
+DISCORD_API_TOKEN="OTk1MTU1NzcyMzYxMT000000.000000.00000000000000000000000000000000"
...
-OPENROUTER_API_KEY=
+OPENROUTER_API_KEY="sk-xx-xx-xxx"
...
-TWITTER_USERNAME= # Account username
-TWITTER_PASSWORD= # Account password
-TWITTER_EMAIL= # Account email
+TWITTER_USERNAME="username"
+TWITTER_PASSWORD="password"
+TWITTER_EMAIL="your@email.com"
```

## Install dependencies and start your agent

```bash
pnpm i && pnpm start
```
