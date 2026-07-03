# Windows RE Lab

> Exploring Windows Internals through Reverse Engineering.

This repository documents my journey toward understanding reverse engineering by building small tools and experiments from scratch.

Rather than simply using existing tools, I want to understand the operating system concepts that make them possible.

Every project in this repository exists to answer a question.

---

## Why?

I became interested in reverse engineering after wondering how tools like Cheat Engine, debuggers, malware, and anti-cheat systems actually work.

Very quickly, I realized that reverse engineering is built on a deep understanding of Windows Internals.

Instead of memorizing APIs or following tutorials step by step, I want to learn by asking questions, reading documentation, building experiments, and verifying my understanding.

---

## Current Research

### Question 01

> **How does Windows enumerate running processes?**

### Current implementation

- [x] Enumerate running processes using the Tool Help API

### Windows APIs explored

- `CreateToolhelp32Snapshot()`
- `Process32First()`
- `Process32Next()`

---

## Learning Philosophy

Every milestone begins with a question.

For each question I try to:

1. Ask why this mechanism exists.
2. Read the official documentation.
3. Build a small experiment.
4. Verify my understanding.
5. Document what I learned.

The goal is not to build as many projects as possible.

The goal is to understand how Windows actually works.

---

## Research Questions

Some questions I hope to answer include:

- How can one process open another process?
- How does `ReadProcessMemory()` actually work?
- How is virtual memory organized?
- Why do memory addresses change?
- How are executable files loaded?
- How do debuggers inspect a running process?
- How do reverse engineers locate data without source code?
- How do anti-cheat systems detect memory manipulation?

I don't expect to know the answers yet.

This repository exists to find them.

---

## Long-Term Goal

Build a strong foundation in:

- Windows Internals
- Systems Programming
- Reverse Engineering
- Software Security

while documenting the entire learning journey.
