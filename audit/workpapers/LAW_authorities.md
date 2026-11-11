# LAW_authorities.md — Authority verification for Fulton dismissal / Athens forfeiture issues
Private attorney work product — prepared 2026-11-11 for John H. Baker, Esq. Reviewer only; I am not acting as an advocate.

## 0. READ FIRST: access limits (this affects every row below)

**No primary-source full text could be opened in this session.** The session's network allowlist is empty (Default environment, "limited" network, `allowed_hosts: []`).
- `curl` to law.justia.com, courtlistener.com, casetext.com, leagle.com, gabar.org, gasupreme.us and gaappeals.us: **CONNECT 403 (proxy policy denial)**.
- `WebFetch` to law.justia.com and www.courtlistener.com: **ENOTFOUND (host not in the allowed network domains)**. Per tool guidance, I stopped trying further hosts.
- **The only working tool was `WebSearch`.** It returns result URLs plus a model-written summary that sometimes quotes snippets from the indexed page. The summaries **are not verbatim opinion text and are sometimes internally inconsistent.** I give examples in §12.

**Verification labels used below**
- **S1**: the search engine indexed the primary-source page (Justia, CourtListener, FindLaw, gasupreme.us) at the URL given. The summary quoted or paraphrased language attributed to that page. **This is not a reading of the opinion.**
- **S2**: the proposition appears only in a citing case, an annotation, or a secondary summary.
- **S0**: not found.
- **Every row is [VERIFY ON WESTLAW]** for verbatim language, pinpoint, and subsequent history unless a row says otherwise. **No row in this file was confirmed against full text.**

**Fix:** allow law.justia.com, www.courtlistener.com, storage.courtlistener.com, caselaw.findlaw.com, www.gasupreme.us, www.gaappeals.us, www.gabar.org and rules.gacourts.gov (or the equivalents) in the environment's network settings. Then re-run this checklist with full-text reads. I did not change the environment, because my assignment was read-only.

## 0A. Bottom line (all items are [VERIFY ON WESTLAW]; see the labels in §0)

**Fulton dismissal**
1. **Pinkard and Mendel are on point against us on facts:** a declared lease forfeiture, subtenant alterations, and a dispossessory. The rule turns on "rights already accrued" and the absence of future undirected action, **not** on filing order. Stevens' own MTD misstates the dates (6/3 vs. 6/23; 3/8 vs. 5/8).
2. **The best answers:**
   - **Gardei v. Taylor (Ga. Oct. 14, 2026)** vacated a declaratory-judgment dismissal and allows a forward-looking declaration on recurring obligations. Cited for "a party need only allege ... future conduct depends on resolution of uncertain legal relations."
   - § 9-4-2(c): relief is available notwithstanding another adequate remedy.
   - The **prior-pending-action line** treats the later dispossessory as the abatable action, not the earlier equity suit: Atlanta Airmotive (1993), Schoen (1980, DeKalb State Court vs. Fulton Superior), Premium Funding (2015).
3. **Same-lease sequel:** Mendel v. Pinkard, 108 Ga. App. 128 (1963). The forfeiture was **not enforced**; forfeiture clauses are strictly construed.
4. **Joinder and amendment:**
   - Zappa (1992): joinder, not dismissal, is the remedy for nonjoinder.
   - Benedek (2015): vacated a dismissal; amendment is as of right before a pretrial order.
   - Doby (2017): adding a party (Bottle Stop) needs a § 9-11-21 order.

**Athens forfeiture**
5. **Strict construction and construction against the lessor:** Peachtree on Peachtree (1983).
6. **Waiver by acceptance of rent:**
   - Tela Invs. v. Razavi (2019): affirmed summary judgment for the tenant on the landlord's dispossessory.
   - Oastler v. Wright (1946): acceptance of rent waives forfeiture, and a demand for arrears is required.
   - Narrowed by Cannon (2002).
7. **Statutory policy:** § 23-1-23 (relief against forfeitures; text conflicting in summaries), § 44-6-41 (damages preferred over forfeiture), and § 13-4-20 (substantial compliance).
8. **Against us:**
   - Nunn v. Taylor (1985): a lessor may terminate for a breach so substantial it defeats the lease's purpose, even without an express clause.
   - Vinings Jubilee (2004): § 44-7-54 requires strict compliance with registry payments.
   - Davita v. Othman (2004): a state court may refuse transfer where only an injunction against the dispossessory is sought; a frivolous-appeal penalty was imposed.
9. **Affirmative equitable relief belongs in superior court:** Thor Gallery v. Monger (2016) **vacated** a state-court lease rescission for lack of equity jurisdiction.
10. **Our complaint's Peachtree paraphrase** ("insubstantial or technical noncompliance") is **not verified and is likely overstated.** **Stevens' "§ 33-24-19(f)…(m)" appears to be miscited** for § 33-24-19.1.

---

## Q1. Authorities cited in Stevens' July 17, 2026 Motion to Dismiss (Fulton 26CV006733)

**Source of Stevens' quotes and pinpoints:** local mirror `corpus/txt/1C-dVz9N41tztviVqNPXNX93FuPNfDkvc__FULTON_26CV006733_FILINGS_AS_FILED_2026-11-02.pdf.rfc.txt`, lines ~2880–3050 (MTD pp. 4–7).

**Factual misstatements in Stevens' own MTD (from the mirror, MTD pp. 4–6):**
- It says "On June 3, 2026, Defendant filed a dispossessory action". The file-stamped date per the brief is 6/23.
- It says "On March 8, 2026, Plaintiffs filed the instant action". The actual date is 5/8/2026.
- It says "Here, Plaintiffs terminated the Prime Lease and filed the dispossessory action". Read literally, this attributes the termination and the filing to the wrong party.

These go to the "already accrued" sequencing argument. As of 5/8 no dispossessory had been filed; Stevens' own dates put the filing either 26 or 46 days later.

### Q1-1. Pinkard v. Mendel, 216 Ga. 487, 117 S.E.2d 336 (1960)
- **Located at:** https://www.courtlistener.com/opinion/1235155/pinkard-v-mendel/ ; Leagle https://leagle.com/decision/1960703216ga4871565 . Decided Nov. 10, 1960; rehearing denied Nov. 22, 1960 (S1).
- **Stevens' quote (MTD p. 6, "Id. at 490"):** "where, as here, the petition shows that the rights of the parties have already accrued and no facts or circumstances are alleged which show that an adjudication of the plaintiffs' rights is necessary in order to relieve the plaintiffs from the risk of taking any future undirected action incident to their rights, which action without direction would jeopardize their interests, the petition fails to state a cause of action for declaratory judgment."
  - **Status: S1, partial.** An exact-phrase search for "risk of taking any future undirected action incident to their rights" returned the Pinkard and Mendel CourtListener pages and later cases quoting the formula: Williams v. Shaffer, Lumbermens Mut. Cas. Co. v. Moody, Poole v. City of Atlanta, Peoples v. Bass, and Walker v. Inman (which quotes Bailey).
  - Secondary citers pinpoint it at "216 Ga. 487, 490(2)", which is consistent with Stevens' "at 490".
  - The full sentence and the "where, as here" lead-in are **[VERIFY ON WESTLAW]**.
- **Stevens' second quote ("Id."):** "denial of the breach of the contract was available as a defense by counter-affidavit to the dispossessory warrant, and the ouster of the plaintiffs and their tenants could be prevented by the filing of such affidavit and the giving of the bond and security required by statute."
  - **Status: S0.** An exact-phrase search returned no hit. **[VERIFY ON WESTLAW]**
- **Facts (S1/S2, conflicting):**
  - Pinkard involved a 99-year lease from 1909. Para. 8 let the lessees make improvements subject to a notice-and-bond requirement. The lessors notified the plaintiffs that the lease was "canceled and at an end" for a claimed violation of para. 8, i.e., alterations by the lessees or their **subtenants**.
  - The plaintiffs sued in Fulton Superior Court for a declaratory judgment and to enjoin a "threatened dispossessory warrant proceeding."
  - **Sequence of filings is conflicting across search summaries:**
    - (i) "They amended their motion for injunction to say that defendants had filed a dispossessory proceeding **after** the declaratory petition was filed."
    - (ii) "The defendants filed a dispossessory warrant in Fulton Superior Court **on the same day** the declaratory petition was filed. The trial court granted an injunction on June 1, 1959."
  - Neither is confirmed from the opinion. **[VERIFY ON WESTLAW] — this is the key factual distinction.** If the Pinkard dispossessory was filed the same day or later, Pinkard is *closer* to our sequence, and Stevens' "already filed" framing does not distinguish it. Under the opinion's logic, the rule turns on whether rights had accrued (termination already declared), **not** on which case was filed first.
- **Posture:** the Supreme Court reversed a judgment for the lessees that had enjoined the dispossessory. This matches Stevens' description (S2). **[VERIFY]**
- **Later treatment:**
  - It is followed, not overruled, in a long line of declaratory-judgment cases (S1/S2).
  - **Same lease, later history (important; see Q1-2A):** in the dispossessory itself, the Court of Appeals declined to enforce the forfeiture: *Mendel v. Pinkard*, 108 Ga. App. 128, 132 S.E.2d 217 (1963).
- **Reviewer note:** Pinkard's own facts are a claimed forfeiture of a very long-term lease, with sublessee involvement, and termination already declared. That makes it hard to distinguish on facts. The better lines of distinction are:
  - (a) the continuing-obligation / "future undirected action" exception: Gardei v. Taylor (Ga. Oct. 14, 2026), Q2;
  - (b) parties and claims not available in the dispossessory (sublessees' independent rights; reformation; affirmative equitable relief), Q3;
  - (c) Pinkard was decided under pre-CPA demurrer practice, with a counter-affidavit and bond regime that the current § 44-7-51 to -54 scheme replaced.

### Q1-2. Mendel v. Pinkard, 217 Ga. 562, 123 S.E.2d 770 (1962)
- **Located at:** https://law.justia.com/cases/georgia/supreme-court/1962/21514-1.html ; https://www.courtlistener.com/opinion/1274947/mendel-v-pinkard/ . Decided Jan. 22, 1962; Candler, J. (S1).
- **Holding per search excerpts (S1):**
  - The first appeal held the petition stated no cause of action for declaratory or injunctive relief. The trial judge therefore should have sustained the general demurrer, and **all later proceedings, including the verdict and final decree for the plaintiffs, were "nugatory."**
  - Dismissing the **amended** petition on an oral motion was proper because it still showed accrued rights. The excerpt characterizes the dispute as essentially whether the plaintiffs "owed a particular payment" (S1 summary; **[VERIFY]**).
  - The court **did not reach** an assignment of error about **consolidation with the dispossessory proceeding** (S1 excerpt). That suggests the declaratory case and the dispossessory were pending together and consolidation was sought. **[VERIFY ON WESTLAW]**
- **Disposition:** "Judgment affirmed" (S1).
- **Stevens' use:** cited generally with Pinkard (MTD p. 5); no pinpoint is quoted.

### Q1-2A. Mendel v. Pinkard, 108 Ga. App. 128, 132 S.E.2d 217 (1963) — same lease, the dispossessory track (helpful to us)
- **Located at:** found only through citing cases (S2): Woodall v. Pharr (1969), https://law.justia.com/cases/georgia/court-of-appeals/1969/44259.html ; Peachtree on Peachtree Investors v. Reed Drug Co., https://www.courtlistener.com/opinion/1295754/ ; Sun Ins. Servs. v. 260 Peachtree St., https://law.justia.com/cases/georgia/court-of-appeals/1989/a89a0360-0.html . Decided June 20, 1963.
- **As described by citing courts (S2):**
  - The lease allowed improvements only after prior notice to the landlord and posting of a bond, and required changes of equal value. Breach was to render the lease "null and void."
  - The lessee made extensive improvements **without notice or bond**. The court nevertheless **declined to enforce the forfeiture**, because the parties' intent was that the landlord's property be of equal or greater value at the end of the term, and the evidence showed that it was.
  - Citing courts use it for the rule that **lease forfeiture provisions are strictly construed**.
- **Significance:** the lessee in Pinkard lost the declaratory and injunction track but **defeated the forfeiture in the dispossessory**. The case supports (a) strict construction and purpose-based reading of forfeiture covenants and (b) the point that forfeiture defenses get a full merits hearing in the dispossessory forum.
- **[VERIFY ON WESTLAW]** the posture (affirmed or reversed), and whether the case arose from the dispossessory or from a consolidated proceeding.

### Q1-3. Bailey v. Dobbs, 227 Ga. 838, 183 S.E.2d 461 (1971)
- **Located at:** Justia's 1971 Supreme Court index lists the case, decided July 15, 1971 (S1). The later Court of Appeals decision is at https://law.justia.com/cases/georgia/court-of-appeals/1972/47231-0.html .
- **Facts (S1/S2):** this is **not a lease case.** City employees were discharged after a city council resolution directed the city manager to fire them. The Supreme Court relied on the city manager's affidavits that the discharge was his own discretionary act.
  - Walker v. Inman quotes Bailey with the same "rights … have already accrued … future undirected action" formula (S2).
  - On remand the plaintiffs added tort claims against the councilmen (1972 Court of Appeals opinion).
- **Stevens' parenthetical (MTD p. 6, "227 Ga. 838, 839"):** "declaratory judgment relief properly denied where the rights of the parties have already accrued."
  - **Status:** the proposition is consistent with the citing-case quote (S2). Page 839 is **[VERIFY]**.
  - **Distinguishing point:** this is a completed employment discharge with no continuing relationship. By contrast, the lease here has continuing obligations (rent, insurance, repairs) if it is not terminated.
- **Negative history:** none found (S0). **[VERIFY ON WESTLAW]**

### Q1-4. Speir v. Davis, 235 Ga. 788, 221 S.E.2d 575 (1976)
- **Located at:** CourtListener's Georgia Reports volume index lists "Speir v. Davis, Jan. 6, 1976, 221 S.E.2d 575, 235 Ga. 788, docket 30324" (S1 listing only). **Text not retrieved.**
- **As quoted by a citing court (S1):** Davita, Inc. v. Othman, 270 Ga. App. 93 (2004), https://law.justia.com/cases/georgia/court-of-appeals/2004/a04a1175.html : "Here, as in Speir v. Davis, 235 Ga. 788, **789**, 221 S.E.2d 575 (1976), the only equitable relief sought by appellant 'was to enjoin the appellees from pursuing their dispossessory action in the [state] court.' The court properly refused to grant such relief."
- **Stevens' quote (MTD p. 7, "at 788"):** "tenant may answer a dispossessory action, the answer may contain any legal or equitable defense or counterclaim."
  - **Status:** S0 for the quote. Davita cites page **789** for the injunction point. **[VERIFY ON WESTLAW]**
- **Distinction to test:** in Speir, and as Davita describes it, the **only** equitable relief sought was to enjoin the dispossessory. The Fulton complaint seeks declaratory relief on the status of the prime lease and the subleases and an injunction. Whether the second amended complaint seeks affirmative equitable relief (e.g., reformation, relief from forfeiture) that a state court cannot grant is the line Davita draws (Q3).

### Q1-5. Imperial Hotel Co. v. Martin, 199 Ga. 801, 35 S.E.2d 502 (1945)
- **Located at:** https://www.courtlistener.com/opinion/3405128/imperial-hotel-company-v-martin/ ; docket 15227, from Fulton Superior Court (S1).
- **Excerpt-level holdings (S1):**
  - A tenant facing a dispossessory warrant could arrest it by counter-affidavit and bond. **"Absent an intervening equity,"** the tenant cannot raise those same defenses in an equitable suit to enjoin the eviction.
  - Also: "A petition for injunction based on apprehension of injury, where no proper facts are alleged to show irreparable damages, should be dismissed on general demurrer."
- **Disposition:** "Judgment reversed." The trial court had granted the tenant an injunction, and the Supreme Court reversed (S1).
- **Stevens' quote (MTD p. 7, "at 803"):** "was to seek the shelter of equity in order to avoid the necessity of defending an eviction warrant and escape filing the statutory bond."
  - **Status: S0.** An exact-phrase search found no hit. **[VERIFY ON WESTLAW]**
- **Useful for us:** the "intervening equity" qualifier. Equity can intervene where the tenant shows an equity that the dispossessory cannot address. Identify it precisely in the full text.

### Q1-6. O.C.G.A. § 44-7-51(b)
- **Located at:** https://law.justia.com/codes/georgia/title-44/chapter-7/article-3/section-44-7-51/ (Justia "2025 Georgia Code"); FindLaw copy at https://codes.findlaw.com/ga/title-44-property/ga-code-sect-44-7-51/ (S1).
- **Text:** the search confirms that subsection (b) contains "**the answer may contain any legal or equitable defense or counterclaim**" (S1, matched on both Justia and FindLaw). Stevens' quote matches.
- **Recent amendment:** the 2025 amendment, effective **July 1, 2025**, changed subsection (a): it substituted "or her deputy," and added ", or an approved process server" (S1, Justia annotation).
- The full current text of (b) is **[VERIFY]**.

### Q1-7. Mabra v. SF, Inc., 316 Ga. App. 62, 728 S.E.2d 737 (2012)
- **Located at:** found only through citing sources (S2). Later courts cite "316 Ga. App. 62, 65" for:
  - the rule that factual allegations are taken as true on a motion to dismiss;
  - "No facts were alleged to support this conclusion" (conclusory allegations).
  - One citing court describes it as a tortious-interference case.
- **Stevens' quote (MTD p. 5, "316 Ga. App. 62, 62"):** "the allegations of the complaint disclose with certainty..." This is the standard dismissal formula. Pinpoint "62" is the first page and is probably a headnote or syllabus page, not the opinion's statement. **[VERIFY ON WESTLAW]**
- **Note:** this standard is **favorable to the non-movant.** The complaint must show "with certainty" that there is no relief under any provable facts.

### Q1-8. Perry v. Emory Healthcare Servs. Mgmt., LLC, 374 Ga. App. 41, 911 S.E.2d 229 (2025)
- **Located at:** https://www.courtlistener.com/opinion/10306610/toni-perry-v-emory-healthcare-services-management-llc/ ; FindLaw https://caselaw.findlaw.com/court/ga-court-of-appeals/116829834.html ; docket **A24A1435**, decided **Jan. 2, 2025** (S1).
- **Facts and posture (S1):** sexual assault and battery, negligent hiring and retention, and related torts. The trial court dismissed on statute-of-limitation grounds. The CourtListener summary lists **"Vacated & Case Remanded."**
- **Stevens' use (MTD p. 4 n.18, "374 Ga. App. 41, 46"):** the trial court erroneously concluded it could not take judicial notice of the defendant's criminal prosecution on a motion to dismiss.
  - The parenthetical is **consistent** with the vacatur (S1).
  - Stevens offers it only to support judicial notice of the Athens filing. Note the irony: the case **reversed (vacated)** a Rule 12(b)(6) dismissal.
- The reporter page 46 is **[VERIFY]**. There is no declaratory-judgment holding.

---

## Q2. Is declaratory relief proper for a lessee facing termination with continuing obligations? (Reversals listed first; then authority that cuts against us)

### Q2-A. Reversals and pro-declaratory-judgment authority
1. **Gardei v. Taylor, No. S25G1209 (Ga. Oct. 14, 2026)** — the strongest and newest.
   - Located at https://www.gasupreme.us/wp-content/uploads/2026/10/s25g1209.pdf and https://www.courtlistener.com/opinion/11049797/gardei-v-taylor/ (S1).
   - **Posture:** the Supreme Court **vacated** a Court of Appeals decision that had affirmed dismissal of a declaratory claim, and remanded "for further proceedings not inconsistent with this opinion" (S1).
   - **Issue, per the oral-argument description:** whether a person "wrongly compelled to comply with an annually-recurring statutory obligation" may use a declaratory action "to obtain a forward-looking ruling on whether they have to keep complying" (S2).
   - **Standard as quoted by a later decision:** *Eager Holdings, LLC v. Patel*, S26C1061 (Ga. Nov. 3, 2026), denial of certiorari, cites Gardei (slip op. 4) for: "a party need only allege the existence of a justiciable controversy in which future conduct depends on resolution of uncertain legal relations" (S1/S2; https://www.courtlistener.com/opinion/11052290/eager-holdings-llc-v-patel/).
   - **Why it matters:** the occupants face recurring obligations (rent, insurance, maintenance) and decisions (pay or tender rent, renew insurance, invest in improvements, re-let). Gardei is the best current answer to "rights already accrued."
   - **Cautions:** the opinion is subject to reconsideration, and there is no reporter cite yet. **[VERIFY FULL TEXT]**
2. **GeorgiaCarry.Org, Inc. v. Atlanta Botanical Garden, Inc. (Ga. 2016).**
   - Located at https://law.justia.com/cases/georgia/supreme-court/2016/s16a0294.html (S1).
   - **Reversed** dismissal of a declaratory action. It repeats the standard formula: the scope of a declaratory judgment is "to adjudge those rights among parties upon which their future conduct depends" (S1). This is not a lease case. **[VERIFY]**
3. **SJN Properties, LLC v. Fulton County Bd. of Assessors (Ga. 2015).**
   - Located at https://law.justia.com/cases/georgia/supreme-court/2015/s14a1493.html (S1).
   - **Reversed** a dismissal on the pleadings in a leasehold-valuation context. The court also noted that SJN itself faced no uncertainty about its own future conduct, which is a mixed signal. **[VERIFY]**
4. **Shippen v. Georgia Better Foods, Inc., 79 Ga. App. 813, 54 S.E.2d 704 (1949)** — lessee declaratory action on lease duties.
   - Located through https://hallapproved.com/ga/cases/appeals/1949/3409920/ (S2).
   - The Court of Appeals held "this is a proper case for a declaratory judgment" and **affirmed** the overruling of the demurrer and the judgment for the lessee and assignee (S2).
   - It is a lease-construction declaration with a continuing relationship. **[VERIFY]**
5. **Quality Foods, Inc. v. Smithberg, 288 Ga. App. 47, 653 S.E.2d 486 (2007).**
   - Located at https://www.courtlistener.com/opinion/1424245/quality-foods-inc-v-smithberg/ (S1).
   - Affirmed in part and reversed in part. On the declaratory point it affirmed the denial of summary judgment against the tenant's declaratory counterclaim: "Disputes concerning ownership of or right of access to land are classic candidates for resolution via declaratory judgment" (S1).
   - The tenant held a lease with a purchase option. **[VERIFY]**

**No Georgia appellate decision was found that expressly distinguishes Pinkard on lease-forfeiture facts and reverses.** Searches with variants of "Pinkard" plus "distinguished" plus lease and rent returned nothing. That is a **gap**: run a Westlaw KeyCite on 216 Ga. 487 headnote 2.

### Q2-B. Authority that cuts against us (balance)
- **Pinkard (1960) and Mendel (1962):** see Q1. A declared lease forfeiture, sublessee alterations, and a threatened or filed dispossessory led to dismissal of the declaratory petition, and later proceedings were held "nugatory."
- **Shippen v. Folsom, 200 Ga. 58, 35 S.E.2d 915 (1945).**
  - Located at https://case-law.vlex.com/vid/shippen-v-folsom-15235-907817489 (S2).
  - The lessee sought a lease construction and an injunction after the lessor claimed unpaid rent and threatened eviction.
  - Per summaries, the court said the Declaratory Judgment Act does not "reach back and nullify the rights, remedies, and penalties in favor of landlords which have already accrued in dispossessory matters" (S2; also quoted in the § 9-4-2 annotations).
  - George v. Dept. of Natural Resources (1983) says Shippen "has been followed since the 1959 amendment." **[VERIFY]**
- **Cobb County v. Floam, 319 Ga. 89, 901 S.E.2d 512 (2024).**
  - Located at https://www.gasupreme.us/wp-content/uploads/2024/05/s24a0599.pdf (S1).
  - **Reversed** a declaratory judgment for the plaintiffs because they "did not demonstrate the necessary uncertainty regarding their future conduct."
  - Lesson: the complaint must plead **specific** future acts the plaintiffs must decide on. Gardei may soften this; compare the two.
- **Patel v. Eager Holdings, LLC, No. A25A1820 (Ga. App. Mar. 3, 2026).**
  - Located at https://www.courtlistener.com/opinion/10803102/monica-patel-v-eager-holdings-llc/ (S1).
  - The court held the declaratory action presented no justiciable issue: "a declaratory judgment claim is improper when the declaration ... concerns rights that have already accrued" (S1 summary).
  - Certiorari was **denied** Nov. 3, 2026 (S26C1061). A Georgia Commons AI summary says one Justice wrote that the lower court "likely erred." **[VERIFY the statement's text]**
  - This appears to be **a different Patel, an LLC-membership dispute**. Confirm there is no connection to our client.
- **Bailey v. Dobbs (1971):** see Q1-3.

**Pleading takeaway (reviewer, not authority):** the second amended complaint should plead concrete future undirected acts, for example:
- whether to keep paying rent to Stevens or tender it into a registry;
- whether to procure or renew insurance in a particular form;
- whether to invest in improvements or renew subleases;
- whether sublessees must attorn.

It should also plead the parties and claims the Athens dispossessory cannot adjudicate (Q3).

---

## Q3. Jurisdiction texts, and equitable defenses vs. affirmative equitable relief in a state court dispossessory

### Q3-1. O.C.G.A. § 15-7-4 (state courts)
- Located at https://law.justia.com/codes/georgia/title-15/chapter-7/article-1/section-15-7-4/ ("2025" Justia page, fragmentary in the search); full 2010 text at https://law.justia.com/codes/georgia/2010/title-15/chapter-7/article-1/15-7-4 (S1).
- **(a) as quoted in Davita v. Othman:** state courts have jurisdiction, "concurrent with the superior courts," over "civil actions without regard to the amount in controversy, except those actions in which exclusive jurisdiction is vested in the superior courts" (§ 15-7-4(a)(2)) (S1).
- Justia annotations: superior courts retain exclusive jurisdiction over **declaratory judgment** actions (S2).
- **Current full text: [VERIFY].**

### Q3-2. Ga. Const. Art. VI, Sec. IV, Para. I (superior courts)
- **The current text differs from older copies.** The pre-2018 version (Justia's constitution page, https://law.justia.com/constitution/georgia/conart6.html) lists "equity cases" in the superior courts' **exclusive** jurisdiction, with felonies, title to land and divorce.
- After the 2018 amendment creating the State-wide Business Court (Ballotpedia, FindLaw copies), the summaries describe equity jurisdiction as exclusive in the superior courts **"concurrent with" the State-wide Business Court** and, in one summary, the Georgia Tax Court (S2).
- **Reviewer inference: on either wording, state courts are not given equity jurisdiction.** Verify the current wording on the official constitution PDF (sos.ga.gov January 2023 PDF located). **[VERIFY]**
- **Related, Art. VI, Sec. I, Para. VIII (transfer):** "Any court shall transfer to the appropriate court in the state any civil case in which it determines that jurisdiction or venue lies elsewhere" (S1, Justia constitution page). Implemented by the Uniform Transfer Rules; a motion to dismiss for lack of jurisdiction is treated as a motion to transfer (S2).

### Q3-3. O.C.G.A. §§ 44-7-50, -51, -53, -54: **version warnings**
- **§ 44-7-50:**
  - Justia's 2025 page is captioned "**[Effective January 1, 2027]** Demand for possession; procedure upon a tenant's refusal; notice to vacate or pay; records unavailable to public": https://law.justia.com/codes/georgia/title-44/chapter-7/article-3/section-44-7-50-d-1/ (S1).
  - So **there are two versions**: the version in force for the 2026 demands and filing, and a later amended version (apparently 2026 legislation, possibly HB 61 "Georgia Anti-Squatting Act of 2026", dealing with public access to dispossessory records; **not confirmed**).
  - (a) covers holdover, nonpayment, and tenancy at will or at sufferance. The owner "may demand the possession" and, on refusal, make an affidavit (S2, FindLaw and elaws copies). **[VERIFY text in force 4/23–6/23/2026]**
- **§ 44-7-51:**
  - Justia 2025: https://law.justia.com/codes/georgia/title-44/chapter-7/article-3/section-44-7-51/ .
  - (b) "the answer may contain any legal or equitable defense or counterclaim" (S1).
  - 2025 amendment, effective 7/1/2025, to (a) (process servers).
- **§ 44-7-53:**
  - Justia 2025: https://law.justia.com/codes/georgia/title-44/chapter-7/article-3/section-44-7-53/ (S1 listing).
  - (b): if the tenant answers, a trial of the issues is held under the Civil Practice Act, and the tenant may remain in possession pending trial if rent is paid into the registry under § 44-7-54 (S2 paraphrase). **[VERIFY]**
- **§ 44-7-54:**
  - FindLaw copy: https://codes.findlaw.com/ga/title-44-property/ga-code-sect-44-7-54/ (S2).
  - Covers payment of rent admittedly due into the registry at answer, and future rent as it falls due. The written rental contract sets the amount. **[VERIFY]**
  - Vinings Jubilee Partners v. Vinings Dining (Ga. App. 2004), https://caselaw.findlaw.com/court/ga-court-of-appeals/1016999.html : "OCGA § 44-7-54 mandates strict compliance" (S1). **Important for our clients' registry compliance in Athens.**

### Q3-4. Cases: equitable defense vs. affirmative equitable relief; transfer
1. **Thor Gallery at S. DeKalb, LLC v. Monger, 338 Ga. App. 235, 789 S.E.2d 806 (2016) — VACATED a state court judgment.**
   - Located at https://www.leagle.com/decision/ingaco20160715270 ; https://case-law.vlex.com/vid/thor-gallery-at-s-891229576 (S1).
   - The State Court of Gwinnett County granted **equitable rescission** of a commercial lease and ordered return of the deposit. The Court of Appeals agreed the state court "lacked jurisdiction to provide Monger with the remedy of equitable rescission," **vacated**, and remanded (summaries say with direction to transfer to superior court).
   - It also recognizes that "State courts ... can exercise jurisdiction over certain cases involving rescission where no affirmative equitable relief is asserted" (S1).
   - **This is the closest reversal for the line: the State Court may hear equitable *defenses* but cannot grant *affirmative* equitable relief.** Relief from forfeiture, reformation, and an injunction would fall on the superior-court side. **[VERIFY disposition wording]**
2. **Davita, Inc. v. Othman, 270 Ga. App. 93, 606 S.E.2d 112 (2004) — affirmed (against the tenant), with a frivolous-appeal penalty.**
   - Located at https://law.justia.com/cases/georgia/court-of-appeals/2004/a04a1175.html (S1).
   - The State Court of Bibb County denied a motion to transfer the dispossessory to superior court because the tenants "had not sought any of the forms of relief reserved by the Georgia Constitution for superior courts."
   - The only equitable relief sought was to enjoin the dispossessory, which was properly refused (citing Speir, 235 Ga. at 789).
   - **Read with Thor Gallery:** the transfer question turns on whether affirmative equitable relief is actually pleaded.
   - $1,000 Court of Appeals Rule 15(b) penalty (S1). **Caution:** an appeal pressing a transfer on an injunction-only theory risks sanctions.
3. **Equity's limit on enjoining a dispossessory:** Imperial Hotel (Q1-5, "absent an intervening equity") and Speir (Q1-4).
4. **Abushmais v. Erby (Ga. 2007)**, https://caselaw.findlaw.com/court/ga-supreme-court/1137155.html (S1): objection to a magistrate-to-superior transfer is waived if not raised in superior court. Peripheral.

---

## Q4. Forfeiture and waiver

### (a) Acceptance of rent with knowledge of breach
1. **Oastler v. Wright (Ga. 1946)**, https://www.courtlistener.com/opinion/3407216/oastler-v-wright/ (S1 headnote excerpt).
   - "A cause for the forfeiture of a lease, or a right on the part of the lessor to reenter the leased premises for a breach of a condition, may be waived." Acceptance of rent with knowledge of the default works a waiver absent contrary circumstances.
   - Also: the lessor "would be estopped to declare a forfeiture, by reason of such prior defaults in rent payments, without first making a demand for the rent in arrears."
   - The court declined to enforce a forfeiture sought through a dispossessory. Reporter cite and dates are inconsistent in sources. **[VERIFY]**
   - **Narrowed by Cannon v. Wesley Plantation Apartments, 256 Ga. App. 244, 568 S.E.2d 137 (2002)**, https://case-law.vlex.com/vid/cannon-v-wesley-plantation-893988253 (S2). It reads Oastler's pro-tenant language as limited to "cases of doubt" and to mutual departure from lease terms.
2. **Tela Investments, LLC v. Razavi, 351 Ga. App. 518, 831 S.E.2d 175 (2019)**, https://www.courtlistener.com/opinion/4639625/tela-investments-llc-v-ehsan-razavi/ (S1). **Affirmed** summary judgment for the **tenant** against the landlord's dispossessory.
   - The landlord "accepted and retained [the tenant's] checks for the claimed arrearage after purportedly terminating the lease."
   - "[T]he trial court correctly ruled that Tela could not terminate the lease while accepting payments under the lease terms." **[VERIFY quotes]**
   - **Directly relevant if Stevens accepted rent after the 2/9/2026 default notice or the 3/19/2026 termination.** Coordinate with the facts workstream.
3. **Cheeves v. Horne (Ga. App. 1983)**, https://law.justia.com/cases/georgia/court-of-appeals/1983/66138-0.html (S1). **Contra or limiting:** acceptance of rent accruing *after* the dispossessory began does not necessarily create a new tenancy or estop the landlord's holdover claim. **[VERIFY]**

### (b) Statutes reflecting equity's aversion to forfeiture
- **O.C.G.A. § 23-1-23**, "Construction of conditions; relief against forfeitures."
  - Located at https://law.justia.com/codes/georgia/2020/title-23/chapter-1/section-23-1-23/ (S1 heading).
  - Search paraphrase: where construction rules permit, equity favors reading conditions subsequent as covenants and favors relief from forfeitures.
  - **Conflict:** a different search summary described § 23-1-23 as saying courts will **not** relieve against a forfeiture the contract clearly provides. Treat the text as **unknown until read**.
  - Cited in First Rebecca Baptist Church v. Atlantic Cotton Mills (Ga. 1993) and Crawford v. Etheridge (Ga. App. 2001) (S2). **[VERIFY]**
- **O.C.G.A. § 44-6-41**, "Conditions precedent and subsequent distinguished; preferred construction and remedy."
  - Located at https://law.justia.com/codes/georgia/2020/title-44/chapter-6/article-3/section-44-6-41/ (S1).
  - Summary: the law inclines to construe a condition as subsequent, and to remedy a breach by damages rather than forfeiture.
  - Annotation: "Law inclines to construe conditions subsequent so as to render their breach remediable in damages rather than by forfeiture, but when the plain words of the grant declare that a breach of the condition shall defeat the estate granted, there is no room for construction" (S1 annotation). **[VERIFY]**
- **O.C.G.A. § 13-4-20** (see Q11-c): performance must "substantially" comply.
- Note § 23-1-8 (equity considers done what ought to be done). Its annotation references preventing forfeitures (S2).

### (c) Covenant vs. condition; express clause; strict construction
- **Peachtree on Peachtree Investors, Ltd. v. Reed Drug Co., 251 Ga. 692, 695(1), 308 S.E.2d 825 (1983):** "Provisions in leases which result in a forfeiture of a tenant's possessory rights will be strictly construed." Also: "As a general rule the provisions of a lease will be construed against the lessor." This is quoted by Main Street Burger, Inc. v. Estate of Collier (Ga. App. 2024, A24A0531) and Smith v. Geiger (S1). See Q11-a.
- **Mendel v. Pinkard, 108 Ga. App. 128 (1963):** forfeiture not enforced despite breach of the notice-and-bond covenant (Q1-2A). An outline cites p. 134 for "All key phrases of forfeiture provision must be given effect" (S2).
- **Woodall v. Pharr (Ga. App. 1969)**, https://law.justia.com/cases/georgia/court-of-appeals/1969/44259.html (S1 excerpts).
  - Leases are construed against the lessor, and forfeiture provisions are strictly read.
  - "When a forfeiture depends on giving a written notice of default, it must appear that the notice was given in strict compliance with the contract both as to time and contents and that the default occurred" (S2, secondary quote).
  - A demand for possession does not terminate where the lease requires a chance to cure. **[VERIFY]**
- **AGAINST US:**
  - **Nunn v. Taylor, 177 Ga. App. 44, 338 S.E.2d 453 (1985)** (farm lease; Justia annotation to § 44-7-1, S2). Where a jury found the breach "so substantial that it defeated the purpose of the lease," the lessor "retains the inherent right to rescind or terminate the lease even in the absence of an express provision."
    - **Read with care:** this is a **materiality** rule (a breach defeating the lease's purpose), not a technical-breach rule. It answers the "no express re-entry clause" argument, but supports our materiality theme.
  - Search excerpt (source unidentified): "Forfeiture of a lease ... because of a breach of a covenant or condition [is] not favored, but where there is an express provision in the contract, termination or forfeiture of the lease will be permitted."
  - **Vinings Jubilee Partners v. Vinings Dining (2004):** strict compliance, and the tenant's good-faith attempt did not prevent termination where the lease had no such clause (S1).
  - **No Georgia appellate holding was found that a lessor may *never* terminate for breach of covenant absent an express forfeiture clause.** Nunn says otherwise for substantial breaches.

### (d) Notice and opportunity to cure absent lease language
- **Oastler (1946):** a demand for arrears is required before forfeiting for prior rent defaults that were tolerated (S1).
- **Swim Dixie Pool Corp. v. Kramer (Ga. App. 1981)** (S2, via a bankruptcy opinion): a warning letter is not itself a termination; the lease "envisions a separate written notice of termination after the expiration of the five day warning." **[VERIFY]**
- The Woodall two-notice reasoning (lease-specific).
- **No Georgia authority found imposing a cure period where the lease is silent.** The cure argument must come from the lease text, waiver or course of dealing (Oastler, Cannon), or § 23-1-23 equity.

### (e) Substantial compliance and materiality
- **O.C.G.A. § 13-4-20** (2024 Justia, https://law.justia.com/codes/georgia/title-13/chapter-4/article-2/section-13-4-20/ , S1): performance must substantially comply with the contract's terms and be completed within a reasonable time (search paraphrase; exact words not retrieved; see Q11-c). Annotation: "substantial compliance with terms of agreement is all that is required of either party."
- **Caution:** a Bankr. M.D. Ga. opinion notes that strict compliance has been required for **termination-notice** clauses in cases concerning forfeiture of real property rights (S2). This cuts both ways: it is strict on Stevens' notices and strict on the tenants' payments (Vinings Jubilee).
- **Nunn:** materiality ("defeated the purpose").
- **Mendel (1963):** purpose-based non-enforcement.

---

## Q5. Prior pending action, abatement, and stays

### Q5-1. Statute texts
- **O.C.G.A. § 9-2-5(a)**, Justia 2024: https://law.justia.com/codes/georgia/title-9/chapter-2/article-1/section-9-2-5/ (S1, matching on multiple versions): "No plaintiff may prosecute two actions in the courts at the same time for the same cause of action and against the same party." For simultaneous filings, "the defendant may require the plaintiff to elect which he will prosecute" (lead-in words not retrieved). "If two such actions are commenced at different times, the pendency of the former shall be a good defense to the latter" (as quoted in Premium Funding).
  - (b) concerns attachments.
  - Annotation: the parties must occupy "the same status in both suits" (S1 annotation). **Note:** in the Fulton case Patel et al. are plaintiffs; in Athens, Stevens is plaintiff. § 9-2-5 speaks to "plaintiff," so § 9-2-44 is the better vehicle.
- **O.C.G.A. § 9-2-44(a)**, Justia 2020: https://law.justia.com/codes/georgia/2020/title-9/chapter-2/article-3/section-9-2-44/ (S1).
  - "... the pendency of a former action for the same cause of action between the same parties in the same or any other court having jurisdiction shall be a good cause of abatement."
  - "[I]f the first action is so defective that no recovery can possibly be had, the pendency of a former action shall not abate the latter."
  - (b) parol evidence on matters not passed upon.
  - Annotation: priority runs from filing once service is perfected, because service relates back.
  - Brock v. C & M Motors (Ga. App. 2016): "pendency" means a still-pending claim.
  - **[VERIFY current text]**

### Q5-2. Cases (a reversal first)
1. **Atlanta Airmotive, Inc. v. Newnan-Coweta Airport Authority, 208 Ga. App. 906, 432 S.E.2d 571 (1993)** — tenant's prior lease action; landlord's later dispossessory; **interlocutory appeal from the DENIAL of the tenant's plea in abatement.**
   - Located at https://www.courtlistener.com/opinion/5791307/atlanta-airmotive-inc-v-newnan-coweta-airport-authority/ (S1 excerpts).
   - The tenant sued 8/28/1992; the authority filed the dispossessory 10/27/1992. Both arose from "compliance with the terms of a lease."
   - The court treated the dispossessory as a "later inconsistent action" while the tenant's prior action was pending, and rejected the argument that denial of the tenant's injunction motion licensed the dispossessory filing.
   - Premium Funding (below) cites it for: the trial court **erred in denying** a tenant's plea in abatement where a favorable decision in the tenant's prior pending lease action would bar the later dispossessory.
   - **This is the single most useful case for an Athens plea in abatement, and it answers Stevens' sequencing argument in Fulton:** Fulton (5/8) was first and Athens (6/23) later. **[VERIFY disposition: likely reversed]**
2. **Schoen v. Home Federal Sav. & Loan Ass'n, 154 Ga. App. 68, 267 S.E.2d 466 (1980)** — **cross-court and cross-county, the same configuration as ours.**
   - Located at https://www.casemine.com/judgement/us/591492cfadd7b0493459eb44 (S1/S2).
   - A dispossessory in **DeKalb State Court**; the tenants' plea in abatement was based on a pending **Fulton Superior Court** action to quiet title and retain possession. The sole question was whether the State Court erred in overruling the plea.
   - Described as holding that the dispossessory should have been abated pending the prior superior-court suit. A plea can be good even where the causes of action differ, if they arise from the same transaction and the second suit would be "unnecessary and oppressive." **[VERIFY]**
3. **Premium Funding Solutions, LLC v. Metro Atlanta Task Force for the Homeless, Inc., 333 Ga. App. 718, 776 S.E.2d 504 (2015)** (physical precedent only).
   - Located at https://caselaw.findlaw.com/court/ga-court-of-appeals/1710418.html (S1).
   - **Affirmed** the grant of the tenant's plea in abatement and a **stay** of the dispossessory pending the related actions: "a plea in abatement has been held to lie where dispossessory proceedings are commenced while other litigation is pending between the same parties in which substantially the same questions to title, and possession of, the same land are presented" (S1).
   - The Supreme Court then treated the related challenge as moot: Metro Atlanta Task Force v. Ichthus Cmty. Trust, 298 Ga. 221 (2015) (S1).
- **Identity-of-parties caution (annotation to § 9-2-5):** dismissal was error where the defendant was not a party to the earlier action (S1 annotation).
  - Athens names Bottle Stop, Mind the Gap, and Graymad, which are not Fulton plaintiffs.
  - Fulton plaintiffs Sonia and Nu Age are not Athens defendants, per the MTD's list.
  - Adding Bottle Stop in Fulton (Q6) helps the party identity.

---

## Q6. Joinder and amendment

### Q6-1. Texts
- **§ 9-11-19**, Justia 2025: https://law.justia.com/codes/georgia/title-9/chapter-11/article-4/section-9-11-19/ (S1).
  - (a) persons to be joined if feasible; "If he has not been so joined, the court shall order that he be made a party" (S1 via the 2020 Justia text).
  - (b) "equity and good conscience" factors where joinder is not feasible.
  - (c) a pleading must name nonjoined required persons. **[VERIFY]**
- **§ 9-11-21** (2010 and 2020 Justia, S1):
  - "Misjoinder of parties is not ground for dismissal of an action" (phrase-match).
  - As quoted in Zappa: "Parties may be dropped or added by order of the court on motion or on its own initiative at any stage of the action." Summaries add "on such terms as are just."
  - Severance is available.
- **§ 9-11-15(a)** (2022 Justia, https://law.justia.com/codes/georgia/2022/title-9/chapter-11/article-3/section-9-11-15/ , S1): "A party may amend his pleading as a matter of course and without leave of court at any time before the entry of a pretrial order. Thereafter the party may amend his pleading only by leave of court or by written consent of the adverse party." Also: "leave shall be freely given when justice so requires" (separately confirmed fragment). An older version has a 15-day response sentence. **[VERIFY current]**
- **§ 9-11-41(b)** (2022 Justia, S1/S2): a dismissal for failure to prosecute does not operate as an adjudication on the merits. "Any other dismissal under this Code section, other than a dismissal for lack of jurisdiction or for improper venue or for lack of an indispensable party, does operate as an adjudication upon the merits unless the court in its order for dismissal specifies otherwise."
  - **Relevance:** a proposed order should say "without prejudice." Stevens' MTD asks for dismissal "without prejudice to the refiling of Plaintiffs' claims in the pending dispossessory action" (MTD p. 7).

### Q6-2. Cases
- **Zappa v. Automotive Precision Machinery, Inc. (Ga. App. 1992)**, https://law.justia.com/cases/georgia/court-of-appeals/1992/a92a1065.html (S1): "the proper remedy for failure to join an indispensable party is not dismissal ... but joinder." It relies on § 9-11-21. **[VERIFY posture]**
- **Glover v. Allstate Ins. Co. (Ga. App. 1997)** (S1): § 9-11-19(a) "does not require dismissal if an individual ... cannot be joined"; the court proceeds to the (b) analysis.
- Justia annotations to § 9-11-19 (S2): where the party can be joined, the court should permit joinder, not dismiss. A reasonable time for joinder must be allowed before dismissal.
- **Doby v. Bivins (Ga. App. 2017)**, https://caselaw.findlaw.com/court/ga-court-of-appeals/1864439.html (S1): **adding a party requires a court order under § 9-11-21**. Applying the § 9-11-14 indispensable-party standard was the wrong framework.
  - **So the Bottle Stop addition needs leave, but the second amended complaint against Stevens is as of right (if no pretrial order).**
- **Benedek v. Bd. of Regents (Ga. App. 2015)**, https://caselaw.findlaw.com/court/ga-court-of-appeals/1705679.html (S1) — **REVERSED / VACATED a dismissal.**
  - The plaintiff could amend as a matter of right before a pretrial order. "[A] motion for leave to amend a complaint to add additional claims against existing defendants is superfluous if it is made before entry of a pretrial order."
  - The court vacated the dismissal and remanded for the trial court to evaluate the amended complaint. **[VERIFY quotes]**
- Artson LLC v. Hudson (Ga. App. 2013): failure to join an indispensable party must be asserted before judgment or it is waived (S1).

---

## Q7. Service, discovery, and uniform-rule texts
- **§ 9-11-5(f)** (FindLaw; rulesofcivilprocedure.com, S2). Consent to e-service is given by:
  - "(A) Filing a notice of consent to electronic service and including the person to be served's e-mail address ..."; or
  - "(B) Including the person to be served's e-mail address ... in or below the signature block of the complaint or answer."
  - Service is by e-mailing a PDF with "STATUTORY ELECTRONIC SERVICE" in the subject line.
  - The served person bears responsibility for e-mail address changes.
  - A sworn certification of non-receipt creates a presumption. Sources differ on the subsection numbering. **[VERIFY]**
- **§ 9-11-6(e)** (2024 Justia, S1, confirmed fragment): "(e) Additional time after service by mail or e-mail. Whenever a party has the right or is required to do some act or take some proceedings within a prescribed period after the service of a notice or other paper ..." The search summary says three days are added where the paper is served by mail or e-mail; the remainder of the text was not retrieved.
  - **Speckhals v. Golf & Tennis Pro Shop, Inc., 320 Ga. 523 (2024)** (S24C0848): certiorari denied. Warren, J., concurring, reads the 3-day rule as applying to e-filing-system e-mails.
  - The Court of Appeals' contrary summary affirmance is unpublished. **The question is open.**
- **§ 9-11-26(e)** (2020 Justia, S1/S2):
  - No general duty to supplement a response complete when made, except (1) persons with knowledge and experts.
  - (2) Duty to "seasonably amend" if the party learns the response "was incorrect when made," or is no longer true and failure to amend "would amount to a knowing concealment."
  - (3) Further duty by order, agreement, or new requests.
- **§ 9-11-33(a)** (2025 Justia, S1): answers and objections are due within 30 days after service (a defendant gets 45 days after service of the summons and complaint). Limit of 50 interrogatories including subparts. Failure to answer or object timely waives objections (case law, S2).
- **§ 9-11-34(b)** (2025 Justia, S1 listing): written response within 30 days (45 for a defendant). The exact text was not retrieved. **[VERIFY]**
- **§ 9-11-36(a)** (2020 Justia / FindLaw, S1):
  - A matter is admitted unless a written answer or objection is served within 30 days (not before 45 days after service of the summons on a defendant).
  - (b) Admissions are "conclusively established" unless the court permits withdrawal (merits served, no prejudice).
- **§ 9-11-37** (2025 Justia, S1):
  - (a)(3) an evasive or incomplete answer is treated as a failure to answer.
  - (d) total failure to respond to interrogatories or inspection requests allows immediate sanctions under (b)(2)(A)–(C).
  - (d)(2) failure "may not be excused on the ground that the discovery sought is objectionable unless the party failing to act has applied for a protective order."
- **USCR 5.2** (official 2026 USCR PDF, https://assets.georgiacourts.gov/4/wp-content/uploads/2026/09/14025702/UNIFORM-SUPERIOR-COURT-RULES-2026_04_09.pdf , S1):
  - "(1) Depositions and other original discovery material shall not be filed with the court unless or until required by the provisions of OCGA § 9-11-29.1(a)(1)-(5)."
  - "(2) A party serving Interrogatories, Requests for Production of Documents, Requests for Admission and Answers or responses thereto upon counsel, a party or a non-party shall file with the court a certificate indicating the pleading which was served, the date of service ... and the persons served."
- **USCR 6.4(B)** (S1): before filing a motion to compel, "counsel for the moving party shall confer with counsel for the opposing party ... in a good faith effort to resolve the matters involved." Older versions require a filed certification of the conference. **[VERIFY current certification sentence]**
- **Uniform State Court Rules** (2019 text, https://www.gwinnettcourts.com/state-court/documents/UNIFORM_STATE_COURT_RULES_2019_03_07.pdf , S1): "The Uniform Rules for the Superior Courts shall be applicable in State Courts except as follows". The exceptions are USCR 24.1–24.7 (domestic relations) and 34.1–34.5 (unified appeal). Rule 15 (default) is superseded by USCR 15. **So USCR 5.2 and 6.4 apply in the Athens-Clarke State Court** (subject to any later order). **[VERIFY current]**

---

## Q8. Insurance: retroactive endorsement, certificates, loss payee vs. additional insured
- **O.C.G.A. § 33-24-19.1** (certificates of insurance), Justia 2024: https://law.justia.com/codes/georgia/title-33/chapter-24/article-1/section-33-24-19-1/ (S1). The search-quoted text includes:
  - "'Certificate' or 'certificate of insurance' shall not include a policy of insurance or insurance binder";
  - "A certificate of insurance shall not confer to a certificate holder new or additional rights beyond what the referenced policy of insurance expressly provides";
  - a required statement that a certificate is "not a policy of insurance and does not affirmatively or negatively amend, extend, or alter the coverage afforded by the policy" (S1/S2);
  - no person may alter or modify an approved form;
  - (i) applies to all certificate holders, policyholders, insurers, producers and forms "covering risks in Georgia";
  - the Commissioner enforces it.
  - **Version:** the Fastcase 2026 edition is captioned "**[Effective Until 1/1/2027]**," so an amended version is pending. **[VERIFY both versions; confirm whether a subsection (m) exists]**
  - Implementing rule: Ga. Comp. R. & Regs. 120-2-103. OCI Bulletins 21-EX-5, 23-EX-9 and 24-EX-4 say "A certificate is not an insurance policy and cannot be used to alter or expand coverage" (S1).
- **O.C.G.A. § 33-24-33 (binders)** (S1 via Georgia Farm Bureau Mut. Ins. Co. v. T & G Enterprises (Ga. App. 2013), https://www.courtlistener.com/opinion/7929280/ ).
  - "(a) Binders or other contracts for temporary insurance may be made orally or in writing and shall be deemed to include all the usual terms of the policy" (plus endorsements designated in the binder).
  - 90-day limit absent Commissioner approval.
  - Binders "are intended to provide temporary protection pending an investigation of the insured or pending issuance of the formal written policy."
  - **Reviewer note:** a binder is excluded from the certificate statute's definition. If the agent issued a **binder** naming Stevens, that binder can be contract coverage. A certificate cannot.
- **Parris & Son, Inc. v. Campbell (Ga. App. 1973)**, https://law.justia.com/cases/georgia/court-of-appeals/1973/47512-0.html (S1):
  - "coverage is not to be extended by estoppel or by waiver";
  - "the expression of an opinion as to coverage does not work an estoppel even against the agent who voiced it, or against his principal."
  - **Cuts both ways:** Stevens cannot use certificate defects to show *no* coverage, and the tenant cannot use a certificate to *create* coverage. Coverage turns on the policy and endorsements.
- **Retroactive or backdated endorsement:** **no Georgia appellate decision found (S0).** Industry sources only. **Gap.**
- **Loss payee vs. additional insured:** **no Georgia appellate decision found (S0).** Secondary sources only:
  - a loss payee has property-proceeds rights, derivative under a simple loss-payable clause;
  - a standard mortgagee clause creates an independent contract;
  - additional-insured status is a liability-policy concept.
  - **Gap. [VERIFY ON WESTLAW]**

---

## Q9. Holdover and reasonable-rental-value damages; sublessee privity
- **Howard v. Scott (Ga. App. 1950)**, https://www.courtlistener.com/opinion/5774833/howard-v-scott/ (S1): "If, in a dispossessory proceeding against a tenant at sufferance, the plaintiff prevails, the tenant holding over is liable for double the reasonable rental value of the premises from the date of the demand proved or presumed." This applied **former Code § 61-305**. **Whether a double-rent provision survives in current § 44-7-50 et seq. was NOT confirmed.**
- **Hall v. VNB Mortgage Corp. (Ga. App. 1984)** (S2, benchbook): a tenant at sufferance is liable for reasonable rental value for the period of occupancy. Acceptance of rent after termination can create a tenancy at will.
- **Hood v. Peck (Ga. App. 2004)** (S1 listing): holdover rent and loss-of-rental-value against a guarantor. Holding not retrieved.
- **Sublessee privity:** no current Georgia appellate holding found (S0).
  - General rule (secondary): no privity of estate between sublessee and prime lessor, so no direct rent liability absent assumption.
  - **Gulden v. Newberry Wrecker Service (Ga. App. 1980)** (S2): "a sublessee is bound by the rights of his lessor." That cuts against a blanket no-privity argument on *possession*: sublessees' possessory rights fall with the prime lease.
  - 1951 Mercer L. Rev. article on Georgia's "peculiar" transfer rules.
  - **Gap. [VERIFY ON WESTLAW]**

---

## Q10. Georgia Rules of Professional Conduct (the gabar.org text could not be fetched)
- Official index: https://www.gabar.org/general-counsel/georgia-rules-of-professional-conduct (S1 listing). The located PDF is the **pre-July 1, 2018** Part IV, so it may be superseded.
- **Rule 1.7(a)** (S2; Ga. L. Rev. quotation of GRPC 1.7(a) (2011), as paraphrased in the search summary): representation is barred where there is a "significant risk" that the lawyer's own interests or duties to another client, former client, or third person "will materially and adversely affect the representation," subject to (b) (informed consent). **[VERIFY current text]**
- **Rule 1.2(a) and Rule 1.4:** **text not retrieved (S0).** Titles confirmed on the gabar index ("Scope of Representation and Allocation of Authority Between Client and Lawyer"; "Communication").
- **Rule 3.3(a)** (S1 partial): opens "A lawyer shall not knowingly:".
  - Per the search summary, it bars false statements of material fact or law to a tribunal and failing to disclose adverse controlling authority. The duties "continue to the conclusion of the proceeding" and "apply even if compliance requires disclosure of information otherwise protected by Rule 1.6." "The maximum penalty for a violation of this Rule is disbarment."
  - **The subparagraph text was not retrieved. [VERIFY]**
- **Rule 3.4** (S1, Cobb Bar CLE copy and clarkcunningham.org). Georgia's version:
  - (b) bars falsifying evidence, assisting false testimony, and contingent witness compensation;
  - (f) restricts asking non-clients to refrain from giving information;
  - (g) bars evidence-gathering methods that violate the legal rights of the opposing party or counsel;
  - (h) bars threatening criminal charges solely for civil advantage.
  - **Whether Georgia's 3.4 contains the Model Rule 3.4(d) discovery-diligence clause ("reasonably diligent effort to comply with a legally proper discovery request") was NOT confirmed. [VERIFY]** Discovery-related misconduct may instead be framed under 3.4(a) (obstructing access to evidence) and 8.4.
- **Rule 4.1** (S1): "In the course of representing a client a lawyer shall not knowingly: (a) make a false statement of material fact or law to a third person; or (b) fail to disclose a material fact to a third person when disclosure is necessary to avoid assisting a criminal or fraudulent act by a client, unless disclosure is prohibited by Rule 1.6." Maximum penalty: disbarment.

---

## Q11. Our cited authorities (5/8/2026 Fulton verified complaint) and the Stevens correspondence cite

**(a) Peachtree on Peachtree Investors, Ltd. v. Reed Drug Co., 251 Ga. 692, 308 S.E.2d 825 (Nov. 16, 1983).**
- Located at https://www.courtlistener.com/opinion/1295754/peachtree-on-peachtree-investors-ltd-v-reed-drug-co/ (S1).
- **Facts:** Reed Drug leased two first-floor spaces in the Winecoff Hotel Building. The lessor's successor (Ackerman / Peachtree on Peachtree) invoked a **demolition-termination clause**. Reed sued for damages, specific performance and equitable relief.
- **Trial court:** granted Reed partial summary judgment. Demolition had not occurred within a reasonable time, and the lessor wrongfully leased to a third party without first offering Reed reoccupancy.
- **Supreme Court (S1 excerpts):**
  - "Provisions in leases which result in a forfeiture of a tenant's possessory rights will be strictly construed" (at 695(1), as quoted by Main Street Burger (Ga. App. 2024)).
  - "As a general rule the provisions of a lease will be construed against the lessor."
  - The court construed the lease to require that Reed be given the right to reoccupy. Reed argued the termination clause was a forfeiture provision that, once wrongfully exercised, may not be used again; **the court's resolution of that argument was not seen.**
- **Disposition (affirmed / reversed / in part): NOT confirmed.**
- **Our complaint's paraphrase:** "leases are construed against forfeiture, and a court will not declare a forfeiture of a long-standing leasehold based on insubstantial or technical noncompliance."
  - **Not supported as phrased.** The exact phrase "insubstantial or technical noncompliance" returned **no hit** anywhere (S0).
  - Peachtree supports **strict construction of forfeiture provisions and construction against the lessor**.
  - It is **not** a "technical noncompliance / long-standing leasehold" holding. It concerned a demolition-termination clause, not a tenant default.
- **Recommendation:** if the language is presented in quotation marks, replace it with the verified "strictly construed" sentence. Pair it with Mendel v. Pinkard (1963) and Nunn (materiality) for the substantiality point. **[VERIFY ON WESTLAW: disposition, pinpoint 695(1), exact quote]**

**(b) O.C.G.A. § 13-2-2(5)** (2017 Justia, https://law.justia.com/codes/georgia/2017/title-13/chapter-2/section-13-2-2/ ; georgiacommons.org/code/13-2-2, S1 **paraphrase only**): where construction is doubtful, the reading that goes most strongly against the party executing the instrument or undertaking the obligation is generally preferred. **The exact statutory words were not retrieved. [VERIFY]**
- **Caution:** construing against the party executing or undertaking the obligation can cut *against the lessee* for covenants the lessee undertook, such as the insurance covenant. Peachtree's "construed against the lessor" is the better lease-specific rule.

**(c) O.C.G.A. § 13-4-20** (2024 Justia, https://law.justia.com/codes/georgia/title-13/chapter-4/article-2/section-13-4-20/ , S1 paraphrase): performance is effectual only if made by the party bound, by an agent where personal skill is not required, or by someone substituted by consent. It must **substantially** comply with the contract's terms and be completed within a reasonable time (search paraphrase; exact words not retrieved).
- The first clause matches the coordinator's quoted text.
- **Relevance:** performance of the insurance covenant **by a sublessee or occupant** (rather than Bottle Stop, the lessee) is effectual only if by an agent or by "someone substituted, by consent." Stevens may argue this. Our side may argue substantial compliance.

**(d) O.C.G.A. § 14-2-510(b)(1)** (Justia 2025, https://law.justia.com/codes/georgia/title-14/chapter-2/article-5/part-2/section-14-2-510/ , S1 paraphrase): for general venue purposes a domestic or authorized foreign corporation is deemed to reside in the county where it maintains its **registered office** (or, if none, the last registered or principal office on Secretary of State records).
- Annotation: the registered office is "in addition to, and not in limitation of" other residences (subsection numbering differs by version).
- **Ga. Const. Art. VI, Sec. II, Para. VI** (FindLaw; SOS January 2023 PDF, S1): "All other civil cases ... shall be tried in the county where the defendant resides; venue as to corporations, foreign and domestic, shall be as provided by law."
- **Fact to confirm (not my workstream):** Stevens' registered-office county at filing (Fulton?) and whether any challenge to Fulton venue was raised or waived.

**(e) O.C.G.A. §§ 9-4-1 et seq.**
- **§ 9-4-2** (2024 Justia, captioned "**[Effective until 7/1/2026]**", https://law.justia.com/codes/georgia/title-9/chapter-4/section-9-4-2/ , S1):
  - "(a) In cases of actual controversy, the respective superior courts of this state and the Georgia State-wide Business Court shall have power, upon petition or other appropriate pleading, to declare rights and other legal relations of any interested party petitioning for such declaration..."
  - (b) extends to any civil case where "the ends of justice require that the declaration should be made."
  - "(c) Relief by declaratory judgment shall be available, notwithstanding the fact that the complaining party has any other adequate legal or equitable remedy or remedies."
  - **Version:** HB 1267 (2024) amends § 9-4-2 effective **July 1, 2026**, after the 5/8 filing but before the MTD rulings (business-court related; text not retrieved).
  - **Note:** (c)'s "other adequate remedy" clause answers part of Stevens' "available as a defense in the dispossessory" argument. The cases (Pinkard line) still require uncertainty about future conduct.
- **§ 9-4-1** (purpose; "to settle and afford relief from uncertainty and insecurity with respect to rights, status, and other legal relations"; liberally construed): **text not retrieved (S2 paraphrase only).**
- **§ 9-4-3:** **text not retrieved (S0).** **[VERIFY]**

**(f) O.C.G.A. § 33-24-19 vs. § 33-24-19.1** — **likely citation error by Stevens' counsel.**
- **§ 33-24-19** is titled "**Incorporation of constituent documents in policies**." Its text (S1, FindLaw): "No policy shall contain any provisions purporting to make any portion of the charter, bylaws, or other constituent document of the insurer a part of the contract unless the portion is set forth in full in the policy. Any policy provision in violation of this Code section shall be invalid." It does not apply to a reciprocal insurer's subscriber agreement.
- **The search showed no lettered subsections (f), (g), (i), (j), (m) in § 33-24-19.** Those subsections belong to **§ 33-24-19.1** (certificates of insurance). If Stevens' correspondence cited "§ 33-24-19(f), (g), (i), (j), (m)," it is miscited.
- Whether § 33-24-19.1 has a subsection **(m)** was not confirmed. OCI Bulletin 23-EX-9 references (n) and (o) for penalties, so (m) likely exists. **[VERIFY]**
- **Effect of a certificate naming a loss payee without an endorsement:** under § 33-24-19.1 as summarized, a certificate "shall not confer ... new or additional rights beyond what the referenced policy ... expressly provides."
  - **A certificate alone does not make Stevens a loss payee or additional insured.**
  - **Conversely, it does not prove the policy lacks that status.** The policy and endorsements control (Parris & Son).
  - A **binder** (excluded from the certificate definition; § 33-24-33) can bind temporary coverage including designated endorsements.

**(g) O.C.G.A. § 13-6-11** (2020 Justia, S1 via quotes in David G. Brown, P.E., Inc. v. Kent, 274 Ga. 849 (2002), and Kraft v. Dalton):
- Confirmed fragments only:
  - "[t]he expenses of litigation generally shall not be allowed as a part of the damages" (Kent's quotation);
  - "where the defendant has acted in bad faith, has been stubbornly litigious, or has caused the plaintiff unnecessary trouble and expense," the jury may award expenses as part of the damages (Kraft's quotation and paraphrase).
- The intervening clause (pleading and prayer requirement) was **not retrieved. [VERIFY full text]**
- Bad faith must relate to the underlying transaction before suit (Kent).
- No fees on appeal (Kent).
- A bona fide controversy defeats stubborn-litigiousness and unnecessary-expense fees (Scott v. White).
- **It is derivative.** If the Fulton claims are dismissed, Count III falls with them, as Stevens argues (MTD p. 7).

**Agent authority / binder before endorsement:**
- Georgia Farm Bureau v. T & G Enterprises (2013) treats § 33-24-33 as "the controlling statutory authority with regard to insurance binders." Forms or endorsements are included only if designated in the binder (S1).
- **No Georgia appellate case was found on an agent's actual or apparent authority to bind additional-insured or loss-payee status by certificate before an endorsement issues (S0).** Parris & Son (no coverage by estoppel) is the closest, and it cuts against coverage-by-certificate. **[VERIFY ON WESTLAW: Title 33, Chapter 23 agency statutes; "binder" plus "apparent authority"]**

---

## 12. Conflicts and discrepancies
1. **Pinkard filing sequence:** search summaries conflict.
   - One says the dispossessory was filed after the declaratory petition, alleged by amendment.
   - Another says it was filed the same day in Fulton Superior Court, with an injunction 6/1/1959.
   - A third calls it a "threatened" proceeding.
   - Must be read in full text.
2. **Stevens' MTD internal dates:**
   - "June 3, 2026" dispossessory vs. 6/23 file stamp per the brief.
   - "March 8, 2026" Fulton filing vs. 5/8.
   - "Plaintiffs terminated the Prime Lease and filed the dispossessory" (wrong party).
   - Source: the local mirror of the MTD, pp. 4–6.
3. **Pinpoints:**
   - Mabra is cited "at 62" (first page); citing courts use 65.
   - Speir is cited "at 788"; Davita cites 789.
   - The Pinkard second quote and the Imperial Hotel "shelter of equity" quote could not be found by exact-phrase search.
4. **§ 23-1-23** is described inconsistently as pro-relief vs. no relief where the contract clearly provides. Read it.
5. **§ 33-24-19 vs. § 33-24-19.1:** Stevens' subsection cites appear to belong to § 33-24-19.1.
6. **Our complaint's Peachtree paraphrase** ("insubstantial or technical noncompliance") is unverified and likely overstated.
7. **Ga. Const. Art. VI, Sec. IV, Para. I:** pre- and post-2018 wording differ ("exclusive ... equity cases" vs. "concurrent with the State-wide Business Court").
8. **Statute versions in transition:**
   - § 9-4-2 (eff. until 7/1/2026);
   - § 44-7-50 (new version eff. 1/1/2027);
   - § 33-24-19.1 (eff. until 1/1/2027);
   - § 44-7-51 (amended eff. 7/1/2025).
   - Cite the version in force on the operative date.
9. **"Patel v. Eager Holdings" (2026)** is an unrelated Patel. Do not confuse it with our client.

## 13. Gaps (where I looked; why it matters)
- **No full text of any authority was read.** Justia, CourtListener, Leagle, Casetext, gabar.org, gasupreme.us and gaappeals.us are blocked by the session network policy (curl 403; WebFetch ENOTFOUND). Only WebSearch summaries were available. **Every quote above needs Westlaw or Lexis confirmation before use in a filing.**
- No Georgia reversal was found that distinguishes Pinkard on lease facts. Gardei (2026) is the best substitute; read it in full.
- Not found:
  - a Georgia case on retroactive or backdated endorsements;
  - a Georgia case on loss payee vs. additional insured;
  - a Georgia case on agent authority to bind via certificate;
  - a current Georgia sublessee-privity holding;
  - the current double-rent provision (if any) for tenants at sufferance;
  - a Georgia cure-period rule absent lease language.
- Texts not retrieved: GRPC 1.2(a) and 1.4; whether a Georgia 3.4(d)-type discovery clause exists; § 9-4-3; § 9-4-1; the amended § 9-4-2 (eff. 7/1/2026); the § 44-7-50 version effective 1/1/2027; § 33-24-19.1(m).
- Dispositions not confirmed: Atlanta Airmotive (likely reversed), Schoen, Peachtree on Peachtree, Thor Gallery (vacated; transfer?), Mendel v. Pinkard (1963).
