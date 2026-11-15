# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

A single learner (the course author): a working software engineer comfortable with Python and pytest, new to AI evaluation. They study theory and code examples in the browser, then switch to VS Code and the terminal to build and run every evaluation themselves.

## Product Purpose

"Mastering AI Evals: From Basics to Hands-On" is a self-paced, browser-read course that takes an engineer from ad-hoc "vibe checks" to a production-grade evaluation practice: error analysis, heuristic metrics, LLM-as-a-Judge, golden datasets, CI regression gates, and online evals. Success means the learner can design, implement, calibrate, and gate evals on their own projects, entirely from local code they wrote.

## Positioning

Two mechanisms define the course:

1. **SWE Mental Model bridge.** Every core module maps eval concepts onto testing practice the learner already owns: Vibe Checking = Ad-hoc Logging, Heuristic Evals = Unit Tests, LLM-as-a-Judge = E2E Integration Tests, Golden Datasets = CI/CD Regression Suites.
2. **Zero-hallucination, production-grade precision.** Every metric, formula, range, tokenization assumption, and framework claim is verified against primary sources (original papers, official library docs) and cited. Nothing is simplified to the point of mathematical inaccuracy.

## Operating Context

- Pages are opened directly from disk (`file://`) by double-clicking `index.html`. No server, no build step, no network dependency.
- All course artifacts live under the project root (`/Users/amankum/learn/evals`) and reference each other with relative paths only.
- Practice happens outside the browser: the learner creates their own local lab directory, writes files in VS Code, and runs Python scripts and `pytest` from the VS Code terminal.
- Learner machine (verified 2026-11-02): macOS 27.2, Python 3.15.0, Ollama installed at `/usr/local/bin/ollama`, VS Code CLI `code` available.

## Capabilities and Constraints

- **Read-only portal.** No interactive widgets, code runners, run buttons, calculators, or in-browser evaluation. The site presents theory, code examples, and lab instructions only.
- **Every lab directs work to VS Code + terminal**, with explicit "copy this into a local file and run it" instructions.
- **Mental Model section** is mandatory in every core part, using the designated four-row analogy comparison.
- **Fact-checking gate:** formulas and metric mechanics are verified before any course text is written; boundaries (e.g., BLEU range, clipped counts, brevity penalty, smoothing, tokenizer dependence) are stated precisely, with citations.
- **Model provider:** provider-agnostic. Labs default to a local Ollama model; hosted APIs (OpenAI, Azure OpenAI) appear as side notes.
- **Offline-safe:** no CDN fonts, scripts, or stylesheets; all assets are local.
- **Curriculum (4 parts, newer topics folded in):**
  1. Foundations & Error Analysis (Vibe Checking ≈ Ad-hoc Logging)
  2. Heuristic & Reference-Based Metrics, incl. deterministic agent and safety checks (≈ Unit Tests)
  3. LLM-as-a-Judge, incl. agent/trajectory judging, judge calibration, RAG metrics, safety judges (≈ E2E Integration Tests)
  4. Golden Datasets, CI & Production, incl. synthetic data, red-team regression, online evals/OpenTelemetry GenAI (≈ CI/CD Regression Suites)
- **Requested surfaces:**
  - Part 1 "Mental Model Foundations" page with the SWE analogy comparison table.
  - Part 2 "String and Statistical Matching Metrics" page: verified BLEU and ROUGE-N mechanics, a Python example (nltk / rouge-score), and a local-execution note.
  - Lab "Building an Automated Evaluation Suite with PyTest": venv setup, `test_evals.py` with a hardcoded golden set, threshold assertion (e.g., accuracy ≥ 0.80), running pytest, and a static mock-terminal display of a passing run.
- **Verified 2026-11-02:** `nltk` 3.10.4, `rouge-score` 0.1.2 (with `numpy` 2.5.4, `absl-py`, `six`), and `pytest` 9.1.1 install and run on Python 3.15.0. Labs can target the learner's default interpreter.

## Brand Commitments

- Course title: "Mastering AI Evals: From Basics to Hands-On".
- Styling must follow the Impeccable design skill's rules (craft floor, anti-pattern bans, detector checks). Impeccable supplies design rules, not a prebuilt class library; the stylesheet is authored for this course and verified with Impeccable's detector.
- Voice: precise, engineer-to-engineer, no hype.

## Evidence on Hand

- No existing content, assets, logos, or imagery. The project folder was empty at init.
- No testimonials, learner metrics, or external endorsements exist; none may be invented.
- Citations must point to real primary sources (e.g., Papineni et al. 2002 for BLEU; Lin 2004 for ROUGE; Zheng et al. 2023 for MT-Bench/LLM-as-a-Judge).

## Product Principles

1. **Read here, build there.** The browser teaches; VS Code and the terminal are where every eval actually runs.
2. **Precision over simplification.** If a formula has a boundary, clip, penalty, or tokenizer dependency, the page states it exactly and cites it.
3. **Bridge from what engineers already know.** Each concept lands through its software-testing analogue before any code appears.
4. **Evidence before abstraction.** Error analysis on real traces comes before choosing metrics.
5. **Works offline, forever.** No server, build, or network required to read the course.
