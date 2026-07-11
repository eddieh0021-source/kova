# Source: https://kovahub.app/privacypolicy

[← Back to Kova](https://kovahub.app/)

# Privacy Policy

Last updated: April 2, 2026

## 1\. Introduction

This Privacy Policy describes how Kova ("we," "us," or "our") collects, uses, stores, and protects your information when you use our computer-aided dispatch platform ("Service"). By using the Service, you consent to the data practices described in this policy.

## 2\. Information We Collect

We collect the following categories of information:

### 2.1 Information from Discord OAuth

- Discord user ID
- Username and display name
- Avatar URL
- Guild (server) memberships (when authorized)

### 2.2 Information from Roblox OAuth

- Roblox user ID
- Roblox username and display name
- Avatar thumbnail URL

### 2.3 Information Generated Through Use

- Server configurations and settings you create
- CAD session data (dispatch calls, unit assignments, status updates)
- Character and civilian records you create within the platform
- Communication data (radio transmissions, bodycam streams) processed during active sessions
- Session identifiers and authentication tokens

### 2.4 Automatically Collected Information

- IP address (used for rate limiting and security)
- Browser type and version
- Session cookies

## 3\. How We Use Your Information

We use your information for the following purposes:

- **Authentication:** To verify your identity and maintain your session.
- **Service Operation:** To provide core CAD functionality, including dispatch, unit management, and records management.
- **Server Management:** To associate you with the servers you own or are a member of, and to enforce role-based permissions.
- **Security:** To enforce rate limits, detect abuse, and protect the integrity of the Service.
- **Communication:** To facilitate in-platform communications such as radio and dispatch features.
- **Improvement:** To analyze usage patterns and improve the Service.

## 4\. Data Storage & Retention

Your data is stored using Supabase (a hosted PostgreSQL service) and in-memory caches during active sessions. Specifically:

- **Session data** is stored in our database and automatically expires after 7 days of inactivity.
- **Server configurations and user records** are retained as long as the associated server exists on the platform.
- **Temporary data** (radio audio, bodycam streams) is held in memory only during active sessions and is not permanently stored.
- **Account data** is deleted when you log out or when a server owner removes their server.

## 5\. Data Sharing & Disclosure

We do not sell, rent, or trade your personal information. We may share data in the following limited circumstances:

- **With server owners and members:** Your username, avatar, and in-session activity (e.g., unit status, dispatch actions) are visible to other members of the same server as part of normal Service operation.
- **Third-party integrations:** If a server owner configures webhook integrations (e.g., PRC webhooks, Discord webhooks), relevant session data may be transmitted to those endpoints. Server owners are responsible for their webhook configurations.
- **Legal requirements:** We may disclose information if required by law, regulation, legal process, or governmental request.
- **Safety:** We may disclose information to protect the rights, property, or safety of Kova, its users, or the public.

## 6\. Third-Party Services

The Service integrates with the following third-party platforms:

- **Discord** – for authentication and bot features. Subject to [Discord's Privacy Policy](https://discord.com/privacy).
- **Roblox** – for authentication and identity verification. Subject to [Roblox's Privacy Policy](https://en.help.roblox.com/hc/en-us/articles/115004630823).
- **Supabase** – for database hosting. Subject to [Supabase's Privacy Policy](https://supabase.com/privacy).

## 7\. Cookies

We use a session cookie (`connect.sid`) to maintain your authenticated session. This cookie is:

- HTTP-only (not accessible via JavaScript)
- Secure in production (transmitted only over HTTPS)
- Set to expire after 7 days

We do not use tracking cookies, advertising cookies, or analytics cookies.

## 8\. Data Security

We implement reasonable security measures to protect your information, including:

- HTTPS encryption for all data in transit
- HTTP-only, secure session cookies
- Rate limiting to prevent abuse
- HMAC signature verification for incoming webhooks
- Server-side only use of database service keys

However, no method of transmission over the Internet or electronic storage is 100% secure. We cannot guarantee absolute security.

## 9\. Your Rights

Depending on your jurisdiction, you may have the right to:

- **Access** the personal data we hold about you.
- **Correct** inaccurate personal data.
- **Delete** your personal data. You can do this by logging out (which removes your user data) or by contacting us.
- **Object** to processing of your personal data.
- **Data portability** – request a copy of your data in a structured format.

To exercise any of these rights, please contact us through the Kova Discord community.

## 10\. Children's Privacy

The Service is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13. If we become aware that we have inadvertently collected such information, we will take steps to delete it promptly.

## 11\. International Users

If you are accessing the Service from outside the country where our servers are located, please be aware that your information may be transferred to, stored, and processed in a different jurisdiction. By using the Service, you consent to the transfer of your information as described in this Privacy Policy.

## 12\. Changes to This Policy

We may update this Privacy Policy from time to time. We will notify users of material changes by updating the "Last updated" date at the top of this page. Your continued use of the Service after any changes constitutes acceptance of the updated policy.

## 13\. Contact

If you have any questions or concerns about this Privacy Policy, please contact us through the Kova Discord community or via the contact methods listed on the platform.