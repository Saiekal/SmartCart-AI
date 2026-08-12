# Software Requirements Specification (SRS)

## SmartCart AI

**Project Type:** Personal Individual Project  
**Status:** In Development  
**Version:** 1.0

---

# 1. Introduction

## 1.1 Project Overview

SmartCart AI is an AI-powered shopping decision-support application that helps users make better purchasing decisions.

Instead of simply showing products and prices, SmartCart AI combines price comparison, historical price analysis, customer review analysis, and AI-generated insights to help users understand whether a product is worth buying and whether they should buy it now or wait.

The system is designed as a decision-support platform rather than an online shopping platform.

---

## 1.2 Problem Statement

Online shoppers often compare products across multiple platforms before purchasing.

Users may face difficulties such as:

- Different prices across shopping platforms
- Difficulty determining whether the current price is actually good
- Large numbers of customer reviews
- Difficulty identifying common positive and negative opinions
- Uncertainty about whether to buy now or wait for a better price
- Difficulty comparing similar products
- Lack of a single platform that combines price and review insights

SmartCart AI aims to simplify this decision-making process.

---

# 2. Objectives

The main objectives of SmartCart AI are:

1. Compare product prices across supported platforms.
2. Maintain historical product price information.
3. Analyze customer reviews using NLP techniques.
4. Identify positive and negative aspects of products.
5. Generate concise AI-powered review insights.
6. Estimate whether the current price is favorable.
7. Provide a BUY NOW / CONSIDER / WAIT recommendation.
8. Provide a value-for-money score.
9. Help users discover better alternatives.
10. Provide a simple and user-friendly shopping decision interface.

---

# 3. Scope

## 3.1 In Scope

The initial MVP will include:

- User registration and login
- Product search
- Product details
- Multi-platform price comparison
- Historical price tracking
- Price analysis
- Buy/Wait recommendation
- Customer review display
- Sentiment analysis
- Aspect-based review analysis
- AI-generated review summary
- Pros and cons extraction
- Value-for-money score
- Wishlist functionality

---

## 3.2 Future Scope

Future versions may include:

- Price forecasting using machine learning
- Sale-period prediction
- Product recommendations
- Personalized recommendations
- Coupon discovery
- Delivery and return comparison
- Fake review detection
- Price-drop notifications
- Mobile application
- More shopping platforms

---

# 4. Target Users

SmartCart AI is intended for online shoppers who want to:

- Compare prices
- Understand customer feedback quickly
- Find good-value products
- Decide when to purchase
- Discover alternatives

---

# 5. Functional Requirements

## FR-01: User Registration

The system shall allow users to create an account using:

- Name
- Email
- Password

Passwords shall be securely hashed before storage.

---

## FR-02: User Login

The system shall authenticate registered users and provide secure access using JWT-based authentication.

---

## FR-03: Product Search

The system shall allow users to search for products using keywords.

Example:

```text
wireless headphones