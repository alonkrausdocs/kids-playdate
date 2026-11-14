# Kids Playdate

Tinder-style app concept that matches parents and families for playdates and parent friendships.

**Portfolio project by Alon Kraus, built with AI-assisted development ("vibe coding").** An AI agent implements (plan, mockups, code, QA) while other AI models review each step; Alon directs, reconciles and decides.

## Status: design and mockup stage

**There is no working app yet.** No code, no backend, no tests. This repo currently holds planning artifacts only:

- `/mockups` - seven UI mockup screens as HTML sources (rendered images are not included; open the HTML files in a browser to view them)
- This README

Everything shown is fictional demo data. No real user data, no credentials, no production backend.

## Proposed stack

Expo / React Native / TypeScript + Supabase. One codebase for Android and iOS. (Proposal, not adopted yet.)

## Planned approach (proposals, not implemented features)

- **Safety first:** children appear only as ages in years - never names, photos or birthdates. Coarse location only (neighbourhood, never exact distance). Phone verification, report/block, content moderation and a named human moderator are planned capabilities to be built before any real users.
- **Phased with gates:** demo MVP > validation pilot > trust & safety hardening > store release > payments last. Each phase needs an explicit go.
- **Compliance researched upfront:** Apple UGC moderation and in-app account deletion, Google Play child-safety standards, age restrictions and account-deletion requirements.

All people, profiles and phone numbers shown in the mockups are fictional. Berlin place names are used as the demo setting.
