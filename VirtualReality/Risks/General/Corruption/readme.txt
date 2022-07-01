A corrupted bit could have vast consequences
where a VR world state can be altered drastically.
The general problem is that VR doesn't lend
well to coarse backups/rollback scenario
with dynamic worlds generating
enormous amount of content that is temporally
relevant and would be much more annoying 
to restore: e.g. moving all players and 
objects to some arbitrary point in time,
ruining immersion and deleting all new content.
The likely strategy would be fine-grained
 backups of individual objects that are restored to their
 "last good configuration".
This strategy will have following problems:
1.Dynamic and temporary states of objects
as sequence from backup point would likely
be absent as their uncorrupted/corrupted status
is in question and cannot be trusted:
limited backups would also limit "permanence" of
object state to series of "save points".

2.Corruption would have to be detected
before it cascades:some changes would appear
to viewers as "glitches" but invisible 
corruption will create harm before its visible.
A set of monitoring programs have to scan
and verify all objects before each interaction,
adding overhead to all dynamic content.

3.Malicious exploits would abuse corrupted
objects before they are detected and 
even use hardware-oriented attacks to trigger
corruption(usually by overload of some property)

4.Avatar corruption could have health effects
and add imperceptible psychological harm.
Immersion itself requires that avatar of a person
 functions as expected.
