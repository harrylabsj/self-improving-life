## Description: <br>
Holistic life satisfaction and balance optimization across health, relationships, work, finances, learning, leisure, and personal growth for life audits, life wheel reviews, burnout prevention, routine resets, quarterly reflection, habit alignment, and systematic self-improvement. <br>

This skill is ready for commercial/non-commercial use. <br>

## Publisher: <br>
[harrylabsj](https://clawhub.ai/user/harrylabsj) <br>

### License/Terms of Use: <br>
MIT-0 <br>


## Use Case: <br>
External users and agents use this skill to review life satisfaction across health, relationships, work, finances, growth, and leisure, then turn imbalances into practical routines, transition plans, or short experiments. <br>

### Deployment Geography for Use: <br>
Global <br>

## Known Risks and Mitigations: <br>
Risk: Life audits can include sensitive health, relationship, work, and finance reflections. <br>
Mitigation: Keep details minimal unless the user asks to record them, and store or delete local notes according to the user's privacy needs. <br>
Risk: The helper script can create a local life-assessment Markdown file in the current directory. <br>
Mitigation: Run the helper only in an intended directory and review, move, or delete the generated file if it contains private information. <br>


## Reference(s): <br>
- [ClawHub skill page](https://clawhub.ai/harrylabsj/self-improving-life) <br>
- [README.md](artifact/README.md) <br>
- [Life wheel assessment template](artifact/assets/LIFE_WHEEL_TEMPLATE.md) <br>
- [Quick life assessment helper](artifact/scripts/quick-life-assessment.sh) <br>


## Skill Output: <br>
**Output Type(s):** [Text, Markdown, Guidance, Shell commands, Files] <br>
**Output Format:** [Markdown guidance with optional local assessment files and shell command snippets] <br>
**Output Parameters:** [1D] <br>
**Other Properties Related to Output:** [May produce local life-assessment Markdown logs when the helper script is used.] <br>

## Skill Version(s): <br>
1.1.0 (source: server release evidence and artifact _meta.json) <br>

## Ethical Considerations: <br>
Users should evaluate whether this skill is appropriate for their environment, review any generated or modified files before relying on them, and apply their organization's safety, security, and compliance requirements before deployment. <br>
