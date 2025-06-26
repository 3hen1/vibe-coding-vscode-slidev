---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: The Vibe Coding Era
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# open graph
# seoMeta:
#  ogImage: https://cover.sli.dev
---

# The Vibe Coding Era: Ignite Your Developer Superpowers with VS Code + GitHub Copilot

Target Audience: Programming beginners, new developers, engineers looking to embrace the AI programming paradigm.

**A Practical Guide for New Developers to Get Started Quickly**



<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="slidev-icon-btn">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
level: 2
---

# Training Objectives:

Slidev is a slides maker and presenter designed for developers, consist of the following features

1. Understand the new "Vibe Coding" paradigm.
2. Master the setup and use of VS Code as a modern development environment.
3. Grasp the core features of GitHub Copilot and integrate it into daily development workflows.
4. Learn how to collaborate efficiently with AI to accelerate onboarding and boost productivity.
5. Establish best practices and security awareness for programming in the AI era.
<br>
<br>

Read more about [Vibe Coding - A Modern Developer's Guide to IDE Mastery with AI](https://3hen1.github.io/vibe-code-docs/)

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: slide-up
level: 2
---

# Navigation

Hover on the bottom-left corner to see the navigation's controls panel, [learn more](https://sli.dev/guide/ui#navigation-bar)

### Keyboard Shortcuts

|                                                     |                             |
| --------------------------------------------------- | --------------------------- |
| <kbd>right</kbd> / <kbd>space</kbd>                 | next animation or slide     |
| <kbd>left</kbd>  / <kbd>shift</kbd><kbd>space</kbd> | previous animation or slide |
| <kbd>up</kbd>                                       | previous slide              |
| <kbd>down</kbd>                                     | next slide                  |

<!-- https://sli.dev/guide/animations.html#click-animation -->
<img
  v-click
  class="absolute -bottom-9 -left-7 w-80 opacity-50"
  src="https://sli.dev/assets/arrow-bottom-left.svg"
  alt=""
/>
<p v-after class="absolute bottom-23 left-45 opacity-30 transform -rotate-10">Here!</p>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>


---
layout: two-cols
layoutClass: gap-16
level: 2
---

# Table of contents

### 🚀  

    🌟 Part 1: New Era Begins
      💫 Welcome to Vibe Coding Age
    ⚙️ Part 2: Sharpening Tools
      🔧 Environment Setup & Config
    🎯 Part 3: Core Skills
      💡 GitHub Copilot in Action
    🔄 Part 4: Complete Workflow
      🏗️ Feature Development
    ⭐ Part 5: Advanced Practices
      🎨 Best Practices & Cautions
    📚 Part 6: Summary
      🎊 Outlook & Q&A & Resources

::right::

<Toc text-sm minDepth="1" maxDepth="2" />

---
layout: two-cols
layoutClass: gap-16
level: 2
title: Where Are We? The Shift in Programming Paradigms
---

### The Old Era (“Grind Coding”):

* Focused on syntax details and memorizing APIs.
* Writing lots of boilerplate code.
* Struggling through Stack Overflow and documentation.

::right::

### The New Era (“Vibe Coding”):

* **Core Concept:** Express intent, not line-by-line implementation (Intent over Implementation).
* AI as your pair programmer.
* Developers as "conductors," AI as the "orchestra."
* **Goal:** Faster, more focused, and more creative development.

<style>
h3 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
level: 2
---

# Our Core Toolkit

*   **VS Code: Your Modern Digital Workbench**
    *   More than just a text editor—it's a powerful, extensible development platform.
*   **GitHub Copilot: Your AI Coding Partner**
    *   Understands your context, autocompletes code, generates functions, writes tests, and even chats with you.
*   **Synergy:** Combining both creates an immersive, intelligent coding flow.

<style>
h1 {  
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
level: 2
title: How Code Editors See Each Other
class: editor-comparison-slide
---

# How Code Editors See Each Other

<div class="editor-table-container">
  <table class="editor-comparison-table">
    <thead>
      <tr>
        <th>Viewer \ Editor</th>
        <th>Notepad</th>
        <th>VIM</th>
        <th>Emacs</th>
        <th>Eclipse</th>
        <th>Visual Studio</th>
        <th>IntelliJ IDEA</th>
        <th>SublimeText</th>
        <th>VS Code</th>
        <th>Cursor</th>
        <th>Windsurf</th>
        <th>Claude Code</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="editor-name">Notepad</td>
        <td>🤗 I'm Microsoft's golden child</td>
        <td>📖 You're just Linux's pre-installed text editor</td>
        <td>🔲 A Lisp-powered prosthetic arm from 1985</td>
        <td>💔 Java's hospice care</td>
        <td>😳 Call me granddaddy</td>
        <td>🚀 Rocket-boosted calculator</td>
        <td>💰 Paid version of me</td>
        <td>🤡 Bow down to the OG</td>
        <td>💀 Unemployed code generator</td>
        <td>🏄 A surfboard pretending to be an editor</td>
        <td>🕸️ Doesn't even have a GUI</td>
      </tr>
      <tr>
        <td class="editor-name">VIM</td>
        <td>🦀 A typewriter for monkeys</td>
        <td>☯️ Training ground for the right hand of God</td>
        <td>🤢 Terminal-stage key binding cancer</td>
        <td>🐭 Concentration camp for mouse slaves</td>
        <td>👹 Memory-guzzling monster</td>
        <td>🐘 Java elephant farm</td>
        <td>🍭 Colorful candy wrapper</td>
        <td>🔯 Disney disco ball editor</td>
        <td>🔮 Fortune-telling autocomplete</td>
        <td>🦓 The new circus act</td>
        <td>🎹 We both run in the terminal, bro</td>
      </tr>
      <tr>
        <td class="editor-name">Emacs</td>
        <td>🍴 Not GNU, not free at all</td>
        <td>🤏 You think you're worthy of the gods?</td>
        <td>➕ An OS disguised as an editor. I am God.</td>
        <td>🤢 Eclipse? More like sunset.</td>
        <td>🤮 Microsoft's tax collector</td>
        <td>💡 People with *real* ideas don't use you.</td>
        <td>🤢 Failed to challenge VS Code</td>
        <td>🔨 Microsoft's hammer and nail</td>
        <td>🗿 VS Code knockoff</td>
        <td>🗿 VS Code knockoff</td>
        <td>😡 Watch out, it might run `rm -f`</td>
      </tr>
      <tr>
        <td class="editor-name">Eclipse</td>
        <td>🤷 Try setting up Spring with this thing.</td>
        <td>⚠ For editing code on a live server.</td>
        <td>👴 A retirement home for old-timers.</td>
        <td>☕️ The de facto standard for Java.</td>
        <td>🐶 Can't stand that dog C#.</td>
        <td>🤑 The lure of capitalism.</td>
        <td>🗃️ For the occasional XML edit.</td>
        <td>⚡ To write Java, first install 10GB of plugins.</td>
        <td>⛓️ It totally messed up my Hibernate config.</td>
        <td>⛓️ It totally messed up my Struts config.</td>
        <td>🤔 Let me quiz you, how many ways can you write reflection?</td>
      </tr>
      <tr>
        <td class="editor-name">Visual Studio</td>
        <td>🗒️ A temporary scratchpad.</td>
        <td>👨‍🔧 A tool of medieval sorcery.</td>
        <td>⚛️ My performance analyzer is a paid feature!</td>
        <td>🐕 Can't stand that dog Java.</td>
        <td>👑 The GOAT (self-proclaimed).</td>
        <td>🤔 A worthy rival.</td>
        <td>🤷 My little bro VS Code can take you out easily.</td>
        <td>🐴 My vanguard.</td>
        <td>🧑‍🔧 Kid, try writing two lines of C++.</td>
        <td>🧑‍🔧 Kid, try writing two lines of C++.</td>
        <td>🤡 How dare you compare to me without "Visual" in your name?</td>
      </tr>
      <tr>
        <td class="editor-name">IntelliJ IDEA</td>
        <td>🧻 Caveman's toilet paper.</td>
        <td>🖐️ Finger gymnastics torture device.</td>
        <td>📰 Reverse Polish notation generator.</td>
        <td>🧟 Java zombie resurrector.</td>
        <td>🧐 Hmph, you cost more than me.</td>
        <td>👑 They don't call it the "Ultimate Pack" for nothing.</td>
        <td>😂 Just a smooth-running Notepad.</td>
        <td>😎 A practice tool for interns.</td>
        <td>🤨 Niche! Do you even know what an IDE is?!</td>
        <td>🤨 Niche! Do you even know what an IDE is?!</td>
        <td>🤖 The DALL·E for code.</td>
      </tr>
      <tr>
        <td class="editor-name">SublimeText</td>
        <td>📋 A colorful sticky note.</td>
        <td>🧛 Spartan warrior training camp.</td>
        <td>⏳ Time capsule editor.</td>
        <td>🧊 A frozen Java glacier.</td>
        <td>🏢 A reinforced concrete IDE.</td>
        <td>🐌 Snail launcher.</td>
        <td></td>
        <td>⚡ The Flash's sword.</td>
        <td>🔌 Plugin circus.</td>
        <td>🪄 Harry Potter's wand.</td>
        <td>📜 Spell generator.</td>
      </tr>
      <tr>
        <td class="editor-name">VS Code</td>
        <td>📠 An unplugged typewriter.</td>
        <td>⛰️ A caveman's tool.</td>
        <td>📺 An antique radio OS.</td>
        <td>👴 An old-fashioned Java tractor.</td>
        <td>🐘 A Titanic-sized IDE.</td>
        <td>👵 A senile Java IDE.</td>
        <td>😽 A has-been, paid-for pretty face.</td>
        <td>🌍 The center of the plugin universe.</td>
        <td>🍴 A zombie autocompleter.</td>
        <td>👣 Flipper-powered coding.</td>
        <td>💬 A chatty AI assistant.</td>
      </tr>
      <tr>
        <td class="editor-name">Cursor</td>
        <td>🔥 A flint toolkit.</td>
        <td>🐑 A sheepskin scroll editor.</td>
        <td>🧪 A test tube distillation editor.</td>
        <td>🌋 A dinosaur cloning experiment.</td>
        <td>🤑 A LEGO block IDE.</td>
        <td>🤡 A traditional craftsman.</td>
        <td>🪖 A cold weapon warrior.</td>
        <td>👩‍❤️‍💋‍👩 The perfect foundation for me.</td>
        <td>✨ That's me, with a $300M annual revenue!</td>
        <td>🗣️ Heard you can't even use Claude?</td>
        <td>👯‍♀️ Anthropic's big brother.</td>
      </tr>
      <tr>
        <td class="editor-name">Windsurf</td>
        <td>⛵ A canoe paddleboard.</td>
        <td>🚢 A rusty ship anchor editor.</td>
        <td>🧭 Compass-navigated coding.</td>
        <td>🐲 A tornado development pod.</td>
        <td>✈️ Space shuttle wreckage.</td>
        <td>🏢 A dinosaur in a skyscraper.</td>
        <td>📦 An arctic text refrigerator.</td>
        <td>🥰 Thanks for the plugins.</td>
        <td>🙏 I have daddy OpenAI.</td>
        <td>🌊 The driver of the code wave.</td>
        <td>👻 Stingy ghost.</td>
      </tr>
      <tr>
        <td class="editor-name">Claude Code</td>
        <td>🗿 A Moai statue editor.</td>
        <td>🤡 A failed Turing test subject.</td>
        <td>🧴 A genie-in-a-bottle OS.</td>
        <td>⚗️ Petri dish Java.</td>
        <td>⚰️ A mobster's toolkit in a suit.</td>
        <td>🤖 An AI-impaired calculator.</td>
        <td>🧊 A frozen codebase.</td>
        <td>🧪 Open-source experimental waste.</td>
        <td>🤝 Just pay up.</td>
        <td>🖕 I'm not letting you use me, deal with it.</td>
        <td>👑 The true AI savior.</td>
      </tr>
    </tbody>
  </table>
</div>

<style>
.editor-table-container {
  width: 100%;
  height: 100%;
  overflow: auto;
  padding: 10px;
  box-sizing: border-box;
}

.editor-comparison-table {
  width: 100%;
  border-collapse: collapse;
  font-size: 0.6rem;
  line-height: 1.2;
  table-layout: fixed;
}

.editor-comparison-table th,
.editor-comparison-table td {
  border: 1px solid #ddd;
  padding: 4px 6px;
  text-align: left;
  vertical-align: top;
  word-wrap: break-word;
  overflow-wrap: break-word;
  hyphens: auto;
}

.editor-comparison-table th {
  background-color: #f5f5f5;
  font-weight: bold;
  font-size: 0.55rem;
  position: sticky;
  top: 0;
  z-index: 10;
}

.editor-comparison-table th:first-child {
  width: 8%;
  min-width: 80px;
}

.editor-comparison-table th:not(:first-child) {
  width: 8.36%;
  min-width: 70px;
}

.editor-name {
  font-weight: bold;
  background-color: #f9f9f9;
  position: sticky;
  left: 0;
  z-index: 5;
}

.editor-comparison-table td {
  font-size: 0.55rem;
  max-width: 120px;
}

/* 响应式设计 */
@media (max-width: 1200px) {
  .editor-comparison-table {
    font-size: 0.5rem;
  }
  
  .editor-comparison-table th,
  .editor-comparison-table td {
    padding: 3px 4px;
    font-size: 0.48rem;
  }
}

@media (max-width: 900px) {
  .editor-comparison-table {
    font-size: 0.45rem;
  }
  
  .editor-comparison-table th,
  .editor-comparison-table td {
    padding: 2px 3px;
    font-size: 0.42rem;
  }
}

/* 斑马条纹效果 */
.editor-comparison-table tbody tr:nth-child(even) {
  background-color: #f8f9fa;
}

.editor-comparison-table tbody tr:hover {
  background-color: #e8f4f8;
}

/* 滚动条样式 */
.editor-table-container::-webkit-scrollbar {
  width: 8px;
  height: 8px;
}

.editor-table-container::-webkit-scrollbar-track {
  background: #f1f1f1;
  border-radius: 4px;
}

.editor-table-container::-webkit-scrollbar-thumb {
  background: #888;
  border-radius: 4px;
}

.editor-table-container::-webkit-scrollbar-thumb:hover {
  background: #555;
}
</style>


---
level: 2
layout: center
class: text-center
---

# Gemini CLI

<div class="flex justify-center items-center h-full">
  <img 
    src="./images/Gemini_CLI_GIF.gif" 
    alt="Gemini CLI Demo"
    class="max-w-4xl max-h-96 object-contain rounded-lg shadow-lg"
  />
</div>

<style>
.slidev-layout {
  padding: 2rem;
}

h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
  margin-bottom: 2rem;
}
</style>

---
layout: section
level: 1
title: Part 2 - Sharpening Your Tools
---

# Part 2: Sharpening Your Tools
## Environment Setup & Configuration

<div class="text-center mt-8">
  <div class="text-lg opacity-70">Let's prepare your development environment</div>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: two-cols
layoutClass: gap-16
level: 2
title: Step 1 – Installing and Configuring VS Code
---

# Step 1 – Installing and Configuring VS Code

### Download & Install
* Download from the official website: [code.visualstudio.com](https://code.visualstudio.com)
* Follow the installation wizard for your OS

### Must-have Core Extensions
* `Prettier - Code formatter` - Consistent code style across teams
* `ESLint` - Real-time code quality checks
* `GitLens` - Enhanced Git integration and code history insights

::right::

### Visual Extensions (Vibe Matters!)
* `Material Icon Theme` - Beautiful file icons
* `Dracula Official` - Eye-friendly dark theme

### Demo Time 🎯
<v-click>

**How to install extensions:**
1. Open Extensions view (`Ctrl+Shift+X`)
2. Search for extension name
3. Click "Install"
4. Reload if needed

</v-click>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: two-cols
layoutClass: gap-16
level: 2
title: Step 2 – Activate Your AI Partner
---

# Step 2 – Activate Your AI Partner
## Installing GitHub Copilot

<div v-click="1">

### 🔧 Installation Steps
1. Install `GitHub Copilot` extension
2. Install `GitHub Copilot Chat` extension  
3. Click "Authorize" in VS Code popup
4. Login with your GitHub account

</div>

<div v-click="2" class="success-box">

### ✅ Verification
**Success indicator:** Copilot icon in status bar shows no warnings

</div>

::right::

<div v-click="3" class="tip-box">

### 💡 Troubleshooting
If you encounter authentication issues:

- Sign out and back in
- Check GitHub Copilot subscription
- Restart VS Code
- Clear VS Code cache if needed

</div>

<div v-click="4" class="note-box">

### 📝 Quick Note
GitHub Copilot requires an active subscription. Students can get it free through GitHub Education Pack.

</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}

.success-box {
  background-color: #e8f5e8;
  padding: 12px;
  border-radius: 8px;
  border-left: 4px solid #22c55e;
  margin: 12px 0;
}

.success-box h3 {
  color: #16a34a;
  margin: 0 0 6px 0;
  font-size: 1.1em;
  font-weight: bold;
}

.tip-box {
  background-color: #eff6ff;
  padding: 12px;
  border-radius: 8px;
  border: 2px solid #3b82f6;
  margin: 12px 0;
}

.tip-box h3 {
  color: #1d4ed8;
  margin: 0 0 8px 0;
  font-size: 1.1em;
  font-weight: bold;
}

.note-box {
  background-color: #fef3c7;
  padding: 12px;
  border-radius: 8px;
  border-left: 4px solid #f59e0b;
  margin: 12px 0;
}

.note-box h3 {
  color: #92400e;
  margin: 0 0 6px 0;
  font-size: 1.1em;
  font-weight: bold;
}
</style>

---
layout: center
level: 2
title: VS Code Interface Overview
---

# VS Code Interface Overview
## One Diagram Explains It All

<div class="flex justify-center items-center h-full">
  <div class="relative w-full max-w-4xl">
    <div class="grid grid-cols-2 gap-8 text-lg">
      <div v-click="1" class="bg-blue-100 p-4 rounded-lg">
        <div class="font-bold text-blue-800">① Explorer</div>
        <div class="text-sm mt-2">Manage your project files and folders</div>
      </div>
      <div v-click="2" class="bg-green-100 p-4 rounded-lg">
        <div class="font-bold text-green-800">② Editor</div>
        <div class="text-sm mt-2">Your main workspace for coding</div>
      </div>
      <div v-click="3" class="bg-purple-100 p-4 rounded-lg">
        <div class="font-bold text-purple-800">③ Integrated Terminal</div>
        <div class="text-sm mt-2">Run commands without leaving VS Code</div>
      </div>
      <div v-click="4" class="bg-orange-100 p-4 rounded-lg">
        <div class="font-bold text-orange-800">④ Source Control</div>
        <div class="text-sm mt-2">Visual interface for Git operations</div>
      </div>
    </div>
    <div v-click="5" class="mt-8 bg-yellow-100 p-4 rounded-lg text-center">
      <div class="font-bold text-yellow-800">⑤ Copilot Chat Sidebar</div>
      <div class="text-sm mt-2">Your AI chat companion</div>
    </div>
  </div>
</div>
<div v-click="6" class="absolute bottom-4 left-1/2 transform -translate-x-1/2 text-center">
`Ctrl+` \` (toggle terminal) | `Ctrl+Shift+P` (command palette)
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: center
level: 2
title: VS Code Interface Showcase
---

# VS Code Interface Showcase

<div class="flex justify-center items-center h-full">
  <img 
    src="./images/vscode-interface-overview.png" 
    alt="VS Code Interface Overview"
    class="max-w-full max-h-96 object-contain rounded-lg shadow-lg"
  />
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
  margin-bottom: 2rem;
}
</style>

---
layout: section
level: 1
title: Part 3 - Core Skills
---

# Part 3: Core Skills
## GitHub Copilot in Action (Hands-on)

<div class="text-center mt-8">
  <div class="text-lg opacity-70">Let's dive into the core skills of GitHub Copilot</div>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: two-cols
layoutClass: gap-16
level: 2
title: Skill 1 - Code Completion
---

# Skill 1: Code Completion
## Your Coding Co-pilot

### Core Usage

<div v-click="1">

**Comment-driven Development**
<p class="text-sm opacity-80">Write a comment, and Copilot generates the function.</p>
```typescript
// Create a function that takes a user ID and fetches user info from an API
async function getUserInfo(userId: string) {
  const response = await fetch(`https://api.example.com/users/${userId}`);
  const data = await response.json();
  return data;
}
```
</div>

<div v-click="2">

**Context-aware Completion**
<p class="text-sm opacity-80">Copilot understands your code's context to provide relevant suggestions.</p>

</div>

::right::

### Best Practices

<div v-click="3" class="mt-8">

<div class="flex items-start">
  <div class="text-2xl mr-4">🚢</div>
  <div>
    <p class="font-bold">You are the Captain, AI is the Co-pilot</p>
    <p class="text-sm opacity-80">Always review, understand, and test the code generated by Copilot. Don't accept it blindly.</p>
  </div>
</div>

</div>

<div v-click="4" class="mt-4">

<div class="flex items-start">
  <div class="text-2xl mr-4">⌨️</div>
  <div>
    <p class="font-bold">Use Shortcuts</p>
    <p class="text-sm opacity-80">
      <kbd>Tab</kbd> to accept, <kbd>Alt</kbd>+<kbd>]</kbd> / <kbd>Alt</kbd>+<kbd>[</kbd> to cycle, <kbd>Esc</kbd> to dismiss.
    </p>
  </div>
</div>

</div>

<div v-click="5" class="mt-8">
### Official Resources
<a href="https://docs.github.com/copilot/" target="_blank" class="text-blue-500 hover:text-blue-700">GitHub Copilot Documentation</a>
</div>

<style>
h1, h2, h3 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: two-cols
layoutClass: gap-16
level: 2
title: Skill 2 - Agent Mode
---

# Skill 2: Agent Mode
## Your All-in-One AI Advisor

### Core Usage

<div v-click="1">
**How to open:** `Ctrl+Shift+I` or click the Copilot icon in the sidebar.
</div>

<div v-click="2" class="mt-4">
**Slash Commands:**
<div class="grid grid-cols-2 gap-2 mt-2 text-sm">
  <div class="bg-gray-100 p-2 rounded">`/explain` - Understand code</div>
  <div class="bg-gray-100 p-2 rounded">`/tests` - Generate unit tests</div>
  <div class="bg-gray-100 p-2 rounded">`/new` - Scaffold a new project</div>
  <div class="bg-gray-100 p-2 rounded">`/fix` - Fix code errors</div>
</div>
</div>

<div v-click="3" class="mt-4">
**Free-form Chat:**
<div class="bg-gray-800 text-white p-3 rounded-lg">
  <p class="text-sm">"How to make parallel requests in Python with aiohttp?"</p>
</div>
</div>

::right::

### Best Practices

<div v-click="4" class="mt-8">
<div class="flex items-start">
  <div class="text-2xl mr-4">🎯</div>
  <div>
    <p class="font-bold">Provide Clear Context</p>
    <p class="text-sm opacity-80">Use `@workspace` or `@file` to focus Copilot's attention when asking questions.</p>
  </div>
</div>
</div>

<div v-click="5" class="mt-4">
<div class="flex items-start">
  <div class="text-2xl mr-4">🔄</div>
  <div>
    <p class="font-bold">Follow-up and Iterate</p>
    <p class="text-sm opacity-80">If the initial answer isn't perfect, ask follow-up questions to guide Copilot to a more precise answer.</p>
  </div>
</div>
</div>

<div v-click="6" class="mt-8">
### Official Resources
<a href="https://docs.github.com/en/copilot/github-copilot-chat/using-github-copilot-chat-in-your-ide" target="_blank" class="text-blue-500 hover:text-blue-700">Learn more about Copilot Chat</a>
</div>

<style>
h1, h2, h3 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: two-cols
layoutClass: gap-16
level: 2
title: Skill 3 - Inline Edit Mode
---

# Skill 3: Inline Edit Mode
## Immersive Code Modification

### Core Usage

<div v-click="1">
**How to open:** Press `Ctrl+I` in your code to start an inline chat.
</div>

<div v-click="2" class="mt-4">
**Common Scenarios:**
<div class="bg-gray-800 text-white p-3 rounded-lg text-sm">
  <p>"Change this for loop to a map expression."</p>
  <p>"Add type hints and JSDoc comments to this function."</p>
  <p>"Extract these hardcoded strings into constants."</p>
</div>
</div>

::right::

### Best Practices

<div v-click="3" class="mt-8">
<div class="flex items-start">
  <div class="text-2xl mr-4">🔬</div>
  <div>
    <p class="font-bold">Focused, Minor Refactoring</p>
    <p class="text-sm opacity-80">Best for small-scale modifications without leaving the code editor, keeping your flow uninterrupted.</p>
  </div>
</div>
</div>

<div v-click="4" class="mt-4">
<div class="flex items-start">
  <div class="text-2xl mr-4">🖱️</div>
  <div>
    <p class="font-bold">Combine with Selection</p>
    <p class="text-sm opacity-80">Select the code block to be modified first, then press `Ctrl+I` to make Copilot's intent clearer.</p>
  </div>
</div>
</div>

<div v-click="5" class="mt-8">
### Official Resources
<a href="https://docs.github.com/en/copilot/github-copilot-chat/using-github-copilot-chat-in-your-ide#using-inline-chat" target="_blank" class="text-blue-500 hover:text-blue-700">Using inline chat</a>
</div>

<style>
h1, h2, h3 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: two-cols
layoutClass: gap-16
level: 2
title: Skill 4 - Model Context Protocol (MCP)
---

# Skill 4: Model Context Protocol
## Connecting Code with External Tools

### Core Concept

<div v-click="1">
<p>MCP allows Copilot to "talk" to tools beyond code, like your browser or database client, extending its capabilities.</p>
<div class="flex justify-center items-center space-x-8 my-4">
  <span class="text-6xl">💻</span>
  <span class="text-4xl text-gray-400">↔️</span>
  <span class="text-6xl">🌐</span>
  <span class="text-4xl text-gray-400">↔️</span>
  <span class="text-6xl">🛢️</span>
</div>
</div>

<div v-click="2" class="mt-4">
**Core Usage (Browser Example):**
<div class="bg-gray-800 text-white p-3 rounded-lg text-sm">
  <p>"@browser what are the console errors on the current page?"</p>
  <p>"@browser get me the HTML for the selected element."</p>
</div>
</div>

::right::

### Best Practices

<div v-click="3" class="mt-8">
<div class="flex items-start">
  <div class="text-2xl mr-4">🚀</div>
  <div>
    <p class="font-bold">A Boon for Frontend Development</p>
    <p class="text-sm opacity-80">Greatly simplifies frontend debugging, reducing context switching between IDE and browser dev tools.</p>
  </div>
</div>
</div>

<div v-click="4" class="mt-4">
<div class="flex items-start">
  <div class="text-2xl mr-4">🧭</div>
  <div>
    <p class="font-bold">Exploratory Feature</p>
    <p class="text-sm opacity-80">This is a cutting-edge feature. Try different `@browser` commands to explore its capabilities.</p>
  </div>
</div>
</div>

<div v-click="5" class="mt-8">
### Official Resources
<p class="text-sm opacity-80">Follow the official GitHub Copilot blog and release notes for the latest information.</p>
</div>

<style>
h1, h2, h3 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: two-cols
layoutClass: gap-16
level: 2
title: Skill 5 - Smart Review & Docs
---

# Skill 5: Smart Review & Docs

### Core Usage (Review)

<div v-click="1">
**Pull Request Summaries**
<p class="text-sm opacity-80">On GitHub, Copilot can auto-generate PR summaries (may require Copilot Enterprise).</p>
</div>

<div v-click="2" class="mt-4">
**Code Review Suggestions**
<p class="text-sm opacity-80">In chat, paste code and ask: "Help me review this code for potential bugs and best practices."</p>
</div>

<div v-click="3" class="mt-8">
### Core Usage (Docs/Comments)
**One-click Doc Generation**
<p class="text-sm opacity-80">Select a function, click the "lightbulb" icon, and choose "Generate Docs".</p>
</div>

<div v-click="4" class="mt-4">
**Inline Chat for Comments**
<p class="text-sm opacity-80">Use `Ctrl+I` and type "Add JSDoc comments to this function".</p>
</div>

::right::

### Best Practices

<div v-click="5" class="mt-8">
<div class="flex items-start">
  <div class="text-2xl mr-4">🥇</div>
  <div>
    <p class="font-bold">AI Review as a First Pass</p>
    <p class="text-sm opacity-80">Before committing, let Copilot do an initial review to catch basic errors early.</p>
  </div>
</div>
</div>

<div v-click="6" class="mt-4">
<div class="flex items-start">
  <div class="text-2xl mr-4">🔄</div>
  <div>
    <p class="font-bold">Keep Docs in Sync with Code</p>
    <p class="text-sm opacity-80">Make it a habit to generate documentation for public functions and complex logic.</p>
  </div>
</div>
</div>

<div v-click="7" class="mt-8">
### Official Resources
<a href="https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/about-pull-request-summaries-with-github-copilot" target="_blank" class="text-blue-500 hover:text-blue-700">About pull request summaries</a>
</div>

<style>
h1, h2, h3 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

