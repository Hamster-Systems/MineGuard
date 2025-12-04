# 🛣️ MineGuard Roadmap
A forward-looking plan for upcoming features, improvements, and system expansions.  
This roadmap outlines what is **completed**, **in progress**, and **planned** for future releases of MineGuard.

---

## ✅ Completed Features
These features are fully implemented and active on the live platform.

### Core System
- [x] Player search page with autocomplete
- [x] Mojang API integration (UUID + skin heads)
- [x] Player profiles with REP score & risk levels
- [x] Known For behavioural summaries (non-AI version)
- [x] Report submission system (categories, evidence, server info)
- [x] CASE ID system (`CASE-XXXX`)
- [x] Pending → Approved / Denied moderation workflow
- [x] Denial reasons + moderator messages  
- [x] Moderator-only visibility for pending reports  
- [x] Pagination for large report lists

### Moderation Tools
- [x] Admin dashboard
- [x] Moderation queue (pending reports)
- [x] Case status editing (approve/deny/update)
- [x] Quick denial templates
- [x] Moderator logs & audit trail
- [x] Role system (Admin, Moderator)
- [x] Private staff notes
- [x] Case search by CASE ID

### User Features
- [x] Login + registration
- [x] Role badges (Admin, Mod, Trusted Reporter tiers)
- [x] Notifications system
- [x] Settings page (email, password)
- [x] My Reports overview
- [x] Dark mode

### UI / UX
- [x] Full Bootstrap 5 redesign
- [x] Homepage mini statistics card
- [x] Polished profile layout
- [x] Two-line report previews + expand/collapse
- [x] Pretty URLs using `.htaccess`

### Analytics
- [x] Stats page (category totals, report counts)
- [x] Basic trend graph
- [x] Peak report times
- [x] Category heat distribution

---

## 🔧 In Progress
These features are currently being built or refined.

### Behaviour & AI
- [ ] AI-powered “Known For” behavioural summary  
- [ ] AI-assisted consistency checking (flag suspicious or duplicate reports)  
- [ ] Behaviour pattern detection (repeated actions, frequent categories)

### Moderation
- [ ] Editable quick-response templates  
- [ ] Moderator assignment per CASE  
- [ ] Nested staff notes / internal discussion threads  
- [ ] Expanded audit logging  
- [ ] Mod dashboard improvements (filters, bulk tools)

### UX / UI
- [ ] Profile badges for risk severity  
- [ ] Enhanced autocomplete (ranking + fuzzy matching)
- [ ] “Trusted server” verification badges  
- [ ] Detailed server history section on profile pages

### Analytics
- [ ] Deep trend analysis  
- [ ] Monthly reports graph  
- [ ] Category comparison timeline  
- [ ] Server comparison charts (top servers by risk, category rates)

---

## 🧭 Planned / Future Features
These items are approved but not yet in development.  
Order may shift based on priority and community needs.

### Player-Facing
- [ ] Appeal system for verified Minecraft account owners
- [ ] Player verification (e.g., sign-in via Minecraft server or code-based confirmation)
- [ ] Public API for read-only profile data
- [ ] Bookmark/watch players for updates
- [ ] Case subscription notifications

### Moderation
- [ ] Senior Moderator role with limited admin power
- [ ] Automated duplicate detection for reports
- [ ] Auto-expire / reputation decay system
- [ ] Moderator performance dashboard

### Security / System
- [ ] IP reputation scoring (server-side, not public)
- [ ] API rate limiting per user/IP
- [ ] Optional 2FA for moderators/admins
- [ ] Encrypted evidence upload support (instead of links only)

### Integrations
- [ ] Server-side plugin integration (Spigot/Paper/Fabric)
- [ ] Webhooks for Discord moderation channels  
- [ ] Public “report widget” embeddable in other websites  
- [ ] JSON API for server-side checks

---

## 🌐 Long-Term Vision
MineGuard aims to become the **trusted standard** for community-generated Minecraft behaviour monitoring.  
Long term, the platform aims to provide:

- A shared safety network between servers  
- Behaviour tracking across multiple communities  
- Robust, fair reviewing and appeals  
- Rich analytical insights  
- Automated detection signals  

---

## 🏗 Versioning Approach
MineGuard follows a simple versioning model:

```
MAJOR.MINOR.PATCH
```

- **MAJOR** — large redesigns, breaking feature changes  
- **MINOR** — new features, UX improvements  
- **PATCH** — bug fixes, UI polishing, minor behaviour changes  

---

## 📣 Contributing & Suggestions
Although the codebase is private, community suggestions are welcome.  
Open an issue in this repository to propose:

- New features  
- UX improvements  
- Moderator tools  
- Bug reports  
- UI/visual changes  

---

## 📅 Roadmap Status
Updated regularly as progress is made.  
Last updated: **4th December 2025**

