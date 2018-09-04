# Research Overhaul
<sub>(Created by Soraphis: 28.9.2016)</sub>

## Preface

This is a mod suggestions which totally overhauls the way research works.

## Overview

### Knowledge

The knowledge about something is now per pawn. Each Research-Topic is partitioned into several small parts. When at the Researchtable, the pawn will learn one random part.

Beginning with an Empty bar: `[ | | | | | | | | | | | | | | | | ]`

after the research it could look like this `[■| | | | | | |■| | | | | |■|■| | ] `

lets say you have a second pawn researching the same topic, and his knowledge about the topic looks like this:
`[■| | | | | |■|■|■| | | | | | | | ] `

When those two pawns talk, they share (based on their social skill) between 1 and 4 dots.

lets say pawn 1 has a social skill about ~8 and will share 2 slots, when talking to pawn 2 (social skill of 4).
so he sends the position of two of his dots to pawn 2, lets say the first and the last.


pawn 2 (with a social skill of 4) sends his second dot to pawn 1. so after talking about their research their knowledge bars look like that:

pawn 1: `[■| | | | | |■|■| | | | | |■|■| | ] `

pawn 2: `[■| | | | | |■|■|■| | | | | |■| | ] `

(pawn 1 has send pawn 2 the left most dot, but pawn 2 already knew about it: in other words, they talked about stuff they both already knew)

- there is a cooldown for a pawn to talk about research to another pawn
- if a pawn has fully researched a topic, he will only send blocks the other pawn does not know already
- the number of parts depends on the research topic
- the higher the researchlevel of a pawn the faster he will learn new parts (lvl < 4: 1 part per 4 hours, lvl < 8: 1 part per 3 hours, lvl < 12: 1 part per 2 hours, lvl < 16: 1 part per hour, lvl >= 16: 1 parts per 0.5 hours)
- pawns will count "talking about another pawn with knowledge about it" as "doing research"-task
    - have 3 pawns who want to research but just 1 research table? no problem, two of them will share their knowledge while one is researching new stuff.

### Researches and the Researchtable

Research-Topics are not global anymore, they are per Researchtable, and you can adress specific pawns to specific tables. So its possible to research multiple topics at once.

### Bad Scientists

There are pawns that are rly bad in researching (research skill < 4), they've got a chance to learn "false knowledge" when talking about it with another pawn, there is a chance (based on the social-skill difference and (a bit) research-skill difference) that they remove a dot in the knowledge bar of another pawn.

(they convince him about this false knowledge) 

## Conclusions

- A mod like this makes research a bit slower, because after one of your pawns has researched e.g. thermal energy, you can plan to build the thermal reactor, but none of your construction-pawns knows about it and cant build it until the knowledge was shared through social interaction in the colony with this pawn.

- To counteract that a bit, researching the task itself should be a bit faster.

- This idea would highly increase the power of the Social skill.
 - it takes *communication overhead* into account (small research topics, don't go faster with many people researching it, nor with talking much about it before completion)
   - "keep your team as small as possible. This will save everyone’s time and increase productivity."
 - while topics with a huge amount of parts, can easily be parallelized

- Capturing a pawn, could bring knowledge into your colony

