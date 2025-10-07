# Proposed Role Hierarchy

| Role            | Description                                                           |
| --------------- | --------------------------------------------------------------------- |
| @Admin          | Owners/co-owners (full control)                                       |
| @Moderator      | Moderation staff                                                      |
| @Trusted        | Members with a good track record, gives access to #live-trading-voice |
| @Server Booster | Members who boost the server                                          |
| @Event Host     | Hosts for Stage/Events                                                |
| @Stage Speaker  | Pre-approved speakers                                                 |
| @Verified       | Completed onboarding & accepted rules                                 |
| @Bot            | Automations and feeds                                                 |
| @Options        | Interest role: options                                                |
| @Stocks         | Interest role: stocks                                                 |
| @Crypto         | Interest role: crypto                                                 |
| @Off-Topic      | Opt-in off-topic access                                               |
| @Historian      | Opt-in archive access (read only)                                     |
| @Muted          | No send permissions                                                   |
| @everyone       | Default channel permissions with limited visibility                   |
|                 |                                                                       |

# Proposed Role Permissions

| Property                                | @Admin/Owner | @Moderator | @Trusted | @Server Booster | @Event Host | @Stage Speaker | @Verified | @Bot | @Options/@Stocks/@Crypto/@Off-Topic/@Historian/@Muted/@everyone |
| --------------------------------------- | :----------: | :--------: | :------: | :-------------: | :---------: | :------------: | :-------: | :--: | :-------------------------------------------------------------: |
| <h3>Display</h3>                        |              |            |          |                 |             |                |           |      |                                                                 |
| Display members separately?             |      ❌      |     ✅     |    ✅    |       ✅        |     ✅      |       ❌       |    ❌     |  ✅  |                               ❌                                |
| Allow anyone to mention?                |      ❌      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| <h3>General Server Permissions</h3>     |              |            |          |                 |             |                |           |      |                                                                 |
| View Channels                           |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  ❌  |                               ❌                                |
| Manage Channels                         |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Manage Roles                            |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Create Expressions (emoji/stickers)     |      ✅      |     ✅     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Manage Expressions                      |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| View Audit Log                          |      ✅      |     ✅     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| View Server Insights                    |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| View Server Subscription Insights       |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Manage Webhooks                         |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Manage Server                           |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| <h3>Membership Permissions</h3>         |              |            |          |                 |             |                |           |      |                                                                 |
| Create Invite                           |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Change Nickname                         |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  −   |                               ❌                                |
| Manage Nicknames                        |      ✅      |     ✅     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Kick, Approve, and Reject Members       |      ✅      |     ✅     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Ban Members                             |      ✅      |     ✅     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Timeout Members                         |      ✅      |     ✅     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| <h3>Text Channel Permissions</h3>       |              |            |          |                 |             |                |           |      |                                                                 |
| Send Messages and Create Posts          |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  ❌  |                               ❌                                |
| Send Messages in Threads and Posts      |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  ❌  |                               ❌                                |
| Create Public Threads                   |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  ❌  |                               ❌                                |
| Create Private Threads                  |      ✅      |     ❌     |    ✅    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Embed Links                             |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  ❌  |                               ❌                                |
| Attach Files                            |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  ❌  |                               ❌                                |
| Add Reactions                           |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  ❌  |                               ❌                                |
| Use External Emoji                      |      ✅      |     ❌     |    ✅    |       ✅        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Use External Stickers                   |      ✅      |     ❌     |    ✅    |       ✅        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Mention @everyone, @here, and All Roles |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Manage Messages                         |      ✅      |     ✅     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Pin Messages                            |      ✅      |     ✅     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Manage Threads and Posts                |      ✅      |     ✅     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Read Message History                    |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  ❌  |                               ❌                                |
| Send Text-to-Speech Messages            |      ❌      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Send Voice Messages                     |      ❌      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Create Polls                            |      ✅      |     ❌     |    ✅    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| <h3>Voice Channel Permissions</h3>      |              |            |          |                 |             |                |           |      |                                                                 |
| Connect                                 |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  ❌  |                               ❌                                |
| Speak                                   |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  ❌  |                               ❌                                |
| Video                                   |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  ❌  |                               ❌                                |
| Use Soundboard                          |      ✅      |     ❌     |    ✅    |       ✅        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Use External Sounds                     |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Use Voice Activity                      |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  ❌  |                               ❌                                |
| Priority Speaker                        |      ✅      |     ❌     |    ❌    |       ❌        |     ✅      |       ✅       |    ❌     |  ❌  |                               ❌                                |
| Mute Members                            |      ✅      |     ✅     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Deafen Members                          |      ✅      |     ✅     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Move Members                            |      ✅      |     ✅     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Set Voice Channel Status                |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| <h3>Apps Permissions</h3>               |              |            |          |                 |             |                |           |      |                                                                 |
| Use Application Commands                |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  ❌  |                               ❌                                |
| Use Activities                          |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  ❌  |                               ❌                                |
| Use External Apps                       |      ❌      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| <h3>Stage Channel Permissions</h3>      |              |            |          |                 |             |                |           |      |                                                                 |
| Request to Speak                        |      ❌      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ✅     |  ❌  |                               ❌                                |
| <h3>Events Permissions</h3>             |              |            |          |                 |             |                |           |      |                                                                 |
| Create Events                           |      ✅      |     ❌     |    ❌    |       ❌        |     ✅      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| Manage Events                           |      ✅      |     ❌     |    ❌    |       ❌        |     ✅      |       ❌       |    ❌     |  ❌  |                               ❌                                |
| <h3>Advanced Permissions</h3>           |              |            |          |                 |             |                |           |      |                                                                 |
| Administrator                           |      ✅      |     ❌     |    ❌    |       ❌        |     ❌      |       ❌       |    ❌     |  ❌  |                               ❌                                |
|                                         |              |            |          |                 |             |                |           |      |                                                                 |
|                                         |              |            |          |                 |             |                |           |      |                                                                 |



## Recommended Role Strategy
Roles work in layers, by adding together all permissions from all roles a user has, then applies any channel-specific overrides on top. We shouldn't duplicate every base permission into higher roles; instead follow a layering approach
* @everyone does not grant any permissions, instead, specific default channels will override the role so new users see a handful of channels before onboarding
* Base role @Verified - This is the foundation. It should include only the essential permissions every member needs: view channels, send messages, join voice, etc. When a user passes onboarding and accepts the rules, they get this role.
* Gating roles (@Options, @Stocks, @Crypto, @Off-Topic, @Historian) - These do not add permissions; they simply control which categories or channels are visible. Leave their permission sets blank
* Reputation / perk roles (@Trusted) - Add only the *extra* perks this group should enjoy. Because they still have @Verified, they'll retain the base rights
* @Moderator and @Admin roles - Grant only the additional powers needed to moderate or manage the server (kicking/banning, managing messages, etc). They still retain all base member rights via @Verified
* Server Booster / Vanity roles - Keep these cosmetic; they don't need extra permissions unless you want to give boosters a small perk like Access to Activities