# Module 3: Custom Skills 🏭
### *The Power of the Agentic Forge*

Hey AI Tech Enthusiast! Allen here. 🤜🤛

In the last module, you witnessed the **"First Magic"**—the native agentic behavior that lets Claude research your world autonomously. 

But if you want to scale, you need **Agentic Acceleration.** Custom skills are your "System Blueprints"—they allow you to repeat complex processes without re-writing the instructions every single time. This is where Claude Code truly shines.

## 🎨 Section 1: The Vibe-to-Skill Philosophy
Before we build our automation factory, we need to understand the two phases of creation:

### 1. Natural Language (Vibing) 🎨
**Vibing** is using your own words to explore new ideas. It allows for creative flexibility and "feeling" your way through a problem. It is the best starting point for anything creative.

### 2. Hardened Skills 🛡️
Once you find yourself repeating a task 10 times, you "harden" that Vibe into a **Skill.** 

---

## 🏗️ Section 2: The Walkthrough (From Vibe to Skill)
Let's walk through how you actually build your "Employee" library.

### Step 1: The Vibe (Testing)
You have a bunch of messy research notes. You talk to the AI naturally:
> *"Hey, can you read my notes in `/input` and find some viral hooks? Use dad jokes and analogies."*

### Step 2: The Decision
The AI gives you a perfect result. You realize: *"I'm going to need to do this every Monday morning for the next year."* Instead of typing that long prompt every week, you decide to **Harden** it.

### Step 3: The Save (Forging the Skill)
You don't need to touch a single line of code. Just tell the AI:
> *"I love that logic. Save it as a skill called `/ideate-niche` in my `CLAUDE.md` file."*

The AI will surgically update your brain for you. Open [**`CLAUDE.md`**](../CLAUDE.md) afterward to confirm the "Engine Room" has been updated correctly.

### Step 4: The Action (Using the Skill)
Now, next Monday, you don't talk to me. You just type:
```bash
/ideate-niche [Source]
```
The AI instantly triggers the exact logic you saved. **Always specify a source (like `/input`) for it to apply its magic to.** If you don't provide a source, the AI will default to the directory specified in the skill definition (in this case, your `/input` folder).

---

## 🏗️ Section 3: The "Big Five" Production Line
We are going to build your first five automated employees. These capture your precise **preferences and constraints** so you can auto-accelerate your repeatable workflows.

### 1. `ideate-niche` (The Spark) ⚡
- **Vibe Kickstart**: *"Look at my messy notes in `/input` and find the 5 most viral hooks. Use dad metaphors."*
- **Save Skill**: *"Save that as a skill called `/ideate-niche` in my `CLAUDE.md`."*
- **Use it again next time**: Run `/ideate-niche [Source]`. Specify the folder or file for it to apply its magic to. If no source is provided, it will default to the `/input` directory defined in the skill.
- **Result**: [**`ideate-niche_output.md`**](../course_example_files/output/03_acceleration_with_skills/ideate-niche_output.md)

### 2. `script-it` (The Writer) ✍️
- **Vibe Kickstart**: *"Take Hook #2 and turn it into a 60-second video script and a Substack draft."*
- **Save Skill**: *"Save that as a skill called `/script-it` in my `CLAUDE.md`."*
- **Use it again next time**: Run `/script-it [Source]`. Specify the hook or idea to process. If no source is provided, it will default to the most recent content in your chat history.
- **Result**: [**`script-it_output.md`**](../course_example_files/output/03_acceleration_with_skills/script-it_output.md)

### 3. `multiply` (The Distributor) 📢
- **Vibe Kickstart**: *"Turn this script into 5 tweets, a LinkedIn post, and 3 IG Reel hooks."*
- **Save Skill**: *"Save that as a skill called `/multiply` in my `CLAUDE.md`."*
- **Use it again next time**: Run `/multiply [Source]`. Specify the input source to instantly fragment one idea. If no source is provided, it will default to the most recent script in your chat history.
- **Result**: [**`multiply_output.md`**](../course_example_files/output/03_acceleration_with_skills/multiply_output.md)

### 4. `audit-voice` (The Humanizer) 🧔
- **Vibe Kickstart**: *"This script sounds too corporate. Strip the AI-bias and make it sound like AITechDad."*
- **Save Skill**: *"Save that as a skill called `/audit-voice` in my `CLAUDE.md`."*
- **Use it again next time**: Run `/audit-voice [Source]`. Specify the source to keep your brand voice "Hardened." If no source is provided, it will default to the most recent draft in your chat history.
- **Result**: [**`audit-voice_output.md`**](../course_example_files/output/03_acceleration_with_skills/audit-voice_output.md)

### 5. `viral-bridge` (The Closer) 🤜🤛
- **Vibe Kickstart**: *"Connect this content to the ViralSpin Ecosystem. We may have offer a free resource via our Resource Hub at https://www.viralspin.ai/resources or a paid resource like our Vibe Coding Course at https://www.viralspin.ai/vibe."*
- **Save Skill**: *"Save that as a skill called `/viral-bridge` in my `CLAUDE.md`."*
- **Use it again next time**: Run `/viral-bridge [Source]`. Specify the source to bolt on your conversion engine. If no source is provided, it will default to the most recent content in your chat history.
- **Result**: [**`viral-bridge_output.md`**](../course_example_files/output/03_acceleration_with_skills/viral-bridge_output.md)

---

## 🔥 Section 4: Acceleration
Once these skills are saved, your content creation becomes a **10-minute checklist.** You are following a **Hardened Logic Trap** that ensures completeness and probability of success every time you launch a new idea.

**This is how you build a "One-Person Empire" with zero overhead.**

---

## 🔁 Section 5: The Power of the Infinite Loop
The result may alter based on your new ideas, but the **Process** is now a perfect constant. You never have to re-explain your brand to your AI ever again.

**Ready to start Vibe-Coding your brand's permanent home?**
👉 [**Module 4: Visual Vibe-Building**](04_visual_vibe_building.md)
