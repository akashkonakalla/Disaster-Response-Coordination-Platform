⭐ Title: **Disaster Response Coordination Platform Assignment** ⭐

Description:
  This project coordinates emergency response efforts by enabling real-time reporting, resource sharing, and official + social media updates during disasters.

🧩 Core Features:
1. 📝 Disaster Report Submission
Users submit disaster reports with:

Disaster ID

User ID

Description

Image URL

✅ Option to verify image manually or via Gemini API (AI verification)

Supabase used to store reports

2. 🌆 Image Verification (AI + Manual)
🧠 Gemini API (Vision model) analyzes submitted images to:

Detect authenticity (real, manipulated, fake)

Relate to disaster context

👨‍💻 Manual override included (verified/pending/fake dropdown)

3. 📍 Geospatial Features
Uses Supabase PostGIS for:

Finding nearby resources

Mapping disaster areas

4. 📡 Live Social Media Feed
Displays mock (or future real) posts about selected disaster

Real-time updates via WebSockets (Socket.IO)

5. 📦 Resource Coordination
Users can add available resources (food, water, shelter, etc.)

Linked to disaster via ID

Location stored using geospatial field

6. 🧭 Admin Dashboard
For viewing/updating report verifications

Monitoring disasters, reports, and resources

7. 🔔 Official Updates Panel
Pulls official news/articles from admin or public sources
