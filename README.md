# Germany & Austria 2026

> **Single Source of Truth Travel Project**

---

# 專案目的

本專案是 Germany & Austria 2026 Road Trip 的唯一工作空間。

本專案遵循 **Single Source of Truth** 原則：

> **所有旅行內容只維護在一份 MASTER 文件，其餘皆由 MASTER 衍生。**

---

# 專案架構

```
Germany & Austria 2026
│
├── README
├── 00 Project Control
├── 01 Master Guide
├── 02 Reservations & Tickets
├── 03 Places & Research
├── 04 Photos
└── 90 Archive
```

## Folder 說明

| Folder | 用途 |
|---------|------|
| README | 專案說明與工作流程 |
| 00 Project Control | Project Index、Change Log、版本管理 |
| 01 Master Guide | 唯一權威旅行主檔（MASTER） |
| 02 Reservations & Tickets | 機票、住宿、票券、預約 |
| 03 Places & Research | 景點、餐廳、路線研究 |
| 04 Photos | 旅行照片 |
| 90 Archive | 舊版本與不再使用資料 |

---

# 工作流程

任何新增或修改旅行資訊時：

```
研究資料
      │
      ▼
更新 MASTER
      │
      ▼
建立 CHG 編號
      │
      ▼
更新 Version
      │
      ▼
（未來）
同步所有 View
```

---

# Single Source of Truth

```
                     README
                        │
                        ▼
        Germany & Austria 2026 — MASTER
                        │
        ┌───────────────┼────────────────┐
        │               │                │
        ▼               ▼                ▼
   AI 對話 / 快速查詢   一頁式 Website   Pocket Guide
```

## 核心原則

- MASTER 是唯一資料來源（Single Source of Truth）
- 所有修改都只更新 MASTER
- Website、Pocket Guide、AI 查詢皆為不同 View
- 未來新增任何輸出，都由 MASTER 自動產生

> **MASTER is the Source. Everything else is a View.**

---

# 更新規則

### Change Log

```
CHG-0001
CHG-0002
CHG-0003
...
```

### Version

- v1.x：內容更新（新增餐廳、調整行程…）
- v2.0：專案架構或工作流程重大調整

### MASTER

MASTER 檔名永遠固定。

不因版本更新而更改名稱。

---

# Project Principles

1. Single Source of Truth
2. Simple by Default
3. 沒有痛點，就不要增加結構
4. README First
5. Project First，LifeOS Second

---

# AI Collaboration

若 AI 協助此專案，請遵守：

1. 所有內容只更新 MASTER。
2. 不建立新的主檔。
3. 每次更新建立新的 CHG 編號。
4. 保留所有版本紀錄。
5. 發現可重複的方法時，再提出建議，不直接修改專案架構。

---

# Design Philosophy

> **LifeOS chooses the simplest tool that solves today's problem.**

**LifeOS 永遠選擇能解決今天問題的最簡單工具。**

先完成旅行。

LifeOS 只從旅行中學習真正值得重複使用的方法，而不是預先設計所有架構。
