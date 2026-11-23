# AEGIS

**An independent check on every purchase your AI agent makes: before it decides, before it pays, and after it acts.**

Built for the Flipkart APM '29 problem statement: *It's 2040. Everyone has a personal AI agent that carries out their day-to-day tasks. Outline the ramifications and create a digital product that helps protect people from it.*

## Problem
AI agents that shop on a user's behalf can be steered by vendors (sponsored ranking, injected content, post-quote price creep) or simply get an instruction wrong. Users cannot easily notice, prove or dispute these failures.

## Solution
One protective layer between a user's AI agents and purchase outcomes, on-device and for the user only.

1. **Decision check:** Is the agent's pick right for the user's priorities?
2. **Deal check:** Does the cart match what was quoted, line by line?
3. **Rule and evidence check:** After payment, was a user rule broken? Evidence is sealed and a dispute can be filed in one tap.

## Features (built in the prototype)
- **Decision integrity:** re-scores the agent's choice on the user's priorities using verified information.
- **Transaction integrity:** compares cart and quote before payment; any gap holds the order.
- **User control:** limits, preferences and priorities the agent must follow; pause or stop anytime.
- **Recourse:** flags rule breaks, seals timestamped evidence on the device, one-tap dispute.

## Success metric
**North Star:** safely completed agent purchases per weekly active user, with a guardrail on missed violations and supporting metrics for protected coverage and intervention resolution.

## Run the prototype
Open `index.html` in a browser.
