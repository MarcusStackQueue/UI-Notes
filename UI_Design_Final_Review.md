## Table of Contents

- [Pre-Midterm (40%)](#pre-midterm-40)
  - [Personas, Scenarios, Use Cases (Lec 5)](#personas-scenarios-use-cases-lec-5)
  - [Nielsen Heuristics](#nielsen-heuristics)
  - [Requirements & Task Analysis (Lec 6)](#requirements--task-analysis-lec-6)
  - [Information Architecture (IA) (Lec 8)](#information-architecture-ia-lec-8)
  - [Card Sorting (Lec 9)](#card-sorting-lec-9)
  - [GESTALT (Lec 10)](#gestalt-lec-10)
  - [Interaction Design (IxD) (Lec 10 + 11)](#interaction-design-ixd-lec-10--11)
- [Post-Midterm (60%)](#post-midterm-60)
  - [Dark Patterns (Lec 15)](#dark-patterns-lec-15)
  - [UX Laws & Cognition (Lec 16)](#ux-laws--cognition-lec-16)
  - [WCAG Principles and Guidelines (Lec 17 + 18)](#wcag-principles-and-guidelines-lec-17--18)
  - [HCI Research Methods (Lec 19)](#hci-research-methods-lec-19)
  - [HCI Data Analysis (Lec 20)](#hci-data-analysis-lec-20)
  - [Future of UX (Lec 21)](#future-of-ux-lec-21)
  - [Smallville Paper (Lec 22)](#smallville-paper-lec-22)

## Pre-Midterm (40%)

### Personas, Scenarios, Use Cases (Lec 5)

#### Persona

A *fictional* person grounded in evidence. Captures goals + constraints. Answers: **"Who are we designing for?"**

**A persona IS:**
- a cluster of research-backed patterns
- goals + jobs-to-be-done + constraints
- a tool to discuss tradeoffs
- updated when evidence changes

**A persona is NOT:**
- a demographic stereotype
- a "user we wish we had"
- one real person
- a poster you never use again

#### Persona Anatomy / Checklist
- Goals (what "success" means)
- Tasks / jobs-to-be-done
- Behaviours + habits
- Context of use (where/when)
- Constraints (time, money, access)
- Pain points + workarounds
- Tech proficiency (relevant)
- Quote (from evidence)

#### Types of Personas
- **Primary persona** - Main target(s). If you satisfy them, you're winning.
- **Secondary persona** - Important, but mostly satisfied by the primary design.
- **Customer persona** - Buyer / decider. May not be the daily user.
- **Served persona** - Affected by the system even if they don't use it directly.
- **Negative persona** - Explicitly **not** designing for (helps avoid scope creep). Negative personas are about **scope**, not disrespect. Write them neutrally.

#### Scenario
A short narrative. Context + trigger + journey. Can be typical / best / worst. Answers: **"What happens in real life?"**

A scenario is a short narrative that explains context + motivation + what unfolds.

#### Scenario Structure
- **Setting** — Where/when? What constraints exist?
- **Trigger** — What kicks this off?
- **Journey** — Key steps + decisions + breakdowns
- **Outcome** — What success looks like (and failure)

#### Biases to Watch For
- **Confirmation bias** — You notice only what supports your original idea.
- **Stereotyping** — You replace evidence with assumptions about a group.
- **Selection bias** — Your sample doesn't represent the user population.
- **Recency bias** — You overweight the latest feedback and ignore the rest.
- **Egocentric bias** — You assume users behave like you.
- **Over-reliance on quant** — You miss emotions, context, and workarounds.

#### Use Cases

Actor ↔ system interaction. Main + alternative flows. System responsibilities. Answers: **"What must the system do?"**

#### Use Case Template
- Title
- Primary actor
- Goal / success end condition
- Preconditions
- Trigger
- Main flow (numbered steps)
- Alternative / exception flows
- Postconditions

### Nielsen Heuristics

#### 1. Visibility of System Status

Designs should keep users informed about what is going on, through appropriate, timely feedback.
*Ex. Interactive mall maps have to show people where they currently are, to help them understand where to go next.*

#### 2. Match Between System and the Real World

The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon.
*Ex. Users can quickly understand which stovetop control maps to each heating element.*

#### 3. User Control and Freedom

Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action.
*Ex. Just like physical spaces, digital spaces need quick "emergency" exits too.*

#### 4. Consistency and Standards

Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform conventions.
*Ex. Check-in counters are usually located at the front of hotels, which meets expectations.*

#### 5. Error Prevention

Good error messages are important, but the best designs carefully prevent problems from occurring in the first place.
*Ex. Guard rails on curvy mountain roads prevent drivers from falling off cliffs.*

#### 6. Recognition Rather Than Recall

Minimize the user's memory load by making elements, actions, and options visible. Avoid making users remember information.
*Ex. People are likely to correctly answer "Is Lisbon the capital of Portugal?"*

#### 7. Flexibility and Efficiency of Use

Shortcuts — hidden from novice users — may speed up the interaction for the expert user.
*Ex. Regular routes are listed on maps, but locals with more knowledge of the area can take shortcuts.*

#### 8. Aesthetic and Minimalist Design

Interfaces should not contain information which is irrelevant. Every extra unit of information in an interface competes with the relevant units of information.
*Ex. A minimalist three-legged stool is still a place to sit.*

#### 9. Recognize, Diagnose, and Recover from Errors

Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution.
*Ex. Wrong-way signs on the road remind drivers that they are heading in the wrong direction.*

#### 10. Help and Documentation

It's best if the design doesn't need any additional explanation. However, it may be necessary to provide documentation to help users complete their tasks.
*Ex. Information kiosks at airports are easily recognizable and solve customers' problems in context and immediately.*

### Requirements & Task Analysis (Lec 6)

#### Task Analysis

**What task analysis captures:**
- Goal: what "done" means
- Steps: user actions + system support
- Decision points and branches
- Exceptions and workarounds
- Outputs: what is recorded/produced

**Why we do it:**
- Prevents "random UI drawing"
- Reveals hidden complexity (rules, quotas, missing info)
- Makes requirements easier to write
- Makes task flows clear and defendable

#### Tasks vs. Goals

**Goal (why)**
- Outcome the user wants to achieve
- *Volunteer module example:* volunteer gets scheduled for a shift
- *Receiving module example:* incoming donation is recorded correctly

**Tasks (what they do)**
- Concrete actions you can observe; have a clear start and end
- *Example:* check schedule → choose shift → confirm → show up
- Avoid treating "fill a form" as the goal (it's usually a task)

#### Task vs. Workflow vs. Job Analysis

**Task analysis**
- One user + one goal
- Tasks + subtasks
- Directly supports task flows

**Workflow analysis**
- Multiple roles + hand-offs
- Shared org goal

**Job analysis**
- Role responsibilities over time
- Training + staffing
- Not the focus of this course

#### Task Analysis Outputs
- **Stage 1:** gather tasks (observe / ask users / read existing docs)
- **Stage 2:** analyze tasks (sequence + hierarchy) and capture decisions/exceptions
- Common deliverables: Hierarchical Task Analysis (HTA), flowcharts, operational sequence diagrams
- In this course: **task flow diagrams** are the output you'll use.

#### Feature
- A possible system capability that supports tasks
- *Example:* a checklist to verify limits (one possible design)

#### Hierarchical Task Analysis (HTA)

**Template:**
- 0. Goal (e.g., "Organization pickup")
- 1. Subtask
- 2. Subtask
- 3. Subtask
- Plan: 1 → 2 → 3 (with decision points and exceptions)

Notes:
- Use HTA to find where decisions and exceptions occur
- Those become branches in your task flow

#### Task Flow Diagrams

**What a task flow should include:**
- Clear start and end
- User actions + system support steps
- At least 1 decision point (diamond) when relevant
- At least 1 exception branch (missing info, conflict)
- Use action verbs ("Record", "Verify", "Assign")

**What to avoid:**
- UI click-by-click ("click the blue button")
- Vague steps ("handle everything")
- No exceptions ("everything works perfectly")
- Flows that don't match your scenario

#### Task Flow - Exceptions

**Why exceptions matter:**
- The "sometimes..." parts of the real workflow drive key requirements.
- *Example requirement:* system must allow marking bill of lading as missing/unknown.
- *Example requirement:* system must support intake records even when some details are unknown.

#### What Is a Requirement

**Definition (plain language):**
- A requirement describes a needed capability, condition, or quality.
- It answers: "What must the system support?"
- Good requirements are **testable**: you can check if it is met.

**Not a requirement:**
- Not a UI sketch ("Add a big blue button...")
- Not a vague wish ("Make it easy...")
- Not an implementation detail ("Use React + Firebase...")

#### Types of Requirements

**Functional** - What the system must do
- *Example:* record an incoming pickup request
- *Example:* log organization sign-in/out

**Data / Info** - What info is captured, stored, shown
- *Example:* item description, count, weight/size
- *Example:* quota limits for the day

**Constraints & Quality** - Usability + context constraints
- *Example:* supports low-tech users
- *Example:* supports incomplete info

#### Good Requirements
- **Clear & unambiguous** - Only one interpretation
- **Testable / verifiable** - You can check if it is met (even by a TA)
- **Singular** - One requirement = one idea
- **Feasible** - Matches real constraints (time, people, context)
- **Traceable** - Links back to a scenario/task and forward to a design

#### Requirement Patterns

**Pattern A: "System must..."** — Use for must-have capabilities
- *Example:* System must allow staff to record item description, count, and weight/size during receiving.
- *Example:* System must support organization sign-in/out tracking.

**Pattern B: "System should..."** — Use for quality goals (still testable)
- *Example:* System should minimize required data entry during time-pressured tasks.
- *Avoid:* "should be easy" without defining "easy".

#### Deriving Requirements from Scenarios / Tasks
1. **Underline actions (verbs)** - What does the person do? What do they need the system to support?
2. **Identify information needs** - What must be recorded, looked up, checked, or printed?
3. **Capture rules + constraints** - Quotas, eligibility, supervision limits, warehouse realities, paper processes
4. **Add exceptions** - Missing info, conflicts, "sometimes...", errors, time pressure
5. **Write requirements (must/should)** and check testability

#### Requirements Gathering
- Identify stakeholders (users, admins, partners, developers, etc.)
- Collect info (interviews, observation, surveys, existing docs)
- Synthesize themes + pain points
- Write requirements (what the system must/should do)
- Prioritize (importance vs. feasibility)

#### Prioritizing Requirements — MoSCoW
- **Must-have** - without it, the core task fails
- **Should-have** - important, but workaround exists
- **Could-have** - nice-to-have; polish or future
- **Won't-have (for now)** - explicitly out of scope

#### Acceptance Criteria
- Short, concrete checks that show a requirement is met
- Often written as "**Given / When / Then**"
- Useful even before you build anything

#### Traceability

Traceability means you can answer: **"Why does this requirement exist?"**

Simple mapping you can include in your write-up:
- Scenario S2 → Task T1 (task flow) → Requirement R3
- Scenario S3 (edge) → Exception branch → Requirement R7

**Benefits:**
- Makes grading easier (TAs can follow your reasoning)
- Prevents random "features" with no user need
- Makes your later wireframes defensible

### Information Architecture (IA) (Lec 8)

#### Definition

**Information architecture (IA)** is a design discipline focused on making information **findable** and **understandable**.

_Grocery store analogy:_ when you walk in looking for bananas, ice cream, ground beef, oregano, eggs, or chips, you find them quickly because the store has an IA - aisles, signs, and groupings that match how people think about food.

#### Problems IA Addresses

- **Information overload** — users drowning in notifications, emails, apps (e.g., 25,386 unread emails)
- **Exploding data volumes** — global data grew from ~2 ZB (2010) to ~149 ZB (2024), projected ~394 ZB by 2028 (KB → MB → GB → TB → PB → EB → ZB)
- **More ways to access information** — e-books, subway-platform virtual stores, mobile apps, wearables, etc. IA must work across many channels and contexts.

#### The Three Circles of IA

IA lives at the intersection of three concerns:

**Content**

- What type of information are we dealing in?
- What relevance does it have to a user?

**Context**

- Where is a user seeking out this content?
- When, why, and how is a user engaging with this content?

**Users**

- Who is consuming this content?
- What does it mean to them? What value does it provide?
- What pre-existing expectations do they have?

#### Design for Finding

Different models for how people look for information.

##### The "Too-Simple" Information Model

The naïve view: `User asks question → Black magic → User receives answer`.

Real information seeking is messier than this - people don't always know what they want, phrase queries poorly, and refine as they go.

##### Information Needs (Rosenfeld, Morville & Arango - _Information Architecture: For the Web and Beyond_, Ch. 3)

Four fishing metaphors for different information needs:
- **The perfect catch** - _known-item seeking._ The user knows exactly what they want and what it's called (e.g., looking up a specific article by title).
- **Lobster trapping** - _exploratory seeking._ The user wants "a few good things" on a topic but doesn't know exactly what exists.
- **The Drift Net** - _exhaustive research._ The user wants everything on a topic (e.g., a systematic literature review).
- **I've seen you before, Moby Dick…** - _refinding._ The user wants to return to something they've already found.

Visualized as nested zones: the whole grid = _Everything_, an inner cluster = _A few good things_, a single cell = _The right thing_, and a loop = _Need it again_.

##### Information-Seeking Behaviours

**Berry picking** (Bates)
- Users don't issue one query and stop. They start with a query (Q0), find some useful items, adjust their thinking (T), issue a new query (Q1), find more, adjust again, and so on until they exit (E).
- The query and the need both evolve as the user learns.

**Pearl growing**
- Start with one known good document (the "key pearl").
- Use its references / keywords / related items to find more pearls (wave 1).
- Use those to find still more (wave 2), and so on.
- Common in academic research: follow citations outward.

##### Supporting These Behaviours

Good IA accommodates berry picking and pearl growing — e.g., Amazon's search lets you refine by category, format, language, availability, and recently viewed items, so you can shift your query as you learn.

##### Learning About Users' Information Needs
- **Search analytics** — e.g., Google Trends (`https://trends.google.com/trends/`); high volume of real user data.
- **Contextual inquiry** — observe how users interact with information in their "natural" settings, and ask them _why_ they're doing what they're doing.

#### Design for Understanding

How people make sense of **where they are** and **what they can do** there. Good IA provides basic organizing principles that make information environments more understandable.

##### A Sense of Place

Physical spaces give us cues - your morning routine works because the bathroom, kitchen, and closet are laid out in predictable ways.

##### Places Made of Information

We talk about digital environments using spatial language: we "go" online, "visit" a website, "enter" a chatroom.

Unlike physical architecture - which composes walls, roofs, and furniture - **information architecture composes semantic elements**: navigation labels, section headings, keywords. It produces the design principles, goals, and guidelines that capture the intended _feeling_ of the place.

Examples of information-places: a bank website, a hospital site, a recipe app, Facebook's feed.

##### Organizing Principles

**Structure and Order**
- Just as buildings use columns, entrances, and rooms to create order, websites use headers, nav bars, and sections.
- _Example:_ CourseLink's top bar (Course Home, Content, Groups, Dropbox, Discussions, Grades, Course Admin, CourseLink Help) establishes a consistent structure across every course.

**Typologies**
- Recognizable **patterns of organization** reused across many instances of the same kind of thing.
- _Physical example:_ the _basilica_ floor plan (nave, transept, apse) - a repeatable church typology.
- _Digital example:_ bank websites all tend to share a typology (login area, Personal / Small Business / Commercial sections, products like Checking, Loans, Credit Cards, etc.).
- _Another example:_ airline websites (Book / Check-in / Flight Status / Manage Trips) follow a typology that makes a new airline site feel familiar.

**Modularity and Extensibility**
- Good IA, like good architecture, is built in layers that can change at different rates - _Site → Structure → Skin → Services → Space Plan → Stuff_ (Stewart Brand's shearing layers).
- Lets a system evolve: the skin (visual design) can be redone without tearing out the structure (core nav and content model).
- _Example:_ FedEx's site has been redesigned many times over the years, but the core modules (Ship, Track, Manage, Support) remain stable - the skin changes, the structure doesn't.

##### Example — The Happiest Place(s) on Earth
- Each Disney park follows the same IA pattern: `Disneyland → {Main Street, Frontierland, Adventureland, Fantasyland, Tomorrowland} → {Attractions, Restaurants, Shops, Services}`.
- That same typology is reused across parks (Disneyland 1955, Magic Kingdom 1971, Tokyo Disneyland 1983, Parc Disneyland Paris 1992, Hong Kong Disneyland 2005, Shanghai Disneyland 2016) - each with its own variations (e.g., Tokyo's "World Bazaar" in place of Main Street, Paris's "Discoveryland" in place of Tomorrowland).
- Demonstrates structure + typology + modularity + extensibility all at once.

#### The Anatomy of an Information Architecture

Four systems work together:
- **Organization system** - how content is grouped and categorized (by topic, audience, task, chronology, etc.)
- **Navigation system** - how users move through the content (menus, breadcrumbs, links)
- **Search system** - how users query for content directly
- **Labeling system** - the words used for categories, links, and headings (must match user vocabulary)

##### Top-Down IA

Creating architecture **directly from understanding product objectives and user needs.** You start from what the business wants and what users are trying to do, and design the structure to answer their questions.

Typical questions a top-down IA should answer on a homepage:
1. Where am I?
2. I know what I'm looking for — how do I search for it?
3. How do I get around this site?
4. What's important and unique about this organization?
5. What's available on this site?
6. What's happening there?
7. How do I engage with them via other digital channels?
8. How can I contact a human?
9. What's their address?
10. How can I access my account?

##### Bottom-Up IA

Creating architecture **directly from analysis of the content and functional requirements.** You start from the actual content items (recipes, photos, messages) and let their structure and attributes drive how things are grouped, tagged, and searched.

_Example:_ a recipe app's step-by-step view is shaped by the content itself (ingredients, prep time, cook time, steps). A phone's Photos search that recognizes "cat" or text in images emerges from analyzing the content rather than from a top-down menu.

Most real IAs combine both: top-down to answer user questions, bottom-up to handle the actual content.

### Card Sorting (Lec 9)

#### What Is Card Sorting?

Card sorting is a **UX research method** used to understand how users categorize information. Participants are given a set of cards (each representing a piece of content or a feature) and asked to group them.

**Why use it:**

- Helps structure websites and apps intuitively
- Aligns navigation with user expectations
- Reveals mental models directly, without having to guess

#### Types of Card Sorting

| Type       | Participants                                             | Purpose                         |
| ---------- | -------------------------------------------------------- | ------------------------------- |
| **Open**   | Create their own categories                              | Discover user mental models     |
| **Closed** | Sort into predefined categories                          | Validate an existing IA         |
| **Hybrid** | Both — sort into given categories _and_ propose new ones | Mix of discovery and validation |

#### Open Card Sorting

Participants are given the cards and asked to **create their own groups** from scratch — no categories are provided.
- Reveals how users naturally categorize content → direct insight into their mental models
- Analogous to **unsupervised learning / clustering** in data science: groups emerge from similarity, with no predefined labels
- Users cluster cards based on how similar _they_ think they are

#### Closed Card Sorting

Participants are given the cards **and a set of predefined group headings**, and asked to sort cards into those groups.
- Useful for **validating** an existing information architecture: do users' mental models line up with the categories we've already designed?
- Analogous to **supervised learning / classification** in data science: the labels exist in advance, and items are assigned to the best-fitting one

#### When to Use Card Sorting

Card sorting fits any situation where **organizing content** is the central problem:
- Designing a new website or app
- Improving findability of existing content
- Refining menu labels and category names
- Reorganizing an IA that users struggle with

#### Running a Card Sorting Study

##### Steps
1. **Create the cards.** Be careful not to overload participants — roughly 30 to 50 cards is a reasonable ceiling.
2. **Pilot test** on a small group first to catch unclear cards or wording, then refine.
3. **Recruit participants** and have them sort the cards (open, closed, or hybrid).
4. **Analyze the data** — look for patterns across participants.

##### Data Collection

Both flavours of data are worth collecting during a session:
- **Qualitative:** Ask participants _why_ they grouped cards a certain way. Think-aloud protocols work well — have them narrate their reasoning in real time.
- **Quantitative:** Look at the statistical shape of the results. How often are two specific cards grouped together across participants? Are there card pairs that are almost always co-located? Are there correlations between categories?

##### Post-Session Questions

After the sort itself, ask participants to identify:
- Items that were **difficult to group**
- Items that could plausibly belong in **multiple groups**
- Ideas for any **unsorted** or leftover items
- Items they think are **missing** and would add

These debrief questions often surface the most useful insights — the edge cases where the IA will struggle.

### GESTALT (Lec 10)

#### What Are Gestalt Principles?

**Gestalt principles** are a set of theories from perceptual psychology that explain how humans organize visual information - how our brains take messy inputs and construct structured, meaningful wholes.

Designers apply these principles to organize content on websites and interfaces so that it is **aesthetically pleasing and easy to understand**. The underlying idea: if you design _with_ how perception already works, users don't have to work as hard to read the interface.

#### The Six Principles

The lecture covers six of the most commonly recognized Gestalt principles: **continuation, similarity, closure, proximity, symmetry, and figure/ground**.

##### Continuation

Users group elements that appear to **follow a path** (a line, curve, or direction). The eye prefers smooth continuous flow over abrupt breaks, so when dots or shapes trace a trajectory, we perceive them as one continuous group rather than a collection of fragments.

_Classic example:_ the **Amazon logo** - the arrow from _a_ to _z_ visually continues as a smile, which users perceive as a single unified gesture rather than two separate marks.

##### Similarity

The eye builds relationships between **visually similar elements** - similar in colour, shape, size, or orientation. Items that share visual properties read as belonging to the same group, even when they're spatially scattered.

_Design use:_ menu items that share a color or typography signal "these are all navigation links" without needing explicit grouping. Restaurant menus often use matching colour swatches on section headings so each section reads as one unit.

##### Closure

The brain prefers **complete shapes**, so when a figure is missing pieces, we mentally fill in the blanks. Three pac-man shapes arranged with their notches facing inward are perceived as a triangle floating over three circles, even though no triangle is actually drawn.

_Classic example:_ the **WWF panda logo** - the panda is constructed from disconnected black shapes, but we see a complete animal. Same principle behind logos where a hand "holds" an absent lightbulb drawn only from its base.

##### Proximity

**Things that are close together are perceived as related.** Spacing alone - with no lines, boxes, or colour changes - is enough to communicate grouping. A grid of dots becomes "three columns" or "four rows" depending purely on which dots sit closer together.

_Design use:_ form field labels placed close to their inputs; search result snippets clustered so title + URL + description read as one item; product cards separated by whitespace so each one is a distinct unit.

##### Symmetry

Symmetrical elements are perceived as a **unified group**. The brain treats balanced compositions as stable and orderly, and it tolerates asymmetry less well than most designers assume. Even a slightly off-balance navigation bar - where icons are distributed unevenly across the menu - feels subtly "wrong" to users compared to a symmetrical version.

_Classic example:_ the **Google homepage** - logo centered, search bar centered below, two buttons centered below that. The whole page is bilaterally symmetric, which makes it feel calm and focused.

##### Figure / Ground

The eye **differentiates an object (figure) from its surrounding area (ground).** A shape is perceived as the figure while everything around it becomes background. Which region the viewer picks as "figure" vs "ground" can sometimes flip - the classic optical illusion of two faces vs a vase.

_Design use:_ modal dialogs darken the page behind them so the modal unambiguously becomes figure. Poster designs (Melbourne Food & Wine Festival - the negative space between wine bottles forms a fork; Peter and the Wolf - the wolf's body forms the profile of a boy's face) play deliberately with this ambiguity.

### Interaction Design (IxD) (Lec 10 + 11)

#### UI vs IxD vs UX

These three terms overlap but describe different scopes:

| Term    | Full Name          | Scope                                                                    |
| ------- | ------------------ | ------------------------------------------------------------------------ |
| **UI**  | User Interface     | What happens _on the screen_ - buttons, layouts, colours                 |
| **IxD** | Interaction Design | The **dialogue** between user and system - the overlap of UI and UX      |
| **UX**  | User Experience    | What happens _in front of the screen_ - the user's whole felt experience |

IxD sits in the intersection: it's where static interface meets dynamic experience.

#### Definition

> "Interaction Design is the creation of a dialogue between a person and a product, system, or service. This dialogue is both physical and emotional in nature and is manifested in the interplay between form, function, and technology as experienced over time."

The key word is **dialogue** - IxD treats use as a two-sided conversation rather than a one-way input-to-output pipeline.

#### The Five Dimensions of IxD

IxD can be decomposed into five progressively richer dimensions. Each new dimension layers on top of the previous ones.

##### 1D - Words

**Words** are the text elements of an interface: button labels, headings, microcopy, error messages. Their job is to give users the **right amount of information** — enough to act confidently, not so much that they have to wade through it.

_Example:_ the difference between a "Delete" button and a "Yes" button in a confirmation dialog. "Do you want to delete this contact? [Cancel] [Delete]" is clearer than "[Cancel] [Yes]" because the action label restates the consequence — the user can confirm without re-reading the prompt.

##### 2D - Visual Representations

**Visual representations** are the graphical elements: images, typography, icons, illustrations. They aid interaction by encoding meaning visually and reinforcing the words.

_Example:_ an "Add to cart" button gains clarity when paired with a cart icon - even non-English readers grasp the function at a glance.

##### 3D - Physical Objects / Space

The **medium through which users interact** - mouse, touchscreen, keyboard, stylus, game controller, drum peripheral, VR headset. This dimension covers the physical affordances of the input device and the space the interaction happens in.

_Example:_ the _Taiko no Tatsujin_ games - same game, but played with an arcade cabinet drum, Switch Joy-Cons, a home drum peripheral, or a phone screen. The physical medium reshapes the interaction even when the software is identical.

##### 4D - Time

**Time** covers media and interface elements that change over time: animations, transitions, videos, sounds, loading indicators.

_Example:_ a loading spinner tells the user the system is working; a **skeleton screen** (blurred placeholder content that morphs into real content) does the same job but feels faster because something changes visually. An error page like Chrome's "No internet" dino frames a time-based failure in a way that's less frustrating than a blank screen.

##### 5D - Behavior

**Behavior** is how the previous four dimensions combine to define the interactions a product **affords**, and how the product **reacts** to user input and provides feedback. It's the emergent layer - the actual back-and-forth of use.

Behavior answers questions like: what can the user do here? What does the system do in response? How does it let the user know the action registered? It's where IxD becomes a genuine dialogue rather than a static screen.

#### IxD Patterns in the Wild

Common IxD patterns to recognize (from the in-class scavenger hunt):

- **Touch & gesture:** swipe, pinch-to-zoom, double-tap to like, long press / haptic touch, drag-and-drop, shake-to-undo
- **Visual feedback & motion:** loading animations, pull-to-refresh, ghost buttons, parallax scrolling, scroll progress indicators, typing indicators
- **Haptic & audio feedback:** keyboard haptics, Taptic Engine responses, button click sounds, error sounds, voice-assistant audio cues, game controller vibration
- **Navigation & IA:** floating action buttons (FAB), hamburger menus, breadcrumbs, sticky headers, contextual toolbars

#### Emerging Technologies in IxD

Areas where IxD is actively being reshaped:

- **Conversational interfaces** - chatbots, voice assistants (Alexa, Siri)
- **Haptic & gesture interfaces** - VR/AR, air-gesture controls
- **AI & personalization** - adaptive interfaces, smart recommendations
- **Wearables & ubiquitous computing** - smartwatches, IoT devices

## Post-Midterm (60%)

### Dark Patterns (Lec 15)

Dark patterns are interface practices that steer, deceive, coerce, or manipulate people into choices that are often not in their best interests (money, data, or attention).

What to look for:
- Unequal choices (easy yes / hard no)
- Hidden or delayed information
- Ambiguous wording
- Default settings that benefit the company
- Hard-to-exit flows (cancel/delete)
- Emotion/urgency pressure

**10 common dark pattern types**
- **1) Confirmshaming** - Uses guilt, shame, or emotional framing to make refusal feel like a "bad" choice
	- Looks like
		- "No thanks, I hate saving money."
		- Neutral option is visually downplayed or insulting.
	- Harms / risks
		- Undermines voluntary consent; can exploit vulnerable users.
	- Fair alternative
		- Use neutral labels, equal button weight, and respectful language.
- **2) Fake urgency / FOMO** - Creates pressure to act quickly using time limits, scarcity, or vague "something happened" prompts.
	- Looks like
		- Countdown timers that reset.
		- "Only 2 left!" without proof; vague "don't miss out" alerts.
	- Harms / risks
		- Leads to impulsive choices; increases unwanted purchases/consent.
	- Fair alternative
		- Use verifiable urgency (real deadlines/stock) or remove urgency cues.
- **3) Nagging** - Repeatedly asks for the same permission or action without allowing a durable "no."
	- Looks like
		- Only "Not now" (no "Never").
		- Same prompt re-appears each session/day.
	- Harms / risks
		- Consent fatigue; users accept just to stop interruptions.
	- Fair alternative
		- Respect "No" for a meaningful period and provide settings access anytime.
- **4) Sneaking** - Adds extra items, fees, or actions into a flow without clear, explicit opt-in.
	- Looks like
		- Add-on is pre-included in cart.
		- Hidden costs appear late in checkout.
	- Harms / risks
		- Unintended spending; user confusion and regret.
	- Fair alternative
		- Default-off for add-ons; clear itemized summary before purchase.
- **5) Disguised ads** - Makes ads look like navigation, downloads, or normal content, inviting misclicks.
	- Looks like
		- "Download" buttons that are ads.
		- Sponsored items styled like regular results/cards.
	- Harms / risks
		- Misclicks, scams/malware risk, wasted time and attention.
	- Fair alternative
		- Clear labels ("Ad"), spacing, and visual separation from content.
- **6) Intentional misdirection** - Uses wording, layout, or visual hierarchy to push the user toward the company-preferred option.
	- Looks like
		- Big primary button for "Accept"; reject is small/hidden.
		- Ambiguous labels like "Cancel" (cancel action vs cancel subscription).
	- Harms / risks
		- Users make choices they didn't intend; informed consent is weakened.
	- Fair alternative
		- Use clear labels and symmetric prominence for accept vs refuse.
- **7) Roach motel (easy in, hard out)** - Makes it easy to sign up but difficult to cancel, delete, or undo.
	- Looks like
		- Signup in 1–2 steps; cancellation buried in settings.
		- Cancel requires phone call or many screens.
	- Harms / risks
		- Traps users into subscriptions; time and money loss.
	- Fair alternative
		- Provide cancellation parity (same channel, comparable steps)
- **8) Preselection (defaults)** - Pre-checks boxes or toggles so the company-benefiting choice happens unless the user notices and opts out.
	- Looks like
		- Newsletter checkbox already checked.
		- Travel insurance / add-ons preselected.
	- Harms / risks
		- Accidental opt-ins; user loses control and transparency.
	- Fair alternative
		- Default-off for non-essential options; ask with explicit opt-in.
- **9) Friend spam (contacts)** - Obtains access to contacts/social graph in ways users don't fully understand, sometimes sending invites on their behalf.
	- Looks like
		- "Find friends" imports all contacts by default.
		- Invites are sent automatically or with unclear consent.
	- Harms / risks
		- Privacy invasion; reputational harm (spam "from you").
	- Fair alternative
		- Explicit permission + preview + select recipients (default).
- **10) Negative option billing / forced continuity** - A trial or discount quietly converts into recurring charges unless the user cancels in time.
	- Looks like
		- "Free trial" requires card; auto-renew is downplayed.
		- No reminder before billing; cancellation is hard.
	- Harms / risks
		- Unexpected charges; disputes; long-term distrust.
	- Fair alternative
		- Clear renewal terms + reminders + easy cancel (same channel).

### UX Laws & Cognition (Lec 16)

#### Fitts' Law

*Predicts how long it takes to point/click/tap a target*

Movement time grows with distance (D) and shrinks with target width (W).
`MT = a + b · log₂( D / W + 1 )`
- D = distance to target; W = target size along movement axis
- a and b are empirically derived constants depend on device + context
- Index of Difficulty: ID = log₂(D/W + 1) → "how hard the pointing is"

Original experiment from Paul Morris Fitts involved tapping on plates as quickly as possible.

**Design Tips**
- Make small targets larger
- Use Screen Edges
- Optimizing Distance to Target

#### Hick-Hyman Law

*Predicts how choice complexity affects decision time*

Decision time increases with the number of choices (and their complexity).
`T = a + b · log₂(n + 1)`
- T: decision time (reaction/selection time)
- n: number of choices
- a: baseline time (perception/overhead)
- b: slope (how strongly choice complexity slows people)

**Design Tips**
- Simplify Navigation Across the Journey
- Group Related Information
- Prioritize Important Actions at All Times
- Use Progressive Disclosure

#### Miller's Law

*How many "chunks" can users hold in mind at once?*

The average person can only keep 7 (plus or minus 2) items in their working memory.

*A "chunk" is a meaningful grouping (e.g., 416-555-1212)*

#### Jakob's Law

*People expect your UI to behave like other UIs they already know*

Users spend most of their time on other sites → they prefer your site to work the same way as those sites.

- Conventions reduce learning cost (navigation, icons, forms, checkout)
- Breaking conventions requires strong payoff + clear signposting
- In dark patterns, breaking conventions is used to trick (e.g., "X" doesn't close)

### WCAG Principles and Guidelines (Lec 17 + 18)

#### Perceivable

Information and user interface components must be presented in ways that all users can perceive. The goal is to make information accessible to users with visual, auditory, or other sensory limitations.

**Guidelines:**
- **1.1 Text Alternatives:** Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as large print, braille, speech, symbols or simpler language.
	- ensure that all non-text content is also available in text. "Text" refers to electronic text, not an image of text. Electronic text has the unique advantage that it is presentation neutral. That is, it can be rendered visually, auditorily, tactilely, or by any combination. As a result, information rendered in electronic text can be presented in whatever form best meets the needs of the user. It can also be easily enlarged, spoken aloud so that it is easier for people with reading disabilities to understand, or rendered in whatever tactile form best meets the needs of a user.
- **1.2 Time-based Media:** Provide alternatives for time-based media.
	- provide access to time-based and synchronized media. This includes media that is:
		- Audio-only
		- Video-only
		- Audio-video
		- audio and/or video combined with interaction
- **1.3 Adaptable:** Create content that can be presented in different ways (for example simpler layout) without losing information or structure.
	- ensure that all information is available in a form that can be perceived by all users, for example, spoken aloud, or presented in a simpler visual layout. If all of the information is available in a form that can be determined by software, then it can be presented to users in different ways (visually, audibly, tactilely etc.). If information is embedded in a particular presentation in such a way that the structure and information cannot be programmatically determined by the assistive technology, then it cannot be rendered in other formats as needed by the user.
- **1.4 Distinguishable:** Make it easier for users to see and hear content including separating foreground from background.
	- making information available in a form that can be presented in alternate formats, this guideline is concerned with making the default presentation as easy to perceive as possible to people with disabilities. The primary focus is on making it easier for users to separate foreground information from the background. For visual presentations this involves making sure that information presented on top of a background contrasts sufficiently with the background. For audio presentations this involves making sure that foreground sounds are sufficiently louder than the background sounds. Individuals with visual and hearing disabilities have much greater difficulty separating foreground and background information.

#### Operable

Users must be able to navigate and interact with all interface elements easily. The goal is to ensure that all users can access functionality, even if they rely on keyboards, screen readers, or other assistive tools.

**Guidelines:**
- **2.1 Keyboard Accessible:** Make all functionality available from a keyboard.
	- If all functionality can be achieved using the keyboard, it can be accomplished by keyboard users, by speech input (which creates keyboard input), by mouse (using on-screen keyboards), and by a wide variety of assistive technologies that create simulated keystrokes as their output. No other input form has this flexibility or is universally supported and operable by people with different disabilities, as long as the keyboard input is not time-dependent.
- **2.2 Enough Time:** Provide users enough time to read and use content.
	- Many users who have disabilities need more time to complete tasks than the majority of users: they may take longer to physically respond, they may take longer to read things, they may have low vision and take longer to find things or to read them, or they may be accessing content through an assistive technology that requires more time. This guideline focuses on ensuring that users are able to complete the tasks required by the content with their own individual response times. The primary approaches deal with eliminating time constraints or providing users enough additional time to allow them to complete their tasks. Exceptions are provided for those cases where this is not possible.
- **2.3 Seizures and Physical Reactions:** Do not design content in a way that is known to cause seizures or physical reactions.
	- Some people with seizure disorders can have a seizure triggered by flashing visual content. Most people are unaware that they have this disorder until it strikes. In 1997, a cartoon on television in Japan sent over 700 children to the hospital, including about 500 who had seizures. Warnings do not work well because they are often missed, especially by children who may in fact not be able to read them.
		- *MARCUS NOTE: I think this is talking about the porygon episode from pokemon lol*
- **2.4 Navigable:** Provide ways to help users navigate, find content, and determine where they are.
	- help users find the content they need and allow them to keep track of their location. These tasks are often more difficult for people with disabilities. For finding, navigation, and orientation, it is important that the user can find out what the current location is. For navigation, information about the possible destinations needs to be available. Screen readers convert content to synthetic speech which, because it is audio, must be presented in linear order.
- **2.5 Input Modalities:** Make it easier for users to operate functionality through various inputs beyond keyboard.
	- All functionality should be accessible via pointer input devices, for example, via a mouse pointer, a finger interacting with a touch screen, an electronic pencil/stylus, or a laser pointer.

#### Understandable

Content and interface elements must be clear and easy for all users to comprehend. The goal is to
create a predictable and intuitive experience, minimising confusion or frustration.

**Guidelines:**
- **3.1 Readable:** Make text content readable and understandable.
	- allow text content to be read by users and by assistive technology, and to ensure that information necessary for understanding it is available
- **3.2 Predictable:** Make web pages appear and operate in predictable ways.
	- help users with disabilities by presenting content in a predictable order from web page to web page and by making the behavior of functional and interactive components predictable. It is difficult for some users to form an overview of the web page: screen readers present content as a one-dimensional stream of synthetic speech that makes it difficult to understand spatial relationships. Users with cognitive limitations may become confused if components appear in different places on different pages.
- **3.3 Input Assistance:** Help users avoid and correct mistakes.
	- Everyone makes mistakes. However, people with some disabilities have more difficulty creating error-free input. In addition, it may be harder for them to detect that they have made an error. Typical error indication methods may not be obvious to them because of a limited field of view, limited color perception, or use of assistive technology. This guideline seeks to reduce the number of serious or irreversible errors that are made, increase the likelihood that all errors will be noticed by the user, and help users understand what they should do to correct an error.

#### Robust

Content must be designed to work well across a variety of devices, browsers, and assistive technologies, ensuring long-term accessibility. The goal is to create a resilient experience that remains functional as technologies evolve.

**Guidelines:**
- **4.1 Robust:** Maximize compatibility with current and future user agents, including assistive technologies.
	- to support compatibility with current and future user agents, especially assistive technologies (AT). This is done both by 1) ensuring that authors do not do things that would break AT (e.g., poorly formed markup) or circumvent AT (e.g., by using unconventional markup or code) and 2) exposing information in the content in standard ways that assistive technologies can recognize and interact with. Since technologies change quickly, and AT developers have much trouble keeping up with rapidly changing technologies, it is important that content follow conventions and be compatible with APIs so that AT can more easily work with new technologies as they evolve.

#### WCAG Video Playlist

Playlist suggested by Zhao herself:

[WCAG YouTube Playlist](https://www.youtube.com/playlist?list=PLWSYD-KxdDxvhRinqF4EufZF5mgazU23a)

### HCI Research Methods (Lec 19)

**Qualitative methods**
- focus on words, stories, explanations, and observations
- help us understand experiences, motivations, frustrations, and context
- often use smaller samples
- good for discovering issues and generating insights

**Quantitative methods**
- focus on numbers, measures, frequencies, and comparisons
- help us measure performance and patterns
- often use larger samples or repeated tasks
- good for comparing designs or tracking outcomes

**Qualitative and quantitative methods are not rivals.**
- They answer different questions, and many strong research use both.
- qualitative data explains why problems happen
- quantitative data shows how much they matter

| Design question               | Best fit      |
| ----------------------------- | ------------- |
| What frustrates users?        | Qualitative   |
| What do users need?           | Qualitative   |
| Which design performs better? | Quantitative  |
| How many users succeed?       | Quantitative  |
| What is happening and why?    | Mixed methods |

#### Method 1: Interviews

- What it is
	- a conversation with users about experiences, habits, needs, or opinions
	- often semi-structured: some planned questions, but room to follow interesting ideas
- Good for
	- exploring a new problem space
	- understanding motivations
	- learning about everyday context
	- finding unmet needs
- Watch out for
	- leading questions
	- users may forget or simplify what they do
	- small samples do not give broad statistics

**Roles:**
- **Interviewer**
	- asks the questions
	- keeps the conversation going
	- listens carefully
	- avoids interrupting or judging
- **Interviewee**
	- answers based on real experience
	- gives detailed examples
	- explains thoughts, feelings, and frustrations
- **Observer**
	- does not speak during the interview
	- takes notes on the interaction
	- watches for strong questions, weak questions, and interesting responses

#### Method 2: observation and contextual inquiry

- What it is
	- watching users do real tasks in context
	- focusing on what they actually do - not only what they say they do
- Useful for
	- workflows and step-by-step actions
	- physical or social context
	- hidden workarounds
	- pain points users may not mention on their own
- Limitations
	- people may act differently when observed
	- can take more time than a short interview
	- not always easy to access real settings
- What observation gives you
	- behaviour, sequence, context
- What interviews may miss
	- small confusions that users forget to mention

#### Method 3: think-aloud usability testing

- What it is
	- give a participant tasks to complete
	- ask them to say what they are thinking while they interact
	- observe where expectations break down
- Produces
	- qualitative insight from comments and behaviour
	- and sometimes simple metrics such as success rate or time on task
- Good for
	- finding usability issues
	- comparing prototype versions
	- testing flows before launch

#### Method 4: surveys

- What surveys do well
	- collect input from many people efficiently
	- capture preferences, attitudes, and self-reported behaviour
	- work well for broad feedback
- Quantitative side
	- Likert scales
	- multiple choice
	- rankings
	- ratings
- Qualitative side
	- open-ended responses
	- comments in participants' own words
	- follow-up ideas for later research

**Survey Design Tips**
- Do
	- keep questions short and clear
	- ask one thing at a time
	- use balanced response options
	- include one or two open-ended questions if needed
- Avoid
	- leading questions
	- jargon users may not understand
	- double-barrelled questions like "easy and enjoyable"
	- too many questions that create survey fatigue

#### Method 5: metrics and simple quantitative evaluation

- Common HCI metrics
	- task completion rate
	- time on task
	- error rate
	- number of clicks or steps
	- satisfaction rating
- Best for
	- benchmarking a design
	- comparing two versions
	- showing improvement over time
- Remember
	- numbers can show what happened
	- but often not why it happened

**A/B testing and comparison studies**
- What it is
	- compare two interface versions
	- keep the task similar and measure which version performs better
	- look at outcomes such as success, speed, or preference
- Best used when
	- there is a clear comparison question
	- you can define a measurable outcome
	- the two alternatives differ in a meaningful way

#### Formative vs. summative research

**Formative research**
- happens earlier in the design process
- aims to improve the design
- common examples: interviews, observation, pilot testing

**Summative research**
- happens later when the design is more stable
- aims to assess or compare
- common examples: benchmarking, comparison tests, performance metrics

### HCI Data Analysis (Lec 20)

#### Quantitative Data Analysis

**Types of Data**
- Nominal
	- **Example:** Button colour chosen
	- **Good tests:** Mode, Chi-square
- Ordinal
	- **Example:** Likert scale rating
	- **Good tests:** Median, Mann-Whitney
- Interval
	- **Example:** Temperature, IQ
	- **Good tests:** Mean, T-test, ANOVA
- Ratio
	- **Example:** Task completion time
	- **Good tests:** Mean, T-test, ANOVA

##### T-Test

Tests whether the means of two groups differ more than expected by chance.

The T-test calculates a ratio that looks at two things simultaneously:
- How big is the difference between the two group means?
- How much natural variation is there within each group?

**p-value**
- Probability of your results if there were no real effect.
- p < 0.05 is a threshold, not a measure of importance.

**effect size**
- How large is the difference in practical terms?
- Cohen's d (T-test): 0.2 small · 0.5 medium · 0.8 large
- Eta-squared η² (ANOVA): 0.01 small · 0.06 medium · 0.14 large

**Step-by-Step**
1) State Hypothesis
2) Check Assumptions
3) Run Independent T-Test
4) Calculate Effect Size
5) Interpret

##### One-Way ANOVA (Analysis of Variance)

**When to use**
- 3 or more independent groups, one continuous outcome.
- Example: Compare error rates across 3 navigation designs (A, B, C)

**The Logic**
- `F = variance between groups / variance within groups`
- Large F → groups differ more than expected by chance.
- A significant F tells you 'something differs' - not which pair.
	- Follow up with Tukey HSD to find which pairs differ.

#### Qualitative Data Analysis

Qualitative data answers WHY - the numbers tell you what happened; qual tells you why users struggled.

- **Think-Aloud Protocol:** Participants narrate actions; captures confusion, reasoning, mental models.
- **Interviews:** Semi-structured; deep dives into user needs, motivations, pain points.
- **Open-ended Surveys:** Free-text responses to survey questions; scalable qual data.
- **Observation Notes:** Field notes from contextual inquiry or usability sessions.

##### Thematic Analysis
1) **Familiarize:** Read all transcripts/notes multiple times. Jot initial impressions.
2) **Generate Codes:** Label meaningful segments. Codes are descriptive, close to data.
3) **Search for Themes:** Group related codes. Look for patterns across participants
4) **Review Themes:** Check themes against coded data & full dataset. Merge/split as needed.
5) **Define & Name:** Write a clear definition for each theme. Capture its essence.
6) **Write Up:** Weave themes into a narrative supported by participant quotes.

##### Affinity Diagramming

**What & When**
- Collaborative method to organize observations from interviews, usability tests, or notes into clusters of related ideas.

**The process**
1) Write one observation per sticky note
2) Silently group similar notes together
3) Label each cluster with a heading
4) Identify higher-level themes from clusters
5) Photograph and document the result

##### Trustworthiness in Qualitative Research
- **Credibility:** Member checking, prolonged engagement, peer debriefing
- **Transferability:** Thick description - describe context so readers judge applicability
- **Dependability:** Audit trail - document decisions, code changes, rationale
- **Confirmability:** Reflexivity - acknowledge researcher bias and its potential influence

#### Mixed Methods

- Quant: identifies WHAT; Qual explains WHY
- Discover in qual -> test in quant

**Quantitative reporting**
1. State the test used and why it was appropriate
2. Report statistic, p-value: t(38) = 2.14, p = .038
3. Always include effect size (Cohen's d or η²)
4. Interpret in plain language for the reader

**Qualitative reporting**
1. Introduce each theme with a clear definition
2. Support every theme with 1–2 participant quotes
3. Interpret the theme - connect it to design implications
4. Don't just describe; analyze and argue

### Future of UX (Lec 21)

**The Traditional UX Workflow**
1) **Research:** User interviews surveys, etc
2) **Ideation:** Brainstorming how-might-we concept sketches
3) **Wireframing:** Lo-fi layouts information architecture content hierarchy
4) **Prototyping:** Interactive mockups user flows hi-fi screens
5) **Testing:** Usability sessions think-aloud protocol error analysis
6) **Iteration:** Synthesise findings prioritise changes re-test

| Before                                                             | After                                                               |
| ------------------------------------------------------------------ | ------------------------------------------------------------------- |
| Wireframes drawn by hand or in Figma, one screen at a time         | AI generates multiple layout options from a text prompt in seconds  |
| Research synthesis done manually with sticky notes or spreadsheets | Tools like Notion AI or Dovetail auto-cluster research themes       |
| Iteration required rebuilding screens from scratch                 | No-code tools let designers (or non-designers) iterate in real-time |
| High technical barrier - non-coders couldn't prototype             | Code generation (Copilot, v0.dev) lowers the technical floor        |
| Days or weeks to produce a testable prototype                      | An interactive prototype can exist within hours of a brief          |

#### The Tools

**No Code**
- Build fully functional products using visual drag-and-drop interfaces - zero programming required
- Who uses it:
	- Designers, marketers, founders, non-technical product teams.
- Examples:
	- Webflow - visual CSS/HTML site builder with CMS
	- Framer - high-fidelity interactive prototyping
	- Bubble - full web app logic builder
	- Glide - mobile apps generated from spreadsheet data

**Low-Code**
- Combines visual building blocks with optional custom code for power users who need flexibility.
- Who uses it:
	- Developers, technical designers, enterprise product teams.
- Examples:
	- Retool - drag-and-drop internal dashboards + SQL
	- OutSystems - enterprise workflow and app builder
	- Microsoft Power Apps - business process automation
	- Appsmith - open-source, self-hosted internal tools

**Why These Tools Matter for UX**
- **Speed to testable:** A prototype that used to take a week can exist in an afternoon. That compresses the research → test loop dramatically - which is good for UX if you use that speed to test more, not test less.
- **Democratized making:** Product managers, clients, and startup founders can now build functional prototypes. This changes the power dynamic: UX designers may increasingly be evaluators and critics, not just makers.
- **Cheaper iteration:** When changing a layout takes minutes instead of hours, designers can explore more directions and throw away bad ideas faster. Iteration cost drops - which should mean better final designs
- **Lower entry barrier:** Communities that previously couldn't afford bespoke software — non-profits, small schools, local businesses - can now build their own tools. No-code has genuine social equity implications.

#### AI Across the UX Workflow

**What AI Genuinely Helps With**
- **Planning phase:** Draft study plans, screeners, interview guides, recruitment emails - including questions you might not have thought of.
- **Desk research:** Aggregate information quickly, summarize long reports, check best practices, acquire domain knowledge for unfamiliar product areas.
- **Analysis phase:** Cluster themes from transcripts, identify patterns across sessions, draft initial findings summaries. NN/g: 'Most helpful for planning and analysis.'
- **Efficiency gains:** NN/g found one practitioner built a full UX Community of Practice proposal - normally several days' work - in under 2 hours using AI

**What AI Cannot Replace**
- **Synthetic users:** the numbers: Interview-based AI twins reached 85% accuracy on survey tasks vs 71% for demographic-only models. But accuracy dropped to 66% for economic decisions.
- **Bias is real and uneven:** Digital twins performed better for white, higher-income, more educated groups. For marginalized populations accuracy was meaningfully lower. AI research proxies can amplify existing inequities.
- **Outsourced analysis loses insight:** When you let AI summarize your raw data, you lose nuance, outliers, and surprises. 'Don't outsource analysis to AI.' The researcher's interpretation is a design artifact in itself.
- **The non-verbal layer is irreplaceable:** Body language, hesitation, tone, unexpected reactions - none survives into text. The most important research moments are often non-verbal

##### CARE Framework

**Context:** describe your situation
- Your role, the product, the users, the specific task you're working on. If you were briefing a new consultant, what would you tell them first?
- Example
	- "I'm a UX designer working on a mental health journaling app for university students under academic stress. Our users are 18–24, often anxious, and access the app late at night."

**Ask:** Request a specific action
- State the role you want AI to play, the exact output you need, how many options, and what format. Be precise - vague asks produce vague outputs.
- Example
	- "Act as a UX writer. Generate 10 error message options for a failed login. Then select the 3 best and rank them with reasoning. Present in a table."

**Rules:** Provide constraints
- Guardrails, best practices, brand voice, character limits, tone requirements. This is where you inject UX knowledge that the AI doesn't have by default.
- Example
	- "Use plain language. Don't be clever or funny. Don't blame the user. Avoid passive voice. Tone: warm and calm, not chipper or clinical. Max 120 characters."

**Examples:** Demonstrate what you want
- Show good examples, bad examples, or existing copy you want to improve: providing examples of existing copy produces more natural output than describing tone.
- Example
	- "Avoid: 'Oopsie, that didn't work!' - too casual for a distressed user. Aim for: 'We couldn't log you in. Check your email and try again.'"

##### AI as an Intern

**Meet Ari - Your AI Intern**
- ✅ Exceptionally book-smart - effective across a huge range of subjects
- ✅ Extremely fast - complex tasks in seconds
- ✅ Never complains, always willing to iterate
- ✅ Great first-draft producer across research, writing, design tasks
- ⚠ No empathy, contextual awareness, or common sense
- ⚠ Will hallucinate - making up facts with total confidence
- ⚠ Sycophantic - will agree with your ideas even when wrong
- ⚠ Can't tell good UX advice from bad LinkedIn posts

**How to Work With Ari**
- **Drafts, not finals:** You wouldn't send an intern's first draft to a stakeholder without reviewing it. Never send AI output without review. It's a starting point, not a deliverable.
- **Double-check everything:** Especially facts, citations, statistics, and UX guidance. AI will cite sources that don't exist. 'ChatGPT said' is not a stakeholder argument.
- **Specific instructions:** Vague prompts produce vague outputs. Walk Ari through each step - use the CARE framework. Don't hand over a big open-ended project.
- **Share context:** Ari has no knowledge of your organization or your users. Provide that context explicitly or the output reflects no one in particular.

##### The 7 Deadly AI Sins for UX Professionals

1) **Sin: Outsourced Thinking**
	- -> Virtue: Ownership
	- Let AI think after you, not instead of you. Think first - then bring AI as a partner. Test: if AI disappeared, could you still do your job?
2) **Sin: Wasted Time**
	- -> Virtue: Automation
	- AI saves time on repetitive tasks you'll do again. For one-off tasks, doing it yourself is often faster. Be discerning about when to dive in.
3) **Sin: Lost Details**
	- -> Virtue: Selectivity
	- AI summaries lose nuance and outliers. When you're accountable for the details — research, key decisions - read the raw material yourself.
4) **Sin: Isolated Ideation**
	- -> Virtue: Inclusion
	- AI ideas don't build team buy-in. Use AI to prepare sharper conversations with colleagues — don't let it replace those conversations.
5) **Sin: Naïve Trust**
	- -> Virtue: Skepticism
	- Hallucinations are real. Verify facts, stats, and UX guidance. Research found AI couldn't write usability tasks to their standards. 'ChatGPT said' isn't evidence.
6) **Sin: Bland Taste**
	- -> Virtue: Originality
	- AI outputs are competent and generic. Taste and discernment are your differentiating value. Modify outputs - don't accept the first draft as an endpoint.
7) **Sin: Defensive Outlook**
	- -> Virtue: Experimentation
	- Don't resist AI out of pride. Find your bottlenecks, give AI a chance there. If it doesn't help, don't force it. Adapt rather than resist.

#### The Risks

**Risk 1 - Generic Design**
- What it looks like:
	- An AI-generated screen looks visually polished. Cards, clean typography, a sidebar, a top nav. It looks like every other SaaS product you've used. Your stakeholder sees it and says 'great, looks done.'
- Why it's a problem:
	- Design is a strategy. The layout should reflect your user's mental model, their task priority, their context of use. Generic layouts serve no one in particular — which means they serve everyone poorly. A design that looks right but isn't grounded in insight is decoration, not UX.

**Risk 2 - Poor User Fit**
- What it looks like:
	- An AI designs a hospital intake app with a 12-step form and dense terminology. Or an app for older adults with 9pt text and icon-only navigation. Or a finance tool that assumes desktop use when 80% of users are on mobile.
- Why it's a problem:
	- AI has never met your users. It knows the average user from its training data — typically young, English-speaking, tech-literate, and Western. Any design that deviates from that average needs a designer who has actually spoken to the target population.

**Risk 3 - Accessibility Gaps**
- What gets missed:
	- Colour contrast failures (WCAG AA requires 4.5:1 ratio for normal text), missing focus indicators for keyboard navigation, unlabelled icon buttons, undefined heading hierarchy, images without alt text, form fields without visible labels.
- Why it matters:
	- AI generates visually appealing layouts - but visual appeal and accessibility are different things. A low-contrast colour scheme can look elegant and be unusable by the 8% of users with colour vision deficiency. These aren't edge cases.

**Risk 4 - False Confidence**
- What it looks like:
	- A hi-fidelity AI prototype goes to stakeholders. Everyone nods. The design 'looks done.' Testing gets dropped from the schedule because there's nothing more to learn from a prototype this finished.
- Why it matters:
	- Fidelity signals completion. When a prototype looks like a real product, the psychological pressure to test it — rather than ship it — drops. This is one of the most consequential risks of AI prototyping tools.

**Risk 5 - Embedded Bias**
- What it looks like:
	- AI-generated personas are predominantly young, able-bodied, tech-literate, and Western. Generated imagery defaults to certain body types and skin tones. Copy assumes heteronormative relationships and English as a first language.
- Why it matters:
	- Design systems built on biased AI output embed those biases into products used by millions. The designer is responsible for the output - 'AI generated it' is not an excuse in a professional or ethical context.

**The Ethical Dimension**
- **Training data & IP:** Most generative AI design tools were trained on images and interfaces scraped from the web - including the work of professional designers, often without consent or compensation. When you use these tools, you are working within a system that has not resolved its relationship with the creative labour it was built on.
- **Ownership of AI output:** Who owns a design generated by AI? The person who wrote the prompt? The company that built the tool? The designers whose work it trained on? Legally, this is unresolved in most countries. Professionally, you are accountable for what you submit - regardless of how it was made.
- **Labour & the profession:** Entry-level UX tasks - wireframing, copywriting, icon selection, basic layout work - are the tasks most directly affected by AI automation. This changes what junior designers are hired for and how they build skills. What does career progression look like in this environment?
- **Whose defaults?:** AI reproduces the assumptions of its training data. Those defaults are Western, English-speaking, abled, and tech-literate. Designers who don't actively work against those defaults embed them into products that reach millions of people.

#### What Designers Still Do

**Productive Uses**
- Generate 10 layout variants to evaluate - not 1 to ship
- Draft microcopy across 20 screens at once, then edit each carefully
- Speed up interview transcription to get to synthesis faster
- Create a rough wireframe to use as a discussion prompt - not a deliverable
- Brainstorm edge cases, error states, and happy paths you might have missed
- Produce a first-pass content structure for a complex information architecture
- Check your own writing for clarity, reading level, and tone consistency

**Dangerous Shortcuts**
- Treating first AI output as a final design decision
- Using AI-generated personas in place of real user research
- Shipping generated copy without reviewing for tone, clarity, and context
- Skipping accessibility review because the output 'looks clean'
- Letting AI define the problem space - it doesn't understand your users
- Using a polished AI prototype as justification to skip usability testing
- Presenting AI work as your own design thinking without attribution or reflection

**What Designers Still Must Do**
- **Understand real users:** Go out and talk to people. Read transcripts. Do contextual inquiry. No tool can substitute the empathy built from sitting with a user who is genuinely struggling with something you designed.
- **Make and defend trade-offs:** Every design involves choosing between competing needs. AI can generate options - but deciding which option is right for your users, your business constraints, and your ethical standards requires human judgment.
- **Test with real humans:**  There is no AI substitute for a usability session. Bring 5 representative users in. Watch them use the product. You will always learn something that changes the design.
- **Take responsibility:** The designer is accountable for the final product - not the tool that helped make it. Accessibility failures, biased outputs, misleading copy, unclear flows: these are design failures, regardless of origin.
- **Frame the right problem:** AI answers the question you ask. Asking the right question — defining the actual problem, not the surface symptom — is the most strategic design skill and the one AI most lacks.

### Smallville Paper (Lec 22)

You can read the full paper here. It's confirmed that she'll ask two questions about it:

[Generative Agents: Interactive Simulacra of Human Behavior (ACM)](https://dl.acm.org/doi/fullHtml/10.1145/3586183.3606763)

**Here is an AI overview of the paper if you are feeling lazy:**
*I would have wrote the summary myself... but I am too lazy. Sorry!*

#### AI Summary

##### The core idea

The paper introduces "generative agents" — computational software agents that simulate believable human behavior. They wake up, cook breakfast, head to work, form opinions, notice each other, initiate conversations, and remember and reflect on past days as they plan the next one. [ACM Digital Library](https://dl.acm.org/doi/abs/10.1145/3586183.3606763) The authors populate a Sims-inspired sandbox town called **Smallville** with 25 of these agents and let users interact with them in natural language.

##### The architecture (the main technical contribution)

The agents extend an LLM (GPT-3.5-turbo) with three components that work together on top of a central **memory stream** — a running log of the agent's experiences in natural language:

1. **Observation / memory stream.** Every experience gets written to the stream as a natural-language record. Memories are retrieved based on recency, importance (mundane to poignant), and relevance to the current situation. [Hugging Face](https://huggingface.co/papers/2304.03442)
2. **Reflection.** Periodically, the agent synthesizes low-level observations into higher-level insights. When the combined importance scores of recent events exceed a threshold (roughly two or three times per in-game day), the system prompts the LLM to ask "what are the most salient high-level questions we can answer about these statements?" and then generates insights like "Klaus Mueller is dedicated to his research on gentrification." [Substack](https://gonzoml.substack.com/p/generative-agents-interactive-simulacra) Reflections can build on earlier reflections, producing a tree of increasingly abstract self-knowledge.
3. **Planning.** Plans prevent the agent from, say, eating lunch three times. Planning is top-down and recursive: first a broad 5–8 point plan for the day is generated from the agent's description and yesterday's summary, then refined to hourly resolution, then to 5–15 minute intervals. [Substack](https://gonzoml.substack.com/p/generative-agents-interactive-simulacra) Plans are themselves written to the memory stream, and agents can react to new observations by revising them.

##### Emergent social behavior

Starting from a single seed — one agent wanting to throw a Valentine's Day party — the agents autonomously spread invitations over two days, form new acquaintances, ask each other out on dates, and coordinate to arrive together at the right time. [ACM Digital Library](https://dl.acm.org/doi/abs/10.1145/3586183.3606763) No one scripted these dynamics; they emerged from the architecture plus the initial seed.

##### Evaluation

Agents were "interviewed" in five areas: self-knowledge, memory retrieval, planning, reacting, and reflecting. 100 human evaluators watched replays of an agent's life and ranked responses from the full architecture, three ablated versions (no reflection, no planning, no observations), and a human-author condition. [Medium](https://artgor.medium.com/paper-review-generative-agents-interactive-simulacra-of-human-behavior-cc5f8294b4ac) Crowdworkers actually rated the generative agents' responses as _more_ believable than those produced by humans pretending to be the agents. [Stanford HAI](https://hai.stanford.edu/news/computational-agents-exhibit-believable-humanlike-behavior) Ablations showed all three components (observation, planning, reflection) contribute meaningfully, with reflection being particularly important for coherent synthesis.

##### Why it matters

Park envisions applications beyond gaming — social prototyping, agent-based modeling in social sciences (he references Schelling's 1971 segregation model, noting generative agents could bring much richer human complexity to that kind of simulation), and ubiquitous computing. [Stanford HAI](https://hai.stanford.edu/news/computational-agents-exhibit-believable-humanlike-behavior)

##### Common failure modes

The most frequent errors were the agent failing to retrieve a relevant memory, fabricating embellishments to its own history, and inheriting overly formal speech patterns from the underlying LLM.
