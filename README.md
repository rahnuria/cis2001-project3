# cis2001-project3
commander and creature battle simulation using python
overview:
This system simulates a battle between two commanders using a sorted linked structure of creatures. Creatures are deep copied and inserted based on defense and strength. During battle, creatures fight pairwise, and damage is calculated using strength vs defense. Dead creatures are removed, and if one commander runs out of creatures, the remaining creature deals damage to the commander.defense values.
FEATURES:
.Deep copy of creatures.
.Sorted insertion based on defense and strength.
.battle simulation between two commanders.
. Proper removal of creatures when defeated.
.Commander takes damage when creatures are exhausted.
CLASSES Creature
.strength(int)
.defense(int)
.next_creature(refesrence)
METHODS:
addCreature (creature)
.adds a deep copy of the given creature.
.maintains sorted order.
.Highest defense first.
.if equal defense,higher strength first.
.BATTLE LOGIC(other_commander):
.simulates battle betwwen two commanders.
.possiblenoutcomes.
.both creatures die.
.one creature dies.
.no creature dies(stop battle)
.commander takes damge id creatures are gone..
EXAMPLE OUTPUT:

