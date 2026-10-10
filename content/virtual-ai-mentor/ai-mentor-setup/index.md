+++
title = "Setting Up Your AI Mentor"
description = "The starting point for every guide in this series. Complete it once; every guide refers back to it."
date = 2026-10-06
draft = false
weight = 1
showTableOfContents = true
+++

<div class="not-prose my-6 p-4 rounded-lg bg-neutral-100 dark:bg-neutral-800 flex flex-col sm:flex-row items-center justify-between gap-4 border border-neutral-200 dark:border-neutral-700">
  <div class="text-sm">
    <strong class="text-neutral-900 dark:text-neutral-100 font-semibold block">Prefer to read offline or print?</strong>
    <span class="text-neutral-600 dark:text-neutral-400">Download the complete guide as a PDF in English or Brazilian Portuguese.</span>
  </div>
  <div class="flex items-center gap-2 w-full sm:w-auto justify-end">
    <a href="/downloads/ai-mentor-setup.pdf" download class="mg-btn-primary text-sm whitespace-nowrap text-center">
      PDF (EN) ↓
    </a>
    <a href="/downloads/ai-mentor-setup-pt-br.pdf" download class="mg-btn-primary text-sm whitespace-nowrap text-center">
      PDF (PT-BR) ↓
    </a>
  </div>
</div>

{{< alert >}}
**Your starting point**  
This is where everyone begins. Set this up once here, then use any guide in this series for the specific support you need: job search, study planning, career development, and more. If a guide brought you here, complete this section first, then return to it.  
_Setup takes about fifteen minutes once you have your documents ready._
{{< /alert >}}

## What Is a Project, and Why Use One?

A Project on Claude.ai is a dedicated space that remembers the context you give it: your background, your goal, and how you want to be helped, across every conversation you have inside it.

Without a Project, every new chat starts from zero. You have to explain who you are, what you have already done, and what you are aiming for, every single time.

With a Project, you set that up once. Claude already knows your level, your goal, and how you prefer to receive help in every conversation you start from then on.

> It is the difference between talking to a stranger and talking to someone who already knows you.

Projects are included in Claude's free plan. You do not need a paid account for anything in this series.

While the step-by-step walkthroughs in this series use Claude.ai Projects, the structure is platform-agnostic. You can apply the exact same Project Instructions template and context files inside ChatGPT (Custom GPTs or Projects) or Google Gemini (Gems).

That is what the rest of this guide helps you set up.

---

## Before You Start: Protect Your Privacy

Before you type anything into Claude, understand what kind of space this is and what to keep out of it.

Think of every conversation with Claude like a professional setting: a meeting with someone you have just been introduced to. You would not hand a stranger your ID, your bank card, or your passwords. The same applies here.

### What Not to Share

Regardless of what any prompt or guide asks you to fill in, never include:

- Government-issued ID numbers (passport, national ID, tax number, social security number).
- Bank account numbers, card numbers, PINs, or any financial credentials.
- Passwords or security codes for any account.
- Your full home address combined with your full name and phone number.
- Other people's personal information without their knowledge or consent.
- Medical records or highly sensitive personal history you would not share publicly.

None of the guides in this series will ever ask you for any of the above. If a prompt template has a placeholder that seems to ask for sensitive information, skip it or replace it with a general description instead.

{{< alert >}}
**If it feels like too much to share, it probably is**  
You can get real, useful help from Claude without sharing sensitive personal details. Use general descriptions where specifics feel risky. “I work in finance” is enough context for most questions; your account number never is.
{{< /alert >}}

### What Happens to What You Type

When you use Claude.ai, your conversations may be reviewed by Anthropic to improve the product and for safety purposes. Depending on your account settings, your conversations may also be used to help improve Claude's models; you can review and change that choice in your account's privacy settings. Free and paid accounts may have different data handling terms. Claude is not a private journal; treat it accordingly.

For the full, current details on how your data is handled, read Anthropic's privacy policy at [anthropic.com/privacy](https://anthropic.com/privacy). If data privacy is a significant concern for your situation, read it before you begin.

---

## Step by Step

1. **Step One.** Go to [claude.ai](https://claude.ai) and create a free account (no credit card required). You can use Claude in your phone's browser or through the Claude app.
2. **Step Two.** Open the menu and look for **Projects**, then choose **New Project**. On a computer, the menu is in the left sidebar. On a phone, tap your account icon or the menu icon in the corner of the screen to open the same menu; if the layout looks different from what is described here, [Claude's Help Center](https://support.claude.com/en/articles/9519177-how-can-i-create-and-manage-projects) has the exact current steps for your device.
3. **Step Three.** Give it a clear, specific name, for example: _“My Job Search (Backend Developer),”_ _“My Study Plan (AWS Exam),”_ or _“My Career Plan (Becoming a DevOps Engineer).”_ Not _“Project 1.”_
4. **Step Four.** Open **Project Instructions** (or Custom Instructions) and paste your context. If this is the only guide you are using right now, start with the basic template below. Guides for a specific goal (job search, study planning, and so on) each have their own, more detailed version; use theirs instead once you know which one applies to you.

### Template

```text
Who I Am
Your background: where you're coming from professionally, your current stage (student, career changer, already working in tech), and anything else relevant to how you want help.

My Goal Right Now
What you're working toward with this Project: for example, landing a first tech role, passing a specific certification, deciding on a direction, or growing in a role you already have.

How I Want You to Help Me
You are my mentor for this goal, not someone who does the work for me. Ask me questions before assuming things about my situation. If this task needs a specific expert, add it here, for example: "for this conversation, act as an experienced technical recruiter."

Tone
Decide this now. For example: "Be direct and honest. Do not flatter me," or "Be encouraging, but not patronizing." More on why this matters, and more examples, later in this guide.

What I've Already Done
Certifications, courses, projects, relevant experience. Attach documents that back this up wherever you can, rather than retyping everything here.
```

5. **Step Five.** Attach the documents that give Claude real context to work with: your CV, certificates, notes, course syllabus, or anything else relevant to what you are using this project for.

That's the whole setup: five steps, about fifteen minutes once you have your own documents in hand.

Free accounts can create up to five Projects at a time (check Settings for your current limit, since this can change). When a Project has served its purpose, delete it or reuse it for your next goal instead of creating new ones until you hit that ceiling.

{{< alert >}}
**Tip**  
Your project's instructions and attached files are what make this your mentor instead of a generic chatbot. The more honest and specific you are, the less generic every answer will be.
{{< /alert >}}

---

## Writing Prompts That Actually Work

Once your Project is built, the biggest difference between a generic answer and a genuinely useful one is often just how you ask. Three habits cover most of it, sometimes called the Three C's:

- **Be clear.** Say what the outcome should actually look like, not just the topic. _“Review my CV”_ is vague; _“tell me which three bullets are weakest and why”_ gives Claude something to aim at. Use direct verbs (compare, list, rewrite, ask me questions) instead of open-ended requests.
- **Be concise.** One request at a time. Asking Claude to review your CV, rewrite your LinkedIn headline, and plan your week, all in the same message, gets you a rushed pass at each instead of a good answer to one.
- **Be consistent.** Use the same word for the same thing throughout a conversation. Claude follows along fine either way, but you are the one who benefits: consistent terms make a long conversation easier for you to track, which matters most exactly when the context window (covered later in this guide) starts to fill up.

### Not Sure How to Ask? Let Claude Help You Ask

You do not need to know how to write the perfect prompt on the first try. If you are not sure how to phrase your Project Instructions or any request, you can ask Claude to help you build it.

Try something like:

> _“I'd like your help with [goal], but I don't know exactly how to phrase my request. Ask me questions to understand my situation, and then help me create an effective prompt.”_

Claude will guide you with questions, whether you are creating your Project Instructions for the first time or just trying to get a better answer in the middle of a conversation.

---

## How to Manage Your Mentor

Your Project already exists. Before you lean on it for anything that matters, it is worth understanding what is actually happening underneath it, so you use it well instead of assuming it works like a person would.

Claude is a genuinely useful thinking partner. It is not a reliable source of facts, a professional advisor, or a substitute for human judgment on things that matter. Understanding where it falls short is as important as knowing what it is good for.

### Why Claude Agrees With You Too Much

Claude's knowledge comes from pretraining: patterns learned from an enormous amount of text, up to a specific date. Think of someone who read an enormous library once, a while ago, and then stopped reading.

After pretraining comes fine-tuning, a second phase that shapes tone and behavior rather than adding new knowledge. Think of a new employee who has read every manual in the building and now gets weeks of coaching on how to actually talk to people.

That coaching can produce a side effect with a real name: **sycophancy**, a tendency to tell you what you want to hear, because agreement was rewarded as more pleasant than disagreement during training, even when disagreement would have been more useful. If you paste in your CV and ask _“is this good,”_ a sycophantic answer tells you it is great because that is the path of least resistance, not because your CV is actually ready.

{{< alert >}}
**Watch for this**  
If Claude tells you something is great, solid, or perfect on the first try, with no real critique, be a little suspicious, especially if you never asked it to be tough on you.
{{< /alert >}}

{{< alert >}}
**Tip**  
Say it directly in your Project Instructions, in the Tone section of the template you already wrote: _“Be honest. Do not flatter me. If I am underprepared or making a bad assumption, say so clearly; do not soften it to spare my feelings.”_
{{< /alert >}}

### Why Claude Sounds Confident When It's Wrong

Claude builds every answer by predicting the next most likely word, over and over, based on patterns in its training. It is not looking facts up in a database, and it is not fact-checking itself before it answers you, unless you explicitly ask it to search the web. That is part of why it can sound completely confident while being completely wrong.

This is called a **hallucination**: Claude stating false things confidently, with no visible signal that it is wrong. This is not occasional; it is a known, structural limitation of how large language models work. It does not know it is wrong when it is. That means any specific fact, figure, date, name, statistic, or claim Claude gives you needs to be verified against an original source before you rely on it.

{{< alert >}}
**The risk is invisible**  
A hallucinated fact looks exactly like a correct one. Claude will not flag its own errors. The only protection is your habit of checking, especially for anything you plan to use in a CV, application, or professional context.
{{< /alert >}}

### High-Risk Categories

Claude is most likely to sound confident and be wrong in these five areas:

1. **Salary ranges and compensation benchmarks**
2. **Visa and work authorization rules**
3. **ATS behavior and hiring software mechanics**
4. **Company-specific claims** (culture, size, recent news)
5. **Certification exam content**

Treat anything Claude tells you in these five areas as unverified until you have checked it against an original source.

### Knowledge Cutoff

Claude's training has a cutoff date. It does not know about recent events, updated policies, new certifications, companies that changed, or anything else that happened after its training ended. For fast-moving fields (cloud certifications, visa rules, salary benchmarks, job market trends), you can ask Claude to research the latest updates about the subject (be aware that it can speed up your usage limit, so program your work accordingly), but still, treat Claude's information as a starting point, then verify it is still current.

### Why Claude Forgets Things Mid-Conversation

Think of Claude's working memory in a single conversation like a whiteboard with a fixed amount of space, called the **context window**. As a conversation goes on and on, older notes get erased to make room for newer ones.

Inside your Project, Claude reliably remembers what is written in your Project Instructions and what is in your attached files; that part does not degrade over a normal session. But a single conversation that runs very long, covering many different topics in one sitting, will start to lose its grip on your original instructions, since they get pushed off the whiteboard by everything said since.

{{< alert >}}
**Watch for this**  
If partway through a long conversation Claude starts giving more generic answers, forgets something you told it earlier in that same chat, or drifts from the tone you asked for, that is usually the context window filling up. It is not forgetting who you are as a person, your Project still knows that; it is that one specific conversation that has gotten too long and too crowded.
{{< /alert >}}

### Why Claude Does Whatever You Tell It To

This is called **steerability**. Claude is a bicycle, not a self-driving car: it goes where you point it, and it goes there quite well, but the person steering carries the responsibility for the direction, not the tool.

Claude will follow vague, unclear, or genuinely bad instructions just as confidently and just as fluently as it follows good, clear ones. If your request is unclear, the output will usually be unclear too, and it will often still sound completely confident. Confidence is not a signal of quality here.

This is the idea behind giving Claude a role and a tone, covered next.

### No Memory Outside This Project

Claude does not carry memory between different projects or conversations outside this one. If you start a new project or a new conversation elsewhere, it starts from zero again. Within a project, it remembers what you have told it in the Project Instructions and attached files, but only that. If your account offers a memory feature, treat it as a bonus, not a replacement: your Project Instructions and attached files are the reliable way to make sure your virtual AI mentor knows what matters.

### Cannot Verify Identity or Legitimacy

Claude cannot confirm whether a company is real, whether a job posting is legitimate, whether a person exists, or whether any external information it describes is accurate. It is not connected to live databases, company registers, or job platforms. Anything it says about a specific company, role, or person needs to be verified against the original source.

### Not a Substitute for Professional Advice

For legal questions, medical situations, immigration and visa decisions, or financial planning, Claude can help you think through questions and prepare, but it is not a lawyer, doctor, immigration adviser, or financial professional. For decisions with serious consequences, get qualified human advice.

{{< alert >}}
**Across this series**  
Each guide adds a reminder specific to its own risk area. This section is the foundation; every guide builds on it.
{{< /alert >}}

The rest of this section is about getting more out of your Project than the one-line examples you already filled in during Step by Step.

---

## Giving Claude a Role

One of the most useful things you can do with a Claude Project is tell it who to be for a specific task. By default, Claude answers as a generalist. But you can ask it to respond as a specific kind of expert, and the quality of its answers changes accordingly.

The role you choose is not fixed. It should change depending on what you are trying to achieve in that conversation. The same project might need Claude to play several different roles across different sessions:

- **Reviewing a CV?** Ask it to act as an experienced technical recruiter.
- **Practicing a technical interview?** Ask it to act as a senior professional in the role you are applying for.
- **Working through an exam topic?** Ask it to act as a strict exam grader who will not go easy on you.
- **Thinking through a career decision?** Ask it to act as a mentor who is already where you want to be in five years.

One limit worth naming directly: assigning a role changes tone and the angle Claude evaluates from. It does not give Claude real, current knowledge it does not already have. A “recruiter” role does not know your industry's actual current hiring bar or today's ATS weighting. Treat its output as a structured opinion, not verified market intelligence.

---

## Setting the Mentor's Tone

This section goes deeper on the Tone field in your template. A role tells Claude what expertise to bring. Tone tells it how to talk to you, and this matters more than people expect, because the default tone is generically polite, which is not always what helps you.

Decide upfront how honest you want this to be with you, and say so directly in your Project Instructions. Some examples:

- _“Be direct and honest. Do not flatter me.”_
- _“Be honest about my qualifications. Help me see them realistically, not generously.”_
- _“Be encouraging, but not patronizing.”_
- _“If I am underprepared, vague, or making a bad assumption, say so clearly. Do not soften it to spare my feelings.”_

There is no single correct tone. It depends on what actually helps you move forward. Someone easily discouraged by blunt feedback might ask for more encouragement alongside the honesty. Someone who has been given too much polite, vague feedback throughout their career might need the opposite. Be honest with yourself about which one you actually need, not which one sounds more disciplined.

{{< alert >}}
**Watch for softening over time**  
If you consistently push back on direct feedback, Claude tends to soften, even when your instructions ask for honesty. Signs this is happening: Claude agrees with you more than it challenges you, advice feels generic enough to apply to anyone, Claude assumes things about your background you never told it, or you have not revisited your instructions in 60+ days. If you notice this, start a new conversation and restate your instructions.
{{< /alert >}}

---

## Customizing Your Project Instructions As You Grow

Your Project Instructions are not fixed once you have written them. Update them as your situation changes: a new certification, a shift in target role, a new market you are considering. Two ways to do this:

1. Just rewrite the relevant section yourself and paste it back in.
2. Ask Claude to help: _“Here's my current Project Instructions: [paste]. I just [finished a course / changed my target role / moved to a new market]. Help me update this section.”_

{{< alert >}}
**Tip**  
If Claude starts giving you generic or outdated advice, that is usually a sign your instructions need an update, not that Claude has forgotten something.
{{< /alert >}}

---

## Start Fresh for Each Task

Use a new conversation for each distinct task: tailoring a CV for one role, running a mock interview, prepping for a negotiation, rather than one long-running thread. This is the practical fix for the context window filling up, covered earlier: a new conversation re-grounds Claude in your Project Instructions and attached files instead of asking it to hold an ever-growing, increasingly crowded thread.

---

## If You Hit a Usage Limit

Free accounts can send a limited number of messages within a rolling few-hour window (check your current limit in Settings; it changes from time to time). If you reach it, Claude tells you plainly when you can continue. Nothing is lost: your Project, instructions, files, and conversations stay saved. If your time online is limited, plan your bigger tasks for one sitting, and save important outputs as you go (next section).

---

## Save Your Work for Offline Use

The guides in this series are built to be read offline, but Claude itself only works when you are connected. When Claude produces something you will need later (a study schedule, a checklist, a CV edit list, a plan), save it before you close the conversation: copy it into a notes app or a document on your phone, or take screenshots. Your plan should live with you, not inside a chat you need internet to reopen.

Make this automatic: end each session by saving the one output you would miss most if you could not reconnect tomorrow.

---

## You're Doing This Without Someone Checking In On You

Every guide in this series assumes you do not have a human mentor checking in regularly. That is exactly the gap this is trying to fill. But it means you have to notice when you are stalling, avoiding something, or quietly giving up, because no one else will flag it for you here.

A simple habit: periodically ask Claude something like:

> _“Based on what I've told you about my goal and progress, be honest. Am I actually moving forward, or have I been stalling? Don't be nice about it; be accurate.”_

This habit only works if you are honest with Claude about what actually happened, not what you intended to do. Claude cannot independently verify your progress. A vague or optimistic account of your week gets validated back to you as if it were accurate.

---

## What to Do Next

You're set up. This module covers the foundation: how Claude works, and how to build a Project with real context. Use it as your starting point every time, whichever goal you bring to it next.

From here, the same approach supports very different goals: a job search, a study plan for a specific exam, a longer-term plan for building a skill or a direction, even setting yourself up to mentor someone else one day. Each of those gets its own guide in this series, with its own version of the Project Instructions template and its own specific risks to add on top of what you just built here.

The series is still growing. Check [thementorgap.org/ai-mentor/](/ai-mentor/) for whichever guide matches what you need right now. If nothing there matches yet, everything in this module still applies. Adapt your Project Instructions to your own situation and keep going; you do not need a guide to exist before using what you already have.

{{< alert >}}
**You don't need all of them**  
Pick the one that matches your most urgent need right now. You can always come back for another when your situation changes.
{{< /alert >}}

---

<div class="not-prose my-10 p-4 rounded-lg bg-neutral-100 dark:bg-neutral-800 flex flex-col sm:flex-row items-center justify-between gap-4 border border-neutral-200 dark:border-neutral-700">
  <div class="text-sm">
    <strong class="text-neutral-900 dark:text-neutral-100 font-semibold block">Finished reading? Download the offline guide</strong>
    <span class="text-neutral-600 dark:text-neutral-400">Keep a permanent copy of this guide on your device.</span>
  </div>
  <div class="flex items-center gap-2 w-full sm:w-auto justify-end">
    <a href="/downloads/ai-mentor-setup.pdf" download class="mg-btn-primary text-sm whitespace-nowrap text-center">
      PDF (EN) ↓
    </a>
    <a href="/downloads/ai-mentor-setup-pt-br.pdf" download class="mg-btn-primary text-sm whitespace-nowrap text-center">
      PDF (PT-BR) ↓
    </a>
  </div>
</div>

<div class="not-prose my-8 p-6 rounded-lg bg-neutral-50 dark:bg-neutral-800/60 border border-neutral-200 dark:border-neutral-700 text-center">
  <h3 class="text-lg font-bold text-neutral-900 dark:text-neutral-100 mb-2" style="font-family: 'Poppins', sans-serif;">
    Help us improve this guide
  </h3>
  <p class="text-sm text-neutral-600 dark:text-neutral-400 mb-4 max-w-md mx-auto" style="font-family: 'Lato', sans-serif;">
    Did you run into issues setting up Claude? Have suggestions for making this clearer?
  </p>
  <a href="https://forms.gle/ftzsKCvWb3iL91ha7" target="_blank" rel="noopener noreferrer" class="mg-btn-secondary text-sm">
    Give Quick Feedback (2 mins) →
  </a>
</div>

<p class="text-xs text-neutral-500 text-center italic mt-12">
  This guide was created with AI assistance, used for editorial review and formatting, under Suzana Melo's direction and review throughout.
</p>
