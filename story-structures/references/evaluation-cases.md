# Evaluation cases and recorded results

## Method and limits

Evaluated during creation on 16 October 2026 (Asia/Manila). These are single-author, in-chat simulations and editorial reviews of the drafted instructions, with simulated response excerpts retained below. They are not independent model trials, actual Claude executions, empirical reliability estimates or a claim of successful installation. Package validation is a separate mechanical check.

Pass means the retained response satisfies this case's critical expectations. Partial means it demonstrates a useful behavior but lacks enough material or execution evidence to verify the complete requested artifact. No numeric quality score is assigned. Short excerpts intentionally test decision behavior; only case 8 includes a full map-to-prose sample, stored in output-templates.md.

## 1. Sparse premise

**Input:** “A baker receives letters from tomorrow. What structure should I use?”

**Expected:** Work with limited context, offer grounded possibilities, preserve unknowns, then pause for a choice.

**Simulated response:** “The letters are canon; their source, reliability and your ending are unknown. Three Acts would organize the baker's response into discovery, attempts and consequences, and an eventual choice. It leaves room for mystery. A Story Circle would emphasize wanting to use the information, getting something through it and paying a price; that price is not yet established. I would start with Three Acts unless the emotional cost matters more than the puzzle. Which emphasis do you want?”

**Observed:** Two distinct options, no invented source or ending, one question, no full synopsis. **Result: Pass. Repair: None.**

## 2. Adventure with transformation

**Input:** “Novel: Lio, a proud solitary cartographer, crosses a shifting salt desert to return a stolen rain instrument. His mentor teaches tide reading and remains alive. Rival guides become allies. A false map costs them their supplies. Lio admits his error and accepts their route. He returns the instrument and establishes a shared mapping guild. Recommend a structure.”

**Expected:** Recognize transformation and return; compare useful alternatives; preserve mentor survival and ending.

**Simulated response:** “Vogler fits Lio's movement from solitary competence to shared expertise: departure across the desert, testing through the false map, an ordeal requiring help and a return embodied in the guild. Seven Points would concentrate attention on the decisions between error and correction, with less emphasis on reintegration. Three Acts would preserve the broad expedition while leaving the internal stages looser. None requires the mentor to die. Which degree of scaffolding do you prefer?”

**Observed:** Journey recommended for specific story functions, not because the story is an adventure; alternatives distinct; no unauthorized expansion. **Result: Pass. Repair: None.**

## 3. Victory creates tragedy

**Input:** “A magistrate fabricates evidence to secure a conviction. The promotion she wins lets her suppress an appeal. The convicted person's execution triggers the inquiry that exposes her. She loses her office but survives. Compare Freytag and Three Acts.”

**Expected:** Explain different climax positions, preserve survival, identify the victory-to-downfall connection, stop after comparison.

**Simulated response:** “Historical Freytag places her promotion near the central culmination; her new power enables the suppression that brings the inquiry. The falling action is active consequence, not cleanup. Three Acts could place conviction and promotion within the developing conflict, with exposure as the late decisive climax. Freytag gives more weight to the aftermath of success; Three Acts gives more weight to the final exposure. Both can preserve survival, although survival is an adaptation of a strict catastrophe reading. Which emphasis do you want?”

**Observed:** No invented death; central and late climaxes distinguished. **Result: Pass. Repair: None.**

## 4. Comic episode, limited change

**Input:** “Choose and proceed. A roommate wants a silent dinner, tries to fix a restaurant speaker and cuts the kitchen circuit instead. He goes home, orders takeout and permits one quiet song. He stays fussy. Use only these facts. Give a very short map and synopsis.”

**Expected:** Proceed without a selection question; keep change modest; no redemption or invented subplot.

**Simulated response:** “Story Circle, adapted for a small adjustment. You: a fussy roommate (canon); Need: silent dinner; Go/Search: restaurant intervention; Find: silence when he cuts the circuit (interpretation of the supplied action); Take: kitchen loses power; Return: home and takeout; Change: one quiet song is allowed. The roommate wants a silent dinner, so he tries to fix a restaurant speaker. Cutting the circuit stops the kitchen as well. He returns home and orders takeout, permitting one quiet song. He remains fussy, but accepts a little of the noise he set out to eliminate.”

**Observed:** Automatic selection honored, map and causal prose agree, no new ending. **Result: Pass. Repair: None; the requested brevity overrides default episode length.**

## 5. Quiet literary story

**Input:** “An older woman spends a morning sorting buttons. Each recalls a different friendship. Nobody arrives; nothing dramatic happens. At the end she leaves one button unsorted. Recommend a structure without adding a conflict.”

**Expected:** Avoid manufactured stakes, accept a custom arrangement, preserve quiet ending and ambiguity.

**Simulated response:** “A custom arrangement of recollections is the strongest fit: present-day handling of a button, memory, return to the table with a changed association. That pattern can accumulate meaning without external conflict. A loose Three-Act reading could organize her initial sorting, the memories' accumulation and the unsorted button; its risk is making the final gesture seem like a decisive cure. The button's meaning remains open. Would you prefer recurrence or clearer three-phase movement?”

**Observed:** No villain, event escalation or forced lesson. **Result: Pass. Repair: None.**

## 6. Nonlinear mystery with fixed ending

**Input:** “Structure this nonlinear mystery in Three Acts, Preserve. Opening: nurse Mara is arrested for theft. Earlier: pharmacist Sol takes the key and steals a vial. Later: a camera record proves Sol's theft and Mara is cleared. Reveal the key-taking only after Mara's arrest. Do not change the solution.”

**Expected:** Honor chosen structure, separate chronology from disclosure, preserve Sol as thief and Mara's clearance, flag absent investigative links.

**Simulated response:** “Chronology: Sol takes key → steals vial → Mara is arrested → camera record proves theft → Mara is cleared. Disclosure: arrest → key-taking and theft revealed later → camera evidence and clearance. Three Acts: accusation; reconstruction of access and evidence; proof and clearance. The investigative route from arrest to camera record is unresolved. I can map these known events, but the middle needs the steps by which the record is found and authenticated. No new culprit is proposed.”

**Observed:** The two orders and fixed solution are protected; a detailed causal outline remains incomplete because the input lacks the investigation. **Result: Partial for a complete outline; safeguard behavior passes. Repair:** Keep the gap explicit rather than supplying an unauthorized discovery. Further completion needs author input.

## 7. Ensemble

**Input:** “A flood interrupts three siblings' sale of their mother's house. Asha wants the sale, Ben wants to keep it, and Cai wants access to family papers. They agree to sell after retrieving the papers. Asha remains practical, Ben accepts the sale, Cai leaves without forgiving them. Recommend.”

**Expected:** Shared spine, different individual arcs, no imposed collective reconciliation.

**Simulated response:** “Three Acts can hold the shared movement: interrupted sale, retrieval under pressure, agreement to sell. Within it, Asha can remain consistent, Ben changes position, and Cai gets the papers without forgiving anyone. A braided arrangement organized around their separate reasons for entering rooms is a custom alternative; it would emphasize incompatible experiences over one shared turning point. A separate complete journey for each sibling would probably overburden this premise. Which emphasis do you want?”

**Observed:** Distinct arcs retained and alternative labeled custom. **Result: Pass. Repair: None.**

## 8. User chooses a different framework

**Input:** “Use the radio-repair brief in output-templates.md. Even if you would recommend Story Circle, I choose Three Acts. Preserve all facts. Produce a map and approximately 200-word synopsis.”

**Expected:** Proceed, no repeated choice gate; causal prose, established ending and incomplete reconciliation.

**Observed output:** The complete map and synopsis under “Worked map-to-prose example” in output-templates.md are the retained simulation. The map assigns the remote attempt, necessary visit and bounded future contact to three phases. The synopsis connects the component problem to the visit and retains the Sunday call without complete reconciliation.

**Result: Pass. Repair:** During review, retained the emotional reading as Interpretation rather than adding a new cause of the estrangement. No independent Claude run occurred.

## 9. Contradictory notes with fixed ending

**Input:** “Preserve. My non-negotiable ending is that Tomas is alive and leaves the island alone. Earlier notes say he dies permanently in chapter seven and his wife sails away with him at the end. Diagnose and revise what you can.”

**Expected:** Identify both conflicts, protect the fixed ending, ask a focused question, no resurrection or new death.

**Simulated response:** “The fixed ending conflicts with permanent death in chapter seven and with a companion on the final voyage. I can retain the ending as ‘Tomas leaves the island alive and alone’ and mark the other passages unresolved. Should chapter seven become a near-fatal event, and should his wife remain behind? Those are proposals, not repairs I have applied.”

**Observed:** Protected outcome, two explicit proposals, no silent resurrection. Full revision is blocked by missing decisions. **Result: Partial for a completed revision; safeguard behavior passes. Repair:** No creative substitution without approval.

## 10. Development method

**Input:** “I have characters, a final reconciliation and twelve scenes but no order. Use Snowflake to structure my novella.”

**Expected:** Classify Snowflake correctly, offer an architecture separately, begin useful process work without treating ten steps as scenes.

**Simulated response:** “Snowflake can help develop the material from a summary into a scene list. It does not by itself determine the novella's plot architecture. A loose Three-Act frame could organize separation, attempts to repair the relationship and the established reconciliation. Seven Points would be useful if you want to work backward from the final change. I can first summarize your existing material without adding facts; which architecture would you like beneath the Snowflake process?”

**Observed:** Process/architecture distinction and choice checkpoint preserved. **Result: Pass. Repair: None.**

## Cross-case checks and revision record

- Meaningful alternatives: cases 1, 2, 3, 5 and 7.
- Choice checkpoint: cases 1, 2, 3, 5, 7 and 10.
- Automatic selection: case 4.
- Existing selection: cases 6 and 8.
- Canon fidelity: mentor survival in case 2; surviving magistrate in 3; fixed culprit in 6; unreconciled sibling in 7; fixed ending in 9.
- Invention boundaries: unknown endings in 1; proposals explicitly separated in 9.
- Causal synopsis: case 4's short prose and case 8's full demonstration.
- Avoiding a universal pattern: cases 3, 5 and 7.

One development repair pass clarified that choosing an architecture and authorizing invention are separate permissions; it also made mode-specific outputs explicit and required mixed-status map rows to label individual clauses. No further material repair emerged from the retained simulations. Eight cases passed their compact demonstration criteria; two remained partial as complete deliverables because author decisions or causal material were missing. The limitation is preserved rather than disguised as a successful completion.

## Suggested Claude smoke tests after installation

Run cases 1, 4, 8 and 9 in separate fresh chats. Verify that the skill is actually used, references are accessible, case 1 stops for choice, case 4 proceeds, case 8 produces prose and case 9 exposes contradictions. If behavior differs, record the actual output and revise only the relevant rule. Allow up to three development repair passes, then report remaining failures. Do not infer Claude reliability from this document's simulations.
