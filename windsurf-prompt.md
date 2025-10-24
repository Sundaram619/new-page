# PropertyCibil.com Homepage Redesign Prompt for Windsurf Agent

## Project Overview
Redesign the entire homepage of PropertyCibil.com (https://propertycibil.com/) with modern animations, improved UX/UI, and enhanced visual appeal while maintaining all existing content and functionality.

## Technical Requirements

### Framework & Technologies
- **Frontend**: React.js with TypeScript
- **Styling**: Tailwind CSS for responsive design
- **Animations**: Framer Motion for smooth, professional animations
- **Icons**: Lucide React or Heroicons
- **Fonts**: Inter or Poppins for modern typography
- **Build Tool**: Vite for fast development

### Animation Requirements
1. **Page Load Animations**:
   - Fade-in effect for the entire page
   - Staggered animations for different sections
   - Smooth transitions between elements

2. **Scroll Animations**:
   - Elements animate in as they come into viewport
   - Parallax effects for background elements
   - Smooth scroll behavior

3. **Interactive Animations**:
   - Hover effects on buttons and cards
   - Micro-interactions on form elements
   - Loading states with smooth transitions

4. **Navigation Animations**:
   - Smooth menu transitions
   - Mobile menu slide-in/out effects
   - Active state indicators

## Content Structure & Sections

### 1. Header/Navigation
- **Logo**: PropertyCibil branding
- **Navigation Menu**: 
  - Home, About, Services, CIBIL Score, Property Reports, Contact
  - CTA Button: "Check Your CIBIL Score" (prominent)
- **Mobile Menu**: Hamburger menu with smooth slide animation

### 2. Hero Section
- **Main Headline**: "Get Your Property CIBIL Score & Reports"
- **Subheading**: "Comprehensive property credit information and CIBIL score analysis"
- **Primary CTA**: "Check CIBIL Score Now" (large, animated button)
- **Secondary CTA**: "View Sample Report"
- **Hero Image/Illustration**: Property or credit-related graphics
- **Background**: Gradient or animated background

### 3. Key Features Section
- **Section Title**: "Why Choose PropertyCibil?"
- **Feature Cards** (3-4 cards with hover animations):
  - "Instant CIBIL Score"
  - "Detailed Property Reports"
  - "Expert Analysis"
  - "Secure & Confidential"

### 4. Services Section
- **Section Title**: "Our Services"
- **Service Cards** (with staggered animations):
  - CIBIL Score Check
  - Property Credit Reports
  - Credit Analysis
  - Financial Planning

### 5. How It Works Section
- **Section Title**: "How It Works"
- **Step-by-step Process** (3-4 steps with animated progress):
  - Step 1: Enter Details
  - Step 2: Verification
  - Step 3: Get Report
  - Step 4: Analysis

### 6. Testimonials Section
- **Section Title**: "What Our Customers Say"
- **Testimonial Cards** (with carousel/slider animation):
  - Customer reviews and ratings
  - Smooth transition between testimonials

### 7. CTA Section
- **Background**: Gradient or pattern
- **Headline**: "Ready to Check Your Property CIBIL Score?"
- **CTA Button**: "Get Started Now"
- **Trust Indicators**: Security badges, certifications

### 8. Footer
- **Company Information**
- **Quick Links**
- **Contact Information**
- **Social Media Links**
- **Legal Links** (Privacy Policy, Terms of Service)

## Design Specifications

### Color Scheme
- **Primary**: Blue (#2563EB) - Trust and professionalism
- **Secondary**: Green (#10B981) - Success and growth
- **Accent**: Orange (#F59E0B) - Call-to-action elements
- **Neutral**: Gray scale for text and backgrounds
- **Background**: White with subtle gradients

### Typography
- **Headings**: Bold, modern sans-serif (Inter/Poppins)
- **Body Text**: Clean, readable font
- **CTA Text**: Bold, attention-grabbing

### Layout
- **Container**: Max-width 1200px, centered
- **Spacing**: Consistent padding and margins
- **Grid System**: CSS Grid and Flexbox
- **Responsive**: Mobile-first approach

## Animation Details

### Entrance Animations
```javascript
// Example animation variants
const fadeInUp = {
  initial: { opacity: 0, y: 60 },
  animate: { opacity: 1, y: 0 },
  transition: { duration: 0.6, ease: "easeOut" }
}

const staggerContainer = {
  animate: {
    transition: {
      staggerChildren: 0.1
    }
  }
}
```

### Hover Animations
- Button scale effect (1.05x)
- Card lift effect with shadow
- Icon rotation or color change
- Smooth color transitions

### Scroll Animations
- Use Intersection Observer API
- Elements fade in from different directions
- Parallax scrolling for background elements

## Interactive Elements

### Forms
- **CIBIL Score Check Form**:
  - Animated input fields
  - Real-time validation
  - Loading states
  - Success/error animations

### Buttons
- **Primary CTA**: Large, prominent, with hover effects
- **Secondary CTA**: Outlined style with smooth transitions
- **Loading States**: Spinner or progress animation

### Cards
- **Feature Cards**: Hover lift effect
- **Service Cards**: Tilt effect on hover
- **Testimonial Cards**: Smooth transitions

## Performance Requirements

### Optimization
- Lazy loading for images
- Optimized animations (60fps)
- Minimal bundle size
- Fast loading times

### Accessibility
- ARIA labels for screen readers
- Keyboard navigation support
- High contrast ratios
- Focus indicators

## File Structure
```
src/
├── components/
│   ├── Header/
│   ├── Hero/
│   ├── Features/
│   ├── Services/
│   ├── HowItWorks/
│   ├── Testimonials/
│   ├── CTA/
│   └── Footer/
├── animations/
│   └── variants.js
├── styles/
│   └── globals.css
└── App.tsx
```

## Implementation Steps

1. **Setup Project**: Initialize React + TypeScript + Vite project
2. **Install Dependencies**: Tailwind CSS, Framer Motion, Lucide React
3. **Create Layout**: Basic structure with header, main, footer
4. **Implement Sections**: One by one with animations
5. **Add Interactions**: Hover effects, form handling
6. **Optimize**: Performance and accessibility
7. **Test**: Cross-browser and device testing

## Additional Features

### Micro-interactions
- Button press feedback
- Form field focus animations
- Success/error state animations
- Loading spinners

### Advanced Animations
- Page transition effects
- Scroll-triggered animations
- Particle effects (optional)
- SVG animations

## Content Guidelines

### Copywriting
- Professional yet approachable tone
- Clear value propositions
- Action-oriented CTAs
- Trust-building elements

### Visual Hierarchy
- Clear information architecture
- Proper use of whitespace
- Consistent visual rhythm
- Focus on conversion elements

## Testing Requirements

### Functionality
- All buttons and forms work correctly
- Animations are smooth and performant
- Responsive design works on all devices
- Cross-browser compatibility

### Performance
- Page load time under 3 seconds
- Smooth 60fps animations
- Optimized images and assets
- Minimal JavaScript bundle

---

**Note**: This prompt provides a comprehensive guide for creating a modern, animated homepage for PropertyCibil.com. The Windsurf agent should follow this structure while adding their own creative touches and ensuring all animations enhance rather than distract from the user experience.