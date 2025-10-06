# Modern Discord Features and Server Structure for Adam’s InTheMoney Trading Community

## Overview of Adam’s Community

Adam (InTheMoney) runs a YouTube channel focused on trading futures and options with a data‑driven but humorous style. The community is primarily interested in options, stocks and crypto, and viewers enjoy learning about trading strategies while also appreciating Adam’s dry humor and casual attitude. A Discord server for this community should offer resources for learning, sharing trades, off‑topic camaraderie, and fun, while ensuring the space remains friendly and safe.

## Modern Discord Features Relevant to Trading Communities

### Onboarding, Server Guide and Welcome Screen

Community Onboarding (available in every community server) guides new members through a personalized survey that assigns them roles and shows them the channels relevant to their interests. Admins choose default channels that everyone initially sees, create customization questions, and link answers to channels or roles so new members can self‑assign access to specific categories (e.g., options, stocks, crypto)[1]. New members must complete onboarding before posting, and they can later adjust their answers via a Channels & Roles tab[2]. Best practices include selecting active and welcoming default channels (e.g., #general, forums, polls) and keeping questions concise[3]. After finishing onboarding, administrators can preview and publish the setup; at least seven default channels are required, five of which must allow @everyone to view and post[4].

Server Guide extends onboarding by providing a dedicated welcome page. It lets admins add a welcome sign message, list 3‑5 tasks for new members (e.g., read the rules, pick roles, post an introduction), and convert read‑only channels into Resource Pages that display content cleanly without avatars[5]. When enabled, Server Guide replaces the normal welcome screen and helps new members quickly understand the server’s purpose[6].

The Welcome Screen can still be used if Server Guide is disabled. It allows up to five recommended channels (general chat, rules, announcements) to be displayed to newcomers, helping them find important areas and increasing member retention[7].

### Verification, Rules & Membership Screening

Rules Screening requires new members to accept a list of up to 16 custom rules before they can chat or DM. Rules can cover etiquette, financial‑advice disclaimer, no spam or pump‑and‑dump schemes etc. Administrators configure the rules in Server Settings > Safety Setup and members must agree to them to gain access[8].

Verification Levels provide graduated security. Levels range from None to Highest. For example, the Medium level requires a verified email older than 5 minutes; High adds a 10‑minute server membership requirement; Highest requires phone verification[9]. Medium or High is recommended to deter spam bots.

Server Member Applications allow the server to be set to “Apply to Join.” Prospective members answer custom questions and moderators can approve, reject or conduct interviews before entry[10][11]. This is useful if the community wishes to vet members (e.g., verifying trading experience).

### Organization Tools

Forum Channels create boards where each post is its own topic and can include tags, guidelines and default reactions[12]. They keep discussions organized and searchable—ideal for separate forums on Options Strategies, Stock Picks, Crypto Chat or Trading Tools.

Threads let conversations branch off from a channel’s feed; they automatically archive after 24 hours and can be public or private[13]. Threads are useful for side discussions without cluttering the main chat.

Polls allow up to 10 answer options; admins set durations and decide whether users can choose multiple answers[14][15]. Polls are integrated with AutoMod and can collect community feedback (e.g., voting for the next AMA topic).

Text Chat in Voice Channels gives each voice channel its own chat window; participants can send links, charts or jokes without interrupting the voice conversation[16].

In‑Channel Conversation Summaries (experimental) group long conversations into topics with previews, making it easier to catch up[17][18].

### Live Events and Engagement

Stage Channels support voice, video and screensharing events with large audiences. They allow moderators to control speakers and enable the audience to request to speak. Stage channels power events such as AMAs, live trading sessions, podcasts, interviews and game nights[19][20]. Stage Discovery can make public events visible to other Discord users[21].

Community Events guidelines recommend setting a clear time/place, providing rules, opening appropriate chat/voice channels and having fun[22]. Use events like trivia nights, trading challenges or watch‑along of economic reports.

Activities and Games integrate interactive experiences like Watch Together, Poker Night, Chess or Gartic Phone. Users start them via the “Rocket Ship” button in a voice channel; everyone can join without needing to install anything[23]. These lighten the mood and foster camaraderie.

Soundboard lets users play short audio clips in voice channels; eight default slots are available, and more can be unlocked through server boosting. Custom sounds can be uploaded and are managed via permissions[24].

Go Live/Screen Share allows streaming an application or entire screen in a voice channel; up to 50 viewers can watch simultaneously[25]. Adam can use this feature to share charts during coaching sessions.

### Safety and Moderation

AutoMod automatically detects and blocks messages containing harmful or unwanted words; it can time‑out offenders and send alerts[26]. Configure custom keyword filters for pump‑and‑dump or scam phrases.

Activity Alerts & Security Actions notify moderators when the system detects suspicious join raids; moderators can temporarily pause invites and DMs[27][28]. This pairs well with Onboarding’s Raid Protection, which uses machine learning to detect mass join raids and can require CAPTCHA for new joiners[29].

Slowmode imposes a cooldown (5 seconds–2 minutes) in busy channels to reduce spam; moderators and people with manage‑channel permission are exempt[30].

Priority Speaker amplifies a user’s volume in voice channels, ensuring hosts or teachers are heard clearly during webinars[31][32].

Linked Roles require members to connect external accounts (e.g., Twitter, Steam or other apps) to obtain roles; admins can gate channels based on account age or verification, which helps ensure authenticity[33][34].

### Customization and Monetization

Server Boosting & New Perks – members can boost the server to unlock perks. In 2025 Discord introduced Enhanced Role Styles and Server Tags, each requiring 3 boosts[35]. Enhanced Role Styles let roles display animated gradient colors, while Server Tags allow members to display a short tag representing the server next to their name across Discord[35][36].

Per‑Server Profiles (for Nitro users) allow custom avatars and banners per server[37], enabling members to adopt trading‑themed profiles.

Server Shop & Subscriptions – servers can sell downloadables (digital guides, spreadsheets) and premium roles for one‑time purchases[38]. Server subscriptions enable monthly membership tiers with perks[39]. These features are optional but could monetize premium analysis or course material.

App Directory – admins can browse and add official and community‑made bots directly within Discord. The directory includes moderation bots, games, and finance apps such as Step for stock prices or Magoosh for study sessions[40][41]. This is the recommended place to find chart‑price bots or option flow bots for trade alerts.

Quests & Orbs – Discord’s 2025 Quests allow members to earn Orbs by completing tasks and redeem them for profile items or Nitro credits[42]. They can be optional engagement rewards.

## Proposed Server Structure for InTheMoney

The goal is to create a welcoming, organized and feature‑rich server that encourages discussion about trading while maintaining a casual, humorous vibe. Below is a suggested skeleton that leverages Discord’s modern tools.

### 1. Welcome & Onboarding

**#server-guide (Resource Page)** – Utilize Server Guide to display a welcome message from Adam, highlight the community’s mission, provide 3–5 New Member To‑Do’s (read rules, pick your interests, introduce yourself, check resources), and convert channels like #rules or #how-to-trade-options into clean resource pages[5].

**Rules Screening** – Create a #rules page and list up to 16 rules; cover respect, no financial advice, no solicitation or pump‑and‑dump, use correct channels, and respect market hours[8].

**Onboarding Questions** – Use community onboarding to ask: Which markets are you interested in? (Options, Stocks, Crypto, All), What’s your experience level? (Beginner, Intermediate, Advanced), Are you interested in off‑topic chat? (Yes, No). Link answers to roles that control access to categories like Options, Stocks or Crypto and off‑topic lounges[43]. Choose at least seven default channels (see below) to show initially[4].

**Verification & Screening** – Set the server verification level to Medium (requires verified email older than 5 minutes) or High for more protection[9]. Consider Apply to Join if you want to vet membership through custom questions (e.g., ask about trading goals)[10].

### 2. Information & Announcements

**Announcement Category**

- **#announcements (Announcement Channel)** – Post new YouTube video releases, podcast episodes, or important trading alerts. Use the Publish button to cross‑post announcements to other servers; avoid overusing @everyone to prevent follower fatigue[44].
- **#calendar-of-events** – Use event scheduling (or a calendar bot) to announce livestreams, AMAs, earnings report watch parties and community challenges.
- **#faq-and-guides (Resource Page)** – Consolidate common trading resources (options basics, risk management, recommended books) using Server Guide’s clean page layout[5].

### 3. Trading Floor

Create categories gated by roles chosen during onboarding. Each category should include:

**Live‑Trading Voice** – Voice channel with text chat enabled. Members can join to talk through trades or quietly watch; use Text Chat in Voice to share charts and links[16]. Enable Go Live for screen sharing during market open; limit watchers to 50 (per standard limit)[25].

**Options**

- **#options-discussion** – Primary chat for options; set slowmode if needed[30].
- **Options Forum** – Forum channel for strategies, trade journals or Q&A. Create tags like Spreads, Straddles, Earnings Plays[12].
- **#flow-alerts** – Integrate a bot from the App Directory (e.g., a reputable options flow app) to post unusual options activity. Use AutoMod to filter out spam or suspicious promotions[26].

**Stocks**

- **#stocks-discussion** and **Stocks Forum** – Similar to options. Use a price/quote bot (via App Directory) to respond to slash commands like `/price AAPL`. Consider a bot for earnings calendar or news headlines.

**Crypto (optional if allowed by regulation)**

- **#crypto-talk** – Channel for crypto discussions. Use AutoMod to filter pump‑and‑dump keywords. Consider gating via a warning that crypto is high risk.

**Analysis & Tools**

- **#charts-and-analysis** – Members share charts or trading view setups. Use a chart‑rendering bot from App Directory (e.g., Step’s stock price visualizer) to generate quick charts.
- **#macro-news** – Post macroeconomic updates; integrate a news feed bot. Encourage using threads for side conversations[13].

### 4. Community & Off‑Topic

- **General Chat** – A casual text channel for daily conversation, memes and jokes; sets the tone of the community. Use threads for long tangents. Enable slowmode to prevent spam during high traffic[30].
- **Off‑Topic Lounges** – Channels for discussing hobbies, music, gaming or fitness. Use Activities like Gartic Phone or Chess to encourage community bonding[23].
- **Voice Lounges** – One or two casual voice channels with Soundboard enabled for humor[24]. Consider separate voice channels for region/time zones or quiet/active rooms.
- **Forum Channel: #ask-me-anything** – Members can post AMA questions for Adam; he can reply when free or schedule Stage events.

### 5. Events & Engagement

- **Stage Channel: InTheMoney Live** – Host livestreams, Q&A, panel discussions and trading workshops. Use Stage features to manage speakers, allow audience requests, and optionally open events to the public via Stage Discovery[20]. Complement with an **#stage-chat** channel for questions and text chat.
- **Polls** – Create polls to decide future topics, challenge ideas, or community meet‑ups; polls support up to 10 answers and time limits[14].
- **Community Challenges** – Use forum posts or polls to propose monthly paper‑trading competitions (e.g., best risk‑adjusted return). Recognize winners with a special role or color via Enhanced Role Styles unlocked through boosting[35].
- **Quests & Orbs (Optional)** – Explore enabling Quests to let members earn Orbs by watching videos or completing tasks, redeemable for profile flair[42].

### 6. Moderation & Safety

- **Mod Team Structure** – Create roles like Admin, Moderator, Event Host, Bot Manager, and Trusted Member. Use Linked Roles to verify moderators via connected accounts[33].
- **AutoMod Rules** – Set up custom keyword filters to block pump‑and‑dump, spam, explicit language and scam links. Configure timeouts or automatic deletion[26].
- **Security Actions** – Enable raid protection alerts; if a join raid is detected, the system will send an alert and require CAPTCHA for new joiners[29]. Moderators can temporarily pause invites and DMs[27].
- **Member Reports & Appeals** – Create a private **#mod-mail** channel where users can report issues or appeal moderation actions.

### 7. Customization & Rewards

- **Enhanced Role Styles & Server Tags** – Once the community contributes enough boosts (3 each), enable these perks. Use Enhanced Role Styles to make moderator or veteran roles stand out with gradients, and give the server a short Server Tag (e.g., “ITM”) so members can rep the community across Discord[35][36].
- **Per‑Server Profiles** – Encourage Nitro members to customize their avatar/banner to match the trading theme[37].
- **Server Shop & Subscriptions (Optional)** – If Adam wants to monetize, create a Server Shop offering downloadable guides, spreadsheets or templates and premium roles granting access to in‑depth analysis channels[38]. Alternatively, set up Server Subscriptions for monthly tiers with perks like priority AMA access or small group coaching[39].

## Additional Tips for Fostering Community

- **Maintain a Casual yet Respectful Tone** – Encourage humor and memes to match Adam’s style, but enforce rules about respect and no harassment.
- **Encourage Collaboration** – Promote teamwork through trading challenges and collaborative spreadsheets. Use threads or forums to gather trade ideas and provide constructive feedback.
- **Educate and Empower** – Use resource channels and guides to teach options strategies, risk management and market psychology. Invite guest speakers via Stage channels.
- **Reward Contributions** – Recognize helpful members with special roles, custom colors or server tags. Use poll‑based awards or highlight posts in an **#hall-of-fame** channel.
- **Use Bots Wisely** – Explore the App Directory for reliable finance bots (price quotes, charts, alerts) and moderation bots. Avoid bots that require dangerous permissions or seem untrustworthy.
- **Iterate Based on Feedback** – Run periodic polls to adjust channels, rules and events. Use Discord’s built‑in tools (server insights) to monitor member retention and activity.

## Conclusion

Discord’s feature set has expanded beyond simple chat into a robust platform for organizing communities. By leveraging modern tools—like Onboarding, Forum Channels, Stage Channels, Polls, AutoMod, Activities, Boosting perks and Server Guide—Adam can build a dynamic, secure and fun home for his trading community. A well‑structured server with clear categories, onboarding questions and interactive events will invite newcomers, encourage engagement, and foster a thriving community around InTheMoney’s content.

---

[1] **Welcome Your New Members Easily with Community Onboarding**  
https://discord.com/blog/community-onboarding-welcome-your-new-members

[2] [3] [4] [29] [43] **Community Onboarding FAQ – Discord**  
https://support.discord.com/hc/en-us/articles/11074987197975-Community-Onboarding-FAQ

[5] [6] **Server Guide FAQ – Discord**  
https://support.discord.com/hc/en-us/articles/13497665141655-Server-Guide-FAQ

[7] **Community Server Welcome Screen – Discord**  
https://support.discord.com/hc/en-us/articles/360043913591-Community-Server-Welcome-Screen

[8] **Rules Screening FAQ – Discord**  
https://support.discord.com/hc/en-us/articles/1500000466882-Rules-Screening-FAQ

[9] **Verification Levels – Discord**  
https://support.discord.com/hc/en-us/articles/216679607-Verification-Levels

[10] [11] **Server Member Applications – Discord**  
https://support.discord.com/hc/en-us/articles/29729107418519-Server-Member-Applications

[12] **Forum Channels: A Space for Organized Conversations**  
https://discord.com/blog/forum-channels-space-for-organized-conversation

[13] **Connect the Conversation with Threads on Discord**  
https://discord.com/blog/connect-the-conversation-with-threads-on-discord

[14] [15] **Polls FAQ – Discord**  
https://support.discord.com/hc/en-us/articles/22163184112407-Polls-FAQ

[16] **Text Channels & Text Chat In Voice Channels – Discord**  
https://support.discord.com/hc/en-us/articles/4412085582359-Text-Channels-Text-Chat-In-Voice-Channels

[17] [18] **In-Channel Conversation Summaries – Discord**  
https://support.discord.com/hc/en-us/articles/12926016807575-In-Channel-Conversation-Summaries

[19] **Bring Your Community Together With Stages | Discord**  
https://discord.com/stages

[20] [21] **Ideas for how Stage Channels can Engage and Grow your Community**  
https://discord.com/blog/stage-channel-ideas-engage-and-grow-your-community

[22] **Planning Community Events**  
https://discord.com/community/planning-community-events

[23] **Discord Activities: Play Games and Watch Together**  
https://discord.com/blog/server-activities-games-voice-watch-together

[24] **Discord Soundboard Guide: Using, Adding, and Managing Sounds – Discord**  
https://support.discord.com/hc/en-us/articles/12612888127767-Discord-Soundboard-Guide-Using-Adding-and-Managing-Sounds

[25] **Go Live and Screen Share – Discord**  
https://support.discord.com/hc/en-us/articles/360040816151-Go-Live-and-Screen-Share

[26] **Meet Your Newest Community Moderator: AutoMod Is Here**  
https://discord.com/blog/automod-launch-automatic-community-moderation

[27] [28] **Activity Alerts + Security Actions – Discord**  
https://support.discord.com/hc/en-us/articles/17439993574167-Activity-Alerts-Security-Actions

[30] **Slowmode - Slllooowwwiiinng down your channel – Discord**  
https://support.discord.com/hc/en-us/articles/360016150952-Slowmode-Slllooowwwiiinng-down-your-channel

[31] [32] **Setting up Priority Speaker – Discord**  
https://support.discord.com/hc/en-us/articles/360011876531-Setting-up-Priority-Speaker

[33] [34] **Connections & Linked Roles: Admins – Discord**  
https://support.discord.com/hc/en-us/articles/10388356626711-Connections-Linked-Roles-Admins

[35] [36] **Get More From Your Boosts With New Server Perks**  
https://discord.com/blog/get-more-from-your-boosts-with-new-server-perks

[37] **Per-Server Profiles – Discord**  
https://support.discord.com/hc/en-us/articles/4409388345495-Per-Server-Profiles

[38] **Server Shop for Members – Discord**  
https://support.discord.com/hc/en-us/articles/17633135983383-Server-Shop-for-Members

[39] **Server Subscriptions for Members – Discord**  
https://support.discord.com/hc/en-us/articles/4415163187607-Server-Subscriptions-for-Members

[40] **Attention Server Owners: The App Directory is Here!**  
https://discord.com/blog/app-directory-is-here-mods-and-admins

[41] **A Beginner’s Guide to using Discord Apps**  
https://discord.com/blog/how-to-use-discord-apps

[42] **Reward Your Play: Complete Quests. Earn Orbs. Get Sweet Stuff.**  
https://discord.com/blog/discord-orbs

[44] **Announcement Channel FAQ – Discord**  
https://support.discord.com/hc/en-us/articles/360032008192-Announcement-Channel-FAQ
