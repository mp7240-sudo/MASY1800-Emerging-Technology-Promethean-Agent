# Assignment 4 Promethean Technology Classification Agent

Meilin Pan | MASY1-GC 1800 | version 0.2-student

Specialist: agents/promethean_agent. Start with its specialist_instructions.md and records/agent_record.md. This working copy preserves the supplied frozen core and standard-library tools.

## Judgment and evidence

Student judgment: Provisional Breakthrough. Broad technological significance does not authorize bank adoption. Three v0.2 cases and one preserved v0.1 primary output passed the basic validator. Sources, limitations, revision history, and comparisons are in agents/promethean_agent/records/. Precise general-label stability under fixed evidence is unproven because retrieval varied; the meeting-summary run withheld a firm category. No measured bank benefits or general reliability claim.

## Reproduce

Run from the repository root with Python 3:

```sh
python3 tools/check_frozen_core.py
python3 tools/build_prompt.py --agent agents/promethean_agent --case agents/promethean_agent/cases/primary.json
python3 tools/validate_response.py agents/promethean_agent/responses/primary_response_v2.json
```

The generated packet uses the shared schema and specialist instructions. To reproduce the v0.2 source-complete setup, supply your authorized copy of Fortino Chapter 11 (August 2026 draft rev 0.1) as course reference alongside the packet, or append its extracted text as done in the recorded runs. The original local v0.2 packets contain extracted chapter text and are excluded from Git by the scaffold's work/ ignore rule. They contain captions but no figure images. Do not infer identical outputs from a new run; record model, date, source access, prompt, and actual raw response.

No API key is needed. Use ChatGPT for the model run. The local tools only build prompts and validate basic structure. Use fresh conversations without previous outputs. Preserve raw results unchanged. The validator does not establish factual or reasoning correctness.

## Repository contents

- core/ and tools/: unchanged frozen course architecture
- agents/promethean_agent/: metadata, instructions, three cases, four raw responses, and review records
- agents/promethean_agent/records/v0_1_configuration/: original instructions and metadata
- docs/, examples/, agents/_template/: original scaffold supporting materials
- work/: local generated prompt packets, excluded from Git

This repository is a course working copy. No license is added to third-party course materials. Original scaffold documentation is retained in README.md.
