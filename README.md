# Dev Collab

_Connect with like-minded developers to collaborate on exciting mini-projects, learn together, and build your portfolio._

> A social coding playground for devs who love to build, learn, and vibe together.

## Overview

**Dev Collab** is a web-based collaboration platform that helps developers find peers with similar interests and team up on mini-projects. Whether you're a beginner looking to learn, an experienced dev wanting to experiment, or someone seeking creative synergy — Dev Collab gives you the environment to thrive.

- **Problem it solves:** Developers often struggle to find collaborators for fun or educational side projects.
- **Target users:** Aspiring developers, hackathon participants, students, and hobbyist builders.
- **What makes it unique:** Lightweight onboarding, interest-based matching, and real-time project creation in a casual, friendly environment.

## Why This Project?

Most developer platforms focus on jobs or open-source contributions, often ignoring the social, fun, and fast-paced mini-project space. **Dev Collab** fills that gap by:

- Making it easy to discover collaborators with shared tech stacks or passions
- Fostering a casual, creative, and welcoming culture
- Encouraging fast prototyping and learning by doing

**Inspired by** the energy of hackathons, study groups, and dev Twitter communities.

## Features

- Interest-based user matching
- Create or join mini-project rooms
- Real-time chat and collaboration tools
- Contribution tracking for each project
- Auth via GitHub or email
- Clean, responsive UI for both desktop and mobile

## Roadmap

- [x] Phase 1: MVP with user auth and project rooms
- [ ] Phase 2: Real-time collaboration tools (chat, code snippets)
- [ ] Phase 3: Team badges, achievements, and public profiles
- [ ] Phase 4: Dev Collab mobile app + AI matchmaker

## Tech Stack

**Web:**
Next.js · React · Tailwind CSS · Express.js · MongoDB

**Real-Time:**
Socket.io · Vercel Serverless Functions

**Cloud:**
Vercel · MongoDB Atlas · GitHub Actions (CI/CD)

## Getting Started

### Prerequisites

- Node.js & npm
- Git
- GitHub OAuth App (for login)

### Installation

```bash
git clone https://github.com/ctvnjhnrmmlp/dev-collab.git
cd dev-collab
npm install
npm run dev
```

## Environment Variables

Create a `.env.local` file in the root directory and define the following:

```env
NEXT_PUBLIC_API_URL=http://localhost:3000
GITHUB_CLIENT_ID=your_github_client_id
GITHUB_CLIENT_SECRET=your_github_client_secret
MONGODB_URI=your_mongodb_connection_string
```

## Usage

```bash
# Run the development server
npm run dev

# Run tests
npm run test
```

## Architecture

```text
[Frontend (Next.js/React)]
      ↓
[Backend (Node.js/Express)]
      ↓
[Database (MongoDB Atlas)]
```

Optional modules:

- Real-time updates via Socket.io
- OAuth via NextAuth.js

## Deployment

- **Cloud:** Deployed on [Vercel](https://vercel.com)
- **Database:** MongoDB Atlas
- **Auth:** GitHub OAuth

## Contributing

We love contributions! Here's how to get started:

1. Fork this repo
2. Create a new branch: `git checkout -b feature/amazing-feature`
3. Commit your changes
4. Push to your branch: `git push origin feature/amazing-feature`
5. Submit a pull request!

## License

This project is licensed under the [MIT License](LICENSE).

## Credits

- Inspired by hackathons, dev Twitter, and collaborative coding spaces
- Built by John Rommel Octaviano
- Powered by Next.js, MongoDB, and GitHub
