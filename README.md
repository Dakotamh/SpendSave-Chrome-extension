# SpendSave

A browser extension that steps in at checkout and gives you instant financial awareness feedback before you buy. It's meant to help you pause and ask, "Do I actually need this?"

## How it works

SpendSave uses psychological and sociological principles to challenge the "buy now" impulse. Instead of just blocking you, it makes you stop and think about whether this purchase is worth it, or whether the money would do more good invested in a fund.

Shows how much the item would grow if invested for 10 years  & converts the price into hours of work & asks a reflection question before checkout

## Features

- Detects when you're on a checkout page
- Shows feedback before you complete the purchase

## Tech stack

- **Extension:** HTML, CSS, JavaScript
- **Backend:** Node.js
- **Database:** MongoDB

## Installation

1. Download or clone this repository.
2. Open your browser's extensions page (`chrome://extensions` in Chrome, `edge://extensions` in Edge).
3. Turn on **Developer mode**.
4. Click **Load unpacked** and select the project folder.
5. Go to a checkout page on a shopping site and the extension will appear.

[IF THE BACKEND MUST RUN LOCALLY, ADD: `cd backend`, `npm install`, `node server.js`, and note any MongoDB connection setup.]

## Usage

Shop as usual. When you reach checkout, SpendSave shows its feedback. [DESCRIBE WHAT THE USER CAN DO: dismiss it, continue anyway, set a budget, etc.]

## Supported sites

Tested on Amazon, Target, Ebay, StockX, etc

## Future improvements

- Use AI/ML for more personalization/variety in the psychology responses
- Tier System (WIP)
