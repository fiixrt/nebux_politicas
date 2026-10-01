# Nebux Privacy Policy

*Last updated: October 2026*

Nebux is a multifunctional Discord bot designed to provide various features and utilities within Discord servers. We take the privacy of our users very seriously and want to ensure you understand how we handle your data.

---

## 1. Data We Collect

Nebux applies the principle of **data minimization**: we only collect what is strictly necessary for the bot to function. The data we store is:

- **Server ID (Guild ID):** To save each server's configuration (welcome messages, autorole, levels, verification, etc.).
- **User ID (User ID):** For the XP/level system, warns, and other per-server tracking features.
- **Channel ID (Channel ID):** To direct automatic messages to the correct channel (welcome, logs, etc.).
- **Role ID (Role ID):** For autorole configuration, verification, and automatic role systems.

**We do NOT collect or store:**
- User message content.
- Personally identifiable information (real name, email, address, etc.).
- Payment or financial data.
- Presence or voice activity data.

> **Note on the Snipe feature:** The `/mod snipe` command temporarily stores the last deleted message **in the bot's memory only** (RAM). This data is never written to any database and is permanently lost when the bot restarts. It is processed ephemerally and solely for the purpose of displaying it upon request.

---

## 2. How We Use the Data

Collected data is used **exclusively** to:

- Manage bot feature configuration on each server (welcome/goodbye messages, autorole, verification, levels, tickets, giveaways, etc.).
- Track XP and level progress for users on servers where the level system is active.
- Record moderation warnings (warns) per server.
- Improve the functionality and stability of the bot.

Data is **not used** for advertising, sale to third parties, training artificial intelligence models, or any purpose outside the direct operation of the bot.

---

## 3. Data Sharing

**Nebux does not share, sell, or transfer your data to any third party** under any circumstances. Data is stored exclusively in our private infrastructure and is not accessible by external parties.

---

## 4. Data Retention

Data is stored while the bot is active in the server or while the user has registered activity:

- **Server configuration data:** Retained while Nebux remains in the server. Upon removing the bot, data becomes inactive and can be deleted upon request.
- **User XP/level data:** Retained indefinitely to preserve user progress, or until the user or server administrator requests deletion.
- **Moderation warnings:** Retained indefinitely or until the server administrator deletes them manually.

---

## 5. Data Security

We are committed to protecting collected data through the following measures:

- Data is stored in **MongoDB Atlas** (managed cloud by MongoDB Inc.), which includes **encryption at rest by default (AES-256)** and **encryption in transit via TLS/SSL**.
- Database access is limited solely to the Nebux development team through protected credentials.
- No passwords or sensitive data of any kind are stored.
- MongoDB Atlas performs automatic backups and complies with SOC 2, ISO 27001, and ISO 27018 security standards.
- Periodic access reviews are conducted to prevent unauthorized connections.

---

## 6. User Rights

You have the following rights regarding your data:

- **Right of access:** You may request information about what data Nebux has linked to your user ID.
- **Right of erasure:** You may request the deletion of all your data at any time.
- **Right to object:** If you do not wish your data to be stored, you may request exclusion from the systems that require it.

### How to request data deletion

Contact the Nebux team through our **official Discord support server**: [Join here](https://discord.gg/c8zCBhrNm) and open a support ticket with your request. We will process your request within a maximum of **30 days**.

---

## 7. Discord Privileged Intents

To provide its features, Nebux uses the following **Privileged Gateway Intents** from Discord:

- **Server Members Intent:** Required to detect member join and leave events (welcome/goodbye messages, autorole, mass role assignment, verification, and the level system). No member information is stored beyond the User ID for features that specifically require it.
- **Message Content Intent:** Required to detect prefix commands and execute custom commands configured by server administrators. Message content is processed in real time and **is never stored** in any database.

---

## 8. Changes to this Privacy Policy

Any changes to this policy will be communicated through our Discord server ([Join here](https://discord.gg/c8zCBhrNm)). Continued use of the bot after changes are published implies acceptance of the updated policy.

---

## 9. Contact

If you have any questions or concerns about this privacy policy, you can contact us through our **official Discord support server**: [https://discord.gg/c8zCBhrNm](https://discord.gg/c8zCBhrNm)
