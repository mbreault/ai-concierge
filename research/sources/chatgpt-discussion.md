# AI Concierge Research — retrieved discussion

Source: [AI Concierge Research](https://chatgpt.com/c/6aa7fce5-659c-83ea-9499-3fff6722ae42). Archived 2026-09-14.

This is a chronological archive of all six turns exposed by the conversation retrieval tool; message wording is unchanged, with editorial headings added. The original ChatGPT deep-research response is not present in the retrieved history. Later replies refer to that research, but those references are not a substitute for the missing report. Attachment notices and ChatGPT citation tokens are retained verbatim; see the [source index](../source-index.md) for the recovered attachments. These are brainstorming messages and model recommendations, not automatically approved decisions.

## Turn 1

Conversation turn ID: `2126787d-c5ed-4592-910d-66ef4a545b7c`

### User

@Deep research I have 30 years experience as a self-employed consultant and software developer.  I want to pivot into AI consulting.  Attached is the offering sheet I’m working on.  This is a rough draft.  I want research on what other “AI Concierge” services are offered, including their pricing, support SLAs, etc.  Please suggest ideas based on your research.

[User attached 1 file; file contents were not included]

## Turn 2

Conversation turn ID: `7ca9bf4e-d94f-400f-af28-7382c97fd954`

### User

this is what gemini produced from the same prompt. how does your plan compare?  the main takeaways from gemini were raise entry level prices and drop the hardware entirely.

[User attached 1 file; file contents were not included]

### ChatGPT

Yeah — Gemini and my research landed in almost the same neighborhood on the big economic issue: your draft is pricing a 30-year senior software consultant like an entry-level AI coach. The main disagreement is the Raspberry Pi / physical “Chief of Staff” idea.

Gemini’s core prescription is pretty aggressive: kill the $100/$200 entry products, replace them with roughly a $950 diagnostic, raise integrations to ~$4,500+, raise Copilot work to $7,500–$12,500, split advisory from managed engineering, and remove the physical kiosk entirely. fileciteturn1file0L65-L72 Its proposed ladder ends up at $950 diagnostics, $3,500–$12,500 workshops, $4,500–$15,000+ builds, and $1,500–$12,500/month retainers. fileciteturn1file0L174-L183

My research agrees with about 80–90% of that, but I’d make a few important adjustments:

| Issue | Gemini | My recommendation | Where I land now |
|---|---|---|---|
| $100 assessment | Eliminate it | Raise to $250–$350 or keep $100 purely as a lead-gen qualifier | **Raise it**, but I wouldn't jump straight to $950 as your only door in |
| $200 tools session | Eliminate / roll upward | $600–$950 working session | **Definitely raise it** |
| Missing diagnostic | $950 AI Opportunity & Systems Audit | $1,500–$2,500 Opportunity Diagnostic | **I prefer $1,500–$2,500** once you've got a few AI cases |
| $15K workshop | Split into $3.5K team / $10–12.5K executive | Split into ~$5–10K team / $12.5–15K executive | **Same concept; Gemini is a little cheaper** |
| $500 model connection | ~$4,500 | ~$1,500–$3,000 floor | **Gemini may be closer for real production integration; $1.5K only for something tiny** |
| $5K Copilot agent | $7.5–12.5K | $5–12K | **$7.5K starting price feels better** |
| $200/hr custom dev | $250/hr | $275–$325/hr internally; fixed-price externally | **I'd still go higher than Gemini** |
| $1K/month advisory | $1.5K advisory | Keep $1K Office Hours, add $2.5K and $5K tiers | **I prefer the three-rung ladder** |
| Production support | $4.5–5.5K/mo | ~$5K managed ops | **Essentially identical** |
| Physical Chief of Staff | Kill it | Keep it as a differentiated premium option, priced much higher | **This is the real disagreement** |

The biggest thing Gemini got right is the signaling problem. The phrase in its report that matters is essentially: a $100 consultation tells the buyer what category you belong in before you've had a chance to demonstrate anything. It also correctly points out that calling two 45-minute calls for $1,000/month “Enterprise” is misleading—the underlying service is perfectly reasonable, but the name creates the wrong expectation. fileciteturn1file0L42-L46 fileciteturn1file0L60-L63

I would therefore change my original recommendation slightly after seeing Gemini's analysis: I’d be more aggressive about your entry pricing.

I think a very strong launch configuration is:

**AI Workflow Diagnostic — $750.** 60–90 minutes, one meaningful workflow, written recommendation afterward. Credit the $750 against a build started within 30 days.

That splits the difference beautifully. You're not asking a new market to hand you $2,000 before you have AI-specific case studies, but you're also not advertising “$100 AI guy.” Once you have three or four strong client results, move it to $1,250–$1,500.

Then I’d make the next step something like **AI Opportunity Sprint — $2,500–$5,000**, where you actually interview multiple people, examine systems/data, quantify the workflow, and produce a build roadmap. That's the product both reports are circling around. Your original sheet jumps almost directly from talking to building. fileciteturn1file0L159-L171

On the hardware question, though, I'm not convinced Gemini is entirely right.

It's absolutely right about the operational risk. A Raspberry Pi sitting under someone's reception desk can become your problem because Karen unplugged it to charge her phone 😂. Wi-Fi, SD cards, OS patches, displays, USB peripherals, local networking, physical access—you can end up doing $300/hour engineering work while troubleshooting HDMI.

Gemini explicitly calls that out as margin-destroying support friction and recommends cloud/browser-native delivery instead. fileciteturn1file0L62-L71

But I think it's conflating two different questions:

**Should you become a hardware support company? Hell no.**

**Could a physical AI appliance be a fantastic sales object? Hell yes.**

That's why my recommendation was to retain the concept but radically change the commercial model.

Don't sell:

> Raspberry Pi AI Chief of Staff — $1,500 + $200/mo.

Sell something more like:

> **Executive AI Desk** — from $7,500 setup + $750/month.

And the actual hardware is incidental. Maybe it's a $600 mini PC, maybe an iPad on a stand, maybe a browser kiosk. The product is the configured AI environment, identity, integrations, company knowledge, secure access, monitoring, documentation and ongoing service.

Crucially: **hardware carries the manufacturer's warranty; onsite break/fix isn't included.** If the box dies, you replace/reimage it rather than diagnose a motherboard.

That turns the physical object from a liability into theater—in the good sense. A CEO can point to it and say, “That's our AI.” That's memorable as hell compared with the 900th consultancy selling an “AI Transformation Roadmap.”

I would, however, **remove it from the main offering sheet initially.** That's where Gemini changed my mind a little.

Launch the core business without it. Keep “Executive AI Desk / AI Chief of Staff” as a special offer or demo concept. If customers light up when they see it, productize it. If nobody cares, you haven't built yourself a tiny Geek Squad business. 🔥

There's another place where I think my research is stronger than Gemini's: **market evidence quality**. Gemini's report has some very useful thinking, but quite a few of its benchmarks come from consultant blogs, Reddit, podcasts, pricing-guide SEO pages and other secondary sources. Its Works Cited section makes that pretty apparent. fileciteturn1file0L209-L239 My research leaned much more heavily on actual published competitor price sheets: AgenTomte at $1,900 audit / $9,500+ build / $2,900 monthly fractional AI officer; Nova3 at $325/hr / $2,500+ monthly / $5K minimum build; Yotta at $8,500 assessment / $4,800 monthly; Intraeli at $1,200–$4,000 monthly; and several other firms.

And those primary-source comps are why I think the conclusion is actually stronger than Gemini makes it:

**You're not just a little underpriced. Certain parts of the sheet are an order of magnitude underpriced.**

The $500 + $100/month “model connection” is the biggest offender. Your original instinct was probably “this could take me a couple hours.” That's developer thinking.

The client isn't purchasing two hours.

They're purchasing:

**“Our company's system can now safely do something it couldn't do yesterday.”**

That's a $3K, $5K, $10K conversation depending on what you touched.

And this connects to what I think is the single best idea in Gemini's report: lean hard into the fact that you're an actual software engineer. It describes your advantage as bridging probabilistic AI systems with deterministic systems—databases, authentication, APIs, RBAC, logging, CI/CD, etc. fileciteturn1file0L125-L146

YES. 🚀

That's the positioning I would build the whole damn business around.

Not:

> “I'll teach your employees how to use ChatGPT.”

But:

> **“You've already got AI. I make it useful inside the systems your business actually runs on.”**

Your 30 years matters enormously there.

There are ten thousand newly minted “AI consultants” who can make Claude write a sales email. There are dramatically fewer people who can walk into a company, understand a crusty 17-year-old SQL application, figure out why operations still exports CSVs every afternoon, recognize the security implications, build the integration, and know which parts absolutely should *not* be handed to an LLM.

That's the moat.

So if I were making the call today, I'd combine the two reports:

**Diagnose → Align → Build → Operate**, exactly as Gemini suggests, but I'd retain your “Concierge” personality rather than becoming another dry “AI Systems Integration” shop. Gemini's proposed architecture is commercially sound. fileciteturn1file0L149-L183

And I'd launch approximately here:

| Offer | Launch price |
|---|---:|
| AI Workflow Diagnostic | **$750** |
| AI Opportunity Sprint | **$2,500–$5,000** |
| Team AI Lab | **$5,000** |
| Executive AI Opportunity Lab | **$12,500** |
| Production AI Integration | **from $4,500** |
| Copilot Studio Agent | **from $7,500** |
| Custom AI System | **from $10,000** |
| AI Office Hours | **$1,500/mo** |
| Fractional AI Advisor | **$3,000/mo** |
| Managed AI Systems | **$5,000+/mo** |
| Custom engineering fallback rate | **$300/hr** |

And **no $100/month production support anywhere.** That one needs to die with extreme prejudice. 😆

The very interesting next exercise is actually not more market research. It's taking your existing offering sheet and rewriting it around this combined model—**without making it sound like McKinsey wrote it.** Your original copy has a nice direct, blue-collar-engineer quality (“find the workflow that hurts…build the thing that runs it”). I'd preserve that voice while fixing the economics.

## Turn 3

Conversation turn ID: `dd6caf15-81c5-45b5-a93b-b4d9526495d1`

### User

ok yes thats good advice and makes sense. especially the hardware. a ton of liability.  it should be 10x more expensive than my weak price

### ChatGPT

Exactly. At $1,500 you’d basically be giving away a **custom physical AI appliance plus a support obligation**. That’s upside-down economics. 😄

If you keep the idea at all, I’d treat it as a premium, almost bespoke product:

**Executive AI Desk / AI Chief of Staff — from $15,000 setup + $1,500–$2,500/month.**

The $15K isn’t “for a Raspberry Pi.” It’s for the whole deployment: discovery, security design, company knowledge setup, identity/access, integrations, configuration, testing, installation, documentation, training, and getting something physical sitting in the executive’s office that actually works.

And I’d put some hard guardrails around it:

- Hardware is purchased by the client or billed separately at cost.
- Manufacturer warranty covers hardware failures.
- Your support covers **your software/configuration**, not Wi-Fi, monitors, routers, printers, power supplies, random USB devices, etc.
- Remote support only by default.
- Onsite service is separately billed — potentially **$2,500/day + travel**.
- If the device dies, you **replace/reimage it**, not spend six hours figuring out why GPIO pin 19 is unhappy.
- Third-party API/model outages are explicitly outside your SLA.
- New integrations or functionality are new work, not “support.”
- No 24/7 coverage unless somebody is paying an obscene amount for it.

And there’s a nice psychological effect here: **$15K actually makes the product make more sense.**

At $1,500, a CEO thinks, “Oh, some little computer with ChatGPT on it.”

At $15,000, the conversation becomes, “What exactly is this thing doing for my company?”

Which is the conversation you want.

You can answer:

> It knows your company’s approved information. It connects to your systems. It can prepare your morning briefing, answer operational questions, draft communications, monitor selected workflows, and surface things requiring your attention.

Now you're selling an **executive system**, not a gadget.

I’d also make it *scarce*. Don't put “Raspberry Pi” anywhere on the offering sheet. 😂 Call it something like **Executive AI Desk**, **AI Chief of Staff**, or **Private AI Office**, and say **“custom deployment — from $15,000.”**

And I still like our previous conclusion: **keep it off the main launch menu.** Build the boring, high-margin consulting engine first. Then have this thing sitting on your desk when you meet prospects. If they point at it and ask, “What the hell is that?” — *now* you have a $15K conversation. 🚀

## Turn 4

Conversation turn ID: `5f6afc31-b936-490a-86a9-21cc2c7c86ce`

### User

ok i asked Claude for his opinion, too.

[User attached 2 files; file contents were not included]

### ChatGPT

Claude’s version is the best of the three on research discipline. It’s much more careful about evidence quality, separates verified vendor pricing from weak SEO benchmarks, and it found a few market patterns neither Gemini nor I emphasized enough. fileciteturn2file0L3-L5

But I would **not adopt Claude’s proposed offering sheet wholesale**. There are several places where I think it gets too clever or too conservative.

The biggest thing Claude adds is the naming issue. Its research says “AI Concierge” is already strongly associated with hospitality/customer-service bots rather than human advisory work, and recommends using something like **“Find it. Build it. Run it.”** as the umbrella while keeping “Concierge” as a premium service tier. fileciteturn2file0L31-L55 I think that is an excellent catch. Your opening sentence is actually stronger branding than “AI Concierge” anyway.

Claude also makes a really compelling case for **paid discovery that produces an artifact**. It found a cluster around roughly $1,500–$2,500 for small-business/solo-provider assessments, with credible offers generally including a workflow map, prioritized opportunities, a 30/60/90 roadmap, and a live readout. fileciteturn2file0L93-L124

That pushes me farther toward Claude than where I was earlier.

I had suggested a $750 entry diagnostic. After reading this, I’d probably change that to:

**Free 20-minute fit call → $2,500 Workflow Audit**

That feels right.

And Claude’s mechanism is excellent:

**$2,500, credited 100% toward a build started within 90 days.**

That solves two problems simultaneously: it filters unserious prospects without making discovery feel like sunk money. Its draft makes that the centerpiece of the revised offer. fileciteturn2file1L17-L37

The **“10 recoverable hours/month or you don’t pay”** guarantee is also interesting. I wouldn’t necessarily put that into every engagement forever, but while you’re building your first AI-specific case studies it’s a strong risk reversal.

Where Claude is especially good is support. Its “Platform Adaptation” idea is probably the single most original insight in all three reports.

It separates:

**Fix:** your thing doesn’t work as specified.

**New work:** the client wants it to do something new.

**Platform Adaptation:** OpenAI/Anthropic/Microsoft changed something underneath you and you have to modify the existing solution just to keep it functioning.

That is exactly the kind of bullshit you are going to encounter constantly. 😆 Claude recommends explicitly naming it and including a limited amount each month rather than silently eating it as “support.” fileciteturn2file0L275-L295

I would absolutely steal that.

Its SLA structure is also better suited to a one-man consultancy than Gemini’s more enterprise-ish SLA suggestions:

**P1 — 4 business hours  
P2 — 1 business day  
P3 — 3 business days**

Business-hours coverage only, explicitly define “response,” don't promise resolution times universally, and don't guarantee uptime on Microsoft/OpenAI/Anthropic infrastructure. fileciteturn2file1L123-L139

That is sane.

Now here’s where I disagree with Claude.

The hardware price is still **way too low**.

Claude moves your Chief of Staff from $1,500 + $200/month to only **$2,500 + $300/month**. fileciteturn2file1L75-L80

Nope.

After our discussion, I think **our conclusion is much better**.

If you sell a physical AI appliance at all, it should be something like:

**$15,000+ deployment + $1,000–$2,500/month**

or don't sell it.

Because Claude is benchmarking that product partly against an appliance vendor. But you're not trying to become an appliance vendor.

That’s the critical distinction.

A company selling standardized AI boxes can charge $4,900 because they've built a repeatable hardware product. You're selling consulting, configuration, integrations, deployment, support, training and potentially onsite responsibility.

Claude itself found PrivateOffice at $4,900 for a standardized appliance, and your original $1,500 was only around a third of that hardware price before even accounting for your consulting time. fileciteturn2file0L220-L234

So I'd actually use Claude's research as evidence for going **much higher**, not merely $2,500.

I also disagree somewhat with Claude on the model connection:

**Claude: $1,500 + $250/month.** fileciteturn2file1L170-L181

I think that's still dangerous as a headline.

A genuinely trivial API hookup could certainly be $1,500. But “connect Claude to our quoting system” can morph extremely quickly into authentication, schemas, retries, logging, permissions, data cleanup, UI changes and error handling.

I'd prefer:

**AI Integration — from $3,500**

and let $1,500 exist only as an internal pricing floor for something hilariously simple.

Same story with custom development.

Claude recommends **$225/hour in 20-hour blocks.** fileciteturn2file1L77-L84

That is perfectly defensible market pricing.

But I'd still rather have you quote **$250–$300/hour equivalent** while selling fixed-price sprints wherever possible.

You're not entering the market as “AI freelancer with five years experience.”

You're entering it with thirty years of “I have seen how software actually breaks inside companies.”

That's worth something.

The workshop research also makes me change my earlier thinking slightly. Claude found that your **$500/head public workshop isn't crazy at all**—there's a University of Iowa half-day at $550—but the actual challenge is competition from free or heavily subsidized AI training. fileciteturn2file0L140-L161

Its solution is clever:

**Don't sell seats yourself. Sell the workshop to Chambers of Commerce, trade groups and associations.**

They bring the audience; you get paid $2,500–$4,000 and harvest qualified leads for audits and builds. fileciteturn2file1L49-L67

That might be your best go-to-market idea so far.

Think about it:

You do a half-day:

> “Five AI workflows hiding inside your business.”

Twenty-five owners/operators attend.

During the workshop three people say:

> “Holy shit, we do exactly that.”

Now you have three potential $2,500 audits.

One becomes a $15K build.

One becomes a $2,500/month retainer.

That's a hell of a customer acquisition machine.

Claude also uncovered something worth paying attention to about retainers: its market research sees a fairly strong split between lower-priced group/leverage delivery around **$800–$1,900/month** and dedicated 1:1 advisory starting around **$3,500/month**. fileciteturn2file0L63-L91

So I actually think Claude's proposed **$2,500 Concierge** is awkwardly sitting near the same hole it criticizes your $1,000 offer for. 😄

I'd simplify:

**AI Office Hours — $500/month**

Group format. Scalable.

Then:

**AI Advisor — $3,500/month**

Dedicated relationship.

Then eventually:

**Fractional AI Lead — $7,500+/month**

Real strategic/technical ownership.

That's cleaner.

So if I combine all three analyses, my current favorite architecture is:

| Offer | Price |
|---|---:|
| Intro / fit call | **Free — 20 min** |
| Tools Working Session | **$500 / 90 min** |
| Workflow Audit | **$2,500** |
| Public / association workshop | **$2,500–$4,000 sponsor fee** |
| Company AI Workshop | **$4,500** |
| Workshop + first production build | **$15,000+** |
| AI Integration | **from $3,500–$5,000** |
| Copilot Studio Agent | **$7,500–$15,000+** |
| Custom development | **$250–$300/hr equivalent** |
| Office Hours | **$500/mo** |
| Dedicated AI Advisor | **$3,500/mo** |
| Managed AI Systems | **$5,000+/mo** |
| Fractional AI Lead | **$7,500–$12,500/mo** |
| Physical Executive AI / Chief of Staff | **$15,000+ + serious monthly support** |

And I'd adopt four Claude ideas basically verbatim:

1. **Find it. Build it. Run it.**
2. **Discovery credits forward for 90 days.**
3. **Platform Adaptation** as its own support category.
4. **Chambers/trade associations as your workshop distribution channel.**

Claude's revised draft has some genuinely great copy too. The bit where the Workflow Audit produces “named tools, not categories” and a prototype of the top candidate is strong because it makes the audit tangible rather than consultant vapor. fileciteturn2file1L19-L35

So the three-model verdict is actually becoming pretty coherent:

**Gemini:** stop underpricing yourself and ditch low-margin liabilities.

**Claude:** productize the discovery/conversion funnel and get rigorous about support.

**Me:** push the technical positioning and implementation prices higher than either of them because that's where your 30-year advantage actually monetizes.

That combination is starting to look like a legitimately strong little consulting business, Mike. 🔥

## Turn 5

Conversation turn ID: `11ea172e-ac86-4388-8591-2cb748677abe`

### User

[@GitHub](plugin://github@openai-curated-remote) can you see this repo?
[https://github.com/mbreault/ai-concierge](https://github.com/mbreault/ai-concierge)

### ChatGPT

Yep — I can see `mbreault/ai-concierge`, and I have full read/write access to it through the connected GitHub account. The default branch is `main`.

I can inspect the files, review the current structure/content, suggest changes, or make edits in a branch and open a PR.

## Turn 6

Conversation turn ID: `8fa83a41-b1ab-4dc6-b801-e32f77c8f1a3`

### User

so there were i want to capture our all of our brainstorming and different version of offerings sheets we can compare and iterate on

### ChatGPT

Yep — I’ve handed this off into a new Work thread so it can actually organize the repo rather than just talk about it.

The goal I gave it is to preserve every version, add the Gemini and Claude research, create a “current best” synthesized offering sheet, and keep a decision/changelog so we can see why pricing, positioning, SLA terms, hardware strategy, etc. changed over time.

That should give us a much better setup for iterating without losing any of the useful branches of thought.
