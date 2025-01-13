# Join Streamz

# Status    
| Status | Description |
|--------|-------------|
| ✅ | Done |
| 🚧 | In Progress |
| ❌ | Not Started |
| ⚫ | Not Applicable |


## Account creation and Management
| Feature | Operations | Status | Comments |
|---------|------------|---------|----------|
| Account management | Create account | ✅ | Managed by Ory |
| | Change password | ⚫ | Handled Frontend side |
| | Change email | ⚫ | Handled Frontend side |

## User management
| Feature | Operations | Status | Comments |
|---------|------------|---------|----------|
| User | Read | ✅ | Can fetch account by user identifier |
| Notifications preferences | Read | ✅ | |
| | Update | ✅ | |
| Followed channels | Create | ✅ | |
| | Read | ✅ | |
| | Delete | ✅ | |
| Followed categories | Create | ✅ |
| | Read | ✅ |
| | Delete | ✅ |

## Channel management
| Feature | Operations | Status | Comments |
|---------|------------|---------|----------|
| Channel | Read | ✅ | Can fetch account by channel identifier |
| Panels | Create | ✅ | |
| | Read | ✅ | |
| | Update | ✅ | |
| | Delete | ✅ | |
| Social links | Create | ✅ | |
| | Read | ✅ | |
| | Update | ✅ | |
| | Delete | ✅ | |
| Subscribers badges | Create | ✅ | |
| | Read | ✅ | |
| | Delete | ✅ | |
| VIPs | Create | ✅ | |
| | Read | ✅ | |
| | Delete | ✅ | |
| OGs | Create | ✅ | |
| | Read | ✅ | |
| | Delete | ✅ | |
| Moderators | Create | ✅ | |
| | Read | ✅ | |
| | Delete | ✅ | |

## Chatroom management
| Feature | Operations | Status | Comments |
|---------|------------|---------|----------|
| Chatroom | Read | ✅ | |
| Settings | Read | ✅ | Settings include chat mode, accounts requirements... |
| | Update | ✅ | |
| Blocked terms | Create | ✅ | |
| | Read | ✅ | |
| | Delete | ✅ | |
| Emotes | Create | ✅ | |
| | Read | ✅ | |
| | Delete | ✅ | |
| Rules | Create | ✅ | |
| | Read | ✅ | |
| | Delete | ✅ | |
| User Identity | Read | ✅ | |
| | Update | ✅ | |
| Banned users | Create | ✅ | |
| | Read | 🚧 | |
| | Delete | ✅ | |

## Chat messages management
| Feature | Operations | Status | Comments |
|---------|------------|---------|----------|
| Messages | Read | 🚧 | includes reading all messages for a user, for a chatroom, for a user in a chatroom - This feature is the history |
| | Send | 🚧 | Requires the websocket system to be implemented|
| | Delete | 🚧 | |

## Livestream management
| Feature | Operations | Status | Comments |
|---------|------------|---------|----------|

## Payment management
| Feature | Operations | Status | Comments |
|---------|------------|---------|----------|

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
| | Receive | 🚧 | |
| Events | Send | 🚧 | |
| | Receive | 🚧 | |
