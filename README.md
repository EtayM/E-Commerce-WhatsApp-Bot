# E-Commerce WhatsApp Bot

A WhatsApp bot designed to help users find better deals on products, discover themed shopping lists (e.g., birthday gifts, holiday costumes), and streamline the e-commerce experience.

## Overview

This project aims to streamline product searches and comparisons for e-commerce consumers. Users can send a message to the bot with a product link or descriptive text, and the bot automatically searches other online stores for better prices, relevant deals, or curated recommendations.

**Key use cases include:**

- **Finding Better Deals**: Paste a product link from an online store, and the bot will attempt to find the same product at a cheaper price elsewhere.  
- **Curated Product Lists**: Browse or request recommended lists for birthdays, holidays, seasonal items, or other special occasions.  
- **Product Searches**: Describe a product in your own words, and the bot returns the best deals found across supported platforms.  

The focus is on convenience, cost savings, and an efficient chat-based interface.

---

## Features

1. **Better Deal Finder**  
   - Users send the bot a link to a product.  
   - The bot scans partner or public e-commerce APIs, searching for the same product at a cheaper price.  
   - Returns the findings with direct purchase links.

2. **Curated Shopping Lists**  
   - Pre-defined lists for various events (e.g., birthdays, Halloween, Mother’s Day).  
   - Offers curated suggestions, top sellers, or budget-friendly options.

3. **Product Discovery by Description**  
   - Users describe an item (e.g., “I’m looking for a red sweater under $50”).  
   - Bot returns relevant matches across multiple online stores.

4. **Potential Affiliate Integration**  
   - Some links may be affiliate-based, meaning the bot may earn a small commission at no extra cost to the user.

---

## How It Works

1. **User Sends a WhatsApp Message**  
   - Either a link to a product or a short description of what they want.

2. **Bot Processes the Input**  
   - Extracts product details from the link or interprets the user’s text.

3. **Deal-Finding Engine**  
   - The bot pings various e-commerce sites or APIs for pricing, availability, and relevant matches.

4. **Response**  
   - Bot constructs a response with the best deals, alternative sources, or curated lists.  
   - User sees a list of links or product details directly in WhatsApp.

---

## Technical Details

- **WhatsApp Cloud API**: Handles incoming and outgoing messages with users.  
- **Python + Flask**: Main server that processes webhooks, orchestrates the deal-finding logic, and returns results.  
- **Scheduling (Optional)**: Periodic tasks (e.g., daily deal highlights).  
- **E-commerce Data Sources**: Possible integration with known marketplaces’ APIs (Amazon, eBay, Shopify-based stores, or local e-commerce sites).

---

## Data Privacy & Compliance

- **User Messages**: Collected only to provide the requested service (finding deals, recommendations).  
- **Personal Information**: The bot may temporarily store phone numbers in order to respond, but does not store personal addresses or payment information.  
- **Usage Data**: High-level logs (e.g., request timestamps, product categories) may be stored to improve recommendations.  
- **No Unsolicited Marketing**: We do not spam users or sell personal information.  
- **Opt-Out**: Users can discontinue interaction at any time.  
- **Cookies & Tracking**: For website references, standard affiliate-tracking cookies may be used by the respective e-commerce sites — those are governed by each site’s privacy policy.  

For any in-depth questions, please contact us via the **Issues** tab or the email listed below.

---

## Business & Policy Compliance

- **Business Objective**: Provide a consumer-focused tool to compare and find cost savings on e-commerce products.  
- **Policies**: This bot respects Meta’s Business and Commerce Policies by offering legitimate consumer services and transparent affiliate practices.

---

## Roadmap

1. **More E-commerce Integrations**: Expand the deal-finding engine to support additional local and global online stores.  
2. **User Accounts**: Optional user profiles to customize product alerts (opt-in only).  
3. **Rich Media Support**: Handle images or screenshots of products, run visual search.  
4. **Language Support**: Provide multilingual capabilities for broader audience reach.  

---

## Contributing

We welcome feedback, feature requests, and bug reports through **GitHub Issues**. For substantial contributions:

1. Fork this repository.  
2. Create a feature branch.  
3. Submit a pull request.

---

## Contact

- **Email**: [etaymatzliah@gmail.com](mailto:etaymatzliah@gmail.com)  
- **Issue Tracker**: [GitHub Issues](../../issues)

---

### Disclaimer

- The bot’s prices and deals are subject to availability and may change at any time.  
- We do not guarantee that deals found are the absolute lowest but strive to provide accurate and current information.
- All brand names and trademarks mentioned are the property of their respective owners.  
