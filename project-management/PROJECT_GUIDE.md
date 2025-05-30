# iSPEAK Language Learning Platform - Complete Project Guide

## 🎯 Project Overview
Building a world-class, conversion-focused website for iSPEAK Language Learning Program that connects African diaspora children (ages 3-14) with their heritage through live 1:1 lessons with indigenous language speakers.

## 📅 Timeline: 30 Days to Launch
- **Start Date**: May 30, 2025
- **Launch Date**: June 29, 2025
- **Today's Event**: Special event at 10 AM EST

## 🎨 Brand Assets & Resources

### Logo Files
- **Primary Logo**: `/Users/mac/Downloads/iSPEAK/branding/ISPEAK.png` (Full logo with text)
- **Icon/Favicon**: `/Users/mac/Downloads/iSPEAK/branding/iSPEAK-Favicon.png` (Paji bird only)
- **Text Logo**: `/Users/mac/Downloads/iSPEAK/branding/ISPEAK Text Logo/`
- **Current Site Logo**: `/Users/mac/Downloads/ispeaklanguage-ready/logo.png`
- **Full Logo on Site**: `/Users/mac/Downloads/ispeaklanguage-ready/ispeak-full-logo.png`

### Image Assets
**Square Images** (`/Users/mac/Downloads/iSPEAK copy/iSPEAK square image/`):
- `Child_learning_online_with_headphones.png` ✅ (Hero section primary)
- `Child_holding_a_Well_done_certificate.png`
- `Child_happily_reading_book.png`
- `Children_learning_languages_together.png`
- `Grandmother_storytelling_to_children.png` ✅ (Cultural connection)
- `Mother_and_daughter_studying_together.png`

**Landscape Images** (`/Users/mac/Downloads/iSPEAK landscape images (1)/`):
- `1.jpg` - iSPEAK merchandise and branding
- `3.jpg` - Grandmother storytelling (powerful emotional connector)
- `4.jpg` - Online classroom interface
- Additional numbered images (2.jpg, 5-10.jpg)

### Background Assets
- `iSPEAK Background.jpg` - Natural/cultural patterns for subtle backgrounds

## 🎨 Design System

### Colors
```css
:root {
    --primary-teal: #6EC5B8;
    --dark-teal: #2B5D52;
    --yellow: #FFD93D;
    --orange: #FFA500;
    --purple: #8B4F9F;
    --dark-blue: #2B2D42;
    --coral: #FF8C61;
    --light-blue: #E0F7FA;
    --cream: #FAF9F6;
    --white: #FFFFFF;
}
```

### Typography
- **Primary Font**: Montserrat (headings)
- **Secondary Font**: Poppins (body text)
- **Font Weights**: 300, 400, 500, 600, 700

### Key Visual Elements
1. **Paji Bird Mascot** - Teal bird with yellow wings and purple belly
2. **Three Pillars** - Listening (ear icon), Speaking (speech bubble), Reading (book)
3. **Cultural Patterns** - African-inspired geometric designs
4. **Gradient Overlays** - Teal to dark teal gradients

## 🏗️ Technical Architecture

### Current Setup
- **Repository**: https://github.com/bakiel/ispeaklanguage-temp
- **Live URL**: https://bakiel.github.io/ispeaklanguage-temp/
- **Custom Domain**: https://ispeaklanguage.org (CNAME configured)
- **GitHub Token**: Stored in `/Users/mac/Downloads/github-token.txt`

### Tech Stack
- HTML5 with semantic markup
- Tailwind CSS 2.2.19
- Vanilla JavaScript (mobile-first approach)
- Font Awesome 6.0.0 for icons
- Google Fonts API

### Performance Requirements
- Lighthouse score > 90
- Mobile-first responsive design
- Image optimization (WebP with fallbacks)
- Lazy loading for below-fold content
- Critical CSS inlined

## 📱 Key Features to Implement

### Phase 1: Foundation (Week 1-2)
1. **Hero Section**
   - Parallax scrolling background
   - Animated Paji mascot (floating animation)
   - Rotating language greetings
   - Video background option

2. **Navigation**
   - Sticky header with transparency
   - Mobile hamburger menu
   - Dropdown menus for desktop
   - Active state indicators

3. **Value Propositions**
   - Interactive cards with hover effects
   - Icon animations on scroll
   - Progress indicators

### Phase 2: Interactive Elements (Week 3-4)
1. **Three Pillars Section**
   - Click-to-explore functionality
   - Animated trees with Paji birds
   - Progress tracking visualization

2. **Language Journey Map**
   - Interactive timeline
   - Hover states showing curriculum
   - Age-appropriate pathways

3. **Live Lesson Preview**
   - Video modal popup
   - Sample lesson snippets
   - Teacher profiles

### Phase 3: Conversion Optimization (Week 5)
1. **Social Proof**
   - Live student counter
   - Testimonial carousel
   - Success story videos
   - Trust badges

2. **Urgency Elements**
   - Limited spots counter
   - Countdown timer for offers
   - "Class starting soon" notifications

3. **Micro-interactions**
   - Button animations
   - Form field validations
   - Loading states
   - Success animations

## 📝 Content Strategy

### Key Messaging
1. **Primary Hook**: "Connect Your Child to Their African Heritage Through Language"
2. **Value Props**:
   - Certified native speakers
   - Personalized 1:1 lessons
   - Cultural preservation
   - Convenience & flexibility

### Emotional Triggers
- **Heritage Connection**: "Your child's link to their roots"
- **Future Success**: "Opening doors to opportunities"
- **Community**: "Join thousands of families preserving culture"
- **Confidence**: "Watch them bloom with pride"
- **Trust**: "Certified native speakers who care"

### Call-to-Actions
- Primary: "Start Your Free Trial"
- Secondary: "Book a Demo Lesson"
- Tertiary: "Download Free Resources"

## 🚀 Deployment & Launch Strategy

### Week 1-2 Deliverables
- [ ] Enhanced hero section with proper images
- [ ] Mobile-responsive navigation
- [ ] Value proposition cards with animations
- [ ] Three pillars interactive section
- [ ] Basic SEO implementation

### Week 3-4 Deliverables
- [ ] Language selection interface
- [ ] Teacher profile section
- [ ] Testimonial integration
- [ ] FAQ accordion
- [ ] Contact form with validation

### Week 5 Deliverables
- [ ] Performance optimization
- [ ] A/B testing setup
- [ ] Analytics integration
- [ ] Final QA testing
- [ ] Launch preparation

## 📊 Success Metrics
- **Conversion Rate**: Target 5-8% for trial signups
- **Bounce Rate**: < 40%
- **Page Load Time**: < 3 seconds
- **Mobile Usage**: Optimize for 70%+ mobile traffic
- **Engagement**: Average session > 2 minutes

## 🔧 Development Guidelines

### Code Standards
- BEM naming convention for custom CSS
- Semantic HTML5 elements
- ARIA labels for accessibility
- Mobile-first media queries
- Component-based structure

### Image Optimization
- Use WebP format with JPEG fallbacks
- Implement responsive images with srcset
- Lazy load below-fold images
- Optimize file sizes < 200KB
- Use CDN for asset delivery

### Git Workflow
```bash
# Daily commits
git add .
git commit -m "feat: [component] - description"
git push origin main

# Feature branches
git checkout -b feature/hero-enhancement
git push -u origin feature/hero-enhancement
```

## 🎯 Today's Priority Tasks
1. Set up enhanced hero section with proper iSPEAK branding
2. Implement image optimization pipeline
3. Create interactive three pillars section
4. Add countdown timer for today's 10 AM EST event
5. Test mobile responsiveness thoroughly

## 📞 Contact & Support
- **Owner**: Daisy Ross
- **Email**: support@ispeaklanguage.org
- **Phone**: +1 (478) 390-4040
- **WhatsApp**: +1 (478) 390-4040

## 🔗 Important Links
- **GitHub Repo**: https://github.com/bakiel/ispeaklanguage-temp
- **Live Site**: https://ispeaklanguage.org
- **Design Reference**: Sample code provided in paste-2.txt
- **Brand Guidelines**: In development

---

## Next Steps
1. Review and approve this project guide
2. Set up task tracking system
3. Begin Phase 1 implementation
4. Daily progress updates
5. Weekly stakeholder reviews