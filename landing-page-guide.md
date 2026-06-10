# How to Build the GN Alumni Annual Event Landing Page
### Step-by-Step Guide Using Claude Tools

---

## What This Page Is

A landing page for **Genius Network alumni** to learn about and register for the Annual Event (November 5–7, 2026, Scottsdale, AZ) at a special Alumni Rate of $10,000. Joe's letter is already written. A QR code on the physical mailer will link here.

**What you have:** Joe's letter (copy is done)
**What you still need:** The registration/payment link (to be provided later — use a placeholder for now)

---

## Tools You'll Use

| Tool | Purpose |
|---|---|
| **Claude Cowork** | Build the actual HTML landing page |
| **Claude Design** (Cowork plugin) | Review the page for UX, layout, and readability |
| **Claude in Chrome** | Preview the live page and check it on mobile |

> **Before you start:** Make sure the Claude Design plugin is installed in Cowork. Get it at [claude.com/plugins/design](https://claude.com/plugins/design).

---

## Step 1: Build the Landing Page in Cowork

Open Cowork and paste this prompt. The full letter copy is already included so Claude can build it immediately.

> **Prompt — copy and paste this exactly:**
>
> "Build me a clean, professional HTML landing page for a Genius Network alumni event invitation. Use a dark, premium feel — dark navy or charcoal background, gold accents, elegant serif font for the letter, clean sans-serif for buttons and headers.
>
> The page should include:
> - A simple header with the Genius Network logo (use a placeholder if needed)
> - A personal letter from Joe Polish (full text below)
> - A prominent CTA button that says 'Register at the Alumni Rate' linking to: ALUMNI-LINK-HERE
> - The event details clearly visible: November 5–7, 2026 | Scottsdale, Arizona
> - A clean footer
>
> Make it mobile-friendly. Here is the full letter:
>
> ---
> Dear [First Name],
>
> A few years ago, I started asking myself a simple question: What makes certain experiences stay with us long after they're over? It's usually not the venue. It's not the food. It's not even the speakers. It's the people. It's the conversations that change how you think. The relationships that turn into friendships. The introductions that lead to opportunities, partnerships, and every once in a while, sometimes even life-changing breakthroughs.
>
> That's what I've always wanted Genius Network and the Annual Event to be. And when I think about the people who've helped make it that way over the years — you're one of them. Which is exactly why I wanted to send you a copy of We Are As Gods, the new book by my dear friends Peter Diamandis and Steven Kotler. Peter and Steven have spent decades exploring human potential, innovation, abundance, and what becomes possible when people decide to play a bigger game. This book may be one of their most thought-provoking works yet.
>
> And here's the fun part — both of them are joining us live at this year's Genius Network Annual Event, November 5–7, 2026, in Scottsdale, Arizona. I'll be interviewing them on stage — digging into the ideas in the book, what they see coming next, and what it actually takes to thrive in a world that's moving this fast.
>
> As I was putting the guest list together this year, I kept thinking about the incredible people who've been in that room before. People like you. The truth is I don't think of you as a former attendee. I think of you as part of the extended Genius Network family. And I'd love the chance to reconnect.
>
> So I want to personally invite you back to this year's Annual Event at a special Alumni Rate. Not because I need another seat filled. Because I genuinely value the people who've been part of Genius Network over the years — and because I've seen, again and again, what happens when great people get back in the same room together.
>
> The world is moving faster than ever. AI is changing everything. Business models are being rewritten in real time. Opportunities are everywhere. But one thing hasn't changed: who you surround yourself with still matters. And now, maybe more than ever.
>
> I hope you enjoy the book. I hope it sparks something. And most of all, I hope you'll think about joining us this year so we can keep the conversation going in person.
>
> Best,
> Joe
>
> P.S. As you're reading We Are As Gods, picture the conversations we'll be having live with Peter and Steven at the Annual Event, November 5–7, 2026, in Scottsdale, Arizona. I'd love to welcome you back at the special Alumni Rate. For more details or to officially register, simply click the button below.
> ---
>
> Save the file as alumni-event-2026.html"

Cowork will generate the file and save it to your outputs folder.

---

## Step 2: Review the Page with Claude Design

Once the page is built, ask Claude Design to review it:

> **Prompt:**
> "Review this landing page for a high-end event invitation. The audience is successful business people and former event attendees. Check: Is the layout easy to read? Does the CTA stand out? Does the design feel premium and trustworthy? Is there anything that could cause confusion or make someone hesitate to register? Give me specific suggestions."

Apply any changes Claude suggests:

> **Prompt:**
> "Make these changes to the page: [paste Claude Design's suggestions]"

---

## Step 3: Preview the Page in Claude in Chrome

Open the saved HTML file in Chrome, then ask Claude in Chrome:

> **Prompt:**
> "Look at this page and tell me: How does it look on mobile? Is the button easy to find? Does anything look broken or off?"

If anything needs fixing, go back to Cowork:

> **Prompt:**
> "The [button / header / spacing] looks off on mobile. Fix it."

---

## Step 4: Add the Real Payment Link (When Ready)

When Eunice sends you the registration/payment URL, open the file in Cowork and say:

> **Prompt:**
> "Replace every instance of ALUMNI-LINK-HERE with this URL: [paste the real link]"

---

## Step 5: Get the URL to Randy

Once the page is live (hosted somewhere), copy the URL and send it to Randy so she can generate the QR code.

If you need help getting it hosted, use Claude Code:

> **Prompt:**
> "I have an HTML file called alumni-event-2026.html. Help me deploy it to Netlify so I get a live URL."

---

## Quick Reference

| What You Need | Prompt Starter |
|---|---|
| Build the page | "Build a clean, professional HTML landing page..." (see Step 1) |
| Review the design | "Review this landing page for a high-end event invitation..." |
| Fix mobile issues | "The [element] looks off on mobile. Fix it." |
| Swap in the real link | "Replace every instance of ALUMNI-LINK-HERE with: [URL]" |
| Deploy and get a URL | "Help me deploy alumni-event-2026.html to Netlify." |

---

## Checklist Before Sending URL to Randy

- [ ] Joe's full letter is on the page
- [ ] CTA button is visible and working
- [ ] Event details correct: November 5–7, 2026 | Scottsdale, AZ
- [ ] Real payment link has replaced ALUMNI-LINK-HERE
- [ ] Page looks good on mobile
- [ ] URL is live and working
