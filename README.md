# Focus Soundtracks

A calming, community-centered web app for the Online Campus Community (OCC). Focus Soundtracks is a 24/7 digital student union for online learners — providing ambient study rooms with curated soundtracks, anonymous emoji interactions, and live presence indicators.

## About

Focus Soundtracks helps online students feel seen, included, supported, and connected to campus life through low-pressure themed study rooms with ambient audio, soft visuals, and light-touch interaction.

**This is not** a learning management system, dashboard, or task manager. It's a digital commons where students can enter a room based on mood, time of day, or academic need.

## Rooms

| Room | Vibe | For Students Who... |
|------|------|---------------------|
| ☕ Rainy Café | Warm, cozy, reflective | Love rainy days, enjoy coffee shop energy |
| 🌙 OCC After Hours | Quiet, focused, comforting | Do their best work at night |
| 🧪 Focus Lab | Structured, efficient | Need maximum concentration |
| 🌿 Soft Reset Space | Gentle, restorative | Feel overwhelmed, need a study break |
| 🎮 Final Boss Level | Determined, motivating | Preparing for finals, major deadlines |
| ☀️ Sunrise Session | Optimistic, energized | Are early risers, enjoy fresh starts |
| 🚂 The Study Line | Cinematic, peaceful | Enjoy movement and scenery while working |
| 🦥 Slow Bloom Café | Mindful, tranquil | Reject hustle culture, value balance |

## Features

- **Curated soundtracks** — Multiple YouTube playlists per room, auto-playing sequentially
- **Ambient visuals** — Canvas-based room-specific animations
- **Anonymous presence** — See how many students are in each room
- **Emoji reactions** — Low-pressure interaction without text chat
- **Focus timer** — Pomodoro-style timer (25min, 50min, or no timer)
- **Encouragement rotator** — Room-specific affirming messages
- **Admin panel** — Manage rooms, emojis, analytics, and seasonal modes
- **Accessible** — Keyboard navigable, screen reader friendly, reduced motion support

## Getting Started

### Prerequisites

- Node.js 18+
- A Firebase project with Realtime Database and Firestore enabled

### Installation

```bash
npm install
```

### Environment Variables

Create a `.env.local` file (see `.env.local.example`):

```
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
NEXT_PUBLIC_FIREBASE_DATABASE_URL=https://your_project.firebaseio.com
```

### Development

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

### Testing

```bash
npm test
```

### Deployment (Vercel)

1. Push to GitHub
2. Import repo at [vercel.com](https://vercel.com)
3. Add environment variables in Vercel dashboard
4. Deploy

## Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Styling**: Tailwind CSS 4
- **Backend**: Firebase (Realtime Database + Firestore + Auth)
- **Music**: YouTube IFrame Player API
- **Animations**: HTML5 Canvas
- **Testing**: Vitest + fast-check (property-based testing)

## Design Principles

1. **Low pressure first** — Enter a room in one click, benefit immediately
2. **Passive belonging** — Know others are present without conversation
3. **Mood-based navigation** — Choose by feeling, not just function
4. **Emotional clarity** — Each room has a distinct vibe and soundtrack
5. **Soft structure** — Tools support focus without feeling busy or demanding

## License

Private — OCC Online Campus Community
