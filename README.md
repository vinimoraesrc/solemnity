# Solemnity

<p align="center">
  <img src="https://github.com/vinimoraesrc/solemnity/blob/main/resources/images/hou-22-solemnity.webp" />
</p>


Solemnity is my favorite Magic: The Gathering Card. It's strong and unique not because it's broken or even clearly competitive, but because it warps a game that has grown to rely on a single commoditized mechanism to make up for its arguably unwarranted complexity, allowing players to find joyful hidden gems and learning more about Magic's inner workings in the process.

I'm hoping to show you why you shouldn't sleep on it.


## Context

Solemnity was released in the Hour of Devastation set back in 2017, with a pretty unique effect:

```
Players can’t get counters.

Counters can’t be put on artifacts, creatures, enchantments, or lands.
```

As of September 2026, there are no cards that are functionally-equivalent to it.

It has seen some share of play in competitive 1v1 Magic, more specifically in Modern shells that combined it with [Phyrexian Unlife](https://scryfall.com/card/nph/18/phyrexian-unlife) to prevent losing the game while the two were in the field, but it has faded off since and does not appear in any relevant competitive list in the formats it's legal in. This is understandable:

* When treated as a Stax piece, it's a generic one that's overshadowed by cheaper, more targeted alternatives like [Stony Silence][https://scryfall.com/card/mm3/25/stony-silence] or [Disruptor Flute](https://scryfall.com/card/mh3/209/disruptor-flute);
* When treated as part of a 2-card combo piece, it's an expensive one: it's known 2-card [combos[(https://commanderspellbook.com/search/?q=solemnity) cost from 6 to a whopping 11 mana, which is simply too slow for eternal formats.

Meanwhile, in commander play, [EDHRec](https://edhrec.com/cards/solemnity) shows Solemnity being included in only 0.88% of decks, or roughly 40,900 of them. Being a potential Stax piece that completely shuts off some counter-based decks, one wouldn't expect Solemnity to be widely accepted in Brackets 1 through 3, and even some Bracket 4 pods. At the same time, it's again often too slow for a cEDH pod.

In many ways, Solemnity is a card that's just shy of being broken: if it costed 1W, or perhaps if it also targeted Planeswalkers, it could already have been banned in multiple formats and made a commander game changer. However, dismissing the card on the basis of it not providing any game-breaking interaction prevents people from noticing the many hidden, more nuanced interactions it has with cards that rely on counters, making it not only a Stax or game-ending combo piece, but an actual enabler of unique strategies. The cherry on top is: Magic's new design direction, that aggressively relies on bespoke counters, will only make this card better over the years.

To give you a taste, consider what happens when you pay the Impending cost of [Overlord of the Balemurk](https://scryfall.com/card/dsk/113/overlord-of-the-balemurk), a card released 7 years after Solemnity, with it in play.

## Counters over the years

Think back to some of the latest sets you've played, and you'll likely think of at least one card that produced or interacted with counters other than +1/+1. This is no coincidence: Magic currently has 178 types of counters, and in roughly 6.5 years, the number of cards that produce or have some sort of interaction with counters grew by 139.7%, with their presence in the card pool growing by 32.8%.

<p align="center">
  <img src="http://github.com/vinimoraesrc/solemnity/resources/plots/expanded_scope_plot_1_counter_types.svg" />
</p>

In Magic's early years, counters were used as a mechanism to help players keep track of the state of the game, and rarely had a type assigned to them. These were later errataed to contain specific types, as was the case of [All Hallow's Eve](https://scryfall.com/card/leg/88/all-hallows-eve) from the Legends set, whose counters received "Scream" as a type. The game continued to increase in scope and complexity, and with it many different types of counters were being introduced, sometimes to support but a single card: a trend which can be clearly seen in Plot 1, from Ice Age until the early 2000s. Once the game matured, bespoke counter types made way for more streamlined ones, with +1/+1 counters becoming the norm and little exploration happening outside of that. Notice the almost flat line in Plot 1 between the original Kamigawa and Lorwynn blocks.

From 2020 onwards, something changed in how counters were being designed. While the exact reason is unknown to me, it's possible that the growth in card text complexity (reading the card no longer explains the card), backed up by a surge in online Spelltable style play due to COVID-19, pushed counters to be seen as a solution for keeping track of game state once again. That, and Magic also started publishing more sets than anyone cares for. Looking at Plot 1, we can see that 2021 pushed the numbers over the trend line for the first time in 7 years, and the numbers continue to spike until this day.

<p align="center">
  <img src="http://github.com/vinimoraesrc/solemnity/resources/plots/expanded_scope_plot_2_counter_cards.svg" />
</p>

<p align="center">
  <img src="http://github.com/vinimoraesrc/solemnity/resources/plots/expanded_scope_plot_3_counter_card_share.svg" />
</p>

Types are not the only counter-related aspect that have seen a spike since 2020. Plots 2 and 3 show the total number of cards that either produce or interact with counters, and the percentage of these cards over the total number of released cards at a given point in time, respectively. They both show how not only counter presence in cards has been steadily increasing over the years, but also how the design inflection point of 2020 aggressively shifted the importance of counters in the game. Ikoria: Lair of Behemoths serves as a good example, as it was a set that both introduced counters representing evergreen abilities such as Lifelink and Deathtouch, and many cards that interacted with these new counters.

As of September 2026, 7,614 cards, or 12.09% of all released cards, produce or have some sort of interaction with counters. The numbers at the time of Theros: Beyond Death's release, right before Ikoria, were 3,177 and 9.1%.

When counter prevalence increases, so does the relevance of Solemnity.

## Solemnity as an elegant enabler

Solemnity completely hoses some counter-based strategies, and due to how prevalent counters are, you can just jam this card in and it'll often get you results. Infect, -1/-1 counters, experience-based commanders like [Meren, of Clan Nel-Toth](https://scryfall.com/card/tdc/297/meren-of-clan-nel-toth), charge-counter based cards like [Helix Pinnacle](https://scryfall.com/card/eve/68/helix-pinnacle), modification-based commanders like [Sephiroth, Fallen Hero](https://scryfall.com/card/fic/92/sephiroth-fallen-hero), all fall flat in the face of Solemnity, to name some. While my Death and Taxes player brain already considers this to be super exciting, it's not necessarily elegant.

The card's elegance comes from the fact that, aside from working as a stax piece for opponents, it can enable many unique interactions that __positively__ influence cards. Take for instance [Finality counters](https://mtg.fandom.com/wiki/Finality_counter), created as a mechanism to help players remember cards that should be exiled when destroyed, which was a common delayed trigger present in the game, that are completely negated by Solemnity and allow you to keep recursively getting your broken reanimation targets from the graveyard.

Being a global effect, it of course can also bolster your opponents. However, a neat detail is that the positive interactions Solemnity triggers are much harder to come by, and cards that could benefit from it often have alternatives, so designing around them puts you at a significant advantage. The best way I've found of digging up these positive interactions was to open up the [full list of Magic counters](https://mtg.fandom.com/wiki/Counter_(marker)/Full_List) and go through the cards the reference them. Counters that are used to represent costs, keep track of turns, or in general represent negative effects, are the most clear targets for such interactions. Here is a non-exhaustive list of interactions currently enabled by Solemnity:

* Cumulative Upkeep cards: cumulative upkeep leverages age counters to keep track of costs to be paid. Those are completely negated, allowing your [Mystic Remora](https://scryfall.com/card/dmr/59/mystic-remora) to stay in indefinitely, making your creatures never take any damage due to [Inner Sanctum](https://scryfall.com/card/wth/18/inner-sanctum), or keeping you away from combat for as many turns as you want with [Glacial Chasm](https://scryfall.com/card/me2/229/glacial-chasm). This is by far the greatest source of cool interactions for Solemnity;
* Vanishing: cards with vanishing counters stay on indefinitely. Moreover, because they never even get these counters if they enter with Solemnity in play, you get effects like [Out of Time](https://scryfall.com/card/mh2/23/out-of-time) becoming a 3 mana wipe that gets around any type of protection and prevent all recursion;
* Damage counters: cards like [Force Bubble](https://scryfall.com/card/scg/14/force-bubble) and [Delaying Shield](https://scryfall.com/card/ody/17/delaying-shield), which would be completely unplayable today, turn into strong pillow fort builders;
* Impending: all cards from the [Overlord cycle](https://scryfall.com/search?q=set%3Adsk+overlord+of&unique=cards&as=grid&order=name) from Duskmourn: House of Horror, can be played by their Impending cost and already enter as creatures;
* Sagas: If played when a saga is already at a specific step, Solemnity can permanently lock the Saga at that step, allowing you to repeatedly get the same effect every turn. Bouncing Solemnity in response to the Saga's lore counter trigger and then re-playing it can allow you to move between steps and lock on to a different effect; 
* [Dark Depths](https://scryfall.com/card/dmr/244/dark-depths): usually seen as a combo with [Vampire Hexmage](https://scryfall.com/card/2xm/112/vampire-hexmage), Solemnity allows Dark Depths to immediately transform when played;
* [Thing in the Ice](https://scryfall.com/card/inr/91/thing-in-the-ice-awoken-horror): can transform with a single cantrip, serving as a handy mass bounce effect with a major upside.

As each set releases, I find myself looking through the card pool and noticing how Solemnity affects them. I am confident the list of interactions will only grow, both in quantity and in quality.

## Methodology

* **Set universe:** 283 released Scryfall sets classified as `core`, `expansion`, `commander`, `draft_innovation`, `duel_deck`, `eternal`, `from_the_vault`, `masters`, `premium_deck`, and `spellbook`, from Limited Edition Alpha through The Hobbit Eternal (2026-08-14). Promos, tokens, memorabilia, un-sets, and unreleased products are excluded.
* **Counter vocabulary:** named terms immediately preceding `counter`/`counters` in Scryfall’s current Oracle text were extracted, with ordinary pronouns/quantifiers removed. The first set containing each term is its introduction point.
* **Card metric:** each set was queried as Scryfall `e:<set>` with `unique=cards`. A card counts when its current Oracle text explicitly names one or more counter types known by that point; a card is counted once per set.
* **Symbols:** every plotted dot embeds the corresponding [Scryfall set symbol](https://scryfall.com/docs/api/sets)
* **Standard Deviation analysis**: Amber rings and callouts in all three plots mark upward onsets. Primary flags have a per-set derivative at least 1.5 standard deviations above that metric’s all-set derivative mean and are locally largest within a five-set window. Plot #2 also marks Mirrodin and Ikoria as sustained level-shift onsets: their following ten-set mean exceeds their preceding ten-set mean, even though their individual-set derivative is not itself a high-z spike.


## Additional files

In the `resources/data/` and `resources/statistics` folders, you'll find .csv files with helpful data in case you want to follow up on or validate my findings: 

* `expanded_scope_mtg_counter_history_by_set.csv`: one row per plotted set, including denominators and all cumulative measures.
* `expanded_scope_counter_type_introductions.csv`: extracted counter type → first detected set/date mapping.
* `expanded_scope_outlier_findings.csv`: statistics about outliers found in each plot.

## Resources

* [MTG Wiki — Counter (marker)/Full List](https://mtg.fandom.com/wiki/Counter_(marker)/Full_List), used as the conceptual counter taxonomy and historical reference.
* [Scryfall Sets API](https://scryfall.com/docs/api/sets) and [Cards API](https://scryfall.com/docs/api/cards), queried on 2026-09-13 for set dates, card records, Oracle text, and set symbols.
