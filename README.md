# TrustLens — AI-Based Community Trust Analyzer

TrustLens is a prototype system designed to detect scams, bot activity, and malicious behavior in online communities such as Telegram, WhatsApp, and Instagram.

It combines AI-based analysis with real-time backend systems to generate a trust score for communities, helping users make informed decisions before engaging.


## Problem

Online communities often lack transparency and are vulnerable to:

- Scam messages
- Bot-driven spam
- Fake promotions
- Misleading groups

Users currently have no reliable way to assess whether a community is trustworthy.


## Solution

TrustLens provides an automated trust scoring system that:

- Analyzes content using AI
- Tracks spam reports
- Assigns a trust score
- Categorizes communities into risk levels

This enables users to quickly identify whether a community is safe or potentially harmful.


## Features

- AI-based scam detection
- Trust score calculation
- Spam report tracking
- Risk classification (Low / Medium / High)
- Real-time updates
- Simple dashboard interface


## Tech Stack

- Frontend: React (generated via AI-assisted development)
- Backend: Supabase (PostgreSQL, Auth, Realtime)
- AI: OpenAI API for text analysis


## System Flow

User Input (message / community link)  
→ AI analysis (spam detection)  
→ Store result in database  
→ Update spam count  
→ Calculate trust score  
→ Return risk level  


## Architecture Overview

TrustLens uses a hybrid architecture:

- Supabase for data storage and real-time updates
- AI for intelligent analysis
- Frontend for interaction and visualization

This allows fast processing while keeping the system scalable.


## Note on Development

This project was developed during a hackathon using AI-assisted development tools to accelerate prototyping.

The focus was on:

- System design
- Data flow
- Integration of AI and backend services

Future iterations will include a fully structured backend and production-level implementation.


## Limitations

- AI accuracy depends on input quality
- No advanced moderation system yet
- Limited scalability optimizations
- Prototype-level error handling


## Future Improvements

- Dedicated backend service (Node.js / APIs)
- Improved trust scoring algorithms
- Browser extension for real-time scanning
- Community verification mechanisms
- Enhanced AI models for better detection


## Setup Instructions

1. Clone the repository

# TrustLens
TrustLens is an AI-powered trust verification system that analyzes online communities for scams, bots, and suspicious behavior using real-time data and automated intelligence.
