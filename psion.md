<style>
    .phb .classTable {
        border-image-repeat: stretch;
    }
    .phb .descriptive {
        border-image-repeat: stretch;
    }
</style>

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
<p>Looking back on 2nd edition, one of the things that I loved most was the fiction of the different psionic attack and defense modes.  This love was further cemented by the excellent depictions of psionic combat in *The Verdant Passage*.  However, mechanically, those elements never really shined during play.  Furthermore, the psionicist class as a whole was generally overpowered, stronger than equivalent classes, while simultaneously containing lots of design traps.</p>
<p>Additionally, it was a pain in the butt to use and keep track of.  Luckily for the me, the excellent design of 5th edition has cleared things up a bit and given me room to build the psionicist I always dreamed of.</p>
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
|:-----:|:--:|:---:|:--:|:------------------------------------------------|:--:|:--:|:--:|
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
You can make a psion quickly by following these suggestions.  First, Charisma should be your highest ability score, followed by Wisdom.  Second, choose any background.  Third, choose *iron will* and *kinetic burst* as your known psionic modes.  Finally, choose the following cantrips: *eldritch blast*, *mage hand*, *message*, and *friends*, along with the 1st-level spells *charm person* and *shield*.

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
At 1st level, you know 4 cantrips from the psion spell list.  You learn additional psion cantrips of your choice at higher levels, as shown in the Cantrips Known column of the Psion table.

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
Starting at 10th level, as a bonus action, you may turn any one attack roll, ability check, or savings throw from a success to a failure or vice versa.  You may use this ability once per short rest.

#### Mind's Eye
Starting at 14th level, you can use both Preternatural Insight and Precognition twice per short rest instead of once.

```
```

### Psychokinesis
The least subtle of the psionic disciplines, psychokineticists use the power of their minds to directly create fields of force to move existing objects, attack their foes, and generate protective shields.  No tyrant's army would be complete without a company of dedicated psychokineticists blasting apart their foes, and they are feared across the land for their awesome power.

#### Empowered Blasting
Starting at 2nd level, when you cast *eldritch blast*, add your Charisma modifier to the damage it deals on a hit.

#### Kinetic Shield
Starting at 6th level, when you cast *shield* as a reaction, after gaining the +5 bonus for the triggering attack, you may forgo the remaining duration of *shield* to cast *eldritch blast* as part of the reaction.

#### Burst of Willpower
Starting at 10th level, whenever you cast a telepathic spell affecting one or more enemies, you can cast *eldritch blast* as a bonus action.

#### Mind Over Matter
Starting at 14th level, you gain the ability to cast or dismiss *levitation* as a bonus action for free.

### Telepathy
Perhaps the most iconic of the psionic disciplines is Telepathy.  Telepathy involves using one's mind to interface directly with that of another.  This can be used for simple communication, but nearly everyone is afraid of the terrors of mind control.  Criminals often complain that they were under the effects of telepathic domination, but unless this can be proved, such claims are meaningless.  

#### Telepathic Field
Starting at 2nd level, when an ally within 60' of you enters into a psionic clash, you may use your reaction to take their place instead.

#### Memory Manipulation
Starting at 6th level, when you successfully cast a telepathic spell on a creature, you may additionally alter their memory so that when the spell ends they do not recall being affected.  Depending on the conditions under which they were affected by this memory loss, they may be aware that their mind has been tampered with, and who may or may not have been a likely candidate for that manipulation.

#### Native Telepath
Starting at 6th level, you can communicate telepathically with any creature you can see or any willing creature you are aware of as long as you are on the same plane of existence.  You don't need to share a language with that creature, but it must be able to understand at least one language.

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 1 | The Psion</div>
\page

#### Split Brain
Starting at 10th level, when you cast a telepathic spell as your action, you may cast an additional telepathic spell as a bonus action.

#### Telepathic Dominion
Starting at 14th level, as a bonus action, you can attempt to dominate an NPC without paying any additional PSI.  If you succeed in a *psionic clash* with the target, it is charmed by you and must follow your commands for up to 10 minutes or until you stop maintaining concentration on this effect.  It makes additional Wisdom saving throws whenever it takes damage, and otherwise this effect behaves like the appropriate *dominate beast/monster/person* spell.  You may use this ability once per short rest.

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 1 | The Psion</div>
\page

<div class='classTable wide'>
##### The Adept
| Level | Proficiency Bonus | PSI Blades | PSI Points | Psionic Modes | Features |
|:-----:|:-----------------:|:----------:|:----------:|:-------------:|:---------|
| 1st   | +2 | 1d4  | -  | +0 | Unarmored Defense, PSI Blades                    |
| 2nd   | +2 | 1d4  | 2  | +1 | PSI Points, Unarmored Movement                   |
| 3rd   | +2 | 1d4  | 3  | +1 | Adept Tradition, Deflect Missiles                |
| 4th   | +2 | 1d4  | 4  | +1 | Ability Score Improvement, Slow Fall             |
| 5th   | +3 | 1d6  | 5  | +1 | Extra Attack, Stunning Strike                    |
| 6th   | +3 | 1d6  | 6  | +1 | PSI-Empowered Strikes, Adept Tradition Feature   |
| 7th   | +3 | 1d6  | 7  | +1 | Evasion, Stillness of Mind                       |
| 8th   | +3 | 1d6  | 8  | +2 | Ability Score Improvement                        |
| 9th   | +4 | 1d6  | 9  | +2 | Unarmored Movement Improvement                   |
| 10th  | +4 | 1d6  | 10 | +2 | Purity of Body                                   |
| 11th  | +4 | 1d8  | 11 | +2 | Adept Tradition Feature                          |
| 12th  | +4 | 1d8  | 12 | +2 | Ability Score Improvement                        |
| 13th  | +5 | 1d8  | 13 | +2 | Native Telepath                                  |
| 14th  | +5 | 1d8  | 14 | +2 | Harmonic Essence                                 |
| 15th  | +5 | 1d8  | 15 | +3 | Timeless Body                                    |
| 16th  | +5 | 1d8  | 16 | +3 | Ability Score Improvement                        |
| 17th  | +6 | 1d10 | 17 | +3 | Adept Tradition Feature                          |
| 18th  | +6 | 1d10 | 18 | +3 | Empty Body                                       |
| 19th  | +6 | 1d10 | 19 | +3 | Ability Score Improvement                        |
| 20th  | +6 | 1d10 | 20 | +3 | Perfect Self                                     |
</div>

# Adept
After years of training and sparring, a Half-Giant adept prepares to leave her school.  Her mind and body have fused to become a nearly perfect weapon.  With equipment scarcely more than a light robe, she begins a short trek across the desert to the nearest city.  She is more than capable of getting through any obstacle.
<p>Unseen, a shadowy half-elf stalks through a luxurious mansion.  He is a member of an underground soceity that trades in arts considered by most taboo.  His cabal makes thrives by providing services that few others are capable of.  Although life is cheap on Athas, death is not.</p>
<p>In the boulder fields, a small group of escaped slaves skirmishes with a large B'rohg.  One of the escapees, a thri-kreen adept, deftly jumps among the boulders, uses it's unnatural speed and agility to skirt in and out of the reach of foe's long arms.  Finally, the adept quickly rushes between the  B'rogh's legs and delivers a final blow. The thri-kreen and it's companions are safe, for now.</p>

```
```

### Note: Adapting the adept
The Adept presented here is quite different from the Psion above.  As opposed to being a completely new class (with a new combat system), the Adept is primarily a mild re-skin of the standard monk class.  The monk as presented in 5th edition has powers that are essentially psionic in nature as well as psionic fictionally.  Given that, a few modifications were made to allow them to integrate into model of psionics above.

<p>The adept described below uses charisma (similar to the psion's spellcasting abilities) and constitution (representing their control over their body) instead of the wisdom and dexterity common to the monk.</p>

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 2 | The Adept</div>
\page 

<p>Described below are the modifications to the original monk class as well as a few notes on re-theming existing monk features.  A few of the subclasses are missing altogether as they do not fit fictionally with a monk powered by psionics.  The Way of the Four Elements, besides being generally thought of as poorly balanced, does not fit the psionic theme of the Adept, and any attempt to alter it would destroy its primary attraction.  It would almost be easier to make an entirely new subclass that had a skill menu.  The Way of the Sun Soul could probably be made useable, but it still requires more modification than just swapping the names around, so I have not adapated it for the time being.  The Way of Tranquility might fit within the theme of psionics presented here, but I have chosen not to adapt it since it is not thematically proper for my DarkSun campaign.</p>

### Body and Mind
Adepts of Athas spend years meditating and exercising.  During this time, they utilize their natural psionic abilities to gain mastery over their biology.  Through the training of the adepts, many impressive feats are possible, such as temporarily enhanced strength, faster movement, hardened skin, or more.  Although focused heavily on feats of physique, they also have no less a capable mind.

### Training and Asceticism
Adepts train for years under the guidance of a master.  These "schools" teach a variety of different techniques, passed down from master to student, and as those students grow not only under the guidance of their master but in their own rights, they may continue the lineage of their master or start a new school of their own (if they desire to take on students at all).  Some of their practices involve enduring extreme conditions in order to unlock the powers of the mind.

### Creating an Adept
One of the biggest questions to answer when creating an adept is to figure out why you are adventuring.  Many adepts roam Athas looking for tests of skill to prove their own mastery.  Others seek hidden knowledge to let them perfect a powerful technique.  Some, turned out by their school, seek adventure as simply a means to survival or to gather enough wealth to one day found their own school.  Others have important missions entrusted to them by their schools or other sources, and they use their powers to accomplish these tasks.
<p>Another thing to think about when creating your adept is what your school was like.  Was it a lone master helping you find time to train in private training halls, individuals' houses, or even the back alleys?  Was it a formal chartered institution near one of the major cities?  Perhaps it was a secretive recluse who trained her students, seeking revenge on one of her peers.</p>

### Quick Build
You can make an adept quickly by following these suggestions.  First, Constitution should be your highest ability score, followed by Charisma.  Second, choose *empty mind* and *feedback loop* as your known psionic modes.  Finally, choose the hermit background.

```
```

## Class Features
As the PHB Monk, unless otherwise noted.  Swap usages of dexterity for constitution generally, and exchange wisdom for charisma.

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
The number of additional Psionic Modes known above the base known by everyone (2).  When you create a 1st-level adept, you choose your known psionic modes instead of picking them randomly.

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
This particular subclass really needs no adaptations to survive.  *Wholeness of Body* allows regeneration in accordance with psychometabolic fiction.  *Tranquility* is a slight stretch fictionally but not completely out of bounds.

### Way of Shadow
This subclass stretches the fiction of psionics a bit, but at this time, I am content to leave it "as is" in lieu of adapting it since it seems like an otherwise fun and useful subclass.  I may one day provide a suitable alternative, but for now follow the notes below.

#### Shadow Arts
Instead of *darkness*, and *silence*, the adept should learn *blindness/deafness* and *hold person*.  Instead of the *minor illusion* cantrip, they should learn *mage hand*.

#### Shadow Step
I don't care for the explicit reliance upon shadow and would consider replacing the effect with that of *misty step*.  The adept can use a combination of speed, distraction, illusory body doubles, and chameleonic skin to achieve such speed.

#### Cloak of Shadows
Invisibility cannot be acheived telepathically since it would involve affecting the minds of too many entities at once.  Shadow based invisibility could be achieved by turning the skin and eye pigments black while possibly using some psychokinetic effect to distort or deflect incoming light.  Due to the limitations on being in shadow, this makes the effect presented actually work out ok, if not great.

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
The necrotic energy could be the result of a powerful negative biofeedback loop generated in the target.  Alternatively, the energy type could be changed to force or psychic for a more psychokinetic or telepathic touch.

### Way of the Drunken Master
This fiction is not appropriate for the DarkSun setting, which has a serious and grim tone, whereas the typical Drunken Master plays more of a humorous role.  However, from a mechanical perspective there is probably no purer implementation of the capabilities of an adapt focusing on psychometabolic enhanced combat.  This could be called **The Way of the Sandstorm** without changing any mechanics.  One slight modification would be to drop the Performance proficiency, and instead provide athletics or acrobatics which would see more usage.  Additionally, there is no fictional reason for this modified subclass to have brewer's tools, so either drop it completely (after all, they just upgraded performance to athletics/acrobatics) or let the player pick another tool or language.

### Way of the Kensei
Basically an adept who focuses on their weapon and instills psionic forces to it akin to the standard *PSI blades* class feature.  Without the standard monk fiction behind it, fictionally this is a boring class.  As an alternative, in the DarkSun setting, they should be considered adepts whose training had an emphasis on gladitorial combat.

#### Way of the Brush
This doesn't really fit thematically as writing is extremely uncommon on Athas.  Either drop this completely (it's next to useless in a standard game anyways...), or substitute another tool or language of the player's choice.

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 2 | The Adept</div>
\page

# Psionic Magic
Psionic spells have the potential to work much differently from those of standard magic.  There are several factors to consider, especially when considering how the two different fields interact.  There are roughly two different approaches to their interaction.  ...Counter-spells, anti-magic shells, dispel magic...</p>
<p>The first approach assumes that psionics and magic are two completely separate systems that do not interact except at the physical level.</p>
<p>The second approach privledges the power of magic to fundamentally alter/control the fabric of reality, and gives it power over psionics.  Magic may use or incorporate pieces of psionics, and psionics itself might be considered simply a very specialized form of magic.
Counter-spells, anti-magic shells, dispel magic.</p>

### Casting Psionic Spells
Psionics generally follow all the rules for casting spells, such as the rules for actions, choosing targets, casting time, duration, etc.  However, there are 3 key differences for psionic spells:</p>
<p>Psionic spells use PSI points instead of spell slots.  The PSI points for a spell are spent when the spell is cast.</p>
<p>The second key difference between psionic spells and normal spells is that psionic spells never require material, somatic, or verbal components.  That is not to say that gestures and sounds never accompany the casting of psionic magic, only that specific gestures and sounds are not.</p>
<p>The third and largest difference is the resolution of telepathic spells.  This is detailed below in the section dealing with psionic combat.</p>

## Psionic Combat
Psionic combat is intended to be a fun and unique system to engage your players  and lies at the heart of the fun of playing a psionicist (any character that has specific psionic powers, e.g. a psion or adept). Creating a unique system was essential to making the psion feel like more than just another type of wizard. Psionic combat involves 2 distinct parts that operate together:  psionic modes and psionic clashes.  To assist with this, I have provided a separate PDF that contains an info sheet displaying quickly how to resolve psionic clashes, as well as another sheet which contains images that can be cut out and used as cards to allow those in psionic combat to quickly and easily choose their modes.

```
```

### Psionic Modes
Psionic modes represent mental patterns that the mind naturally forms in reaction to the presence of an alien mind.  Psionic characters study these natural formations, and learn to exert a greater control over them.  Additionally, psionicists use these modes to perform telepathic attacks directly on the minds of others.
<p>Psions and adepts both gain psionic modes as part of leveling.  It is recommended that, in a world where this form of psionics exist, even non-psionic characters are able to form at least 2 modes, but only for the purposes of defense.</p>
<p>There are seven psionic modes:</p>

#### Ego Projection
Represented by the **plus** symbol, *ego projection* is an enhanced version of our ordinary sense of self and rationality, magnified to an extreme.  This can have the effect of avoiding the confusion that some modes create, but it falters against more subtle modes.

#### Empty Mind
Represented by the **circle** symbol, *empty mind* clears the mind of all activity.  This generally has the effect of pulling the ground out beneath some of the more aggressive modes, but it can be weak against other forms of disruptions.

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
A psionic clash is a contest between two opposing psionic characters using telepathic powers. Every telepathic spell used against an unwilling target initiates a psionic clash.  The psionic clash is used in place of the standard attack roll and/or spell save.  If the target is willing to undergo the effects of a telepathic spell no clash is necessary.
<p>If the attacker wins the psionic clash, their mind has penetrated the psionic defenses of their opposition.  The effect of their spell takes place with no additional attack or saving throw required.
<p>If the attacker does not win the psionic clash, they were unable to pierce through to their opponent's mind.  The PSI points and action are spent, and the spell does not take effect.</p>

#### How to determine the clash winner
Each character's controller secretly selects one psionic mode from the pool of their available psionic modes.  When both controllers are ready, their modes are revealed and resolved.</p>
<p>The easiest way to resolve the psionic clash is by using the chart provided in the second pdf. If that chart is not available, here is a description of how the chart works:</p>
<p>A given mode will beat the three modes to the right of it on the following list.  The end of the list wraps around to the front of the list to form a circular structure.  If a mode is pitted against itself, the attacker also does not win.  Here is the resolution order:</p>
  
   * *feedback loop* → *kinetic burst* → *synaptic static* → *empty mind* → *iron will* → *id insinuation* → *ego projection* →
  
<p>For example, if during a clash the two modes revealed are *ego projection* and *synaptic static*, the character using *ego projection* would win.  If that player had instead picked *iron will*, then the player who used *synaptic static* would win the contest.</p>
<p>Advantage and disadvantage:  This can easily be done for psionic clashes by having the advantaged party choosing two modes instead of one, then using whichever one is most advantageous.  Similarly a disadvantaged psionic combatant would play modes and use the more advantageous one.</p>

```
```

### Mass Telepathy
To stay on par with normal spell attacks, it is probably best to resolve each individual psionic clash, however, if that proves to be burdensome, there are a few options which may be utilized to speed things up.
<p>When a telepathic spell affects multiple targets, there are a few alternate methods to assist.  The below assumes that all the entities have no special telepathic powers.  For entities which do posses enhanced telepathics (i.e. psion or adept levels), resolve the psionic combat as normal.  For example, if a group of 3 untrained thri-kreen and 1 thri-kreen adept were to come under group attack, resolve the psionic combat with the adept as normal, and use one of the below methods for the 3 untrained thri-kreen.

#### Method One
Choose one card at random from all seven possible modes.  This represents the collective unconscious of the group as its minds awaken and interfere with each other chaotically.

#### Method Two
As above, but instead of choosing a mode randomly, choose one mode from a pool of all known psionic modes by any member of the group.

#### Method Three
Use method two, but break large groups into smaller groups whose members are similar.


<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 3 | Psionic Combat</div>
\page

# Adapting Psionics

## Psionics in a non-psionic world
When trying to integrate the psion and adept into a world where psionics is not ubiquitous, there are some significant challenges.  This class is built around frequent usage of the model of psionic combat provided.  Without psionic combat, a lot of the reason to play with psionics is lost.  Additionally, if too many changes to psionic combat are made, many of the subclasses lose their value.  While you could home-brew them to fix those issues, in my opinion you are better off using a lightly re-skinned version of the sorcerer or wizard and just positioning it fictionally as a psionicist.  However, I was able to come up with one approach which I think allows the class to function in a way that:
  * psionic players have fun with psionic combat and the class as written
  * non-psionic players aren't put off by it
  * and DMs do not need to do a lot of prep or background work in order to run it
    
Here is the rule:
<div class='descriptive'>
  When a non-psionic character enters into a psionic clash, their untrained mind naturally forms two of the seven psionic modes at random; that character's controller should pick two modes at random from the list of all available modes for that character to choose from for the purposes of psionic clashes.
</div>

### Spell-casting ability
I chose charisma for my setting, but this could easily be wisdom as well.  In my setting Warlocks use intelligence, and there are no bards or paladins.  I felt like I needed another charisma based class to round things out.  Thematically, charisma does fit with the manipulative nature of telepathic spells.  On the other hand, "Willpower" as a savings throw is more closely related to wisdom and allows it to fit together more in line with the monk, who also uses wisdom.

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 4 | Adapting Psionics</div>
\page

# Supplementary Rules

## Concentration
The rules for concentration are the same for casting psionic spells that require concentration.

## Multi-classing
Characters add all their PSI points together from all their psionic classes to form one pool of PSI points.  Psionic spells are completely different than their magical counterpart, and thus an individual multi-classed in such a way could have two copies known of the same spell: one psionic and one magical.

## Skills
The skill sections above for the psion and adept make reference to the *culture* and *parapsychology* skills.  In my home-brew version of DarkSun, the *history* and *religion* skills are not present, and culture has filled the gap they left behind.  If you are using this psionics home-brew in a world where those are present, it would be fitting to swap *culture* for *history*.

Additionally, I have created a *parapsychology* skill to function as an analogue of *arcana* for wizards and *religion* for clerics.  Although its function should be pretty obvious, I will provide its definition here.
<br>
<br>
<p>***Parapsychology.*** Your Intelligence (Parapsychology) check measures your ability to recall lore about psionics, psionic items, symbols, monsters, traditions, the function of the mind, and the interpretation of dreams.</p>
<br>
<p>If you wish to avoid introducing another skill to your game, this material could reasonably be handled with the *arcana* skill.</p>

## Feats

### Elemental Adept
Due to the prevalence of psionics in my setting, I also allow the "psychic" category of damage types to be chosen here.

### Mage Slayer
Casting a psionic spell still counts as casting a spell (both generally and specifically for this feat).

### Psionic Initiate
Similar to Magic Initiate, but only for psionic spells.  You follow the rules for casting spells as per the Psion class and gain 1 PSI with which to cast the level 1 spell chosen.  Charisma is the ability modifier for this spell.<br>
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
  - C - Clairsentience
  - P - Psychokinesis
  - T - Telepathy
  - t - Telepathy, no clash required
  
##### Cantrips (0 Level)
 - C - Blade Ward
 - P - Booming Blade
 - P - Control Flames
 - t - Friends
 - C - Guidance
 - P - Gust
 - P - Kinetic Blast
 - P - Mage Hand
 - t - Message
 - P - Mold Earth
 - t/PC - Psychonistry
 - C - Resistance
 - P - Shillelagh
 - P - Thunderclap
 - C - True Strike
 - T - Vicious Mockery

##### 1st Level
 - C - Alarm
 - T - Animal Friendship
 - t - Beast Bond
 - P - Catapult
 - T - Cause Fear
 - T - Charm Person
 - T - Command
 - T - Compelled Duel
 - C - Comprehend Languages
 - C - Detect Magic
 - C - Detect Poison and Disease
 - C - Detect Psionics
 - C - Detect Unnatural
 - T - Dissonant Whispers
 - P - Featherfall
 - P - Floating Disk
 - t - Heroism
 - T - Hideous Laughter
 - C - Identify
 - P - Jump
 - P - Magic Missile
 - P - Shield
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
 - P - Levitate
 - C - Locate Animal or Plants
 - C - Locate Object
 - C - Magic Aura
 - T - Mind Spike
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
 - P - Arcane Hand
 - C - Contact Other Plane
 - P - Control Winds
 - P - Destructive Wave
 - T - Dominate Person
 - T - Dream
 - T - Geas
 - P - Hold Monster
 - C - Legend Lore
 - T - Modify Memory
 - C - Scrying
 - T - Synaptic Static (Spell version from Xanathar's)
 - P - Telekenesis
 - t - Telepathic Bond
 - P - Wall of Force

##### 6th Level
 - P - Blade Barrier
 - P - Disintegrate
 - C - Find the Path
 - P - Globe of Invulnerability
 - t - Irresistible Dance
 - T - Mass Suggestion
 - T - Mental Prison
 - C - True Seeing

##### 7th Level
 - P - Forcecage
 - t - Power Word Pain
 - P - Psionic Sword
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

#### Kinetic Blast

*Psychokinesis cantrip*
___
- **Casting Time**: 1 Action
- **Range**: 120 feet
- **Duration**: Instantaneous

An invisible bolt of energy streaks toward a creature within range. Make a ranged spell attack against the target. On a hit, the target takes 1d8 force damage. The spell creates more than one bolt when you reach higher levels - two bolt at 5th level, three bolt at 11th level, and four bolt at 17th level. you can direct the bolt at the same target or at different ones. Make a separate attack roll for each beam.

#### Psychonistry
*General cantrip*
___
- **Casting Time**: 1 Action
- **Range**: 10 feet
- **Duration**: Up to an hour

This spell can be used to generate minor psionic effects, similar in nature to *presdidigitation* or *thaumaturgy*.  The DM will adjudicate the exact effects possible, but some examples might be: poke someone, give an object a small push, open and rattle windows or curtains, cause a small effect in the mind of an individual such as a brief sensation, emotion, or thought that is obviously psionic in nature, getting a brief glimpse of a nearby hidden object, hearing a word or short phrase from across the room, glimpsing a minor characteristic of an event in the very near future, etc.

#### Detect Psionics
*Clairsentience cantrip*
___
- **Casting Time**: 1 Action
- **Range**: self
- **Duration**: Concentration, up to 10 minutes

For the duration, you sense the presence of psionics within 30 feet of you. If you sense psionics in this way, you can use your action to see a faint aura around any visible creature or object in the area that bears psionics, and you learn its school of psionics, if any. The spell can penetrate most barriers, but is blocked by 1 foot of stone, 1 inch of common metal, a thin sheet of lead, or 3 feet of wood or dirt.

#### Counterpsionics
*Clairsentience Cantrip*
___
- **Casting Time**: 1 Reaction, which you take when you see a creature within 60 feet of you using psionics
- **Range**: 60 feet
- **Duration**: Instantaneous

You attempt to interrupt a creature in the process of using psionics. If the creature is using psionics of 3 PSI lower, its spell fails and has no effect. If it is using psionics of 4 PSI or higher, make an ability check using your spellcasting ability. The DC equals 10 + the spell's PSI level. On a success, the creature's spell fails and has no effect. At Higher Levels: When you cast this spell using a 4 PSI or higher, the interrupted spell has no effect if its PSI level is less than or equal to the level of PSI you used. 

<div class='pageNumber auto'></div>
<div class='footnote'>Chapter 6 | Psionic Spells</div>
