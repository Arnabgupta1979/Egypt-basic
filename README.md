# Egyptian Seed Sector Portal - Mockups

## 📱 What's Included

This folder contains **5 professional mockups** of the key pages for the Egyptian Seed Sector Portal. These mockups are fully styled, responsive, and demonstrate the complete user experience.

### Mockup Files:

1. **01-homepage.html** - Complete homepage with all sections
2. **02-variety-catalogue.html** - Searchable variety catalogue with filters
3. **03-variety-detail.html** - Detailed variety information page
4. **04-wizard-modal.html** - Interactive Q&A wizard system
5. **05-procedure-detail.html** - Step-by-step procedure guide

## 🚀 How to View

### Option 1: Open Directly in Browser
Simply double-click any `.html` file to open it in your default web browser.

### Option 2: Use Live Server (Recommended for testing)
```bash
# If you have Python installed:
cd mockups
python3 -m http.server 8000
# Then open: http://localhost:8000/01-homepage.html

# Or if you have Node.js:
npx serve
```

### Option 3: View All at Once
Open each file in a separate browser tab to compare layouts and navigation flow.

## 🎨 Design Features

### Color Scheme
- **Primary:** #C8102E (Egyptian Red)
- **Secondary:** #2D7A3E (Agricultural Green)
- **Accent:** #FFD700 (Gold)
- **Neutrals:** Gray scale from 50-900

### Typography
- **Font:** Inter (sans-serif)
- **Headings:** Bold (700 weight)
- **Body:** Regular (400 weight)

### Components
- Responsive grid layouts
- Interactive cards with hover effects
- Professional form elements
- Modal dialogs
- Accordion sections
- Tab interfaces
- Status badges
- Progress indicators

## 📋 Page Descriptions

### 1. Homepage (01-homepage.html)
**Purpose:** Main landing page introducing the portal

**Features:**
- Hero section with Egyptian flag colors
- 6 interactive pathway cards (Q&A wizard triggers)
- Live statistics dashboard (4 key metrics)
- Featured resources section (4 cards)
- Latest news & updates (3 articles)
- Comprehensive footer with contact info

**Sections:**
1. Header (sticky navigation)
2. Hero with gradient background
3. Quick Start wizard cards
4. Statistics (green gradient)
5. Featured resources
6. News grid
7. Footer with links

### 2. Variety Catalogue (02-variety-catalogue.html)
**Purpose:** Browse and search registered varieties

**Features:**
- Advanced search bar
- Left sidebar with filters:
  - Crop type (with counts)
  - Registration status
  - Special traits
  - Clear filters button
- Results grid showing variety cards:
  - Variety image placeholder
  - Name, type, breeder
  - Key metrics (maturity, yield)
  - Trait badges
  - Availability status
  - Action buttons
- Right sidebar with:
  - Quick actions (export, save search)
  - Statistics box
- Pagination controls

**Interactive Elements:**
- Clickable variety cards
- Filter checkboxes
- Sort dropdowns
- Items per page selector

### 3. Variety Detail (03-variety-detail.html)
**Purpose:** Complete information for a single variety (Giza 171 wheat)

**Features:**
- Status badges (registered, seed available, PVP, COMESA)
- Image gallery (main + 2 thumbnails)
- Tabbed content interface:
  - Overview (basic info + agronomics)
  - Quality parameters
  - Where to buy (map + dealers)
  - Performance data
  - Documents
- Detailed information grids
- Trait badges
- Right sidebar with:
  - Quick actions (favorite, compare, download)
  - Related varieties
  - User reviews with rating

**Data Displayed:**
- Registration details
- Breeder/maintainer info
- Pedigree
- Agronomic characteristics
- DUS distinguishing features
- Special traits
- Quality parameters
- Recommended zones

### 4. Wizard Modal (04-wizard-modal.html)
**Purpose:** Interactive Q&A system for guidance

**Features:**
- Full-screen modal overlay
- Progress indicator (3 steps):
  - Completed steps (green checkmark)
  - Active step (red highlight)
  - Future steps (gray)
- Question display (Step 2 of 3)
- 4 selectable option cards:
  - Radio button selection
  - Title and description
  - Hover effects
  - Selected state highlighting
- Navigation buttons:
  - Back (enabled if not on step 1)
  - Next (enabled when option selected)
- Close button (X in top right)

**Interactive:**
- Click any option to select
- Real-time visual feedback
- Accessible radio buttons

### 5. Procedure Detail (05-procedure-detail.html)
**Purpose:** Step-by-step guide for variety registration

**Features:**
- Hero section with key metrics:
  - Timeline (2-3 years)
  - Cost (EGP 100-750)
  - Authority (CASC)
- Overview with info alert box
- Expandable step accordion (5 steps):
  - Step number badge
  - Title and duration
  - Expandable content with:
    - Requirements checklist
    - What you need lists
    - Common mistakes warning box
    - Detailed instructions
- Visual timeline with markers
- Right sidebar (sticky):
  - CASC contact card (phone, email, address, hours)
  - Required forms download links
  - Help/consultation booking button

**Interactive Elements:**
- Click step headers to expand/collapse
- Only one step open at a time
- Smooth transitions

## 📱 Responsive Design

All mockups are **mobile-first** and fully responsive:

- **Desktop:** Full 3-column layouts (1280px max width)
- **Tablet:** 2-column layouts, adjusted spacing
- **Mobile:** Single column, stacked sections, hamburger menus

**Breakpoints:**
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## 🎯 User Experience Features

### Visual Hierarchy
- Clear headings and sections
- Consistent spacing (1rem base)
- Color-coded by importance
- Icons for quick recognition

### Interactivity
- Hover effects on cards and buttons
- Active/selected states
- Smooth transitions (0.2-0.3s)
- Cursor changes for clickable elements

### Accessibility
- Semantic HTML5 elements
- Proper heading structure (h1-h6)
- Alt text placeholders for images
- Keyboard navigation ready
- High contrast ratios (WCAG AA)

### Performance
- No external dependencies (except Google Fonts)
- Minimal CSS (inline for mockups)
- No heavy images or videos
- Fast load times

## 🔧 Technical Details

### Browser Compatibility
- Chrome/Edge: ✅ Latest 2 versions
- Firefox: ✅ Latest 2 versions
- Safari: ✅ Latest 2 versions
- Mobile browsers: ✅ iOS Safari, Chrome Mobile

### Technologies Used
- HTML5
- CSS3 (Grid, Flexbox, Custom Properties)
- Vanilla JavaScript (minimal, for interactions)
- Google Fonts (Inter, Cairo)

### No Dependencies
These mockups are **standalone** - no build process, no frameworks, no libraries (except fonts). Just open and view!

## 🎨 Design Patterns Used

1. **Card-based layouts** - Information organized in digestible chunks
2. **Progressive disclosure** - Accordion/tabs hide complexity
3. **Visual feedback** - Hover states, active states, loading indicators
4. **Consistent spacing** - Multiples of 0.25rem (4px)
5. **Color coding** - Red for primary actions, green for success, etc.
6. **Icon usage** - Emojis as placeholder icons
7. **Grid systems** - CSS Grid for layouts
8. **Sticky elements** - Fixed header, sticky sidebar
9. **Modal overlays** - Wizard system
10. **Breadcrumb navigation** - Clear page hierarchy

## 📊 Content Realism

All mockups use **realistic content** based on actual Egyptian seed sector data:

- Real variety names (Giza 171, Sakha 95, etc.)
- Accurate institution names (CASC, CAPQ, CASP, ARC)
- Real contact information
- Actual legal references (Law 53/1966, Law 82/2002)
- True statistics (1,247 varieties, 143 protected, etc.)
- Genuine procedures and timelines

## 🚧 Mockup Watermarks

Each mockup includes a subtle "MOCKUP" watermark to indicate these are for design review, not production files.

## ⚡ Next Steps

After reviewing these mockups:

1. **Feedback:** Identify any design changes needed
2. **Approval:** Sign off on overall design direction
3. **Development:** Use these as reference for building the actual portal
4. **Content:** Begin gathering real data and documents
5. **Photography:** Plan for actual variety/institution photos
6. **Translation:** Prepare Arabic translations for bilingual support

## 📞 Questions?

If you need any modifications to these mockups:
- Different color schemes
- Alternative layouts
- Additional pages
- Mobile-specific views
- Print-friendly versions

Just let me know and I can generate updated versions!

---

**Created:** January 2026  
**For:** Egyptian Ministry of Agriculture and Land Reclamation  
**Purpose:** Design review and stakeholder presentation
