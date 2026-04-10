
# NetOps Triage Agent

Scenario-based network operations tool inspired by real-world service provider environments. 

## Overview

This app simulates how NetOps teams think through issues:

- What is happening?
- What does it indicate?
- What’s the impact?
- What should happen next?

It focuses on **decision-making**, not tools.

## Features

**Scenario Explorer**
- Signal → meaning → actions → impact

**Persona Lens**
- NetOps, NOC, SRE, Security, Executive
- What they care about + how they think

**Value Translation**
- Technical → operational → business context

**Action Plan**
- Triage thinking
- Next steps
- Stakeholder questions
- Communication framing

## Example Scenarios

- Latency spikes (shared path issues)
- MPLS / QoS saturation
- BGP routing anomalies
- DNS failures
- API abuse / DDoS patterns
- SD-WAN instability
- VPN auth issues

## Why This Matters

Most incidents aren’t obvious.  
This tool helps:
- Identify the real problem faster
- Separate ops vs security signals
- Reduce bad escalation
- Communicate clearly under pressure

## Tech Stack

- Python
- Streamlit

## Run Locally

```bash
python3 -m venv venv
source venv/bin/activate
pip install streamlit

streamlit run app.py
