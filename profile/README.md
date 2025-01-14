# Streamz

# Status    
| Status | Description |
|--------|-------------|
| ✅ | Done |
| 🚧 | In Progress |
| ❌ | Not Started |
| ⚫ | Not Applicable |


## Account creation and Management
| Feature | Operations | Public API | Private API | Admin API | Internal | Comments |
|---------|------------|------------|-------------|------------|----------|-----------|
| Account management | Create account | ⚫ | ⚫ | ⚫ | ✅ | Managed by Ory - using a webhook |
| | Fetch by user_identifier | ✅ | ✅ | ✅ | ✅ | works with username or user_id |
| | Fetch by channel_identifier | ✅ | ✅ | ✅ | ✅ | works with slug or channel_id |
| | Change password | ⚫ | ⚫ | ⚫ | ❌ | Handled Frontend side - using a webhook |
| | Change email | ⚫ | ⚫ | ⚫ | ❌ | Handled Frontend side - using a webhook |

## User management
| Feature | Operations | Public API | Private API | Admin API | Internal | Comments |
|---------|------------|------------|-------------|------------|----------|-----------|
| Notifications preferences | Fetch account settings | ⚫ | ✅ | ⚫ | ✅ | |
| | Update account settings | ⚫ | ✅ | ⚫ | ✅ | |
| | Fetch settings for specific channel | ⚫ | ✅ | ⚫ | ✅ | |
| | Update settings for specific channel | ⚫ | ✅ | ⚫ | ✅ | |
| Followed channels | Follow channel | ⚫ | ✅ | ⚫ | ✅ | |
| | Unfollow channel | ⚫ | ✅ | ⚫ | ✅ | |
| | Fetch followed channels | ⚫ | ✅ | ⚫ | ✅ | |
| | Check if following channel | ⚫ | ✅ | ⚫ | ✅ | |
| Followed categories | Follow category | ⚫ | ✅ | ⚫ | ✅ | |
| | Unfollow category | ⚫ | ✅ | ⚫ | ✅ | |
| | Fetch followed categories | ⚫ | ✅ | ⚫ | ✅ | |
| | Check if following category | ⚫ | ✅ | ⚫ | ✅ | |

## Channel management
| Feature | Operations | Public API | Private API | Admin API | Internal | Comments |
|---------|------------|------------|-------------|------------|----------|-----------|
| Panels | Create new panel | ✅ | ✅ | ✅ | ✅ | |
| | Fetch panels for channel | ✅ | ✅ | ✅ | ✅ | |
| | Update panel | ⚫ | ✅ | ✅ | ✅ | |
| | Update panel order | ⚫ | ✅ | ✅ | ✅ | |
| | Delete panel | ⚫ | ✅ | ✅ | ✅ | |
| Social links | Create new social link | ✅ | ✅ | ✅ | ✅ | |
| | Fetch social links for channel | ✅ | ✅ | ✅ | ✅ | |
| | Update social link | ⚫ | ✅ | ✅ | ✅ | |
| | Update social link order | ⚫ | ✅ | ✅ | ✅ | |
| | Delete social link | ⚫ | ✅ | ✅ | ✅ | |
| Subscribers badges | Create new subscribers badge | ✅ | ✅ | ✅ | ✅ | |
| | Fetch subscribers badges for channel | ✅ | ✅ | ✅ | ✅ | |
| | Delete subscribers badge | ⚫ | ✅ | ✅ | ✅ | |
| VIPs | Create new VIP | ✅ | ✅ | ✅ | ✅ | |
| | Fetch VIPs for channel | ✅ | ✅ | ✅ | ✅ | |
| | Delete VIP | ⚫ | ✅ | ✅ | ✅ | |
| OGs | Create new OG | ✅ | ✅ | ✅ | ✅ | |
| | Fetch OGs for channel | ✅ | ✅ | ✅ | ✅ | |
| | Delete OG | ⚫ | ✅ | ✅ | ✅ | |
| Moderators | Create new moderator | ✅ | ✅ | ✅ | ✅ | |
| | Fetch moderators for channel | ✅ | ✅ | ✅ | ✅ | |
| | Delete moderator | ⚫ | ✅ | ✅ | ✅ | |

## Chatroom management
| Feature | Operations | Public API | Private API | Admin API | Internal | Comments |
|---------|------------|------------|-------------|------------|----------|-----------|
| Chatroom | Fetch by channel identifier | ✅ | ✅ | ✅ | ✅ | works with slug or channel_id |
| | Fetch by chatroom id | ✅ | ✅ | ✅ | ✅ | works with chatroom_id |
| Settings | Fetch for chatroom | ✅ | ✅ | ✅ | ✅ | Settings include chat mode, accounts requirements... |
| | Update for chatroom | ⚫ | ✅ | ✅ | ✅ | |
| Blocked terms | Create new blocked term | ✅ | ✅ | ✅ | ✅ | |
| | Fetch for chatroom | ✅ | ✅ | ✅ | ✅ | |
| | Delete blocked term | ⚫ | ✅ | ✅ | ✅ | |
| Emotes | Create new emote | ✅ | ✅ | ✅ | ✅ | |
| | Fetch for chatroom | ✅ | ✅ | ✅ | ✅ | |
| | Delete emote | ⚫ | ✅ | ✅ | ✅ | |
| Rules | Update for chatroom | ⚫ | ✅ | ✅ | ✅ | |
| | Fetch for chatroom | ✅ | ✅ | ✅ | ✅ | |
| | Clear for chatroom | ⚫ | ✅ | ✅ | ✅ | |
| User Identity | Fetch computed identity | ✅ | ✅ | ✅ | ✅ | |
| | Update computed identity | ⚫ | ✅ | ✅ | ✅ | |
| Banned users | Ban user | ✅ | ✅ | ✅ | ✅ | |
| | Unban user | ⚫ | ✅ | ✅ | ✅ | |
| | Fetch for chatroom | ✅ | ✅ | ✅ | ✅ | |

## Chat messages management
| Feature | Operations | Public API | Private API | Admin API | Internal | Comments |
|---------|------------|------------|-------------|------------|----------|-----------|
| Messages | Send new chat message | ✅ | ✅ | ⚫ | ✅ | |
| | Delete chat message | ✅ | ✅ | ⚫ | ✅ | |
| | Fetch for chatroom | ✅ | ✅ | ⚫ | ✅ | |
| | Fetch for user | ✅ | ✅ | ⚫ | ✅ | |
| | Fetch for user in chatroom | ✅ | ✅ | ⚫ | ✅ | |
| | Fetch messages in a thread | ✅ | ✅ | ⚫ | ✅ | |

## Livestream management
| Feature | Operations | Public API | Private API | Admin API | Internal | Comments |
|---------|------------|------------|-------------|------------|----------|-----------|
| Livestream | Fetch information | ⚫ | ✅ | ⚫ | ✅ | |
| | Update information | ⚫ | ✅ | ⚫ | ✅ | |
| Livestreams | Fetch for directory | ✅ | ✅ | ⚫ | ✅ | should include filters|
| | Fetch for category | ✅ | ✅ | ⚫ | ✅ | should include filters |
| | Fetch for channel | ✅ | ✅ | ⚫ | ✅ | |
| | Fetch recommended livestreams | ✅ | ✅ | ⚫ | ✅ | should include filters |
| | Fetch livestreams for followed channels | ✅ | ✅ | ⚫ | ✅ | should include filters |
| VODs | Fetch VODs for channel | ✅ | ✅ | ⚫ | ✅ | |
| | Get VOD information | ✅ | ✅ | ⚫ | ✅ | |
| | Update VOD information | ⚫ | ✅ | ⚫ | ✅ | |
| | Delete VOD | ⚫ | ✅ | ⚫ | ✅ | |

<!-- ## Payment management
| Feature | Operations | Public API | Private API | Admin API | Internal | Comments |
|---------|------------|------------|-------------|------------|----------|-----------| -->


# Internal processing

## Categories management

The categories are managed by an internal service connected with IGDB.
IGDB sends new categories using a webhook. Once received, the service will create a new category in the database.

| Operations | Status | Comments |
|------------|---------|----------|
| Receive new category | 🚧 | |
| Store category | 🚧 | |

## Livestreams management

The livestreams are managed by an internal service connected with Livepeer Studio.
Livepeer Studio sends new livestreams using a webhook. Once received, the service will create a new livestream in the database.

| Operations | Status | Comments |
|------------|---------|----------|
| Receive new livestream | 🚧 | |
| Store livestream | 🚧 | |

## Search system

The search system is managed by an internal service connected with Typesense.
Typesense is used to search for channels, categories and livestreams.

| Entity | Operations | Status | Comments |
|--------|------------|---------|----------|
| Channels | Search | 🚧 | |
| | Index | 🚧 | |
| Categories | Search | 🚧 | |
| | Index | 🚧 | |
| Livestreams | Search | 🚧 | |
| | Index | 🚧 | |

## WebSocket system

The WebSocket system is used to send and receive messages between the client and the server.
This is also the system used to send events to the clients (e.g. user banned, new subscription, pinned message updated, etc.)

The complexity here is on the architecture of the system.

| Feature | Operations | Status | Comments |
|---------|------------|---------|----------|
| Chat Messages | Send | 🚧 | |
| Events | Send | 🚧 | |

## Notifications system

The notifications system is used to send notifications to the users. We use FCM to send notifications to the users by mobile, and Amazon SES to send notifications to the users by email.

The solution should be designed to be particularly robust, and to be able to handle a high number of notifications.

| Feature | Operations | Status | Comments |
|---------|------------|---------|----------|
| Notifications | Send | 🚧 | |
