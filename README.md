# FINTO Mobile App

A mobile-first fintech application for **FINTO**, translating the existing FINTO payment platform into a polished, intuitive, and trustworthy mobile experience.

## Overview

FINTO currently has an existing WordPress website that establishes the brand identity, visual language, product direction, and functionality.

**Website:** https://dev-finto-payment.pantheonsite.io/

This project explores how the existing platform can be translated into a dedicated mobile application while preserving the FINTO brand and improving the experience for mobile users.

---

# AI Design Prompt

## Design Goal

Design FINTO as a realistic, production-quality mobile fintech application — **not simply a responsive version of the website squeezed into mobile view**.

The existing FINTO website should be treated as the primary reference for:

- Brand identity
- Logo
- Colors
- Typography
- Visual language
- Product positioning
- Existing functionality
- Content
- UI patterns

The mobile experience should feel:

- Clean
- Modern
- Premium
- Trustworthy
- Intuitive
- Professional
- Fast
- Accessible

Avoid generic fintech templates, excessive decoration, unnecessary complexity, or simply shrinking the website into a mobile layout.

---

# Core Mobile Experience

### 1. Splash Screen

- FINTO logo
- Minimal branded loading experience

### 2. Onboarding

Create 2–3 concise screens introducing FINTO's core value proposition.

Include:

- Clear messaging
- Visual storytelling
- Get Started CTA
- Login option

### 3. Authentication

Include:

- Sign up
- Login
- Email/phone authentication
- Password
- Forgot password
- Social authentication where appropriate

Keep authentication simple and frictionless.

### 4. Home Dashboard

The primary screen should immediately communicate:

- Current balance
- Recent activity
- Quick actions
- Payment activity
- Notifications
- Important account information

Users should quickly understand:

**What do I have?**  
**What happened recently?**  
**What can I do next?**

### 5. Payments

Design the complete payment flow:

- Send money
- Receive money
- Select recipient
- Enter amount
- Review payment
- Confirm payment
- Payment success
- Payment failure

Financial actions should always provide clear confirmation and feedback.

### 6. Transaction History

Include:

- Recent transactions
- Search
- Filters
- Categories
- Status indicators
- Transaction details

### 7. Transaction Details

Display:

- Amount
- Date/time
- Sender/recipient
- Payment status
- Transaction ID/reference
- Relevant metadata
- Receipt/share/download where appropriate

### 8. QR Payments

If supported by FINTO:

- Scan QR
- Generate personal QR
- Confirm payment

### 9. Profile

Include:

- Personal information
- Account details
- Security
- Payment settings
- Notifications
- Help/support
- Logout

### 10. Notifications

Include:

- Payment notifications
- Account alerts
- Security notifications
- FINTO updates

### 11. Settings

Include appropriate settings for:

- Security
- Biometrics
- Notifications
- Language
- Privacy
- Help

### 12. System States

Design intentional states for:

- Loading
- Empty
- Error
- Success
- Payment pending
- Payment failed
- Payment completed

---

# UX Principles

Because FINTO involves financial transactions, the interface should prioritize **clarity, trust, and user confidence**.

Use:

- Clear confirmation steps
- Strong transaction status indicators
- Obvious success/error feedback
- Consistent amounts and currencies
- Security cues
- Confirmation before irreversible actions
- Simple financial terminology
- Accessible interaction patterns

---

# Navigation

Use a bottom navigation system where appropriate.

Possible structure:

**Home · Payments · Activity · Profile**

However, navigation should be based on the actual FINTO product requirements rather than forcing the product into a predefined structure.

---

# Design System

Establish a consistent mobile design system covering:

- Typography
- Colors
- Spacing
- Buttons
- Inputs
- Cards
- Transaction rows
- Status badges
- Icons
- Navigation
- Modals
- Bottom sheets
- Alerts
- Empty states

Use an **8pt spacing system** where appropriate.

Design primarily for:

**390 × 844 px**

The interface should remain responsive across modern mobile screen sizes.

---

# Core User Flow

```text
Onboarding
    ↓
Login / Sign Up
    ↓
Home
    ↓
Payment
    ↓
Review
    ↓
Confirmation
    ↓
Success
    ↓
Activity
    ↓
Transaction Detail
