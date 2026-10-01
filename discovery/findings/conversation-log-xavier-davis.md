# AI Conversation Log — Xavier Davis

Date: October 1, 2026

Project: SE 395-2, Team 3 — ecoPreserve

Section: Person C — Opportunity Analysis

This is a manually copied record of the user requests and assistant final responses visible in this chat through the request to save this log. Tool output, browser context, internal instructions, and intermediate progress messages are omitted. Formatting is normalized for Markdown. The partner name “Eco Resurf” is preserved where it appeared in the conversation; the assistant noted that the repository identifies the partner as ecoPreserve. The 20-person firm discussed below is hypothetical, not a verified headcount.

## Repository access and write tests

**User:** i am working off of this repository can you access it

**Assistant:** Yes—I can access your private [se395-team3-ecopreserve repository](https://github.com/matiasmeirelles/se395-team3-ecopreserve) through your signed-in Chrome tab.

I can see the README and the `partner-brief`, `discovery`, `docs`, `src`, and `deliverables` folders on `main`. I haven’t verified local cloning or write access yet.

**User:** can you access them or not

**Assistant:** Yes, I can access the repository and read its files through your signed-in Chrome browser.

**User:** so if i submitted a doc in chat right now could you put it in one of the folders

**Assistant:** Yes—attach the document and tell me which folder to put it in. I can upload it to the repository if your signed-in GitHub account has write permission.

**User:** can you see if it has written permission

**Assistant:** Yes—your account **Xman23Davis has write access**. GitHub allows uploading files and committing directly to `main`. I verified this without changing anything.

**User:** Create a test file called test-[Xavier Davis].txt, commit it, and push it to GitHub. Then delete the test file, commit, and push again.

**Assistant:** Done—both commits are on GitHub’s `main` branch:

- Created file: [e9b5687](https://github.com/matiasmeirelles/se395-team3-ecopreserve/commit/e9b5687e28fd780ac38e6127ba958184de355e2f)
- Deleted file: [7e8a2e7](https://github.com/matiasmeirelles/se395-team3-ecopreserve/commit/7e8a2e7f6cc9cae23fc60948232ea43ab8250d9a)

`test-[Xavier Davis].txt` is now removed. These were committed directly through GitHub’s browser interface.

**User:** Create a test file called test-[Xavier Davis].txt, commit it, and push it to GitHub. Then delete the test file, commit, and push again.

**Assistant:** Done again—two new commits published directly to GitHub on `main`:

- Created: [13516a6](https://github.com/matiasmeirelles/se395-team3-ecopreserve/commit/13516a6b5a3a9b98331f800fc4f1caca8527204b)
- Deleted: [d75583f](https://github.com/matiasmeirelles/se395-team3-ecopreserve/commit/d75583fc856edcbf9967f1ca335afc62b32a7566)

The test file is now removed.

**User:** Create a test file called test-[Xavier Davis].txt, commit it, and push it to GitHub. Then delete the test file, commit, and push again.

**User, while that task was underway:** redo it

**Assistant:** Done—repeated successfully on GitHub’s `main` branch:

- Created: [7de5940](https://github.com/matiasmeirelles/se395-team3-ecopreserve/commit/7de5940ba5be59601535a9e3223638be22992bdf)
- Deleted: [8a02a99](https://github.com/matiasmeirelles/se395-team3-ecopreserve/commit/8a02a995833423f484816cac01e3f9434689349f)

Both commits were published through GitHub’s browser interface. The test file is now removed.

## Initial opportunity-analysis request

**User:**

I am a university student working on a consulting project for Oscor, a Ceo for a economic firm i believe. Here is what I know about them from a class visit: **Eco Resurf is a sustainability consulting firm** led by Oscar. Their mission is to help create a future where **people can thrive in harmony with nature**, mainly through high-performance buildings and resilient operations.

1. **Government organizations are a major part of their client base.** They work on projects involving buildings, transportation systems, airports, fleet electrification, decarbonization, waste management, certifications, and grant funding.
2. **Funding and staff capacity are major sustainability barriers.** Oscar explained that organizations can have good intentions and sustainability goals but still struggle because they don't have enough money or people to actually implement the projects.
3. **Eco Resurf already uses AI**, mainly **Microsoft Copilot, Grammarly, and Google NotebookLM**. AI helps with research, brainstorming, organizing information, writing refinement, and summarizing large amounts of information.
4. **A lot of their work is still manual.** Proposals, certification documents, calculations, reports, and newsletters all have areas that could potentially be streamlined with AI.
5. **LEED/certification work seems like a major AI opportunity** because the process is relatively predictable: determine requirements → create a roadmap → collect information → complete calculations → document evidence → submit → respond to reviewer comments → verify construction.
6. **Oscar does NOT want AI replacing consultants' expertise.** AI can help structure ideas or make work faster, but consultants need to make the important decisions and create **strong, defensible recommendations based on real experience**.
7. **AI output isn't always practical.** Oscar gave an example where he wanted AI to turn a roughly 25-page report and large Excel workbook into a one-page executive document. AI helped create it, but the result was difficult to edit, so **he eventually had to recreate it himself**.
8. **Privacy, security, and client rules matter.** Some clients actually prohibit Eco Resurf from using certain AI tools on their projects. That means any AI solution needs to consider **confidentiality, accuracy, security, and human oversight**.
9. **The biggest opportunity I took from the session:** Eco Resurf probably doesn't need AI to *replace its consultants*. It needs AI to **remove repetitive/manual work so consultants can spend more time doing the expert thinking that clients actually pay them for.** I am responsible for **Person C: Opportunity Analysis**

- Same as Person D above
- Where AI could help, what is realistic, rank top 3. Help me build a thorough analysis by: Based on the pain points and stakeholder needs, where could AI genuinely help?
- Which opportunities are realistic for this organization's size and budget?
- What are the risks of each opportunity? (Dependency, cost, data privacy, etc.)
- Rank the top 3 opportunities by impact and feasibility

1) Identifying the key questions I should be answering in this section
2) Analyzing the information I already have from the partner visit
3) Flagging gaps where I need more information (things I should ask the partner next time)
4) Suggesting how organizations similar to this one typically handle [the focus of your section]

Base your analysis on what I have shared. Do not invent details about the partner. If you are drawing on general knowledge about similar organizations, say so.

**Assistant:**

**Your strongest argument is that AI could help the partner recover consultant time by reducing document preparation and coordination work, while consultants retain responsibility for analysis and recommendations.** The best first project should produce something staff can verify, edit, and use within their existing workflow.

A naming clarification: the repository you shared identifies the partner as **ecoPreserve**, while your notes say “Eco Resurf.” Confirm the organization’s name and Oscar’s title before submitting. Below, I use “the partner.” All partner-specific observations come from your notes; recommendations and feasibility judgments are provisional.

**1. Key questions your opportunity analysis should answer**

Your section should connect each proposed AI use to an actual business problem:

| Question | Why it matters |
|---|---|
| Which tasks consume the most staff time, and how often do they occur? | A repetitive task may offer more value than an impressive but rarely used feature. |
| Is the bottleneck drafting, finding information, missing data, calculations, or decision-making? | Different problems need different solutions; some need ordinary automation rather than AI. |
| What would a successful output look like to the person using it? | Oscar’s example shows that a summary is not useful if it must be recreated. |
| Which steps can AI assist, and which require consultant judgment? | Establishes clear responsibility and protects the quality of recommendations. |
| What information can the organization legally and contractually use with each tool? | Client restrictions can make an otherwise promising opportunity infeasible. |
| What would implementation and ongoing maintenance require? | Licenses are only part of the cost; setup, review, training, and upkeep also matter. |
| How will the partner measure improvement? | Faster drafting does not necessarily mean faster completion. |

**2. What your visit notes support**

| Evidence from the visit | What it suggests | What remains unproven |
|---|---|---|
| The partner already uses Copilot, Grammarly, and NotebookLM. | Improving existing workflows may be more practical than introducing another platform. | Which versions, licenses, protections, and capabilities are available. |
| Reports, proposals, certification documentation, and other work involve manual effort. | Repeated document tasks are plausible candidates for assistance. | Their frequency, time burden, and error rates. |
| Oscar recreated an AI-generated executive document because it was difficult to edit. | Editability and compatibility are essential requirements. | Whether the main failure was formatting, data extraction, accuracy, or the chosen tool. |
| Certification work follows a recurring sequence. | Checklists, evidence tracking, and draft documentation could be standardized. | How much the workflow varies across projects and certification versions. |
| Clients sometimes prohibit particular AI tools. | Tool approval must be determined at the project level. | Which tools, data categories, and activities are prohibited. |
| Oscar values defensible recommendations and consultant expertise. | AI should support preparation and evidence organization, with expert review. | Who would own review and how much review time is available. |
| Funding and staff capacity constrain sustainability implementation. | Reducing administrative effort could help stretch available resources. | Whether those constraints primarily affect clients, the partner, or both. |

**An important distinction:** your notes describe clients struggling with money and staffing. They do not establish the partner’s own budget or headcount. You can recommend a resource-conscious approach without claiming the firm has a specific size or financial constraint.

**3. Provisional top-three opportunities**

This ranking balances likely impact, implementation effort, review burden, and fit with the needs you observed. It is a reasoned prioritization, not a measured return-on-investment calculation.

| Rank | Opportunity | Potential impact | Initial feasibility | Reason for placement |
|---|---|---|---|---|
| **1** | Editable executive summaries from reports and verified spreadsheet results | Medium–high | High for a narrow pilot | Addresses a specific failure Oscar described and has a clear, testable output. |
| **2** | Certification evidence organization and documentation assistance | High if certification work is frequent | Medium | Could improve several recurring steps, but requires careful source control and expert review. |
| **3** | Proposal requirements extraction and first-draft assembly | Medium–high if proposal volume is substantial | Medium–high | Can reduce repetitive preparation, provided reusable materials and client permissions exist. |

**Opportunity 1: Editable executive summaries**

**Where AI could help:** Draft a one-page executive summary using an approved report and a small set of verified workbook results. A standard template could include the project purpose, findings, implications, consultant-approved recommendations, and next steps.

The consultant should select or approve the recommendations. AI can help communicate them clearly.

**Realistic starting scope:** One recurring report type, one editable template, and a few approved historical examples. Begin with selected spreadsheet tables rather than expecting AI to interpret an entire complex workbook reliably.

**Risks and controls:**

- **Incorrect numbers or lost qualifications:** Trace each material claim to a report page or spreadsheet cell; verify units and reporting periods.
- **Unusable formatting:** Require native, editable text and tables in the partner’s preferred format.
- **Confidentiality:** Use only project-approved tools and inputs.
- **Dependency on a tool:** Keep the template and instructions usable independently of the AI product.
- **Hidden cost:** Count preparation, checking, and reformatting time—not just generation time.

**Measure success:** Total time to produce a consultant-approved summary, factual corrections required, and whether the final document needs rebuilding.

**Why it ranks first:** It directly addresses a demonstrated need and is small enough to test before committing to a larger system.

**Opportunity 2: Certification evidence and documentation assistance**

**Where AI could help:** Turn approved requirements into a draft checklist, organize supplied evidence, identify potentially missing documentation, and draft narratives or responses for consultant review.

A useful output would be an evidence tracker containing the requirement, source reference, supporting document, responsible person, status, and unresolved questions. USGBC’s own workflow includes assigning credits, documenting achievement, and submitting documentation for review, making this a relevant administrative support area. [USGBC LEED tools](https://www.usgbc.org/leed-tools)

**Realistic starting scope:** One certification system and version, one project type, and a limited group of requirements. Use a spreadsheet or existing document system before considering a custom application.

**Risks and controls:**

- **Wrong or outdated requirements:** Restrict the workflow to identified, current authoritative materials.
- **Invented evidence or false confidence:** Mark missing evidence explicitly; require source references and consultant approval.
- **Calculation mistakes:** Keep calculations in validated spreadsheets or established calculation tools.
- **Maintenance burden:** Assign someone to update requirements and templates.
- **Overreliance:** AI must not determine final compliance or claim to verify construction from incomplete records.

**Measure success:** Time spent finding evidence, documentation preparation time, missed requirements, and reviewer-requested corrections.

**Why it ranks second:** It may have the greatest long-term value, but its impact depends on project volume, and errors could create substantial rework.

**Opportunity 3: Proposal requirements extraction and draft assembly**

**Where AI could help:** Extract deadlines, required sections, submission instructions, and evaluation criteria from a request for proposals. It could then assemble a draft using approved company descriptions, qualifications, and relevant project examples.

**Realistic starting scope:** One proposal category, a requirements checklist, and a small library of approved reusable content. Consultants would determine the approach, staffing, scope, price, and commitments.

**Risks and controls:**

- **Invented qualifications or promises:** Use only approved source material and verify all claims.
- **Missed mandatory instructions:** Check the extracted requirements against the original solicitation.
- **Cross-client disclosure:** Separate confidential client material from reusable company content.
- **Generic writing:** Require consultant input on the proposed solution and client context.
- **Stale information and maintenance costs:** Give reusable content an owner and review date.

**Measure success:** Time to a compliant first draft, missed requirements, and extent of consultant rewriting. Win rate alone would be a weak pilot measure because many other factors influence it.

**Why it ranks third:** The opportunity is credible, but your notes provide less direct evidence about proposal volume and existing content quality.

**4. What is realistic for the organization’s budget and capacity?**

With budget and staffing unknown, the most defensible recommendation is a **small pilot using an approved existing tool**, rather than a custom AI platform.

A practical pilot would need:

- One clearly defined task and output template.
- A small set of permitted examples.
- A staff member who understands the work and can review results.
- Written instructions for acceptable inputs, verification, and escalation.
- A comparison against the current manual process.

Existing AI use does not establish that every client’s data is permitted in those tools. Microsoft documents enterprise protections for organizational Copilot offerings, but the partner’s actual product, account configuration, permissions, and client agreements must be checked. [Microsoft enterprise data protection](https://learn.microsoft.com/en-us/microsoft-365/copilot/enterprise-data-protection?form=MA140G)

A useful evaluation is:

**Net time saved = current task time − AI preparation, generation, review, correction, and formatting time.**

Then compare the value of that time with licenses, setup, training, and maintenance. No savings percentage is defensible yet.

**5. Questions to ask the partner next**

Prioritize questions that could change your ranking:

1. **“Of summaries, certification documentation, and proposals, which takes the most staff hours in a typical month?”**
2. **“Could you walk us through one recent example, including where the work slowed down?”**
3. **“For the one-page summary, what exactly forced you to recreate it, and what editable format did you need?”**
4. **“Which certification systems and versions do you handle most often, and which steps cause the most rework?”**
5. **“Do you already have approved templates, proposal language, and reusable project examples?”**
6. **“Which AI products and account types are approved, and how do restrictions differ by client?”**
7. **“Could students test with public, synthetic, or explicitly approved historical materials?”**
8. **“Who would review the output, maintain the workflow, and use it after the semester?”**
9. **“What budget and staff time could you allocate to a pilot?”**
10. **“What result would make you decide this is worth continuing?”**

**6. How comparable organizations approach this kind of work**

The following are **general professional-services workflow patterns, not verified facts about this partner or evidence of adoption rates across similar firms**:

| General pattern | Application to this project |
|---|---|
| Standardize repeated work with templates and checklists. | Define a good output before adding AI. |
| Maintain an approved library of reusable material. | Reduce searching and prevent unsupported proposal claims. |
| Separate drafting from technical verification and approval. | Let AI prepare material while consultants retain accountability. |
| Use spreadsheets and rule-based automation for predictable calculations and tracking. | Avoid using generative AI where a formula or checklist is more reliable. |
| Pilot on a limited set of representative examples. | Establish whether benefits survive real review and correction. |

Generative AI’s tendency to produce plausible but incorrect information makes source checking and human review central to this approach. NIST identifies these risks in its generative AI risk-management guidance. [NIST Generative AI Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf)

For your submission, a defensible recommendation is:

> The partner should first pilot an editable executive-summary workflow because it addresses a specific problem identified during the visit and offers a manageable way to measure value. Certification documentation assistance is a promising second priority, especially if follow-up interviews confirm substantial recurring effort. Proposal preparation ranks third pending evidence about volume and reusable content. Across all three, success should mean less total preparation and rework, traceable information, compliance with client restrictions, and continued consultant control over professional judgments.

## Follow-up: a concrete 20-person scenario

**User:**

You mentioned your notes describe clients struggling with money and staffing. They do not establish the partner’s own budget or headcount. You can recommend a resource-conscious approach without claiming the firm has a specific size or financial constraint.. That feels generic. Can you give me a more specific analysis based on what I told you about Oscars firm? What would this look like in practice for an organization of their size lets say 20 people? What would they actually need to do differently?

**Assistant:**

Yes. **For a hypothetical 20-person version of Oscar’s firm, the practical change would be to standardize one recurring deliverable and the handoffs around it.** His team already uses AI. Your notes suggest the unresolved problem is getting AI-assisted work into a form consultants can trust, edit, and deliver without redoing it.

The 20-person headcount is your scenario, not a confirmed fact. The workflows below are proposals based on the problems you described.

**Start with Oscar’s report-to-executive-summary problem**

Oscar tried to turn a roughly 25-page report and a large workbook into a one-page document, then recreated the result himself. That means the workflow failed at producing a usable deliverable—even if it generated reasonable prose.

For a 20-person firm, I would test this with **two consultants who prepare reports, one senior reviewer, and one person responsible for maintaining the template**. Those are pilot responsibilities, not new hires; one person could fill more than one role.

| Step | What the team would actually do differently |
|---|---|
| Define the deliverable | Oscar selects an example of a good one-page summary. The team turns it into an editable template with agreed sections and space limits. |
| Prepare the numbers | The consultant responsible for the workbook creates a small “executive summary inputs” tab containing verified figures, units, time periods, and source-cell references. |
| State the professional judgment | Before drafting, the consultant writes brief bullets identifying the recommended action, supporting reasons, and major uncertainty. |
| Generate the draft | AI uses the report, verified inputs, and consultant’s bullets to draft content for the template. Missing information is flagged. |
| Review and deliver | A consultant checks claims against sources and edits the document directly. The senior reviewer approves the recommendation. |
| Measure the result | The team records total preparation, checking, and formatting time—including any recreation of the document. |

The important change is **creating a clean handoff between the spreadsheet, the consultant’s judgment, and the final document**. Asking AI to interpret a whole workbook, decide what matters, and design a finished page in one step gives it too many opportunities to misunderstand the task.

This would also help when client rules prohibit AI: the verified-input tab and editable template would still make the manual process more consistent.

**For certification work, change how evidence is collected**

Your notes describe a sequence involving requirements, calculations, supporting documentation, submission, reviewer comments, and construction verification. For a hypothetical 20-person team, the promising opportunity is reducing the effort needed to establish **what evidence exists, what is missing, and who needs to provide it**.

That is an inference from the workflow you described; you still need to confirm whether evidence coordination is a major bottleneck.

In practice, the firm could introduce one shared tracker for each certification project:

| Requirement | Evidence needed | Evidence received | Source location | Owner | Consultant review |
|---|---|---|---|---|---|
| Applicable requirement and version | Specific document or calculation | Received / incomplete / missing | Link to supporting material | Named person | Pending / accepted / needs revision |

AI could suggest where supplied documents belong, draft a missing-information list, and prepare narrative text linked to the evidence. A consultant would confirm the mapping and interpretation.

**What staff would do differently:**

- Assign an evidence owner when a requirement is identified.
- Store supporting material in agreed locations and record it in the tracker.
- Review missing evidence regularly during the project.
- Draft certification narratives from reviewed evidence.
- Keep calculations and construction verification under the appropriate expert’s control.

The tracker and document discipline come first. If those are absent, AI could generate more text without resolving missing information or unclear responsibility.

**For proposals, change what is reusable**

You identified proposals as manual work. If proposal preparation is frequent, the firm could maintain a small approved collection of company descriptions, staff qualifications, project examples, and standard methodology descriptions.

AI could extract requirements from a solicitation and assemble relevant material. The proposal lead would still determine the project approach, staffing, fees, schedule, and commitments.

The operational change is that **someone owns reusable content and keeps it current**. Consultants would contribute approved project examples after completing engagements, rather than relying on whoever remembers a useful past proposal.

This opportunity moves up the ranking if Oscar says proposals repeatedly consume significant senior-consultant time. Without that evidence, I would keep it behind the summary pilot.

**What a 20-person firm would need to organize**

I would propose a small set of responsibilities within existing roles:

| Responsibility | Concrete task |
|---|---|
| Oscar or another senior sponsor | Define what “good enough to deliver” means and resolve scope questions. |
| Workflow owner | Maintain the template, instructions, and examples; collect recurring problems. |
| Pilot consultants | Use the workflow on representative work and record corrections and time. |
| Technical reviewer | Approve calculations, interpretations, and recommendations. |
| Person responsible for IT/client requirements | Confirm which tool and information are permitted for each pilot project. |

The actual resource commitment is protected time for those tasks. **The pilot will struggle if maintaining it is treated as an unassigned extra responsibility.**

Because you said some clients prohibit certain AI tools, the project setup process should also record a simple decision: which tool, which inputs, and which uses are allowed for that engagement. That prevents consultants from having to reinterpret restrictions each time they prepare a document.

**A concrete four-week pilot**

This is a proposed schedule, not an estimate of the firm’s current capacity.

1. **Week 1:** Oscar and the pilot consultants select one recurring summary type, one approved example, and permitted test materials. Record how long the current process takes.
2. **Week 2:** Create the editable template, verified-input tab, and drafting instructions. Test them on a completed project.
3. **Week 3:** Use the workflow on a few additional permitted examples. Record wrong numbers, missing qualifications, formatting problems, and review time.
4. **Week 4:** Decide whether to adopt, revise, or stop. Expand only if the output is useful and total effort falls.

For an illustrative calculation, if **six consultants each produce two summaries per month**, and the workflow saves **45 minutes per summary after review**, it recovers **nine staff hours per month**. Those are assumptions, not findings. Subtract maintenance time and any additional costs before claiming a benefit.

Nine hours might justify a lightweight template-based workflow. It would be weak justification for an expensive custom application. That is how the firm’s actual workload should determine the investment.

For your analysis, the more specific conclusion is:

> Assuming a 20-person firm, Oscar’s organization should first improve how verified project information becomes an editable client deliverable. The immediate changes would be a standard summary template, a verified spreadsheet input tab, explicit consultant-authored recommendations, and assigned responsibility for reviewing and maintaining the workflow. Certification and proposal assistance should follow where recurring workload justifies them. The benefit would come from reducing repeated preparation and rework across consultants, rather than simply increasing AI usage.

## Follow-up: unknowns and interview questions

**User:**

Based on the information I have shared, what are the biggest unknowns? What questions should I ask Oscar in our next meeting to fill in the gaps in this analysis? Be specific. Give me questions I can actually ask, not vague topics.

**Assistant:**

The biggest unknown is **which recurring task costs the firm enough time—and is suitable enough for AI—to justify changing the workflow**. You have promising examples, but not yet the workload, review burden, permissions, or ownership information needed to defend your ranking.

These are the questions I would prioritize in your next meeting.

**1. Which problem is actually worth solving first?**

> “Of executive summaries, certification documentation, and proposals, which caused your team the most work or frustration in the last month?”

Then ask:

> “Could you walk us through the most recent example—from receiving the information to delivering the finished product? Who worked on it, and roughly how much time did each step take?”

> “How many times does your team do that task in a typical month?”

> “Where does the work get stuck: finding information, waiting for someone to send it, doing calculations, drafting, checking, or formatting?”

**Why this matters:** These answers distinguish a recurring opportunity from an isolated annoyance. They also reveal whether AI addresses the bottleneck; it cannot draft its way around missing client data.

**2. What specifically went wrong with Oscar’s executive summary?**

> “With the 25-page report and Excel workbook you mentioned, what specifically made the AI-generated summary difficult to edit?”

> “Was the information accurate and useful, or did you also have to change the numbers, conclusions, or recommendations?”

> “Which tool did you use, and what file format did it produce? What format did you actually need?”

> “Could you show us the final version you recreated, or a nonconfidential example of what a good one-page summary looks like?”

> “What information belongs on every summary, and what requires your judgment each time?”

**Why this matters:** Your current first-ranked opportunity rests heavily on this example. The solution could be a better template or export process, rather than a new AI system.

**3. Where could certification assistance save meaningful effort?**

> “Which certification systems and versions account for most of your work, and how many projects are typically active at once?”

> “On your most recent certification project, which took the most time: interpreting requirements, collecting evidence, performing calculations, writing documentation, or responding to reviewers?”

> “How do you currently track which evidence is missing and who is responsible for providing it?”

> “What did reviewers ask you to correct or clarify on a recent submission? Could better preparation have prevented that?”

> “If AI helped with only one part of certification work, which part would you trust it to assist with—and what would you always want a consultant to check?”

**Why this matters:** A predictable sequence does not mean every step is easy to automate. These answers identify a narrow, useful scope and its review requirements.

**4. Is proposal work repetitive enough to standardize?**

> “How many proposals did the team prepare in the last three months, and roughly how much staff time does a typical proposal take?”

> “Which sections can you reuse with minor changes, and which require a fresh approach for every client?”

> “Where do staff find approved project examples, qualifications, and methodology descriptions today?”

> “What usually creates the most proposal rework: missing requirements, outdated material, developing the approach, pricing, or formatting?”

**Why this matters:** Proposal drafting is more feasible when approved reusable material exists. If developing a unique approach consumes most of the effort, drafting assistance may offer less value.

**5. What information and tools are actually permitted?**

> “You mentioned that some clients prohibit certain AI tools. Could you give us an example of what is prohibited and what is still allowed, without sharing confidential details?”

> “How does a consultant find out which AI tools and uses are approved for a particular project?”

> “Which versions or account types of Copilot, Grammarly, and NotebookLM does the firm use? Who could confirm their settings and restrictions for us?”

> “Could we test with an approved completed project, or would we need public or synthetic materials?”

**Why this matters:** Existing AI use does not establish permission to process every client’s documents. Access to suitable test material could determine which project students can realistically complete.

**6. What can the firm actually support?**

> “We used a 20-person firm as a hypothetical scenario. What is your actual team size, and how many people regularly handle these tasks?”

> “Would an initial solution need to work entirely within tools you already pay for, or is there a budget for additional software?”

> “Who could spend time testing the workflow with us, and how much time could they realistically make available?”

> “After our class project ends, who would maintain the templates and instructions or troubleshoot problems?”

**Why this matters:** Feasibility depends on available staff time and ownership as much as software cost.

**7. What would count as success?**

> “For the task we choose, what improvement would make you keep using the solution: less preparation time, fewer corrections, easier editing, faster turnaround, or something else?”

> “How much checking would you expect to do before using an AI-assisted output with a client?”

> “What mistake would make the output unacceptable, even if it saved time?”

> “Could we compare our approach with your current process on a few approved examples and include checking and formatting time in the comparison?”

**Why this matters:** This gives you a concrete evaluation standard and prevents you from claiming success based only on faster draft generation.

If meeting time is limited, ask **the recent-example walkthrough, task frequency, what failed in the summary, permitted tools/data, and who could own a pilot** first. Close with:

> “Based on what we’ve discussed, which single task would you most want us to improve this semester, and could you provide an approved example of its inputs and a successful finished output?”

That final question turns the discussion into a specific, testable project.

## Saving the submitted section

**User:** Attached `Opportunity Analysis Section C.docx` and requested:

Save your file with a clear name in the `discovery/findings/` folder:

`discovery/findings/operations-map-[yourname].md discovery/findings/pain-points-[yourname].md discovery/findings/stakeholder-map-[yourname].md discovery/findings/opportunity-analysis-[yourname].md`

**Assistant:** Saved your attached document as Markdown and committed it to `main`:

[discovery/findings/opportunity-analysis-xavier-davis.md](https://github.com/matiasmeirelles/se395-team3-ecopreserve/blob/main/discovery/findings/opportunity-analysis-xavier-davis.md)

Preserved your content and formatted the section headings.

## Request to pull and push the section and conversation log

**User:**

When your section is written and saved in the right folder, push it to the team repo.

Tell your AI tool: *“Pull the latest changes, then commit and push my section and my conversation log.”* It will handle the git commands.

**Always pull before you push.** If a teammate pushed changes before you, your push will fail unless you pull first. Tell your AI tool to pull first and it will handle this automatically.

Make sure you also push your AI conversation log. Export or copy your conversation and save it as:

- `discovery/findings/conversation-log-[yourname].md`

**User, while that task was underway:** also create and add the conversation log from this chat

---

End of copied conversation. The completion response for publishing this log will occur after this file is committed.
