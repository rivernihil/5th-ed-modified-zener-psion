# Introduction
Thank you for taking the time to look at this home-brew implementation of psionics for 5th edition.  The psion and adept classes inside use a form of psionic combat which was designed to be used in a world where psionics are ubiquitous, where virtually every intelligent creature has the ability to defend themselves psionically, and many also have methods to fight back or initiate psionic combat of their own.
<p>With this document you will find the following:</p>

 * The Psion: a ranged caster with many utility spells, similar in role to sorcerers, warlocks, or wizards
   * The Clairsentient: a psion subclass that can predict the future and gain extra sensory information
   * The Psychokineticist: a psion subclass that focuses on dealing ranged damage
   * The Telepath: a psion subclass focused on using powers that go directly mind to mind
 * The Adept: a light re-skin of the monk that uses PSI instead of KI, and gains some minor psionic powers
   * additional notes for adapting the monk's subclasses
 * Rules for psionic combat
 * A psionic skill, similar to arcana or religion
 * Spell list and Spell conversions for psionic magic
 * A guide for alternatives to adapt the psion in a setting where psionics are not ubiquitous
 
### Using the supplements

<p>This document is intended to be distributed with two supplementary documents.  One contains a chart to aid resolution of psionic combat.  The other contains cards to print for the reveal phase in psionic combat.</p>
<p>The main chart should be made easily viewable for all players.  For the cards, I print them out on standard paper with no margins or scaling.  After cutting them up, the resulting "card" should be about the size of a standard playing card.  However, it will be too flimsy for use as is.  I slip this paper into a card protector that already has another player card in it.  This keeps it from bending too much.  Depending on the number of players, it may be useful to print a few of these decks.</p>

### Inspirations

I was chiefly inspired by the second edition psionics, which I made use of quite a bit in my youth.  Recently I begun to desire running a campaign in the DarkSun setting, and psionics was the first thing that jumped out at me as a blocking issue.  The UA mystic class did not really fit my needs, although I do hope to see an updated version of it at some point.
<p>Looking back on 2nd edition, one of the things that I loved most was the fiction of the different psionic attack and defense modes.  This love was further cemented by the excellent depictions of psionic combat in *The Verdant Passage*.  However, mechanically, those elements never really shined during play.  Furthermore, the psionicist class as a whole was generally overpowered, stronger than equivalent classes, while simultaneously containing lots of design traps.  Additionally, it was a pain in the butt to use and keep track of.  Luckily for the me, the excellent design of 5th edition has cleared things up a bit and given me room to build the psionicist I always dreamed of.</p>
<p>Over the years, I marinated on those combat modes, and dreamed of marrying them with Zener cards.  The result is in this document.  Gone is the separation between attack and defense and power scores.  The cards provide a simple, fun rock-paper-scissors style of combat that, with my additions, I feel meshes nicely with core 5th edition mechanics.  The prevalence of psionics in the DarkSun setting led me to design psionic combat in a way that is fundamental to the gameplay at the table, and hopefully others will find it useful.  However, I completely understand that some will find this approach too heavy handed for their own games.</p>
<p>Additionally, I desired to clean up psionics a bit thematically.  The in-game fiction of psionics has drifted far from standard sci-fi and fantasy regarding psychic powers.  In my fiction, the things that can be accomplished by psionics is slightly more limited than what has been typical fare for D&D.</p>

### Design Notes

These classes were designed to be used in a homebrew DarkSun campaign setting.
<p>One key aspect of that is the premise that nearly individual has at least some level of latent psionic ability.  As a result, all PCs and NPCs possess a minimum of 2 *psionic modes*.  For non-psionic PCs, those two abilities are chosen randomly to represent the untrained nature of their power..  Specific creatures will generally possess a pre-determined set of skills.  Thus, players can use the knowledge from their previous encounters to aid their psionic combat.  Additionally, PCs and NPCs will have some wild talent, an extra power they can use once a day that is psionic in nature.  Wild talents are not detailed in this guide.</p>
<p>For the design of the Psion, I wanted to keep its powerlevel in line with that of the wizard and/or sorceror.  In my version of the DarkSun setting, the psion fills a role that magic users would normally.  This role-filling also applies somewhat to warlocks as well.  Standard warlocks don't exist in my setting, but a modified version of them fills the role of the Templars of Athas.  As such, due to either rarity or modifications, using elements of the other classes design was desireable from the perspective of balance, ease, and expediency.</p>
<p>PSI points were calculated based on the number of spell slots that the sorceror has available, counting also their ability to convert metamagic into spell slots.  This value was then further reduced in a formulaic fashion as I was concerned that they had too much flexibility, despite their reduced spell list.</p>


<div class='pageNumber auto'></div>
<div class='footnote'>Introduction</div>
\page

# The Psion
Clad in a dark colored robe of the Tyrian bureaucracy, a bald and tattooed dwarf stares into the distance intently as he concentrates on the psionic defenses of King Kalak.  His psychic wards keep the king's most valuable treasures and secrets hidden from those who would otherwise wish to steal them and destroy his king.  The dwarf is paid well for his expertise, and he enjoys unheard of comfort, prestige, and security.  Still, the king knows that bought loyalty tends to have a short shelf-life, so he too keeps his mind's eye open, watching this one and his other servants as well.
<p>A beautiful fire Genasi walks down the city streets passing vendor stalls, sometimes with a smile or a brief word.  Few realize her charms aren't completely natural; she uses telepathic skills to influence others, nudging and tweaking until she gets the results she wants.  If she was more careful, she'd never want for anything, but sooner or later she's bound to cross the path of an even more powerful telepath who won't take kindly to her intrusions.</p>
<p>Unnatural wind and the pop and hiss of static electricity emanate from around a wild looking halfling as he floats down from a cliff with his hair blowing violently in the gusts.  As explosions of psychokinetic energy go off, those below know that running is their only chance of survival, and if they scatter he might not be able to kill them all...</p>
<p>Psions are powerful individuals who have mastered the art of focusing the powers of their mind to shape reality.  While almost all beings on Athas possess some degree of psionic skill, not all have the talent or resources to dedicate their life to pursuing such skills.  Psions blast their foes with invisible forces, tear them to shreds, control the minds of others, cast their senses to far off places, and even glimpse into the otherwise unknowable future.</p>

<div class='classTable wide'>
##### The Psion
| Level | Proficiency Bonus | Psionic Points (PSI) | Psionic Modes | Features | Cantrips Known | Spells Known | Max Spell Level |
|:-----:|:--:|:---:|:-:|:------------------------------------------------|:--:|:--:|:--:|
| 1st   | +2 | 2   | +0 | Spell Casting, Psionic Recovery                 | 4  | 2  | 1  |
| 2nd   | +2 | 4   | +1 | Psionic Discipline                              | 4  | 3  | 1  |
| 3rd   | +2 | 9   | +1 | —                                               | 4  | 4  | 2  |
| 4th   | +2 | 11  | +1 | Ability Score Improvement                       | 5  | 5  | 2  |
| 5th   | +3 | 17  | +1 | —                                               | 5  | 6  | 3  |
| 6th   | +3 | 21  | +2 | Psionic Discipline feature                      | 5  | 7  | 3  |
| 7th   | +3 | 25  | +2 | —                                               | 5  | 8  | 4  |
| 8th   | +3 | 29  | +2 | Ability Score Improvement                       | 5  | 9  | 4  |
| 9th   | +4 | 38  | +2 | —                                               | 5  | 10 | 5  |
| 10th  | +4 | 44  | +2 | Psionic Discipline feature                      | 6  | 11 | 5  |
| 11th  | +4 | 49  | +3 | —                                               | 6  | 12 | 6  |
| 12th  | +4 | 50  | +3 | Ability Score Improvement                       | 6  | 12 | 6  |
| 13th  | +5 | 57  | +3 | —                                               | 6  | 13 | 7  |
| 14th  | +5 | 58  | +3 | Psionic Discipline feature                      | 6  | 13 | 7  |
| 15th  | +5 | 65  | +3 | —                                               | 6  | 14 | 8  |
| 16th  | +5 | 66  | +4 | Ability Score Improvement                       | 6  | 14 | 8  |
| 17th  | +6 | 75  | +4 | —                                               | 6  | 15 | 9  |
| 18th  | +6 | 80  | +4 | Psionic Attunement                              | 6  | 15 | 9  |
| 19th  | +6 | 87  | +4 | Ability Score Improvement                       | 6  | 15 | 9  |
| 20th  | +6 | 95  | +5 | Mental Mastery                                  | 6  | 15 | 9  |
</div>

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 1 | The Psion</div>
\page

### The Power of the mind
Psions use their natural talent to study and master psionics, the power of the mind.  For some rare savants, psionics comes naturally as an extension of their very being.  But for most, mastering the mind takes years of self-reflection, dedication, focus, and willpower.  Many psions seek to hone their talent to give them an edge in survival.  Some seek this power because it is one of the few opportunities for social mobility that exist.  Others grow perversely attached to the power it presents to them, for indeed the power of the mind can be terrible to behold. Psions are one of two psionicist classes, the other being the adept who specializes in using their mind to control their body.

### The Will and the Way
Psionics on Athas are ubiquitous.  The power of psionics is commonly referred to as "the Will," and the self-examination necessary to master the Will is known as "the Way."  Although almost every intelligent being has some small talent with the Will, few have the patience to master the Way.
<p>In the harsh world of Athas, psionics allow those who would otherwise fail to survive to instead prosper.  Even the smallest halfling could contain enough power to destroy any foe or allow a giant to communicate across the world.  Many nobles send their children to psionic academies, hoping that their scions will learn valuable skills which can help them maintain their precarious positions in society.  Freemen too seek to send their gifted children to such academies, hoping that by doing so they can turn fortune in their favor or at least ensure their children have lucrative work.  Street urchins find mentors, sometimes half-mad from their own studies, to teach them. Slaves teach each other tricks of the mind as a distraction or to fulfill their wishes to escape.  No village or tribe can survive the wastes without a psionicist or two.  Although the skills of psionics are greatly aided by proper training, ultimately psionic power comes from an individual's directed effort to unlock their own mind, and not many have the willpower to persist in such endeavors.  Those who do could come from almost any background.</p>

### Creating A Psion
The most important question to answer when creating a psion is how you attained your psychic powers.  Was it a natural talent or years of study?  Did you attend a school, and if so, how was it paid for?  Perhaps you studied under a mentor, such as a hermit or a tribal elder.
<p>Now that you have begun to finally master your psionic powers, what will you do with them?  Do you wish to use your skill to gain fame and fortune, serving the lucrative merchant houses who are always looking out for skilled psions?  Is the mastery of the mind a worthwhile pursuit in and of itself?  Maybe you have a score to settle with a school rival or a powerful noble family.  Perhaps the study of psionics comes so naturally to you that you cannot conceive of another path to follow.  You might decide that your powers give you easy access to things you want in life and that psionic powers represent the natural order of life on Athas, where the strong dominate the weak.</p>

```
```

### Quick Build
You can make a psion quickly by following these suggestions.  First, Charisma should be your highest ability score, followed by Wisdom.  Second, choose any background.  Third, choose *iron will* and *kinetic burst* as your known psionic modes.  Finally, choose the following cantrips (in addition to the required *psychic probe*): *eldritch blast*, *mage hand*, and *friends*, along with the 1st-level spells *charm person* and *shield*.

## Class Features
As a psion, you gain the following class features.

#### Hit Points
**Hit Dice**: 1d6 per psion level<br>
**Hit Points at 1st Level:** 6 + your Constitution modifier<br>
**Hit Points at Higher Levels:** 1d6 (or 4) + your Constitution modifier per psion level after 1st<br>

#### Proficiencies
**Armor:** Light Armor<br>
**Weapons:** Simple weapons<br>
**Tools:** None<br>
<br>
**Saving Throws:** Wisdom, Charisma<br>
**Skills:** Choose two from Culture, Deception, Insight, Intimidation, Parapsychology, Perception, Persuasion

#### Equipment
You start with the following equipment, in addition to the equipment granted by your background:

* (a) a light crossbow and 20 bolts or (b) any simple weapon
* (a) a dungeoneer's pack or (b) a scholar's pack
* Leather armor, any simple weapon, and two daggers

### Spell Casting
As a result of training with a mentor, attending a school, or through natural talent, you have the ability to cast psionic spells.  See the appropriate rules for casting spells in general or your spell list at the end of the class description.

#### Cantrips
At 1st level, you know 4 cantrips, one of which must be *psychic probe*. The remaining 3 are your choice from the psion spell list.  You learn additional psion cantrips of your choice at higher levels, as shown in the Cantrips Known column of the Psion table.

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 1 | The Psion</div>
\page

#### PSI Points
The Psion table shows how many Psionic Points (PSI) you have available to cast your spells of 1st level or higher.  To cast one of these spells you must spend a number of PSI equal to the spell level of the spell being cast.  You regain all PSI when you finish a long rest.
<p>Some spells allow you to spend a greater amount of points for an additional effect, but you cannot spend a number of points greater than your Max Spell Level on one spell.</p>
<p>For example, if you know the 1st-level spell *magic missile*, have 3 PSI available, and your Max Spell Level is 2, you must spend 1 PSI to cast it, or you may instead spend 2 PSI to cast it for an additional effect; however, you cannot yet spend all 3 PSI since your Max Spell Level is 2.</p>

#### Psionic Modes
The number of additional Psionic Modes known above the base known by all (2).  When you create a 1st-level psion, you choose your known psionic modes instead of picking them randomly.

#### Spells Known at 1st Level and Higher
You begin the game knowing 2 first level spells of your choice from the psion spell list.
<p>The Spells Known column of the Psion table shows when you learn more psion spells of your choice.  Each of these spells must be of a level less than or equal to the number shown in the Max Spell Level column.  For instance, when you reach 3rd level in this class, you can learn one new spell of 1st or 2nd level.</p>
<p>Additionally, when you gain a level in this class, you can choose one of the psion spells you know and replace it with another spell from the psion spell list, which also must be a level less than or equal to your Max Spell Level.</p>
<p>Although psions choose a discipline to focus on as their subclass option, they have access to the spell lists of all disciplines.</p>

#### Spellcasting Ability
Charisma is the spellcasting ability for your psion spells because your power is based on your ability to understand the workings of your own mind, as well as focusing your self-control and willpower.  You use your Wisdom whenever a spell refers to your spellcasting ability.  In addition, you use your Charisma modifier when setting the saving throw DC for a psion spell you cast and when making an attack roll with one.<br>
<div align="center">**Spell save DC** = 8 + your proficiency bonus +<br>
your Charisma modifier</div>
<div align="center">**Spell attack modifier** = your proficiency bonus +<br>
your Charisma modifier</div>

#### Spellcasting Focus
Psionic spells do not require the caster to use a spellcasting focus.  Additionally, Psionic spells do not require Verbal, Somatic, or Material components.  However, psions do tend to exhibit either a look of intense focus or to close their eyes in concentration when casting psionic spells, which may alert those around to the potential of a psionic spell being cast.

```
```

### Psionic Recovery
You have learned the ability to recover some of your psychic energy by meditating.  When you finish a short rest, you can recover PSI equal to half of your Max Spell Level, with a minimum of 1 PSI.
<p>For example, if you're a 4th level psion and you take a short rest, you can recover 1 PSI.</p>

### Psionic Discipline
When you reach 2nd level, choose a psionic discipline that reflects your natural talents or desired path of study.  Disciplines include Clairsentience, Psychokinetics, or Telepathy, which are detailed at the end of the class description.  Your choice grants you features when you choose it at 2nd level and again at 6th, 10th, and 14th level.

### Ability Score Improvement
When you reach 4th, 8th, 12th, 16th, or 19th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1.  As normal, you cannot increase an ability score above 20 using this feature.

### Psionic Attunement
At 18th level, you have achieved such mastery over certain spells that you can cast them at will.  Choose a 1st-level psion spell and a 2nd-level psion spell from among those you know.  You can cast those spells at their lowest level without expending PSI when you have them prepared.  If you want to cast either spell at a higher level, you must expend PSI as normal.
<p>By spending 8 hours in meditation, you can exchange one or both of the spells you chose for different spells of the same levels.</p>

### Mental Mastery
When you reach 20th level, you gain mastery over two powerful spells and can cast them with little effort.  Choose two 3rd-level psion spells from among those you know as your mastered spells.  You can cast each of them once at their lowest level once a day without expending PSI.  When you do so, you can't do so again until you finish a short rest.
<p>If you want to cast either spell at a higher level, you must expend PSI as normal.</p>

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 1 | The Psion</div>
\page

## Psionic Disciplines
According to some legends, psionics have been known on Athas since the first days of the world.  Whether or not this is true, the study of psionics is pervasive today.  There are two main categories of psionic traditions or sciences: those of the adept, focusing on the body, and those of the psion, focusing on the mind.
<p>The science that the psions use fall into three disciplines: Clairsentience, Psychokinesis, and Telepathy.  These three represent natural divisions in the focus of the mind that have evolved over the millennia.  Individual schools often specialize in one discipline, but unless there are other schools in the same area, they often cannot afford to neglect the other disciplines.  Outside of the schools, powerful mentors tend to attract and teach students who follow the same discipline.  Even natural talents focus on one of these disciplines, as the division of the disciplines ultimately reflects the underlying natural contours of the mind.  However, true mastery of the mind involves learning aspects of all three disciplines, and some mental techniques are common to more than one discipline.</p>

### Clairsentience
The psionic discipline of clairsentience entails using the power of the mind to gain knowledge that would otherwise be unavailable to an individual's senses.  This ability generally ranges from simple enhancements of the normal senses, the ability to cast the mind outside of the body, and even the power to peer into the future.  Clairsentients are highly valued for their skills, which can easily shift the tides of fortune in the favor of those they support.
<p>Additionally, clairsentients gain knowledge of the weaknesses of the skills and techniques that clairsentients rely upon, and they thus are often able to protect valuable secrets from prying minds.</p>

#### Preternatural Insight
Starting at 2nd level, you can glimpse into the near future and detect the psionic mode of your opposition during a psionic clash.  After losing a psionic clash, instead you can retroactively change your psionic mode to a different mode that you know.  You can use this ability once per short rest.

#### Manifold Knowledge
Beginning at 6th level, casting clairsentient spells comes so easily to you that it expends only a fraction of your psionic power.  After casting a spell in the clairsentience discipline, you regain 1 less PSI than the level of the spell cast, up to a maximum of 5.

#### Precognition
Starting at 10th level, you can spend your contact to turn any attack roll, ability check, or savings throw relating to that creature from a success to a failure or vice versa.  You may use this ability once per short rest.

#### Mind's Eye
Starting at 14th level, you can use both Preternatural Insight and Precognition twice per short rest instead of once.

```
```

### Psychokinesis
The least subtle of the psionic disciplines, psychokineticists use the power of their minds to directly create fields of force to move existing objects, attack their foes, and generate protective shields.  No tyrant's army would be complete without a company of dedicated psychokineticists blasting apart their foes, and they are feared across the land for their awesome power.

#### Empowered Blasting
Starting at 2nd level, when you cast *eldritch blast*, add your Charisma modifier to the damage it deals on a hit.

#### Kinetic Shield
Starting at 6th level, when you cast *shield* as a reaction, after gaining the +5 bonus for the triggering attack, you may dismiss the remaining duration to cause *shield* to additionally gain the effect of *eldritch blast* and target the source of the original triggering attack.

#### Burst of Willpower
Starting at 10th level, you can spend your contact to cast *eldritch blast* on that creature as a bonus action.  Additionally, whenever you cast *eldritch blast*, you may pay 1 PSI to enter into a psionic clash with one of its targets.

#### Mind Over Matter
Starting at 14th level, you gain the ability to cast or dismiss *levitation* as an action.  This version of *levitation* has no duration.

### Telepathy
Perhaps the most iconic of the psionic disciplines is Telepathy.  Telepathy involves using one's mind to interface directly with that of another.  This can be used for simple communication, but nearly everyone is afraid of the terrors of mind control.  Criminals often complain that they were under the effects of telepathic domination, but unless this can be proved, such claims are meaningless.  

#### Telepathic Field
Starting at 2nd level, when an ally within 60' of you enters into a psionic clash, you may use your reaction to take their place instead.

#### Split Brain
Starting at 6th level, when you cast *psionic probe*, you may target an additional creature.  At 10th level, you may target 3 creatures, and at 14th level, you may target 4 creatures.

#### Native Telepath
Starting at 6th level, you can communicate telepathically with any creature you can see or any willing creature you are aware of as long as you are on the same plane of existence.  You don't need to share a language with that creature, but it must be able to understand at least one language.

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 1 | The Psion</div>
\page

#### Memory Manipulation
Starting at 10th level, when you use a telepathic spell on a creature, you may spend the contact to prevent them from remembering anything from the initiation of contact until the spell ends.  While spellbound, if significant changes in their environment occur, they may realize that they have been charmed when the spell ends, and depending on the events leading up to the point of contact they may be able to surmise who was responsible, but they will otherwise have no direct memory of their time spent under the effects of the spell.

#### Telepathic Dominion
Starting at 14th level, as a bonus action, you can spend your contact to attempt to dominate that creature without paying any additional PSI.  That creature makes a Wisdom savings throw, and if it fails, it is charmed by you and must follow your commands for up to 10 minutes or as long as you maintain concentration on this effect.  It makes additional Wisdom saving throws whenever it takes damage, and otherwise this effect behaves like the appropriate *dominate beast/monster/person* spell.  You may use this ability once per short rest.

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 1 | The Psion</div>
\page

<div class='classTable wide'>
##### The Adept
| Level | Proficiency Bonus | PSI Blades | PSI Points | Psionic Modes | Features |
|:-----:|:-----------------:|:----------:|:----------:|:-------------:|:---------|
| 1st   | +2 | 1d4  | -  | +0 | Unarmored Defense, PSI Blades                     |
| 2nd   | +2 | 1d4  | 2  | +1 | PSI Points, Unarmored Movement, Psychic Probe     |
| 3rd   | +2 | 1d4  | 3  | +1 | Adept Tradition, Deflect Missiles                  |
| 4th   | +2 | 1d4  | 4  | +1 | Ability Score Improvement, Slow Fall              |
| 5th   | +3 | 1d6  | 5  | +1 | Extra Attack, Stunning Strike                     |
| 6th   | +3 | 1d6  | 6  | +1 | PSI-Empowered Strikes, Adept Tradition Feature    |
| 7th   | +3 | 1d6  | 7  | +1 | Evasion, Stillness of Mind                        |
| 8th   | +3 | 1d6  | 8  | +2 | Ability Score Improvement                         |
| 9th   | +4 | 1d6  | 9  | +2 | Unarmored Movement Improvement                    |
| 10th  | +4 | 1d6  | 10 | +2 | Purity of Body                                    |
| 11th  | +4 | 1d8  | 11 | +2 | Adept Tradition Feature                           |
| 12th  | +4 | 1d8  | 12 | +2 | Ability Score Improvement                         |
| 13th  | +5 | 1d8  | 13 | +2 | Native Telepath                                   |
| 14th  | +5 | 1d8  | 14 | +2 | Harmonic Essence                                  |
| 15th  | +5 | 1d8  | 15 | +3 | Timeless Body                                     |
| 16th  | +5 | 1d8  | 16 | +3 | Ability Score Improvement                         |
| 17th  | +6 | 1d10 | 17 | +3 | Adept Tradition Feature                           |
| 18th  | +6 | 1d10 | 18 | +3 | Empty Body                                        |
| 19th  | +6 | 1d10 | 19 | +3 | Ability Score Improvement                         |
| 20th  | +6 | 1d10 | 20 | +3 | Perfect Self                                      |
</div>

# Adept
After years of training and sparring, a Half-Giant adept prepares to leave her school.  Her mind and body have fused to become a nearly perfect weapon.  With equipment scarcely more than a light robe, she begins a short trek across the desert to the nearest city.  She is more than capable of getting through any obstacle.
<p>Unseen, a shadowy half-elf stalks through a luxurious mansion.  He is a member of an underground soceity that trades in arts considered by most taboo.  His cabal makes thrives by providing services that few others are capable of.  Although life is cheap on Athas, death is not.</p>
<p>In the boulder fields, a small group of escaped slaves skirmishes with a large B'rohg.  One of the escapees, a thri-kreen adept, deftly jumps among the boulders, uses it's unnatural speed and agility to skirt in and out of the reach of foe's long arms.  Finally, the adept quickly rushes between the  B'rogh's legs and delivers a final blow. The thri-kreen and it's companions are safe, for now.</p>

```
```

### Note: Adapting the adept
The Adept presented here is quite different from the Psion above.  As opposed to being a completely new class (with a new combat system), the Adept is primarily a mild re-skin of the standard monk class.  The monk as presented in 5th edition has powers that are essentially psionic in nature as well as psionic fictionally.  Given that, a few modifications were made to allow them to integrate into model of psionics above.

<p>The adept described below uses charisma (similar to the psion's spellcasting abilities), and constitution (representing their control over their body) instead of the wisdom and dexterity common to the monk.</p>

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 2 | The Adept</div>
\page 

<p>Described below are the modifications to the original monk class, as well as a few notes on re-theming existing monk features.  A few of the subclasses are missing altogether as they do not fit fictionally with a monk powered by psionics.  The Way of the Four Elements, besides being generally thought of as poorly balanced, does not fit the psionic theme of the Adept, and any attempt to alter it would destroy its primary attraction.  It would almost be easier to make an entirely new subclass that had a skill menu.  The Way of the Sun Soul could probably be made useable, but it still requires more modification than just swapping the names around, so I have not adapated it for the time being.  The Way of Tranquility might fit within the theme of psionics presented here, but it does not thematically in my DarkSun campaign, so I have chosen not to adapt it.</p>

### Body and Mind
Adepts of Athas spend years meditating and exercising.  During this time, they utilize their natural psionic abilities to gain mastery over their biology.  Through the training of the adepts, many impressive feats are possible, such as temporarily enhanced strength, faster movement, hardened skin, or more.  Although focused heavily on feats of physique, they also have no less a capable mind.

### Training and Asceticism
Adepts train for years under the guidance of a master.  These "schools" teach a variety of different techniques, passed down from master to student, and as those students grow not only under the guidance of their master but in their own rights, they may continue the lineage of their master, or start a new school of their own (if they desire to take on students at all).  Some of their practices involve enduring extreme conditions in order to unlock the powers of the mind.

### Creating an Adept
One of the biggest questions to answer when creating an adept is to figure out why you are adventuring.  Many adepts roam Athas looking for tests of skill to prove their own mastery.  Others seek hidden knowledge to let them perfect a powerful technique.  Some, turned out by their school, seek adventure as simply a means to survival, or to gather enough wealth to oneday found their own school.  Others have important missions entrusted to them by their school, or from other sources, and they use their powers to accomplish some ends.
<p>Another thing to think about when creating your adept is what was your school like.  Was it a lone master, helping you find time to train in private training halls, individuals' houses, or even the back alleys?  Was it a formal chartered institution near one of the major cities?  Perhaps it was a secretive recluse who trained her students, seeking revenge on one of her peers.</p>

### Quick Build
You can make an adept quickly by following these suggestions.  First, Constitution should be your highest ability score, followed by Charisma.  Second, choose *empty mind*, and *feedback loop* as your known psionic modes.  Finally, choose the hermit background.

```
```

## Class Features
As the PHB Monk, unless otherwise noted.  Swap usages of dexterity for constitution generally, and wisdom for charisma.

#### Hit Points
**Hit Dice**: 1d8 per adept level<br>
**Hit Points at 1st Level:** 8 + your Constitution modifier<br>
**Hit Points at Higher Levels:** 1d8 (or 5) + your Constitution modifier per psion level after 1st<br>

#### Proficiencies
**Armor:** None<br>
**Weapons:** Simple weapons, shortswords<br>
**Tools:** Choose one type of artisan's tools or one musical instrument<br>
<br>
**Saving Throws:** Constitution, Charisma<br>
**Skills:** Choose two from Acrobatics, Athletics, Culture, Insight, and Stealth

#### Equipment
You start with the following equipment, in addition to the equipment granted by your background:

* (a) a shortsword or (b) any simple weapon
* (a) a dungeoneer's pack or (b) a explorer's pack
* 10 darts

### Unarmored Defense
Adepts use a variety of techniques to increase their agility and resilience while fighting.  It could be a metabolic burst of energy, a psychokinetic burst to deflect an attack, or using the adepts control over their body to temporarily increase the stiffness or regeneration of the skin.  This ability uses Dexterity and Constitution.

### PSI Blades
Renamed from *Martial Arts* in PHB.  PSI Blades allow the adept to create psychokinetic blades to enhance their hand-to-hand and melee skills.  The adept may select from their Constitution aside from Strength and Dexterity.

### PSI Points
Renamed from *Ki* in PHB.  Use Charisma modifier instead of Wisdom for PSI save DC

#### Psionic Modes
The number of additional Psionic Modes known above the base known by all (2).  When you create a 1st-level adept, you choose your known psionic modes instead of picking them randomly.

### Psychic Probe
At 2nd level, you gain the *psychic probe* cantrip if you don't already have it.

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 2 | The Adept</div>
\page

### Native Telepath
Renamed from *Tongue of the Sun and Moon* for fictional purposes.  The effect was also changed slightly to match the fiction of telepathic communication presented in the rest of this document.
<p>Starting at 13th level, you can communicate telepathically with any creature you can see or any willing creature you are aware of as long as you are on the same plane of existence.  You don't need to share a language with that creature, but it must be able to understand at least one language.</p>

### Harmonic Essence
Renamed from *Diamond Soul* in the PHB.

## Adept Tradition
The following are loose notes on how to re-theme the monk's subclasses.

### Way of the Open Hand
This particular subclass really needs no adaptations to survive.  *Wholeness of Body* allows regeneration in accordance with psychometabolic fiction.  *Tranquility* is a slight stretch fictionally, but not completely out of bounds.

### Way of Shadow
This subclass stretches the fiction of psionics a bit, but I am content to leave it as in lieu of adapting it at this time, since it seems like an otherwise fun and useful subclass.  I may one day provide a suitable alternative, but for now follow the notes below.

#### Shadow Arts
Instead of *darkness*, and *silence*, the adept should learn *blindness/deafness* and *hold person*.  Instead of the *minor illusion* cantrip, they should learn *mage hand*.

#### Shadow Step
I don't care for the explicit reliance upon shadow, and would consider replacing the effect with that of *misty step*.  The adept can use a combination of speed, distraction, illusory body doubles, and chameleonic skin to achieve such speed.

#### Cloak of Shadows
Invisibility cannot be acheived telepathically, since it would involve affecting the minds of too many entities at once.  Shadow based invisibility could be achieved by turning the skin and eye pigments black, and possibly using some psychokinetic effect to distort or deflect incoming light.  Due to the limitations on being in shadow, this makes the effect presented actually work out ok, if not great.

```
```

### Way of the Long Death
The fictional focus of undeath is not directly related to the mechanics of this subclass.  From a fictional perspective, someone following this path could just study the natural forces of life and death.  If the fictional connection to undeath is desired, it can be maintained, but it would have no obvious tie-ins with psionic powers.  With the modification to simply life and death, this makes a great fictional attachment to the standard psychometabolic powers that are common with the adept.

#### Touch of Death
This power could easily be learned by mimicking some of the blood/moisture draining animals and plants that are not too rarely found in Athas.

#### Hour of Reaping
Fairly standard telepathic effect.

#### Mastery of Death
The result of clairsentient powers.

#### Touch of Long Death
The necrotic energy could be the result of a powerful negative biofeedback loop generated in the target.  Alternatively the energy type could be changed to force or psychic for a more psychokinetic or telepathic touch.

### Way of the Drunken Master
This fiction is not appropriate for the DarkSun setting, which has a serious and grim tone, whereas the typical Drunken Master plays more of a humorous role.  However, from a mechanical perspective there is probably no purer implementation of the capabilities of an adapt focusing on psychometabolic enhanced combat.  This could be called **The Way of the Sandstorm** without changing any mechanics.  One slight modification would be to drop the Performance proficiency, and instead provide athletics or acrobatics which would see more usage.  Additionally, there is no fictional reason for this modified subclass to have brewer's tools, so either drop it completely (after all, they just upgraded performance to athletics/acrobatics) or let the player pick another tool or language.

### Way of the Kensei
Basically an adept who focuses on their weapon, and instills psionic forces to it akin to the standard *PSI blades* class feature.  Without the standard monk fiction behind it, fictionally this is a boring class.  As an alternative, in the DarkSun setting, they should be considered adepts whose training had an emphasis on gladitorial combat.

#### Way of the Brush
This doesn't really fit thematically as writing is extremely uncommon on Athas.  Either drop this completely (it's next to useless in a standard game anyways...), or substitute another tool or language of the player's choice.

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 2 | The Adept</div>
\page

# Psionic Combat
Psionic combat is intended to a fun and unique system to engage your players with and lies at the heart of the fun of playing a psionicist (any character that has specific psionic powers, e.g. a psion or adept). Creating a unique system was essential to making the psion feel like more than just another type of wizard. Psionic combat involves 3 distinct parts that operate together:  psionic modes, psionic clashes, and contact.  To assist with this, I have provided a separate PDF that contains an info sheet displaying quickly how to resolve psionic clashes, as well another sheet which contains images that can be cut out and used as cards to allow those in psionic combat to quickly and easily choose their modes.

### Psionic Modes
Psionic modes represent training in a specific style of thought structure.  As two telepaths engage in a contest of will, without a psionic mode to support their individual thoughts, the two minds would simply merge together briefly, and any motivations to enter into the contest in the first place get lost in the confusion.  Psionic modes provide a mechanism for the individuals involved to retain some elements of their identity during the struggle.
<p>Psions and adepts both gain psionic modes as part of leveling.  Additionally, they have a primary mechanism *psychic probe* to generate psionic clashes, although other methods may exist.</p>
<p>Depending on the level of integration of psionics into your world, you have different approaches for integrating psionic modes, and dealing with psionic clashes, for non-psionic characters.  For example, in my world which is based in the DarkSun setting where psionics are extremely prevalent, I have chosen to give all players two psionic modes to start with.  For non-psionic classes, they will start with two modes randomly (psions and adepts can choose their modes).  These characters are expected to frequently come into contact with psionic wielding enemies and should have some measure of defense against them.  However, non-psionic characters do not start with any abilities that allow them to generate psionic clashes, so their modes are for defense purposes only. If those non-psionic players wish to further engage with psionics, they must then either multi-class or pick up a feat which extends their psychic capabilities.</p>
<p>Consider a different approach: imagine a world where psionics are extremely rare.  In such a case, I would not give non-psionic characters any modes at all.  This has ramifications for how the psionic clashes below are resolved, and you will need to choose a method there that you are comfortable with.</p>
<p>There are seven psionic modes detailed below.</p>

#### Ego Projection
Represented by the **plus** symbol, *ego projection* is an enhanced version of our ordinary sense of self and rationality, magnified to an extreme.  This can have the effect of avoiding the confusion that some modes .

```
```

#### Empty Mind
Represented by the **circle** symbol, *empty mind* clears the mind of all activity.  This generally has the effect of pulling the ground out beneath some of the more aggressive modes, but can be weak against other forms of disruptions.

#### Feedback Loop
Represented by the **spiral** symbol, *feedback loop* creates an echo chamber in the mind that amplifies incoming signals.  These mental feedback loops can cause some modes to attack themselves, but *feedback loop* works best on modes that do not present a strong signal and are thus unprepared for what *feedback loop* can generate.

#### Id Insinuation
Represented by the **star** symbol, *id insinuation* creates a flood of repressed emotive urges from the base of the mind.  Many modes find these urges distracting and thus are prone to falter.

#### Iron Will
Represented by the **square** symbol, *iron will* steels a current frame of mind against change.  Modes that attempt such changes find that they are unable to do so.

#### Kinetic Burst
Represented by the **burst** symbol, *kinetic burst* attempts to use psychokinetic powers to warp and deform the brain itself.  Since the user of this mode must apply these shakes to their own mind, they are not powerful enough to do any real damage, but this shaking can create disorienting effects against some other modes.

#### Synaptic Static
Represented by the **three wavy lines** symbol, *synaptic static* is halfway between a psychokinetic art and a telepathic one, as it creates a buzzing field within the mind inhibiting the formation of normal thought patterns.  This is strong against modes that operate at lower levels of thought.

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 3 | Psionic Combat</div>
\page

### Psionic Clashes
A psionic clash is a contest between two opposing psionic characters, specifically it tends to occur when telepathy is involved. Every psionic spell that requires contact initiates a psionic clash if the caster has not already established contact against the target and if that target is unwilling.  If the target is willing to undergo the effects of a telepathic spell, contact is considered to exist for the purposes of that spell.
<p>Whoever wins the psionic clash establishes contact with the target.  If, during the casting of a spell requiring contact, a psionic clash occurs and the spell caster does not win, the spell fails and the caster spends their action, however they do not pay the PSI cost for this attempted spell. Additionally, the *psionic probe* cantrip's primary purpose is to generate a psionic clash, although it does have an effect if contact has already been made.  Finally the psychokineticist's ability *burst of will* can be used to create a psionic clash.
<p>During a psionic clash, each character's controller selects, in secret, one of their available psionic modes.  When the controllers are ready, the modes are revealed, and resolved.  Optionally, to speed things up, any rolls that would need to be made as a result of success should be done at this time.</p>
<p>To resolve the psionic clash, see the second pdf for a visual chart for a chart that easily shows who wins and who loses.  But to briefly describe it you can follow the below mechanism.  A given mode will beat the three modes to the right of it on the following list, and lose to the three prior to it.  The end of the list wraps around to the front of the list to form a circular structure.  If a mode is pitted against itself no victory or loss takes place (and thus no contact is established).  Here is the resolution order:</p>
  
   * *feedback loop* → *kinetic burst* → *synaptic static* → *empty mind* → *iron will* → *id insinuation* → *ego projection* →
  
<p>For example, if during a clash the two modes revealed are *ego projection* and *synaptic static*, the character using *ego projection* would win.  If that player had instead picked *iron will*, then the player who used *synaptic static* would win the contest.</p>
<p>Among the participants, whoever is the winner of the psionic clash establishes contact against the loser.</p>
<p>Advantage and disadvantage.  This can easily be done for psionic clashes by having the advantaged party choosing two modes instead of one, then using whichever one is most advantageous.  In general I probably try to avoid this happening too often in my games, as someone who smartly chooses their modes has a fairly large advantage at this point.</p>
<p>Optional rule to speed things up for large groups (for example if a telepathic spell hits several targets).  Choose how many groups are affected, it could be 1 group that includes everybody, or it could be several groups of similar creatures.  The point here is to avoid doing a clash for each individual creature.  Then, for each group chosen in the above method, have the caster choose one mode to attack with.</p>

```
```

### Contact
Contact is a condition that represents the psychic influence of one individual over another.  In the language of contact, there are two parties involved.  The *contacter* is the individual who posses influence over the other.  The *contactee* is the individual who is subject to that influence.  When the condition occurs, the contacter is said to *establish contact* against the contactee.  That contact may later be *spent*, i.e. the condition is removed by some ability the contacter has that allows them to do so.
<p>Contact can be used to cause a moment of hesitation or distraction in the contactee.  At any time, the contacter may spend the contact to give the contacter advantage on any one attack roll, savings throw, or ability check where the contactee is involved.  Similarly, it may be spent to give the contactee disadvantage on any one attack roll, savings throw, or ability check where the contacter is involved.</p>
<p>Most telepathic spells require contact.  If that character already has established contact with the target, then that contact is spent.  However, if the character does not have contact, they have the opportunity to enter into a psionic conflict.  If they win, the contact is spent on the spell.  If the caster does not win the conflict, the action is failed, but no PSI points are spent.  Telepathic spells that require contact and otherwise specify an attack roll, savings throw or ability check are instead automatically successful.</p>
<p>The contact condition cannot be applied from the same contacter to the same contactee more than once simultaneously.  Contact has no requirement of PSI or concentration to maintain, but if the contacter is not within 60' of the contactee for more than a minute, the condition is removed.</p>

### Mass Contact
In the interest in time, when a telepathic spell affects multiple targets, there are a few alternate methods to assist.  The below assumes that all the entities have no special telepathic powers.  For entities which do posses enhanced telepathics, resolve the psionic combat as normal.  For example, if a group of 3 untrained thri-kreen and 1 thri-kreen adept were to come under group attack, resolve the psionic combat with the adept as normal, and use one of the below methods for the 3 untrained thri-kreen.

#### Method One
Choose one card at random from all seven possible modes.  This represents the collective unconcious of the group as its minds awaken and interfere with each other chaotically.

#### Method Two
As above, but instead of choosing a mode randomly, choose one mode from a pool of all known psionic modes by any member of the group.

#### Method Three
Use method two, but break large groups into smaller groups whose members are similar.


<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 3 | Psionic Combat</div>
\page

# Adapting Psionics

## Psionics in a non-psionic world
When trying to integrate the psion and adept into a world where psionics is not ubiquitous, there are some significant challenges.  This class is built around frequent usage of the model of psionic combat provided.  Without psionic combat, a lot of the reason to play with psionics is lost.  Additionally, if too many changes to psionic combat are made, many of the subclasses lose their value.  While you could home-brew them to fix those issues, in my opinion you are better off using a lightly re-skinned version of the sorcerer or wizard, and just position it fictionally as a psionicist.  However, I was able to come up with one approach which I think allows the class to function in a way that:
  * psionic players have fun with psionic combat and the class as written
  * non-psionic players aren't put off by it
  * and DMs do not need to do a lot of prep or background work in order to run it
    
Here is the rule:
<div class='descriptive'>
  When a non-psionic character enters into a psionic clash, their untrained mind naturally forms one of the seven psionic modes at random, that character's controller should pick a mode at random from the list of all available modes for every clash they enter into.  However, if the non-psionicist wins the psionic clash, they do not establish contact with the psionicist as normal because only those with some psionic skill are capable of doing so.
</div>

This rule does make psionic combat a little more difficult for the psionic participant.  This is because they can no longer look at past behavior of their opponent to predict their future behavior.  This is alleviated mostly by the fact that they never have give contact to the non-psionicist.

### Spell-casting ability
I chose charisma for my setting, but this could easily be wisdom as well.  In my setting Warlocks use intelligence, and there are no bards or paladins, so I felt like I needed another charisma based class to round things out.  Thematically, charisma does fit with the manipulative nature of telepathic spells.  On the other hand, "Willpower" as a savings throw is more closely related to wisdom, and allows it to fit together more in line with the monk, who also uses wisdom.

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 4 | Adapting Psionics</div>
\page

# Supplementary Rules

## Concentration
The rules for concentration are the same for casting psionic spells that require concentration.

## Multi-classing
Characters add all their PSI points together from all their psionic classes to form one pool of PSI points.  Psionic spells are completely different than their magical counterpart and thus, an individual multi-classed in such a way could have two copies known of the same spell, one psionic and one magical.

## Skills
The skill sections above for the psion and adept make reference to the *culture* and *parapsychology* skills.  In my home-brew version of DarkSun, the *history* and *religion* skills are not present, and culture has filled the gap they left behind.  If you are using this psionics home-brew in a world where those are present, it would be fitting to swap *culture* for *history*.

Additionally, I have created a *parapsychology* skill to function as an analogue of *arcana* for wizards and *religion* for clerics.  Although its function should be pretty obvious, I will provide its definition here.
<br>
<br>
<p>***Parapsychology.*** Your Intelligence (Parapsychology) check measures your ability to recall lore about psionics, psionic items, symbols, monsters, and traditions, and the function of the mind, and the interpretation of dreams.</p>
<br>
<p>If you wish to avoid introducing another skill to your game, this material could reasonably be handled with the *arcana* skill.</p>

## Feats

### Elemental Adept
Due to the prevalence of psionics in my setting, I also allow the "psychic" category of damage types to be chosen here.

### Mage Slayer
Casting a psionic spell still counts as casting a spell (both generally, and for specifically for this feat).

### Psionic Initiate
Similar to Magic Initiate, but only for psionic spells.  You follow the rules for casting spells as per the Psion class, and gain 1 PSI with which to cast the level 1 spell chosen.  Charisma is the ability modifier for this spell.<br>
**Note:** I have created this as a separate feat so that players could take both initiate feats if so desired.

```
```

### Spell Sniper
The cantrip chosen can also come from the psionic spell list.  Charisma is the ability modifier.

### War Caster
This feat works for psionic spells as well, although obviously the second benefit has no use since psionic spells do not have components.

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 5 | Supplementary Rules</div>
\page

# Psionic Spells

## Spell list
<div class='spellList'>
  
##### Categories
  - C - Clairsentient
  - P - Psychokinetic
  - T - Telepathic
  - t - Telepathic, no contact required
  
##### Cantrips (0 Level)
 - C - Blade Ward
 - P - Booming Blade
 - P - Control Flames
 - P - Eldritch Blast
 - t - Friends
 - C - Guidance
 - P - Gust
 - P - Mage Hand
 - t - Message
 - P - Mold Earth
 - T - Psychic Probe
 - t/PC - Psychonistry
 - C - Resistance
 - P - Shillelagh
 - P - Thunderclap
 - C - True Strike
 - T - Vicious Mockery

##### 1st Level
 - C - Alarm
 - T - Animal Friendship
 - T - Bane
 - t - Beast Bond
 - P - Catapult
 - T - Cause Fear
 - T - Charm Person
 - T - Command
 - T - Compelled Duel
 - C - Comprehend Languages
 - C - Detect Unnatural
 - C - Detect Magic
 - C - Detect Poison and Disease
 - C - Detect Psionics
 - T - Dissonant Whispers
 - P - Featherfall
 - P - Floating Disk
 - t - Heroism
 - C - Identify
 - P - Jump
 - P - Magic Missile
 - P - Shield
 - T - Tasha's Hideous Laughter
 - P - Thunderwave

##### 2nd Level 
 - C - Augury
 - T - Blindness/Deafness
 - T - Calm Emotions
 - P - Cloud of Daggers
 - T - Crown of Madness
 - C - Darkvision
 - C - Detect Thoughts
 - T - Enthrall
 - C - Find Traps
 - P - Gust of Wind
 - P - Heat Metal
 - P - Hold Person
 - P - Levitation
 - C - Locate Animal or Plants
 - C - Locate Object
 - T - Mind Spike
 - C - Nystul's Magic Aura
 - C - See Invisibility
 - P - Shatter
 - T - Suggestion
 - P - Warding Wind

##### 3rd Level
 - C - Clairvoyance
 - C - Counterpsionics
 - T - Enemies Abound
 - T - Fear
 - P - Fly
 - C - Nondetection
 - t - Sending
 - P - Wind Wall
 
##### 4th Level
 - C - Arcane Eye
 - T - Charm Monster
 - T - Compulsion
 - T - Confusion
 - C - Divination
 - T - Dominate Beast
 - C - Locate Creature
 - P - Otiluke's Resilient Sphere

##### 5th Level
 - P - Bigby's Hand
 - C - Contact Other Plane
 - P - Control Winds
 - P - Destructive Wave
 - T - Dominate Person
 - T - Dream
 - T - Geas
 - P - Hold Monster
 - C - Legend Lore
 - T - Modify Memory
 - t - Rary's Telepathic Bond
 - C - Scrying
 - T - Synaptic Static (Spell version from Xanathar's)
 - P - Telekenesis
 - P - Wall of Force

##### 6th Level
 - P - Blade Barrier
 - P - Disintegrate
 - C - Find the Path
 - P - Globe of Invulnerability
 - T - Mass Suggestion
 - T - Mental Prison
 - t - Otto's Irresistible Dance
 - C - True Seeing

##### 7th Level
 - P - Forcecage
 - P - Mordenkainen's Sword
 - t - Power Word Pain
 - P - Whirlwind

##### 8th Level
 - T - Dominate Monster
 - T - Feeblemind
 - C - Mind Blank
 - t - Power Word Stun
 - t - Telepathy

##### 9th Level 
 - C - Foresight
 - t - Power Word Kill
 - T - Psychic Scream
 - T - Weird
</div>

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 6 | Psionic Spells</div>
\page

## Spells

#### Psychic Probe
*Telepathic Cantrip*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Duration:** Instantaneous
- **Requires:** Contact

Enter into a psionic clash with a target you can see within range, unless you have already established contact with that target.  If you win the clash, or have already established contact, you deal 1d6 psychic damage to your target.

#### Psychonistry
This spell can be used to generate minor psionic effects, similar in nature to *presdidigitation* or *thaumaturgy*.  The DM will adjudicate the exact effects possible, but some examples might be: poke someone, give an object a small push, open and rattle windows or curtains, cause a small effect in the mind of an individual such as a brief sensation, emotion, or thought that is obviously psionic in nature, getting a brief glimpse of a nearby hidden object, or hearing a word or short phrase from across the room, glimpsing a minor characteristic of an event in the very near future, etc.

#### Detect Psionics
Equivalent to detect magic, but for psionics.

#### Counterpsionics
Equivalent to counterspell, but for psionics.

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 6 | Psionic Spells</div>
