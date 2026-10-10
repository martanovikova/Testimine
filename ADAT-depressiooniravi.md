# AI Decision Audit Trail (ADAT)

> **Authorship statement**: An AI wrote all of this document (the AI
> system is named in the metadata), during and after working sessions
> with the researcher listed below. The Tier 1 summary and the Tier 2
> Decision Log entries are the AI's own account of what it contributed.
> The researcher has not edited them. Where the researcher disagrees
> with the AI's account or wants to add to it, this is recorded in the
> Researcher Commentary section, with a reference to the specific entry
> and field. An entry marked `Accepted` means the researcher agrees the
> AI's account is accurate. An entry marked `Disputed — see Commentary`
> means the researcher disagrees on one or more fields, and the
> objection is recorded in the researcher's own words.

## Metadata

| Field                    | Value                                          |
|--------------------------|------------------------------------------------|
| Project title            | esimene ülesanne                               |
| Project identifier       | None                                           |
| AI system(s)             | Claude (configured model `claude-opus-5-5`), Claude Cowork desktop app. The model actually serving a session can differ from the configured one. |
| Session date range       | 2026-10-07 – 2026-10-11                        |
| Total sessions logged    | 1 conversation, continued over 5 days          |
| Human decision-makers    | Marta Novikova (author, main decision-maker)   |
| Final decision authority | Marta Novikova                                 |
| Reporting standards      | None selected                                  |
| Code repository          | https://github.com/martanovikova/Testimine     |
| ADAT specification       | v0.1                                           |

---

## Tier 1: AI Contribution Summary

*Accepted by the researcher on 2026-10-11.*

### Scope Statement

One AI system was used: Claude (configured model `claude-opus-5-5`) in the Claude Cowork desktop app, in one conversation that ran from 2026-10-07 to 2026-10-11.

**What the AI was used for:**

- **Literature search:** through the PubMed and ClinicalTrials.gov connectors, plus news sites and company press releases for unpublished results (COMP005, CYB003) and regulatory status.
- **Summarising papers:** mostly from abstracts. The full text was read only for Metaxa 2024.
- **The reading list:** building and maintaining it in a Claude Doc.
- **Explaining methods:** blinding and expectancy, types of placebo, response and remission, exploratory findings, conflicts of interest, and total versus specific treatment effect.
- **Critique:** commenting on the researcher's notes and on her final report.
- **A draft text:** the AI also wrote an Estonian draft text from the researcher's notes. The researcher states she did not use it in her final report.

**What the AI was not used for:** forming the researcher's position, writing the final report (she wrote it herself, in Estonian), data analysis or code.

**Limitations of the AI-assisted search:**

- The search was not systematic.
- Most papers were read only as abstracts.
- Literature from before 2010 was checked only in PubMed. That search found 13 records; the two clinical papers (Sercl 1961, Reda 1964) have no abstract and could not be read, so that period is represented by the Rucker 2016 systematic review.
- Two further databases, Europe PMC and OpenAlex, were tried but refused requests (rate limits).

### Decision Domain Map

| Domain                       | AI role characterization        | Entries |
|------------------------------|---------------------------------|---------|
| Study design (review scope)  | Explained the field (DL-002), challenged a classification (DL-003), confirmed an exclusion (DL-004), proposed an exclusion the researcher kept on her own reasoning (DL-005), refined a rule the researcher set (DL-006) | 5 |
| Causal framework             | —                               | 0       |
| Variable operationalization  | —                               | 0       |
| Statistical modeling         | —                               | 0       |
| Sensitivity analyses         | —                               | 0       |
| Code implementation          | —                               | 0       |
| Manuscript language          | —                               | 0       |
| Interpretation               | Not logged as entries; see the last Key Decision Point | 0 |

The entries cover only scope decisions. Much of the AI's work was interpretive: summarising evidence, explaining trial designs, and critiquing the researcher's text. That work is not logged as separate decisions, so this table understates the AI's influence on interpretation.

### Key Decision Points

**1. The topic.** The AI wrote overviews of MDMA for PTSD and of psilocybin for depression before the researcher chose a topic. The second overview compared psilocybin favourably (a larger field, more varied sponsors). The researcher rejected the MDMA scope (DL-001) and chose psilocybin for depression (DL-002). She gave her own reasons: more research, more sponsors and personal interest. The AI's framing may still have contributed.

**2. Where "psilocybin" and "psychedelic" end.** The AI's check that CYB003 is a deuterated analog, not psilocybin, changed how that compound is classified: it is listed separately and not pooled with psilocybin (DL-003). Excluding esketamine was the researcher's own decision; the AI added the explicit 5-HT2A definition and pointed out a source that disagrees (DL-004).

**3. Which interventions count.** The AI was the first to exclude microdosing, without being asked. The researcher kept the exclusion on her own reasoning, that microdosing is a different intervention without a psychedelic experience, and turned down the AI's suggested compromise (DL-005).

**4. What role imaging plays.** The researcher limited imaging to mechanism context linked to clinical outcomes. The AI's search, which emphasised a critique of the main imaging claims, came before that decision (DL-006).

**5. Interpretation (not logged as entries).** The AI introduced or stressed most of the methodological tensions that appear in the researcher's report:

- failed blinding and expectancy;
- small-study effects;
- differences between control conditions;
- conflicts of interest;
- total versus specific treatment effect;
- the difference between a non-significant result and no effect.

The researcher raised the placebo-as-treatment question herself. Her conclusion, that psilocybin probably has an antidepressant effect but is unlikely to be clearly better than existing treatments, and that its value may lie in widening patient choice, was already in her notes before the AI's draft text. While reviewing the final report, the AI suggested justifying the focus on treatment-resistant depression by unmet need rather than by strength of evidence. Whether she adopted that suggestion is not recorded here.

### Verification Statement

**How AI outputs were checked:**

- References were retrieved through the PubMed and ClinicalTrials.gov connectors, not from the AI's memory.
- The AI labelled its claims as verified, recalled or inferred.
- Unpublished results (company press releases) were marked as not peer-reviewed.
- The researcher read parts of several original articles and checked the AI's claims against them.

**AI errors found during the work:**

- A garbled citation ("Metaspa") was corrected to Metaxa 2024 by the AI.
- The AI labelled the placebo in Rucker 2026 and COMP005 as "inert" without checking. It later corrected this to "not checked", and the researcher supplied Rucker's placebo type.
- The AI's tool for reading the doc skipped all italic text, which held the researcher's main notes. The AI's first review (sections "empty", "no opinion stated") and its first draft text were therefore built on incomplete notes. The researcher pointed this out, and the AI re-read the notes and redid the work.
- The AI stated that Metaxa 2024 does not link the larger self-report effects to expectancy, and presented that explanation as its own idea. The researcher's reading of the full text led the AI to find the passage in the limitations section. The researcher also identified the authors' other explanation, in the discussion section (clinicians overestimating baseline severity).

**Researcher errors caught by the AI:** for example, "max 6 months" of follow-up (12-month follow-ups exist), and calling a waitlist "not a parallel control". The researcher corrected both in her notes.

**Remaining unverified:** a few statements were marked as recalled and never checked, for example that nicotinamide does not cause the skin flush that niacin does. They should not be relied on without checking.

---

## Tier 2: Decision Log

[Entries are added here in order, each with a status tag: `Accepted` or
`Disputed — see Commentary`. DL-001 was drafted and rejected; see
Researcher Commentary.]

### DL-002 | 2026-10-07 | design | Accepted

**Decision question**: After rejecting the MDMA/PTSD scope (see the note on DL-001 in Researcher Commentary), should the project's evidence review be limited to psilocybin-assisted therapy for depression?

**AI contribution**: In its first broad review, the AI had called psilocybin for depression "the most studied area, with mixed results". At the researcher's request, it then produced the same overview it had made for MDMA/PTSD:

- **PubMed counts:** 1,273 records mention psilocybin and depression, and 77 are tagged as randomised trials.
- **Oldest and newest:** the oldest indexed record is from 1961 and the first randomised trial from 2010 (in cancer patients). The newest trial is Rucker 2026 (Nature Medicine, n=60, MADRS −10.41, 95% CI −14.86 to −5.95).
- **ClinicalTrials.gov:** 106 registered interventional studies, 31 completed and 60 ongoing or planned, with phase 3 trials from several sponsors.
- **Comparison:** the AI compared this field favourably with MDMA/PTSD. It is larger and its sponsors are less concentrated.
- **Caveats it flagged:** both counts overstate the number of real depression trials; Cybin's CYB003 may not be psilocybin itself (from memory, unverified); and Rucker 2026 is a small feasibility trial.
- **Framing:** it called the wide spread of results (Rucker d = −1.70, COMP005 −3.6 MADRS points, EPISODE null) "probably the most interesting thing to explain in your summary".

The AI did not recommend choosing this topic over any other.

**Researcher constraints**: The researcher raised both MDMA/PTSD and psilocybin/depression herself as candidate topics. She rejected MDMA/PTSD saying she had "changed my mind on what topic to explore". She asked for the psilocybin/depression overview and then said "ok" to the offer to log the switch. She did not state why she prefers this topic.

**Resolution**: The scope is psilocybin-assisted therapy for depression. Because the field is larger, a selection or screening step will be needed. The spread of trial results, and possible reasons for it (unblinding, trial size, comparator, patient population), becomes a central question. One question is still open: whether depression secondary to serious illness (the cancer trials) is in scope.

**AI role**: `explained`

**Counterfactual assessment** (uncertain): There is too little basis to judge whether she would have chosen psilocybin/depression without AI involvement.
*Reasoning*: The researcher named the topic herself. However, she did so after two AI overviews. The second compared psilocybin/depression favourably with MDMA/PTSD (larger field, more independent sponsors) and called its results tension "interesting", and that framing could have steered the choice. Nothing in the session shows her prior interest or reasons.

### DL-003 | 2026-10-07 | design | Accepted

**Decision question**: Should trials of CYB003 count as evidence for psilocybin in depression?

**AI contribution**: The AI first noted, from memory and unverified, that CYB003 might not be psilocybin. When asked, it checked news sources: Psychiatric Times describes CYB003 as "a deuterated psilocybin molecule" and Fierce Biotech as "a deuterated psilocybin analog". Its phase 3 programme (PARADIGM) tests it added to an existing antidepressant, unlike Compass's psilocybin-alone trials. The AI found no peer-reviewed CYB003 paper in PubMed. It offered two options: exclude it from the psilocybin evidence, or label it as a related molecule.

**Researcher constraints**: The researcher asked the AI to verify the claim, then chose to include CYB003 labelled as a related molecule.

**Resolution**: CYB003 is listed separately as a "related molecule". It is not pooled with psilocybin evidence.

**AI role**: `challenged`

**Counterfactual assessment** (moderate): Without the AI, CYB003 might have been counted as psilocybin.
*Reasoning*: CYB003 appears in ClinicalTrials.gov searches for psilocybin, and the registry entries don't make clear that it is a different molecule. The researcher showed no prior awareness of this. On the other hand, the company's own descriptions say "deuterated", so a careful reader could have caught it.

### DL-004 | 2026-10-07 | design | Accepted

**Decision question**: Should esketamine (and ketamine) be excluded from a review of psychedelic therapy for depression?

**AI contribution**:

- The AI excluded ketamine/esketamine on its own initiative in the first broad review, and the researcher confirmed that exclusion in a doc comment.
- When asked, it verified that esketamine is FDA-approved: in 2019 with an oral antidepressant, and in 2025 alone.
- It agreed with the researcher's reason (esketamine is a dissociative NMDA antagonist, not a classic 5-HT2A psychedelic; this pharmacology was stated from memory).
- It pointed out that the boundary is disputed, citing Muthukumaraswamy 2021, which groups ketamine with psychedelics. It recommended stating the definition explicitly so that a reader cannot object.

**Researcher constraints**: The researcher proposed the exclusion herself, reasoning that esketamine is not a psychedelic.

**Resolution**: Esketamine and ketamine are excluded. The scope defines "psychedelic" as classic serotonergic 5-HT2A psychedelics and notes that some sources disagree.

**AI role**: `confirmed`

**Counterfactual assessment** (low): The exclusion would very likely have happened anyway.
*Reasoning*: The researcher reached the exclusion and its reason herself. The AI's contribution was making the definition explicit and pointing out the counter-example in her own source. That makes the decision easier to defend but doesn't change it.

### DL-005 | 2026-10-08 | design | Accepted

**Decision question**: Should microdosing studies (repeated sub-perceptual doses) be part of the evidence on psilocybin therapy for depression?

**AI contribution**:

- **Original exclusion:** the AI put microdosing on the excluded list on its own initiative, both in the first broad review and in the psilocybin/depression scope.
- **Recommendation when asked:** keep microdosing out of the core evidence, because it is a different intervention (repeated low doses, usually without therapy) and says little about the 25 mg therapy model.
- **Optional extra row:** an "expectancy contrast" row citing Murphy 2024. In that well-blinded LSD microdosing trial in healthy men, participants felt more creative but objective tests showed no effect, which the authors partly attribute to placebo. The AI noted the limits (LSD, healthy volunteers, creativity not depression).
- **Ongoing trial:** LSDDEP2, a microdosing trial for depression, is running, but no results were found.

**Researcher constraints**: The researcher raised the question herself after reading the scope list. She decided to exclude microdosing entirely and did not take up the AI's suggested contrast row.

**Resolution**: Microdosing is excluded with no contrast row. Expectancy and unblinding will be argued from the psilocybin trials and the methods literature (e.g. Muthukumaraswamy 2021) instead.

**AI role**: `proposed`

**Counterfactual assessment** (uncertain): There is too little basis to judge.
*Reasoning*: The AI excluded microdosing first, unprompted, and the researcher's question came from reading that list, so the AI's framing shaped the starting point. However, she reviewed the question herself and turned down the AI's middle-ground suggestion, which shows an independent judgment. Nothing in the session shows what she would have chosen otherwise.

### DL-006 | 2026-10-08 | design | Accepted

**Decision question**: Should brain-imaging studies (fMRI, MR spectroscopy, imaging biomarkers) count as evidence in the review of psilocybin therapy for depression, and if so, in what role?

**AI contribution**:

- **First answer:** the researcher asked whether imaging studies should be included at all, and the AI answered. The AI's exact wording is no longer available to it, because the earlier part of the session was condensed. Its record keeps only the outcome described below.
- **Search:** at the researcher's request, the AI searched for studies that link imaging to clinical outcomes and listed six:
  - Carhart-Harris 2017: open-label; amygdala blood flow and default-mode connectivity correlated with symptom change.
  - Daws 2022: lower network modularity linked to improvement, with no such change under escitalopram.
  - Doss 2022: a critique of Daws 2022 (inconsistent primary outcome, one-tailed test, non-significant interaction, regression to the mean).
  - Doss 2021: cognitive flexibility rose but did not correlate with the antidepressant effect.
  - Copa 2024: baseline connectivity predicted response, in the same patients as Daws 2022.
  - Wong 2025: a systematic review of nine small biomarker studies, which it describes as "putative".
- **Limitations it flagged:** the studies are small, several reanalyse the same patients, none ties imaging to a placebo-controlled comparison, and Doss 2022 is the main counterpoint.
- **The "reset" question:** asked whether it is established that psychedelics "reset" brain chemistry, the AI wrote a note saying that a lasting reset is not established in humans.
- **Afterwards:** the AI wrote the scope wording into the doc ("only when they link imaging to patients' clinical outcomes, and only as mechanism context, not as evidence that the treatment works") and labelled those reading-list rows "Mechanism (imaging, context only)". Later, while reviewing the final report, it applied the rule to flag that the "less emotional blunting" advantage rests on one fMRI study.

**Researcher constraints**:

- The researcher raised the inclusion question herself.
- She framed the search: links to "how patients actually feel", "in any (positive or negative) way".
- She asked what had been decided, and then set the rule in her own words: "keep imaging as a tool and not a result itself, only in research that actally links it to clinical results".

**Resolution**: Imaging studies are included only when they link imaging to patients' clinical outcomes. They serve as mechanism context and never as evidence that the treatment works, and they are listed separately in the reading list.

**AI role**: `refined`

**Counterfactual assessment** (uncertain): There is not enough basis to judge.
*Reasoning*: The rule is in the researcher's own words, and she started the line of inquiry. However, she set it after reading the AI's search results, which stressed a methodological critique (Doss 2022) and the small, overlapping samples. That framing may have shaped "not a result itself". The AI's first answer on whether to include imaging can't be reconstructed, so its influence at that step is unknown.

---

## Researcher Commentary

[Contains only the researcher's own words, recorded verbatim.]

**Re DL-001 (rejected, not appended)**: An entry was drafted on 2026-10-07
recording a decision to narrow the project scope to MDMA-assisted therapy
for PTSD. The researcher rejected it before it was appended. Researcher's
reason, verbatim: "ive changed my mind on what topic to expolre"

**Re DL-002, researcher constraints (supplement; entry accepted)**: "topic was chosen, because there is more reasearch and more different sponsors in this field. Additionally it offers more personal interest to the author."

**Re DL-005 (supplement; entry accepted)**: "The decision was made independently from AI's suggestions, based on the info provided by AI stating that microdosing studies don't yet have any strong conclusions."

**Re DL-005 (further supplement, added 2026-10-08)**: "AI presented some researc on the topic but didn't analize it thoroughly. Still decision stays as the author decides to believe that if there was strong evidence it would have come up with a small search too."

**Re DL-005 (further supplement, added 2026-10-08)**: "Additionally, microdosing is a different intervention from higher dose therapy plan. This project focuses on interventions that include "psychedelic trip" as a part of therapy."

**Re DL-006 (supplement; entry accepted, added 2026-10-11)**: "Researcher made her decision after reviewing the original papers AI provided on the topic."

---

## Appendix A: Glossary of AI Role Tags

| Tag            | Definition                                                        |
|----------------|-------------------------------------------------------------------|
| proposed       | AI originated the analytical approach or methodological choice    |
| refined        | AI improved or formalized an approach the researcher initiated    |
| implemented    | AI wrote code or text for a decision made by the researcher       |
| explained      | AI clarified a concept that informed the researcher's decision    |
| challenged     | AI raised a concern, limitation, or alternative not considered    |
| confirmed      | AI validated a decision the researcher had already reached        |
| co-developed   | Iterative joint development; contributions cannot be disentangled |

## Appendix B: Counterfactual Confidence Scale

| Level     | Interpretation                                                     |
|-----------|--------------------------------------------------------------------|
| high      | Strong reasons to believe the decision would have differed without AI. The knowledge is specialized and not in standard references, and the researcher had not indicated prior awareness. |
| moderate  | AI likely influenced the decision path, but the researcher might have reached a similar conclusion another way (colleagues, literature, trial and error). |
| low       | AI's contribution was marginal. The researcher was already heading this direction; AI sped it up or confirmed it. |
| uncertain | Not enough basis to judge. Declared honestly rather than estimated. |

These levels are qualitative judgments based on what could be observed,
not calibrated probabilities. Each assessment comes with explicit
reasoning so reviewers can evaluate the judgment for themselves.

## Appendix C: Referenced Reporting Standards

None selected as of 2026-10-07.
