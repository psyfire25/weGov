# The weGov Manifesto

*Draft 0.1. This is a living document, and it will be amended by the process it describes.*

---

## Preamble

*Demokratia*: power (*kratos*) held by the people (*demos*).

Athens had the right idea and applied it badly. Its assembly was open to every citizen, but most people were not counted as citizens. Women, enslaved people, foreigners and the poor were all left out. Every democracy since then has repeated that pattern in some form. The promise is made to everyone and kept for a few.

Today most of humanity is governed but does not govern. Decisions about their water, land, schools, wages and futures are made far away, by people they did not choose, often for interests they do not share. Money speaks louder than votes. Distance, language, literacy and poverty decide who gets heard.

We believe this can change, and that the tools to change it already exist. A person with a basic phone can now take part in decisions as easily as a person in a parliament building. What is missing is not technology. It is a commons: shared, open infrastructure for self-government that no company, state or individual owns.

**weGov is that commons.** This manifesto sets out what we believe and what we commit to building.

---

## Part I: Principles

### 1. Every person has an equal voice, in every decision

One person, one voice, regardless of wealth, gender, race, caste, religion, nationality, disability, literacy or location. Voice cannot be bought, sold, inherited or concentrated. No feature, fee or algorithm may make one person's participation count for more than another's.

**Every person can take part in every decision that affects them, at every layer, from their street to the whole world.** Nobody needs permission. No delegate, assembly or institution can close the door. Each person chooses how involved they want to be: to vote on everything, to follow only what matters to them, or to trust someone else on a topic. That choice is theirs alone, and they can change it at any time. The chance to have your say is never taken away.

### 2. People before profit

weGov exists to serve people, not to extract value from them. It will never sell attention, data or influence. It will never run advertising. It will never be optimised for engagement at the cost of wellbeing or truth. Where money is needed, it is raised openly and accounted for publicly.

### 3. Access is a right, not a feature

A democracy that only works for the connected, the literate and the comfortable is not a democracy. weGov must work for the poorest person on Earth: on a basic phone, by SMS or voice, offline, in their own language, whether or not they can read. If a design choice excludes the least advantaged, it is the wrong choice.

### 4. Power flows from the bottom up

Decisions should be made as close as possible to the people they affect. A village decides village matters. A city decides city matters. Wider questions belong to wider circles. This principle is called *subsidiarity*.

weGov is built in five nested layers: **individual, local, regional, national and global**. All power starts with the individual. Each higher layer holds only the powers the layers below have chosen to grant it, and those powers can be taken back. Higher layers exist to serve the communities that form them, not to rule over them. The rights in Principle 6 apply at every layer. See [The Layers of weGov](docs/layers.md).

### 5. No centre, no owner, no single point of failure

weGov is open source and decentralised. No company, government or founder controls it, and that includes us. Any community can run its own instance, change it and connect it to others. If the original project disappears, the platform lives on.

### 6. Rights that no majority can vote away

Majority rule is a tool, not a god. Some things are not up for a vote: the dignity of every person, freedom of conscience and expression, protection from violence, and the right to take part in every decision at every layer. Minorities must be protected from majorities, and the future must be protected from the present.

### 7. Deliberation before decision

Good decisions come from understanding, not just counting. weGov puts listening, discussion, evidence and compromise ahead of the vote. The aim is not to win arguments but to find what a community can genuinely live with.

### 8. Open in public, private in the ballot

How decisions are made, who proposed what, how money is spent and how the software works must all be open to everyone. How an individual votes must be secret, so that nobody can be coerced, bribed or punished for their choice.

### 9. Power is borrowed, never owned

Anyone given authority, whether a delegate, coordinator, moderator or maintainer, holds it on behalf of the community, for a limited time, and can be recalled. Roles rotate. Records are kept. Nobody is above the rules they help make.

### 10. Education is the foundation of self-government

People can only govern well if they understand what they are deciding. weGov treats civic education, clear information and the ability to question sources as core infrastructure, not an add-on. Every proposal should be explainable in plain language.

### 11. Shared infrastructure for shared needs

Clean water, food, shelter, health, energy, education and connectivity are the ground that human freedom stands on. Communities have the right to decide together how these are provided, maintained and shared, and weGov exists partly to make that possible.

### 12. Responsibility to the Earth and to those not yet born

We govern on behalf of future generations who cannot vote today, and of a planet we share with all life. Long-term consequences must be visible in every decision.

### 13. Peaceful by design

weGov is a tool for nonviolent self-organisation. It does not exist to overthrow anyone. It exists to show, in practice, that people can govern themselves fairly. It will not be used to organise harm against any person or group.

---

## Part II: What we commit to build

The principles above are only worth something if the software follows them. These are our design commitments. Every feature will be judged against them.

| Principle | Commitment |
|---|---|
| Every voice, every decision | **Every decision at every layer is open** for anyone it affects to see, discuss, propose changes to and vote on. People choose their own level of involvement and are told about what affects them in plain language, on any phone. |
| Equal voice | Identity built on **one person, one account** without needing a passport or bank account. Community vouching, local verification and privacy-preserving proofs, never surveillance. |
| Access | **Low-bandwidth first.** SMS, USSD and voice (IVR) interfaces alongside web and mobile. Works offline and syncs later. Multilingual from day one, with audio and pictographic options. |
| No centre | **Federated architecture.** Communities run their own nodes, which connect to others through open protocols. Data belongs to the community that produced it. |
| Open & private | **Auditable, secret ballots.** Anyone can verify the count, but nobody can learn how an individual voted. All code is public, with reproducible builds. |
| Deliberation | **Structured discussion tools** that bring out common ground instead of rewarding outrage. Plain-language summaries of every proposal. Time to reflect before voting. |
| Bottom-up | **[Five nested layers](docs/layers.md):** individual, local, regional, national and global, plus issue-based communities that cut across them. Power is granted upward by consent and can be revoked. Safeguards grow stronger the higher the layer. |
| Power is borrowed | **Rotation, term limits and recall** built into every role. Optional delegation of a vote that can be taken back at any time. |
| People before profit | **No ads, no tracking, no data sales.** Funded openly through donations, grants and voluntary community contributions, with public accounts. |
| Education | **Built-in learning.** Explainers, source-checking and civic skills, available to everyone and in every language. |

---

## Part III: Hard questions we will not hide from

We do not have all the answers. Honesty about what is difficult is part of the commitment.

- **Identity without control.** How do we make sure each person has exactly one voice without building a surveillance system or excluding people who have no official papers?
- **Coercion.** How do we protect voters whose phone is shared, watched or taken from them by family, employers or armed groups?
- **The digital divide.** Some people have no phone and no signal. How do offline and in-person participation stay first-class?
- **Legitimacy.** How do decisions made on weGov relate to existing laws and governments? Where do they carry weight, and how is that earned?
- **Manipulation.** How do we resist disinformation, fake accounts, vote buying and capture by well-organised minorities?
- **Scale.** How does deliberation that works for fifty people work for fifty million?

- **Layers.** How are regions and nations formed, how far can votes be delegated, and how does weGov relate to existing states?

These are tracked openly in the [Open Questions register](docs/open-questions.md) and worked on together. Anyone can contribute an answer, or challenge the question itself.

---

## Part IV: How this manifesto changes

This manifesto belongs to everyone who takes part in weGov. Until the platform can govern itself, changes are proposed openly as pull requests and discussed in public. Once weGov is running, the manifesto will be amended through weGov itself, and the project will be the first community to govern itself with its own tool.

The principles in Part I, Section 6 (rights no majority can vote away) can be strengthened by amendment but never weakened.

---

## Join us

If you believe that every person deserves a say in the decisions that shape their life, this is your project. Read it, question it, translate it, improve it, build it. [Start here](CONTRIBUTING.md).

**We, the people. All of us, this time.**
