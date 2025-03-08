---
description: This page describes the lexicon defined and used by pmsky
---

# Lexicon

PMsky defines two main record types: labels, and votes.  The former is heavily based on the definition in use by ATproto itself [here](https://github.com/bluesky-social/atproto/blob/a8f06939f94b3a5efee4b56c4de0e36502ff15fd/lexicons/com/atproto/label/defs.json#L5). &#x20;

## Proposals

```
// social.pmsky.proposal
```

These records closely mirror that of an Atproto Label, defined in `com.atproto.label.defs#label`.  They have a _subject_, which is another record they apply to, and a _value_, which is the text of the proposal itself.  There is also a `type`, which determines which type of proposal the record is.  The two current types of labels are `POST_LABEL` and `ALLOWED_USER`, respectively referring to a label on a bsky post and whitelisting a user to the pmsky platform.

See the full definition here: [https://github.com/pmsky-social/app/blob/main/lexicons/proposal.json](https://github.com/pmsky-social/app/blob/main/lexicons/proposal.json)&#x20;

## Votes

```
// social.pmsky.vote
```

Votes are similar to labels, in that they have a _subject_ they apply to.  They also have a _value_, which is either `1` or `-1`. &#x20;

See the full definition here: [https://github.com/pmsky-social/app/blob/main/lexicons/vote.json](https://github.com/pmsky-social/app/blob/main/lexicons/vote.json)

