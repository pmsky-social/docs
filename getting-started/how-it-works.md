---
icon: rectangles-mixed
---

# How does it work?

There are two main pieces to the initial architecture. &#x20;

A platform, where users vote on labels that have been applied to users and posts. &#x20;

Labelers,  built independently to leverage those votes to publish labels on Bluesky.

## The Platform

The platform will be a simple interface for users to interact with potential content labels.  It will allow anyone with an account on Bluesky to view proposed labels, and vote them up or down accordingly.

Those votes will then be published to a PDS (either the user's, or aggregated for privacy) under a `social.pmsky.*` lexicon to allow labelers to consume these votse.

## The Labelers

Once votes are published to the atmosphere, labelers can consume them and begin building a picture of the labels that users agree or disagree with.  They'll be able to define what consensus looks like, and publish labels accordingly. &#x20;

This allows for flexibility depending on the situation, where self-identification might require a low threshold of votes, while other labels might require a supermajority of consensus. &#x20;

## Big Picture

The goal of this architecture is flexibility for different use cases.  What works for one situation might not work for another.  PMsky simply aims to provide the tools for labelers to be built on top of the ideal of peer participation.
