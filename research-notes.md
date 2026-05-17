# Research Notes - AI-Driven Social Engineering
**Author**: Kurutsi Manasseh  
**Program**: The Purpose Protocol — Cohort 1  
**Date**: Week 1, Sept 2026  

---

## 1. Initial Questions
- How is AI changing social engineering attacks in 2025/2026?
- What makes AI voice cloning different from old vishing?
- Are Nigerian/West African orgs actually getting hit by this?
- What can a small team do without buying expensive tools?

## 2. Key Findings & Quotes

### BBC Deepfake CFO Case - Feb 2024
- "Finance worker pays out $25m after video call with deepfake ‘chief financial officer’"
- Multiple people on call were fake. Used real employees’ names and faces.
- Source: https://www.bbc.com/news/world-asia-68359054
- Takeaway: Video + voice cloning is now credible enough to fool finance teams.

### MITRE ATT&CK T1566.001 – Spear phishing Voice
- Technique: Adversaries may use AI-generated voices to impersonate trusted individuals.
- MITRE notes this bypasses email filters and MFA if call is the only check.
- URL: https://attack.mitre.org/techniques/T1566/001/
- Mapping: Initial Access > Phishing

### Trend Micro Report 2024
- AI lowers barrier: No need for actors or linguists anymore.
- Attackers use LLMs to write emails in local languages, match company tone.
- Link: https://www.trendmicro.com/vinfo/us/security/news/cybercrime-and-digital-threats
- Note: Saw mention of WhatsApp being used heavily in West Africa for these scams.

### NITDA Nigeria Cybersecurity Outlook 2025
- Social engineering listed as top threat for Nigerian SMEs and govt agencies.
- Public officials have lots of audio/video online = easy for cloning.
- URL: https://www.nitda.gov.ng
- Action item: Check if NITDA has specific guidance on call back policies.

## 3. Nigeria-Specific Examples
- Lagos SME loss ₦12M, 2025: Fake supplier on WhatsApp, AI chatbot held convo for 2 weeks.
- Source: Local news, need to verify exact outlet. [TODO: find link]
- Pattern: Urgency + new account + refusal to verify on known number.

## 4. Tools & Detection Ideas
- AI detection tools exist but have high false positives. Not reliable alone.
- Low-cost: Safe word system, call back policy, MFA with passkeys.
- Process change matters more than tech for most SMEs.

## 5. Random Links & Tabs to Check Later
- https://openai.com/research/gpt-4 - system card mentions misuse risks
- https://www.mandiant.com/resources/reports/m-trends - check 2025 section on social eng
- Search term: "AI vishing Nigeria 2025" - got some LinkedIn posts, not sure if credible.
- YouTube: "deepfake voice cloning demo" - want to clip 30s for training demo.

## 6. Things I’m Unsure About
- How common is this really in Nigeria vs other regions? Data is thin.
- Legal reporting requirements if you get hit? Need to check NITDA/NCC.
- What’s the cost of basic MFA for a 20-person SME?

## 7. Next Steps
- Verify Lagos SME case with source.
- Check if NITDA has published playbook for voice cloning attacks.
- Draft 5-slide training deck using BBC case + local example.
- Ask mentor if safe word system is actually used in Nigerian banks.

---

**Notes**: Keep this file messy. It’s for showing research process, not final output.
