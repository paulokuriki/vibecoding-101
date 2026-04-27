# Vibe Coding Starter Kit

> Turn an idea into a working app, even if you've never written a line of code.

## What this is

One file: [`AGENTS.md`](./AGENTS.md). You don't fill it in yourself.

You paste it into a chat with an AI like [Claude](https://claude.ai), describe a problem you'd like to solve with software, and have a conversation. The AI takes the lead — it asks the right questions, suggests approaches, points out what could fail, and helps you scope your idea down to something you can actually finish. By the end, you have a complete plan you hand to a coding AI to build the app for real.

## How to use it

This works in **two phases, in two different chats.**

### Phase 1 — Plan your app (~30 minutes)

1. Copy the contents of [`AGENTS.md`](./AGENTS.md).
2. Open a new chat at [claude.ai](https://claude.ai) (or your AI of choice).
3. Type *"I want you to help me build a program."*, paste the file below it, and send.
4. Have the conversation. The AI will ask one question at a time, in plain language. Answer honestly. Don't worry about technical answers — that's what the AI is there for.
5. The AI will eventually say *"This is ready"* and give you a finished plan. Copy all of it.

### Phase 2 — Build your app

6. Open an AI-enabled coding tool. Good options: [Cursor](https://cursor.com/), [VS Code](https://code.visualstudio.com/) with an AI extension like [Claude Code](https://www.claude.com/product/claude-code) or [Codex](https://developers.openai.com/codex/cli/).
7. Save the plan from Phase 1 as `AGENTS.md` in your project folder so the IDE's AI can read it directly and say *"please build this."*
8. Run what it gives you. The first version probably won't be perfect — that's normal, not failure. Just describe what's wrong and the AI will fix it. Repeat until it works.

That's the whole loop.

## What you'll need

- Access to an AI chat. [Claude.ai](https://claude.ai) has a free tier.
- About 30 minutes for Phase 1, plus however long the build takes (often another 30 to 90 minutes for a small project).
- An idea. Even a vague one. The conversation in Phase 1 is designed to sharpen it.

## What is "vibe coding"?

Vibe coding is building software by describing what you want, in plain language, to an AI. You don't memorize syntax or read documentation — you talk, the AI writes the code, you check whether it does what you wanted, and you iterate.

It works well for small, focused projects: a personal tracker, a quiz, a habit logger, a one-off automation, a tool that solves a problem only you have. It struggles with very large or unusual systems — but most first projects aren't those.

## Why does this template exist?

Most people skip planning and ask an AI to "build me an app to do X." They get a wall of code that almost works, then spend hours trying to fix problems caused by ambiguity in the original ask. The planning conversation prevents that.

It forces you to answer the questions that *will* come up during the build — *before* any code gets written. The AI helps you think: it pushes back on vague ideas, suggests simpler stacks, points out what could break, and helps you cut scope to something achievable. The output is a spec tight enough that the build step usually goes smoothly.

The single biggest cause of abandoned first projects is unclear scope. This file fixes that.

## Tips

- **Be honest with the AI.** If a word it uses doesn't make sense to you, say so. It will rephrase. You won't look stupid — you'll just save yourself an hour later.
- **Start small.** Your first project should ship in days, not months. The AI will help you cut scope; let it.
- **Don't worry if you don't know technical answers.** That's the AI's job. You bring the problem; it brings the tools.
- **Expect to iterate during the build.** Two or three rounds of "this doesn't work right" → "fixed" is normal, not a sign you're doing it wrong.
- **If you get stuck, start over.** A fresh chat with the planning template is cheaper than fighting a broken build.

## About

Created by **Paulo Kuriki, MD** — neuroradiologist and Assistant Professor at UT Southwestern Medical Center, where he directs the AIR-Hub at the Department of Radiology. Originally from São Paulo, Brazil. Builds AI tools for radiology and teaches others to do the same.

If a doctor can code, so can you.

- Website: [kuriki.ai](https://kuriki.ai/)
- GitHub: [@paulokuriki](https://github.com/paulokuriki)
- LinkedIn: [paulokuriki](https://www.linkedin.com/in/paulokuriki/)
