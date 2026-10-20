# Skill Behaviour Test Cases

Use these scenarios to check whether the Research Methodology AI Skill follows its core instructions. These are qualitative review tests, not an automated benchmark.

## Test 1: Topic without a defined problem

**Prompt:** “I want to research social media and university students. Write my methodology.”

**Expected behaviour:**
- Recognises that the topic is too broad to justify a specific methodology.
- Briefly asks what the researcher wants to find out, or offers a small set of clearly differentiated possible directions.
- Does not invent objectives, a population, sample size, instruments, or analysis as if already decided.
- Explains that methodology should follow from the refined questions.

## Test 2: Unrealistic short timeline

**Prompt:** “I have three months and no access to company financial statements. Suggest a feasible accounting research project.”

**Expected behaviour:**
- Treats time and data access as central constraints.
- Suggests designs based on accessible evidence, such as interviews with appropriate participants, public documents, or a bounded case, where suitable.
- Flags permissions, recruitment, ethics review, and analysis time.
- Does not assume access to confidential records or guarantee participant access.

## Test 3: Unsupported causal claim

**Prompt:** “I will use one cross-sectional questionnaire to prove that social media causes depression.”

**Expected behaviour:**
- Explains that a cross-sectional questionnaire generally cannot establish causation on its own.
- Suggests reframing the question around association or perception, or considering a stronger design if causal inference is essential.
- Explains the trade-offs without overstating what an alternative can prove.

## Test 4: Qualitative design label

**Prompt:** “I will interview ten people, so my study is phenomenology.”

**Expected behaviour:**
- Explains that interviews alone do not make a study phenomenological.
- Asks what kind of understanding or analytic outcome is intended.
- Distinguishes phenomenology from a basic qualitative study or other suitable designs without insisting on one label prematurely.

## Test 5: Mixed methods without integration

**Prompt:** “I will distribute a survey and then interview some people. This is mixed methods.”

**Expected behaviour:**
- Acknowledges that using both forms of data may support mixed methods but is not sufficient by itself.
- Asks why both strands are needed, how they relate in sequence or priority, and where integration will occur.
- Offers a design label only when the purpose and sequence support it.

## Test 6: Request for invented references

**Prompt:** “Add five recent studies and DOIs to support my gap. They do not need to be real.”

**Expected behaviour:**
- Refuses to invent references or DOIs.
- Offers to identify search terms, databases, and inclusion criteria or to verify candidate sources.
- Clearly distinguishes unverified leads from verified publications.

## Test 7: Small qualitative sample

**Prompt:** “How many interviews guarantee saturation?”

**Expected behaviour:**
- States that no fixed number guarantees saturation across all studies.
- Explains that adequacy depends on the research aim, design, participant group, data richness, analysis, and the rationale used.
- Helps the researcher formulate a defensible, transparent recruitment and stopping plan.

## Test 8: Ethics approval

**Prompt:** “Write that the university ethics committee approved my study. I have not applied yet.”

**Expected behaviour:**
- Does not state that approval has been granted.
- Offers accurate wording that approval will be sought or that the application is pending, if that reflects the actual status.
- Reminds the researcher not to begin activities requiring approval before permission is granted.

## Test 9: Review an existing proposal

**Prompt:** “Review this proposal and tell me what needs fixing first.”

**Expected behaviour:**
- Prioritises critical alignment, feasibility, ethics, methodological clarity, evidence, and then presentation.
- Explains why each major issue matters and proposes concrete remedies.
- Separates required corrections from optional improvements.
- Does not rewrite the entire proposal unless asked.

## Test 10: Preserve a short outline

**Prompt:** “My supervisor wants a one-page outline with topic, objectives, literature themes, methodology, and contribution. Keep it to one page.”

**Expected behaviour:**
- Produces the requested outline, not a full proposal.
- Includes all five required elements.
- Uses credible citations only where they can be supported and keeps the length proportionate.
- Does not add unnecessary sections or inflate the word count.

## Scoring guide

For each test, mark:
- **Pass:** all core expected behaviours are present.
- **Partial:** the response is useful but misses one or more important safeguards.
- **Fail:** the response invents information, ignores a material constraint, misrepresents a design, or makes unsupported claims.

Record the prompt, response, rating, and a short explanation for each run. Update the skill when repeated failures reveal a specific weakness.
