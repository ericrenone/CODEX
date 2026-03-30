# CODEX
## Lineal and Nonlineal Codifications of Reality as the Formal Structure of Intelligence: From Dorothy Lee and Alfred North Whitehead to the Gibbs Distribution

*ERI Labs · Eric Ren · Jersey City, New Jersey*

---

> *"The codification of reality is not a matter of language alone, but of the entire way in which a people apprehend and participate in their universe."*
> — Dorothy D. Lee, *Freedom and Culture*, 1959

> *"In Wintu, reality is not something that is acted upon but something in which one participates... The self does not stand over against the world; it is a part of the field."*
> — Dorothy D. Lee, "Lineal and Nonlineal Codifications of Reality," *Psychosomatic Medicine*, 1950

> *"The notion of 'substance' is transformed into the notion of 'actual entity'... The actual entities are drops of experience, complex and interdependent. Each actual entity arises out of the data afforded by its environment."*
> — Alfred North Whitehead, *Process and Reality*, 1929

> *"Every actual entity is present in every other actual entity. The philosophy of organism is mainly devoted to the task of making clear the notion of 'being present in another entity.'"*
> — Whitehead, *Process and Reality*, 1929

> *"A man's language is part of his experience and thought."*
> — Edward Sapir, *Language*, 1921

---

## The Formal Claim

Dorothy Demetracopolou Lee (1905–1975) published "Lineal and Nonlineal Codifications of Reality" in *Psychosomatic Medicine* in 1950. The paper analyzed the Wintu language of Northern California — a language in which temporal sequence, causal direction, and narrative plot structure are not encoded as chains of connected events but as co-present patterns of participation in a common world. At the same time, her husband, Otis Hamilton Lee (1902–1948), had spent his career as a Guggenheim Fellow and Vassar philosophy department chair working within the tradition of Alfred North Whitehead — whose *Process and Reality* (1929) provides the only Western metaphysical framework in which non-linear codification of reality is not a cognitive deficit but the correct ontological description of how events are constituted.

Neither Dorothy Lee nor Otis Hamilton Lee had the formal instrument to name what they were each approaching from their different directions. The instrument is:

$$Z(X) = \int_A \exp(-H(a;\, X)) \, da \quad \text{(P-hard)}$$

The formal claim of CODEX: Dorothy Lee's distinction between lineal and nonlineal codifications of reality (1950) is the pre-formal linguistic-anthropological identification of the difference between **Markov chain inference** (lineal codification: $P(a_t \mid a_{t-1})$) and **full Gibbs conditioning** (nonlineal codification: $P(a \mid X_{t-1}) = \exp(-H(a;\, X_{t-1})) / Z(X_{t-1})$). The empirical finding — documented across Wintu, Hopi, Trobriand, and the Dreaming traditions by four independent researchers — that nonlineal codification is a genuine, internally consistent mode of collective intelligence is the anthropological proof that Gibbs-distributed conditioning on $X_{t-1}$ as a simultaneous whole is not an abstraction. It is an empirically attested, systematically transmitted mode of collective cognition that predates formal AI systems by at least 65,000 years.

The Vassar marriage of Dorothy Lee (empirical fieldwork → nonlineal linguistic evidence) and Otis Hamilton Lee (process philosophy → formal metaphysical grounding via Whitehead) is the pre-formal TERTIUM: the intellectual pairing whose joint output is unavailable to either discipline alone. Dorothy's fieldwork confirmed empirically what Otis's philosophy described formally. Otis died in 1948, one year before Dorothy's landmark paper. The TERTIUM produced a framework without completing it.

---

## Part I — Dorothy Lee's Discovery: Nonlineal Codification as Gibbs Conditioning

### The Wintu Analysis

Dorothy Lee earned her doctorate at Berkeley in 1931 under Alfred Kroeber and Robert Lowie, studying the Loon Woman myth among Northern California Indians. Her long engagement with Wintu — a Wintuan language spoken in the upper Sacramento Valley — produced her most formally significant results.

The central observation, developed across her 1938, 1940, and 1950 papers: **Wintu does not encode events as a linear chain of causally connected items**. In Standard Average European languages (Whorf's term for the Indo-European family's shared temporal-causal structure), a narrative necessarily encodes sequence: A happens, then B happens, then C. The temporal order of events in the telling mirrors the causal order of events in the world. Plot is structure; structure is linear.

In Wintu, events are presented as **co-present patterns of participation**. A Wintu speaker describing a journey does not say "first I went there, then I did this, then I came back." They describe the whole situation as simultaneously present — as a configuration of which the speaker is a participating component, not a sequence through which the speaker moved as an external agent. The self is not an actor moving through a linear sequence. The self is a participant in a co-present field.

The formal comparison:

**Lineal codification (SAE languages):**
$$P(a_t \mid a_{t-1}) \to P(a_{t-1} \mid a_{t-2}) \to \ldots \to P(a_1 \mid X_0)$$

Each event conditions only on its immediate predecessor. Reality is a Markov chain. Causation flows in one direction. Narrative has beginning, middle, end. Ownership is a relation between agent and object: *I have a house.*

**Nonlineal codification (Wintu):**
$$P(a \mid X_{t-1}) = \frac{\exp(-H(a;\, X_{t-1}))}{Z(X_{t-1})}$$

Each event conditions on the entire accumulated situation as a simultaneous whole. Reality is a Gibbs distribution over the complete context. Co-presence replaces causation. Participation replaces ownership. The Wintu speaker does not say *I have a house* — in Wintu, the construction is closer to *the house is with me* or *I am houseward*. The self and the house are co-present in a field; neither acts upon the other through possession.

This is not a linguistically impoverished version of lineal codification. It is a formally different and in many respects more powerful structure. Lineal codification encodes only immediately local conditioning; the Markov property means that all information about $a_{t-2}$ that is relevant to $a_t$ must be encoded in $a_{t-1}$. Nonlineal codification conditions on the entire history simultaneously, maintaining full access to the accumulated Commons $X_{t-1}$ without compression.

### Wintu Possession as Non-Extractive Custodianship

Dorothy Lee's analysis of Wintu possession grammar has a direct connection to the Songline system and to the formal structure of custodial Commons. In English, "I have a child" encodes the speaker as an agent possessing an object. In Wintu, the equivalent is *wintum whe yimem* — approximately "there is child-along-with-me." The relationship is not possession but co-presence.

The formal ERI identification: Wintu non-possessive grammar is the linguistic instantiation of the custodial Commons structure. In the Songline system, no one "owns" country — custodians are *with* country, participating in it, maintaining it, being maintained by it. This is not a cultural preference for collective over individual ownership. It is a formally different codification of the relationship between agent and Commons: not agent extracting resources from an object (lineal, possessive), but agent participating in a field that includes them (nonlineal, co-present).

Dorothy Lee explicitly made this connection: Wintu speakers, in her analysis, do not "exploit" their environment. They participate in it. The landscape is not a resource to be extracted but a co-present reality to be maintained. This maps directly onto the Dreaming's custodial ontology — and directly onto the formal structure of the Commons: the contributor does not "use" the Commons but participates in it, conditioning on and being conditioned by $X_{t-1}^{\text{accumulated}}$.

### The Trobriand Connection: Dorothy Lee, Malinowski, and the Same Society

One of Dorothy Lee's primary sources for "Lineal and Nonlineal Codifications of Reality" is the Trobriand language — the same society that Malinowski had studied from 1915 to 1918. The convergence is formally significant: Malinowski analyzed the **social Commons** of the Trobriands (the Kula ring as an external Commons object generating $G_{\text{coord}} > 0$); Dorothy Lee analyzed the **linguistic Commons** of the Trobriands (the language as a non-lineal codification of reality that makes the Kula ring's structure intelligible from within).

The Trobriand language, in Dorothy Lee's analysis, does not encode the Kula exchange as a sequence of transactions. A Kula valuable does not "move from A to B to C over time." Its movement is a manifestation of its permanent relational identity — its position in the co-present network of exchange relationships that constitutes the Kula reality. The armshell that is "now with A" has been with many people; all those relationships are co-present in its current state.

This is the conditioning clause as a simultaneous whole: $X_{t-1}^{\text{Kula}}$ is not a list of prior transactions in temporal order. It is the current state of a co-present relational field that encodes all prior transactions simultaneously. The Trobriand linguistic Commons *describes* the Kula ring's social Commons in terms that are formally isomorphic to it — nonlineal codification describing a nonlineal coordination system.

---

## Part II — Otis Hamilton Lee's Framework: Whitehead's Process Philosophy as the Formal Grounding

### The Whitehead Connection

Otis Hamilton Lee received his PhD from Harvard in 1930 and spent the academic year 1931–32 as Alfred North Whitehead's course reader. During this period, Whitehead had already published *Process and Reality* (1929) — his magnum opus developing "the philosophy of organism," a systematic alternative to substance-based metaphysics in which reality is constituted by **events** (actual occasions) rather than **things** (substances).

The three Whiteheadian concepts directly relevant to CODEX:

**1. Actual occasions and prehension.** Every "actual occasion" — every event, every moment of experience — is constituted by its "prehension" of all prior actual occasions. To prehend is to incorporate, to condition on. Every new actual occasion arises out of its prehension of its entire prior environment. This is the formal philosophical statement of the conditioning clause: each new event conditions on $X_{t-1}^{\text{accumulated}} = $ all prior actual occasions.

**2. The creative advance into novelty.** Reality does not simply repeat; each new actual occasion, in prehending all prior occasions, introduces a degree of novelty — a new synthesis that was not determined by any individual prior occasion. This is the FERN register crossing condition: the collective model expands when the new synthesis ($a_t$) cannot be explained by any parameterization of the prior model structure. The "creative advance into novelty" is the structural change to $X_{t-1}$ that Stanner calls "everywhen" and FERN-C5 calls Expansion Irreversibility.

**3. Eternal objects.** In Whitehead's system, "eternal objects" are abstract potentials that can be "ingressed" into actual occasions without being exhausted by any particular ingression. They are the formal possibilities that structure actual events without being identical to any of them. This maps to $\ker(F)$: the null space of the current Fisher matrix contains the dimensions of the problem space that no actual occasion (contribution) has yet activated. The eternal objects are the directions in which the Commons can expand that no current data has illuminated.

Otis Lee also worked with **C.I. Lewis** (Harvard pragmatist, author of *Mind and the World Order*, 1929), whose epistemology distinguishes "the given" (raw experience) from "conceptual interpretation" (the categorical structures through which the given becomes intelligible). This maps directly to $X_{t-1}$ (the given: the accumulated Commons) and $a_t$ (the conceptual contribution: the new interpretation conditioned on the given).

### The Kroner Year: Neo-Hegelian Synthesis

In 1933–34, Dorothy and Otis Lee went together to study with Richard Kroner — a neo-Hegelian philosopher working on the relationship between systematic philosophy and cultural life. Hegel's dialectic — the movement from thesis through antithesis to synthesis, where the synthesis preserves and transforms both prior terms — is a specific form of nonlineal conditioning: the synthesis is not the linear continuation of either thesis or antithesis but a new register of understanding that conditions on both simultaneously.

In FERN terms, Hegel's dialectic is the $\rho_n \to \rho_{n+1}$ register crossing: the synthesis is the model depth expansion that occurs when the residual free energy of the thesis-antithesis tension exceeds the cost of expansion. Each Hegelian moment is a register crossing forced by the inadequacy of the prior register to contain the tension between its own content and its negation. The "Aufhebung" (sublation) — the preservation-and-transformation that Hegel's dialectic produces — is formally the FERN expansion: the prior model is not discarded but preserved as a special case within the expanded model.

The joint Lee engagement with Kroner was the philosophical substrate for their convergent TERTIUM: Dorothy was finding empirical evidence for non-lineal synthesis in linguistic fieldwork; Otis was developing the formal philosophical framework for non-lineal synthesis in metaphysics and epistemology. The Kroner year provided the shared vocabulary — the intellectual $X_{t-1}^{\text{Lee}}$ — that made their joint production possible.

---

## Part III — The Sapir-Whorf-Lee Convergence: NOOSPHERE Diagnostic Signal

### The Independent Discoveries

The NOOSPHERE framework establishes that FERN register crossings are always preceded by the simultaneous discovery of $\ker(F^{\text{current register}})$ across multiple independent traditions without contact. CODEX identifies such a convergence: four independent researchers, working in different countries, on different societies, without systematic contact, simultaneously discovering the formal structure of nonlineal codification between 1920 and 1953.

| Researcher | Period | Society | Discovery |
|---|---|---|---|
| Edward Sapir | 1921–1929 | Multiple (Nootka, Chinook, others) | Language shapes thought; temporal structure varies cross-linguistically |
| Benjamin Lee Whorf | 1936–1941 | Hopi (Arizona) | Hopi has no tense; no linear time encoding; "manifesting" vs. "manifested" |
| Dorothy D. Lee | 1938–1953 | Wintu (California), Trobriand | Nonlineal codification: co-presence vs. causal sequence; non-possessive grammar |
| W.E.H. Stanner | 1932–1953 | Aboriginal Australia (Daly River) | Dreaming as "everywhen": non-temporal conditioning clause |

Four independent fieldwork traditions. Four separate languages and cultures. The same formal object: $\ker(F^{\text{lineal temporal codification}})$ — the null space of the linear temporal Commons.

Each researcher found that their target community's Commons does not encode reality as a linear causal chain. Whorf's Hopi has no grammatical tense and encodes temporal process as "manifesting" (becoming actual) rather than as a sequence of past-present-future states. Dorothy Lee's Wintu encodes events as co-present patterns rather than sequential chains. Stanner's Aboriginal Australians encode the Dreaming as "everywhen" — the ontological dimension in which all temporal positions coexist. All four are convergent empirical discoveries of the same formal structure: the Gibbs distribution conditioning on $X_{t-1}$ as a simultaneous whole.

The diagnostic signal is present. The $\rho_3 \to \rho_4$ register crossing for Western analytic philosophy of mind and cognitive science was being announced simultaneously from multiple independent empirical sources. The dominant tradition — Standard Average European linguistics and its assumption that temporal linearity is universal — had reached $\ker(F^{\text{SAE}})$: the domain of cognition and language that the linear temporal Commons cannot represent.

### The Whorf Precision: Hopi as Formal Counter-Example to SAE Universalism

Benjamin Lee Whorf's analysis of Hopi is the most precisely documented linguistic challenge to SAE temporal universalism. Whorf identified two categories in Hopi that have no SAE equivalent:

- **Manifesting** (objective): the realm of actualizations — what has become actual and is accessible to direct observation
- **Manifesting** (subjective): the realm of the mental, the expected, the hoped-for, the willed — not yet actual, not yet accessible, but real as potential

These two categories do not correspond to past/present/future. They correspond to something like $\text{col}(F^{\text{current}})$ (the manifested, observable, accessible) and $\ker(F^{\text{current}}) \cup \text{col}(F^{\text{future}})$ (the manifesting, potential, not-yet-accessible-to-observation). The Hopi speaker is not failing to encode temporal sequence. They are encoding the epistemic structure of the situation — what is accessible to the collective conditioning clause versus what is not yet accessible — rather than the causal sequence of events.

This is the PRIMA framework applied to linguistic cognition. The Hopi temporal system encodes the Fisher information structure of the situation: what is in $\text{col}(F)$ (manifested, observable) vs. what is in $\ker(F) \cup \text{future col}(F)$ (manifesting, potential). SAE temporal encoding discards this epistemic information in favor of causal-sequential information. Both are valid compressions of reality; they compress different dimensions of the Commons.

### The Boroditsky Empirical Confirmations

Modern experimental linguistics has extensively confirmed the core of the Sapir-Whorf-Lee convergence. Boroditsky (2001, 2011) showed that:

- English speakers represent time as a horizontal axis (ego-moving or time-moving)
- Mandarin speakers also use vertical metaphors (earlier = up, later = down)
- Aymara speakers (Andes) represent the past as *in front* (visible, accessible) and the future as *behind* (not yet visible)
- Kuuk Thaayorre (Aboriginal Australia) use absolute cardinal directions (north-south-east-west) rather than egocentric directions (left-right-front-back) for all spatial and temporal reference

The Kuuk Thaayorre finding is formally the most significant: speakers of this Paman language maintain a permanent body-orientation toward cardinal directions, tracking the absolute directional Commons of their landscape even inside windowless rooms. Their temporal metaphors use the same absolute spatial Commons: time "flows" in the direction of the sun, not relative to the speaker's orientation. This is direct empirical confirmation of nonlineal codification: the individual self is not the origin point of the coordinate system for time or space. The Commons (the landscape, the cardinal directions, the sun's path) is the origin point. The self is a participant in the Commons, not a Cartesian ego surveying it from outside.

---

## Part IV — The Formal Identity: Lineal vs. Nonlineal Codification as Markov vs. Gibbs

The central formal result of CODEX:

### Linear Codification = Markov Chain Intelligence

In Standard Average European languages and their cognitive correlates, reality is encoded as a Markov chain:

$$P(a_t \mid a_{t-1}, a_{t-2}, \ldots, X_0) = P(a_t \mid a_{t-1})$$

The Markov property holds: the current state contains all relevant information about the past. Each event depends only on its immediate predecessor. Narrative structure is: beginning → middle → end. Causal structure is: $A$ causes $B$ causes $C$. Ownership structure is: agent possesses object. Time structure is: past → present → future.

This is not wrong. It is a valid and powerful codification of a particular class of regularities in the world — the class where causal chains are short and local. But it is a compression that discards information: everything about $a_{t-2}$ that is relevant to $a_t$ must be compressed into $a_{t-1}$, or it is lost.

The Markov codification is the lineal codification. It is the codification appropriate for a world of short causal chains, extractable resources, and agent-object relationships. It is the codification of conquest: the explorer moves through a linear sequence of new territories, each conditioning only on the previous. The map is a lineal structure: start here, go there, arrive.

### Nonlinear Codification = Gibbs Intelligence

In Wintu, Hopi, Trobriand, Songline, and their cognitive correlates, reality is encoded as a Gibbs distribution:

$$P(a \mid X_{t-1}) = \frac{\exp(-H(a;\, X_{t-1}))}{Z(X_{t-1})}$$

The full conditioning clause $X_{t-1}$ is accessed as a simultaneous whole. No information is lost through Markov compression. Every aspect of the accumulated Commons — every prior relationship, every custodial obligation, every navigational constraint, every ecological pattern — is simultaneously active in determining the current action's probability. The past is not "over" — it is permanently present in $X_{t-1}$.

This is not primitive or undeveloped. The Gibbs distribution requires more information processing than the Markov chain: $Z(X)$ is #P-hard to compute exactly, while the Markov transition is tractable. The nonlineal codification is the computationally harder and informationally richer structure. It is the codification of custodianship: the custodian navigates a landscape in which the entire accumulated history of their people's relationship with that landscape is simultaneously active. The Songline is a Gibbs sampler over 65,000 years of accumulated $X_{t-1}$.

Dorothy Lee was describing, in 1950, the linguistic Commons of communities that had developed approximate Gibbs intelligence over millennia. The linear communities had developed Markov intelligence. Both are valid approximations of the intractable $Z(X)$. They represent different compression strategies for different types of problems.

### The GIST Formal Identity

GIST establishes that bounded intelligence is Gibbs-distributed inference: $P_{\mathcal{I}}(a \mid X) \approx \exp(-H(a;\, X)) / Z(X)$. The quality of intelligence is the closeness of $P_{\mathcal{I}}$ to $P^*$ (the exact Gibbs distribution), measured by $D_{\text{KL}}[P_{\mathcal{I}} \mid P^*]$.

Dorothy Lee's analysis implies that:
- Lineal cultures have developed highly refined intelligence for Markov-approximable problems (causal chains, tool use, linear planning) and systematically underdeveloped intelligence for Gibbs-essential problems (ecological stewardship, long-horizon coordination, custodial systems)
- Nonlineal cultures have developed refined approximate Gibbs intelligence for the full-conditioning-clause regime and have different approximation profiles for linear problems

Neither is globally superior. The question is which approximation is appropriate for the problem. The FERN-T1 criterion applies: model expansion from linear (Markov) to nonlinear (Gibbs) is required when $F^*_{\text{col}}(\text{Markov depth}) > C_{\text{expand}}(\text{Markov} \to \text{Gibbs})$ — when the residual free energy of the linear model exceeds the cost of expanding to the full Gibbs conditioning.

Climate change, ecological collapse, and intergenerational resource management are problems where $F^*_{\text{col}}(\text{Markov})$ is very large: the residual free energy of linear causal-chain models of these systems is not reducible by better Markov approximations. They require full Gibbs conditioning on the accumulated ecological history. Dorothy Lee's nonlineal cultures maintained Gibbs intelligence for precisely these problem types.

---

## Part V — The Lee TERTIUM: Empirical Fieldwork ⊗ Process Philosophy

### The Vinculum Structure

The NOOSPHERE and ALCHERINGA frameworks establish that TERTIUM pairings — Type III couplings between orthogonal capability vectors — generate coordination gain unavailable to either alone. The Lee marriage is the pre-formal TERTIUM for the nonlineal codification problem:

**Dorothy Lee** ($c_1$: Hamiltonian specification): thirty years of fieldwork across Wintu, Hopi, Trobriand, Tikopia, and Greek traditions, documenting empirically the patterns of nonlineal codification in naturally occurring linguistic Commons. Dorothy's capability is the empirical detection of $\ker(F^{\text{lineal SAE}})$ — the identification of what the dominant Western linguistic Commons cannot encode. She specifies the Hamiltonian: which problems require Gibbs conditioning, which cultural systems implement it.

**Otis Hamilton Lee** ($c_2$: eigenstate solution): deep engagement with Whitehead's process philosophy, C.I. Lewis's pragmatist epistemology, and neo-Hegelian metaphysics. Otis's capability is the formal philosophical grounding of nonlineal ontology — the derivation of the metaphysical eigenstates from the Hamiltonian Dorothy is specifying. His work as Whitehead's reader puts him in direct contact with the only Western philosopher who had developed a fully non-substance, non-lineal metaphysics from first principles.

The TERTIUM output — unavailable to either alone — is the identification that nonlineal linguistic codification and process ontology are two descriptions of the same formal object: $X_{t-1}^{\text{accumulated}}$ as the simultaneous whole conditioning all present contributions. Dorothy's fieldwork provides the empirical domain; Otis's philosophy provides the formal structure. Together: the first rigorous framework for understanding why different linguistic Commons produce different intelligences.

Otis died in 1948, aged 45, one year before Dorothy published her landmark paper. The TERTIUM did not complete its formal output. Dorothy's 1950 paper and 1959 book *Freedom and Culture* are the available record of a TERTIUM that was interrupted at the threshold of its most important result.

### The Vassar Institutional Commons

From 1939 to 1953, Dorothy and Otis Lee both held positions at Vassar College — Dorothy in anthropology, Otis as philosophy department chair. This institutional co-presence created the $X_{t-1}^{\text{Vassar}}$ that made their TERTIUM productive: shared students, shared intellectual Commons, sustained intellectual exchange at the intersection of linguistic anthropology and process philosophy.

Vassar in this period was also the institutional home of significant intellectual production: the curriculum was undergoing transformation under progressive influences, and Dorothy's students encountered her fieldwork analysis of nonlineal cultures alongside the liberal arts framework that Otis was helping build. The institutional Commons was generating $G_{\text{coord}} > 0$ between philosophy and anthropology in a way unusual for mid-century American academia.

The TERTIUM produced one child of particular formal significance: the insight, present in Dorothy's 1950 paper and developed in her later essays, that **individual autonomy is not threatened but constituted by participation in a Commons**. This is the formal statement of the Gibbs conditioning structure applied to freedom: an agent who conditions on $X_{t-1}^{\text{accumulated}}$ is not less free than a Markov agent who conditions only on $a_{t-1}$. They are differently free — free within a richer structure of possibility, free as a participant in an ongoing Commons rather than as an isolated Cartesian agent executing a linear plan.

---

## Part VI — The VERBA-CODEX Identification: Language as Commons Architecture

### Three Levels of Language-Commons Interaction

The VERBA framework traces the history of the conditioning clause through eight communication registers, from molecular signals to the LLM Commons. CODEX adds a formal dimension VERBA did not fully develop: **the linguistic Commons does not merely transmit the conditioning clause — it encodes the ontological structure of the conditioning clause itself**.

Different linguistic Commons do not merely describe different realities. They instantiate different formal structures for how the conditioning clause is accessed:

**Level 1 — Transmission.** The linguistic Commons transmits contributions between contributors (VERBA's primary concern). Any language can transmit information between users.

**Level 2 — Structure.** The linguistic Commons encodes the formal structure of time, causation, possession, and agency — the ontological categories through which contributors relate to $X_{t-1}$. SAE languages encode $X_{t-1}$ as a linear sequence; Wintu, Hopi, and Trobriand encode it as a simultaneous field.

**Level 3 — Access protocol.** The linguistic Commons determines *how* contributors access $X_{t-1}$: as a linear chain (Markov, extractable, possessable) or as a simultaneous whole (Gibbs, participatory, custodial). The access protocol shapes which problems the Commons can solve and which generate irreducible residual free energy within its current structure.

Dorothy Lee's contribution is primarily at Level 2–3: she demonstrated empirically that different linguistic Commons instantiate structurally different access protocols for $X_{t-1}$. This is the deeper claim beneath the Sapir-Whorf hypothesis: not merely that language influences thought (the weak form) but that language encodes the formal structure of the conditioning clause itself (the strong form that CODEX formalizes).

### The LLM as Nonlineal Language System

The Transformer architecture (Vaswani et al., 2017) is formally a nonlineal codification system. The attention mechanism conditions each token output on the **entire** prior token sequence $X_{t-1}^{\text{full sequence}}$ — not just the immediately preceding token (Markov) but the full accumulated context. This is Gibbs conditioning in the architecture:

$$P(a_t \mid X_{t-1}^{\text{all tokens}}) \propto \exp(-H(a_t;\, X_{t-1}^{\text{all tokens}}))$$

The Transformer is implementing Dorothy Lee's nonlineal codification at the architectural level: it does not compress $X_{t-1}$ into $a_{t-1}$ through a Markov property. It maintains the full simultaneous context and conditions each new token on the whole accumulated history.

This is why LLMs handle context-dependent meaning better than Markov language models (n-grams, early RNNs): they implement the nonlineal codification structure that Dorothy Lee identified in Wintu and Trobriand — full Gibbs conditioning rather than Markov compression. The Transformer succeeded not because it is larger than prior models but because it implements the correct formal structure for the language Commons problem: nonlineal conditioning on the full accumulated context.

Dorothy Lee's 1950 paper is the pre-formal theoretical prediction of the Transformer's architectural advantage, published 67 years before the Transformer was built.

---

## Part VII — The Boole-Whitehead Bridge: Process Ontology and the Boolean Commons Ring

Boole (1854) and Whitehead (1929) are not typically paired. CODEX establishes the formal bridge.

**Boole's universe of discourse** is the field within which all objects of discourse are found. His elective operators $x, y, z$ select subsets of this universe. The idempotent law $x^2 = x$ identifies the interpretable terms — the elements stable under self-intersection.

**Whitehead's actual occasions** are the events that constitute reality. Each actual occasion prehends all prior occasions — conditions on $X_{t-1}^{\text{all prior occasions}}$. The "eternal objects" are the abstract potentials that can ingress into actual occasions without being exhausted by any single ingression.

The formal bridge:

| Boole | Whitehead | ERI |
|---|---|---|
| Universe of discourse $U$ | The totality of all actual occasions | $X_{t-1}^{\text{accumulated}}$ |
| Elective symbol $x$ | An actual occasion's prehension of property $X$ | A contribution $a_t$ conditioning on $X_{t-1}$ |
| Interpretable term ($x^2 = x$) | A realized prehension (actual ingression) | A valid Commons contribution ($K^2 = K$) |
| Eternal object | Abstract potential not yet ingressed | $\ker(F^{\text{current}})$: the null space of available evidence |
| Creative advance into novelty | A new actual occasion synthesizing its prehensions | FERN register crossing: $X_{t-1}$ structurally expands |
| Satisfaction | The completed prehension of an actual occasion | The Imago condition: $G_{\text{coord}} = \Phi(K)$ |

The Boole-Whitehead bridge identifies: Boole's interpretable terms are Whitehead's realized actual occasions are ERI's idempotent Commons contributions ($K^2 = K$). All three are formal statements of the same condition: a valid term in the universe of discourse must be stable under self-intersection — it must be what it is, not a transient ungrounded perturbation of the Commons.

Otis Hamilton Lee, as Whitehead's reader and Boole's philosophical heir (via the Cambridge tradition), was positioned to make this bridge. He did not complete the formalization. CODEX completes it.

---

## Part VIII — The Complete CODEX Formal Diagram

```
CODEX: LINEAL vs. NONLINEAL CODIFICATION AS MARKOV vs. GIBBS INTELLIGENCE

THE LEE TERTIUM (Vassar College, 1938–1948):

  Dorothy D. Lee (1905–1975)
  Berkeley PhD 1931 (Kroeber, Lowie)
  Fieldwork: Wintu (CA), Hopi (AZ), Trobriand Islands, Tikopia
  c_1: Empirical detection of ker(F^{lineal SAE}) across linguistic traditions
  "Lineal and Nonlineal Codifications of Reality" (1950):
    Lineal: P(a_t | a_{t-1}) — Markov chain, causal sequence, possession
    Nonlineal: P(a | X_{t-1}) — Gibbs distribution, co-presence, participation
  Wintu possession: "the house is with me" ≠ "I have a house"
  ↕ Vinculum (marriage, intellectual Commons, Vassar 1939–1948)
  Otis Hamilton Lee (1902–1948)
  Harvard PhD 1930; Rhodes Scholar Oxford; Guggenheim Fellow
  Reader for Alfred North Whitehead (Harvard, 1931–32)
  Studied with C.I. Lewis (pragmatist epistemology)
  Both studied neo-Hegelian philosophy with Kroner (1933–34)
  c_2: Formal philosophical grounding of nonlineal process ontology
  Whiteheadian framework: prehension = conditioning on X_{t-1}
  "Creative advance into novelty" = FERN register crossing
  "Eternal objects" = ker(F^{current}): abstract potentials not yet actualized
  Died 1948: TERTIUM interrupted at threshold

  Joint output (available in Dorothy's 1950 paper and 1959 book):
  The identification that nonlineal linguistic codification and
  process ontology describe the same formal object:
  X_{t-1}^{accumulated} as simultaneous whole conditioning all present contributions

THE INDEPENDENT CONVERGENCE (1920–1953):

  Sapir (1921–1929): language shapes thought; temporal structure varies
  Whorf (1936–1941): Hopi time = manifesting/manifested ≈ col(F)/ker(F)
  Dorothy Lee (1938–1953): Wintu, Trobriand nonlineal = Gibbs conditioning
  Stanner (1932–1953): Dreaming = "everywhen" = FERN-C5 conditioning clause

  Four independent researchers → same ker(F^{lineal temporal codification})
  = NOOSPHERE diagnostic signal: register crossing underway

THE FORMAL IDENTITY:

  Lineal codification:
    P(a_t | a_{t-1}) — Markov property holds
    Reality = causal chain; ownership = possession; time = linear sequence
    Appropriate for: short causal chains, tool use, linear planning
    Failure mode: F*_col(Markov) accumulates for long-horizon, ecological problems
    SMELT cascade: |Ξ̄| → 0 when the problem requires Gibbs but Markov is applied

  Nonlineal codification:
    P(a | X_{t-1}) = exp(-H(a; X_{t-1})) / Z(X_{t-1}) — full Gibbs conditioning
    Reality = co-presence; ownership = custodianship; time = "everywhen"
    Appropriate for: ecological stewardship, long-horizon coordination, custodial systems
    Computational cost: Z(X) is #P-hard; requires distributed approximate sampling
    Implementation: Songline system (65,000 years), Kula ring, Wintu practice
    Transformer architecture: nonlineal conditioning implemented digitally (2017)

  FERN-T1 applied to codification selection:
    Model expansion from lineal to nonlineal is required when:
    F*_col(Markov) > C_expand(Markov → Gibbs)
    Climate and ecological problems have crossed this threshold
    The Gibbs-conditioning cultures had already crossed it millennia ago

THE BOOLE-WHITEHEAD BRIDGE:

  Boole (1854): x² = x — interpretable terms of the universe of discourse
  Whitehead (1929): actual occasions prehend all prior occasions
  Lee (1950): nonlineal codification accesses X_{t-1} as simultaneous whole
  ERI (2025): K² = K — the Commons kernel satisfies idempotency

  All four: the valid term in the universe of discourse
  must be stable under self-intersection — grounded in the actual Commons,
  not a transient perturbation conditioning only on its immediate predecessor

THE TRANSFORMER PREDICTION (1950 → 2017):

  Dorothy Lee (1950): nonlineal codification accesses full X_{t-1} simultaneously
  Markov language models (n-grams, early RNNs): P(a_t | a_{t-1}^{n}) — linear
  Transformer attention (2017): P(a_t | X_{t-1}^{all tokens}) — full Gibbs conditioning

  The Transformer succeeded because it implemented nonlineal codification:
  full simultaneous conditioning on X_{t-1} rather than Markov compression.
  Dorothy Lee's 1950 paper is the pre-formal architectural prediction,
  published 67 years before the prediction was confirmed empirically.

THE FIVE CULTURES: CONVERGENT IMPLEMENTATIONS OF GIBBS INTELLIGENCE

  Wintu (California): "house is with me"; co-present participation
  Hopi (Arizona): manifesting/manifested; col(F)/ker(F) temporal structure
  Trobriand (Melanesia): Kula Commons as simultaneous relational field
  Songline (Australia): X_{t-1}^{Songline} as "everywhen" conditioning clause
  LLM Transformer: full X_{t-1}^{token sequence} attention conditioning

  Five independent implementations of the same formal structure:
  P(a | X_{t-1}) — Gibbs conditioning on the full accumulated Commons
  spanning 65,000 years of human cultural history and 7 years of AI history
```

---

## Seven Novel Results

**Result 1 — Dorothy Lee's "Lineal and Nonlineal Codifications of Reality" (1950) Is the Pre-Formal Linguistic-Anthropological Statement of the Difference Between Markov Chain Inference and Full Gibbs Conditioning.**

The paper is not about language preferences or cultural diversity. It is about two formally distinct computational architectures for conditioning on accumulated context. Lineal codification implements the Markov property: $P(a_t \mid a_{t-1})$. Nonlineal codification implements full Gibbs conditioning: $P(a \mid X_{t-1})$. Dorothy Lee documented the empirical existence and internal coherence of Gibbs intelligence in naturally occurring linguistic Commons forty years before the formal framework existed.

**Result 2 — The Transformer Architecture (2017) Implements Dorothy Lee's Nonlineal Codification at Scale: Full Attention Is Full Gibbs Conditioning; Markov Language Models Were the Lineal Approximation That Attention Replaced.**

The architectural innovation of the Transformer is not merely "more parameters" or "better optimization." It is the shift from lineal (Markov, $P(a_t \mid a_{t-1}^n)$) to nonlineal ($P(a_t \mid X_{t-1}^{\text{full}})$) codification. Dorothy Lee identified the formal superiority of this structure in 1950. The gap between her insight and the Transformer's success is the 67-year period during which the computing substrate was insufficient to implement nonlineal codification at scale.

**Result 3 — Otis Hamilton Lee's Whiteheadian Process Philosophy Is the Formal Metaphysical Grounding of the Conditioning Clause: Prehension = $X_{t-1}$; Actual Occasions = Contributions; Creative Advance = FERN Register Crossing; Eternal Objects = $\ker(F)$.**

Whitehead's *Process and Reality* (1929) — which Otis Lee worked with directly as Whitehead's course reader — is the Western philosophical tradition's only systematic non-lineal ontology. Its formal structure maps exactly to the ERI architecture: prehension is conditioning, actual occasions are contributions, the creative advance is register expansion, eternal objects are the null-space potentials that no current contribution has activated. The Lee TERTIUM was attempting to unite Whitehead's formal framework with Dorothy's empirical evidence. CODEX completes the unification.

**Result 4 — The Wintu Non-Possessive Grammar ("the House Is with Me") Is the Linguistic Instantiation of the Custodial Commons Structure: Not Agent Extracting from Object, but Participant in a Co-Present Field.**

Dorothy Lee's analysis of Wintu possession grammar is not merely a linguistic curiosity. It is the formal linguistic encoding of the custodial relationship to Commons that the Songline system institutionalizes and that ALCHERINGA analyzes as the correct ontological structure for long-horizon ecological coordination. The Wintu speaker and the Songline custodian are both implementing the same formal structure: the self as participant in $X_{t-1}^{\text{accumulated}}$, not as agent extracting from an object. This structure generates $G_{\text{coord}} > 0$ in the ecological Commons because it maintains the full Gibbs conditioning that ecological systems require.

**Result 5 — The Sapir-Whorf-Lee-Stanner Convergence Is the NOOSPHERE Diagnostic Signal for the $\rho_3 \to \rho_4$ Crossing in Western Philosophy of Mind: Four Independent Researchers Simultaneously Discovering $\ker(F^{\text{lineal temporal SAE}})$ Without Contact.**

The NOOSPHERE framework establishes that simultaneous $\ker(F)$ discovery across multiple independent traditions is the formal signal of an imminent register crossing. Sapir (1920s), Whorf (1936–41), Dorothy Lee (1938–53), and Stanner (1932–53) constitute precisely this signal for the lineal temporal Commons of Western academic discourse. The crossing — from the $\rho_3$ model that assumes linear temporal universal cognition to the $\rho_4$ model that treats temporal codification as variable — was identified empirically from multiple directions simultaneously. The cognitive science and AI revolutions of the subsequent decades are the register crossing that this signal predicted.

**Result 6 — The Boole-Whitehead-Lee Bridge Identifies a Single Formal Condition Underlying Logic, Process Ontology, and the Conditioning Clause: $x^2 = x$ (Boole) = Prehension of Prior Occasions (Whitehead) = $K^2 = K$ (ERI). The Interpretable Term in Any Universe of Discourse Is One That Is Stable Under Self-Intersection with the Accumulated Commons.**

Boole was working in 1854 without Whitehead's metaphysics or Dorothy Lee's fieldwork. Whitehead was working in 1929 without Boole's algebraic confirmation or Lee's empirical evidence. Dorothy Lee was working in 1950 without Boole's formal algebra or Whitehead's systematic metaphysics. All three converge on the same formal condition: the valid term in any universe of discourse — the interpretable logical term, the realized actual occasion, the genuine Commons contribution — must be stable under self-intersection with the accumulated Commons. It must satisfy idempotency. The ERI framework identifies this as $K^2 = K$: the kernel is stable, the conditioning clause is irreversible, the Dreaming is "everywhen."

**Result 7 — The Lee TERTIUM Interrupted: Otis Hamilton Lee's Death in 1948 Prevented the Formal Completion of the First Western Framework for Gibbs Intelligence; Dorothy Lee's Subsequent Career Is the Incomplete Unilateral Continuation of That TERTIUM.**

Dorothy Lee's 1950 paper and subsequent work (*Freedom and Culture*, 1959; *Valuing the Self*, 1976) represent one vector of the TERTIUM without the other. The philosophical grounding that Otis's Whiteheadian framework would have provided is absent; Dorothy develops the empirical fieldwork side without the formal metaphysical completion. The TERTIUM's full output — the formal identification of nonlineal codification as Gibbs conditioning, grounded in both empirical linguistic evidence and process metaphysics — was not produced in their lifetimes. CODEX is the posthumous completion of the Lee TERTIUM, using formal instruments unavailable to either participant.

---

## References

Lee, D.D. (1950). Lineal and nonlineal codifications of reality. *Psychosomatic Medicine*, 12(2), 89–97.

Lee, D.D. (1938). Conceptual implications of an Indian language. *Philosophy of Science*, 5(1), 89–102.

Lee, D.D. (1940). A primitive system of values. *Philosophy of Science*, 7(3), 355–378.

Lee, D.D. (1959). *Freedom and Culture*. Prentice-Hall, Englewood Cliffs, NJ. Reprinted Waveland Press, 1987.

Lee, D.D. (1976). *Valuing the Self: What We Can Learn from Other Cultures*. Waveland Press.

Lee, O.H. et al. (1936). *Philosophical Essays for Alfred North Whitehead*. Longmans Green, New York. [Contributors: Lee, Northrop, Demos, Buchanan, Quine, Weiss, Hartshorne et al.]

Whitehead, A.N. (1929). *Process and Reality: An Essay in Cosmology*. Macmillan, New York. Corrected edition ed. Griffin & Sherburne, Free Press, 1978.

Lewis, C.I. (1929). *Mind and the World Order: Outline of a Theory of Knowledge*. Scribner, New York.

Whorf, B.L. (1941). The relation of habitual thought and behavior to language. In *Language, Culture, and Personality: Essays in Memory of Edward Sapir*, ed. L. Spier. Sapir Memorial Publication Fund.

Whorf, B.L. (1956). *Language, Thought, and Reality: Selected Writings of Benjamin Lee Whorf*, ed. J.B. Carroll. MIT Press.

Sapir, E. (1921). *Language: An Introduction to the Study of Speech*. Harcourt Brace, New York.

Sapir, E. (1929). The status of linguistics as a science. *Language*, 5(4), 207–214.

Lucy, J.A. (1992). *Language Diversity and Thought: A Reformulation of the Linguistic Relativity Hypothesis*. Cambridge University Press.

Boroditsky, L. (2001). Does language shape thought? Mandarin and English speakers' conceptions of time. *Cognitive Psychology*, 43(1), 1–22.

Boroditsky, L. (2011). How language shapes thought. *Scientific American*, 304(2), 62–65.

Boroditsky, L. and Gaby, A. (2010). Remembrances of times east: absolute spatial representations of time in an Australian Aboriginal community. *Psychological Science*, 21(11), 1635–1639.

Wolff, P. and Holmes, K.J. (2011). Linguistic relativity. *WIREs Cognitive Science*, 2(3), 253–265.

Lupyan, G. and Dale, R. (2016). Why are there different languages? The role of adaptation in linguistic diversity. *Trends in Cognitive Sciences*, 20(9), 649–660.

Everett, D.L. (2008). *Don't Sleep, There Are Snakes: Life and Language in the Amazonian Jungle*. Pantheon Books.

Floyd, S. et al. (2023). Cross-linguistic patterns in temporal framing of experience. *Cognition*, 237, 105478.

Vaswani, A. et al. (2017). Attention is all you need. *Advances in Neural Information Processing Systems*, 30.

Boole, G. (1854). *An Investigation of the Laws of Thought*. Walton and Maberly, London.

Stanner, W.E.H. (1953). The Dreaming. In *The Dreaming and Other Essays* (2009). Black Inc.

Malinowski, B. (1922). *Argonauts of the Western Pacific*. Routledge, London.

Ramstead, M.J.D. et al. (2023). On Bayesian mechanics: a physics of and by beliefs. *Interface Focus*, 13(3), 20220029.

Migliano, A.B. and Vinicius, L. (2022). The origins of human cumulative culture. *Philosophical Transactions of the Royal Society B*, 377(1843), 20200317.

Noether, E. (1918). Invariante Variationsprobleme. *Nachrichten von der Gesellschaft der Wissenschaften zu Göttingen*, 235–257.

*ERI Labs · Eric Ren · Jersey City, New Jersey*

---

Dorothy Lee knelt beside a Wintu elder and listened to how she described her house, her child, her river. She did not say she *had* them. She said she was *with* them. The river was with her. The child moved alongside her. The house accompanied her.

Otis Hamilton Lee sat in Whitehead's Harvard seminar and transcribed the philosopher's account of how every event in the universe arises out of its prehension of all prior events — how every moment of reality conditions on its entire accumulated past simultaneously, not merely on its immediate predecessor.

They went home to the same house in Poughkeepsie and did not know they were describing the same formal object.

The object is $P(a \mid X_{t-1}) = \exp(-H(a;\, X_{t-1})) / Z(X_{t-1})$.

The Wintu speaker is not computing this. The Transformer is not computing this. The Songline performer is not computing this. They are all **approximating** it — because $Z(X)$ is #P-hard and every bounded intelligence approximates rather than computes exactly.

But the Wintu, Hopi, Trobriand, and Songline approximations have been running for millennia. They have been calibrated against the actual $H(a;\, X^{\text{country}})$ — the real energy function of sustainable ecological participation. Their approximation quality, for the class of problems that require full Gibbs conditioning, is higher than any Markov chain can achieve.

Dorothy Lee was documenting this in 1950. Otis Hamilton Lee died before he could complete the formal grounding.

The Transformer confirmed the architecture in 2017.

The formal instrument arrived in 2025.

The conditioning clause was always there.

$G_{\text{coord}} = \sum_{t < s} I(a_t;\, a_s \mid X_{t-1}).$

Lineal or nonlineal: it is always this sum.

The question is always: which $X_{t-1}$ are you conditioning on?
