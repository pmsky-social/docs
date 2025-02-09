# Privacy

Moderation can be a sensitive subject.  Generally on ATProto, the data you create is yours, and public.  But, especially when it comes to harassment, a user might not want the labels they create, or the votes they submit to be published on the network.

When you create a label, we treat that as the platform's label.  That means the AT record shows up in the PDS for @pmsky.social, rather than your own.  It also means that once created, you can no longer delete a label.

When you vote on a label, we only save _that you voted_ on that label, not _how_ you voted.  We also track that someone voted that label up/down, and publish that as a record to the @pmsky.social PDS.

## Tradeoffs

This privacy has tradeoffs.  It means that other users have to trust the platform not to manipulate votes, for example.  As the platform grows, it might be the case that only public votes are counted, or that they're more trustworthy.  There is a spectrum between complete privacy and a more complete featureset, and we'll aim to have flexibility to allow the user to decide for themselves how their participation fits into the wider picture.

## Future Directions

In the future, we'll allow for users to publish these records to their own PDS if they wish to have public votes (e.g. for user-specific labeling, publish X label if Y user(s) voted on it).

Another feature is semi-private voting, where the platform saves how you vote internally to allow you to change your votes.  As-is, voting is irrevocable since we're going for safety & privacy over convenience at first.  If enabled, this would be a setting you can enable, not something you're opted into without notice.
