# Astral Turf Lite

A lightweight version of the Astral Turf soccer management application, optimized for viewing on GitHub without memory constraints.

## Overview

This is a streamlined version containing only the essential files for the soccer tactics board and team management features.

## Features

- Interactive soccer field with draggable player tokens
- Formation editor and tactical planning
- Team management interface
- Player statistics and analytics
- Match simulation capabilities

## Tech Stack

- React with TypeScript
- Vite for build tooling
- Tauri for desktop application
- Context API for state management

## Project Structure

```
astral-turf-lite/
├── components/         # Core UI components
├── pages/             # Main application pages
├── context/           # State management
├── services/          # Business logic
└── hooks/            # Custom React hooks
```

## Full Version

For the complete application with all features, see: [Astral Turf Full](https://github.com/Damatnic/astral-turf)

## Getting Started

```bash
npm install
npm run dev
```

For desktop version:
```bash
npm run tauri dev
```

## License

MIT