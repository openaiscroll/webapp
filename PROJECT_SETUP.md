# AI Chat Sharing Platform - Project Setup

## Project Overview
An open-source platform for sharing and exploring AI chat conversations from various sources (ChatGPT, Claude, Gemini, etc.) with a focus on code sharing and discovery.

## Core Features (MVP)

### 1. Chat Display
- Clean, mobile-first interface
- Code blocks with syntax highlighting
- Language detection and display
- Copy-to-clipboard functionality
- Responsive design (320px and up)

### 2. Navigation (Bottom Nav Bar)
- **Info Button**: Platform information and help
- **Play/Pause**: Auto-scroll functionality
- **Next**: Skip to next conversation
- **Plus**: Future functionality (placeholder)
- **Search**: Toggle search interface

### 3. Technical Stack
- **Frontend**: Next.js 14 (App Router)
- **Styling**: Tailwind CSS
- **Icons**: Feather Icons
- **State Management**: React Context (Zustand if needed)
- **Database**: MongoDB Atlas
- **Hosting**: Vercel
- **CI/CD**: GitHub Actions

## Project Structure
```
apps/
  web/                 # Next.js application
  ├─ app/              # App Router pages
  ├─ components/       # Reusable components
  │  ├─ chat/         # Chat-related components
  │  ├─ ui/           # Base UI components
  │  └─ layout/       # Layout components
  ├─ lib/             # Utilities and hooks
  └─ styles/          # Global styles

packages/
  config/            # Shared configs (ESLint, Tailwind)
  types/             # Shared TypeScript types
  ui/                # Shared UI components (future)


infra/
  mongodb/           # Database schemas & indexes

docs/                 # Project documentation
  features/          # Feature documentation
  architecture.md    # System architecture
```

## Development Phases

### Phase 1: Setup & Core Components
1. Initialize Next.js with TypeScript and Tailwind
2. Set up MongoDB connection
3. Create basic layout with bottom navigation
4. Implement chat message display
5. Add code block component with copy functionality

### Phase 2: Core Features
1. Implement auto-scroll functionality
2. Add next conversation navigation
3. Create search UI (frontend)
4. Add basic animations

### Phase 3: Polish & Refinement
1. Performance optimization
2. Loading states
3. Error boundaries
4. Basic analytics

## Open Source Considerations

### Documentation
- [ ] README.md
- [ ] CONTRIBUTING.md
- [ ] CODE_OF_CONDUCT.md
- [ ] LICENSE (MIT recommended)
- [ ] Issue templates
- [ ] Pull request template

### Development Setup
1. Node.js 18+
2. pnpm
3. MongoDB Atlas account
4. Vercel account

### Environment Variables
```
MONGODB_URI=your_mongodb_uri
NEXT_PUBLIC_SITE_URL=your_vercel_url
# Add other environment variables as needed
```

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   pnpm install
   ```
3. Set up environment variables
4. Run development server:
   ```bash
   pnpm dev
   ```

## Future Considerations
- User authentication
- Chat submission system
- Advanced search with MongoDB Atlas Search
- User profiles and collections
- Social features (likes, comments)
- Dark/light mode
- PWA support

## Contributing
Please read our [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
