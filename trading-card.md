# Trading Card Game

Rules and ideas for the POLARIS LINE trading card game.

# Table of Contents

- [Trading Card Game](#Trading-Card-Game)
- [Table of Contents](#Table-of-Contents)
- [Concept](#Concept)
- [The General Idea](#The-General-Idea)
  - [Creatures](#Creatures)
  - [Forces](#Forces)
  - [The Discard Zone](#The-Discard-Zone)
  - [The Field](#The-Field)
- [The Game Proper](#The-Game-Proper)
  - [Deck Restrictions](#Deck-Restrictions)
  - [Opening](#Opening)
  - [Turns And Phases](#Turns-And-Phases)
    - [Draw Phase](#Draw-Phase)
    - [Play Phase](#Play-Phase)
    - [Attack Phase](#Attack-Phase)
      - [Declare](#Declare)
      - [Activate](#Activate)
      - [Battle](#Battle)
      - [Damage](#Damage)
    - [Discard Phase](#Discard-Phase)
    - [End Phase](#End-Phase)
  - [End-of-Game](#End-of-Game)
  - [Advance Creatures](#Advance-Creatures)
    - [Progression Creatures](#Progression-Creatures)
 
# Concept

A Yu-Gi-Oh-esque card game where you have to choose between only playing cards with matching symbols, only playing the same card, or playing up to three cards each turn, kinda something like MMBN.

[(*Back to top*)](#Trading-Card-Game)

# The General Idea

The **goal of the game** is to defeat the opponent, by reducing their *Health Points* to zero or causing them to have no cards in their deck. Players start with **4000 HP each.**

**Players** build **decks** of **40 to 60 cards**, and draw **six cards** in their opening *hand* (maximum **eight** in a hand). There are two major types of cards, *Creatures* and *Forces*.

[(*Back to top*)](#Trading-Card-Game)

## Creatures

**Creatures** reside in the **front row**, and can **battle** the opponent's creatures (as well as the **opponent themself**, when they have no creatures). Up to **five** Creatures can be on the field. They have two major stats, *Attack Spec* and *Guard Spec*.

**When two Creatures battle**, the attacker's Attack Spec is **compared** against the defender's Guard Spec (unless Creature or Force **effects** come into play; more on those later). Whichever creature has the lower stat **loses**, and is **destroyed**, with the owner of the losing card **taking damage**.

Creatures can also **enter "*Guard Over*"** (unless Creature or Force effects come into play) **by turning them upside down,** increasing their Guard Spec by an amount stated on the card but **preventing them from attacking.** The loser will not take damage from any battles involving Guard Over Creatures, though their creature is **still destroyed.**

Creature **effects** are usually either **always active** or **require conditions to be met** to be activated. Effects can **change stats**, cause players to **draw or discard cards**, **destroy or summon Creatures**, allow you to **play extra cards**, etcetera. Creature effect types include *Keyword Effects*, effects which are generic enough that they can be represented by a word or phrase; and *Unique Effects*, effects which take more explanation that aren't as generic.

Creatures **cannot battle** the turn they are played (*summoning sickness*).

[(*Back to top*)](#Trading-Card-Game)

## Forces

**Forces** reside in the **back row**, and have no stats. Instead, every Force has an **effect** that has requirements to be met (often simply requiring you to either play or "*tap*" (turn) the card, though sometimes more requirements need to be met). **All Force effects are Unique Effects.**

**Both players** are able to see any Forces currently on the field. You can have up to **seven** Forces on the field.

Forces usually have a **timeframe** placed on the card for how long their effect will last. There's *Instant*, in which a Force's effect resolves immediately; *Moment*, in which a Force's effect will resolve after another effect is activated, a battle happens, or the phase changes; *Phase*, in which a Force's effect will resolve once the phase changes; *Turn*, in which a Force's effect will resolve once the turn ends; and *Continuous*, in which a Force's effect will not resolve until the card leaves the field by external means.

[(*Back to top*)](#Trading-Card-Game)

## The Discard Zone

When cards are **discarded**, **destroyed**, or **their effects resolve** (in the case of Forces), they are sent to the *Discard Zone*. While most cards cannot be used from the Discard Zone, **some effects can only be activated from the Discard Zone.**

Cards in the Discard Zone can be **brought out of** the Discard Zone if an effect says so.

[(*Back to top*)](#Trading-Card-Game)

## The Field

The **field** consists of the *Creature Field* and the *Forces Field*, **where you can play cards to directly** - the Creatures in the Creature Field and the Forces in the Forces Field. Areas outside of the field include the *deck*, the *Advance deck* and the *Discard Zone*.

```
Field Diagram:

    CfCfCfCfCf    Dz
  FfFfFfFfFfFfFf  AD
                  De

Cf: Creature Field
Ff: Forces Field
Dz: Discard Zone
AD: Advance Deck
De: Deck
```

[(*Back to top*)](#Trading-Card-Game)

# The Game Proper

## Deck Restrictions

A deck can have between 40 to 60 cards. You can have up to three copies of a single card, up to eight cards with a particular Letter Mark, and up to five Wild Card Mark cards.

The Advance Deck, which can contain up to 15 cards, is where you store your Advance Creatures (more on them later).

(You can also have a side deck of 10 cards for swapping into your main deck between games.)

## Opening

Each player shuffles their deck, then draws six cards on their first turn. If a player does not like their hand, they can announce to their opponent that they will take a new hand, and then shuffle their current hand back into their deck. Then, they draw a new six-card hand which cannot be shuffled back in - what you draw is what you get.

The players must then decide who goes first - usually, this is done through a coin flip or rock-paper-scissors.

[(*Back to top*)](#Trading-Card-Game)


##  Turns And Phases

After the opening hands are drawn, the first turn begins.

### Draw Phase

The turn player draws. If the turn player cannot draw, the game ends and the opposing player is declared the victor.

[(*Back to top*)](#Trading-Card-Game)

### Play Phase

The turn player may play cards from their hand, and/or activate the effects of cards on the field (if possible).

Every turn, a player can choose to either play up to one creature and two forces, up to three copies of a single card, or play up to five cards with a matching Letter Mark (or a Wild Card Mark) at once.

Some Creatures cannot be played directly from the hand; they will usually require a certain amount of creatures to be played at once; once that amount of creatures are played, they are sent to the Discard Zone and the new creature is played instead. (These creatures cannot be played on the first turn.)

When effects are activated, they resolve in this manner:

`First effect activates > Next effect activates > ... > Last effect activates and resolves > ... > Next effect resolves > First effect resolves`

[(*Back to top*)](#Trading-Card-Game)

### Attack Phase

The turn player may make any of their Creatures that aren't summoning sick attack the opponent's creatures. Any effects that can be activated during this phase may be activated. Creatures can only battle once per turn.

If the opposing player controls no creatures, the turn player may attack them directly. The opposing player takes damage equal to the Attack Spec of the attacking creature.

When a battle occurs, it goes something like this:

#### Declare

The turn player declares what creature of theirs is attacking, and which creature is the target for the attack (or if the opposing player has no creatures, the turn player instead declares a direct attack).

#### Activate

Any effects that take place during a battle, unless stated otherwise, take place during this timeframe. If an effect activates that removes a combatant from the field, causes a combatant to change sides, or would otherwise prevent the battle from taking place, the battle stops here.

#### Battle

The two creatures officially battle, and the winner is decided by whose stat is higher (after any effects applied). (If a direct attack has been declared, this step is skipped; the attacking creature is automatically declared the winner.)

#### Damage

If a combatant was not in Guard Over, the owner of the losing creature takes damage equal to the difference between the Attack Spec of the attacking creature and the Guard Spec of the defending creature. (In the case of a direct attack, the opponent's Guard Speck is counted as 0.)

[(*Back to top*)](#Trading-Card-Game)

### Discard Phase

If they have more than eight cards in their hand, the turn player must discard cards from their hand until they have eight.

[(*Back to top*)](#Trading-Card-Game)

### End Phase

The turn player's turn ends, and the opposing player conducts their Draw Phase.

[(*Back to top*)](#Trading-Card-Game)

## End-of-Game

Once one player loses, the game ends. However, players may instead opt for a best-of-three Set, composed of up to three games- whoever wins two games first is the winner. Between games in a Set, players may add and remove cards from their Side Deck or Deck, as long as the amount of cards in both remain the same by the end.

[(*Back to top*)](#Trading-Card-Game)

## Advance Creatures

Creatures that can only be put in the Advance Deck are called "Advance Creatures". To play an Advance Creature, you must:

1. Have met the requirements of that type of Advance Creature.
2. Have not played more than one Creature this turn.

Once you have fulfilled those requirements, you may 'Advance' by sending the requisite components to the Discard Zone and playing the Advance Creature right from the Advance Deck.

You can look through your Advance Deck at any time, unlike your regular deck.

### Progression Creatures

Progression Creatures are the example type of Advance Creature shown here. In order to play a Progression Creature, you need the Creatures listed on the card to be on the field.
For example, let's say a Progression Creature named "Knight Del Sol Rigel" required the Creatures "Knight Del Sol Satellite Luna" and "Knight Del Sol Satellite Charon". To play Knight Del Sol Rigel from the Advance Deck, you would need both Luna and Charon on the field. Then, you would 'Advance' by sending both Luna and Charon to the Discard Zone. Once that's done, you would draw and immediately play Rigel from the Advance Deck.