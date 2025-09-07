# Prompt 1, Gemini

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

# Output 1, Gemini

Here's a breakdown of the provided project pitch companion, designed to help you explore and understand the different components of the assignment.

Understanding the Prompt's Core Components

The assignment asks for four key deliverables to pitch a project: a memo, a system sketch, an evidence base, and a risk register. The goal is to present a clear, coherent, and realistic plan for a software project that's small enough to have a Minimal Viable Artifact (MVA) shipped in just two weeks.

Breaking Down the Provided Example

The example, TravelMath-Lite, is a great model for how to approach the prompt. It doesn't just describe an idea; it structures it according to the assignment's requirements, making it easy to see how each part connects.

Project Pitch Memo

The memo is the central narrative of your pitch. The TravelMath-Lite example effectively frames the problem, identifies stakeholders, sets a clear scope, and defines success metrics.

Problem: The example clearly articulates a specific pain point: travelers struggle to compare driving versus flying because the necessary information is scattered and lacks transparency. This problem is specific and solvable, which is key for a successful pitch.

Stakeholders: It identifies different user groups, from the primary traveler to moderators and even the course participants themselves. This shows an understanding of the product's ecosystem and who it serves.

Scope: The scope is meticulously defined with "in-scope" and "out-of-scope" items. This is crucial for managing expectations and showing that the project is realistic. Notice how the out-of-scope items (e.g., automated airfare scraping) are complex features that would be difficult to deliver in two weeks, demonstrating a practical understanding of project constraints.

Success Metrics: These aren't just vague goals; they're measurable. The metrics, such as "Decision clarity" and "Accuracy proxy," are directly tied to the problem statement. They provide a way to objectively evaluate whether the MVA is successful.

Minimal Viable Artifact (MVA): The MVA is the most critical part of this section. The example outlines a truly minimal, yet functional, product. It focuses on the core features (the calculator, tips module, and evidence drawer) that solve the primary problem, ignoring all the "nice-to-have" features. The name "TravelMath-Lite" itself reinforces this concept of a simplified, focused version.

System Sketch

The system sketch visually represents how the different parts of the application will communicate. The example's sketch shows a simple, coherent architecture.

Clarity: The diagram is labeled and uses standard components like a front-end, back-end, and database. It also correctly includes touchpoints for external services (APIs for fuel data) and AI assistance for moderation. This makes the design easy to understand and shows how all the pieces fit together.

Traceability: This sketch directly reflects the features mentioned in the memo (e.g., the AI assistance for tips, the use of external data sources). This is what the evaluation guide calls "traceability".

Evidence Base

The evidence base lends credibility to your project by rooting it in authoritative sources. The example uses official sources like the IRS, U.S. Department of Transportation, and the U.S. Energy Information Administration.

Authority: These aren't just random blogs or articles; they are government agencies and reputable organizations. This shows that the project's assumptions (like the standard mileage rate) are based on reliable, verifiable data.

Relevance: Each source is directly relevant to a specific part of the problem. For instance, the IRS is used for vehicle costs, while the EIA is for fuel prices.

Risk Register

The risk register demonstrates foresight and an understanding of potential project pitfalls. It's not about being perfect; it's about being prepared. The example identifies three key risks and provides practical mitigations.

Realism: The identified risks (volatile inputs, low-quality tips, scope creep) are highly realistic for this type of project. They're not generic; they're specific to the TravelMath-Lite concept.

Mitigation: The suggested mitigations are actionable and thoughtful. For example, instead of just saying "we'll handle bad tips," the example provides a multi-layered approach: AI pre-screening, human moderation, and flagging. This shows a well-considered plan.

This detailed analysis of the provided example should help you explore your own project ideas by using the same structured approach. Think about how you can frame your problem, identify your stakeholders, set a realistic scope, and anticipate risks for your chosen topic. What's a project you're passionate about that you could define and scope in a similar fashion?

Here are some possible problems you could use to answer the prompt, categorized by domain to help you find one that resonates with your interests. For each, I'll provide a brief problem statement and some ideas for in-scope and out-of-scope features for an MVA.

1. Productivity & Personal Finance

Problem Idea: "BudgetBuddy-Lite"

Problem Statement: Many individuals and small households struggle to track their daily spending and categorize expenses effectively, leading to overspending and a lack of financial clarity. Existing solutions are often too complex, requiring manual input or linking to bank accounts, which raises privacy concerns for some users.

MVA Scope: A simple web or mobile app that allows users to manually input expenses with a few taps. The app would automatically categorize expenses based on keywords (e.g., "Starbucks" = "Coffee," "Uber" = "Transportation") using a pre-defined list. It would provide a basic daily and weekly summary of spending by category.

Out of Scope (for MVA): Bank account linking (Plaid API, etc.), income tracking, budget setting, bill reminders, machine learning models for advanced categorization.

Stakeholders: Individuals, families, financial literacy educators.

Evidence Base: Financial literacy reports, data on consumer debt, articles on personal finance best practices.

2. Health & Wellness

Problem Idea: "HydrationTracker-Lite"

Problem Statement: Many people fail to drink enough water throughout the day, leading to dehydration and related health issues. Existing water tracking apps are often cluttered with unnecessary features, require constant manual updates, or are difficult to integrate into a busy daily routine.

MVA Scope: A simple web page or mobile app that allows a user to log their water intake with a single click. The app would track intake against a default daily goal (e.g., 8 glasses) and display a progress bar. It could have a simple "reset" button for the start of a new day.

Out of Scope (for MVA): Personalized hydration goals based on weight or activity level, reminders/push notifications, social sharing, integration with fitness trackers (Apple Watch, Fitbit), historical data analysis.

Stakeholders: Individuals, health-conscious users, fitness coaches.

Evidence Base: Health reports from CDC or WHO on hydration, academic articles on the benefits of adequate water intake, data on daily water consumption habits.

3. Education & Learning

Problem Idea: "StudySessionScheduler"

Problem Statement: Students and lifelong learners often struggle to structure their study time effectively. They may not know how to break down large tasks into manageable chunks or allocate time efficiently, leading to procrastination and burnout.

MVA Scope: A web application that helps users plan a study session. The user would input a topic and the total time they have available. The app would then apply the Pomodoro Technique (or a similar method) and output a simple schedule: a series of focused study periods (e.g., 25 minutes) and short breaks (e.g., 5 minutes) until the total time is used.

Out of Scope (for MVA): User accounts, long-term multi-day planning, calendar integration, advanced scheduling algorithms, a built-in timer.

Stakeholders: Students, educators, corporate trainers.

Evidence Base: Academic studies on learning and memory (e.g., spaced repetition), educational psychology articles on effective study techniques (e.g., Pomodoro), reports on student procrastination.

4. Community & Social

Problem Idea: "LocalExchange-Lite"

Problem Statement: People living in apartment buildings or small communities often have unused items they'd be willing to share or lend but have no easy way to connect with their neighbors to do so. Existing platforms like Craigslist or Facebook Marketplace are too broad and lack the specific, trusted context of a small community.

MVA Scope: A lightweight web bulletin board for a single, pre-defined location (e.g., "123 Main Street Apartments"). Users could post a single, simple listing for an item they want to lend or give away (e.g., "Lending: a power drill" or "Giving away: a large moving box"). The listing would only show a title, a short description, and an email address for contact. No images.

Out of Scope (for MVA): User authentication/accounts, image uploads, location-based searching, messaging features, rating systems.

Stakeholders: Apartment dwellers, property managers, community organizers.

Evidence Base: Reports on the sharing economy, articles on community building, data on waste reduction and resource sharing.

5. Hobbies & Recreation

Problem Idea: "RecipeBuilder-Lite"

Problem Statement: Home cooks frequently find themselves with a few leftover ingredients and no inspiration for what to make. Searching online is often cumbersome and returns complex recipes that require additional ingredients they don't have.

MVA Scope: A simple web tool where a user can manually input up to three ingredients they have on hand. The system would then display a pre-curated list of simple, single-serving recipes that only use those ingredients (plus common pantry staples like salt and pepper).

Out of Scope (for MVA): User accounts for saving recipes, recipe ratings, smart ingredient recognition (e.g., from a photo), advanced search filters (e.g., dietary restrictions, cooking time).

Stakeholders: Home cooks, individuals looking to reduce food waste, food bloggers.

Evidence Base: Statistics on food waste, surveys on home cooking habits, culinary standards for ingredient combinations.

When you select a problem, remember to follow the structure of the provided example. Frame it clearly, define a realistic scope, and choose authoritative sources for your evidence base. Good luck!

# Prompt 2, Gemini

I have an idea for an app: 

Sports enjoyers have an issue getting engaged with Major League Baseball due to the stretches of low action. I have an idea for an app where the app uses schedules (start times, schedule conflicts, etc), current matchups (batter vs pitcher), game situations (bottom of the ninth, tied game, etc), importantness of the game (playoff run, rivalry games, etc.). I believe player stats (to determine the likeliness of action), team stats (to determine the likeliness of entertainment), etc, could be used to help make recommendations, as well as favorite teams, preferred watch time, fan level (how into baseball the user is), etc. 

Give me tips to write my project based off of this, and create a name for the project. 

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

=====================================================================================================================================  

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

# Output 2, Gemini

Let's get this project scoped out! A great name for your app is InningSight. It's a play on "insight" and "inning," which directly relates to baseball. It suggests the app provides a deeper understanding of the game's key moments.

Here are some tips for writing your project pitch, following the structure provided by your instructor.

Project Pitch: InningSight

Problem

Many potential fans find it difficult to engage with Major League Baseball (MLB) due to the sport's slower pace and frequent periods of inactivity. This can make watching a full game a significant time commitment without the guarantee of high-stakes, exciting moments. InningSight addresses this by providing users with a personalized "highlight reel" of live game opportunities. Instead of passively watching a full nine-inning game, users can get real-time notifications about moments of high action, such as a tied game in the late innings, a high-stakes at-bat, or a potential game-winning play. The app uses a unique algorithm to predict these moments based on a range of data points. This helps users stay connected to the sport in a way that fits their schedule and level of engagement.

Stakeholders

Casual Baseball Fans: Individuals who enjoy the sport but don't have time to watch entire games. They want to be alerted to the most exciting plays.

New Baseball Fans: People new to the sport who need help understanding key moments and want an accessible way to get into the game.

Fantasy Sports Players: Users who want to track specific players or matchups in real-time to monitor their fantasy teams.

Media Partners (Potential): Broadcasters and streaming services who could use the app's data to drive live viewership during peak moments.

Course Participants: Learners applying iterative web-system design principles to a concrete artifact.

Scope

In-scope

Real-time Game Alerts: The core functionality will be a notification system that sends alerts to users for pre-defined "action-rich" moments. This includes but isn't limited to late-inning clutch situations, bases-loaded scenarios, and potential no-hitters or cycles.

Recommendation Algorithm: The app will use a basic version of the recommendation engine. It will utilize publicly available data such as live game scores, player and team stats (e.g., batting average, ERA), and game context (e.g., playoff implications, rivalry games).

User Preferences: Users will be able to set basic preferences, such as their favorite team, a list of players they want to follow, and their preferred notification times.

Minimalist User Interface (UI): The app will have a clean, easy-to-use interface that displays current games and provides a clear feed of alerts.

Risk Register and Evidence Base: The project will include a detailed risk register with mitigation strategies and an evidence base with at least three authoritative sources, such as official MLB data, academic research on sports viewership, and industry reports.

Out-of-scope (for the minimal viable artifact)

Personalized Video Highlights: The MVA will not include integrated video streaming or highlight clips.

Advanced Analytics: The app will not feature in-depth, predictive analytics like a batter-vs-pitcher win probability model. The focus is on using existing data to identify high-action moments.

Social Features: The MVA will not include user accounts, profiles, or social sharing capabilities.

Monetization: There will be no ads, premium subscriptions, or other monetization features in the initial version.

Success Metrics

Engagement Rate: A high percentage of users who receive a notification open the app within 5 minutes.

Session Duration: Users spend an average of at least 5 minutes per session once they're in the app.

User Retention: A significant portion of users return to the app at least 3-4 times per week during the baseball season.

Notification Accuracy: The algorithm correctly identifies and alerts users to a high percentage of significant game-changing moments.

Minimal Viable Artifact (MVA)

The MVA will consist of a web-based application that allows users to:

Select a favorite MLB team.

Receive push notifications for high-leverage moments in their favorite team's games.

View a simple dashboard showing live game scores and the reason for the alert.
This version is a focused solution that validates the core idea: can a recommendation engine effectively drive user engagement with baseball's most exciting moments?

System Sketch

Evidence Base

MLB Advanced Media (MLBAM): This is the official digital arm of Major League Baseball and a primary source for real-time game data, stats, and schedules.

Academic Research: Studies from sports economics and media journals that analyze fan engagement, viewership patterns, and the impact of game pace on audience retention.

Industry Reports: Market research reports from firms like Nielsen or Statista that detail trends in sports viewership and the growth of mobile-first content consumption.

Risk Register

Risk	Impact	Likelihood	Mitigation
Data Latency/Accuracy	High	Medium	Use official, high-quality data sources (e.g., MLBAM) and build in error handling to manage occasional data delays or inaccuracies.
Notification Fatigue	Medium	High	Allow users to customize notification frequency and types. Prioritize only truly high-leverage situations to avoid overwhelming users.
Poor Algorithm Performance	High	Medium	Start with a simple, rule-based algorithm and iterate based on user feedback. The MVA should only alert for unambiguous "clutch" moments, not speculative ones.

# Prompt 3, Gemini

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

# Output 3, Gemini

Yes, the PinchHitter-Lite project pitch aligns well with the provided prompt and example. It effectively mimics the structure, tone, and content of the TravelMath-Lite example, demonstrating a solid understanding of the iterative design process and the required components of a project pitch.

Alignment Analysis

The PinchHitter-Lite pitch successfully mirrors the key elements and a iterative design approach outlined in the instructor's example:

Problem Statement: Both pitches clearly identify a specific problem faced by a target audience. PinchHitter-Lite focuses on the challenge of finding "high-leverage" moments for casual baseball fans, which is a niche but well-defined problem similar to TravelMath-Lite's focus on scattered travel cost data for intercity travelers. Both pitches propose a solution that is an accessible tool that addresses both an analytical challenge and a user experience problem.

Stakeholders: Both pitches identify a range of relevant stakeholders. PinchHitter-Lite names casual fans, time-constrained viewers, and broader organizations like MLB and broadcasters. This is analogous to TravelMath-Lite's identification of primary travelers, budget-sensitive users, and community contributors. Both lists correctly include the "Course Participants" as a stakeholder.

Scope: The pitch provides clear and specific lists for both "In-Scope" and "Out-of-Scope" features for the Minimal Viable Artifact (MVA). This is a critical component of the prompt. PinchHitter-Lite's scope is realistic and appropriately limited, mirroring how TravelMath-Lite avoids complex features like automated airfare scraping and full navigation, focusing instead on core functionality.

Success Metrics: The success metrics for PinchHitter-Lite are clear, measurable, and directly tied to the project's goals. Metrics like Discovery Efficiency and Recommendation Relevance are analogous to TravelMath-Lite's Decision Clarity and Accuracy Proxy. This demonstrates an understanding of how to define success in a project context.

Minimal Viable Artifact (MVA): The MVA for PinchHitter-Lite is thoughtfully defined, outlining a modest but functional set of deliverables. It correctly prioritizes a core feature (the recommendation calculator) and supporting elements (preference settings and evidence drawer), which is an exact parallel to the TravelMath-Lite MVA.

Iterative Design Approach: Both pitches describe the same repeatable, cyclical development process. PinchHitter-Lite explicitly mentions building the core calculator first and then adding features in subsequent cycles, which is the exact same logic and structure as the TravelMath-Lite example. It emphasizes a bounded, transparent, and adaptable process, using the same terminology as the provided example.

Suggestions for Improvement

While the pitch is strong, a few minor refinements could enhance it further:

Clarity and Detail in Metrics: While the success metrics are good, adding a quantitative target would make them more robust. For example, instead of just saying "a measurable share of sessions includes a user clicking," you could propose a goal like "20% of sessions include a user clicking on a game." .

Evidence Base: The pitch doesn't explicitly mention the Evidence base or Risk register, which are required deliverables in the full assignment prompt. While these sections aren't in the provided "pitch companion," they should be included in the final submission. The pitch's "evidence drawer" hints at this, but a dedicated section in the full memo would be necessary to fully meet the prompt's requirements.