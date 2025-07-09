---
layout: default
title: LuNote Manual
---

# LuNote User Manual

> Last updated: {{ site.time | date: '%Y-%m-%d' }}

Welcome to **LuNote**, your all-in-one diary, todo, and life-logging companion. This guide focuses on the main screen controls—what happens when you tap, double-tap, or long-press—and gives an overview of every major feature so you can get the most out of the app.

## 1. Home Screen at a Glance

| Area | Purpose |
|------|---------|
| **Date Bar** | Shows today’s date. Tap to open the calendar picker and jump to any date. |
| **Cards** | Quick widgets for *Today Diary* preview, *D-Day* countdown, and *Step* summary. |
| **Bottom Navigation** | Five tabs for Diary, Todo, D-Day, Statistics, and Settings. |
| **Floating Action (+) Button** | Create new entries from anywhere. |

## 2. Bottom Navigation Buttons

| Button | Single Tap | Double Tap | Long Press |
|--------|-----------|-----------|------------|
| **Diary** | Open diary list for selected date | Scroll to top of list | Open date picker |
| **Todo** | Toggle *Today* ⇄ *Tomorrow* list | Collapse / expand *Today* section | Mark all todos complete / incomplete |
| **D-Day** | View countdown timers | Jump to nearest upcoming event | Sort / filter options |
| **Stats** | Open main statistics hub | Cycle range *7 → 30 → 90* days | Export current chart as CSV |
| **Settings** | Open preferences | — | View app information |

## 3. Floating Action Button (+)

| Gesture | Action |
|---------|--------|
| Tap | Choose *Diary* / *Todo* / *D-Day* entry type |
| Double-tap | Immediate quick-diary entry |
| Long press | Voice command (beta) |

## 4. App Bar & Tool Icons

| Icon | Action |
|------|--------|
| 🔍 **Search** | Global search across diary, todo, and D-Day |
| 🔄 **Sync** | Manual cloud backup / restore prompt |
| 🔔 **Midnight Alert** | Toggle 00:00 daily reminder |
| 📊 **Send to Stats** | Push current data to statistics module |
| ⋮ **More Menu** | Export / Import • GPS Tracking • Distance Comparison • Activity Pattern • **Database Management** • **User Manual** |

## 5. Gestures Everywhere

- **Swipe left** → Delete current item
- **Swipe right** → Edit item
- **Pinch** → Adjust text size on the fly
- **Shake** → Toggle dark mode

## 6. Statistics Dashboard

Accessed via the **Stats** tab, the dashboard offers multiple pages:

| Page | Widgets & Tools |
|------|-----------------|
| **Diary Stats** | Entry frequency heatmap, keyword word-cloud, mood pie chart |
| **Step Counter** | Daily steps line chart, distance & calorie estimates |
| **Activity Pattern** | Hour-by-hour histogram, active / idle ratio |
| **Distance Comparison** | Bar chart comparing walking vs running vs cycling |
| **Daily Route Map** | Map overlay of GPS traces (requires location permission) |
| **Weather & Moon** | Weather trends & moon phase widgets |

Every chart supports: *Zoom / Pan* with pinch, *Range switch* (double-tap), and **Export** as PNG / CSV / PDF via the top-right ⋮ menu.

## 7. Backup & Restore

1. Open **Settings ▸ Backup / Restore**.
2. Connect to Google Drive (first time only).
3. Tap **Backup Now** to upload JSON + SQLite snapshot.
4. To restore, pick a backup and tap **Restore**.

## 8. FAQ

**Why are ads not showing?**  
Ads may be blank for up to 48 h after a fresh Play-Store release. To verify integration, enable **Test Ads** in *Settings ▸ Debug*.

**iCloud / Drive sync is stuck?**  
Sign out of the cloud account and sign back in, then retry.

## 9. Support

- Email: [support@lunote.app](mailto:support@lunote.app)
- GitHub Issues: <https://github.com/schaam/lunote/issues>

---
Made with ❤️ by the **LuNote Team** 