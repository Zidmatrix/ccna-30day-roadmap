# 🛡️ CCNA 30-Day Master Roadmap

A **single-file interactive HTML web app** for completing **Jeremy's IT Lab — CCNA 200-301** course in **30 days**, at **3 hours of study per day**, with **6 study days + 1 revision day** every week.

Built in a **SOC / Cybersecurity Dashboard** aesthetic (Dark Mode, Neon accents, Glassmorphism) — no backend, no external libraries besides Tailwind CDN, and works fully offline once opened.

---

## 🚀 Demo / Running the Project

No install or server needed. Just open the file directly in your browser:

```
ccna_30day_roadmap.html
```

Or, if hosted on GitHub Pages, open it straight from the link.

---

## ✨ Features

- 📊 **Main Dashboard**: animated progress ring, stat cards (hours studied, videos, labs, flashcards, exams), weekly progress bars.
- 📅 **Full 30-Day Roadmap** — each day is an accordion containing:
  - Objectives
  - Hour-by-hour breakdown of the 3-hour block (time + task + details)
  - Full Packet Tracer lab spec (Topology, Devices, Commands, Verification, Common Mistakes, Troubleshooting)
  - Interactive checklist (auto-saved)
  - Flashcards with flip animation
  - Mini quiz (5 MCQs) with instant grading
- 🔁 **Weekly revision day** (every 7th day) with mistake review, a combined lab challenge, and a mini practice exam.
- 🧠 **Memory Techniques section**: Active Recall, Spaced Repetition, Blurting, Feynman Technique, Pomodoro, Interleaving, Mind Mapping, Cornell Notes, Retrieval Practice — with guidance on when to use each.
- 📝 **Notebook** with auto-save (basic Markdown notes).
- 🔍 Instant search across days.
- 💾 Full progress persistence via **localStorage** + JSON export/import.
- 🎉 Confetti animation when a day is fully completed.
- 🖨️ Print support, back-to-top button, keyboard shortcuts (`/` to search, `T` to scroll to top).
- 📱 Fully responsive on mobile.

---

## 🛠️ Tech Stack

- HTML5
- TailwindCSS (via CDN)
- Vanilla JavaScript (no frameworks)
- LocalStorage for persistence

Everything lives in a single file, `ccna_30day_roadmap.html` — easy to move around and easy to host as a GitHub Pages site.

---

## 📂 Day Structure

| Week | Content |
|---|---|
| Week 1 | Network Fundamentals (OSI, TCP/IP, Cabling, IPv4, Subnetting) |
| Week 2 | Network Access (VLANs, Trunking, STP, EtherChannel, WLAN) |
| Week 3 | IP Connectivity (Static Routing, OSPF, HSRP, IPv6) |
| Week 4 | IP Services & Security & Automation (DHCP, NAT, ACLs, Port Security, APIs) + final review |

> ⚠️ Note: Video topics and pacing follow the official Cisco blueprint order that Jeremy's IT Lab's course is structured around, not an exact copy of his video titles/timestamps. If you want to sync the exact video numbers/durations, edit the `unitBank` array directly in the code.

---

## 📥 Local Setup / Editing

1. Download the repo or the file.
2. Open `ccna_30day_roadmap.html` in any browser.
3. To edit content (days, quiz questions, flashcards), all data lives inside the `<script>` block in the file, under the `DATA MODEL` section.

---

## 📤 Deploying to GitHub Pages (optional)

1. Create a new GitHub repository.
2. Upload `ccna_30day_roadmap.html` (you can rename it to `index.html` so it loads directly).
3. Go to Settings → Pages, enable GitHub Pages on the main branch.
4. You'll get a link where the app is live and accessible from anywhere.

---

## 📄 License

Personal study project — use and modify freely.
