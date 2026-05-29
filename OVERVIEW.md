# Project Overview

Below is an interactive chart showing the project phases. **Click on a box** to jump to that section in the [Checklist](./CHECKLIST.md).

```mermaid
flowchart TD
    Phase1[Phase 1: Ideation] --> Phase2[Phase 2: Proposal]
    Phase2 --> Phase3[Phase 3: Implementation]
    Phase3 --> Phase4[Phase 4: Defense]

    click Phase1 "./CHECKLIST.md#phase-1-ideation-week-3" "Go to Phase 1"
    click Phase2 "./CHECKLIST.md#phase-2-proposal-week-6" "Go to Phase 2"
    click Phase3 "./CHECKLIST.md#phase-3-implementation-weeks-6-10" "Go to Phase 3"
    click Phase4 "./CHECKLIST.md#phase-4-defense--deliverables-week-11" "Go to Phase 4"
```

## How it works
This uses **Mermaid.js**, which is supported natively by GitHub and VS Code. 
- The `click` command assigns a link to the node.
- In VS Code, you may need to `Ctrl + Click` depending on your settings.
- On GitHub, these links will navigate within the repository.
