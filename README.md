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
- **🛠️ Admin Tools** - Station dashboard for managing portfolio, assets, and email evaluation system

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

**💾 Save & Share**
- Save generated emails to user account
- Version history tracking
- Shareable preview links
- Export as HTML files
- Copy to clipboard functionality

---

#### 👤 **Profile**
User account management and learning progress tracking.

**Profile Features:**
- 📊 Learning progress dashboard
  - Modules completed
  - Overall progress percentage
  - Next recommended module
  - Completion badges
- 👤 Account settings
  - Display name
  - Email preferences
  - Marketing communications opt-in/out
- 🔐 Password management
  - Reset password
  - Update security settings
- 📈 Activity history
  - Recently viewed modules
  - Saved templates
  - Bookmarked portfolio pieces

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
| **Vercel** | Hosting & Deployment |
| **Vercel Analytics** | Traffic and performance monitoring |

### AI & Machine Learning
| Technology | Purpose |
|------------|---------|
| **Claude Sonnet 4** | Kinetic email HTML/CSS generation |
| **GPT-4** | Query rewriting & embeddings generation |
| **Pinecone** | Vector database for semantic search |
| **OpenAI Embeddings** | text-embedding-3-small & text-embedding-3-large |
| **RAG Pipeline** | Retrieval-Augmented Generation system |

### Database Schema

**Tables:**
- `user_profiles` - User account data and preferences
- `admin_users` - Admin access control list
- `learning_progress` - Module completion tracking
- `portfolio_projects` - Portfolio campaign data (future)
- `assets` - Asset manager metadata (future)

**Authentication:**
- Email/password authentication
- Magic link login
- Google OAuth (optional)
- Session persistence with JWT

---

## 📧 Email Client Compatibility

### Kinetic Email Support

| Email Client | Interactive Support | Fallback Support | Notes |
|-------------|-------------------|------------------|-------|
| **Apple Mail (macOS)** | ✅ Full Support | ✅ | Best experience |
| **Mail (iOS)** | ✅ Full Support | ✅ | Primary target client |
| **Outlook for Mac** | ✅ Full Support | ✅ | Webkit-based rendering |
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

### Admin Tools (Station)
- ✅ **Asset manager** for organizing campaign media
- ✅ **Email evaluation system** for testing campaigns
- ✅ **Portfolio manager** for adding/editing projects
- ✅ **User management** (admin access control)
- ✅ **Analytics dashboard** (traffic, engagement)
- ✅ **Database admin** via Supabase interface

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
│   ├── contexts/           # React Context (Auth, Learning Progress)
│   ├── hooks/              # Custom React hooks
│   ├── lib/                # Utilities (Supabase client)
│   ├── pages/              # Route components
│   │   ├── home/          # Landing page
│   │   ├── learn/         # Learning modules
│   │   ├── portfolio/     # Portfolio showcase
│   │   ├── profile/       # User profile
│   │   └── admin/         # Station (admin dashboard)
│   │       ├── assets/    # Asset manager
│   │       ├── eval/      # Email evaluation system
│   │       └── portfolio/ # Portfolio manager
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
- **AI Playground**: [kinetic.email/portfolio](https://kinetic.email/playground)

---

**Made with ❤️ for the email design community**

*Pushing the boundaries of what's possible in email design, one kinetic interaction at a time.*
