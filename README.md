# Joomni + Claude MCP: Manage Your Online Store and Website by Chatting

Connect **Joomni** to **Claude** using **MCP (Model Context Protocol)** and run your website and online store from a chat. Ask about sales, orders and stock, build and edit pages, write blog posts, check your traffic and leads, all in plain language.

It uses your own Claude subscription, starts **read-only**, and **asks for your approval before every change**.

[Joomni Website](https://joomni.com) | [AI Connections page](https://joomni.com/features/ai-connections) | [Pricing](https://joomni.com/pricing) | [Documentation](https://joomni.com/documentation)

---

## Table of Contents

- [What is Joomni?](#what-is-joomni)
- [What is MCP?](#what-is-mcp-model-context-protocol)
- [What you can do](#what-you-can-do)
- [Requirements](#requirements)
- [How to connect Joomni to Claude](#how-to-connect-joomni-to-claude)
- [Permissions and safety](#permissions-and-safety)
- [Example prompts](#example-prompts)
- [Tips for better results](#tips-for-better-results)
- [Using ChatGPT or other MCP apps](#using-chatgpt-or-other-mcp-apps)
- [Troubleshooting](#troubleshooting)
- [Frequently asked questions](#frequently-asked-questions)
- [Learn more](#learn-more)

---

## What is Joomni?

[Joomni](https://joomni.com) is Nepal's all-in-one, no-code platform to build a professional website, launch an online store, take local payments (eSewa, Khalti, IME Pay, Fonepay), book Pathao and Upaya pickups, sell in-store with an offline-ready POS, take online bookings and grow your business, all from one dashboard.

## What is MCP (Model Context Protocol)?

**MCP** is an open standard that lets AI apps connect safely to the tools and data you already use. Instead of copying numbers into a chat window, the AI can read and work with your store directly, within the permissions you give it.

Joomni implements MCP, so any MCP-compatible app can connect to your store. Claude and ChatGPT work today.

## What you can do

### Sales, orders and customers

- Ask how this week compared with last week
- See which orders are still waiting to be fulfilled
- Find your best customers, or customers who used to order and have gone quiet

### Stock and store settings

- See what is running low and what will run out first
- Adjust stock levels (with your approval)
- Review and update store settings

### Build and edit your website

- Create new pages, such as About, Pricing or Contact
- Add, edit, reorder and remove sections, such as testimonials, FAQs and heroes
- Change headlines and page content
- Update header, footer and navigation menus
- Change theme colors and settings

### Content and SEO

- Write blog posts and save them as drafts
- Check every page for missing SEO titles and descriptions, and write better ones
- Upload images to your media library from a URL

### Bookings, leads and traffic

- See what is in the diary for a given day
- Review leads and update their status
- Check website traffic, live visitors and your busiest booking hours

---

## Requirements

- A Joomni account and a store
- **A Joomni Business or Enterprise plan.** AI connections are included on these plans. Every new store gets a 14-day free trial of the Business plan, with no card needed. [See plans](https://joomni.com/pricing)
- A Claude account with support for connectors

You do not pay extra for AI. Your own Claude subscription does the thinking, so this does not use your Joomni AI credits.

---

## How to connect Joomni to Claude

1. **Sign in or sign up** at [joomni.com](https://joomni.com).
2. **Open your dashboard**, then go to **Settings**.
3. **Open the MCP Connection tab.**
4. **Copy your MCP URL.**
5. **Open Claude** and go to your connector settings.
6. **Add a new connector.** Name it Joomni and paste your MCP URL.
7. **Sign in to Joomni and allow access.** Choose the store you want Claude to reach.
8. **Start a new chat**, turn on Joomni, and type your first request.

> Keep your MCP URL private. Treat it like a key to your store, and never post it in screenshots or videos.

---

## Permissions and safety

Handing an AI access to your store should feel like a decision, not a default. Joomni is built around that.

| Safeguard | How it works |
|---|---|
| **Read-only by default** | A new connection can answer questions and change nothing. |
| **You allow changes** | Permission to make changes is something you grant on purpose. |
| **Approval for every change** | Each change is described to you first and waits for your yes. |
| **Separate permission for custom code** | Code is checked before it is saved and stays hidden on a live page until you unhide it. |
| **One store only** | You pick one store when you connect. The connection cannot reach your other stores. |
| **Full activity log** | Every action is recorded: what was done, which app did it, when, and whether it worked. |
| **Instant disconnect** | Disconnect any app in one click and it stops working immediately. |

Start read-only, try a few questions, and only grant change permissions when you are comfortable.

---

## Example prompts

Copy these into a new Claude chat with Joomni turned on. Replace the details with your own business.

### Sales and orders

```
How did we do last week compared with the week before?
```

```
Which orders are still waiting to be fulfilled?
```

```
Who are my best customers this month?
```

### Stock

```
What is about to run out?
```

```
Set the stock of "Cotton Kurta Set" to 40.
```

### Pages and design

```
Create an About page for my bakery with a hero section and our story.
```

```
Add a testimonials section to my homepage.
```

```
Add a frequently asked questions section to the About page.
```

```
Change my homepage headline to "Fresh bread, baked every morning".
```

```
Change my theme's primary color to green.
```

### SEO and content

```
Check every page for missing titles and descriptions, and write better ones where they are weak.
```

```
Write a blog post about 5 tips for first-time customers and save it as a draft.
```

### Bookings, leads and traffic

```
What is in the diary for Saturday?
```

```
How many leads did I get this week?
```

```
Show me my website traffic for the last 7 days.
```

---

## Tips for better results

- **Start read-only.** Ask questions first, then allow changes when you trust the results.
- **Be specific.** "Create an About page for my bakery with a hero and our story section" works better than "make a page".
- **Give real business details.** Names, offers and tone help Claude write content that fits your brand.
- **Work in small steps.** Ask for one change at a time and check the result.
- **Draft first.** For blog posts, ask for a draft so you can review before publishing.
- **Check your live site** after a change, and use the activity log if you want to see what happened.

---

## Using ChatGPT or other MCP apps

Joomni works with any app that supports the Model Context Protocol, including ChatGPT. The idea is the same: add Joomni as a connector, sign in once, choose your store, and start asking. The exact menu names differ by app, so check that app's connector or integration settings.

---

## Troubleshooting

**I can't find the MCP Connection tab.**
Make sure you are signed in and on a plan that includes AI connections (Business or Enterprise), then look in your dashboard Settings.

**Claude does not show Joomni in my chat.**
Check that the connector was added, then start a new chat and make sure Joomni is turned on for it.

**Claude can answer questions but won't change anything.**
That is the default. Connections start read-only. Grant change permission in your Joomni connection settings when you are ready.

**It asks me to sign in again.**
Sign in to Joomni and allow access when prompted.

**A change is not showing on my live site.**
Refresh your site and check the page in your Joomni dashboard. Custom code added through AI stays hidden on a live page until you unhide it.

**I want to see what the AI did.**
Open your connection activity log in your Joomni settings.

**I want to disconnect.**
Disconnect the app from your Joomni connection settings, or remove the connector in Claude.

---

## Frequently asked questions

### What does connecting Claude to Joomni do?
It lets Claude read and work with your store directly. You can ask about sales, orders, stock and customers, and, if you give permission, have it update orders, adjust stock, build pages and write website sections.

### Do I need to pay extra?
No. Your own Claude subscription does the thinking. The connector is included on the Business and Enterprise plans.

### Can Claude change my store without asking?
No. A new connection is read-only. Even after you allow changes, each one is described to you and waits for your approval.

### Can it see my other stores?
No. The connection can only reach the single store you choose.

### Which AI apps work with this?
Any app that supports MCP. That includes Claude and ChatGPT today.

### How do I know what it has done?
Every action is recorded in your Joomni settings with what was done, which app did it, when, and whether it worked.

### Do I need to know how to code?
No. You describe what you want in plain language.

### Is this only for Nepal?
Joomni is built for businesses in Nepal, with local payments and delivery built in.

---

## Learn more

- [Joomni AI Connections](https://joomni.com/features/ai-connections)
- [All Joomni features](https://joomni.com/features)
- [Pricing and plans](https://joomni.com/pricing)
- [Documentation](https://joomni.com/documentation)
- [Help Center](https://joomni.com/help)
- [Contact the Joomni team](https://joomni.com/contact)

**Follow Joomni:** [Facebook](https://www.facebook.com/joomni225) | [Instagram](https://www.instagram.com/joomni.np) | [LinkedIn](https://www.linkedin.com/company/joomni)

---

## Keywords

Joomni, Joomni MCP, connect Claude to online store, Claude MCP ecommerce, Claude connector online shop, Model Context Protocol ecommerce, MCP connector for ecommerce, AI store management Nepal, run store with AI, manage website with AI, AI website builder Nepal, connect ChatGPT to online store, website builder Nepal, online store builder Nepal

---

*Joomni: build, launch and grow your online business in Nepal.*
