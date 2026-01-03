# The Website That Got Me Hired

> ⚠️ **Code is private (client confidentiality), but here's everything else about how I built it.**

## What Happened

A startup reached out asking for a basic 5-page website. They had barely any requirements — just "make something that works."

I could've given them exactly that. Instead, I spent 3 weeks building them a full production website with blogs, SEO, analytics, an AI chatbot, and a proper design system.

When I showed it to them, the founder said: *"I asked for A, but you gave me A+B=C."*

Two weeks later, they offered me a job as a Data Modeler and Software Engineer. I'm still there.

## What I Built

**Tech I used:**
- React 18 + TypeScript
- Vite (because Webpack is painfully slow)
- Tailwind CSS with custom design tokens
- Shadcn/UI for accessible components
- Framer Motion for animations
- Zod for form validation

**Pages (10 total):**
- Home, Services, About, Contact, Blog index
- 6 blog posts about AI, data engineering, ML, cloud, analytics, system design
- Privacy policy, terms of service, custom 404 page

**Features I added that they didn't ask for:**
- Full SEO setup (meta tags, sitemaps, structured data)
- Google Analytics 4 integration
- AI chatbot with 50+ questions answered across 11 categories
- Dark mode that follows system preferences
- Page transition animations
- Scroll progress indicator
- Contact form with proper validation
- Mobile-first responsive design
- Loading skeletons for better UX

## Why These Choices Mattered

**React + Vite instead of Next.js:**
They wanted simple hosting without dealing with servers. Vite gave them fast builds and easy deployment. Sometimes the simpler solution wins.

**Custom design system instead of Material-UI:**
Wanted the site to feel unique to their brand. Plus, the final CSS bundle was 40% smaller than if I'd used MUI.

**Pre-programmed chatbot instead of real AI:**
They didn't have budget for OpenAI API calls. Built a smart Q&A system that feels interactive but costs nothing to run. Works perfectly for their scale right now.

## The Technical Stuff

I set up code splitting so the initial load is fast. Each route lazy loads only when you need it. Images are optimized to WebP. The whole thing scores 95+ on Lighthouse for performance.

For SEO, I made sure every page has proper meta tags, Open Graph data for social media, and JSON-LD structured data. Built a sitemap generator. Basically made sure Google could actually find and rank their content.

The chatbot was fun to build — it's not actually AI, just a really well-organized set of responses with fuzzy matching. But users don't care about the implementation, they care that it works.

Dark mode was easier than expected. Used CSS custom properties with HSL values, so switching themes is just swapping a few color variables. Smooth.

## What This Taught Me

**About reading between the lines:**
They said they wanted a website. What they actually needed was credibility, discoverability, and a way to engage visitors. The website was just the tool.

**About scope creep (the good kind):**
Usually scope creep is bad. But strategic over-delivery? That's different. I didn't add features randomly — I added things that solved real business problems they hadn't articulated yet.

**About systems thinking:**
This project isn't just frontend work. It's thinking about SEO strategy, analytics, user behavior, business goals. That's the same kind of thinking I use now in data modeling.

## Screenshots
![hero-section](https://github.com/user-attachments/assets/093d6a98-3b11-4c6b-8087-f0ac2d95ed46)
![chatbot](https://github.com/user-attachments/assets/6cd3cc3b-1d8c-44e9-93e7-9da198c5ce09)
![blog-section](https://github.com/user-attachments/assets/04006da9-6506-4417-a688-a16fb52dfd4a)
![Interactive-diagram](https://github.com/user-attachments/assets/3a5cf8e5-c2a1-4387-bdf4-dc51b70ac9e7)
![Mobile-view-light mode](https://github.com/user-attachments/assets/fe4feb8b-98a1-494b-a5b7-6f92a6d75ca3)
![Mobile-View-dark mode](https://github.com/user-attachments/assets/e64592ad-25ff-4fee-bdb7-7148071a3a5c)

## How This Changed My Path

Before this project, I was a web dev intern. I built websites, fixed bugs, wrote SEO content, dealt with WooCommerce, handled spam issues — basically did whatever needed doing.

My 6-month internship got extended to 11 months because I kept taking on more responsibilities. Digital marketing, software testing, technical writing — I just kept saying yes to new challenges.

Then this project happened. I wasn't trying to change careers. I was just trying to build something good.

But over-delivering on this website proved something to them (and to myself): I could handle ambiguity, design systems, and deliver production-ready work independently.

That's exactly what data engineering needs. So now I'm building schema mapping tools, integrating databases like Snowflake and Databricks, and modeling data architectures.

Weird journey, but it makes sense somehow.

## What I'm Working On Now

- Schema mapping tool that's actually going to production
- AWS Solutions Architect certification (in progress)
- Data modeling using erwin
- Database integration systems

## The Part That Matters Most

This wasn't about knowing React really well or being some incredible developer. It was about understanding what the client needed before they knew it themselves.

That's the skill that's useful everywhere — in web dev, in data engineering, probably in whatever I do next.

If you're building something and wondering whether to add that extra feature or clean up that documentation or make that experience just a bit better — do it. Someone will notice.

---

**Built during my final year at Osmania University (8.5 CGPA). Probably drank too much coffee.**

## 💭 Frequently Asked Questions

**Q: Why can't you share the code?**
A: Client confidentiality agreement. However, I've documented architecture patterns and can discuss technical decisions in detail.

**Q: How long did this take?**
A: 3 weeks from requirement gathering to deployment.

**Q: What was the hardest part?**
A: Balancing feature richness with deadline constraints. I had to make conscious decisions about what would provide immediate value vs. what could be added later.

[LinkedIn](https://www.linkedin.com/in/farheen-sultana-54723a254/)  • [Email](Farheensultana0615@gmail.com)
