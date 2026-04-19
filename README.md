# Flemming N. Larsen — Biography

## Short (~200 characters)

Principal Software Engineer. Programming since 1984. Lead developer of Robocode since 2006, and creator of Robocode Tank Royale.

---

## Medium (~500 characters)

Flemming N. Larsen is a Principal Software Engineer and a formally educated computer scientist (cand.scient.dat, Aalborg University, 2001) with certified IT architect qualifications — and unlike many who carry the architect title, he actually trained for it. He has been programming since 1984, lead developer of Robocode since 2006, and creator of Robocode Tank Royale. He advocates Architecture as Code and Spec-Driven Development through plain-text artefacts in version control, and author of the Book of Robocode.

---

## Full

Flemming N. Larsen is a Principal Software Engineer with a focus on Agentic Engineering, Spec-Driven Development, and Architecture as Code. He graduated with a Master's degree in computer science (cand.scient.dat) from Aalborg University in 2001, and has been working professionally ever since. He has been programming since 1984. Over more than two decades his career has spanned embedded systems, telecom middleware, enterprise architecture, and cloud-native backend development — giving him an unusually broad foundation for someone who now works at the architecture and AI layer.

### Where It Started

In 1984, a Danish school introduced a class of fourth-graders to computing via a Butler machine from Regnecentralen — running COMAL with a custom Turtle language built on top of it. Flemming was one of those students. He liked it enough to get an access card so he could use the machine after school, often alone.

One day he accidentally interrupted the Turtle program and saw COMAL underneath. He went to the library, read a book on COMAL 80, and wrote a circle routine to extend the teacher's Turtle program. His access card was confiscated. He was ten years old.

With no computer at home, he made do: a hand-me-down Lambda 8300 — a ZX81 clone with a 16KB RAM expansion that reset the machine when touched, and no tape or disk drive, meaning every program had to be rebuilt from scratch. From there: a Sharp pocket PC, a Commodore VIC-20, then a Commodore 64, and finally an Amiga 500, where he wrote assembler. None of it was handed to him.

### Robocode

Robocode is a programming game where you write the AI for a robot battle tank — you code it, then watch it fight. It was created by Mathew Nelson at IBM in 2001. When active development stopped in 2006, Flemming stepped up as lead developer and has driven the project ever since — 20 years of features, fixes, and Java version compatibility, version by version. It is a leisure project alongside his professional work, with no commercial involvement. He earns nothing from it.

Working within the constraints of an active tournament community (RoboRumble, later LiteRumble) meant that determinism was non-negotiable and backwards compatibility was demanded. He built within those limits — and built well. But the architecture was never his to reshape.

Robocode Tank Royale is what he built when he finally had a blank canvas. Development began privately in 2010 — while simultaneously maintaining classic Robocode for its community — and was made public in 2022. The core engineering challenge he had to solve piece by piece: how do you build a real-time game that works across all platforms and is straightforward to implement in any programming language? The answer was a protocol-based architecture over WebSockets — modular, language-agnostic, and platform-independent. Classic Robocode he considers legacy. Tank Royale is the platform's future.

> "This is my game and I have been using all my skills to develop it."

He is also the author of [The Book of Robocode](https://book.robocode.dev/), a comprehensive guide covering both platforms. It was written because the community wiki was decaying and outside his control — if it is not in a repo you own, it will rot.

### Architecture as Code and Plain Text as Code

Flemming is a formally educated computer scientist with certified IT architect qualifications (DISAC Foundation and Practitioner, 2014). In a field where many carry the architect title without ever having studied it, he actually trained for it. He does not find rigid architectural frameworks useful in practice — his actual tools are Structurizr C4, UML, and Mermaid, all as plain text. But what defines his thinking is not the frameworks or tools — it is a philosophy he has been building and practising for years, grounded in real architectural training and two decades of backend systems in the Cloud with Kubernetes, primarily in Java and Kotlin.

He believes that anything worth knowing about a system should live as plain text in version control. *Infrastructure as Code* proved the concept. *Architecture as Code* extends it. *Plain Text as Code* takes it all the way.

In practice this means: ADRs for decisions, C4 diagrams in Structurizr DSL for structure, domain models in Mermaid, specifications in plain text — all in the repository, versioned alongside the code. No Enterprise Architect licences. No PlantUML servers. No Confluence pages where documentation goes to die quietly.

> "If it's not in the repo, it doesn't exist. If it can't be versioned and read by an AI agent, it will rot."

He had been applying this approach on Robocode Tank Royale for over three years before writing about it publicly. He chose to publish rather than document internally because Confluence is where documentation goes to die — writing for everyone forces the thinking to be real.

The philosophy is documented in his [Plain Text as Code repository](https://github.com/Plain-Text-as-Code) and demonstrated in his [Architecture as Code example repository](https://github.com/flemming-n-larsen/architecture-as-code-example). He writes about it on his blog: [Architecture as Code](https://architecture-as-code.hashnode.dev/).

### Agentic Engineering

When agentic AI tools arrived on the desktop — with file access, CLI integration, and the ability to act rather than just respond — something shifted. After 40 years of programming, Flemming found he no longer had to write the code himself. The AI can do that. What it cannot do is architecture, data modelling, system design, or the judgement that comes from understanding a domain. That is where he works now.

This is not a retreat from engineering. It is a return to what engineering is actually for.

His position on how to work with AI is deliberate and opinionated. Spec-Driven Development is the foundation: write the specification first — the what, the why, the acceptance criteria — before any implementation begins. The AI then works from that spec as a precise, reviewable contract. Human in the loop is not optional. Architecture, intent, and accountability remain with the engineer.

This is the opposite of vibe coding. Vibe coding — prompting and iterating by intuition — has its place: quick prototypes, mock-ups, throwaway experiments. It has no place in production-grade software. The distinction matters, and he makes it explicitly.

> "Software development hasn't fundamentally changed — developers have simply stopped writing production code."

Steering an AI agent effectively requires more than a prompt. It requires being explicit about what you value. That is the idea behind [.principles](https://github.com/.principles) — a catalogue of 375 software engineering principles, organised as plain-text `.principles` files that tell an AI agent which subset of established practices matters in your specific context.

> "The AI already knows everything. The question is: does it know what you care about?"

### How He Works

There is a consistent thread running from a ten-year-old extending his teacher's Turtle program without permission, to stepping up when Robocode was abandoned, to spending twelve years rebuilding a game engine from scratch because the architecture was wrong: Flemming does not accept the status quo when he can see a better way. He will go far to remove whatever stands in the way of working faster, more freely, and more effectively.

This applies to code, to tools, and to process. If requirements come from above, he will counter-demand that the process be lean and that it actually deliver value. Bureaucracy for its own sake — governance rules that exist to satisfy a checklist rather than solve a real problem — he has no patience for. DRY. KISS. Small is better. If it does not contribute value, cut it.

He is a genuine believer in Open Source — not as a career signal, but as a conviction. Code should be open.

He has been a recreational runner since 2012, typically running several times a week. It is not just exercise. Running is where he thinks, reflects, and gets his best ideas — the kind of uninterrupted headspace that the day job rarely allows. He lives in a small city near Aalborg in Northern Jutland, Denmark, with his partner. He is a father of four.

---

*Links:*
- [Plain Text as Code](https://github.com/Plain-Text-as-Code)
- [.principles](https://github.com/.principles)
- [Architecture as Code example](https://github.com/flemming-n-larsen/architecture-as-code-example)
- [Architecture as Code blog](https://architecture-as-code.hashnode.dev/)
- [Robocode Tank Royale](https://github.com/robocode-dev/tank-royale)
- [Book of Robocode](https://book.robocode.dev/)
