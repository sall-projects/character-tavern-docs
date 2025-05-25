---
title: Memory | Character Tavern
sidebar_label: 🧠 Chat Memory & Tools
sidebar_position: 3
description: Sal breaks down Character Tavern's chat memory & instruction tools—Smart Context, Infinite Memory, Memory Snippet, & Summaries—for immersive AI roleplays.
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

# Memory & Instructions: Keeping Our Conversation Alive & On Track

Hey everyone, Sal here again! For truly amazing chats with AI characters (our 'Cards') on Character Tavern, two things are key: how the AI *remembers* your ongoing conversation and how you can *guide* its behavior.

## Core Memory Systems

Let's first look at the **core memory systems** that help characters recall your shared history. It's important to know that **you don't manually choose between these for a chat; the specific AI model you've selected is inherently designed to use one of these systems (either Smart Context or Infinite Memory).** This is applied automatically by the model itself to ensure the best possible memory performance for its architecture.

<Tabs groupId="core-memory-systems">
  <TabItem value="smart-context" label="🧩 Smart Context">

First up is **Smart Context**. Think of this as my clever little assistant for managing chat memory super efficiently for certain models. I designed it to get the best performance out of the AI while also being smart about how much data is flying back and forth.

Here's the gist from my end:
* **Intelligent Optimization:** Smart Context isn't just about sending a wall of text to the AI. I've programmed it to look at your conversation and prioritize the bits that are most important for keeping the chat coherent, on-topic, and engaging for the next reply.
* **Balancing Act:** It's all about finding that sweet spot between giving the AI enough context for a rich, memorable conversation and not overloading the system (or your wallet, if you're using models with per-token costs!). This helps keep everything running smoothly.

Essentially, Smart Context is my way of trying to ensure the AI has the crucial parts of your chat history ready to go, without it getting bogged down in every single detail from hours ago. Models designed with Smart Context handle this prioritization automatically.

  </TabItem>
  <TabItem value="infinite-memory" label="♾️ Infinite Memory">

Then we have **Infinite Memory** – this is my premium approach used by other models, and I'm pretty proud of how it's turned out! I designed this to make your conversations feel like they can go on practically forever without the AI forgetting those crucial plot points or character developments. It's a two-pronged system I cooked up that really pushes what the AI can recall.

Here's how I've set it up for models that use Infinite Memory:

1.  **Using the Full Context Window:** I noticed some platforms might unnecessarily limit how much of your chat history actually gets sent to the AI, even if the AI model itself could handle way more. With Character Tavern, I've made sure models with Infinite Memory strive to use the *entire* available context window. So, if a model supports a massive 128K context (that's a lot of text!), my system aims to fill that space if your conversation is long enough. For most chats that naturally stay under these large limits, this means pretty much *everything* you've discussed gets sent to the AI.

2.  **Smart Optimizations When You Go REALLY Long:** Now, what happens if your epic story *does* somehow go beyond even these huge context limits? That's where what I like to call the "true magic" of Infinite Memory kicks in. Instead of just bluntly chopping off the oldest parts of your conversation, the system intelligently optimizes what gets sent to the AI.
    * It tries to identify and compress parts of the conversation that the AI might struggle with if they were too far back, or parts that have less immediate impact on what the AI should say next.
    * I'm also using various other optimization techniques behind the scenes to condense the information, always trying to make sure the most important points are retained.

My goal with Infinite Memory is to make it *feel* genuinely limitless for the vast majority of your interactions with models that support it. I've designed it to be significantly more effective – think up to 10 times more – than Smart Context at preserving your chat history for those super long, in-depth roleplays.

  </TabItem>
</Tabs>

---

## Additional Memory Features & Tools

Beyond the core, automatic memory systems tied to the models, Character Tavern also offers tools that give *you* more direct control over guiding the AI and managing key information. You'll typically find these in your chat's **Top Right Menu > Memory Settings**.

### 📝 Memory Snippet (Instructions)

Sometimes you need to give the AI specific, short-term instructions or reminders for the current flow of conversation. That's where the **Memory Snippet** comes in! Think of it like a director's note to an actor for the current scene.

**(Image like the one you provided for Memory Snippet could be embedded here if your Docusaurus setup allows, e.g., `![Memory Snippet UI](./path/to/image_73aed4.png)`)**

**What is it?**
The Memory Snippet is a tool that lets you add special instructions or context that will be considered by the AI for its upcoming responses. It's great for guiding style, tone, or temporary situational details.

**Key Features:**

* **Instruction Box:** A simple text area where you can type your instructions. For example:
    * `[Speak in a tired, exhausted way and keep responses short]`
    * `[Focus on describing the snowy weather outside]`
    * `[{{char}} is currently suspicious of {{user}}]`
* **Use Smart Placement:** When this option is checked (recommended!), Character Tavern will intelligently try to place your snippet into the prompt where it will be most effective for influencing the AI's next reply.

**Common Use Cases:**

* **Guiding Response Style/Tone:**
    * `[Write your next reply in a very formal and polite manner.]`
    * `[Keep your responses under 50 words for this exchange.]`
* **Reinforcing Temporary States or Actions:**
    * `[Remember that {{user}} just handed you a mysterious map.]`
    * `[{{char}} is trying to hide their fear.]`
* **Quick Reminders (not for permanent lore):**
    * `[It's nighttime and very dark.]`

The Memory Snippet is designed for these kinds of immediate, contextual nudges.

### 📋 Manual Summaries (Alpha)

Another tool available in your chat's **Top Right Menu > Memory Settings** is the **Manual Summarization** feature. This is designed to help you keep track of long, evolving narratives by creating your own notes.

**Big Heads Up:** This feature is currently in its **Alpha** phase. That means it's brand new, and I'm still actively working on it. Your experiences and honest feedback are GOLD to me as I polish it up!

**Crucial Detail for Now:** These manual summaries are **only compatible if you have my "Smart Prompt" feature enabled**.

**What is it?**
Think of it as your personal notebook for the chat – a way to jot down key takeaways, plot twists, or important character notes. This helps ensure both you and the AI can recall crucial information, especially during those marathon chat sessions.

**What You Can Do with Summarization (Currently v2 Alpha):**

* **Get an AI Assist:** You can have the AI generate a summary for you as a starting point.
* **You're the Editor-in-Chief:** Edit, add, or remove parts of any summary to make it perfectly capture the essence of your chat.
* **Built for Smart Prompt:** Designed to work hand-in-hand with the "Smart Prompt" system.
* **Pick Your Summary Style:**
    * **Premium Summaries:** For a deeper, more nuanced overview (costs **2 Puni** per generation).
    * **Free Summaries:** Unlimited and won't cost Puni, perfect for quick notes.
* **Look Back at Past Notes:** The system keeps a history of your generated summaries.

**How It Looks and Feels (when accessed via Memory Settings with Smart Prompt on):**

You'll see a space for your summary and buttons to:
* **Save changes** to the current summary.
* **Generate a New Summary** (with an option to **Use Premium Summary**).
* **Show Previous Summaries**.

Please dive in, try it out (with Smart Prompt enabled!), and let me know what you think – your feedback is invaluable!

---

I really hope these memory systems and tools help you create even more engaging, immersive, and long-lasting experiences here on Character Tavern!

Happy chatting!

- Sal