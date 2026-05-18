# The Creator Chronicle — Deployment Guide

## What's Inside This Folder

```
creator-chronicle/
├── index.html              ← Homepage
├── netlify.toml            ← Netlify config
├── admin/
│   ├── index.html          ← CMS login page (yoursite.com/admin)
│   └── config.yml          ← CMS settings
├── posts/
│   ├── together-we-rise.md       ← Article (markdown source)
│   └── together-we-rise.html     ← Article (live page)
└── assets/
    └── css/
        ├── main.css        ← Shared styles
        └── article.css     ← Article page styles
```

---

## Step 1 — Create a GitHub Account
Go to https://github.com and sign up for a free account.

## Step 2 — Create a New Repository
1. Click the green **New** button
2. Name it: `creator-chronicle`
3. Set it to **Public**
4. Click **Create repository**

## Step 3 — Upload Your Files
1. Click **uploading an existing file**
2. Drag your entire `creator-chronicle` folder contents into the page
3. Click **Commit changes**

## Step 4 — Create a Netlify Account
Go to https://netlify.com and sign up free using your GitHub account.

## Step 5 — Deploy to Netlify
1. Click **Add new site → Import an existing project**
2. Choose **GitHub**
3. Select your `creator-chronicle` repository
4. Leave all settings as default
5. Click **Deploy site**

Your site will be live in ~60 seconds at a URL like `https://creator-chronicle-abc123.netlify.app`

---

## Step 6 — Enable the CMS (so you can publish daily)
1. In Netlify dashboard → **Site configuration → Identity**
2. Click **Enable Identity**
3. Scroll to **Registration** → set to **Invite only**
4. Scroll to **Services → Git Gateway** → click **Enable Git Gateway**
5. Go to **Identity tab** → click **Invite users** → enter your email
6. Check your email and accept the invite

Now go to `https://yoursite.netlify.app/admin` — you can log in and publish!

---

## How to Publish a New Post Daily

1. Go to `yoursite.netlify.app/admin`
2. Log in with your email
3. Click **New Blog Post**
4. Fill in: Title, Author, Date, Category, Excerpt, and Body
5. Click **Publish**
6. The post goes live on your site automatically within seconds

---

## Optional: Add a Custom Domain (e.g. thecreatorchronicle.ng)
1. Buy your domain at https://qservers.net or https://whogohost.com (Nigerian registrars)
2. In Netlify → **Domain management → Add custom domain**
3. Follow the DNS instructions — takes about 10 minutes to go live

---

## Need Help?
Everything is free. No credit card. No expiry.
