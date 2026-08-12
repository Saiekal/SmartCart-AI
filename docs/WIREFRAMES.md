# UI Wireframes

## SmartCart AI

**Status:** Initial MVP Design

---

# 1. User Flow

```text
Home
  ↓
Search Product
  ↓
Search Results
  ↓
Product Details
  ↓
┌───────────────────────────────┐
│ Price Comparison              │
│ Price History                 │
│ Buying Insight                │
│ AI Review Insights            │
│ Value Score                   │
│ Alternatives                  │
└───────────────────────────────┘
  ↓
User Decision
  ↓
Buy / Wait / Consider
```

---

# 2. Home Page

```text
┌─────────────────────────────────────────────┐
│ 🛒 SmartCart AI                Login  ♡     │
├─────────────────────────────────────────────┤
│                                             │
│             Shop Smarter.                  │
│             Spend Better.                  │
│                                             │
│   Compare prices. Understand reviews.      │
│   Know when it's worth buying.             │
│                                             │
│ ┌─────────────────────────────────────────┐ │
│ │ 🔍 Search for a product...             │ │
│ └─────────────────────────────────────────┘ │
│                                             │
│              [ Search ]                     │
│                                             │
│ Popular Searches                            │
│ Headphones | Smartphones | Makeup | Shoes  │
│                                             │
└─────────────────────────────────────────────┘
```

---

# 3. Search Results

```text
┌──────────────────────────────────────────────┐
│ 🛒 SmartCart AI                   ♡ Profile   │
├──────────────────────────────────────────────┤
│                                              │
│ 🔍 wireless headphones                 Search │
│                                              │
│ Filters:                                     │
│ [Price] [Rating] [Brand] [Platform]          │
│                                              │
│ 24 products found                            │
│                                              │
│ ┌──────────────────────────────────────────┐ │
│ │ Sony WH-CH720N                           │ │
│ │ ⭐ 4.4/5                                 │ │
│ │ 🏆 Best Price: ₹7,499                    │ │
│ │ 💡 Good time to buy                      │ │
│ │                                          │ │
│ │ [View Insights]                     ♡    │ │
│ └──────────────────────────────────────────┘ │
│                                              │
│ ┌──────────────────────────────────────────┐ │
│ │ JBL Tune 770NC                           │ │
│ │ ⭐ 4.5/5                                 │ │
│ │ 🏆 Best Price: ₹5,999                    │ │
│ │ 💡 Great Value                           │ │
│ │                                          │ │
│ │ [View Insights]                     ♡    │ │
│ └──────────────────────────────────────────┘ │
│                                              │
└──────────────────────────────────────────────┘
```

---

# 4. Product Details

## Product Header

```text
┌──────────────────────────────────────────────┐
│ ← Back                                      │
│                                              │
│ 🎧 Sony WH-CH720N                            │
│ ⭐ 4.4/5       2,438 reviews                 │
│                                              │
│ 🏆 BEST AVAILABLE PRICE                      │
│ ₹7,499                                       │
│                                              │
└──────────────────────────────────────────────┘
```

---

# 5. Price Comparison

```text
┌──────────────────────────────────────────────┐
│ 💰 PRICE COMPARISON                          │
│                                              │
│ Amazon       ₹7,499       [Visit Store]      │
│ Flipkart     ₹7,699       [Visit Store]      │
│ Croma        ₹7,999       [Visit Store]      │
│                                              │
│ 🏆 Best price: Amazon ₹7,499                 │
└──────────────────────────────────────────────┘
```

---

# 6. Buying Insight

```text
┌──────────────────────────────────────────────┐
│ 🤖 BUYING INSIGHT                            │
│                                              │
│                  🟢 BUY NOW                  │
│                                              │
│ Current Price       ₹7,499                   │
│ Recent Average      ₹7,850                   │
│ Recent Low          ₹7,399                   │
│                                              │
│ 💡 Current price is close to the recent low.│
│                                              │
│              PRICE HISTORY                   │
│                                              │
│ ₹8,000 ┤╮                                   │
│ ₹7,500 ┤╰──╮    ╭──                         │
│ ₹7,000 ┤   ╰────╯                           │
│         └────────────────                    │
└──────────────────────────────────────────────┘
```

Possible recommendations:

```text
🟢 BUY NOW
🟡 CONSIDER
🔴 WAIT
```

---

# 7. AI Review Insights

```text
┌──────────────────────────────────────────────┐
│ 🤖 AI REVIEW INSIGHTS                        │
│                                              │
│ 😊 87% Positive                              │
│                                              │
│ WHAT PEOPLE LIKE                             │
│                                              │
│ 🔊 Sound Quality       █████████░ 91%        │
│ 🔋 Battery Life        ████████░░ 88%        │
│ 🎧 Comfort             ████████░░ 82%        │
│                                              │
│ COMMON COMPLAINTS                            │
│                                              │
│ 📞 Microphone          ██████░░░░ 64%        │
│                                              │
│ 👍 PROS                                      │
│ • Excellent sound quality                   │
│ • Long battery life                         │
│ • Comfortable                               │
│                                              │
│ 👎 CONS                                      │
│ • Average microphone                        │
│ • No carrying case                          │
│                                              │
│ 📝 SUMMARY                                   │
│ Most customers are satisfied with the sound  │
│ quality and battery life.                   │
└──────────────────────────────────────────────┘
```

---

# 8. Value for Money

```text
┌──────────────────────────────────────────────┐
│ 💎 VALUE FOR MONEY                           │
│                                              │
│                  8.7 / 10                   │
│                                              │
│ Price          █████████░ 9.0               │
│ Reviews        ████████░░ 8.7               │
│ Features       █████████░ 9.0               │
│                                              │
│ Good value at the current price.            │
└──────────────────────────────────────────────┘
```

---

# 9. Alternatives

```text
┌──────────────────────────────────────────────┐
│ 🔄 BETTER ALTERNATIVES                       │
│                                              │
│ JBL Tune 770NC                               │
│ ⭐ 4.5       ₹5,999                          │
│                                              │
│ ₹1,500 cheaper                               │
│ Similar battery life                         │
│                                              │
│ [Compare]                                    │
└──────────────────────────────────────────────┘
```

---

# 10. Wishlist

```text
♡ Add to Wishlist
```

The wishlist button should be available on:

* Product cards
* Product details page

---

# 11. Mascot

SmartCart AI will use a friendly AI shopping robot as its visual mascot.

The mascot may be used for:

* Buying recommendations
* Empty states
* Loading states
* AI insights
* Price alerts
* Helpful messages

Example:

```text
🤖👍  BUY NOW

🤖🤔  WAIT

🤖🔎  I found a better option!

🤖💰  Great deal!
```

The mascot is a UI personality element and does not affect the underlying recommendation logic.

---

# 12. MVP Screen Summary

| Screen             | Main Purpose                      |
| ------------------ | --------------------------------- |
| Home               | Search products                   |
| Search Results     | Display matching products         |
| Product Details    | Show complete product information |
| Price Comparison   | Compare prices across platforms   |
| Buying Insight     | Recommend Buy / Wait / Consider   |
| Price History      | Show historical price trend       |
| AI Review Insights | Summarize customer reviews        |
| Value for Money    | Calculate product value score     |
| Alternatives       | Suggest better alternatives       |
| Wishlist           | Save products                     |
| Mascot             | Provide friendly AI interaction   |

---

# 13. MVP Navigation

```text
                    ┌──────────────┐
                    │     HOME     │
                    └──────┬───────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │ PRODUCT SEARCH  │
                  └────────┬────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │ SEARCH RESULTS  │
                  └────────┬────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │ PRODUCT DETAILS │
                  └────────┬────────┘
                           │
            ┌──────────────┼──────────────┐
            │              │              │
            ▼              ▼              ▼
     ┌────────────┐ ┌────────────┐ ┌────────────┐
     │   PRICE    │ │   AI       │ │   VALUE    │
     │ COMPARISON │ │  INSIGHTS  │ │   SCORE    │
     └────────────┘ └────────────┘ └────────────┘
            │              │              │
            └──────────────┼──────────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │  ALTERNATIVES   │
                  └─────────────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │ BUY / WAIT /    │
                  │    CONSIDER     │
                  └─────────────────┘
```

---

# 14. Design Principles

The SmartCart AI interface should follow these principles:

1. **Simple** — Users should understand the product information quickly.
2. **Trustworthy** — AI recommendations should show supporting information.
3. **Comparison-focused** — Prices and product alternatives should be easy to compare.
4. **Insight-driven** — Avoid overwhelming users with raw data.
5. **Mobile-friendly** — The interface should work well on desktop and mobile.
6. **Consistent** — Cards, buttons, icons, and spacing should follow a consistent design system.
7. **Transparent AI** — Recommendations should provide a simple explanation.
8. **Fast interaction** — Searching and viewing insights should require minimal steps.

---

# 15. Future Screens

These screens are outside the initial MVP but may be added later:

* User Profile
* Login / Registration
* Wishlist Dashboard
* Price Drop Alerts
* Personalized Recommendations
* Product Comparison Dashboard
* Admin Dashboard
* Data Management Dashboard
* AI Model Monitoring
* Recommendation Explanation Details
