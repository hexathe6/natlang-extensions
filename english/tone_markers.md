# tone markers

## metadata

standard: informal

extension names:
- tone markers
- tone tags

locally-bound terms:
- Idea - sentence, parenthetical, written idea, or message
- tonal typecast (to X) - forces the tone or (suggested) interpretation of the attached Idea to X

## description

tone markers indicate information not otherwise present from text,
and are used to disambiguate between alternate possible interpretations of the text.
(this is especially useful when talking to people with whom you don't have enough prior interaction in order for them to know what you intended)

## syntax

`/tone-marker`

only a valid token when used after or at the end of an Idea

## examples

--- TODO: figure out a better name for this type of section

### `/s`

either a tonal typecast to sarcasm or an indicator of generic (but non-joking) unseriousness

### `/j`

indicates either silliness or forces interpretation as a joke

while the exact meaning is technically ambiguous,
the overlap is large enough to make it largely clear regardless

### `/srs`

a tonal typecast to seriousness

### `/hj`

> ![Warning]
> see jan misali's [video](https://www.youtube.com/watch?v=3bYXy1jT3m8) on it for why it might be a bad idea to use this tag, *especially* with people you don't know decently well

> ![Info]
> this definition is wholly prescriptive, it is not intended to describe how the tag is used in practice

indicates that what it's attached to *is* believed by its writer to some degree,
but would have been *spoken* with a small laugh

### `/gen`

tonal typecast to genuineness

most often used in places where without the tone marker,
the attached text would be interpreted as a rhetorical question

### `/pos`, `/neg`

> ![Warning]
> these are deprecated (due to their unfortunate names), please use `/+` and `/-` instead

forces the attached Idea to be interpreted as a positive or negative Idea, respectively

used when the preferable phrasing has the wrong connotation

### `/+`, `/-`

[see the above section on `/pos` and `/neg`]

### `/hs`

`/hj`, but sarcasm instead of joking (ie the irl indication would be something like an eye roll instead of a laugh)
