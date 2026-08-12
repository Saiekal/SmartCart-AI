# Database Design

## SmartCart AI

**Database:** PostgreSQL  
**Status:** Initial MVP Design

---

## 1. Overview

SmartCart AI uses PostgreSQL as its relational database.

The database stores users, products, prices, customer reviews, wishlists, and AI-generated review summaries.

---

## 2. Database Tables

The initial MVP contains six main tables:

- `users`
- `products`
- `prices`
- `reviews`
- `wishlists`
- `ai_review_summaries`

---

## 3. Entity Relationship

```text
┌──────────────┐
│    users     │
├──────────────┤
│ id (PK)      │
│ name         │
│ email        │
│ password_hash│
│ created_at   │
│ updated_at   │
└──────┬───────┘
       │
       │ 1
       │
       │ *
┌──────▼───────┐
│  wishlists   │
├──────────────┤
│ id (PK)      │
│ user_id (FK) │
│ product_id   │
│ created_at   │
└──────┬───────┘
       │
       │ *
       │
       │ 1
┌──────▼──────────────┐
│      products       │
├─────────────────────┤
│ id (PK)             │
│ name                │
│ brand               │
│ category            │
│ description         │
│ image_url            │
│ created_at          │
│ updated_at          │
└──┬────────┬──────┬──┘
   │        │      │
   │        │      │
   ▼        ▼      ▼
┌──────┐ ┌──────┐ ┌──────────────────────┐
│prices│ │reviews│ │ai_review_summaries  │
└──────┘ └──────┘ └──────────────────────┘