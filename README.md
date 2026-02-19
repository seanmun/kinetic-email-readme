# <a href="https://kinetic.email" target="_blank">Kinetic.Email</a>

> Interactive, engaging, and dynamic email experiences that push the boundaries of traditional email design.
>
> **🌐 <a href="https://kinetic.email" target="_blank">Visit kinetic.email →</a>**

[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black)](https://kinetic.email)
[![Built with React](https://img.shields.io/badge/Built%20with-React-61DAFB)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)](https://typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

## 🌟 Overview

Kinetic.Email is a comprehensive educational platform and portfolio showcase for kinetic emails - interactive email experiences that break free from static limitations. The platform combines learning resources, real-world examples, and admin tools for managing email campaigns and digital assets.

**Platform Purpose:**
- **📚 Educational Hub** - Comprehensive learning modules teaching kinetic email techniques
- **🎨 Live Examples** - Interactive code demonstrations with detailed explanations
- **💼 Portfolio Showcase** - Real client campaigns with iOS Mail simulator previews
- **🤖 AI Playground** - Claude-powered email generation with RAG retrieval and multi-client simulator
- **⚡ Token Economy** - Credit system with signup bonuses, course rewards, and referral program
- **🛠️ Admin Tools** - Station dashboard for managing portfolio, assets, tokens, and email evaluation system

---

## 🗺️ Site Architecture

### Public Sections

#### 🏠 **Home**
Landing page introducing kinetic email concepts and showcasing the platform's capabilities.

**Features:**
- **Hero section showcasing a live kinetic email**
  - Interactive demo email with real kinetic techniques (tabs, accordions, lightswitch)
  - Live tracking widget demonstrating real-time engagement analytics
  - Visual explanation of how tracking works conceptually
- **What's Included in the Kinetic Course**
  - Overview of 6 comprehensive learning modules
  - Learning path from beginner to advanced techniques
  - Interactive code examples and downloadable templates
- **AI Playground Quick Tutorial**
  - Step-by-step guide to generating your first kinetic email
  - How to use natural language prompts effectively
  - Preview, edit, and export workflow
- **How Our AI Playground Works**
  - Claude Sonnet 4 for HTML/CSS generation
  - GPT-4 embeddings for semantic search of proven examples
  - RAG pipeline retrieves similar campaigns from vector database
  - Template selection and customization process
  - Real-time preview with iOS Mail simulator
  - Built-in testing and optimization tools

---

#### 📚 **Learn**
Comprehensive educational platform with interactive learning modules.

**Learning Path:**

1. **Introduction to Kinetic Emails**
   - What are kinetic emails?
   - Why they matter for engagement
   - Email client compatibility overview
   - Real-world use cases and ROI

2. **The Checkbox Hack**
   - CSS-only interactivity technique
   - How `:checked` pseudo-class works
   - Building interactive accordions
   - Image carousels without JavaScript
   - Live code examples with syntax highlighting

3. **Kinetic Lightswitch**
   - Detecting light/dark mode in emails
   - Automatic theme adaptation
   - Graceful fallbacks for non-supporting clients
   - Best practices for accessibility

4. **Building Tabbed Elements**
   - Creating tab interfaces with radio buttons
   - Multi-state content switching
   - Navigation patterns in emails
   - Advanced styling techniques

5. **Advanced Techniques**
   - CSS animations and transitions
   - Combining multiple interaction patterns
   - Performance optimization
   - Complex state management

6. **Kinetic Email Tracking**
   - How tracking pixels work
   - Privacy-conscious analytics
   - Measuring engagement beyond opens
   - Attribution and conversion tracking

**Learning Features:**
- ✅ Progress tracking (saved to user profile)
- 📊 Completion badges and achievements
- 💻 Interactive code editors with live preview
- 📱 Mobile-responsive examples
- 🎯 Quiz questions to reinforce learning
- 📥 Downloadable code templates

---

#### 💼 **Portfolio**
Showcase of real client campaigns demonstrating kinetic email techniques in production.

**Client Industries:**
- Technology & Hardware
- Health & Wellness
- E-commerce & Consumer Goods
- Cryptocurrency & Finance
- Medical & Healthcare

**Campaign Types:**
- Educational email series
- Product tutorials and guides
- Interactive product showcases
- Newsletter updates with data visualization
- E-commerce carousels and CTAs

**Portfolio Features:**
- 📱 iOS Mail simulator (realistic iPhone preview)
- 🖼️ Before/after interaction states
- 💡 Technique breakdowns for each campaign
- 📊 Performance metrics (open rates, click-through rates)
- 🎨 Design process and client goals

---

#### 🤖 **AI Playground**
AI-powered kinetic email generation platform that transforms ideas into production-ready interactive emails.

**Core Features:**

**🎨 AI Email Generation**
- Natural language prompts to describe desired email
- Claude Sonnet 4 powered HTML/CSS generation
- RAG (Retrieval-Augmented Generation) with Pinecone vector database
- GPT-4 embeddings for semantic search of proven email examples
- Automatic kinetic technique selection based on similar campaigns
- Brand-aware styling and tone matching
- Multiple design variations per prompt

**⚡ Real-time Preview**
- Live rendering of generated emails
- iOS Mail simulator integration
- Light/dark mode switching
- Interactive element testing
- Instant feedback loop

**🔧 Interactive Editing**
- Visual code editor with syntax highlighting
- Drag-and-drop element positioning
- Real-time HTML/CSS modification
- Undo/redo functionality
- Export to production-ready code

**📋 Smart Templates**
- Pre-built kinetic email templates
- Industry-specific starting points
- Customizable component library
- One-click technique insertion (tabs, accordions, carousels)

**🧪 Built-in Testing**
- Email client compatibility checks
- Fallback validation
- Accessibility scoring
- Performance optimization suggestions
- Spam score analysis

**📱 Multi-Client Simulator**
- One-click "Simulate" button after email generation
- Side-by-side rendering across Apple Mail, Gmail, Outlook, and Yahoo
- Per-client CSS transformation with warning indicators
- 2x2 grid preview or individual client focus mode

**💾 Save & Share**
- Save generated emails to user account
- Version history tracking
- Shareable preview links
- Export as HTML files
- Copy to clipboard functionality

---

#### 👤 **Profile**
User account management, token balance, referrals, and learning progress tracking.

**Profile Features:**
- ⚡ Token balance & economy
  - Current balance, lifetime earned, lifetime spent
  - Transaction history with pagination (load 5, then 10 more at a time)
  - CSV export for transaction records (100+ transactions)
- 🔗 Referral program
  - Unique referral share link with copy-to-clipboard
  - Referral count and tokens earned from referrals
  - Both referrer and referred user earn tokens
- 📊 Learning progress dashboard
  - Developer Course and Marketing Course progress bars
  - Completion percentage per course
  - Next recommended module links
  - Earned badges displayed as compact chips
- 👤 Account settings
  - Display name
  - Email preferences
  - Marketing communications opt-in/out
- 🔐 Password management
  - Reset password
  - Update security settings

---

### Admin Section

#### 🎛️ **Admin Dashboard**
Comprehensive control panel for managing all aspects of the platform.

**Access Control:**
- 🔒 Restricted to admin users only (database-driven access control)
- ✅ Secure authentication via Supabase
- 🔐 Automatic redirect for unauthorized users

**Admin Tools:**

**📸 Asset Manager**
- Digital asset library for managing campaign media
- Drag-and-drop upload with batch processing
- Automatic image optimization and format conversion
- CDN URL generation and embed codes
- Asset usage analytics and version control

**📧 Email Evaluation System**
- Internal testing platform for campaign validation
- Multi-client email rendering simulators
- Interactivity testing (checkboxes, tabs, carousels)
- Dark/light mode switching
- Performance analysis and accessibility audits
- Pre-flight checklist and client approval workflow

**🖼️ Portfolio Manager**
- Backend interface for managing portfolio projects
- Project creation with client and campaign details
- Production code storage with version control
- iOS Mail simulator configuration
- Portfolio organization with drag-and-drop
- Analytics dashboard for engagement metrics

**📊 Kinetic Database**
- Real-time tracking dashboard for kinetic email interactions
- Action definition builder for creating tracking pixels
- Batch tracking pixel generation (create multiple actions at once)
- Visual dashboard showing engagement metrics and recent activity
- Query interface for analyzing user interactions by email, type, or date
- Convex-powered real-time database with automatic sync
- Secure tracking with validation and suspicious activity logging
- Support for all kinetic interaction types: surveys, quizzes, tabs, carousels, accordions, toggles, activations, selectors, and shopping carts

**⚡ Token Manager**
- Token economy overview — total tokens in circulation, earned, spent, average balance
- Searchable user balances table with manual adjust (award/deduct) per user
- Configurable bonus amounts — signup bonus, course completion reward, referral reward
- Configurable action costs — set token cost per AI generation, email send, or other actions
- Active/inactive toggle per action for free vs. paid enforcement
- Referral analytics — total referrals, top referrers, recent activity

**🧠 AI System Management**
- **RAG Pipeline Architecture**
  - Claude Sonnet 4 for kinetic email generation
  - GPT-4 for query rewriting and embedding generation
  - Pinecone vector database for semantic search
  - Hybrid search combining vector similarity and metadata filters
- **Knowledge Base Management**
  - Custom embedding generation from portfolio campaigns
  - Proven email examples indexed by technique, complexity, and purpose
  - Blog content and documentation integrated into retrieval
  - Similarity threshold filtering (>0.7) for quality control
- **System Optimization**
  - Prompt engineering and template refinement
  - AI evaluation system with automated quality scoring
  - A/B testing framework for generated email variations
  - Performance monitoring and retrieval accuracy tracking

---

## 🛠️ Technology Stack

### Frontend
| Technology | Purpose | Version |
|------------|---------|---------|
| **React** | UI Framework | ^18.0.0 |
| **TypeScript** | Type Safety | ^5.0.0 |
| **Vite** | Build Tool & Dev Server | ^5.0.0 |
| **Tailwind CSS** | Utility-First Styling | ^3.0.0 |
| **React Router** | Client-Side Routing | ^6.0.0 |
| **React Syntax Highlighter** | Code Display | ^15.0.0 |
| **React Icons** | Icon Library | ^4.0.0 |

### Backend & Database
| Technology | Purpose |
|------------|---------|
| **Supabase** | PostgreSQL Database + Auth |
| **Supabase Auth** | User authentication & sessions |
| **Row Level Security (RLS)** | Database security policies |
| **Convex** | Real-time database for kinetic email tracking |
| **Vercel** | Hosting & Deployment |
| **Vercel Analytics** | Traffic and performance monitoring |

### AI & Machine Learning
| Technology | Purpose |
|------------|---------|
| **Anthropic Claude** | Kinetic email HTML/CSS generation |
| **OpenAI** | Query rewriting & embeddings |
| **Pinecone** | Vector database for semantic search |
| **RAG Pipeline** | Retrieval-Augmented Generation system |

### Data Layer

**Supabase (PostgreSQL):**
- User profiles and account preferences
- Admin access control
- Learning progress and course completion tracking
- Token economy (balances, transactions, referral tracking, configurable costs)
- Row Level Security (RLS) on all tables

**Convex (Real-time):**
- Kinetic email interaction tracking
- Email send records and metadata
- Tracking pixel definitions
- Security and abuse monitoring

**Authentication:**
- Email/password, magic link, and Google OAuth
- Session persistence with secure tokens

---

## 📧 Email Client Compatibility

### Kinetic Email Support

| Email Client | Interactive Support | Fallback Support | Notes |
|-------------|-------------------|------------------|-------|
| **Apple Mail (macOS)** | ✅ Full Support | ✅ | Best experience |
| **Mail (iOS)** | ✅ Full Support | ✅ | Primary target client |
| **Outlook for Mac** | ❌ No Support | ✅ | Webkit-based rendering |
| **Outlook for iOS** | ❌ No Support | ✅ | Shows fallback version |
| **Gmail (Web)** | ❌ No Support | ✅ | Strips interactive CSS |
| **Gmail (Mobile App)** | ❌ No Support | ✅ | Limited CSS support |
| **Outlook (Windows)** | ❌ No Support | ✅ | Word rendering engine |
| **Yahoo Mail** | ❌ No Support | ✅ | Basic HTML support |

**Fallback Strategy:**
All kinetic emails include graceful degradation to ensure readability and functionality in non-supporting clients. Fallback versions display static content with clear CTAs.

---

## 🎯 Key Features

### Learning Platform
- ✅ **6 comprehensive modules** covering beginner to advanced techniques
- ✅ **Progress tracking** with completion badges
- ✅ **Interactive code examples** with live preview
- ✅ **Downloadable templates** for each technique
- ✅ **Mobile-responsive** learning experience
- ✅ **Syntax highlighting** for HTML/CSS code

### Portfolio Showcase
- ✅ **iOS Mail simulator** with realistic iPhone preview
- ✅ **6 client campaigns** across multiple industries
- ✅ **Before/after states** showing interactivity
- ✅ **Performance metrics** for each campaign
- ✅ **Technique breakdowns** explaining implementation
- ✅ **Responsive gallery** with filtering

### Token Economy & Growth Hacking
The token system is a growth hacking engine built around a core insight: **educated users become advocates**. The self-reinforcing loop — **sign up → learn → refer → repeat** — uses token incentives to create platform stickiness by rewarding course participation. Completing courses isn't just about earning tokens; it equips users with a deep understanding of how kinetic email works and what it can accomplish. That education transforms casual users into informed advocates who genuinely understand the value of interactive email and are motivated to spread the word. The referral program adds a viral component — every user gets a unique share link, and both the referrer and the new user earn tokens when the link converts, turning every educated user into a distribution channel. Tokens gate premium actions (AI email generation), creating natural scarcity that drives users back to learning and sharing rather than hitting a hard paywall. All reward amounts and action costs are admin-tunable from Station, enabling rapid experimentation with incentive structures.

- ✅ **Signup bonus** — new users receive tokens on account creation
- ✅ **Course completion rewards** — earn tokens for finishing Developer and Marketing courses
- ✅ **Referral program** — unique share links; both referrer and referred earn tokens
- ✅ **Token gating** — AI generation costs tokens; configurable per action
- ✅ **Transaction history** — full audit log with pagination and CSV export
- ✅ **Insufficient tokens modal** — guides users to earn more via courses or referrals
- ✅ **Admin-configurable** — all bonus amounts and action costs adjustable from Station

### Multi-Client Email Simulator
- ✅ **Render Simulator** embedded in Sandbox with real-time CSS transformation
- ✅ **Four email clients** — Apple Mail, Gmail, Outlook, Yahoo side-by-side
- ✅ **Simulate from Playground** — one-click preview of AI-generated emails
- ✅ **Per-client warnings** — surface CSS compatibility issues per client
- ✅ **Grid and focus views** — 2x2 overview or single-client deep dive

### Admin Tools (Station)
- ✅ **Asset manager** for organizing campaign media
- ✅ **Email evaluation system** for testing campaigns
- ✅ **Portfolio manager** for adding/editing projects
- ✅ **Token manager** for user balances, manual adjustments, and economy configuration
- ✅ **Kinetic database** for tracking email interactions in real-time
- ✅ **Action builder** for creating tracking pixels (batch generation support)
- ✅ **User management** (admin access control)
- ✅ **Analytics dashboard** (traffic, engagement)
- ✅ **Database admin** via Supabase and Convex interfaces

### Authentication & Security
- ✅ **Email/password login** with Supabase Auth
- ✅ **Magic link authentication** (passwordless)
- ✅ **Google OAuth** integration
- ✅ **Row Level Security (RLS)** on all database tables
- ✅ **Admin-only routes** with automatic redirect
- ✅ **Session persistence** across page refreshes
- ✅ **Secure profile management** (users see only their data)

---

## 🗂️ File Structure

```
kinetic-email/
├── public/                  # Static assets
├── src/
│   ├── assets/             # Images, icons, media
│   ├── components/         # Reusable React components
│   ├── contexts/           # React Context (Auth, Tokens, Learning Progress)
│   ├── hooks/              # Custom React hooks (useTokenGate, useReferralCapture)
│   ├── lib/                # Utilities (Supabase client)
│   ├── pages/              # Route components
│   │   ├── home/          # Landing page
│   │   ├── learn/         # Learning modules
│   │   ├── portfolio/     # Portfolio showcase
│   │   ├── profile/       # User profile
│   │   ├── render-simulator/ # Multi-client email renderer
│   │   └── admin/         # Station (admin dashboard)
│   │       ├── assets/    # Asset manager
│   │       ├── eval/      # Email evaluation system
│   │       ├── portfolio/ # Portfolio manager
│   │       └── tokens/    # Token manager
│   ├── routes.tsx         # React Router configuration
│   ├── main.tsx           # App entry point
│   └── index.css          # Global styles
├── database/              # SQL schemas and migrations
├── .env                   # Environment variables (gitignored)
└── README.md             # This file
```

---

## 🚀 Deployment

**Platform:** Vercel
**URL:** [kinetic.email](https://kinetic.email)

**Environment Variables:**
- `VITE_SUPABASE_URL` - Supabase project URL
- `VITE_SUPABASE_ANON_KEY` - Supabase public API key
- `VITE_CONVEX_URL` - Convex deployment URL
- `CONVEX_DEPLOY_KEY` - Convex deployment key (build-time only)

**Deployment Workflow:**
1. Push to `main` branch
2. Vercel auto-deploys from GitHub
3. Environment variables configured in Vercel dashboard
4. Automatic HTTPS and CDN distribution

---

## 📊 Analytics & Monitoring

**Vercel Analytics:**
- Real-time visitor tracking
- Page load performance
- Geographic distribution
- Traffic sources

**Supabase Logs:**
- Database query performance
- Authentication events
- Error tracking
- API usage

---

## 🔒 Security

**Database Security:**
- ✅ Row Level Security (RLS) enabled on all tables
- ✅ Users can only access their own profiles
- ✅ Admin users table is read-only via policies
- ✅ SQL injection protection via Supabase client

**Authentication Security:**
- ✅ JWT-based session management
- ✅ Secure password hashing (bcrypt)
- ✅ HTTPS-only cookies
- ✅ CSRF protection
- ✅ Rate limiting on auth endpoints

**Admin Access:**
- ✅ Database-driven admin list (`admin_users` table)
- ✅ Email-based access control
- ✅ No hardcoded credentials
- ✅ Audit trail for admin actions

---

## 📞 Contact

- **Website**: [kinetic.email](https://kinetic.email)
- **Learning Hub**: [kinetic.email/learn](https://kinetic.email/learn)
- **AI Playground**: [kinetic.email/playground](https://kinetic.email/playground)

---

**Made with ❤️ for the email design community**

*Pushing the boundaries of what's possible in email design, one kinetic interaction at a time.*
# Trigger redeploy
