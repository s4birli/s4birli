# Mehmet Sabırlı

Full-stack engineer, 15+ years. After hours I run my family's infrastructure on a homelab and build AI agents that take real chores off our plate. Reading, UK.

### Homelab

An old gaming laptop turned home server, replacing Dropbox and iCloud for the whole family.

- Ubuntu Server and Docker Compose, one stack per service
- Photos in Immich with GPU face and object search, files in Seafile, films and music in Jellyfin and Navidrome
- No open ports: Cloudflare Tunnel for the family apps, Tailscale for admin
- Glance dashboard, nightly backups with health-check pings, and a watchdog agent that keeps an eye on it all

### Hermes agents

A family assistant built on [Hermes Agent](https://github.com/NousResearch/hermes-agent), living in WhatsApp and on the Echo speakers.

- School-day morning briefings: weather, what to wear, PE kit, clubs, which bus to catch
- Reads school emails, newsletters and calendars, and turns anything that needs action into a to-do card
- Nothing gets sent or closed without my approval
- Every agent runs in its own locked-down container; cheap models for routine runs, bigger ones only when something looks wrong

### Second brain (in progress)

One place to ask anything about our life: mail, attachments, photos, documents and chats.

- Every mailbox pulled into Postgres, attachments into local S3 storage
- Facts and relationships extracted into typed tables, vectors in Qdrant
- Sensitive facts kept encrypted in their own table
- Ask "when does the car insurance end?" and get the answer, not the PDF

### Side quests

- Instagram saves turned into a searchable, visual wiki, refreshed every night
- A one-page AI news "comic newspaper", delivered every evening

### Stack

TypeScript · Node.js · React / Next.js · Python · C# / .NET · PostgreSQL · Qdrant · Docker · MCP

[LinkedIn](https://www.linkedin.com/in/s4birli)
