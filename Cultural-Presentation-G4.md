# Global Scrum Team G4: Intercultural Collaboration Under Time Pressure

**Course:** IKHT, BINT24, Provadis Hochschule  
**Presenters:** Luca Doerner, Anton Reinicke, Janek Thor Becker  
**Target duration:** 8:50 minutes plus brief handovers  
**Format:** Nine slides; speakers alternate after every slide  

## Presentation Overview

| Slide | Topic | Speaker | Target time |
| ---: | --- | --- | ---: |
| 1 | Introduction | Luca | 0:40 |
| 2 | Use Case Overview | Anton | 0:50 |
| 3 | Team Composition | Janek | 1:00 |
| 4 | Communication Styles | Luca | 1:10 |
| 5 | Challenges | Anton | 1:10 |
| 6 | Solutions: Operating Model | Janek | 1:05 |
| 7 | Solutions: Leadership and Trust | Anton | 1:00 |
| 8 | Outcome and Evaluation | Luca | 0:55 |
| 9 | Lessons Learned and Reflection | Janek | 1:00 |
|  | **Total** |  | **8:50** |

---

## Slide 1 - Introduction

**Speaker:** Luca  
**Target time:** 0:40

### On the slide

- Eight people, four countries, one fixed launch date
- Fully remote and no shared team history
- Focus: turning cultural diversity into usable perspectives
- Central claim: the main risk is implicit coordination, not diversity itself

### Speaker notes

Our case follows Global Scrum Team G4, a fictional team developing a mobile fitness app. Eight colleagues in Germany, the United States, India and Japan must deliver within eight months, although they have never worked together or met in person. We examine how team composition, communication and leadership affect delivery. Our central argument is that diversity is not the problem by itself. The real risk is an operating model based on implicit agreement, unclear decision rights and live meetings that cannot include everyone. The case covers formation and the first two sprints; later results are forecasts, not observed facts.

**Handover:** Anton now gives a short overview of the project conditions.

---

## Slide 2 - Use Case Overview

**Speaker:** Anton  
**Target time:** 0:50

### On the slide

- Mobile fitness app: tracking, wearables and social features
- Eleven three-week sprints from June 2026 to February 2027
- Fixed deadline, flexible scope and a strict Definition of Done
- No common working-hours window across all four locations

### Speaker notes

The product combines workout tracking, progress statistics, wearable integration and social functions. These features create dependencies around sensors, privacy and international user expectations. The team has about eleven three-week sprints. The launch date is fixed, so the Product Owner may reduce scope through MoSCoW prioritisation. Quality is not flexible: every increment needs tests, peer review, English documentation and no critical defects. Geography is a structural constraint. The US working day starts five hours after the Japanese day ends, so no normal all-hands slot exists.

**Handover:** Janek will show why the team's composition both helps and intensifies this situation.

---

## Slide 3 - Team Composition and Development

**Speaker:** Janek  
**Target time:** 1:00

### On the slide

- German PO, US Scrum Master and six full-stack developers
- Two Indian specialists: sensors/performance and architecture/privacy
- Diversity: four national backgrounds, 42-year age range, education and DISC preferences
- **Belbin:** many Implementers; no Plant or Monitor Evaluator
- **Tuckman:** forming in Sprint 0, early storming in Sprint 2

### Speaker notes

Leadership is divided between a German Product Owner and a US Scrum Master. Six full-stack developers add flexibility, while Dev1 and Dev3 hold specialist knowledge in sensors, architecture and privacy. The team also spans 42 years of age, different educational experiences and different DISC preferences. Most profiles lean toward Steadiness or Conscientiousness, which supports reliable work but can delay disagreement. Belbin reveals a similar pattern: the team has several Implementers and Completer Finishers, but no Plant for generating alternatives and no Monitor Evaluator for independent review. Tuckman's model places Sprint 0 in forming and the architecture conflict in early storming. Norming and performing are goals, not achieved stages. These models describe possible team patterns; they do not define any individual.

**Handover:** Luca now connects those patterns to the team's communication failure.

---

## Slide 4 - Communication Styles: Hofstede and Hall

**Speaker:** Luca  
**Target time:** 1:10

### On the slide

> "Why was the integration not completed?"

- **Hall:** explicit request or contextual blame?
- **Hofstede:** different expectations about hierarchy, voice and responsibility
- Silence can be caution, not consent
- Country scores are hypotheses at group level, never individual predictions

### Speaker notes

This message captures the central communication problem: "Why was the integration not completed?" Hall distinguishes low-context communication, where meaning is stated explicitly, from high-context communication, where relationships, status and surrounding cues carry more meaning. A low-context sender may intend a precise request for facts. A high-context recipient may infer public blame from the wording, audience and hierarchy. Hofstede adds testable hypotheses. Differences in power distance may affect willingness to challenge a leader, while individualism may affect comfort with public responsibility. But national scores describe tendencies, not named people. The team must verify preferences directly. In this case, silence is mistakenly treated as consent, so an indirect technical concern remains unresolved until it becomes a blocker.

**Handover:** Anton will diagnose how that single misunderstanding connects to wider team challenges.

---

## Slide 5 - Challenges: From Task Conflict to Relationship Conflict

**Speaker:** Anton  
**Target time:** 1:10

### On the slide

| GRPI area | Diagnosis |
| --- | --- |
| Goals | Fixed date, disputed scope trade-offs |
| Roles | Formal roles, unclear technical accountability |
| Processes | No response, decision or escalation rules |
| Relationships | Low trust and a public face threat |

- Pseudo-consensus hides disagreement
- Time zones create unequal access to decisions
- Productive task conflict escalates into process and relationship conflict

### Speaker notes

The GRPI model shows that the failure is systemic. At the goal level, everyone accepts the launch date but disagrees about scope and technical debt. Formal roles exist, but technical accountability is diffuse. Processes lack response deadlines, decision owners and escalation rules. Relationships are fragile because the team has no shared history. This creates pseudo-consensus: direct communicators think a decision is closed, while cautious members still have concerns. A useful task conflict about architecture then becomes a process conflict when nobody owns the decision. The public correction finally turns it into a relationship conflict. Different conflict preferences, from competing to avoiding or accommodating, strengthen this sequence. Time zones add unequal influence because specialists may be absent from live discussions. However, technical complexity, deadline pressure or limited capacity could produce the same delay, so culture is only one possible explanation.

**Handover:** Janek will translate this diagnosis into concrete operating rules.

---

## Slide 6 - Solutions: A Shared Operating Model

**Speaker:** Janek  
**Target time:** 1:05

### On the slide

- Async-first updates and written decisions in shared tools
- Every site answers: **agree, concern or question**
- RACI matrix for product, process, architecture, privacy and quality
- Rotating meeting times and named specialist backups
- Rotating challenge role to compensate for the missing Monitor Evaluator
- Feedback on artefacts: observation, impact and requested next step

### Speaker notes

The first solution is an async-first team charter. Jira tracks work, Confluence records decisions, Git supports review and Teams carries updates. Every critical proposal names its options, evidence, owner and deadline. Each site must answer "agree," "concern" or "question"; silence never counts as consent. A RACI matrix separates who performs work from who is accountable for product, process, architecture, privacy and quality. Inconvenient meeting times rotate, while specialist pairing creates backups and transfers knowledge. Because Belbin identified no Monitor Evaluator, a rotating challenge role gives one developer the legitimate task of presenting the strongest counterargument. Feedback targets an artefact rather than a person: state the observed issue, its delivery impact and the requested next step. The Scrum Master mediates unresolved conflict within 48 hours.

**Handover:** Luca will add the leadership and trust conditions that make these rules effective.

---

## Slide 7 - Solutions: Leadership and Psychological Safety

**Speaker:** Anton  
**Target time:** 1:00

### On the slide

- **Directive PO:** backlog, release scope and urgent compliance decisions
- **Cooperative SM:** planning, retrospectives and input from every site
- **Transformational leadership:** shared purpose and individual development
- **Psychological safety:** challenge ideas and report blockers without humiliation
- Use video for conflict and relationships; use documents for coordination

### Speaker notes

One leadership style cannot fit every situation. The Product Owner should be directive when deciding backlog order, release scope and urgent compliance questions. The Scrum Master should use cooperative leadership in planning and retrospectives, deliberately collecting input from every site. Both should use transformational leadership to connect daily tasks with a shared purpose: a stable and responsible global product. This division preserves decision speed without excluding technical evidence. It also supports psychological safety, which Edmondson defines as a shared belief that interpersonal risk-taking is safe. Safety does not lower standards; it allows members to report blockers and challenge proposals without humiliation. Leaders must respond predictably and visibly follow up. Documents support coordination, but video and rotating pair calls remain necessary for conflict repair and relationship building.

**Handover:** Anton will separate the one observed result from the outcomes we expect after these changes.

---

## Slide 8 - Outcome and Evaluation

**Speaker:** Luca  
**Target time:** 0:55

### On the slide

- **Observed:** Milestone 1 delayed after an unresolved dependency
- **Forecast by Sprint 5:** clearer ownership and earlier risk reporting
- Key indicators:
  - at least 90% of major decisions include all four sites
  - fewer than 10% of decisions reopen because context was missing
  - all known critical domain risks recorded before implementation
- Expected release: smaller scope, stable quality, Sprint 11

### Speaker notes

We must distinguish evidence from expectation. The only observed project result is the delayed Milestone 1 and the corrective decision in the Sprint 2 retrospective. The later outcome is a forecast. By Sprint 5, the team expects clearer ownership, earlier risk reporting and fewer reopened decisions. It will test this through the decision log, risk timestamps and Definition-of-Done results. The longer-term forecast is a reduced but stable release in Sprint 11, possibly with fewer social features to protect wearable quality and privacy. Improved numbers would still not prove that culture caused the original problem; easier backlog items, growing familiarity or scope reduction could also explain them.

**Handover:** Janek closes with the lessons and our critical reflection.

---

## Slide 9 - Lessons Learned and Reflection

**Speaker:** Janek  
**Target time:** 1:00

### On the slide

- Separate intention from effect and verify meaning
- Staff global teams for role balance and time-zone coverage, not availability alone
- Tools coordinate work; they do not create trust
- Diversity improves decisions only when different perspectives become visible

### Speaker notes

We take four lessons from the case. First, intention and effect are different: directness can protect delivery and still damage trust, while politeness can preserve a relationship and still hide a blocker. Meaning must be confirmed. Second, project managers should staff global teams for role balance, specialist backups, language confidence and time-zone coverage, not availability alone. Third, digital tools can document work but cannot create trust; relationship time must be designed deliberately. Fourth, diversity improves performance only when different perspectives enter the decision. This is consistent with research showing that its benefits depend on team processes. The key takeaway is simple: explicit collaboration rules turn cultural difference from a delivery risk into a source of better decisions.

---

## Reference Slide - Not Included in Speaking Time

- Aritz, J., & Walker, R. C. (2014). Leadership styles in multicultural groups.
- Belbin, R. M. (2010). *Team Roles at Work*.
- Edmondson, A. C. (1999). Psychological safety and learning behavior in work teams.
- Hall, E. T. (1976). *Beyond Culture*.
- Hofstede, G., Hofstede, G. J., & Minkov, M. (2010). *Cultures and Organizations*.
- Jehn, K. A., Northcraft, G. B., & Neale, M. A. (1999). Diversity, conflict and performance.
- Minkov, M., & Kaasa, A. (2021). A test of Hofstede's model of culture.
- Stahl, G. K., Maznevski, M. L., Voigt, A., & Jonsen, A. (2010). Effects of cultural diversity in teams.
- Tuckman, B. W. (1965). Developmental sequence in small groups.
- Abdullah, L. (2026). IKHT Lecture Notes 02, 04, 05 and 06.

## Delivery Notes

- Keep each handover to one sentence and change speaker while the next slide appears.
- Do not read the slide bullets verbatim; use the speaker notes as the spoken narrative.
- Rehearse once with a timer. If the presentation exceeds nine minutes, shorten examples before removing theory.
- Keep the reference slide available for questions but do not present it during the timed section.