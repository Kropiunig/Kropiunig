# Europe-wide PI map: agentic/multi-agent LLMs, evals/benchmarks, AI x blockchain (for a 3–12 month research stay)

Scope note: About 16 web searches and fetches were run (late Nov 2026). Entries marked **[V]** have a 2025–2026 source cited below confirming the affiliation or work. Entries marked **[U]** come from background knowledge only, and their affiliation or paper details have NOT been re-verified in this pass. The report writer should treat [U] items as leads, not facts. One fetch failed because people.inf.ed.ac.uk is blocked by the network allowlist.

## Which European groups publish most on LLM agents / multi-agent LLMs / cooperative AI / agent safety & security (Theme 1)?

### Takeaway
The strongest verified Theme-1 hosts are these four.
- ETH Zurich SPY Lab (Tramèr): agent security, with the AgentDojo and CaMeL lines of work.
- ELLIS Institute Tübingen / MPI-IS: Abdelnabi's COMPASS group (multi-agent safety and prompt injection) and Andriushchenko's AISA group (agent alignment and evals).
- Oxford FLAIR (Foerster): multi-agent LLM coordination.
- UCL DARK (Rocktäschel): open-endedness and agents.

Stefano Albrecht has LEFT Edinburgh for NTU Singapore, so he is out of scope. The Edinburgh Autonomous Agents group should not be listed under his name.

### Cited Findings
- **Sahar Abdelnabi**
  - PI at the ELLIS Institute Tübingen, leading the COMPASS group ("COoperative Machine intelligence for People-Aligned Safe Systems"). She is also an Independent Research Group Leader at MPI for Intelligent Systems. **[V]**
  - Group focus: safe, aligned, interpretable and steerable AI agents, with an emphasis on security, human aspects and cooperative multi-agent systems.
  - She was previously at the Microsoft Security Response Center, and did her PhD at CISPA/Saarland. — [MPI-IS news](https://is.mpg.de/news/sahar-abdelnabi-starts-her-position-as-new-group-leader); [ELLIS profile](https://institute-tue.ellis.eu/person/sabdelnabi)
  - Recent papers: "Firewalls to Secure Dynamic LLM Agentic Networks" (arXiv 2025); "Cooperation, Competition, and Maliciousness: LLM-Stakeholders Interactive Negotiation" (ICLR 2025); "Safety is Essential for Responsible Open-Ended Systems" (arXiv 2025). She pioneered work on indirect prompt injection. — [s-abdelnabi.github.io](https://s-abdelnabi.github.io)
- **Maksym Andriushchenko**
  - Leads the AI Safety and Alignment (AISA) group at the ELLIS Institute Tübingen, and is a PI at MPI-IS. **[V]**
  - Group interests: alignment of autonomous LLM agents, rigorous AI evaluations, and generalization.
  - EPFL PhD in 2024 under Flammarion. He is chapter lead for the International AI Safety Report, and a MATS mentor.
  - Sources conflict on his title. An older ELLIS page says "postdoc at EPFL", while Schmidt Sciences and MATS say PI. — [ELLIS AISA](https://institute-tue.ellis.eu/aisa); [MPI-IS AISA](https://is.mpg.de/aisa); [MATS mentor page](https://www.matsprogram.org/mentor/andriushchenko)
- **Florian Tramèr, SPY Lab, ETH Zurich** **[V]**
  - Assistant professor at ETH Zurich.
  - AgentDojo (NeurIPS 2024 Datasets & Benchmarks, with Invariant Labs) has a public leaderboard and a pip package. NIST CAISI used it for agent-hijacking evaluations. — [arXiv 2406.13352](https://arxiv.org/abs/2406.13352v3); [NIST](https://www.nist.gov/node/1872381); [PyPI agentdojo](https://pypi.org/p/agentdojo)
  - CaMeL, "Defeating Prompt Injections by Design" (March 2025). — [Schmidt Sciences profile](https://www.schmidtsciences.org/profile-2025/florian-tramer/)
  - "The Attacker Moves Second" (2025) shows adaptive attacks bypassing jailbreak and prompt-injection defenses. — [arXiv 2510.09023](https://arxiv.org/html/2510.09023v1)
  - Open-source culture: GitHub org ethz-spylab. — [GitHub](https://github.com/ethz-spylab)
- **Jakob Foerster, FLAIR, Oxford** **[V for work; title U]**
  - "Zero-Shot Coordination among LLM Agents" (Hayler, Chirra, Lupu, Forkel, Sarkar, Feng, Foerster) finds that frontier LLM agents fail to coordinate with novel partners. The secondary article dates it Nov 2026, which is unverified against arXiv. — [cryptobriefing](https://cryptobriefing.com/oxford-study-llm-agents-coordination-failures/)
  - Co-author of the Cooperative AI Foundation's "Multi-Agent Risks from Advanced AI" (Tech Report #1). — [arXiv 2502.14143](https://web3.arxiv.org/pdf/2502.14143)
- **Oxford / KCL position paper**: "Large Language Models Miss the Multi-Agent Mark" (NeurIPS 2025 position track). Its authors are from Oxford, KCL, Sussex and others. — [arXiv 2505.21298](https://arxiv.org/html/2505.21298v1); [ORA](https://ora.ox.ac.uk/objects/uuid:36deedad-9a8a-4cc7-87e1-cc3b6d48baf3)
- **Tim Rocktäschel, UCL DARK** **[V]**
  - Professor of AI at UCL and PI of the DARK Lab; ELLIS Fellow.
  - Focus: AGI, open-endedness, self-improvement, and foundation world models.
  - Also linked to Google DeepMind's Open-Endedness team. His current industry title was not confirmed. — [ICLR 2025 invited talk](https://iclr.cc/virtual/2025/invited-talk/10000536); [rockt.github.io](https://rockt.github.io)
- **Stefano V. Albrecht** **[V — MOVED]**
  - Now an Associate Professor at NTU Singapore (College of Computing and Data Science), leading the Autonomous Agents Research Group there.
  - An NTU news item from Oct 2026 confirms this. The Edinburgh pages are stale. — [NTU news, 28 Oct 2026](https://www.ntu.edu.sg/computing/news-events/news/detail/ntu-ccds-professor-publishes-ai-book-with-cambridge-university-press); [agents-lab.org](https://agents-lab.org/)

### Inferences
Ranked Theme-1 shortlist for the person's profile: agents, open-source tooling (pydantic, litellm, ray) and security. Verification status is given for each.

1. **Abdelnabi (COMPASS), ELLIS Tübingen / MPI-IS** [V]
   - Fit: the best single match for multi-agent LLMs, agent security and negotiation benchmarks.
   - ELLIS Tübingen is used to hosting visitors; it runs an ELLIS PhD/exchange programme.
2. **Tramèr (SPY Lab), ETH Zurich** [V]
   - Fit: agent security and benchmarks, with strong open-source code.
   - The person's pydantic and litellm experience maps directly onto the AgentDojo-style harnesses.
3. **Andriushchenko (AISA), ELLIS Tübingen** [V]
   - Fit: agent alignment and evals, e.g. AgentHarm, which he co-authored [U for exact venue].
   - MATS-mentor culture suggests openness to short-term researchers.
4. **Foerster (FLAIR), Oxford** [V]
   - Fit: multi-agent LLM coordination and cooperative AI.
   - FLAIR is JAX-heavy and runs a large open-source program (JaxMARL etc.) [U].
5. **Rocktäschel (DARK), UCL** [V]
   - Fit: open-ended agents, plus DeepMind links.
6. **Michael Wooldridge, Oxford** [U]
   - Fit: classic MAS meeting LLMs. He gave an NTU IAS talk, "Rethinking Multi-Agent Systems in the Era of LLMs", whose date was not checked. — [NTU IAS](https://www.ntu.edu.sg/ias/news-events/news/detail/rethinking-multi-agent-systems-in-the-era-of-large-language-models-by-prof-michael-wooldridge)
7. **EPFL** [U]
   - Robert West (dlab: LLM agents, societal simulation), Antoine Bosselut (NLP, knowledge, agents) and Nicolas Flammarion (TML: jailbreak robustness, JailbreakBench with Andriushchenko).
8. **Mario Fritz / CISPA, Saarbrücken** [U]
   - Fit: LLM security and agents. CISPA has a large visiting-researcher culture.
9. **Cooperative AI Foundation (London)** [U]
   - Lewis Hammond (also Oxford) leads research. The Multi-Agent Risks report links many European PIs. CAIF runs summer schools and fellowships [U].
10. **IIIA-CSIC Barcelona** [U]
    - Carles Sierra, Juan A. Rodríguez-Aguilar et al.: norms, agreement technologies and LLM-agent value alignment. Natural hosts for AAMAS-style MAS.
11. **Utrecht University** [U]
    - Mehdi Dastani (intelligent systems, normative MAS). Also **TU Delft** [U]: Catholijn Jonker / Pradeep Murukannaiah / Luciano Siebert (hybrid intelligence, LLM agents, values).
12. **King's College London** [U]
    - Fit: the MAS group (e.g. Michael Luck, now at Sussex [U], plus co-authors of the Oxford/KCL position paper). Also UCL's Mirco Musolesi (multi-agent LLM, machine behaviour) [U, he splits UCL/Bologna].
13. **Cambridge** [U]
    - David Krueger moved to Mila/Université de Montréal around 2025 [U — likely out of Europe; verify]. Andreas Vlachos (factuality, agents) [U].
14. **University of Copenhagen** [U]
    - Isabelle Augenstein (NLP, factuality, LLM evaluation) and the Pioneer Centre for AI, which has visiting programmes.
15. **University of Amsterdam** [U]
    - Fit: AMLab / ILLC, e.g. Herke van Hoof (RL) and Frans Oliehoek at TU Delft (multi-agent decision making) [U].
16. **Apollo Research, London** [U]
    - Marius Hobbhahn: agentic scheming evals and in-context scheming (2024–25) [U]. A non-academic lab, but it hosts fellows and MATS scholars.

### Gaps
- No publication-count ranking across NeurIPS/ICML/ICLR/AAMAS/ACL 2024–2026 by European institution was found. A DBLP/OpenReview scrape would be needed.
- Edinburgh after Albrecht: the current lead of the agents group (agents.inf.ed.ac.uk) was not checked. The page could not be fetched because the host was blocked.
- David Krueger's and Michael Luck's current affiliations were not verified.
- Wooldridge's and Foerster's titles and visitor policies were not checked on primary pages.

## Which groups hold evaluation/benchmark work (HELM-like, agent benchmarks, AISI Inspect, safety evals, auditing)? (Theme 2)

### Takeaway
UK AISI's Inspect / Inspect Evals is the dominant European open-source eval ecosystem. Contributing to it is a strong fit for the person's open-source record.

Academic eval and benchmark hubs:
- ETH SPY Lab (AgentDojo).
- ELLIS Tübingen AISA (agent evals).
- EPFL Flammarion (JailbreakBench) [U].
- Tübingen's Bethge / Brendel ecosystem [U].

### Cited Findings
- **UK AISI Inspect / Inspect Evals** **[V]**
  - Inspect Evals is a community-contributed benchmark repo built on Inspect AI, the open-source framework from the UK AI Security Institute. It was co-created with Arcadia Impact and the Vector Institute.
  - It includes the agent benchmarks GAIA, SWE-Bench, GDM CTF, Cybench and AgentBench, plus CodeIPI (coding agents and embedded malicious instructions). — [AISI Inspect Evals](https://www.aisi.gov.uk/work/inspect-evals); [inspect.aisi.org.uk](https://inspect.aisi.org.uk)
  - It has more than 200 pre-built evaluations. — [AISI engineering playbook](https://www.aisi.gov.uk/blog/releasing-aisis-engineering-playbook)
  - From 8 May 2026, community contributions move to a /register/ folder and require a GitHub issue with an arXiv URL and a source code link. — [GitHub wiki](https://github.com/UKGovernmentBEIS/inspect_evals/wiki)
- **AgentDojo (ETH SPY Lab)** is used by NIST CAISI for agent-hijacking evaluations. — [NIST](https://www.nist.gov/node/1872381)
- **Andriushchenko's AISA group** lists "rigorous AI evaluations" as a core interest. — [ELLIS AISA](https://institute-tue.ellis.eu/aisa)
- **Abdelnabi** lists "evaluation robustness" as an expertise, and ran the SaTML 2024 LLM CTF dataset. — [ELLIS profile](https://institute-tue.ellis.eu/person/sabdelnabi); [s-abdelnabi.github.io](https://s-abdelnabi.github.io)

### Inferences
Theme-2 shortlist:
1. **UK AISI (London)** [V for Inspect]
   - Not an academic host, but it has fellowship and secondment pathways and the Inspect open-source community [U for visitor schemes].
   - The person's pydantic and litellm skills directly match Inspect's provider and solver architecture.
2. **ETH SPY Lab** [V]
3. **ELLIS Tübingen AISA** [V]
4. **EPFL TML (Flammarion)** [U]
   - Work: JailbreakBench (NeurIPS 2024 D&B, with Andriushchenko).
5. **Tübingen AI Center** [U]
   - Matthias Bethge (benchmarks, open-ended evaluation), Wieland Brendel and Jonas Geiping (ELLIS/MPI-IS: LLM security and evals) [U].
6. **Apollo Research** [U]: scheming and deception evals.
7. **Oxford Internet Institute / Oxford Reasoning with Machines Lab** [U]
   - Adam Mahdi: benchmark validity, e.g. the 2025 "measuring what matters" construct-validity review of LLM benchmarks [U].
8. **Cambridge Leverhulme CFI** [U]
   - José Hernández-Orallo (also at Valencia, UPV): AI evaluation science, capability measurement. A top-tier eval-methodology host [U].
9. **Saarland / CISPA** [U]: security evals.
10. **Copenhagen (Augenstein)** [U]: NLP evaluation and factuality.
11. **Bocconi** (Dirk Hovy, MilaNLP) [U]: LLM evaluation and sociodemographic bias.

### Gaps
- AISI's visiting, fellowship and secondment terms for non-UK PhDs were not verified.
- The Hernández-Orallo, Mahdi and Geiping details are unverified in this pass.

## AI x blockchain / mechanism design / DeFi / MEV / smart-contract security with ML: which European academic groups? (Theme 3)

### Takeaway
Arthur Gervais (UCL) is the clearest European PI at the intersection of AI agents and DeFi. Christof Ferreira Torres is a key MEV / smart-contract-security researcher, but his current institution could NOT be verified. Other likely hosts:
- ETH DISCO (Wattenhofer)
- Edinburgh (Kiayias / IOG)
- Imperial (Knottenbelt)
- TU Wien (Maffei)
- IMDEA (Garcia-Alfaro?) — not verified
- Aarhus (Concordium)
- Luxembourg SnT

### Cited Findings
- **Arthur Gervais, UCL** **[V for work; exact title unclear]**
  - "AI Agent Smart Contract Exploit Generation" (A1), with Liyi Zhou (Sydney), arXiv 2507.05558 (v4 Jan 2026). An agentic LLM system generates and validates exploits on forked chain state, with a 63% success rate on VERITE and up to $8.59M per exploit. — [arXiv 2507.05558](https://arxiv.org/abs/2507.05558v4)
  - TxRay (arXiv 2602.01317): an LLM agent that produces Foundry PoC replays of DeFi exploits, evaluated on 120 DeFiHackLabs incidents. — [arXiv 2602.01317](https://arxiv.org/html/2602.01317v4)
  - Profiles list group interests in decentralized intelligence, LLMs and DeFi, plus BlockGPT (LLMs on blockchain transactions). Crunchbase says "Associate Professor", other sources say "Professor". — [Crunchbase](https://www.crunchbase.com/person/arthur-gervais); [UCL blockchain](https://blockchain.cs.ucl.ac.uk/?p=8)
- **Christof Ferreira Torres** **[U — current affiliation unverified]**
  - The only located affiliation is University of Luxembourg SnT, with Radu State: frontrunning detection, ~200,000 frontrunning attacks found (USENIX Sec 2021). He did his TUM dissertation on smart-contract security. — [SnT highlights](https://snt-highlights.uni.lu/?p=12493); [TUM dissertation](https://mediatum.ub.tum.de/doc/1641114/1641114.pdf)
  - His Layer-2 rollup MEV analysis (Apr 2024) is cited in a 2026 MEV SoK. — [arXiv 2603.07716](https://arxiv.org/html/2603.07716v1)
  - Searches for an ETH Zurich or IST Lisbon faculty post returned nothing. A SECO note on "15 new professors appointed at the two Federal Institutes of Technology" appeared in results, but it was not confirmed to include him. — [SECO](https://www.seco.admin.ch/seco/en/home/seco/nsb-news.msg-id-71504.html)
- **Wattenhofer DISCO** **[U]**: no 2025 DISCO paper on LLM agents and blockchain was found in search. Related non-DISCO work:
  - "SoK: Security and Privacy of AI Agents for Blockchain" (Romandini, Mazzocca, Otsuki, Montanari; Bologna; BCCA 2025). — [arXiv 2509.07131](https://arxiv.org/html/2509.07131v1)
  - "Giving AI Agents Access to Cryptocurrency" (2025). — [arXiv 2507.08249](https://arxiv.org/html/2507.08249v2)
- **Cambridge Judge Business School** published "Where AI meets blockchain: assets, agents and blind spots" in 2026; this points to CCAF / JBS interest. — [JBS 2026](https://www.jbs.cam.ac.uk/2026/where-ai-meets-blockchain-assets-agents-and-blind-spots/)
- A Frontiers research topic, "Blockchain, DeFi and AI: Economic Systems, Intelligent Agents, and Mechanism Design", is evidence of an emerging field. Its editors were not checked. — [Frontiers](https://www.frontiersin.org/research-topics/81179/blockchain-defi-and-ai-economic-systems-intelligent-agents-and-mechanism-design)

### Inferences
Theme-3 shortlist:
1. **Arthur Gervais, UCL (London)** [V]
   - The best fit for LLM agents and DeFi security. The person's viem and CoW Protocol work fits A1/TxRay-style forked-state tooling.
2. **Roger Wattenhofer, ETH Zurich DISCO** [U]
   - Fit: blockchain, MEV, DEX/AMM theory and graph learning. DISCO hosts many master's and visiting students [U].
3. **Aggelos Kiayias, Edinburgh Blockchain Technology Lab / IOG** [U]
   - Fit: protocol design and incentives.
4. **William Knottenbelt, Imperial Centre for Cryptocurrency Research and Engineering** [U]
5. **Matteo Maffei, TU Wien Security & Privacy / CDL-BOT** [U]
   - Fit: formal verification of smart contracts, payment channels, and possibly MEV and AI-agent work.
6. **Christof Ferreira Torres** [U — locate first]
   - Fit: MEV and LLM-assisted contract analysis.
7. **Sarah Meiklejohn, UCL** [U]: cryptocurrency security and transparency. She is also at Google, so her availability as a host is unclear.
8. **Bryan Ford, EPFL DEDIS** [U] (decentralized systems). Also **EPFL DCL** (Rachid Guerraoui) [U].
9. **University of Luxembourg SnT** [U]: Radu State's SEDAN group (blockchain, ML for security).
10. **Aarhus University, Concordium Blockchain Research Center** [U]: crypto and incentive design. Its funding status after 2024 was not verified.
11. **IMDEA Software (Madrid)** [U]: smart-contract verification, e.g. César Sánchez's group, plus possibly a separate blockchain group whose PIs were not verified.
12. **Bocconi** [U]: economics of crypto / mechanism design. **Cambridge CCAF** [U]: crypto-economics policy research.
13. **Mechanism design for batch auctions / intents (CoW-adjacent)** [U]
    - Industry and academic links via Flashbots, the Ethereum Foundation Robust Incentives Group, and CoW DAO research grants.
    - Candidate academics: Andrea Canidio (CoW Protocol, with academic papers on batch auctions) and Fabio Maffei? [U — unverified names].
14. **Uni Bern** (Christian Cachin, cryptology and distributed systems) [U].

### Gaps
- Ferreira Torres's current post is unresolved. Check his Google Scholar or personal site before contacting him.
- No DISCO 2024–26 LLM x blockchain paper was confirmed.
- The Kiayias, Knottenbelt, Maffei, Aarhus and IMDEA details were not verified this pass.
- No CoW-specific academic mechanism-design group was located in search.

## Groups explicitly advertising visiting student positions

### Takeaway
No explicit visiting-PhD calls were verified in this pass. The visitor-friendly signals found were:
- MATS mentorship (Andriushchenko).
- Inspect Evals' public contribution pathway (AISI).
- ELLIS institute structures.

### Cited Findings
- Andriushchenko is a MATS mentor, which shows short-term researcher hosting. — [MATS](https://www.matsprogram.org/mentor/andriushchenko)
- Inspect Evals accepts community contributions through a registered process. — [GitHub wiki](https://github.com/UKGovernmentBEIS/inspect_evals/wiki)

### Inferences
- The ELLIS PhD & Postdoc Program exchange stays (Tübingen, ETH, Oxford, UCL, EPFL and other ELLIS units) are the most formal route [U for 2026 call dates]. CISPA, IIIA-CSIC and the Pioneer Centre (Copenhagen) traditionally host visiting PhDs [U].

### Gaps
- Specific 2026–27 visiting-student announcements for these groups were not found or checked.
