# Module 3: The Sequential Skill-Stack 🏗️
### *Building Your Automation Pipeline*

Hey Creator! AITechDad here. 🤜🤛

Slash commands like `/explain` are built-in, but the *real* power of Claude Code is creating your own **Custom Skills**. 

**The "Pro" Way to Build Skills:**
Instead of jamming giant prompts into your `CLAUDE.md` (which can get cluttered), we use the **"Brain & Library"** architecture:
1.  **CLAUDE.md (The Brain)**: Stores your persona and an *index* of your skills.
2.  **/skills/ (The Library)**: A dedicated folder where each skill gets its own file with deep, multi-step instructions.

Today, we're building a 5-part production engine using this modular system.

---

## 📱 The "Smartphone vs. Apps" Metaphor
Before we build, you might wonder: *"Why not just put everything in CLAUDE.md?"* Think of it like this:

- **CLAUDE.md is your OS Settings**: It’s your brand's "Operating System." It stores your voice, your name, and your global goals. It applies to *every* chat.
- **The `/skills` folder is your App Library**: These are the tools (the "Apps") you only open when you need them. You wouldn't want the entire code for Instagram and Excel baked into your phone's settings menu, right?

**Why the modular way wins:**
1. **Speed**: It keeps Claude's "working memory" focused on the task at hand.
2. **Portability**: You can drag-and-drop your skill library into any new project instantly.
3. **Clarity**: It stops your `CLAUDE.md` from becoming a giant, unreadable mess.

---

## 🛠️ Step 1: Create Your Library
First, we need a place for our skills to live.
Run this in your terminal:
```bash
mkdir skills
```

---

## 🛠️ Step 2: Build Your First Elaborate Skill
Let's build the **`ideate-niche`** skill—this is where your content engine starts. It takes your messy notes and finds the high-signal hooks.

**Run this command to create the skill file:**
```bash
claude "Create an elaborate skill file at skills/ideate-niche.md for finding spicy, on-brand hooks. It should analyze my project files, identify a core insight, and generate 5 hook ideas using my AITechDad persona. Ensure each hook has a 'Curiosity Gap' to drive engagement."
```

---

## 🛠️ Step 3: Link it to the "Brain"
Finally, we need to tell Claude where to find it.

**Run this:**
```bash
claude "Update my CLAUDE.md to include a 'Custom Workflows' section. For the 'ideate-niche' skill, tell yourself to always read skills/ideate-niche.md before executing."
```

---

## 🏗️ Step 4: Filling the Library
Now that you have the spark, let’s build the rest of your **Production Engine:**

**1. The Script Engine (`script-it`)**
```bash
claude "Create an elaborate skill file at skills/script-it.md. This skill turns a hook into two assets: a punchy 60s video script (with timestamps) and a value-packed newsletter draft. It must use my brand voice from CLAUDE.md and include a 'Logic Check' step to strip out any buzzwords like 'unleash' or 'delve'."
```

**2. The Multiplier Engine (`multiply`)**
```bash
claude "Create an elaborate skill file at skills/multiply.md. This skill atomizes a script into a distribution bundle. It must generate: 1 LinkedIn post, a high-converting 8-tweet X thread, and 5 short-form video hooks. Use my AITechDad voice."
```

**3. The Brand Guardian (`audit-voice`)**
```bash
claude "Create an elaborate skill file at skills/audit-voice.md. This skill analyzes any draft for 'AI Buzzwords' (delve, tapestry, etc.) and replaces them with my 'AITechDad' voice. It ensures the tone is approachable but authoritative."
```

**4. The Monetizer (`viral-bridge`)**
```bash
claude "Create an elaborate skill file at skills/viral-bridge.md. When I run it on a piece of content, it should identify the core insight and draft a 'Soft CTA' that connects that insight into my free lead magnet."
```

**5. Link them all:**
```bash
claude "Update my CLAUDE.md to include pointers for all my new skills in the /skills directory."
```

---

## 🏎️ The "Alpha Loop" in Action
Now that Claude knows your skills, you can call them sequentially. This is the **Perfect Production Loop** that will save you 15+ hours a week:

1. **Ideate**: `claude ideate` ➔ Pick your winning hook.
2. **Script**: `claude script "[MY HOOK]"` ➔ Turn idea into asset.
3. **Audit**: `claude audit-voice` ➔ Ensure it sounds 100% like you.
4. **Multiply**: `claude multiply` ➔ Shred it for all social platforms.
5. **Bridge**: `claude viral-bridge` ➔ Find the natural pitch for your product.

---

## ✅ Exercise: Run the Full Loop
Try running all five skills in order. Watch how the chaos of a raw idea becomes a professional, branded content bundle in under 2 minutes.

**Want to see what the "Correct Answer" looks like?** 
- **Step 1 (Ideate)**: [**`ideate-niche_output.md`**](samples/output/03_sequential_skills/ideate-niche_output.md)
- **Step 2 (Script)**: [**`script-it_output.md`**](samples/output/03_sequential_skills/script-it_output.md)
- **Step 3 (Audit)**: [**`audit-voice_output.md`**](samples/output/03_sequential_skills/audit-voice_output.md)
- **Step 4 (Multiply)**: [**`multiply_output.md`**](samples/output/03_sequential_skills/multiply_output.md)
- **Step 5 (Bridge)**: [**`viral-bridge_output.md`**](samples/output/03_sequential_skills/viral-bridge_output.md)

---

## 🔁 The Power of the Infinite Loop
You’ve just built more than a few files. You’ve built a **Repeatable Production Line.**

Here is the secret to scaling as a solo creator: **Consistency without Cognitive Load.**

### 1. Zero Instruction Overhead
Every day (or every week) when you start a new content cycle, you don't have to re-explain your brand, your thread length, or your newsletter formatting. The "Big Five" skills in your `/skills` folder remember it all for you. 

### 2. The One-Command Factory
For every new idea, you simply run the cycle again:
1. `ideate` ➔ 2. `script` ➔ 3. `multiply` ➔ 4. `audit` ➔ 5. `bridge`.

### 3. Structural Consistency
Whether it's Monday morning or Friday night, your content will have the same high-signal "Allen" voice and the same premium structure. You are no longer "writing from scratch"; you are **Orchestrating a System.**

---

**Ready to get visual? Let's build a home for all this content.**
👉 **[Module 4: Website Vibe-Building](04_website_vibe_building.md)**
