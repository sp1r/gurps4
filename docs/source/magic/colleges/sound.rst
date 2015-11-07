************
Sound spells
************


Заклинания, которые производят звук "субьект" - это точка, из которой звук исходит.


=============================================== =========================================== ================================
Spell                                           Requires                                    Classes
=============================================== =========================================== ================================
:ref:`Sound <spell__sound>`                                                                 Regular
:ref:`Silence <spell__silence>`                 :ref:`Sound <spell__sound>`                 Area
:ref:`Thunderclap <spell__thunderclap>`         :ref:`Sound <spell__sound>`                 Regular
:ref:`Voices <spell__voices>`                   :ref:`Sound <spell__sound>`                 Regular
:ref:`Garble <spell__garble>`                   :ref:`Voices <spell__voices>`               Regular, Resisted by Will
:ref:`Wall of Silence <spell__wall_of_silence>` :ref:`Silence <spell__silence>`             Area
:ref:`Hush <spell__hush>`                       :ref:`Silence <spell__silence>`             Regular, Resisted by Will
:ref:`Great Voice <spell__great_voice>`         :ref:`Thunderclap <spell__thunderclap>` and Regular
                                                :ref:`Voices <spell__voices>`
:ref:`Delayed Message <spell__delayed_message>` :ref:`Magery 1 <skill__magery>`,            Area
                                                :ref:`Sense Life <spell__sense_life>` and
                                                :ref:`Voices <spell__voices>`
:ref:`Converse <spell__converse>`               :ref:`Magery 1 <skill__magery>`,            Regular
                                                :ref:`Garble <spell__garble>` and
                                                :ref:`Silence <spell__silence>`
:ref:`Far-Hearing <spell__far_hearing>`         :ref:`Magery 1 <skill__magery>`,            Information
                                                4 other sound spells
:ref:`Message <spell__message>`                 :ref:`Seeker <spell__seeker>` and           Regular, Resisted by spells that block sound
                                                :ref:`Great Voice <spell__great_voice>`
=============================================== =========================================== ================================


.. _spell__sound:

Sound
=====

| **Prerequisite**: None
| **Classes**: Regular
| **Duration and cost**: 1 to create 5 seconds of sound; 2 to create a sound that
  lasts for a full minute; 1 per minute to maintain

Produces any sort of meaningless
sound the caster wishes – the drone of
an insect, the distant babble of voices,
the clatter of something falling, or
anything similar. The spell cannot
produce
loud
noise. It requires no
concentration once the spell is cast.





.. _spell__silence:

Silence
=======

| **Prerequisite**: :ref:`Sound <spell__sound>`
| **Classes**: Area
| **Duration**: 1 minute
| **Base Cost**: 2 to cast, 1 to maintain

Creates an area of quiet. No one
within this area can hear anything,
and nothing that happens in this area
makes any sound. It is the area that is
affected and not the people in it; anyone moving out will be able to speak.
Note that an area of silence will
prevent spoken spells from working!



.. _spell__thunderclap:

Thunderclap
===========

| **Prerequisite**: :ref:`Sound <spell__sound>`
| **Classes**: Regular
| **Duration**: instant
| **Base Cost**: 2

Produces a single loud sound like
an explosion or crash of thunder. The
“subject” is the spot the caster chooses
as the spell’s center. Outdoors, anyone
within 3 yards of this place must make
a HT roll or be deafened; anyone deafened may roll vs. HT every hour to
recover. In an enclosed area – less than
10 yards in any dimension – increase
this distance to 6 yards! The caster
makes his roll at HT+2.



.. _spell__voices:

Voices
======

| **Prerequisite**: :ref:`Sound <spell__sound>`
| **Classes**: Regular
| **Duration**: 1 minute
| **Base Cost**: 3 to cast, 2 to maintain

Produces a meaningful sound –
voices, music, etc. – of normal speaking volume. Requires constant
concentration on the part of the caster.




.. _spell__garble:

Garble
======

| **Prerequisite**: :ref:`Voices <spell__voices>`
| **Classes**: Regular; Resisted by Will
| **Duration**: 1 minute
| **Base Cost**: 4 to cast, 2 to maintain

The subject (a living being) can no
longer make meaningful sounds; it
comes out completely garbled. This
spell could make an opposing wizard
powerless!





.. _spell__wall_of_silence:

Wall of Silence
===============

| **Prerequisite**: :ref:`Silence <spell__silence>`
| **Classes**: Area
| **Duration**: 1 minute
| **Base Cost**: 2 to cast, 1 to maintain


Surrounds the affected area with a
wall that sounds will not pass. Those
within it cannot hear outside sounds,
or be heard by those outside. Casting
of spoken spells is unaffected.




.. _spell__hush:

Hush
====

| **Prerequisite**: :ref:`Silence <spell__silence>`
| **Classes**: Regular, Resisted by Will
| **Duration**: 10 seconds if subject attempted to resist, 1 minute otherwise.
| **Time to cast**: 2 seconds
| **Base Cost**: 2 to cast, 1 to maintain

The subject (an object or living
being) can make no sounds, either
accidentally or on purpose. Add 3 to
the subject’s Stealth skill whenever a
roll is necessary, or subtract 5 from the
Hearing roll of anyone listening for
the subject. This spell can silence an
opposing wizard in battle!




.. _spell__great_voice:

Great Voice
===========

| **Prerequisite**: :ref:`Thunderclap <spell__thunderclap>` and :ref:`Voices <spell__voices>`
| **Classes**: Regular
| **Duration**: 1 minute
| **Time to cast**: 2 seconds
| **Base Cost**: 3 to cast, 1 to maintain

The subject can be heard clearly and
distinctly by everyone he can see, even
at a great distance. The subject can
choose to be heard by only a few chosen
targets if he specifies before speaking
(those within ordinary earshot will hear
him whether he wants it or not, of
course). Note that, for instance, one
could not cut off the subject’s voice by
ducking behind a rock. This spell is
widely used by ship captains, military
commanders, and public speakers. The
sound may become irritatingly loud if
the original voice is loud, but will not
deafen or cause harm.




.. _spell__delayed_message:

Delayed Message
===============

| **Prerequisite**: :ref:`Magery 1 <skill__magery>`, :ref:`Sense Life <spell__sense_life>` and :ref:`Voices <spell__voices>`
| **Classes**: Area
| **Duration**: Until the specified person arrives.
| **Time to cast**: 4 seconds
| **Cost**: 3 per simple sentence – one idea per sentence, cannot be maintained

Creates an oral message, which can
be delayed to go off until a certain per-
son, specified at casting, arrives in the
area. The recipient hears it clearly,
regardless of other noise, but nobody
else hears it. A Detect Magic spell cast
in the area reveals that it contains a
delayed message, but only a critical
success reveals more. A critical success
reveals one of the following (roll ran-
domly): the sender, the intended recip-
ient, or the words (not any hidden
meanings) of the message.
This does not count as a “continu-
ing spell” – the mage casts it and
forgets about it.




.. _spell__converse:

Converse
========

| **Prerequisite**: :ref:`Magery 1 <skill__magery>`, :ref:`Garble <spell__garble>` and :ref:`Silence <spell__silence>`
| **Classes**: Regular
| **Duration**: As long as eye contact is maintained.
| **Time to cast**: 4 seconds
| **Cost**: 2

Allows the caster and his subject to
converse quietly without fear of eaves-
dropping, even in a noisy environment
(such as a raucous party). Each one
will hear the words of the other clear-
ly regardless of the surrounding din.
Other beings within earshot will hear
a meaningless buzz of conversation.
Converse resists spells that block
sound such as Silence or Noise.



.. _spell__far_hearing:

Far-Hearing
===========

| **Prerequisite**: :ref:`Magery 1 <skill__magery>`, 4 other sound spells
| **Classes**: Information
| **Duration**: 1 minute
| **Time to cast**: 3 seconds
| **Cost**: 4 to cast. 2 to maintain

The caster can hear any conversa-
tion that he can see, even at a great
distance, or hear through solid objects
totaling no more than six feet of thick-
ness. He automatically makes all
Hearing rolls.
This is also a Knowledge spell.





.. _spell__message:

Message
=======

| **Prerequisite**: :ref:`Seeker <spell__seeker>` and :ref:`Great Voice <spell__great_voice>`
| **Classes**: Regular; Resisted by spells that block sound
| **Duration**: The message travels to the subject at 50 mph. This speed doubles when the casting cost is doubled
| **Time to cast**: 3 seconds
| **Cost**: 1 per 15 seconds of message duration


Send a spoken message to a sub-
ject. Use the long-distance modifiers
(p. 14). If the caster doesn’t know the
subject, he is at -2. If he doesn’t know
the subject’s whereabouts, he is also at
-5 (a successful Seeker spell will elim-
inate this). These penalties may be
cumulative. A successful Trace gives a
+5 bonus.
The subject hears the message
clearly and distinctly whatever his
sonic surroundings, but nobody else
hears it. Silence, Wall of Silence, and
Noise will resist the incoming message.
This is also a Communication and
Empathy spell.






