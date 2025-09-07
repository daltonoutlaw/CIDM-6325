# Prompt 1

What could be some possible problems I could use to answer the prompt of this project using the example provided by the instructor?

Module 1 Project Pitch Companion
Here is a Companion to JUST the Project Pitch Component of Module 1's Assignment (All others are deferred).
NOTE: I did use an LLM to explore answers to the prompts, I hope you will too.
I provide an illustration based on the prompts:
The Prompt Given:
A. Project Pitch (100 points)
Deliverables
2–3 page memo (≈800–1,000 words): problem, stakeholders, scope, success metrics; define a minimal viable artifact shippable within 2 weeks.
System sketch: labeled diagram (block/sequence) showing front‑end back‑end data OR AI touchpoints.
Evidence base: at least 3 authoritative sources (industry reports, academic articles, standards). Use a consistent citation style.
Risk register: table of top 3 risks with mitigations.
Submission
Include memo text and embedded/exported diagram in your PDF.
Link to any /docs/ materials in your GitHub repo.
Evaluation guide
Clarity of problem framing and realism of scope
Design coherence & traceability from goals architecture
Evidence quality & integration
Communication quality (structure, clarity, citations)

Help me explore answers to the prompt

Provided Ex:
Module 1 Assignment Companion
Module 1 Project Pitch Companion
Here is a Companion to JUST the Project Pitch Component of Module 1's Assignment (All others are deferred).

NOTE: I did use an LLM to explore answers to the prompts, I hope you will too.

I provide an illustration based on the prompts:

The Prompt Given:
A. Project Pitch (100 points)

Deliverables

2–3 page memo (≈800–1,000 words): problem, stakeholders, scope, success metrics; define a minimal viable artifact shippable within 2 weeks.
System sketch: labeled diagram (block/sequence) showing front‑end back‑end data OR AI touchpoints.
Evidence base: at least 3 authoritative sources (industry reports, academic articles, standards). Use a consistent citation style.
Risk register: table of top 3 risks with mitigations.
Submission

Include memo text and embedded/exported diagram in your PDF.
Link to any /docs/ materials in your GitHub repo.
Evaluation guide

Clarity of problem framing and realism of scope
Design coherence & traceability from goals architecture
Evidence quality & integration
Communication quality (structure, clarity, citations)
My Initial Design Thoughts for Exploration
I want a web application the helps in the travel math involved in estimating the cost of trips, how long to drive, whether I should drive or fly and ways to share travel tips based on locations or travel segments. Some of this can be similar to the travelmath website, but we can have user-supplied tips on either journey segments, places to say, or even gas prices. I want to explore this design problem iteratively (Marshmallow Challenge Links to an external site., Implementing Best Practices for Web Design with Iterative Methodologies | Entrepreneur Links to an external site.).

My First Iteration Considering an Iterative Design Approach
Below would be a reasonable (and actually somewhat advanced) first iteration on defining a solution approach.

Project Pitch: TravelMath-Lite
Problem
Intercity travelers routinely face the decision of whether to drive or fly, yet essential inputs are dispersed across multiple sources and expressed with differing assumptions. Total trip cost and time depend on multiple factors: fuel prices and vehicle operating costs, tolls and parking, overnight lodging for longer drives, airline ancillaries (baggage, seat fees), and ground transfers at origin and destination. Existing calculators provide partial support but seldom make assumptions explicit, and they rarely incorporate contextual knowledge from traveler experience.

TravelMath-Lite addresses this gap by combining (i) a transparent cost/time calculator with editable defaults drawn from authoritative sources and (ii) a mechanism for users to share tips tied to route segments and waypoints. The problem is both analytical (coherent modeling of cost and time) and social (collecting, curating, and presenting experiential knowledge in a usable form).

Stakeholders
Primary travelers: individuals and families seeking a structured drive-versus-fly comparison.
Budget-sensitive users: travelers who require clear, editable assumptions for cost transparency.
Community contributors: travelers who submit route/segment tips (e.g., fuel stops, lodging, congestion).
Moderators: reviewers who ensure tips are appropriate, non-duplicative, and constructive.
Course participants: learners applying iterative web-system design principles to a concrete artifact.
Scope
In-scope
Drive vs. Fly calculator with editable parameters: fuel price (default: national average), per-mile vehicle cost (default: standard mileage rate), value of time (default: intercity personal travel guidance), and ancillary costs (tolls, parking, lodging, baggage/seat fees). Outputs include total cost, total time, and a recommendation.
Evidence drawer that discloses active assumptions with citations and retrieval dates.
Tips module (CRUD) for segments and waypoints with categories (fuel, lodging, traffic/parking), voting, and flagging.
Moderation workflow with lightweight AI assistance for summarization and duplicate detection; human approval remains authoritative.
Project documentation in /docs/ describing formulas, assumptions, and iteration notes.
Out-of-scope (for the minimal viable artifact)
Automated airfare scraping or fare prediction.
Full turn-by-turn maps and navigation.
User accounts, profiles, or advanced gamification.
Success Metrics
Decision clarity: a large proportion of sessions complete a comparison and receive a recommendation.
Accuracy proxy: cost/time estimates remain within approximately 10–15% of validated trip logs.
Transparency: users can locate and modify assumptions with minimal friction.
Community engagement: a measurable share of sessions include viewing, submitting, or upvoting tips.
Minimal Viable Artifact (MVA)
The MVA comprises three deliverables: (1) a working drive-versus-fly calculator with editable defaults and ancillary inputs, (2) a tips module with moderation and AI-assisted summarization/deduplication, and (3) an evidence drawer that shows active assumptions with citations. This configuration is intentionally modest while enabling meaningful decisions and future extensibility.

Iterative Design Approach
Development proceeds in short cycles through a repeatable loop: Planning and requirements → Analysis and design → Implementation → Testing → Evaluation and review, then back to Planning. The initial cycle emphasizes the calculator and evidence drawer to establish a usable baseline; the subsequent cycle introduces tips and moderation. Each cycle concludes with an explicit review gate against success metrics, which governs scope for the next pass. This approach keeps the artifact bounded, transparent, and adaptable.

System Sketch
System Sketch.png

Evidence Base
Internal Revenue Service (2025). Standard mileage rates. https://www.irs.gov/
U.S. Energy Information Administration (2025). Gasoline and diesel fuel update. https://www.eia.gov/petroleum/gasdiesel/
U.S. Department of Transportation (2024). Benefit-Cost Analysis guidance: Value of travel time. https://www.transportation.gov/
AAA (2024). Your Driving Costs. https://newsroom.aaa.com/
Bureau of Transportation Statistics (2025). Average domestic itinerary fares. https://www.bts.gov/
Risk Register
Risk Impact Likelihood Mitigation
Volatile inputs (fuel prices, ancillaries, atypical delays) High Medium Display dates/sources; permit overrides; present sensitivity bands; refresh defaults on a regular cadence.
Low-quality or unsafe tips (spam, misleading advice) Medium Medium Pre-screen with AI; human moderation; rate limits; flagging and rollback; upvote-based surfacing.
Scope creep relative to MVA Medium High Use review gates to confirm or defer features; track enhancements in a public roadmap; keep core flows stable.
Submission Notes
Supporting docs in repo.

# Prompt 2

I have an idea for an app:

Sports enjoyers have an issue getting engaged with Major League Baseball due to the stretches of low action. I have an idea for an app where the app uses schedules (start times, schedule conflicts, etc), current matchups (batter vs pitcher), game situations (bottom of the ninth, tied game, etc), importantness of the game (playoff run, rivalry games, etc.). I believe player stats (to determine the likeliness of action), team stats (to determine the likeliness of entertainment), etc, could be used to help make recommendations, as well as favorite teams, preferred watch time, fan level (how into baseball the user is), etc.

Help write my project pitch based off of this, and create a name for the project.

Provided ex from instructor:
Module 1 Assignment Companion 
Module 1 Project Pitch Companion 
Here is a Companion to JUST the Project Pitch Component of Module 1's Assignment (All others are deferred). 

NOTE: I did use an LLM to explore answers to the prompts, I hope you will too. 

I provide an illustration based on the prompts: 

The Prompt Given: 
A. Project Pitch (100 points) 

Deliverables 

2–3 page memo (≈800–1,000 words): problem, stakeholders, scope, success metrics; define a minimal viable artifact shippable within 2 weeks. 
System sketch: labeled diagram (block/sequence) showing front‑end back‑end data OR AI touchpoints. 
Evidence base: at least 3 authoritative sources (industry reports, academic articles, standards). Use a consistent citation style. 
Risk register: table of top 3 risks with mitigations. 
Submission 

Include memo text and embedded/exported diagram in your PDF. 
Link to any /docs/ materials in your GitHub repo. 
Evaluation guide 

Clarity of problem framing and realism of scope 
Design coherence & traceability from goals architecture 
Evidence quality & integration 
Communication quality (structure, clarity, citations) 
My Initial Design Thoughts for Exploration 
I want a web application the helps in the travel math involved in estimating the cost of trips, how long to drive, whether I should drive or fly and ways to share travel tips based on locations or travel segments. Some of this can be similar to the travelmath website, but we can have user-supplied tips on either journey segments, places to say, or even gas prices. I want to explore this design problem iteratively (Marshmallow Challenge Links to an external site., Implementing Best Practices for Web Design with Iterative Methodologies | Entrepreneur Links to an external site.). 

My First Iteration Considering an Iterative Design Approach 
Below would be a reasonable (and actually somewhat advanced) first iteration on defining a solution approach. 

Project Pitch: TravelMath-Lite 
Problem 
Intercity travelers routinely face the decision of whether to drive or fly, yet essential inputs are dispersed across multiple sources and expressed with differing assumptions. Total trip cost and time depend on multiple factors: fuel prices and vehicle operating costs, tolls and parking, overnight lodging for longer drives, airline ancillaries (baggage, seat fees), and ground transfers at origin and destination. Existing calculators provide partial support but seldom make assumptions explicit, and they rarely incorporate contextual knowledge from traveler experience. 

TravelMath-Lite addresses this gap by combining (i) a transparent cost/time calculator with editable defaults drawn from authoritative sources and (ii) a mechanism for users to share tips tied to route segments and waypoints. The problem is both analytical (coherent modeling of cost and time) and social (collecting, curating, and presenting experiential knowledge in a usable form). 

Stakeholders 
Primary travelers: individuals and families seeking a structured drive-versus-fly comparison. 
Budget-sensitive users: travelers who require clear, editable assumptions for cost transparency. 
Community contributors: travelers who submit route/segment tips (e.g., fuel stops, lodging, congestion). 
Moderators: reviewers who ensure tips are appropriate, non-duplicative, and constructive. 
Course participants: learners applying iterative web-system design principles to a concrete artifact. 
Scope 
In-scope 
Drive vs. Fly calculator with editable parameters: fuel price (default: national average), per-mile vehicle cost (default: standard mileage rate), value of time (default: intercity personal travel guidance), and ancillary costs (tolls, parking, lodging, baggage/seat fees). Outputs include total cost, total time, and a recommendation. 
Evidence drawer that discloses active assumptions with citations and retrieval dates. 
Tips module (CRUD) for segments and waypoints with categories (fuel, lodging, traffic/parking), voting, and flagging. 
Moderation workflow with lightweight AI assistance for summarization and duplicate detection; human approval remains authoritative. 
Project documentation in /docs/ describing formulas, assumptions, and iteration notes. 
Out-of-scope (for the minimal viable artifact) 
Automated airfare scraping or fare prediction. 
Full turn-by-turn maps and navigation. 
User accounts, profiles, or advanced gamification. 
Success Metrics 
Decision clarity: a large proportion of sessions complete a comparison and receive a recommendation. 
Accuracy proxy: cost/time estimates remain within approximately 10–15% of validated trip logs. 
Transparency: users can locate and modify assumptions with minimal friction. 
Community engagement: a measurable share of sessions include viewing, submitting, or upvoting tips. 
Minimal Viable Artifact (MVA) 
The MVA comprises three deliverables: (1) a working drive-versus-fly calculator with editable defaults and ancillary inputs, (2) a tips module with moderation and AI-assisted summarization/deduplication, and (3) an evidence drawer that shows active assumptions with citations. This configuration is intentionally modest while enabling meaningful decisions and future extensibility. 

Iterative Design Approach 
Development proceeds in short cycles through a repeatable loop: Planning and requirements → Analysis and design → Implementation → Testing → Evaluation and review, then back to Planning. The initial cycle emphasizes the calculator and evidence drawer to establish a usable baseline; the subsequent cycle introduces tips and moderation. Each cycle concludes with an explicit review gate against success metrics, which governs scope for the next pass. This approach keeps the artifact bounded, transparent, and adaptable. 

System Sketch 
System Sketch.png 

Evidence Base 
Internal Revenue Service (2025). Standard mileage rates. https://www.irs.gov/ 
U.S. Energy Information Administration (2025). Gasoline and diesel fuel update. https://www.eia.gov/petroleum/gasdiesel/ 
U.S. Department of Transportation (2024). Benefit-Cost Analysis guidance: Value of travel time. https://www.transportation.gov/ 
AAA (2024). Your Driving Costs. https://newsroom.aaa.com/ 
Bureau of Transportation Statistics (2025). Average domestic itinerary fares. https://www.bts.gov/ 
Risk Register 
Risk Impact Likelihood Mitigation 
Volatile inputs (fuel prices, ancillaries, atypical delays) High Medium Display dates/sources; permit overrides; present sensitivity bands; refresh defaults on a regular cadence. 
Low-quality or unsafe tips (spam, misleading advice) Medium Medium Pre-screen with AI; human moderation; rate limits; flagging and rollback; upvote-based surfacing. 
Scope creep relative to MVA Medium High Use review gates to confirm or defer features; track enhancements in a public roadmap; keep core flows stable. 
Submission Notes 
Supporting docs in repo.

# Prompt 3

Does this project pitch:
Project Pitch: PinchHitter-Lite
Problem
Major League Baseball (MLB) has a low engagement problem among casual sports fans. Unlike fast-paced sports with continuous action, baseball often has stretches of slow play, making it difficult for new or time-constrained fans to stay engaged. Many fans only tune in during high-leverage moments, but discovering these moments in real-time is a significant challenge. Fans must manually check multiple games, often missing the most exciting plays. A tool is needed to identify these high-leverage moments and notify fans, transforming the passive act of checking scores into a dynamic, personalized viewing experience.
PinchHitter-lite solves this by acting as a personalized baseball curator. It analyzes real-time game data to identify high-leverage situations, such as a key batter-pitcher matchups, a late-inning rally, or a tie game, and provides a notification. This system addresses both the analytical problem of identifying game importance and the user experience problem of delivering timely, digestible information to fans.
Stakeholders
Casual Sports Fans: Individuals who enjoy baseball but lack the time or dedication to watch entire games. They want to be alerted to exciting moments.
Time-Constrained Viewers: Parents, professionals, and students who can only spare a few minutes to tune in.
MLB & Broadcasters: Organizations that benefit from increased fan engagement and viewership, as a more dynamic viewing experience can lead to higher ratings and interest.
Course Participants: Learners applying iterative web-system design principles to a concrete artifact.
Scope
In-Scope
Recommendation calculator that scores each game's "excitement level" based on a few key factors, such as inning (higher score for late innings), score differential (higher score for close games), and base runners (higher score for bases loaded).
Evidence drawer that discloses active assumptions with citations and retrieval dates
User preference setting where a user can input their favorite team which will then highlight their team's game in the list.
Basic user interface that displays a list of all active MLB games.
Project documentation in /docs/ describing the algorithm's logic and data sources.
Out-of-scope (for the minimal viable artifact)
Automated real-time MLB data scraping.
Integration with video streams or live game feeds.
User accounts, profiles, and push notifications.
Success Metrics
Discovery Efficiency: Users can find a game with a high-leverage situation within a few seconds of opening the application.
Recommendation Relevance: The app's top-ranked games consistently align with what a human baseball expert would consider "exciting" or "high-leverage" situations.
Clarity of Preferences: A large proportion of users successfully input a favorite team, and the highlighting feature works as expected.
User Engagement: A measurable share of sessions includes a user clicking on a game to view more details, indicating that the excitement ranking is a useful metric.
Minimal Viable Artifact (MVA)
The MVA for PinchHitter-Lite will consist of three core deliverables: 
a live-updating web scoreboard that ranks active MLB games
a basic preference setting where a user can specify a favorite team to highlight
an evidence drawer that details the logic and citations for the recommendation calculator
This configuration is intentionally modest while addressing the core problem of helping casual fans find compelling baseball games.
Iterative Design Approach
Development will proceed in short cycles through a repeatable loop: Planning and Requirements → Analysis and Design → Implementation → Testing → Evaluation and Review, then back to Planning. The initial cycle will emphasize building the core recommendation calculator and evidence drawer to establish a usable baseline; the subsequent cycle will introduce the favorite team highlighting feature. Each cycle concludes with an explicit review gate against success metrics, which will govern the scope for the next pass. This approach keeps the artifact bounded, transparent, and adaptable.

Align well with the project prompt and provided example by the instructor:
Module 1 Assignment Companion
Module 1 Project Pitch Companion
Here is a Companion to JUST the Project Pitch Component of Module 1's Assignment (All others are deferred).
NOTE: I did use an LLM to explore answers to the prompts, I hope you will too.
I provide an illustration based on the prompts:
The Prompt Given:
A. Project Pitch (100 points)
Deliverables
2–3 page memo (≈800–1,000 words): problem, stakeholders, scope, success metrics; define a minimal viable artifact shippable within 2 weeks.
System sketch: labeled diagram (block/sequence) showing front‑end back‑end data OR AI touchpoints.
Evidence base: at least 3 authoritative sources (industry reports, academic articles, standards). Use a consistent citation style.
Risk register: table of top 3 risks with mitigations.
Submission
Include memo text and embedded/exported diagram in your PDF.
Link to any /docs/ materials in your GitHub repo.
Evaluation guide
Clarity of problem framing and realism of scope
Design coherence & traceability from goals architecture
Evidence quality & integration
Communication quality (structure, clarity, citations)
My Initial Design Thoughts for Exploration
I want a web application the helps in the travel math involved in estimating the cost of trips, how long to drive, whether I should drive or fly and ways to share travel tips based on locations or travel segments. Some of this can be similar to the travelmath website, but we can have user-supplied tips on either journey segments, places to say, or even gas prices. I want to explore this design problem iteratively (Marshmallow ChallengeLinks to an external site.
, Implementing Best Practices for Web Design with Iterative Methodologies | EntrepreneurLinks to an external site.
).
My First Iteration Considering an Iterative Design Approach 
Below would be a reasonable (and actually somewhat advanced) first iteration on defining a solution approach.

Project Pitch: TravelMath-Lite
Problem
Intercity travelers routinely face the decision of whether to drive or fly, yet essential inputs are dispersed across multiple sources and expressed with differing assumptions. Total trip cost and time depend on multiple factors: fuel prices and vehicle operating costs, tolls and parking, overnight lodging for longer drives, airline ancillaries (baggage, seat fees), and ground transfers at origin and destination. Existing calculators provide partial support but seldom make assumptions explicit, and they rarely incorporate contextual knowledge from traveler experience.
TravelMath-Lite addresses this gap by combining (i) a transparent cost/time calculator with editable defaults drawn from authoritative sources and (ii) a mechanism for users to share tips tied to route segments and waypoints. The problem is both analytical (coherent modeling of cost and time) and social (collecting, curating, and presenting experiential knowledge in a usable form).
Stakeholders
Primary travelers: individuals and families seeking a structured drive-versus-fly comparison.
Budget-sensitive users: travelers who require clear, editable assumptions for cost transparency.
Community contributors: travelers who submit route/segment tips (e.g., fuel stops, lodging, congestion).
Moderators: reviewers who ensure tips are appropriate, non-duplicative, and constructive.
Course participants: learners applying iterative web-system design principles to a concrete artifact.
Scope
In-scope
Drive vs. Fly calculator with editable parameters: fuel price (default: national average), per-mile vehicle cost (default: standard mileage rate), value of time (default: intercity personal travel guidance), and ancillary costs (tolls, parking, lodging, baggage/seat fees). Outputs include total cost, total time, and a recommendation.
Evidence drawer that discloses active assumptions with citations and retrieval dates.
Tips module (CRUD) for segments and waypoints with categories (fuel, lodging, traffic/parking), voting, and flagging.
Moderation workflow with lightweight AI assistance for summarization and duplicate detection; human approval remains authoritative.
Project documentation in /docs/ describing formulas, assumptions, and iteration notes.
Out-of-scope (for the minimal viable artifact)
Automated airfare scraping or fare prediction.
Full turn-by-turn maps and navigation.
User accounts, profiles, or advanced gamification.
Success Metrics
Decision clarity: a large proportion of sessions complete a comparison and receive a recommendation.
Accuracy proxy: cost/time estimates remain within approximately 10–15% of validated trip logs.
Transparency: users can locate and modify assumptions with minimal friction.
Community engagement: a measurable share of sessions include viewing, submitting, or upvoting tips.
Minimal Viable Artifact (MVA)
The MVA comprises three deliverables: (1) a working drive-versus-fly calculator with editable defaults and ancillary inputs, (2) a tips module with moderation and AI-assisted summarization/deduplication, and (3) an evidence drawer that shows active assumptions with citations. This configuration is intentionally modest while enabling meaningful decisions and future extensibility.
Iterative Design Approach
Development proceeds in short cycles through a repeatable loop: Planning and requirements → Analysis and design → Implementation → Testing → Evaluation and review, then back to Planning. The initial cycle emphasizes the calculator and evidence drawer to establish a usable baseline; the subsequent cycle introduces tips and moderation. Each cycle concludes with an explicit review gate against success metrics, which governs scope for the next pass. This approach keeps the artifact bounded, transparent, and adaptable.