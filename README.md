# LLXML

A self-describing format for AI-assisted development.

## Getting Started

1. Download and extract [seed-v8.zip](https://github.com/llxml/kernel/releases/download/seed-v8/seed-v8.zip)
2. Instruct a frontier AI assistant to read `boot.xml`

## What It Is

LLXML defines two primitives:
- `<self>` — specs that describe themselves
- `<skill>` — teachable processes

Everything else — project structures, workflows, document types — are skills built using the format.

## The Recursive Part

LLXML is written in LLXML. The kernel develops itself using its own ticket workflows, skills, and processes. When you boot it, you get the same system the kernel uses to improve itself — and you use that system to build your own projects.

Individual projects can reflect on themselves and improve their own processes. So can the kernel. On top of that, you use the same system for regular development work.

## The Harness

The kernel ships with skills for ticket workflows, project organization, and building a "harness" — a context assembler that watches your files and feeds relevant context to AI sessions. You use the harness to develop your apps and shared libraries, and also to develop the kernel itself.

## Model Agnostic

LLXML works with any frontier AI model. One format to bridge working across Claude, GPT, Gemini, and whatever comes next.

## License

CC0 — Public Domain
