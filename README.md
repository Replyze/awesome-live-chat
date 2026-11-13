# Awesome Live Chat [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Live chat and customer support software: chat widgets for websites and apps, shared inboxes and help desks, and AI agents that answer customers.

This list is maintained by the Replyze team, and Replyze is one of the listed products. Entries are in alphabetical order, with no ranking, and each one meets the [inclusion criteria](CONTRIBUTING.md#criteria): a real, publicly available product or project that is actively maintained and in scope. Descriptions are one neutral, factual line taken from the product's own site, README or docs. There are no prices, because they change. Pull requests with additions and corrections are welcome, including from the companies listed.

## Contents

- [Open source and self-hosted](#open-source-and-self-hosted)
  - [Live chat and omnichannel inboxes](#live-chat-and-omnichannel-inboxes)
  - [Help desks and ticketing](#help-desks-and-ticketing)
  - [Comparison](#comparison)
- [Hosted live chat and help desks](#hosted-live-chat-and-help-desks)
- [AI support agents and chatbots](#ai-support-agents-and-chatbots)
- [Chat widgets and SDKs](#chat-widgets-and-sdks)
  - [Open-source chat UI components](#open-source-chat-ui-components)
  - [Vendor SDKs](#vendor-sdks)
- [WordPress live chat plugins](#wordpress-live-chat-plugins)
- [Developer resources](#developer-resources)
  - [APIs](#apis)
  - [MCP servers](#mcp-servers)
- [Alternatives](#alternatives)
  - [Intercom alternatives](#intercom-alternatives)
  - [Zendesk alternatives](#zendesk-alternatives)
  - [tawk.to alternatives](#tawkto-alternatives)
  - [Crisp alternatives](#crisp-alternatives)
  - [Tidio alternatives](#tidio-alternatives)
  - [Chatwoot alternatives](#chatwoot-alternatives)

## Open source and self-hosted

Software you can run on your own server. Licenses differ, and the comparison table at the end of this section shows each one.

### Live chat and omnichannel inboxes

- [Chatwoot](https://github.com/chatwoot/chatwoot) - Customer support platform with website live chat, email, WhatsApp and social channels, a help center and the Captain AI agent; self-hosted or cloud.
- [LibreDesk](https://github.com/abhinavxd/libredesk) - Support desk for email, live chat and WhatsApp with a help center and an AI assistant, distributed as a single binary.
- [Live Helper Chat](https://github.com/LiveHelperChat/livehelperchat) - Live support chat for websites with bots, voice and video calls, mobile apps and extensions for Telegram, Messenger and WhatsApp.
- [Rocket.Chat](https://github.com/RocketChat/Rocket.Chat) - Communications platform whose Omnichannel features add a website Livechat widget and apps for WhatsApp, SMS and Telegram.
- [Tiledesk](https://github.com/Tiledesk/tiledesk) - Live chat with a no-code chatbot and AI agent builder and hand-off to human agents, for web, WhatsApp, Messenger and Telegram.

### Help desks and ticketing

- [Frappe Helpdesk](https://github.com/frappe/helpdesk) - Ticketing system that turns support email into tickets, with a customer portal, SLAs, assignment rules and a knowledge base.
- [FreeScout](https://github.com/freescout-help-desk/freescout) - Help desk and shared mailbox built with Laravel, extended through modules for WhatsApp, Telegram, Facebook and live chat.
- [osTicket](https://github.com/osTicket/osTicket) - Ticket system that collects requests from email, phone and web forms in one web interface.
- [UVdesk](https://github.com/uvdesk/community-skeleton) - Help desk built on Symfony with email piping, a support portal, a knowledge base and workflows.
- [Zammad](https://github.com/zammad/zammad) - Help desk for email, web forms, chat, SMS, Telegram, WhatsApp and Facebook, owned by the independent Zammad Foundation.

### Comparison

Checked on 2026-11-13 against each project's repository, README and documentation. Stars are rounded. A dash means no official mobile app was listed there.

| Project          | License                     | Language         | Self-hosting                                | Mobile apps  | Channels                                                                          | Stars |
| ---------------- | --------------------------- | ---------------- | ------------------------------------------- | ------------ | --------------------------------------------------------------------------------- | ----- |
| Chatwoot         | MIT, `enterprise/` separate | Ruby             | Docker, Kubernetes, Heroku                  | iOS, Android | Web chat, email, WhatsApp, Facebook, Instagram, Telegram, Line, SMS               | 39.7k |
| LibreDesk        | AGPL-3.0                    | Go               | Docker, single binary                       | —            | Web chat, email, WhatsApp                                                         | 3.1k  |
| Live Helper Chat | Apache-2.0                  | PHP              | PHP package, Docker                         | iOS, Android | Web chat; Telegram, Viber, Messenger, Instagram, WhatsApp, SMS through extensions | 2.3k  |
| Rocket.Chat      | MIT, `ee/` separate         | TypeScript       | Docker, Podman, Kubernetes                  | iOS, Android | Web chat, email; WhatsApp, SMS, Telegram through apps                             | 46.5k |
| Tiledesk         | MIT                         | Node.js, Angular | Docker Compose, Kubernetes                  | iOS, Android | Web chat, WhatsApp, Messenger, Telegram                                           | 330   |
| Frappe Helpdesk  | AGPL-3.0                    | Python, Vue      | Docker, install script                      | —            | Email, customer portal                                                            | 3.5k  |
| FreeScout        | AGPL-3.0                    | PHP              | Docker, one-click installers, Ubuntu script | PWA          | Email; WhatsApp, Telegram, Facebook, live chat through modules                    | 4.7k  |
| osTicket         | GPL-2.0                     | PHP              | PHP and MySQL                               | —            | Email, web forms, phone                                                           | 4.0k  |
| UVdesk           | OSL-3.0                     | PHP              | Docker, Composer                            | —            | Email, support portal                                                             | 19.6k |
| Zammad           | AGPL-3.0                    | Ruby             | Docker, Kubernetes, DEB/RPM packages        | —            | Email, web form, chat, SMS, Telegram, WhatsApp, Facebook                          | 6.1k  |

## Hosted live chat and help desks

Software as a service: the vendor runs it for you.

- [Chatra](https://chatra.com/) - Multichannel support platform with live chat, chatbots, email and social messaging.
- [Comm100](https://www.comm100.com/) - Omnichannel customer service platform with live chat and AI automation.
- [Crisp](https://crisp.chat/en/) - Multichannel messaging platform with a website chat widget, a shared inbox and an AI agent.
- [Freshchat](https://www.freshworks.com/live-chat-software/) - Omnichannel messaging with live chat, chatbots and the Freddy AI agent, from Freshworks.
- [Freshdesk](https://www.freshworks.com/freshdesk/) - Help desk with omnichannel ticketing, automated workflows and AI features, from Freshworks.
- [Front](https://front.com/) - Customer service platform where support, sales and operations teams work on customer conversations together with AI agents.
- [Gleap](https://www.gleap.ai/) - AI customer service for chat, email, WhatsApp and phone, with in-app bug reporting and surveys.
- [Gorgias](https://www.gorgias.com/) - Help desk, chat and AI agent for ecommerce stores, with integrations for Shopify and BigCommerce.
- [HappyFox](https://www.happyfox.com/) - Help desk with ticketing, SLAs, a knowledge base, reporting and AI assistance.
- [Help Scout](https://www.helpscout.com/) - Support platform with shared inboxes, live chat, a knowledge base and AI features.
- [HelpCrunch](https://helpcrunch.com/) - Customer communication platform with live chat, a chatbot, a knowledge base, popups and email marketing.
- [Hiver](https://hiverhq.com/) - Customer service platform where teams and AI work on customer issues across channels.
- [HubSpot Service Hub](https://www.hubspot.com/products/service) - Customer service software with a help desk, live chat and AI, connected to the HubSpot CRM.
- [Intercom](https://www.intercom.com/) - Help desk for human and AI customer service, with the Fin AI agent built in.
- [JivoChat](https://www.jivochat.com/) - Live chat for websites that brings chat and social networks into one app.
- [Kustomer](https://www.kustomer.com/) - Customer service platform and CRM that unifies conversations and automates workflows.
- [Lime Connect](https://connect.lime-technologies.com/en/) - Chat, messaging and AI for support and sales, formerly called Userlike.
- [LiveAgent](https://www.liveagent.com/) - Help desk with email, live chat, phone and social media in one inbox, plus AI agents.
- [LiveChat](https://www.livechat.com/) - Live chat for websites with an AI agent and sales tracking from chats.
- [Olark](https://www.olark.com/) - Website chat with an AI agent that answers and qualifies visitors and brings in a person when needed.
- [Plain](https://www.plain.com/) - AI support platform for B2B teams that can be configured with no code or with code.
- [Pylon](https://www.usepylon.com/) - B2B support platform where people and AI agents work on customer issues together.
- [Re:amaze](https://www.reamaze.com/) - Customer service and AI agent platform for online businesses, with chat, social, SMS, FAQ and email.
- [Replyze](https://replyze.chat/?utm_source=github&utm_medium=referral&utm_campaign=awesome-live-chat) - AI agent that answers from your knowledge base, a website chat widget, and one shared inbox for web chat, email, WhatsApp and Telegram.
- [Respond.io](https://respond.io/) - Conversation platform that brings WhatsApp, TikTok, Instagram and Facebook into a team inbox with AI agents.
- [Smartsupp](https://www.smartsupp.com/) - Live chat, chatbots and AI tools for online stores.
- [tawk.to](https://www.tawk.to/) - Free live chat with ticketing, a knowledge base and a CRM in one inbox for customer channels.
- [Tidio](https://www.tidio.com/) - Customer service platform with live chat and the Lyro AI agent.
- [Trengo](https://trengo.com/) - Omnichannel customer engagement platform with a shared dashboard and AI automation.
- [Zendesk](https://www.zendesk.com/) - Customer service platform with ticketing, messaging, live chat and AI agents.
- [Zoho Desk](https://www.zoho.com/desk/) - Help desk platform built for support teams and AI to work together.
- [Zoho SalesIQ](https://www.zoho.com/salesiq/) - Customer engagement platform for websites with live chat, chatbots and visitor tracking.

## AI support agents and chatbots

AI agents that answer customers, and tools to build them.

- [Ada](https://www.ada.cx/) - AI customer service agents for enterprise support teams.
- [Botpress](https://botpress.com/) - Platform for building AI agents for customer support.
- [Chatbase](https://www.chatbase.co/) - AI agents for customer service, sales and product guidance across channels.
- [Chatwoot Captain](https://www.chatwoot.com/captain) - AI agent and copilot in Chatwoot that answers from your help center, drafts replies and hands off to your team.
- [Decagon](https://decagon.ai/) - Platform to build, improve and scale customer-facing AI agents.
- [DocsGPT](https://github.com/arc53/DocsGPT) - Open-source (MIT) AI assistant that answers from your documents, with a website chat widget and a Chatwoot integration.
- [Fin](https://fin.ai/) - AI customer agent from Intercom.
- [Forethought](https://forethought.ai/) - AI agents that resolve customer issues for support teams.
- [Gorgias AI Agent](https://www.gorgias.com/ai-agent) - AI agent for ecommerce support and sales, built on Gorgias.
- [HubSpot AI Customer Agent](https://www.hubspot.com/products/artificial-intelligence/ai-customer-service-agent) - AI agent in HubSpot that handles routine questions and hands off to your team with context.
- [Lyro](https://www.tidio.com/ai-agent/) - AI agent from Tidio that answers customer questions from your support content.
- [Replyze](https://replyze.chat/features?utm_source=github&utm_medium=referral&utm_campaign=awesome-live-chat) - AI agent that answers from your own help articles and hands the conversation to your team when needed.
- [Sierra](https://sierra.ai/) - Conversational AI agents that businesses use for customer experience.
- [Typebot](https://github.com/baptisteArno/typebot.io) - Visual chatbot builder you can self-host, with embeds for websites and WhatsApp, under a Fair Source license.
- [Voiceflow](https://www.voiceflow.com/) - Platform to build chat and voice AI agents for customer support.
- [Zendesk AI agents](https://www.zendesk.com/service/ai/ai-agents/) - AI agents in Zendesk that resolve requests and automate workflows across connected systems.

## Chat widgets and SDKs

Components and SDKs that put a chat window in your website or app.

### Open-source chat UI components

- [assistant-ui](https://github.com/assistant-ui/assistant-ui) - TypeScript and React library for building AI chat interfaces.
- [Deep Chat](https://github.com/OvidijusParsiunas/deep-chat) - Customizable AI chat web component that connects to popular AI APIs or your own server.
- [LiveChat Chat Widget Adapters](https://github.com/livechat/chat-widget-adapters) - React, Vue and Angular packages for the LiveChat chat widget.

### Vendor SDKs

- [Chatwoot Flutter SDK](https://github.com/chatwoot/chatwoot-flutter-sdk) - Client SDK that adds Chatwoot conversations to Flutter apps on Android and iOS.
- [Crisp chatbox SDKs](https://docs.crisp.chat/guides/chatbox-sdks/) - Web, iOS, Android and React Native SDKs for the Crisp chatbox.
- [HubSpot mobile chat SDK](https://github.com/HubSpot/mobile-chat-sdk-android) - Android SDK for HubSpot chat, bots and push notifications in mobile apps, with a matching iOS SDK.
- [Intercom SDKs](https://developers.intercom.com/installing-intercom) - Install guides for Intercom on web, iOS, Android, React Native and Cordova.
- [Zendesk Web Widget and SDKs](https://developer.zendesk.com/documentation/zendesk-web-widget-sdks/) - Zendesk messaging for websites and for Android, iOS and Unity apps.

## WordPress live chat plugins

- [3CX Live Chat](https://wordpress.org/plugins/wp-live-chat-support/) - Website live chat, calls and messaging from 3CX.
- [Chatra](https://wordpress.org/plugins/chatra-live-chat/) - Live chat, chatbot and cart saver for WordPress and WooCommerce.
- [Crisp](https://wordpress.org/plugins/crisp/) - Adds the Crisp live chat and AI chatbot to a WordPress site.
- [Gleap](https://wordpress.org/plugins/gleap/) - AI support chat, help center, bug reports and surveys, with order lookups for WooCommerce.
- [HubSpot](https://wordpress.org/plugins/leadin/) - CRM, forms, popups and live chat from HubSpot.
- [LiveChat](https://wordpress.org/plugins/wp-live-chat-software-for-wordpress/) - Adds the LiveChat widget to a WordPress site.
- [Smartsupp](https://wordpress.org/plugins/smartsupp-live-chat/) - Live chat, AI tools and chatbots for online stores on WordPress.
- [tawk.to](https://wordpress.org/plugins/tawkto-live-chat/) - Official plugin for the free tawk.to chat widget.
- [Tidio](https://wordpress.org/plugins/tidio-live-chat/) - Live chat and AI chatbots for WordPress sites.
- [Zoho SalesIQ](https://wordpress.org/plugins/zoho-salesiq/) - Live chat, chatbots and visitor tracking for WordPress sites.

## Developer resources

### APIs

- [Chatwoot developer docs](https://developers.chatwoot.com/introduction) - Installation, configuration and API documentation for Chatwoot.
- [Crisp REST API](https://docs.crisp.chat/references/rest-api/v1/) - Reference for version 1 of the Crisp REST API.
- [Freshdesk API](https://developers.freshdesk.com/api/) - REST API reference for Freshdesk tickets, contacts and other resources.
- [Front Core API](https://dev.frontapp.com/reference/introduction) - Backend API for everything in Front, from contacts to comments.
- [Help Scout API](https://developer.helpscout.com/) - Developer documentation for the Help Scout APIs.
- [Intercom API](https://developers.intercom.com/docs/references/introduction) - REST API reference for Intercom.
- [Replyze API](https://github.com/Replyze/replyze) - Widget embed code, JavaScript API, REST API, webhooks and an OpenAPI 3.1 spec for Replyze.
- [Rocket.Chat API](https://developer.rocket.chat/apidocs) - API reference for Rocket.Chat.
- [tawk.to JavaScript API](https://developer.tawk.to/jsapi/) - JavaScript API for controlling the tawk.to widget on a page.
- [Text Platform](https://platform.text.com/docs/) - Developer docs and APIs for LiveChat and the other Text products.
- [Zammad REST API](https://docs.zammad.org/en/latest/api/intro.html) - REST API documentation for Zammad.
- [Zendesk API reference](https://developer.zendesk.com/api-reference/) - API reference for Zendesk products.

### MCP servers

Model Context Protocol (MCP) servers let AI assistants such as Claude, ChatGPT or Cursor work with a support tool.

- [Crisp MCP server](https://docs.crisp.chat/guides/mcp-server/) - Lets an AI agent read data from a Crisp workspace and perform actions in it.
- [Freshdesk MCP server](https://support.freshdesk.com/support/solutions/articles/50000012670) - Connects AI tools such as Cursor and Claude to Freshdesk.
- [Front MCP server](https://dev.frontapp.com/docs/mcp-server) - Remote server at `mcp.frontapp.com/mcp` that lets AI agents act on Front conversations as a signed-in user.
- [HubSpot MCP server](https://developers.hubspot.com/ai-tools/mcp) - Connects AI tools to HubSpot CRM data.
- [Intercom MCP server](https://developers.intercom.com/docs/guides/mcp) - Remote server hosted by Intercom that gives AI tools authenticated access to Intercom data.
- [Live Helper Chat MCP](https://doc.livehelperchat.com/docs/mcp-setup) - Exposes the Live Helper Chat back office to MCP clients such as ChatGPT and Claude.
- [Replyze MCP server](https://github.com/Replyze/replyze-mcp) - Remote server for reading and answering conversations, adding notes, assigning chats and searching the knowledge base.

## Alternatives

Pointers for common searches. Every product named here has an entry above. "Free plan" means the vendor's pricing page listed a free plan on 2026-11-13. Plans change, so check before you decide.

### Intercom alternatives

Intercom combines a help desk, a messenger and the Fin AI agent. The main differences between the alternatives are whether you can self-host, whether there is a free plan, and whether the AI agent is part of the inbox or a separate product.

- Open source and self-hostable: Chatwoot, LibreDesk, Live Helper Chat, Rocket.Chat, Tiledesk.
- Hosted, with a free plan: Chatwoot, Crisp, Freshchat, Help Scout, HubSpot Service Hub, Tidio.
- Hosted, with an AI agent in the inbox: Crisp, Front, Gleap, Help Scout, Replyze, Tidio, Zendesk.
- Separate AI agent platforms: Ada, Botpress, Chatbase, Decagon, Forethought, Sierra, Voiceflow.

### Zendesk alternatives

Zendesk is built around tickets, with email, messaging, SLAs and a knowledge base. Look at ticketing depth, whether you can self-host, and which channels reach the ticket queue.

- Open source and self-hostable help desks: Frappe Helpdesk, FreeScout, osTicket, UVdesk, Zammad.
- Hosted help desks: Freshdesk, Front, HappyFox, Help Scout, Hiver, Kustomer, LiveAgent, Zoho Desk.
- Hosted, with a free plan: Help Scout, HubSpot Service Hub.

### tawk.to alternatives

tawk.to is free live chat with ticketing, a knowledge base and a CRM. Alternatives either also have a free plan or can be self-hosted.

- Hosted, with a free plan: Chatwoot, Crisp, Freshchat, HubSpot Service Hub, JivoChat, Smartsupp, Tidio, Zoho SalesIQ.
- Open source and self-hostable: Chatwoot, LibreDesk, Live Helper Chat, Rocket.Chat, Tiledesk.

### Crisp alternatives

Crisp is a multichannel inbox with a website chat widget and an AI agent. Compare the channels each product connects, how the shared inbox works, and whether there is a free plan.

- Hosted chat and messaging platforms: HelpCrunch, Intercom, LiveChat, Re:amaze, Replyze, Respond.io, Trengo.
- Hosted, with a free plan: Chatwoot, Freshchat, HubSpot Service Hub, JivoChat, Smartsupp, tawk.to, Tidio, Zoho SalesIQ.
- Open source and self-hostable: Chatwoot, LibreDesk, Tiledesk.

### Tidio alternatives

Tidio pairs live chat with the Lyro AI agent and is often used by online stores. Check whether the AI answers from your own content, which ecommerce integrations exist, and whether there is a free plan.

- Live chat with an AI agent: Crisp, Gorgias, Intercom, LiveChat, Olark, Replyze, Smartsupp.
- Built for ecommerce: Gorgias, Re:amaze, Smartsupp.
- Hosted, with a free plan: Crisp, HubSpot Service Hub, JivoChat, Smartsupp, tawk.to, Zoho SalesIQ.
- Self-hostable: Chatwoot, Tiledesk, Typebot (chatbot builder, Fair Source license).

### Chatwoot alternatives

Chatwoot is an open-source omnichannel inbox (MIT core) that you can self-host or use as a cloud service. Compare the license, the tech stack you would run, and which channels are built in rather than added.

- Self-hostable live chat and inboxes: LibreDesk (Go, single binary), Live Helper Chat (PHP), Rocket.Chat (TypeScript), Tiledesk (Node.js).
- Self-hostable help desks with chat or messaging channels: FreeScout, Zammad.
- Hosted: Crisp, Front, Help Scout, Intercom, Trengo, Zendesk.

## Related Lists

- [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted#readme) - Self-hosted software, with sections for ticketing and custom communication systems.
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers#readme) - MCP servers for many kinds of tools and services.

## Contributing

Additions and corrections are welcome. Read the [contribution guidelines](CONTRIBUTING.md) first.

## Footnotes

Facts, links and free-plan notes were checked on 2026-11-13. Projects that were considered but are archived, inactive or discontinued are listed in [inactive.md](inactive.md), with the reason.
