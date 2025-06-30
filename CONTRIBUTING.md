# Contributing to You Lie You Drink 🤝

Thank you for your interest in contributing to **You Lie You Drink**! This psychology-powered team building game thrives on community collaboration and diverse perspectives.

Whether you're a psychology researcher, UX designer, game developer, corporate trainer, or team building enthusiast, we welcome your contributions.

## 🌟 **Ways to Contribute**

### 🧠 **Psychology & Research**
- **Cognitive Bias Research**: Propose new psychological principles for game mechanics
- **Academic Citations**: Add research papers supporting game design decisions
- **Experimental Design**: Suggest A/B testing approaches for game effectiveness
- **Cultural Psychology**: Help adapt game mechanics for different cultural contexts

### 🎮 **Game Design & Mechanics**
- **New Round Ideas**: Design additional psychological rounds beyond the core 7
- **Corporate Scenarios**: Create industry-specific game content
- **Accessibility Features**: Improve game accessibility for diverse teams
- **Mobile Optimization**: Enhance mobile gameplay experience

### 💻 **Technical Development**
- **Real-time Multiplayer**: Help implement WebSocket/Firebase integration
- **Performance Optimization**: Improve loading times and responsiveness
- **Browser Compatibility**: Test and fix cross-browser issues
- **Progressive Web App**: Enhance PWA features and offline capability

### 🎨 **Design & User Experience**
- **Visual Design**: Improve UI components and visual hierarchy
- **User Research**: Conduct usability testing with corporate teams
- **Conversion Optimization**: A/B test landing page elements
- **Brand Development**: Expand visual identity and design system

### 📊 **Business & Product**
- **Market Research**: Analyze competitor features and pricing
- **User Personas**: Develop detailed corporate buyer profiles
- **Partnership Opportunities**: Identify potential business collaborations
- **Internationalization**: Help expand to global markets

---

## 🚀 **Getting Started**

### **1. Development Environment Setup**

```bash
# Clone the repository
git clone https://github.com/sree-pm/you-lie-you-drink.git
cd you-lie-you-drink

# Install development dependencies
npm install

# Start development server
npm start

# Open in browser
# http://localhost:3000
```

### **2. Project Structure Understanding**

```
you-lie-you-drink/
├── src/                    # Main application code
│   ├── index.html         # Landing page
│   ├── game.html          # Game interface
│   └── assets/            # CSS, JS, images
├── docs/                  # Product & technical documentation
├── research/              # Psychology research & market analysis
├── examples/              # Usage examples & demos
└── tests/                 # Testing suite (coming in v1.1)
```

### **3. Running Quality Checks**

```bash
# Code formatting
npm run format

# Code linting
npm run lint

# HTML validation
npm run validate

# Performance testing
npm run lighthouse
```

---

## 📋 **Contribution Process**

### **🔍 Before You Start**

1. **Check Existing Issues**: Browse [open issues](https://github.com/sree-pm/you-lie-you-drink/issues) to see if your idea already exists
2. **Read Documentation**: Review relevant docs in the `docs/` directory
3. **Understand Psychology Principles**: Familiarize yourself with the 7 cognitive biases we implement
4. **Review Corporate Focus**: Understand our target market (corporate team building)

### **📝 Types of Contributions**

#### **🐛 Bug Reports**
Use our [Bug Report Template](.github/ISSUE_TEMPLATE/bug_report.md)

**Required Information:**
- **Browser & Device**: Chrome 91, iPhone 12, etc.
- **Steps to Reproduce**: Detailed reproduction steps
- **Expected vs Actual**: What should happen vs what happens
- **Screenshots**: Visual evidence when applicable
- **Corporate Context**: If bug affects corporate team usage

#### **💡 Feature Requests**
Use our [Feature Request Template](.github/ISSUE_TEMPLATE/feature_request.md)

**Consider These Questions:**
- **Psychology Basis**: How does this feature leverage cognitive bias?
- **Corporate Value**: How does this benefit corporate teams?
- **User Research**: What evidence supports this need?
- **Implementation Impact**: Technical complexity and timeline

#### **🧠 Psychology Research Contributions**
- **Academic Sources**: Peer-reviewed research only
- **Practical Application**: How research translates to game mechanics
- **Cultural Considerations**: Cross-cultural validity of psychological principles
- **Ethical Guidelines**: Ensure user privacy and psychological safety

#### **🏢 Corporate Feature Development**
- **Enterprise Requirements**: Scalability and security considerations
- **Integration Needs**: Slack, Teams, HR platform compatibility
- **Data Privacy**: GDPR, CCPA compliance for corporate data
- **Customization Options**: Industry-specific adaptations

---

## 🛠️ **Development Guidelines**

### **📱 Code Standards**

#### **HTML/CSS**
```html
<!-- Use semantic HTML for accessibility -->
<section class="game-round" role="main" aria-label="Current Game Round">
  <h2 class="round-title">Round 1: First Impressions</h2>
  <!-- Structured, accessible markup -->
</section>
```

#### **JavaScript**
```javascript
// Use clear, descriptive function names
function calculateVulnerabilityScore(statements, playerChoices) {
  // Implement psychology-based scoring
  return score;
}

// Document cognitive bias implementation
/**
 * Implements Zeigarnik Effect by creating unfinished story tension
 * @param {string} incompleteStory - Player's interrupted narrative
 * @param {Array} completionOptions - Possible story endings
 * @returns {Object} Psychological engagement metrics
 */
```

#### **CSS Design System**
```css
/* Follow established color psychology system */
:root {
  --obsidian: #0D0D0F;        /* Authority, Mystery */
  --neural-gold: #D4AF37;     /* Achievement, Status */
  --cognitive-red: #DC2626;   /* Truth/Lie Tension */
  --trust-blue: #1E40AF;      /* Corporate Reliability */
}

/* Use consistent naming conventions */
.psychology-round {}
.corporate-feature {}
.ai-assisted-element {}
```

### **🧪 Testing Requirements**

#### **Psychology Validation**
- **A/B Testing**: Test psychological effectiveness of new features
- **User Research**: Corporate team feedback on game mechanics
- **Academic Review**: Expert validation of psychological principles

#### **Technical Testing**
- **Cross-Browser**: Chrome, Firefox, Safari, Edge
- **Mobile Responsive**: iOS Safari, Android Chrome
- **Accessibility**: Screen readers, keyboard navigation
- **Performance**: <2.5s load time, 95+ Lighthouse score

#### **Corporate Environment Testing**
- **Enterprise Networks**: Firewall and proxy compatibility
- **Security**: Data privacy and corporate compliance
- **Integration**: Slack, Teams, calendar applications

---

## 🎯 **Contribution Areas & Expertise Needed**

### **🧠 Psychology Research** *(Academic Background Preferred)*
- **Cognitive Science**: Understanding of bias mechanisms
- **Social Psychology**: Group dynamics and team behavior
- **Experimental Design**: A/B testing and validation methodology
- **Cultural Psychology**: Cross-cultural adaptation needs

### **💼 Corporate Experience** *(Business Background Helpful)*
- **HR/People Operations**: Team building program experience
- **Management Consulting**: Corporate training delivery
- **Organizational Psychology**: Workplace dynamics understanding
- **Sales/Business Development**: Enterprise software experience

### **🎮 Game Design** *(Gaming Industry Experience)*
- **Social Game Mechanics**: Multiplayer engagement strategies
- **Mobile Game UX**: Touch-first interaction design
- **Gamification**: Psychology-driven motivation systems
- **Narrative Design**: Storytelling in interactive experiences

### **💻 Technical Development** *(Software Engineering)*
- **Frontend**: Vanilla JS, Progressive Web Apps, WebSocket
- **Backend**: Node.js, real-time systems, database design
- **DevOps**: CI/CD, deployment automation, performance monitoring
- **Security**: Enterprise-grade security, privacy compliance

### **🎨 Design & UX** *(Design Background)*
- **Corporate UX**: Enterprise software design patterns
- **Conversion Optimization**: Landing page psychology
- **Accessibility**: WCAG compliance, inclusive design
- **Brand Design**: Professional visual identity systems

---

## 🔄 **Pull Request Process**

### **1. Preparation**
```bash
# Create feature branch
git checkout -b feature/psychology-round-8
# or
git checkout -b fix/mobile-safari-issue
# or  
git checkout -b docs/corporate-onboarding-guide
```

### **2. Development**
- **Follow Code Standards**: Use established patterns and naming
- **Add Documentation**: Update relevant docs for new features
- **Include Tests**: Add appropriate testing for changes
- **Psychology Validation**: Cite research for psychology-based features

### **3. Pre-Submission Checklist**

#### **✅ Code Quality**
- [ ] Code follows project style guidelines
- [ ] No console.log statements in production code
- [ ] Responsive design tested on mobile devices
- [ ] Accessibility guidelines followed (WCAG 2.1)

#### **✅ Psychology Integration**
- [ ] New game mechanics cite academic research
- [ ] Cognitive bias implementation is scientifically accurate
- [ ] User psychology is respected and ethical
- [ ] Corporate team dynamics considered

#### **✅ Documentation**
- [ ] README.md updated if needed
- [ ] CHANGELOG.md entry added
- [ ] Code comments explain psychology principles
- [ ] API documentation updated (future backend features)

#### **✅ Testing**
- [ ] Manual testing completed across browsers
- [ ] Mobile responsive testing done
- [ ] Performance impact assessed
- [ ] Corporate use cases validated

### **4. Pull Request Template**

Use our [Pull Request Template](.github/PULL_REQUEST_TEMPLATE.md) which includes:

- **Change Description**: What does this PR accomplish?
- **Psychology Basis**: What cognitive principles are involved?
- **Corporate Impact**: How does this benefit corporate teams?
- **Testing Done**: What testing was completed?
- **Screenshots**: Visual evidence of changes
- **Breaking Changes**: Any API or behavior changes

---

## 📚 **Resources for Contributors**

### **🧠 Psychology Research**
- [Cognitive Bias Codex](https://upload.wikimedia.org/wikipedia/commons/6/65/Cognitive_bias_codex_en.svg)
- [Psychology of Games Research](docs/psychology/research-papers.md)
- [Team Dynamics Studies](research/psychology/team-behavior.md)

### **💼 Corporate Team Building**
- [Corporate Market Analysis](research/market-validation/pricing-analysis.md)
- [User Personas](docs/product/user-personas.md)
- [Enterprise Requirements](docs/technical/enterprise-features.md)

### **🛠️ Technical Resources**
- [Architecture Documentation](docs/technical/architecture.md)
- [API Planning](docs/technical/api-documentation.md)
- [Performance Guidelines](docs/technical/performance-standards.md)

### **🎨 Design Resources**
- [Design System](docs/design/design-system.md)
- [Color Psychology](docs/design/color-psychology.md)
- [Corporate UI Patterns](docs/design/enterprise-ux.md)

---

## 🤝 **Community Guidelines**

### **🌟 Our Values**

#### **Science-Based Approach**
- All psychology features must cite peer-reviewed research
- Claims about team building effectiveness require evidence
- User privacy and psychological safety are paramount

#### **Corporate Professionalism**
- Communications should be enterprise-appropriate
- Features should enhance workplace relationships
- Business impact should be measurable and positive

#### **Inclusive Collaboration**
- Welcome contributors from all backgrounds
- Respect diverse perspectives on team dynamics
- Create safe spaces for idea sharing and feedback

#### **AI-Assisted Development**
- Embrace AI collaboration tools like Claude, GPT, etc.
- Document AI-assisted development processes
- Share effective prompting strategies with community

### **📞 Communication Channels**

- **GitHub Issues**: Bug reports, feature requests, technical discussion
- **GitHub Discussions**: General questions, psychology research, corporate use cases
- **Email**: reachme@sreedurairaj.com for sensitive or private matters
- **LinkedIn**: https://www.linkedin.com/in/sreedurairaj for professional networking and partnerships
- **Website**: https://sreedurairaj.com for portfolio and professional background

### **🎖️ Recognition**

Contributors are recognized in:
- **CHANGELOG.md**: Major contributions acknowledged in release notes
- **Contributors Section**: GitHub contributors automatically listed
- **Research Citations**: Academic contributors credited in psychology documentation
- **Corporate Case Studies**: Business contributors featured in success stories

---

## 📄 **Legal & Licensing**

### **Contributor License Agreement**
By contributing to this project, you agree that:
- Your contributions are your original work or properly attributed
- You grant the project maintainers rights to use your contributions under the MIT License
- You have the right to make the contribution (no employer restrictions, etc.)

### **Psychology Research Ethics**
- All user data must be anonymized and aggregated
- No personally identifiable information should be collected
- Corporate team data must be handled with enterprise-grade privacy
- Academic research must follow ethical guidelines for human subjects

### **Corporate Data Handling**
- Enterprise client data requires special handling procedures
- Custom corporate scenarios must maintain confidentiality
- Business intelligence must be anonymized before sharing

---

## 🚀 **Getting Help**

### **New Contributor Support**
- **Mentorship Available**: Experienced contributors available to guide newcomers
- **Documentation**: Comprehensive guides in `docs/` directory
- **Good First Issues**: Tagged issues perfect for first-time contributors
- **Pair Programming**: Remote collaboration available for complex features

### **Specialized Expertise**
- **Psychology Consultation**: Connect with academic advisors for research validation
- **Corporate Advisory**: Business professionals available for enterprise feature guidance
- **Technical Mentorship**: Senior developers available for architecture discussions

---

**Thank you for contributing to the future of psychology-powered team building! 🧠🎮**

*Together, we're transforming how teams connect, communicate, and collaborate through the power of applied psychology and modern technology.*

---

## 📈 **Contribution Impact Tracking**

We track contribution impact through:
- **User Engagement**: How features affect game completion rates
- **Corporate Adoption**: Enterprise team feedback on new features  
- **Psychology Effectiveness**: A/B testing of cognitive bias implementations
- **Technical Performance**: Load times, mobile compatibility, accessibility scores

Your contributions directly improve team dynamics for thousands of corporate users worldwide!
