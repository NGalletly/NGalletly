<svg width="1200" height="300" xmlns="http://www.w3.org/2000/svg">
  <!-- Gradient Background (mystical swamp vibes) -->
  <defs>
    <linearGradient id="swampGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1a472a;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#2d5f3f;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#1a472a;stop-opacity:1" />
    </linearGradient>
    
    <!-- Star twinkle animation -->
    <radialGradient id="starGlow">
      <stop offset="0%" style="stop-color:#fff;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#ffd700;stop-opacity:0" />
    </radialGradient>
  </defs>
  
  <!-- Background -->
  <rect width="1200" height="300" fill="url(#swampGradient)"/>
  
  <!-- Floating magical sparkles -->
  <circle cx="150" cy="50" r="2" fill="url(#starGlow)">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="980" cy="80" r="2" fill="url(#starGlow)">
    <animate attributeName="opacity" values="1;0.3;1" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1100" cy="200" r="2" fill="url(#starGlow)">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="100" cy="220" r="2" fill="url(#starGlow)">
    <animate attributeName="opacity" values="1;0.4;1" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Lily pads (decorative) -->
  <ellipse cx="100" cy="270" rx="40" ry="15" fill="#2d5f3f" opacity="0.6"/>
  <ellipse cx="1100" cy="280" rx="45" ry="18" fill="#2d5f3f" opacity="0.6"/>
  
  <!-- Wizard hat outline (left side) -->
  <path d="M 80 120 L 120 40 L 160 120 Z" fill="#4a1a4a" stroke="#8b4789" stroke-width="2"/>
  <ellipse cx="120" cy="120" rx="50" ry="12" fill="#4a1a4a" stroke="#8b4789" stroke-width="2"/>
  
  <!-- Stars on hat -->
  <text x="110" y="85" font-size="20" fill="#ffd700">✨</text>
  
  <!-- Main Title -->
  <text x="600" y="120" font-family="'Courier New', monospace" font-size="64" font-weight="bold" 
        fill="#7CFC00" text-anchor="middle" letter-spacing="2">
    NEVILLE
  </text>
  
  <!-- Subtitle with magical flair -->
  <text x="600" y="165" font-family="'Courier New', monospace" font-size="24" 
        fill="#98FB98" text-anchor="middle" letter-spacing="1">
    🐸 The Frog Wizard 🐸
  </text>
  
  <!-- Tagline -->
  <text x="600" y="200" font-family="'Courier New', monospace" font-size="18" 
        fill="#90EE90" text-anchor="middle" style="font-style: italic;">
    Conjuring Code & Casting APIs
  </text>
  
  <!-- Code brackets (decorative) -->
  <text x="300" y="240" font-family="monospace" font-size="32" fill="#7CFC00" opacity="0.5">&lt;/&gt;</text>
  <text x="870" y="240" font-family="monospace" font-size="32" fill="#7CFC00" opacity="0.5">&lt;/&gt;</text>
  
  <!-- Magical staff (right side) -->
  <line x1="1080" y1="80" x2="1080" y2="200" stroke="#8b6914" stroke-width="6"/>
  <circle cx="1080" cy="70" r="15" fill="#9370DB" stroke="#7B68EE" stroke-width="2">
    <animate attributeName="fill" values="#9370DB;#BA55D3;#9370DB" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1080" cy="70" r="8" fill="#E6E6FA" opacity="0.7"/>
  
  <!-- Sparkles around crystal -->
  <text x="1065" y="60" font-size="12" fill="#ffd700">✨</text>
  <text x="1090" y="75" font-size="12" fill="#ffd700">✨</text>
  
  <!-- Footer text -->
  <text x="600" y="270" font-family="'Courier New', monospace" font-size="14" 
        fill="#98FB98" text-anchor="middle" opacity="0.8">
    Junior Full-Stack Developer | London 🇬🇧 | Seeking Backend Sorcery Roles
  </text>
</svg>

# Hi, I'm Neville

## Junior Full-Stack Developer | London, UK

I'm a recent graduate of Northcoders' full-stack software development bootcamp, currently seeking my first role in software engineering. While I enjoy working across the entire stack, I'm particularly focused on **backend development** – specifically RESTful API design and server engineering.

Right now, I'm deepening my backend skills by learning **Python** and **C#** to complement my JavaScript foundation.

---

### Tech Stack

**Languages & Environments:**  
JavaScript (Node.js, Browser), TypeScript, SQL, Python (learning), C# (learning)

**Backend:**  
Node.js, Express.js, PostgreSQL, RESTful APIs, Database Design & Seeding

**Frontend:**  
React, React Native (Expo), HTML, CSS, Accessibility (Lighthouse)

**Testing:**  
Test-Driven Development (TDD), Jest, Supertest

**Hosting & Deployment:**  
Supabase, Render

**Methodologies:**  
Agile, SCRUM, Pair Programming, SDL

---

### Featured Projects

#### [**Borough Books**](link-to-repo)
*React Native (Expo) | Node.js | PostgreSQL | RESTful API*

A full-stack mobile application for tracking book loans within a community. Built the Express server from scratch, designed and implemented the PostgreSQL database schema (8 tables), and developed 15+ RESTful endpoints supporting CRUD operations for books, loans, and real-time messaging.

**Key Features:**
- Barcode scanning integration with Google Books API
- Real-time messaging with Supabase WebSockets
- Complex SQL queries with JOINs for relational data (loan tracking, borrower profiles)
- TDD approach with Jest & Supertest

---

#### [**Emerald News**](link-to-repo)
*React | Node.js | PostgreSQL*

A full-stack news aggregation platform with voting, commenting, and topic filtering. Focused heavily on backend architecture – designed the API, built the Express server, and managed database migrations and seeding.

**Key Features:**
- RESTful API with comprehensive error handling
- PostgreSQL database with normalized schema
- Responsive frontend with React
- Full test coverage using TDD

---

### Currently Learning

- **Backend Server Engineering** – diving deeper into scalable API design and architecture patterns
- **Python** – expanding my backend language toolkit
- **C#** – exploring .NET ecosystem and enterprise backend development

---

### About Me

When I'm not coding, you'll find me:

- **Powerlifting** – training for my first competition at the end of this year
- **Muay Thai/Kickboxing** – casual training (visited Thailand last year to train)
- **Dungeons & Dragons** – monthly sessions with my group
- **Social deduction games** – yes, it's as bizarre as it sounds
- **Arts & Culture** – museums, galleries, theatre, and ballet at the Royal Opera House
- **Music** – alternative music enthusiast

I'm a big fan of science fiction and fantasy – both in books and on screen.

---

### Let's Connect

- **LinkedIn:** https://www.linkedin.com/in/neville-galletly-603a7b2b9/
- 

Always happy to chat about tech, collaborate on projects, or discuss the finer points of a good fantasy novel.

---

**Open to junior full-stack or backend roles in London**
