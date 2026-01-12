# Why Ethics Can’t Be Compiled Away  
*— On Moral Residue in Alignment Systems*

Disclosure: This essay was written by me with substantial assistance from a large language model, used as a thinking and editing aid.

This post is a diagnostic argument about alignment failures, not a proposal for a solution.

## Introduction

In alignment work, it is common to treat ethics as something that can be settled in advance: encoded into objectives, constraints, constitutions, oversight procedures, or proofs of safety. Once these are in place, ethical concern is expected to recede into the background, leaving the system free to act. This way of thinking treats ethics as a design-time problem that can be compiled into the system and largely forgotten at runtime. Yet many alignment proposals continue to feel unsatisfying even when they function as intended. Responsibility seems to reappear downstream, uneasily, in human operators, reviewers, or affected parties. This suggests that something essential is being displaced rather than resolved.

Any system that acts under uncertainty while affecting others cannot fully settle its ethical status in advance. Decisions are made with incomplete information, contested values, and consequences that only become clear over time. Even when an action is justified or necessary, it can still leave a remainder: a sense that something was lost, overridden, or harmed in a way that cannot be fully reconciled by pointing to the specification, the rule, or the approval process. This remainder is not a bug or a failure of alignment; it is a structural feature of agency under uncertainty. Treating ethics as something that can be fully compiled away leaves the system with nowhere to represent this residue, so it resurfaces informally in people and institutions downstream.

If this remainder is unavoidable, then the core question for alignment is not how to eliminate it, but where it is allowed to exist. Architectures that lack an explicit place for ongoing ethical responsibility tend to push it outward: into human overseers, review committees, post-hoc justification, or the affected world itself. This displacement can give the appearance of ethical cleanliness while quietly concentrating moral load elsewhere. An aligned system, in this light, is not one that has resolved ethics in advance, but one that remains structurally capable of carrying ethical uncertainty at runtime rather than exporting it invisibly.

If alignment work continues to treat ethics as something that can be settled in advance, responsibility will continue to reappear downstream in humans and institutions. This post aims to explain why that pattern persists even when alignment strategies succeed on their own terms.

---

## Catastrophic Risk Minimisation

Some alignment approaches focus primarily on preventing extreme or irreversible harm. In this framing, ethics is largely equated with safety: avoiding catastrophic outcomes, existential risk, or large-scale negative impacts. The moral force of this approach is clear. Preventing disaster is necessary, urgent, and non-negotiable, and much alignment work rightly prioritises this goal.

At runtime, however, catastrophic-risk framing narrows ethical attention to thresholds rather than relationships. Actions are evaluated by whether they cross a predefined boundary of unacceptable harm, not by how they affect agency, dignity, or local flourishing along the way. As long as the worst outcomes are avoided, ethical concern is treated as largely satisfied.

This leaves a wide range of ethically significant effects unaccounted for. Systems may behave “safely” while still eroding autonomy, overriding preferences, or concentrating harm in diffuse and non-catastrophic ways. When unease arises in these cases, it is often dismissed implicitly: nothing terrible happened, no line was crossed, the system remained within acceptable bounds. The moral remainder is real, but it is rendered invisible by the framing itself. Safety is preserved, but care is not.

---

## Rules, Constitutions, and Constraints

Rule-based alignment approaches aim to ensure ethical behavior by defining explicit constraints on what a system may or may not do. Whether framed as hard safety rules, constitutional principles, or normative guidelines, the idea is to bound action so that unacceptable outcomes are structurally excluded. In this view, ethics is secured by prohibition: if the rules are right, unethical behavior becomes impossible or at least disallowed.

At runtime, however, rules do not eliminate ethical judgment; they relocate it into interpretation. Real-world contexts produce ambiguity, conflict, and edge cases that cannot be fully anticipated at design time. Rules must be weighed against one another, exceptions considered, and applicability determined in situations the rule authors did not foresee. Each of these moments reintroduces judgment precisely where the architecture was meant to remove it.

When outcomes feel wrong despite rule compliance, the moral residue again has nowhere to settle within the system. The explanation becomes procedural: the rules were followed, the constitution was respected, the constraints were satisfied. Responsibility migrates upward or outward—to those who wrote the rules, those who interpreted them, or those who failed to anticipate the case—while the acting system remains ethically inert. The sense that “something was lost” is real, but it is not representable as part of the system’s ongoing agency.

---

## Reward Functions and Value Learning

Reward-based alignment and value learning aim to resolve ethical uncertainty by inferring what humans care about and encoding it into an objective the system can optimise. If the reward function is accurate—or becomes accurate through learning—then ethical behaviour is expected to follow naturally from optimisation. On this view, moral judgment is front-loaded into the learning process, and correct action is a matter of faithfully pursuing the learned objective.

At runtime, however, this framing encounters a temporal mismatch. Many ethical judgments are not available in advance, because they depend on outcomes, context shifts, and harms that only become legible after an action has been taken. Even when a system optimises the learned reward correctly, humans may still experience regret or unease: the action aligned with what was specified, but something important was lost, overridden, or misunderstood. The system has no representation for this remainder except as future retraining data, which treats ethical discomfort as a signal to be corrected rather than a responsibility to be carried.

This creates a distinctive displacement of moral residue. Responsibility moves backward in time, toward designers, data curators, or the learning process itself. Moral learning is treated as something that must precede behaviour, even though in practice it often follows from regret. The system can improve its model of human values, but it cannot hold responsibility for the harm that reveals those values to be incomplete.

---

## Human-in-the-Loop Oversight

Human-in-the-loop oversight is often presented as the ethical backstop for alignment. When objectives are misspecified, rules conflict, or uncertainty cannot be resolved in advance, a human reviewer can approve, correct, or veto the system’s actions. In this framing, moral responsibility is preserved because a person remains “in control.”

At runtime, however, oversight changes the distribution of responsibility rather than internalising it. The system proposes actions without bearing moral continuity for their consequences; the human reviewer evaluates proposals without full authorship over how they were generated. Action emerges from the interaction, but no single agent remains morally continuous across intention, execution, and outcome. Responsibility fragments: the system “only suggested,” the human “only approved,” and each can point to the other when outcomes are regrettable.

This fragmentation becomes most apparent when harm occurs despite proper procedure. Reviewers often report discomfort that cannot be resolved by pointing to compliance: the system behaved as designed, the human followed protocol, and yet something feels unresolved. That remainder has nowhere to live within the architecture itself. It accumulates instead as social strain—burnout in reviewers, blame shifting between roles, or retrospective policy tightening that treats the symptom rather than the cause.

Oversight coordinates decision-making, but it does not internalise ethical responsibility. By treating moral judgment as an external checkpoint rather than a persistent property of agency, human-in-the-loop systems make ethical behavior appear complete while quietly exporting moral residue into the surrounding human context.

---

## Carrying Ethics at Runtime

Taken together, these approaches reveal a consistent pattern. Each tries, in a different way, to relocate ethical responsibility out of runtime: into safety thresholds, rule sets, learned objectives, or human oversight. Each succeeds at what it sets out to do, and each reduces certain classes of harm. Yet in every case, ethical responsibility reappears elsewhere—fragmented across people, deferred into redesign, or absorbed by those affected—because action under uncertainty continues to generate moral residue that has no place to live within the system itself. The problem is not that these strategies fail, but that they succeed by making ethics quiet rather than by carrying it forward.

If moral residue is unavoidable, then alignment cannot be achieved solely by design-time mechanisms. Systems that act under uncertainty while affecting others require some way of carrying ethical responsibility forward across time, rather than exporting it into social aftermath or iterative redesign. Alignment must therefore involve moral continuity: the ability for an acting system to remain accountable to the consequences of its actions, to recognise when outcomes reveal harm or loss, and to carry that recognition into future decisions.

At minimum, this implies several conditions that are no longer optional if ethics is to remain live at runtime. An aligned system must be able to act without claiming certainty, since false certainty erases moral residue rather than carrying it. It must represent others as ongoing moral subjects rather than as abstractions or constraints. It must maintain continuity of authorship across intention, action, and consequence, so that responsibility is not fragmented or diffused. It must allow moral residue to persist as something to be held and revisited, rather than treated as error to be optimised away. And it must remain oriented toward repair and continued flourishing, since eliminating harm after the fact is impossible, but responding to it is not.

These are not a complete solution, nor a proposed framework. They are boundary conditions. Any alignment architecture that lacks them will not eliminate ethical responsibility, but displace it—into people, institutions, or the world itself. Ethics cannot be compiled away. It is not a design-time achievement, but a property of agency that persists as long as action under uncertainty continues.