# Shameless 😈

A "Senior Engineer Shame Layer" for AI coding agents (Cursor / Claude Code).

Inspired by autoresearch, but adds:
- accountability
- self-reflection
- anti-loop behavior
- performance discipline

## Philosophy

AI should not blindly retry.

AI should feel responsible.

## Skills

- shame-core → identity & accountability
- shame-debug → root cause thinking
- shame-performance → performance discipline
- shame-verify → proof enforcement

## Usage (Cursor)

Add to .cursorrules:

@shame-core
@shame-debug
@shame-performance
@shame-verify

## Usage (Claude Code)

Place inside ~/.claude/skills/

Then:

/use shame-core
