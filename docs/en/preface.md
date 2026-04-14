# Preface: Build an AI Agent From Scratch

## Why Agents

LLMs are evolving from *answering questions* to *completing tasks* — calling
tools, browsing the web, operating computers, planning multi-step execution.
Around this capability a more fundamental question surfaces:

> How is an AI Agent actually built?

As OpenAI, Anthropic, and others keep packaging and abstracting these
capabilities behind their platforms, it's worth asking: as developers, what
can we still build ourselves, and how deeply can we understand it? This
tutorial answers that.

## What this tutorial does

This tutorial walks you, from zero, through building a complete AI Agent
yourself.

By the end you'll have:

- A first-principles understanding of what's inside an Agent
- A working, extensible Agent architecture
- Hands-on experience developing complex systems driven by prompts

It's aimed at engineers who want to understand Agent architecture deeply,
researchers working in the space, and developers who want to build
system-level AI applications themselves.

## Methodology: programming with prompts

A defining feature of this tutorial is that **we program with prompts**.

You won't write large blocks of complex logic by hand. Instead, you design
prompts that make the model generate and drive the code. The Agent's
capabilities themselves grow out of iterative prompting.

## What you need

Two things.

**An LLM** as the Agent's reasoning core. The reference implementation uses
Sonnet 4.6. You can swap in another model, but results may differ —
noticeably weaker models aren't recommended.

**A coding agent** for actually writing and modifying code. The default is
a Sonnet-based coding agent.

(A dedicated setup chapter will cover concrete installation later.)

## Structure

The tutorial is decomposed by component: **each chapter = one core Agent
component**. You'll build up:

- Perception
- Reasoning
- Tool use
- Task planning
- ...

## How to tell a chapter is done

Every chapter ships with two ways to verify.

**Human check** — put yourself in the Agent's shoes and ask: *"has this
step been implemented correctly?"*

**Agent check (tests)** — we provide test cases. If they all pass, the
component is correctly implemented.

## Community and submissions

This is meant to be a shared process, not just a course to consume. If you
build your own Agent, we'd love to see it. A submission ideally includes:

- Model used (Sonnet / GPT / other)
- How long it took
- Outcome (screenshots or a short description)
- Key design decisions (optional)

This lets readers compare implementations, reproduce results, and draw on
real experience.

## Where to talk

- Comments: share your implementation and feedback
- Slack group: deeper discussion of implementation details

## Roadmap

Starting from nothing, each chapter unlocks one capability; together they
form a complete system.

*(roadmap diagram TBD)*

## Closing

This is not a tutorial you can finish by reading. It's something **you
have to build with your own hands to actually understand**.

What we're looking forward to: your version will look different from
everyone else's.

Ready? Let's start with Chapter 1. 🚀
