# Privacy Policy for Synqy Bot

Last Updated: February 27, 2025

Synqy ("we," "our," or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and protect your data when you interact with Synqy, a Discord bot designed for product purchases, queue management, and community interactions within Discord servers. By using Synqy, you agree to the practices described in this policy.

## 1. Data We Collect
Synqy operates within the Discord platform and relies on data provided by Discord for functionality. We do not collect personal data directly from users unless explicitly provided via Discord interactions. The data we process includes:

- **Discord-Provided Data**:
  - **User IDs**: Unique identifiers for Discord users interacting with the Bot (e.g., for tabs, purchases, queue management).
  - **Guild IDs**: Unique identifiers for Discord servers where Synqy is invited, used to manage guild-specific products, configs, and queues.
  - **Messages**: Content of messages (e.g., commands like `/buy`, `/tabs`) processed to execute Bot actions, stored temporarily for functionality and deleted after processing unless required for persistence.
  - **Role/Permission Data**: Discord role and permission information to enforce admin-only commands (e.g., `/load-data`).

- **User-Provided Data**:
  - **Product Data**: Product names and prices uploaded via `/load-data` (e.g., from CSV files), stored in our database for guild-specific use.
  - **Tab/Queue Data**: Purchase totals, queue items, and user interactions (e.g., quantities, product IDs) stored in our database for guild-specific functionality.

We do not collect personally identifiable information (PII) like email addresses, real names, or payment details unless you voluntarily provide them via Discord (e.g., in messages), and we do not store or process such data beyond what Discord provides.

## 2. How We Use Your Data
We use the data collected to:
- Operate Synqy’s core functions (e.g., product purchases, queue management, tab tracking).
- Enforce guild-specific configurations (e.g., shipping limits, timers).
- Provide admin tools (e.g., `/load-data`, `/remove-product`).
- Debug and improve the Bot, logging errors and usage (e.g., command invocations, errors in `log.txt`).

We do not sell, trade, or share your data with third parties, except as required by law or to comply with Discord’s policies.

## 3. Data Storage and Security
- **Storage**: Data is stored in a PostgreSQL database hosted on a local private cloud. Guild-specific data (products, tabs, queues) is linked to guild IDs, not individual users, and is accessible only within Discord servers where Synqy is invited.
- **Retention**: Data is retained as long as necessary for functionality or as required by server admins. You can remove Synqy from a server to delete associated data, or admins can use commands (e.g., `/remove-product`) to clear specific data.
- **Security**: We implement reasonable security measures (e.g., encryption for database connections, secure token storage in `.env`) to protect your data. However, no method is 100% secure—use at your own risk.

## 4. Data Sharing
- We do not share your data with third parties except:
  - With Discord, as required for Bot operation (e.g., sending messages, managing channels).
  - As required by law, legal process, or to protect our rights, property, or safety.
- Guild admins can access guild-specific data (e.g., products, queues) within their Discord server.

## 5. Your Rights
- **Access and Deletion**: You can request access to or deletion of guild-specific data by contacting us (see below) or removing Synqy from your server. Individual user data (e.g., tabs, queues) is tied to Discord IDs and managed by guild admins.
- **Opt-Out**: You can stop using Synqy or remove it from your server at any time via Discord settings.

## 6. International Data Transfers
If hosted on a cloud provider in addition to the local private cloud, data may be transferred internationally. We comply with applicable data protection laws, including U.S. federal laws and West Virginia state laws, and ensure data security during transfers.

## 7. Children’s Privacy
Synqy is not intended for children under 13. If you believe a child under 13 has provided data, contact us to request removal.

## 8. Changes to This Policy
We may update this Privacy Policy periodically. Notices of changes will be posted in the Bot’s documentation or Discord servers where it operates. Continued use after updates constitutes acceptance.

## 9. Contact Us
For questions, concerns, or data requests, contact synqysell@gmail.com.