---
title: Setup Stripe
nav_order: 1
---

# How to Setup Stripe for Mega Taxi App
{: .no_toc }

One of the most important things in an taxi business is giving our clients an easy way to finalize their purchase while maintaining a secured transaction.

**We will be using Stripe as our payment processing partner since they offer amazing support while trying their best to keep away the fraudulent charges.**

## Table of Content
{: .no_toc .text-delta }

- TOC
{:toc}

## Create new Stripe account

Visit Stripe and create your account on their [Sign up](https://dashboard.stripe.com/register) page.

To complete your registration you will need to activate your email address and fill business related information:

### Activate your Account

- In Stripe's dashboard click on `Activate your account` and fill out the first page then click Next.
- Fill up the required info in `Business representative` page and click Next.
- Fill up the required info in `Business details` page and click Next.

### Set-up Two-step Authentication

Two-step authentication can be set up using SMS (common) or an authenticator app.

After verifying you will get an emergency backup code, please store that in a safe document. This will be used in case you couldn't authenticate your account in the future.

### Get API keys

- Once you are in your dashboard click on Developers in the left.
- Click API keys.
- Copy the Publishable key and save it.
- Click on reveal key next to Secret Key and copy the Secret key and save it.
