Objective: to turn a SPA website into a 'one-button-one-page' html website.
Design Specifications
Header
● Dimensions: 3010px wide × 182px tall
● Background: Vibrant pink/magenta gradient (#D946EF to #C026D3)
● Screen width: 3456px total
● Left margin: 233px empty space
● Right margin: 233px empty space (3456 - 3010 = 446px total, split evenly)
● Content: "CallGenix | AI Decoded" title with logo on left side
● Logo: Circular emblem with geometric pattern
Navigation Sidebar
● Width: 302px
● Position: Left side, directly under header
● Button height: 200px each
● Background: Light blue/gray (#E5F3FF)
● Buttons: Vertically stacked navigation items
● Active state: Darker blue highlight
Navigation Menu Items:
1. About Me (default/home page)
2. Agentic Workflow
3. Running DeepSeek Offline
4. Scheduling Automation
5. OpenAI Operator
6. Desktop Workflows (RPA)
7. FAQ
8. Next on This Blog
Content Area
● Position: Right side of navigation
● Width: Remaining screen width minus sidebar (approximately 3154px)
● Background: White (#FFFFFF)
● Padding: Appropriate margins for readability
● Typography: Clean, modern font stack
Page Content Requirements
1. About Me (Homepage - index.html)
● Professional headshot image (left-aligned)
● Biography text describing IT career, entrepreneurship, and technical leadership
● Industry Experience: Telecoms, IoT/M2M, Software Development, eCommerce, Call Centers, Data Centers
● Areas of Expertise: Agile Product Development, Customer Engagement, Service Delivery, Team Leadership, Business Transformation
● Languages: English, Portuguese, Spanish, Intermediate Italian
● Personal interests: Tennis, family, astronomy, astrobiology
● LinkedIn connection section
● Footer tagline: "Focused, Guided, and Condensed Knowledge in AI Micro-Certs"
2. Running DeepSeek Offline
● Article about running LLM environments locally
● Technical specifications section:
○ NVIDIA GeForce RTX 3050 Ti Laptop GPU
○ 11th Gen Intel Core i9-11900H @ 2.50GHz
○ 32GB RAM
● Discussion of DeepSeek-R1 model
● Reference to foundational models (Alibaba's Qwen LLM, Meta's Llama LLM)
● Technical implementation details
3. FAQ Section
● Expandable/collapsible question format
● Topics include:
○ "Are Recruiters Secretly Testing Your GPT Skills?"
○ "Do LLMs dynamically add new knowledge?"
○ "LLMs, by Andrej Karpathy"
○ "What is Synthetic Data?" (expanded by default)
○ "LLMs trained by thousands of humans"
4. Additional Pages
Create placeholder content for remaining navigation items, maintaining consistent layout and styling.
Technical Requirements
HTML Structure
● Create separate HTML files for each navigation item
● Use semantic HTML5 elements
● Include proper meta tags for SEO
● Add Open Graph and Twitter Card meta tags
● Implement structured data markup where appropriate
CSS/Tailwind Styling
● Use Tailwind CSS for responsive design
● Maintain exact color scheme and spacing from original
● Implement smooth hover effects on navigation
● Ensure mobile responsiveness with appropriate breakpoints
● Use CSS Grid/Flexbox for layout management
JavaScript Functionality
● Minimal JavaScript for enhanced UX
● Smooth scrolling and transitions
● Active navigation state management
● Mobile menu toggle if needed
● No SPA routing - use traditional page navigation
Mobile Responsiveness
● Breakpoints: sm (640px), md (768px), lg (1024px), xl (1280px), 2xl (1536px)
● Navigation should collapse to hamburger menu on mobile
● Content should stack vertically on smaller screens
● Maintain readability and usability across all devices
● Optimize touch targets for mobile interaction
SEO Optimization
● Unique title tags for each page
● Meta descriptions (150-160 characters)
● H1, H2, H3 heading hierarchy
● Alt tags for all images
● Clean URL structure (/about, /deepseek-offline, /faq, etc.)
● XML sitemap generation
● Robots.txt file
Performance Requirements
● Optimize images (WebP format where supported)
● Minify CSS and JavaScript
● Implement lazy loading for images
● Use efficient font loading strategies
● Minimize HTTP requests
● Target Google PageSpeed score of 90+
File Structure
/
├── index.html (About Me)
├── agentic-workflow.html
├── deepseek-offline.html
├── scheduling-automation.html
├── openai-operator.html
├── desktop-workflows.html
├── faq.html
├── blog.html
├── assets/
│ ├── css/
│ │ └── style.css
│ ├── js/
│ │ └── main.js
│ └── images/
│ ├── logo.png
│ ├── headshot.jpg
│ └── [other images]
├── sitemap.xml
└── robots.txt
Brand Colors
● Primary Pink: #D946EF
● Secondary Pink: #C026D3
● Light Blue: #E5F3FF
● Navigation Active: #3B82F6
● Text Dark: #1F2937
● Text Light: #6B7280
● White: #FFFFFF
Final Deliverables
1. Complete HTML files for all pages
2. Consolidated CSS file with Tailwind classes
3. Minimal JavaScript file for interactions
4. Optimized image assets
5. SEO configuration files (sitemap.xml, robots.txt)
6. Documentation for deployment and maintenance
Success Criteria
● Pixel-perfect recreation of original design
● Full mobile responsiveness
● Fast loading times (<3 seconds)
● SEO-friendly structure
● Individual page URLs for direct linking
● Maintainable, clean code structure
