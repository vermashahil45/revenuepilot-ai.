# Infonetica Agentic AI Demo

**Production-ready demonstration of an autonomous agent system for demand generation in B2B SaaS.**

A true agent loop executing the **Observe → Think → Act → Learn → Adapt** cycle in real-time.

## What This Shows

### The Agent Loop
1. **OBSERVE** — Agent reads 120-lead dataset, scores each lead 0-100
2. **THINK** — Agent evaluates decision model per segment (Tier 1, Mid-market, Regulatory)
3. **ACT** — Agent autonomously routes emails to hot + warm leads
4. **LEARN** — Agent tracks opens/clicks and identifies high-performing patterns
5. **ADAPT** — Agent updates decision model allocations, confidence 45%→75%+

### Core Metrics
- **Lead Scoring Model:** Revenue + Engagement + Recency (compound scoring)
- **Segmentation:** Tier 1 (large orgs), Mid-market, Regulatory Bodies
- **Email Strategy:** Personalized by segment + decision model
- **Performance Tracking:** Opens, clicks, conversion by lead type
- **Agent Confidence:** Increases with data (45% baseline → 75%+ after learning)

## Features

✅ **120-lead dataset** (Stanford, MIT, Harvard, NIH, Google, Microsoft, Meta, etc.)
✅ **Real-time scoring** (0-100 per lead)
✅ **Automatic segmentation** (revenue, engagement, recency)
✅ **Agent control panel** (confidence threshold, email budget)
✅ **Live execution log** (watch agent decide and act)
✅ **Email tracking** (opens, clicks, CTR)
✅ **Learning engine** (pattern identification by segment+type)
✅ **Adaptation analytics** (how agent evolved decision model)
✅ **Performance dashboard** (comprehensive metrics)

## How to Use

### 1. Upload Leads
- Paste CSV: `Company,Revenue,Type,Role,Engagement,Days,Pages,Source`
- Agent automatically scores and segments

### 2. Configure Agent
- Set confidence threshold (70% default)
- Set email budget (60% default)
- Watch live execution

### 3. Monitor Performance
- Execution log shows every agent decision
- Tracking tab shows email performance
- Learning tab shows discovered patterns
- Adaptation tab shows how agent evolved
- Performance tab shows final metrics

## Technical Architecture

**Frontend:** Pure HTML/CSS/JavaScript (client-side only)
**Scoring:** Proprietary scoring model (40 baseline + modifiers)
**Segmentation:** Revenue-based + engagement analysis
**Simulation:** Open/click probability based on lead score
**Learning:** Pattern tracking across all actions
**Adaptation:** Decision model updates after each cycle

## Interview Demo Script

"I built an end-to-end agentic system for demand generation. Watch:

1. **OBSERVE** — Agent loads and scores 120 leads
2. **THINK** — Decision model evaluates by segment (Tier 1: 40% compliance, 35% ROI, 25% demo)
3. **ACT** — Agent routes emails automatically
4. **LEARN** — Sees opens/clicks, identifies patterns
5. **ADAPT** — Rewrites decision model, confidence 45%→75%

This isn't just campaigns. It's a self-improving system that compounds week over week. In production, the email transport is Twilio Mailgun or SendGrid via API. The intelligence layer — agent orchestration — is what I've built here."

## Performance Expectations

- **Initial Confidence:** 45%
- **After First Cycle:** 65-75%
- **Typical Open Rate:** 35-50% (varies by segment)
- **Click Rate:** 12-25% (varies by content type)
- **Adaptation Speed:** 1 cycle per week

## Deployment

Deployed on Vercel. Share the link on:
- Resume/Portfolio
- LinkedIn
- Interview prep
- Job applications

No backend needed. Pure client-side simulation.

## About

Built as a production-grade demo for marketing technology interviews, specifically targeting:
- Product Manager roles
- Marketing Manager roles
- Growth Engineer roles
- Business Analyst roles

Demonstrates:
- Systems thinking
- Agentic AI understanding
- Autonomous decision-making
- Learning & adaptation
- Data-driven strategy
- B2B SaaS knowledge

---

**Resume Link:** Share your Vercel URL anywhere
**Interview Time:** 5-10 minute demo
**Technical Depth:** Production-ready architecture
