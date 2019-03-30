# London 20th March 2019

## Session Notes

### Topic 1 - Security culture through threat modeling? (11 votes)

![Topic 1](https://raw.githubusercontent.com/threatmodelingmeetup/outputs/master/london_20190320/20190320_210229.jpg)

#### Discussions

* Solidify what threat modeling means to you (org)
* Involving none security teams
* Does not have to be perfect
* Arrogance in security professionals
* How do we influence security fixes in other teams?
* Understand business requirements and risk appetite

#### What we learned

* What you see on the news is normally the result of not doing basic security B.P.
* Keep it simple
* Threat modeling is a social activity, not just a technical one
* Threat modeling to empower engineering teams to be part of security process, rather than a consumer of it

### Topic 2 - How do you measure the value of threat modeling? (12 votes)

![Topic 2](https://raw.githubusercontent.com/threatmodelingmeetup/outputs/master/london_20190320/20190320_210326.jpg)

#### Objectives

* Making it easier to satisfy auditors
  * Every control that's needed -> Take value of control as value of threat model
* Persuade devs to adopt (audience)
  * Value in skilling up employees
    * More efficient delivery
    * Motivation
  * Collaboration is unquantifiable
* Product Owners
  * "Safe to market"
  * "Predictable delivery"
* A good outcome is *not* doing something. Based on threat modeling. 10 things that aren't worth doing.
* Supporting of risk management tools.
  * Threat modeling is a maintaining business cost.

#### Discussions

* Threat model the enterprise
  * Acquisition
  * 3rd party
* OKRs as a driver, but what are the objectives?
* Objective: Has audience
  * Auditors
  * Regulation
  * Product Owners
  * Devs
* With embedded QA

#### What we learnt (key results)

* Control value (threat model value) = ( ALE before - ALE after) / (Cost of control or threat model)
* Threat modeling, if it feeds into another OKR, it becomes measurable (if that OKR is measurable)
* Look at AppSec findings and ask "where should this have been considered?"
  * If threat modeling is the answer, then value
  * For anything you have seen
  * Value is expressed in showing all ways biz could be damaged (R.C.A.)
* Key result: Pentest findings decrease 
  * Time of discovery of finding - if at end, then threat modeling would have saved money

### Topic 3 - What is the best way to get started with threat modeling for an organisation? (9 votes)

![Topic 3](https://raw.githubusercontent.com/threatmodelingmeetup/outputs/master/london_20190320/20190320_210235.jpg)

#### Discussions

* What are you trying to archieve?
* Is there an industry standard? (no)
* Is there already a mature framework?
* What help can I get?
* System level vs separate components

#### What we learned

* How to fit in agile / lean
* Feature checklist: Does it trigger threat modeling?
* Business context of outcomes helps buy-in
* Educate champions / security team as a seed
* Educate devs: Troy Hunt
* Champion can be perceived as team's enemy
* Pilot team
* Scare management with competitor story
* Support (down) / Interest (up)
* How can threat modeling help drive positive change?
* Mitre <3
* Stakeholder buy-in is critical to threat modeling success
* Unfetter (https://nsacyber.github.io/unfetter/)

### Topic 4 - Rapid Threat Model Prototyping 

![Topic 4](https://raw.githubusercontent.com/threatmodelingmeetup/outputs/master/london_20190320/E-ru4zEI.jpg)

* Process-oriented
* Automated, reporting autoamted
* Re-address trust boundaries
* Things that are outside model discarded. Data on disk; high ranking
* Simple STRIDE -> Then mitigate. CVE, ASVS
* MVP in sprint, iterate
* Trigger points, changes demand new model
* Repeatable flows: Login, signup, logging etc.
* Reducing cycle time with patterns
* Get architect or team to draw diagram
  * Score (fear/trust score):
     * 0 - outside of control
     * 1-9 (talks to outside world)
     * 9 (data on disk)
* Elevation of privilege ???? step up
* Spoofing at ingress, identity enforcement
* Tampering: lower to higher
* Repudiation: authless, tamperable, logless etc.
* Info disclosure: at step-down points
* DoS: Something out-of-control coming in
* Takes nodes and vectors, tag, generate threats -> black duck integration
* Backs off to security champion
* Numbers: likelihood, impact, severity?, combined?

## Suggested Topics

![Suggested Topics](https://raw.githubusercontent.com/threatmodelingmeetup/outputs/master/london_20190320/20190320_211759.jpg)

* Discrete components vs system & emergent (6 votes)
* JWT-Auth APIs
* Empathy maps & design thinking in threat modeling?
* Threat modeling state-sponsored "employees" or equipment
* Examples of how you (successfully) implemented threat modeling into your process (3 votes)
* How do we upskill delivery teams to perform threat modeling in a high cadence delivery environment? (9 votes)
* AJAX Apps (1 vote)
* Mitre ATT&CK - The future of threat modeling? (2 votes)
* Agile architecture
* D.P. / Ethics
* Asset-based threat modeling (1 vote)
* Threat modeling frameworks (1 vote)
* What is threat modeling?
* Code-driven threat modeling - The future of agile threat modeling? (3 votes)
* Concentric circles / layers of threats: perimeter -> trust
* Domain specific threats
* Github
* Cloud Architecture (5 votes)
* J.I.T documentation
* Is threat modeling growing / maturing as an industry practice?
* STRIDE - Is it still relevant? (2 votes)
* How would the threat modeling fit into the whole risk assessment picture? (1 vote)
* Who is responsible for what in the threat modeling process? (3 votes)
* AI / ML in Cyber
* What artifacts should a threat model create? (3 votes)
* How do you run a threat modeling session? (1 vote)
* Managing threat modeling - tools (excel, confluence/jira, Mitre/unfetter, other)?
* Threat modeling for DNS
* Threat intel vs secure systems
* How to utilise threat modeling as part of SSDLC (1 vote)
* Continuous security pipeline (1 vote)
* CI/CD pipeline (1 vote)
* Enterprise-wide threat model framework (5 votes)
* What bits of threat modeling should we automate? (2 votes)
* Think of a more intuitive name than "threat modeling"
* How to explain threat modeling to people






