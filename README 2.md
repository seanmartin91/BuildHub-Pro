# 🏗️ BuildHub Pro — Construction Project Manager

A full-featured, mobile-friendly construction project management web app. **Zero dependencies. Pure HTML/CSS/JS.**

## 🚀 Running on Replit

1. Upload `index.html` to a new Replit project (choose **HTML/CSS/JS** template)
2. Click **Run** — the app opens instantly in the browser panel
3. That's it. No npm install, no build step.

---

## ✨ Features

### 📊 Dashboard
- Live stats: active projects, files uploaded, completion %, total budget
- Quick-view project progress bars
- Site weather widget
- Today's tasks & activity feed

### 🏛️ Project Management
- Create unlimited build site projects
- Each project tracks: type, location, budget, status, progress, files
- Status indicators: Active / On Hold / Complete
- Search & filter projects

### 📁 Files & Photos
- Drag-and-drop file uploads (images, PDFs, DWGs, DOCX)
- Photo gallery with thumbnail previews
- **Image viewer** with full controls:
  - Rotate left / right
  - Zoom in / out
  - Flip horizontal / vertical
  - Reset transform
- File type filtering (images, PDFs, drawings, documents)
- Search across all files

### 📅 Timeline
- Visual Gantt-style progress chart
- Milestone tracker with status (done / active / pending)
- Visual timeline with phase descriptions

### ✅ Site Checklist
- Daily inspection & safety checklist
- Toggle items done/undone
- Filter by all / pending / done
- Priority tags (High / Medium / Low)
- Category labels (Safety, QA, Logistics, etc.)

### 🧮 Calculator (dual)
- **Standard calculator** — full arithmetic with expression display
- **Build Cost Estimator** — construction-specific:
  - Concrete & foundations (£/m³)
  - Steel rebar (£/tonne)
  - Brickwork & timber frame (£/m²)
  - Electrical points & plumbing units
  - Flooring (£/m²)
  - Auto-calculates with 15% contingency

### 💰 Budget Tracker
- Per-category budget vs. spent breakdown
- Visual status tags (% used with colour alerts)
- Summary cards for total / spent / remaining

### 📝 Site Notes (Site Diary)
- Create tagged notes: Urgent / Important / Info / Resolved
- Cards with author, date, content preview
- Searchable

### 👷 Team Contacts
- Contractor, engineer, client, and H&S contacts
- Role, company, phone, email, project assignment
- Clickable phone/email links

### 🤖 AI BuildBot Agent
- Floating chat agent (bottom-right)
- Query files: "show site photos", "find floor plans", "find PDFs"
- Budget queries: "budget summary"
- Timeline: "upcoming milestones"
- Safety: "safety checklist"
- Quick-chip shortcuts for common queries

---

## 📱 Mobile Ready
- Responsive layout for phones and tablets
- Touch-friendly buttons and controls
- Collapsible sidebar

## 🔧 Extending the App

The app uses plain JS arrays as the data layer. To connect a real backend:
- Replace `projects`, `files`, `notes`, etc. arrays with `fetch()` calls to your API
- Add a Node.js/Express backend (easy to add as a second Replit file)
- Connect to Firebase, Supabase, or any REST API for persistence

## 📦 File Structure
```
index.html    ← Everything (single file — styles + app + logic)
.replit       ← Replit run config
README.md     ← This file
```

---

Built with 🧱 by BuildHub Pro
