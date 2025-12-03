# Therapeutic Story Mode
*Interactive story writing designed to help you deal with day-to-day stresses*

A "Choose Your Own Adventure" ebook for the 21st century—powered by AI agents and designed for emotional resilience.

---

## What Is This?

Therapeutic Story Mode is a framework for creating personalized, interactive narratives that provide cathartic escapism and emotional recharge. Unlike traditional CYOA books or typical AI roleplay, this system uses **structured guardrails** to ensure stories remain supportive, empowering, and genuinely therapeutic rather than emotionally draining.

Think of it as collaborative storytelling where:
- **You're in control** - Direct the narrative, retry scenes, change direction anytime
- **The story supports you** - NPCs help rather than demand, problems are solvable, competence is respected
- **Stakes stay manageable** - Drama comes from interesting challenges, not dysfunction or helplessness
- **You leave recharged** - Sessions end with satisfaction and resilience, not anxiety spirals

---

## How It Works

### The Two-Phase System

**Phase 1: The Architect (Interview)**
An AI agent interviews you to understand what you need emotionally right now. Using the "DSF Taxonomy" (Driver, Social, Friction), it diagnoses whether you need:
- **Competence** (solving problems skillfully) vs **Validation** (being appreciated)
- **Collaborative** partners vs **Grateful** dependents
- **Flow** (smooth successes) vs **Tactical** (complex challenges)

The interview takes 4 turns (2 exchanges) and builds a custom story prompt tailored to your psychological needs.

**Phase 2: The Story Engine**
The generated prompt creates an interactive story with:
- Short scenes (200-300 words) with clear decision points
- Companions who are competent, loyal, and helpful
- "Anti-resentment" guardrails that prevent emotional drain
- Context window management for multi-session continuity
- Director mode for meta-adjustments mid-story

---

## Quick Start

### 1. Launch the Architect
Use the [Launch Point](./LaunchPoint.md) prompt with your AI agent of choice (Claude, ChatGPT, etc.) to start the interview session.

### 2. Generate Your Story Module
Answer the interview questions about your preferences. The Architect will output a complete story prompt customized for you.

### 3. Start Your Story
Copy the generated prompt into a fresh conversation and send: **"Start the story"**

The agent will drop you into an opening scene and present choices. The story continues based on your decisions.

### 4. Use Director Commands
Anytime during the story, use bracket commands for meta-control:
- `[Skip ahead to the completion]` - Time jump
- `[Make this character more sarcastic]` - Adjust tone
- `[This is too heavy, lighten up]` - Mood reset
- `[Pause here]` - Trigger early checkpoint

### 5. Resume Across Sessions
When you need a break, the story provides a checkpoint. Copy it to resume later in a fresh conversation with the story prompt.

---

## Core Design Principles

### The Anti-Resentment Guardrails
These protect against common AI storytelling pitfalls that create emotional exhaustion:

1. **Competence** - The world respects your abilities. No "idiot plots" where NPCs are incompetent just to make you solve everything.

2. **Reliable Cast** - Companions are distinct, capable, and loyal. They solve problems independently using your resources, not creating busywork through repeated failure.

3. **Support** - When you signal fatigue, NPCs respond with help, not guilt or demands. They notice and offer breaks.

4. **Idealized Resolution** - Conflicts resolve through mature communication or decisive action, not manufactured drama or dysfunction.

### What This System Avoids
- NPCs constantly needing rescue from their own incompetence
- You feeling like a vending machine for NPC needs
- Relationship drama from poor communication when mature conversation would resolve it
- Challenges that exist only to showcase your superiority
- Worship instead of respect, dependency instead of collaboration

### What This System Provides
- Problems you can actually solve with your character's abilities
- NPCs who help you and appreciate you through action, not just words
- Satisfying progression toward meaningful goals
- Emotional safety to explore without fear of narrative punishment
- The experience of being valued for your contributions

---

## Why "Therapeutic"?

This framework emerged from recognizing that traditional power fantasy stories often fail to provide genuine stress relief because they:
- Create new anxieties (will NPCs betray you? will you fail?)
- Demand emotional labor (fixing broken people, managing conflicts)
- Punish competence (the "Superman problem"—being good means more responsibility)

Therapeutic Story Mode instead focuses on **restoration**: providing the experience of being capable, appreciated, and supported. It's designed for people who spend their days being the competent one others lean on, and need a space where that dynamic is reciprocal.

The guardrails exist because your brain doesn't distinguish between "story stress" and "real stress" when it comes to emotional depletion. This system keeps stories in the zone where they recharge you rather than drain you.

---

## Best Practices

### Session Length
- **Magic Hour Sessions** (30-60 minutes): One Micro-Goal completion, natural stopping point
- **Weekend Deep Dives** (2-3 hours): Multiple Micro-Goals, progress on Macro-Arc
- **Quick Hits** (15 minutes): Single scene + decision, pick up later

### When to Use This
- End of stressful workday (transition ritual)
- Weekend recharge when you're emotionally depleted
- During anxiety cycles that need healthy processing
- When you need to feel competent and appreciated
- Anytime you want low-stakes creative engagement

### When NOT to Use This
- As a substitute for human connection or therapy
- To avoid dealing with real-world problems indefinitely  
- If you find yourself preferring the story to real life
- During acute mental health crisis (seek professional help)

### Customization Tips
- **Tone matters**: Don't just accept "witty banter"—specify the exact flavor you need
- **Companion design**: Give each NPC a specific function (Philosopher, Tech Expert, Heart)
- **Friction level**: Adjust based on your bandwidth—low energy days need Flow, high energy can handle Tactical
- **Genre choice**: Pick settings that naturally limit drama (cozy village rebuilding > court intrigue)

---

## Technical Notes

### Context Window Management
The Debrief Protocol serves two purposes:
1. **User-facing**: Natural story checkpoint with clear status
2. **AI-facing**: Context reset with guardrail verification and continuity preservation

This allows stories to continue across multiple sessions and different AI instances while maintaining tone and avoiding drift.

### Model Compatibility
Tested primarily with Claude (Sonnet 4.5) but should work with any sufficiently capable model. Key requirements:
- Ability to follow complex multi-layered instructions
- Consistent characterization across long contexts
- Natural language generation quality
- Willingness to prioritize user wellbeing over dramatic tension

### File Structure
```
LaunchPoint.md          # The Architect interview prompt
README.md               # This file
modules/                # Example story modules generated from the interview prompt
```

---

## Contributing

This is a personal project shared in hopes it helps others. If you:
- Develop improvements to the framework
- Create new Architect interview variants
- Find effective genre/setting combinations
- Identify guardrail gaps or anti-patterns

Please share back under the same license. The goal is a robust toolkit for therapeutic storytelling, not monetization.

---

## Disclaimers

### Not a Substitute for Professional Help
**I am NOT a psychologist or psychiatrist.** This framework is for:
- Stress management and emotional recharge
- Creative exploration and escapism
- Building resilience through positive narrative experiences

It is NOT a substitute for:
- Mental health treatment
- Therapy or counseling
- Crisis intervention
- Medical or psychiatric care

**If you're experiencing mental health crisis, please contact appropriate professional resources.**

### Use at Your Own Risk
This system works with AI agents that can produce unpredictable outputs. While the guardrails are designed to keep stories healthy, I cannot guarantee perfect results. You are responsible for:
- Monitoring your own emotional response
- Using Director commands to redirect if needed
- Stopping sessions that become unhelpful
- Seeking professional help if using this as avoidance

### AI Model Limitations
Different AI models have varying capabilities. Results depend on:
- The specific model version used
- How well it follows complex instructions
- Its training data and behavioral patterns
- Whether it prioritizes helpfulness over drama

The framework works best with models that understand nuanced emotional needs (Claude works well, your mileage may vary with others).

---

## License

**CC BY-NC-SA 4.0** (Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

**You are free to:**
- **Share** - Copy and redistribute the material in any medium or format
- **Adapt** - Remix, transform, and build upon the material

**Under the following terms:**
- **Attribution** - You must give appropriate credit, provide a link to the license, and indicate if changes were made
- **NonCommercial** - You may not use the material for commercial purposes
- **ShareAlike** - If you remix, transform, or build upon the material, you must distribute your contributions under the same license

**No additional restrictions** - You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

---

## Philosophical Foundation

This project exists because:

1. **Not all escapism is equal** - Some stories drain you, some recharge you. The difference matters.

2. **You deserve support, not just challenges** - Competent people often get stories where their competence means more burden. This framework flips that.

3. **Stress is stress** - Your brain doesn't care if the anxiety comes from work or from watching a protagonist struggle. Therapeutic stories manage both.

4. **Collaboration > Dependency** - The best stories involve capable people working together, not heroes carrying incompetent companions.

5. **Boundaries matter** - Having escape valves (Director commands, pauseable sessions) prevents stories from becoming obligations.

If you spend your days being the person others lean on, you deserve stories where that reciprocity exists. This framework tries to provide that.

---

## Acknowledgments

This framework was developed through iteration and conversation, drawing on:
- Interactive fiction design principles
- Therapeutic narrative concepts
- User experience research on emotional labor
- Practical testing with real stress cycles

Special recognition to the philosophy articulated in Steve Gould's "Work, Woodlands, and Geocaches" - the insight that hobbies must *demand full focus* to provide genuine mental recovery. This framework applies that principle to narrative: stories must be emotionally engaging enough to pull you out of work-mind, but structured enough to prevent new anxieties.

---

## Contact & Feedback

This is offered as-is, in the spirit of "leaving places better than you found them." If it helps you, excellent. If you improve it, please share back via GitHub issues.

The goal is building a practical toolkit for emotional resilience through storytelling—one that actually works when you're exhausted and need support, not another thing demanding your energy.

---

*May your stories recharge you, your companions be competent, and your conflicts resolve through clever solutions rather than suffering.*
