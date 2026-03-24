# cis2001-project3
commander and creature battle simulation using python
overview:
this project simulates a battle system betwwen two commanders. Each commander controls a collection od creatures. The creatures fight based on their strength and defense values.
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

