# Writeup
# Identify A Threat

## Objective

The primary goal of this room is to analyze and identify a cyber threat using realistic threat intelligence tools and frameworks. Specifically, the objectives include:

-Analyze threat indicators using an intelligence platform (OpenCTI).

-Correlate artifacts (hashes, domains, IPs) from a USB drive (USBFerry attack).

-Use the MITRE ATT&CK framework to identify the tactics, techniques, and procedures (TTPs) used by the threat actor.

-Attribute the threat to a known APT group (e.g., Tropic Trooper).

-Understand the flow of threat intelligence analysis in a real-world environment.

### Skills Learned

-Threat Intelligence Analysis
Correlating IOCs (Indicators of Compromise) like hashes, IPs, and domains.
Recognizing patterns of behavior used by known threat groups.

-MITRE ATT&CK Framework Proficiency
Mapping observed behaviors to ATT&CK techniques and tactics.
Understanding how different ATT&CK components relate to one another.

-Investigative Research and Attribution
Using OpenCTI to research threat entities and campaigns.
Drawing links between artifacts and known threat actors.

-Analyst Workflow Development
Working through the process of collecting data, enriching it, and drawing conclusions.

### Tools Used

-OpenCTI (Open Cyber Threat Intelligence Platform)
A powerful platform for storing, visualizing, and correlating threat intelligence.
Used to search, analyze, and map out indicators and threat entities.

-MITRE ATT&CK Navigator (built into OpenCTI)
Visual reference for mapping tactics and techniques.
Helps identify what techniques are used in which stage of the kill chain.

-Trooper Platform
Simulated environment provided by TryHackMe to emulate a real-world analyst scenario.

-STIX & TAXII Concepts (Implied)
Structured data formats and protocols used for threat intelligence sharing.

-OSINT (Open-Source Intelligence) (as part of enrichment workflow)
Although not directly emphasized, the room encourages thinking like an analyst who would gather public data.



## Steps

---
Ref.1: scenario
<img width="959" alt="1- scenario" src="https://github.com/user-attachments/assets/6b7753c3-2c1f-4d72-b297-4d30981c3df7" />
---
Ref.2: question 1
<img width="398" alt="2- question 1" src="https://github.com/user-attachments/assets/db19c91b-1707-4467-8466-7abe8068352a" />
---
Ref.3: spearphishing text
<img width="724" alt="3- spearphishing text" src="https://github.com/user-attachments/assets/c25bdeb2-f50d-42a7-90d7-e348bfaafdc4" />
---
Ref.4: Question 1 answer
<img width="961" alt="4- question 1 answer" src="https://github.com/user-attachments/assets/956bc482-fa69-4cdc-a791-cadd301df6d6" />
---
Ref.5: Question 2
<img width="328" alt="5-q2" src="https://github.com/user-attachments/assets/6524afdc-483d-4a3b-995a-8b0bc507d10c" />
---
Ref.6: Malware identifcation
<img width="344" alt="6- malware identification" src="https://github.com/user-attachments/assets/626f7813-5811-4fe1-8b31-319ba1e854bb" />
---
Ref.7: Question 2 answer
<img width="967" alt="7- q2 answer" src="https://github.com/user-attachments/assets/fb3401ac-59e5-4d5b-b7f9-76225a362dc2" />
---
Ref.8: Question 3
<img width="996" alt="8-q3" src="https://github.com/user-attachments/assets/d7b93f19-a535-41f6-8ffc-b4ab82ce3e1a" />
---
Ref.9: Opencti, usbferry, stixID
<img width="1269" alt="9- opencti, usbferry, stixID" src="https://github.com/user-attachments/assets/de2d14df-0b53-4218-9224-8e96aa77615f" />
---
Ref.10: Question 3 answer
<img width="958" alt="10-q3 answer" src="https://github.com/user-attachments/assets/4dd1b292-ed9f-4916-87e1-4ca488527654" />
---
Ref.11: Question 4
<img width="960" alt="11-q4" src="https://github.com/user-attachments/assets/0eab5863-7906-4fbd-ab59-af2448cfbcc0" />
---
Ref.12: Initial access opencti
<img width="1262" alt="12 - initial access opencti" src="https://github.com/user-attachments/assets/122f451e-b331-4e3e-9174-e16fa45f2f9c" />
---
Ref.13: Question 4 answer
<img width="992" alt="13-q4 answer" src="https://github.com/user-attachments/assets/9406bbba-38f9-4942-8bef-5129b9bde602" />
---
Ref.14: Question 5
<img width="1010" alt="14- q5" src="https://github.com/user-attachments/assets/4a217a65-9253-434d-bda9-216e8d8decbe" />
---
Ref.15: Tropic Trooper
<img width="1277" alt="15- tropic trooper" src="https://github.com/user-attachments/assets/ac1db720-3ee8-4cff-85cf-d272d4dcc920" />
---
Ref 16: Question 5 answer
<img width="1009" alt="16-q5 answer" src="https://github.com/user-attachments/assets/4709ff0e-d8f4-4fae-9542-007dff3151f2" />
---
Ref.17: Question 6
<img width="997" alt="17-q6" src="https://github.com/user-attachments/assets/2eddddf8-1d9d-4464-8b1b-af3d91280838" />
---
Ref.18: tropic trooper, 39 attack patterns
<img width="1280" alt="18- topic trooper, 39 attack patterns" src="https://github.com/user-attachments/assets/d532b2a8-476d-4345-82a3-70fa8c9b59b6" />
---
Ref.19: Question 6 answer
<img width="1087" alt="19-q6 answer" src="https://github.com/user-attachments/assets/f11d4f70-a19d-499a-8aa8-04116f2f5d46" />
---
Ref.20 Question 6
<img width="344" alt="20-q6" src="https://github.com/user-attachments/assets/36de56e2-8894-45eb-b1d4-40bdea0f901c" />
---
Ref.21: Tropic trooper, tools, bitsadmin
<img width="1165" alt="21- tropic trooper, tools, bitsadmin" src="https://github.com/user-attachments/assets/705e65ab-879b-4061-8dc7-22e9d346674e" />
---
Ref.22: Question 6 answer
<img width="922" alt="22- q6 answer" src="https://github.com/user-attachments/assets/e72b68ea-c34b-41e2-bd6d-0b0141918ccb" />
---
Ref.23: Question 7
<img width="980" alt="23-q7" src="https://github.com/user-attachments/assets/a84c2c44-de26-4dd5-b8ec-8ff0fd6b2f6d" />
---
Ref.24: trooper, valid accounts, local accounts highlighted
<img width="276" alt="24- trooper, valid accounts, local accounts highlighted" src="https://github.com/user-attachments/assets/6e2d67b8-4bfa-479c-8676-1f2de0a9cb28" />
---
Ref.25: Question 7 answer
<img width="971" alt="25- q7 answer" src="https://github.com/user-attachments/assets/e52b1cc6-ec27-48cc-a080-744064e42a7e" />
---
Ref.26: Question 8 
<img width="1102" alt="26-q8" src="https://github.com/user-attachments/assets/6d19aed0-605a-43bd-a098-88f1d954380f" />
---
Ref.27: valid accounts, local accounts, tactics
<img width="1259" alt="27- valid accounts, local accounts, tactics" src="https://github.com/user-attachments/assets/5c9758af-d0cd-421d-b794-1ae0ca38c805" />
---
Ref.28: Question 8 answer
<img width="983" alt="28- q8 answer" src="https://github.com/user-attachments/assets/2effdaa5-afc1-42fe-a03e-252fc83f2f01" />
---
Ref.29: Question 9
<img width="965" alt="29- q9" src="https://github.com/user-attachments/assets/1a3e68d2-fc27-41f8-bf5d-65a618b71894" />]
---
Ref.30: collection, automated collection
<img width="286" alt="30- collection, automated collection" src="https://github.com/user-attachments/assets/bb25afd1-3250-4924-bd33-606636cc9d27" />
---
Ref.31: Question 9 answer
<img width="803" alt="31-q9 answer" src="https://github.com/user-attachments/assets/859e3c51-1612-4e9e-b93c-0d9debe9c9f9" />
---






















