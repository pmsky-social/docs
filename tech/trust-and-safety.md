# Trust & Safety

In building infrastructure around moderation, trust and safety are paramount.  To reduce the potential of issues with the platform, we're taking a number of steps to minimize risk as the platform is developed.

## Initial Labels and Users

At first, only a small set of labels will be allowed, hardcoded into the app.  Over time, users will be able to introduce labels, which will be added to the set of allowed labels based on other users' votes on those proposals.  Additionally, the initial set of users will also be limited during initial testing.  Again, new users can be proposed & voted on to be added to the whitelist.

## Opt-in Nature of Labeling

The larger ecosystem of labeling on bluesky makes it fairly resistant to abuse.  A labeler can publish incorrect or negative labels, but only those who subscribe to it will see those labels on their feed. &#x20;

In the case of labelers that leverage pmsky vote data, those labelers will serve small use cases and be independent from the platform, rather than providing one monolithic labeler.  This provides users with fine-grained control over their labeler experience on bluesky, and puts the onus on labelers for adequately mitigating anti-social behavior.  The worst case scenario for a user is the same as the baseline on bluesky, where they are not subscribed to any 3rd party labelers.&#x20;

## Layers of Protection

For users that do subscribe to labelers driven by pmsky data, there are two main layers of protection: the platform itself, and the labelers built on top of pmsky.

### Protection on PMsky

We already require a bluesky account to interact with the platform, but as activity ramps up we can require verified emails, accounts over a certain age, or even implement reputation systems to weigh or eliminate votes from problematic accounts. &#x20;

### Labeler-Level Protection

Part of the ethos driving pmsky is one of building blocks and interoperability.  This allows for some labelers to assume more risk while others make their decisions more conservatively.  The end-user is then able to subscribe to labels that fit their apetite, fine-tuning their personalized signal-to-noise ratio.  As the platform grows, more sophisticated labelers will be built with better mechanisms to defend against harassment and gaming the system. &#x20;

## Potential Threats

### Targeted Harassment

The hope is that pmsky allows users to mitigate harassment via community labeling & defense, however it's also possible that the platform is abused to produce harassment itself.  Like any other system, its mechanisms can be gamed such that unsavory or misleading labels are published. &#x20;

This can be mitigated with high consensus levels, reputation systems, or public votes.  For example, if a label requires a 90% level of agreement, it only takes 10% of users to block that label from being published.  Public votes also allow labelers to associate accounts with problematic behavior, and reputation systems could be built based on voting and other behavior on the platform.

### Sybil attacks

A [sybil attack](https://en.wikipedia.org/wiki/Sybil_attack) involves a bad actor using multiple fake identities to carry out abuse of a system.  A bluesky account is required to vote on pmsky, but a bad actor could programmatically create hundreds or thousands of accounts to manipulate votes.  This can be mitigated by requiring email verification, or putting up roadblocks based on account age, activity, reputation, etc. &#x20;

To mitigate these behaviors, pmsky will begin as a closed platform, evolving to invite-only over time.  It will not be open to the public until sufficient safeguards have been put in place.

