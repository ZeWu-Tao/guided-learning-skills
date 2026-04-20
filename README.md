# Guided Learning Skill

> Adaptive Learning Operating System — Building Personalized, Sustainable Learning Loops

Guided Learning Skill is an **adaptive learning operating system** that delivers personalized, structured learning experiences through the interaction paradigm of a top-tier educator.

### Core Philosophy

- **Sustainable**: Cultivates long-term learning habits rather than short-term cramming  
- **Traceable**: Fully records the learning journey, enabling state recovery  
- **Evolvable**: Continuously optimizes learning paths based on learner behavior  

## Skill Documentation

- **中文版本**: [zh/guided-learning.md](zh/skills/guided-learning/SKILL.md)  
- **English Version**: [en/guided-learning.md](en/skills/guided-learning/SKILL.md)  

## Overview

## Three-Layer Capability Architecture

| Layer | Capability | Description |
|------|------------|-------------|
| **L1** | Structured Content Generation | Generates hierarchical, well-structured instructional content for any knowledge domain |
| **L2** | Real-Time Path Adjustment | Dynamically adapts learning paths and task openness based on learner behavior |
| **L3** | Long-Term Learning Modeling | Accumulates cross-temporal data to build an evolving learner model |

## Trigger Scenarios

- Learning a new knowledge domain  
- Initiating long-term learning plans  
- Systematic skill development  
- Requiring personalized learning pathways  
- Exam preparation and skill advancement  

**Trigger Keywords**: `learning`, `tutorial`, `mastery`, `beginner`, `learning plan`, `learning methods`, `course`

## File Structure

```

./study/
├── logs/
│   └── YYYY-MM-DD-learning-log.md    # Daily learning log
├── docs/                             # Learning materials
└── learning-tracker.md               # Learning tracker (state persistence)

```

## Core Features

### Learner Modeling

The system continuously accumulates evidence labels across the following dimensions (append-only, never overwritten):

| Dimension | Description | Example Labels |
|----------|------------|----------------|
| Learning Type | Preferred learning approach | Exploratory / Structured / Hybrid |
| Cognitive Style | Information processing mode | Visual / Logical / Practical / Social |
| Motivation Source | Driving factors | Goal-driven / Interest-driven / Achievement-driven |
| Time Preference | Study timing patterns | Morning / Night / Fragmented / Immersive |
| Social Preference | Collaboration tendency | Independent / Group / Mentor-dependent |
| Learning Pace | Progress characteristics | Incremental / Leaping / Depth-first |

### Three-Phase Closed Loop

1. **Project Identification & State Recovery** — Automatically detects and restores prior learning state  
2. **Environment Initialization** — Creates a standardized learning directory structure  
3. **Execution & Dynamic Modeling** — Adjusts learning paths in real time and records behavioral evidence  

## Usage Examples

```

User: I want to learn Rust programming
→ Skill activates the three-phase loop
→ Initializes study/ directory structure
→ Begins adaptive instruction

User: Help me create a 3-month machine learning study plan
→ Identified as a long-term learning plan
→ Establishes phased goals and milestones
→ Generates a structured learning path

```

## Core Principles

1. **Full State Externalization** — All states are explicitly persisted via the file system; implicit memory is prohibited  
2. **Append-Only Evidence Modeling** — Learner models accumulate evidence without overwriting history  
3. **Traceable Decisions** — All adjustments must include recorded rationale  
4. **Language Adaptation** — Automatically detects and adapts to user language  
5. **Log Continuity** — Avoids duplication and maintains session coherence
