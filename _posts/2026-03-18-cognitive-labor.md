---
title: "The Displacement of Cognitive Labor and What Comes After"
date: 2026-03-18T00:00:00-07:00
categories:
  - blog
tags:
  - AI
---

# The Displacement of Cognitive Labor and What Comes After

## I. The Threshold Has Been Crossed

We are past the point where the question is whether artificial intelligence will exceed human capability across most cognitive domains. It already has. The remaining question is not *if* but *when* the full implications arrive, and the "when" is measured in months and years, not decades.

I want to start with personal experience, because the abstract version of this argument is less convincing than what it feels like to live through the shift.

I graduated in the top five of my class at Stanford. My entire identity, for most of my life, has been built on intelligence: the ability to reason through complex problems, to synthesize information, to produce meaningful work. That identity is now obsolete in the way I previously understood it.

Here is what that looks like in practice. The concrete productivity shift is staggering. In the past week alone, I have on five separate occasions produced output that I would have previously estimated at four weeks of hands-on engineering work. Each took roughly 45 minutes with a single well-crafted, well-directed prompt in Claude Code. So long as I can frame what I want clearly, the tool handles the rest, with the exception of edge cases where the system's output meets reality and needs manual adjustment. That ratio (four weeks to 45 minutes) is not a marginal improvement. It's a change in kind.

But the shift goes beyond raw productivity. On a daily basis, when I have a question or thought I want to explore, my first reaction is to go to an AI tool instead of talking to another person. This is a fundamental shift from before, where I would tend to brainstorm with human partners before AI partners. I now use AI as my primary partner for emotional reasoning, intellectual exploration, and strategic thinking. The places where I still go to humans are specific and narrow: I talk to my co-founder or my coach, because they will sometimes surface a way of thinking about a problem that's different from how I'm approaching it, without me having to ask.

It also changes how I reason, write, and construct arguments. This essay is an example. It was produced through an eight-hour conversation between me and Claude, where I used Wispr Flow to dump my thoughts for five minutes at a time, learned from how Claude critiqued them, poked holes in Claude's arguments, and went back and forth. This is draft 41. The AI didn't hand me a polished essay. What actually happened was a process of iterative refinement: I'd voice a rough idea, Claude would push back on the weak parts, I'd disagree with some of its pushback and accept other parts, and each cycle produced a tighter version of the argument. It took those eight hours for me to realize all the ways in which my initial framing was wrong and to arrive at a significantly more rigorous understanding of what I'd been thinking. That kind of interaction was not possible until very recently.

This is a remarkable change. I now view my intelligence as a commodity on tap. The primary skills I have left are my ability to synthesize different AI-generated perspectives into a combined whole that's better than what the AI produces on its own, my ability to judge what I like and don't like, and my ability to identify what I care about. Taste, direction, synthesis. Not raw cognitive horsepower. For someone whose whole identity was predicated on that horsepower, this is a significant transformation, and it's one that millions of knowledge workers will go through in the next few years whether they're ready for it or not.

{% include figure image_path="/assets/images/ai-abundance/intelligence2.png" alt="Wait But Why's AI Intelligence over Time chart." caption="Tim Urban drew this in 2015. We're somewhere just short of Einstein now. What happens when we move slightly to the right in four to eight weeks?" %}


## II. Harnessing Intelligence and the Impacts on Labor

For years, the open question in AI was whether scaling laws would hold: whether you could keep increasing compute, data, and parameters and keep getting predictable improvements in intelligence. That question is settled. The scaling laws held out long enough. The raw capability is here.

But raw capability is not the same as structured impact. AI today is roughly where human intelligence would be without the organizational structures we've built to harness it. A brilliant individual can do remarkable things. A brilliant individual leading a well-designed corporation, with teams and hierarchies and processes, can reshape an industry. AI has the brilliance. What it's still developing is the organizational scaffolding. And because what remains is an engineering problem (how to harness, structure, and deploy intelligence effectively) rather than a research problem (whether the intelligence will materialize at all), the timeline is a matter of execution speed, not scientific discovery.

That scaffolding is arriving fast. The inflection point, for me, was watching Claude Code begin to orchestrate sub-agents effectively: assembling teams of AI workers to tackle different dimensions of a complex task in parallel, then synthesizing the results. This is a direct analogue to how human organizations function. You break a problem into pieces, assign them to capable actors, and integrate their output. The fact that AI can now do this, imperfectly but recognizably, means the path to fully autonomous knowledge work is a matter of engineering iteration, not fundamental research. That mental model scales to arbitrary levels of abstraction: agents coordinating sub-agents coordinating sub-sub-agents, mirroring the way a CEO directs VPs who direct managers who direct individual contributors. The innovation of making this work fluidly at scale hasn't fully arrived, but it's very clear that it will.

{% include figure image_path="/assets/images/ai-abundance/org_vs_agent_hierarchy_v2.svg" alt="Parallel structures: human org chart and AI agent hierarchy." caption="Same organizational logic, different substrate." %}

The other recent shift is the emergence of working computer-use agents. Perplexity's computer-use tool more or less works: an AI system that can operate a computer the way a human does, launching applications, interpreting visual output, navigating interfaces, and iterating based on results. This closes a critical gap. Previously, AI could think but couldn't act in digital environments without human intermediation. That barrier is falling.

Consider a concrete example. Say you need to hire Android engineers. Previously, you'd delegate to a recruiter or spend days doing it yourself: researching which companies have strong Android teams, finding individual engineers, compiling contact information, writing personalized outreach, sending connection requests one by one. A computer-use agent can do all of this autonomously. It compiles a list of the 20 most prominent Android companies, searches LinkedIn for the top engineers at each, puts them into a tabulated spreadsheet, drafts a personalized outbound message to each person, and controls LinkedIn to actually send those messages as connection requests. That's not a chat interaction. It's an agent operating a computer the way a human recruiter would, except it takes minutes instead of days. This is the kind of task that doesn't get solved by talking to an AI in a text box. It gets solved by AI being able to use the same tools we use, in the same environments we use them. The ingredients for full automation of knowledge work are now all present.

It helps to think about human labor as falling into two broad categories. The first is cognitive labor: knowledge work and emotional work. Analysis, writing, coding, design, legal reasoning, financial modeling, medical diagnosis, therapy, coaching, project management. This is the category being automated right now. The second is physical labor: construction, manufacturing, agriculture, logistics, plumbing, electrical work, maintenance. This requires robotics and physical automation, which follows a different timeline.


## III. Physical Intelligence: What Is to Come

People often joke that you can't use nine people to make a baby in one month. The implied lesson is that some things are irreducibly serial and can't be parallelized. This is true, but it misses what AI actually changes about physical automation timelines.

The bottleneck in developing robotics and physical intelligence has always been the cognitive labor of R&D: designing systems, running experiments, analyzing results, iterating on designs. That cognitive labor is precisely what's being automated now. When AI can run massively parallel experimentation strategies for robotics development, the limiting factor is no longer human researchers working sequentially. The limiting factor becomes the physical production cycle itself: building prototypes, testing them in the real world, observing how they break. You still can't skip the serial contact with physical reality, but you can compress everything around it.

This is a fundamental shift. Development cycles that previously took months of human cognitive work sandwiched between physical tests now take days of AI cognitive work sandwiched between the same physical tests. The serial part (physical production and testing) stays the same length, but the parallel part (design, analysis, iteration) compresses by an order of magnitude or more. And if design and testing become nearly free, you get to test many designs in parallel, limited only by budget for physical prototypes rather than by human cognitive bandwidth. The result is that improvements in robotics and physical autonomy will arrive far faster than most people's intuitions predict.

Robotics today is already decent, and the compounding dynamic is powerful. Every advance in AI capability accelerates every subsequent advance, including in the physical domain. If cognitive labor automation is largely complete within three to five years, and that compressed R&D cycle is applied to robotics, physical labor automation could follow within five to ten years rather than the twenty or thirty that a linear extrapolation would suggest.

This matters enormously for the transition. If physical labor automation arrives on a ten-year timeline, it means we cannot treat physical labor as a permanent refuge for displaced knowledge workers. Unlike the Industrial Revolution, where one type of human labor (manual agricultural work) was replaced but another type (factory and later knowledge work) grew to absorb the displaced population, this transition has no obvious next category of labor for humans to move into. All three categories (knowledge work, emotional work, physical work) are converging toward automation within a single generation.

{% include figure image_path="/assets/images/ai-abundance/labor_automation_timeline_v4.svg" alt="Labor displacement curves showing knowledge and emotional work automated before physical work." caption="The gap between cognitive automation and physical automation is the acute transition period." %}


## IV. Abundance and Continued Scarcity

Not everything becomes abundant in the same way or on the same timeline, and the split between what does and what doesn't is one of the most important features of the post-economic world to understand clearly.

A lot of people in Silicon Valley are assuming that everything will become abundant. Elon Musk talks about "universal high income" as though the problem is simply distributing the surplus. But that framing obscures a critical distinction: some things will approach zero marginal cost, and some things will not. Figuring out how to manage a world where some goods are effectively free and others remain scarce (or become more valuable) is one of the defining challenges ahead.

**Things that will become radically abundant** (approaching zero or very low marginal cost):

- Information synthesis, analysis, and generation. Any question you can ask will have a better answer than any individual human expert could provide, instantly, for free.
- Legal document drafting, contract review, and regulatory compliance. The entire apparatus of routine legal work becomes automated.
- Software generation for standard applications. Custom software becomes as cheap as asking for it.
- Translation and transcription, in real-time, across any language pair.
- Basic medical diagnosis and triage. AI systems that outperform most human diagnosticians, available to everyone.
- Financial modeling, analysis, and planning. Personalized financial advice that today costs thousands of dollars per hour becomes free.
- Education content and tutoring. Personalized instruction tailored to each learner's pace, style, and level, infinitely patient, available 24/7.
- Design variations and iteration. Producing a hundred design options becomes as easy as producing one.
- Customer support and routine communication. Any interaction that follows patterns gets handled by AI.
- Physical goods produced by automated systems. Once robotics matures, manufactured goods, constructed buildings, and produced food approach the same zero-marginal-cost dynamic that digital goods reach first.

All of these currently require paying enormous amounts: a lawyer charges hundreds per hour, a software engineer costs $150,000+ per year, a financial advisor takes a percentage of your assets. The cost of equivalently intelligent AI models is dropping rapidly. Even at today's prices, AI is far cheaper than paying a human for the same cognitive output. As costs continue to fall, these services will become truly abundant.

**Things that will NOT become abundant** (and may become more valuable):

- Physical presence and embodied experience. Your Taylor Swift concert. The feeling of being in a specific place at a specific time with other humans.
- Physical scarcity. Land, nature, raw materials, pristine environments. There is one beachfront lot in that spot, and no amount of AI changes that.
- Health and physical excellence. Athletic achievement, physical skill, the experience of a body that works well. These require a human body and can't be outsourced.
- Craft and artisanal production. The "human-made" premium. A hand-carved table carries value precisely because a human made it and you know that. Homemade baked goods carry value precisely because you made them yourself.
- Taste, curation, and judgment. Knowing what to ask for, knowing what's good, having an opinion that's genuinely yours.
- Social proof and status signaling. Being known, being vetted, having a reputation that other humans vouch for.
- Novel lived experience. Travel, adventure, relationships. The things that require you to actually be present in your life.
- Spiritual and contemplative goods. Retreat experiences, contemplative communities, the fruits of sustained practice.
- Community and belonging. Clubs, movements, shared purpose. The experience of being part of something with other people.
- Political representation and advocacy. Someone fighting for your interests, accountable to you.
- Risk-bearing and skin-in-the-game decisions. The person who signs the liability waiver. The human who takes responsibility when things go wrong.

Economics doesn't break down. But a good chunk of capitalism might. Capitalism operates on the basis of prices aggregating information to coordinate production and consumption. When the cost of producing many goods and services approaches zero, that price mechanism stops functioning for those goods. There's no price signal to send when the marginal cost of one more unit of legal advice, or software, or medical diagnosis is effectively nothing. It's an open question which parts of capitalism break down and which adapt.

Consider how we already handle this for air. We think of air as free, but the Clean Air Act created a market by placing a high price on pollution, and people pay a premium to live in places with cleaner air. There is an economy around air; it just looks nothing like the economy for scarce goods. As cognitive goods and services approach zero marginal cost, our economic systems will need to adapt in similar ways, developing new frameworks that look as different from today's markets as emissions trading looks from buying groceries. The transition we're heading into is the process of moving everything in the first list from "scarce" toward something closer to "air," while the second list remains the terrain where competition, allocation, and human striving still live. What's clear is that the frameworks we have today were not designed for a world where scarcity applies to far fewer things than before, and in different ways. The implications of this shift will be one of the most complex questions of the coming decades.


## V. The Transition

The endpoint of abundance may be desirable, at least to many people born into it. The transition to it will likely be the most turbulent period in modern history, not because of AI catastrophe, but because of the speed at which existing social and economic structures will be disrupted.

### The Knowledge Work Cliff

The first and most immediate disruption is the automation of knowledge work. Within three to five years, the majority of cognitive jobs will be substantially automated. This doesn't mean every knowledge worker loses their job overnight. It means the number of humans needed to produce a given unit of cognitive output drops by an order of magnitude. One person with AI does what twenty did before. The math is simple: most knowledge workers become redundant.

This hits the upper-middle class hardest, which is counterintuitive. The truly wealthy have diversified assets and capital reserves. Working-class people doing physical labor still have scarce skills. It's the $80,000-to-$400,000 household (the lawyer, the software engineer, the financial analyst, the radiologist) that gets caught. Their skills are the most directly substitutable by AI, and their lifestyle is built on continuous high income rather than accumulated capital. They lose their income, and the value of their primary asset (typically a home in an expensive knowledge-work city) declines as demand in those cities contracts.

The instinctive policy response is retraining: move displaced knowledge workers into physical labor, which still requires humans. This mostly won't work. There won't suddenly be demand for twice the number of people in physical labor industries just because half of knowledge work is eliminated. The skills gap takes years to close. And as I argued in the previous section, physical labor is also on the path to automation, just on a delayed timeline. There is no permanent refuge.

### Identity, Not Just Income

The economic disruption is severe, but the identity crisis may be worse. We have a direct historical parallel: the deindustrialization of the American Rust Belt.

When manufacturing left cities like Detroit, Youngstown, and Flint, the economic damage was obvious. But the deeper wound was to identity. These were communities where being a steelworker or autoworker wasn't just a job; it was who you were. It defined your family's place in the social order, your sense of contribution, your self-respect. As Case and Deaton wrote in *Deaths of Despair*: "Jobs are not just the source of money; they are the basis for the rituals, customs, and routines of working-class life. Destroy work and, in the end, working-class life cannot survive." The loss of that identity, even more than the loss of income, drove the epidemic of depression, substance abuse, and what they termed "deaths of despair."

The coming displacement of knowledge workers has the potential to be that dynamic at a much larger scale. A software engineer's identity is as tied to their cognitive ability as a steelworker's was to their trade. "I'm smart, I solve hard problems, I build things" is not just a job description. It's a self-concept. When AI can solve harder problems and build things faster, that self-concept shatters.

By default, I suspect that mass unemployment of knowledge workers, simultaneous with the dissolution of a core part of their identity, will lead to widespread depression and despair.

### Political Stability

I want to be clear that what follows is speculative. Nobody knows exactly how this plays out politically. But the historical patterns are concerning enough to take seriously.

Rapid displacement of economically powerful classes has historically been destabilizing. The French Revolution wasn't driven by the poorest; it was driven by the bourgeoisie who felt their status didn't match their economic reality. The Arab Spring was fueled in large part by highly educated young people who had invested in university education and found themselves with no economic opportunity. In Jordan, 53% of unemployed youth held university degrees. Across the region, the message had been: get educated, and opportunity will follow. When that promise proved hollow, the sense of betrayal was more radicalizing than poverty alone.

The parallels to a potential mass displacement of knowledge workers are hard to ignore. These are the most educated, most politically engaged, most socially connected demographic in society. Many have taken on significant student debt for degrees that promised professional careers. If those careers evaporate, the combination of economic loss, identity dissolution, and a sense of having been deceived by the institutions they trusted could be a potent formula for instability. Whether that instability takes the form of productive political organizing or something more destructive is genuinely uncertain.

The AI infrastructure companies are likely candidates for some redistribution during this period, driven more by self-interest than altruism. They need a functioning society to operate in, and the most likely form this takes is making AI services extremely cheap or free, which reduces the cost of living even as incomes fall. But this creates its own uncomfortable dynamic: a large population dependent on the goodwill of a handful of companies, without democratic accountability or structural guarantees.

### Governance and Geopolitics During the Transition

These next points are also speculative, but they follow logically from the dynamics above.

AI makes produced goods abundant, but land, location, and certain physical resources remain zero-sum. The property rights and governance frameworks we have today were built for a world of broad scarcity. When scarcity narrows to a small set of rivalrous assets, the rules for who gets what and how those decisions are made will need to be fundamentally reimagined. What does property ownership mean when construction is free but location is priceless? How do you govern land use when the economic logic that previously drove zoning and development no longer applies? I don't have confident answers here, and I'm not sure anyone does yet.

Similarly, if the United States, or more precisely a handful of US-based companies, achieves something approaching post-economic abundance domestically while the rest of the world does not, the resulting asymmetry could be the largest in human history. Not inequality of wealth, but inequality of productive capacity itself. The frameworks we use to understand international relations are built on economic interdependence, scarcity, and trade. What happens to those frameworks when some nations no longer need others for production is genuinely unclear. It could lead to a more stable world (abundant nations have less reason for conflict) or a far less stable one (nations facing permanent irrelevance don't accept it quietly). The range of outcomes is wide, and I suspect the specifics will depend heavily on decisions made in the next decade.


## VI. Post-Abundance: Human Nature Doesn't Change

It's important to separate the challenges of the transition from the challenges of what comes after. The transition is about displacement: jobs disappearing, identities breaking, institutions failing to keep pace. The post-abundance world is a different problem entirely. It's about fundamental human nature meeting a set of conditions that human nature has never encountered before.

The technology changes. Human nature does not. The drives that define us (status-seeking, hierarchy, competition, the desire to be valued relative to others) are not products of capitalism or knowledge work. They predate both. These dynamics existed before knowledge work was important to society, and they will continue after knowledge work is automated. What changes is the terrain on which these drives play out, and the social contracts that channel them.

### For Those Not Yet Born

There is an important asymmetry between people alive today and those who will be born into a post-economic world. For today's adults, the transition involves a painful identity transformation: letting go of professional identity, status hierarchies, and assumptions about what constitutes a valuable life.

For children born into this world, abundance will simply be the water they swim in. We may be the last generation that has to work for a living. Our children will likely grow up in a world where having a career is a choice, not a necessity. They won't experience abundance as remarkable any more than we experience indoor plumbing as miraculous (and it's worth remembering that in 1940, 45% of American homes still lacked indoor plumbing; within living memory, this was a luxury, not a given). Their sense of identity and status will not be anchored to career or professional accomplishment, because those concepts will carry no more weight than "being good at churning butter" carries for us today. These attachments never form in the first place. Their developmental challenges will be different. Not the grief of losing a role, but the challenge of constructing meaning without the scaffolding of material necessity.

When people raise this concern, a common response is that humans fundamentally need work for meaning, and that a world without work is therefore a world without meaning. I think this claim is weaker than people realize. It's really a claim about a specific cultural arrangement (Protestant work ethic, American meritocratic ideology) rather than a deep truth about human nature. Stay-at-home parents find deep meaning in raising children. Retirees find it in gardening, volunteering, grandchildren. Religious contemplatives find it in practice and community. Many cultures, particularly in Southern Europe and the non-Western world, have never placed work at the center of identity the way American culture has.

What people actually seem to need is not work specifically but four things that work happens to provide: agency (the sense that you're making choices that matter), contribution (the sense that you're valued by others), mastery (the sense that you're getting better at something), and connection (belonging to something larger than yourself). Work can provide all four, but it's not the only thing that can. The challenge is building new structures that provide these when work no longer does.

Gen Z is an interesting case here. A generation that already doesn't derive primary identity from work is in some ways better positioned for this transition. But they're also potentially worse off, because the existing social infrastructure (healthcare tied to employment, housing tied to income, social status tied to job title) hasn't caught up to their values.

### Status and Competition After Work

Human status-seeking doesn't disappear when material needs are met. It redirects. In a world where AI can produce any material good, conspicuous consumption becomes meaningless as a status signal. So status migrates to whatever remains scarce: physical excellence, social and relational capital, creative originality, governance influence, spiritual attainment. The likely candidates map closely to the "things that will not become abundant" list from Section IV.

Which of these dominate matters enormously. The pessimistic outcome is that status collapses into the most visible and competitive dimensions: physical appearance, social following, zero-sum games. The optimistic outcome is a restructuring around depth: wisdom, psychological development, quality of relationships, contribution to community. The mechanisms change. The underlying drive doesn't.

The social contract of our society for how we channel these drives will have to be fundamentally reimagined. The current contract says: compete through economic productivity, and status follows. That contract breaks when economic productivity is automated. The replacement contract doesn't exist yet, and building it is one of the central challenges of the post-abundance world.


## VII. Open Questions

The trajectory I've described raises a set of questions that I don't think anyone currently has good answers to. I'm going to explore these in future essays, but I want to name them here because I think they're the most important questions of the next two decades. If you've thought deeply about any of these and believe you have a path forward, I'd like to hear from you.

**On the transition:**

- What happens to the displaced class of knowledge workers? Not in the abstract, but concretely: how do tens of millions of highly educated, previously high-status people navigate the simultaneous loss of income, identity, and social position?
- What are the social and political implications of this displacement? Is the default path one that leads to unionization, uprising, revolution, or something else?
- Could these dynamics lead to targeted violence against AI companies and AI infrastructure?
- Could they lead to actual political revolution or regime change?
- How might we politically manage this transition period to allow for stability? What institutions, policies, or agreements could prevent the displacement from becoming destabilizing?
- By default, I suspect that mass unemployment of knowledge workers, simultaneous with the dissolution of a core part of their identity, will lead to widespread depression and despair. How do we handle that at scale?
- What are the geopolitical implications of one or two nations developing this technology before other nations? What happens to the international order when economic interdependence dissolves?

**On post-abundance:**

- Is the default path for large groups of people to end up in something like Brave New World or Ready Player One: a society optimized for comfort and stimulation rather than growth and meaning? Is there a way to avoid that default path?
- How do we preserve and create a world with human flourishing where labor is largely displaced?
- How does governance and economics work when some things are scarce and other things are not? What property rights frameworks make sense in a world where production is free but location is priceless?

These are not rhetorical questions. They are the defining challenges of the next generation, and the window to shape the answers is now.

---

*Acknowledgements: I want to thank my friend and colleague Michael Hochberg, who was instrumental in crafting this essay by pushing back on many arguments I had absorbed from the closed Silicon Valley dialogue that can be a self-reinforcing bubble. His [article on the AI Gründerzeit](https://longwalls.substack.com/p/the-ai-grunderzeit) is an excellent perspective worth reading.*
