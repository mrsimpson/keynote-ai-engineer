---
theme: apple-basic
title: Why AI Makes You More of an Engineer, Not Less
author: Oliver Jägle
info: |
  ## Why AI Makes You More of an Engineer, Not Less
  A keynote about the shift from "10x faster" to "10x enabled" - 
  how AI transforms impossible problems into possible solutions.
class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
aspectRatio: 16/9
canvasWidth: 980
fonts:
  sans: Inter
  serif: Inter
  mono: "Fira Code"
colorSchema: auto
---

# Why AI Makes You More of an Engineer, Not Less

<div class="text-2xl opacity-80 mb-4">From "10x Faster" to "10x Enabled"</div>

<div class="text-lg opacity-60">Oliver Jägle</div>

<style>
h1 {
  background: linear-gradient(45deg, #4f46e5, #06b6d4);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>

---
layout: image-lower-third
image: /02-lego-transformation.png
---

# Building stuff evolves

<!--
**Speaker Notes:**

"Dad, programming used to be like professional Lego building - you had to place every single piece yourself, right?"

"Now you just explain to the computer in German what you want to build, and it builds it like a Lego robot!"

She was right. But here's what I realized - I was completely wrong about what makes someone an engineer.

This conversation with my daughter made me realize that we're experiencing a fundamental shift in how we think about software development. But the real question isn't about the tools - it's about what makes us engineers in the first place.
-->

---
layout: image-lower-third
image: 04-10x.png
---

# The 10x Myth

<!--
**Speaker Notes:**

Everyone's talking about "10x developers"
- 10x faster coding
- 10x more productive  
- 10x better performance

But that's not what AI actually does. This whole conversation around "10x developers" misses the point entirely. We're measuring the wrong thing.

The tech industry is obsessed with efficiency metrics - story points, velocity, lines of code, commits per day. When AI came along, everyone immediately jumped to "10x faster development."

But here's the fundamental misunderstanding: The revolutionary value of AI can't be measured in simple efficiency gains.
-->

---

<style scoped>h1 {display: none}</style>

# The Real Shift

<div class="text-center mt-16">
<div class="text-6xl font-bold bg-gradient-to-r from-red-600 to-gray-600 bg-clip-text text-transparent mb-8">
10x Faster
</div>
<div class="text-2xl opacity-60 mb-16">vs</div>
<div class="text-6xl font-bold bg-gradient-to-r from-blue-600 to-green-600 bg-clip-text text-transparent">
10x Enabled
</div>
</div>

<!--
**Speaker Notes:**

AI doesn't make you 10x faster - it makes you 10x enabled.

The difference is crucial:
- 10x Faster = Speed-focused mindset, doing known tasks quicker
- 10x Enabled = Capability-focused mindset, solving previously impossible problems

This is the shift from "Unmöglich" to "Machbar" - from "Impossible" to "Possible."

The biggest impact of AI isn't making known tasks faster, but making the impossible possible. It's about expanding what we can achieve, not just how quickly we can achieve known things.
-->

---
layout: section
class: text-center
---

<div class="text-8xl font-bold bg-gradient-to-r from-orange-600 to-red-600 bg-clip-text text-transparent">
Stories
</div>

<!--
**Speaker Notes:**

Let me share three real examples of this 10x enabled effect from my own experience. These aren't about speed - they're about solving problems I couldn't even approach before AI.
-->

---
layout: image
image: /06-kalman.png
---

<style scoped>h1 {display: none}</style>

# The Jumping Train

<!--
**Speaker Notes:**

**Problem:** At DB Systel, I work with streaming train position data. GPS signals fail in workshops, causing trains to "jump" erratically on maps.

**Before AI:** I would have spent weeks researching academic papers about signal filtering, learning complex mathematical theories I'd never encountered.

**With AI:** I described the problem: "I need to smooth GPS data for trains that move on tracks." Claude introduced me to Kalman filters - something I'd never heard of. After understanding that trains move with high continuity and direction, we developed a directional Kalman filter.

**Result:** I solved a problem I didn't even know how to approach. This wasn't about coding faster - it was about accessing domain knowledge I never could have acquired on my own in a reasonable timeframe.

The image shows the before and after - erratic jumping signals smoothed into realistic train movement.
-->

---
layout: image  
image: /07-canvas-dnd.gif
---

<style scoped>h1 {display: none}</style>

# Canvas Magic

<!--
**Speaker Notes:**

**Problem:** For a personal project, I needed pixel-perfect QR code placement on images - something requiring HTML Canvas manipulation.

**Before AI:** I would have spent days going through Canvas tutorials, learning coordinate systems, understanding drag-and-drop mechanics from scratch.

**With AI:** Using bolt.new, I had a basic implementation in seconds. For the complex drag-and-drop functionality, Claude guided me through the Canvas API intricacies.

**Result:** I focused on the problem I was trying to solve, not the implementation details. The technology became a tool rather than a barrier.

This image shows the drag-and-drop interface we built - something that would have taken me weeks to figure out alone.
-->

---
layout: image-lower-third
image: /20-engineering-disciplines.png
---

# Engineering is ... Engineering

<!--
**Speaker Notes:**

It's not about speed - it's about expanding what's possible.

The skills that matter now:
- Problem identification - What are we actually trying to solve?
- Creative solution design - How might we approach this differently?
- Context Engineering - How do we provide the right information to AI systems?
- Understanding what you want to achieve - Clarity of purpose and goals

Traditional engineering was about understanding problems and finding solutions. This fundamental aspect hasn't changed.

What's changed is the partnership model. We're not being replaced - we're being amplified.
-->

---
layout: image-lower-third
image: /19-implementation-practice.png
---

# The New Partnership


<!--
**Speaker Notes:**

**Traditional Engineering:** Understanding problems + Finding solutions
**This hasn't changed.**

What's new is the partnership model:

**You bring:** 
- Engineering mindset - the ability to break down complex problems
- Problem context - understanding the real-world constraints and requirements  
- Workflow skills - knowing how to structure and approach development

**AI brings:**
- Implementation capability - the ability to write code, create solutions
- Domain knowledge - access to specialized knowledge across many fields
- Rapid iteration - the ability to quickly test and refine approaches

**Together:** Problems that seemed impossible become achievable. We're not talking about incremental improvements - we're talking about quantum leaps in what individual developers can accomplish.
-->

---
layout: section
class: text-center
---

<div class="text-8xl font-bold bg-gradient-to-r from-teal-600 to-green-600 bg-clip-text text-transparent">
Get started now!
</div>

<div class="text-8xl font-bold bg-gradient-to-r from-teal-600 to-green-600 bg-clip-text text-transparent">
No fear
</div>

<!--
**Speaker Notes:**

This brings me to engaging to all of you.
-->

---
layout: image-lower-third
image: /old-and-new-tools.png
---

# You've got skills – time for new tools

<!--
**Speaker Notes:**

Here's what I've learned: AI doesn't replace engineers - it gives us superpowers we never knew we needed.

If you're feeling uncertain about this change, that's completely normal. Every engineer I know has felt that way, including me.

But here's the beautiful thing: you already have the most important skill - you know how to solve problems.

You understand how to break down complex challenges, think systematically, and work toward solutions. These are the core engineering skills that matter most in an AI-enabled world.

Everything else - the specific technologies, the implementation details, even domain knowledge you don't have yet - we can learn together with AI as our partner.

The future belongs to engineers who embrace this partnership, who see AI not as a threat but as an amplifier of their existing problem-solving abilities.

Your engineering mindset is your superpower. AI just makes it possible to apply that mindset to problems you never thought you could tackle.
-->

---
layout: image
image: /25-questions.png
---

<!--
**Speaker Notes:**

Thank you for your attention. I'd love to hear about your own experiences with AI in development, or any questions you have about this shift from "impossible" to "possible."

Let's explore together what becomes achievable when we're 10x enabled.
-->