# Handoff Notes — "White Hole" Novel Project

Context for whichever agent/session picks this up next (e.g. Claude Code). This summarizes the full development conversation that produced `TIMELINE.md` and the repo scaffold, including reasoning behind decisions and things that were tried and discarded, so nothing has to be re-litigated from scratch.

---

## Project shape

A journal-format novel. One woman, from age 10 to her final year on Earth (~age 19-20), then into an unknown new world. Told across three interwoven narrative registers (see "Narrative structure" below and `notes/NARRATIVE_STRUCTURE.md`).

The author's own framing of the core idea, early in the conversation: the book should open not with "a girl who dreams of being an astronaut" but with a girl who simply wants to confide in someone and be remembered — the space dream is downstream of that deeper need, not the point of origin. This is the emotional throughline the whole cosmology and plot is built to serve. Don't let later plot complexity crowd this out — it's the reason the journal format exists at all.

## Physics/premise decisions and why (in case they get questioned later)

Several premise options were explored and discarded before landing on the current version — worth knowing what was rejected and why, so we don't circle back to dead ends:

- **Brown dwarf hitting the sun → black hole**: rejected. Not enough mass by any real mechanism (brown dwarfs are ~0.01–0.08 solar masses; black hole formation needs a collapsing core of several solar masses). Discussed as scientifically indefensible.
- **A black hole "tearing Earth apart" just by being at the sun's location**: rejected. Gravity at a given distance depends on mass, not density — a same-mass black hole exerts the same pull as the sun. Tidal disruption requires close proximity (Roche limit), not just presence.
- **Collision cascade among a swarm of captured bodies**: explored, then explicitly walked back by the author in favor of a simpler mechanism — the rogue planet moves too fast to be gravitationally captured into other orbits, so it just strikes the sun directly. Keep this simpler version; don't reintroduce the debris-swarm cascade.

**Current, locked physics/premise chain:**
1. A rogue, unbound planet (originally floated as Jupiter-mass, kept general) enters the solar system on a hyperbolic trajectory, moving too fast to be captured into any orbit.
2. It strikes the sun directly (Year 5 of the in-story timeline, protagonist age 17). Public terror initially fears stellar-scale failure ("the sun exploding"); in reality it's "just" a violently disturbed convective zone/magnetic dynamo — survivable, but devastating.
3. This produces a multi-year flare-storm era: grid collapse, fried electronics, inverted seasons (heatwaves in winter, blizzards in summer), lethal unpredictable storms. Public mood fractures — relief that the sun didn't detonate curdles into skepticism of scientists. Grey-market/scam exodus schemes proliferate alongside the legitimate, coalition-run Ark Program.
4. Underneath the survivable flare chaos, the rogue planet's passage has also been destabilizing the system's orbital mechanics. Around years 8-10, scientists confirm the deeper, slower verdict: genuine orbital collapse and eventual system-wide collision is now inevitable — the true unsurvivable horizon, distinct from (and initially overshadowed by) the flare-storm chaos people are already numb to.
5. Separately, and unbeknownst to anyone on Earth, an ancient tunnel (see "The Entity" below) arrives at almost exactly this same window — from Earth's side, indistinguishable from a second, crueler black hole.

This dual-track disaster (survivable-but-brutal flares as the lived daily experience; slow orbital collapse as the deeper, later-confirmed verdict) is intentional and should be preserved — it gives two different registers of dread rather than one, and lets public skepticism/denial be dramatically justified rather than just irrational.

## The Entity and the tunnel (core cosmological conceit)

This is the single most important worldbuilding decision in the whole project — everything about the Level 1 narrator flows from it.

- Millions of years before the story begins, a vast, non-corporeal intelligence — composed of self-sustaining electrical/electromagnetic energy, not matter; capable of telekinesis and of exerting influence on magnetic phenomena; functionally long-lived but genuinely mortal (can die) — predicts, through means beyond human science, that this exact solar system will eventually suffer the rogue-planet-triggered orbital collapse described above.
- It opens a tunnel long in advance: a black hole mouth positioned to arrive near the doomed system, a white hole mouth on its own side of the universe, millions of light-years away. Timed to arrive near the point of no return, so life can be pulled through and preserved before the collision cascade makes rescue impossible.
- **Important nuance, explicitly established by the author**: this is NOT the entity acting out of knowledge of or care for Earth's civilization specifically. It has no advance knowledge of Earth, no expectation of finding intelligent life. It is a preservation mechanism tuned to capture biological/genetic material in general (DNA/carbon-based life), not consciousness. The entity's rescue effort and humanity's Ark Program are two entirely independent, uncoordinated responses to the same underlying threat, converging on the same narrow window by coincidence, not design.
- **The twist the entity does not anticipate**: her. A technologically evolved being capable of reasoned argument and ethical appeal (logos and ethos) — arriving intact, self-aware, and able to speak back. This is the entity's own first-contact moment, and it inverts the usual "human discovers alien" structure into "cosmic intelligence discovers, to its own surprise, a mind."
- The entity and the protagonist will eventually meet in the new world. This has not been drafted yet — it's a future plot beat, not yet detailed.

## Human-side plot mechanics (why she ends up alone)

Also important context, since these were arrived at through several rounds of the author refining the "why":

- **Mission design**: NOT solo-by-design. The Ark Program's standard mission is two humans per ark (one woman, one man) — paired specifically for companionship and eventual joint parenthood on arrival, alongside a full biological repository (sperm/egg bank, seed vaults, cryo embryos of fish, chicken, pig, insects, etc.) for terraforming.
- **Scale**: 10,000 arks total, internationally coalition-built (coalition instigated by China, requiring broad multinational resource pooling), each sent to a different, pre-identified neighboring star system. On arrival, crew are decryogenized and work with the ark's AI to assess terraforming potential and eventually begin having children.
- **Her crewmate dies before departure** — clearly established as happening before launch, not during transit or at the threshold (this was an explicit correction from the author; earlier drafts of the idea had it happening later, which was rejected). Exact cause is still an open question (see below).
- **Why she isn't reassigned**: normally, losing a crewmate would trigger a protocol review and reassignment to a replacement couple. But: (a) she is cosmologically trained and personally discovers the second (black hole/tunnel) threat a few days ahead of official confirmation — not through any special genius, but because her MA thesis (an independent re-analysis of existing gravitational-fluctuation data, asking a narrower question than the coalition's broad monitoring sweep) surfaces the signal before it clears the coalition's slower, multi-stage verification pipeline; (b) local/national military launch authorities (untrained in cosmology, operating on rigid paired-crew protocol) try to reassign her ark to a replacement couple; (c) coalition-wide chaos from the flare-storm crisis degrades communications badly enough that the reassignment order stalls in the handoff between local command, coalition oversight, and her ark's automated systems; (d) no confirmed countermand ever reaches the ark; (e) she deliberately does not escalate what she knows through proper channels — protecting her seat through calculated silence rather than active defiance. This silence is meant to carry real ethical weight/ambiguity (see open questions).
- **Departure logistics**: the arks are already stationed in Earth orbit (not launched from the ground at this point in the story) — she has to physically reach orbit through a collapsing, chaotic Earth, alone, freshly grieving. The ark's automated pre-programmed departure sequence proceeds because it never received an authenticated stand-down order.
- **The threshold**: the entity's tunnel arrives at Earth during her ark's departure sequence, indistinguishable from the human side from the very extinction event everyone feared. It consumes her ark and destroys Earth in the same event.

## Personal arc / journal voice progression

Full year-by-year breakdown is in `TIMELINE.md`. Key voice-progression notes from the conversation, useful for actual drafting:

- Age 10: short, present-tense, associative jumps; NOT about space — about wanting to confide and be remembered. The astronaut dream should surface sideways/incidentally, not as the opening subject.
- Age 11-14: half-understands escalating world events through kid logic; personal losses/disappointments sharpen the "remembered" fear into something real.
- Age 15-17: ambition sharpens into intent; she starts writing slightly for an imagined future reader while still being honest.
- Age 17-19: controlled, competent voice in public/training contexts, with the journal as the one place composure cracks.
- Final year: entries shorten again — not from inability (as at age 10) but from time pressure and uncertainty she'll get to finish a thought. Final entry should cut off physically, mid-sentence, at the moment of crossing.

## Narrative structure: the three levels (see `notes/NARRATIVE_STRUCTURE.md` for full detail)

This was the last major structural decision and is fully locked in with a worked example:

- **Level 1 — The Entity's voice.** Frame narrator. Speaks in **direct address to the reader** ("us") — confiding, not narrating at a remove. This is important and was explicitly clarified by the author: the entity is talking *to us*, not referring to itself collectively or implying other entities exist. Assembles its knowledge of her after the fact from her diary and all digital content (photos, videos, recordings) — it can directly interface with digital/magnetic storage since it's electromagnetic in nature, so it doesn't need her to narrate anything to it. Carries small, uncanny idiom near-misses from having learned language entirely from her records (e.g. "in someone else's sock" instead of "in someone else's shoes") — deliberate, keep this device, it's a good uncanny-valley texture.
- **Level 2 — Her own voice.** Diary entries plus multimedia (photos, videos, recordings). Later includes direct address once she becomes aware of the entity's presence — some of her words are knowingly spoken *to* it, blending unwitnessed private record with witnessed communication.
- **Level 3 — Remembrance.** Not a document type, a *register*: inner dialogue, half-formed thoughts, remembered exchanges with someone else (crewmate, parent, mentor). Can appear directly in her voice, or filtered through the entity's figurative language when it's reconstructing something the record only implies. Deliberately ambiguous whether a given fragment is her true memory or the entity's imaginative approximation — this ambiguity is intentional and should be preserved in drafting, not resolved.

**Worked example given by the author** (useful as a template for chapter drafting):

> (first voice) She grabbed the piece of paper.
> (second voice) Don't forget me.
> (third voice) What could that mean?
> (first voice) She was always having a hard time being in someone else's sock. We all knew what that meant.

## Repo state

A local git repo was scaffolded (`whitehole-repo/`) with:
- `README.md` — project overview and workflow suggestions
- `notes/TIMELINE.md` — full timeline (same content as the standalone `TIMELINE.md` delivered alongside this handoff doc)
- `notes/NARRATIVE_STRUCTURE.md` — three-level narration breakdown with worked example
- `characters/protagonist.md`, `characters/entity.md` — starter bios with open questions flagged inline
- `chapters/` — empty, not yet drafted
- One commit made locally; not yet pushed to GitHub (no GitHub connector/credentials available in the chat environment that produced this — needs to be pushed by the author via their own machine or Claude Code).

Earlier in the conversation, this same timeline content was also uploaded to a Google Drive folder called "White Hole" as several versions (v1 through v4) due to the Drive connector only supporting file *creation*, not in-place editing — this created duplicate files. The author was advised to migrate to Git for exactly this reason (real diffs, no duplication), which is why this repo exists. The Drive versions are now superseded; no need to sync back to them.

## Open threads / unresolved decisions

Carried over from `TIMELINE.md`, still open as of this handoff:

- Protagonist's name (not yet chosen)
- Exact cause of her crewmate's death before departure (established as before launch, not during transit or threshold — cause itself still undecided)
- How much guilt or ambiguity she carries about not escalating what she knew about the second object/timeline acceleration
- The nature of "the leftover of her old world" in the new environment — literal remnants, environmental echoes, or something else
- How/when she resumes writing after arrival, and to whom (if anyone) she now imagines she's writing
- Details of her eventual path toward bearing a child alone in the new world (mission was designed for a pair; she arrives alone)
- The exact nature of the entity's mortality — how a being like this could die, and whether that becomes plot-relevant
- Whether the entity has done this before (other systems, other rescues) and what became of what it gathered
- What the actual first meeting between her and the entity looks like (not yet drafted at all)
- Protagonist's specific nationality within the coalition (China-instigated, but she need not be Chinese — this was discussed as an open choice, not decided)

## Tone/craft notes worth preserving

- Avoid over-explaining scientific mechanisms in-narrative; the physics discussion in this conversation was for the author's own confidence in plausibility, not necessarily material to dump into the prose itself.
- The central irony to protect across drafting: her lifelong fear of being forgotten almost becomes literal via what she believes is her destruction — but the very record she kept in order to be remembered becomes the exact material through which the entity comes to know her.
- Cosmic irony to protect: humanity spends its final years terrified of what it reads as a second, crueler extinction event, never knowing it's simultaneously an ancient, deliberate rescue arriving on schedule for entirely unrelated reasons.
