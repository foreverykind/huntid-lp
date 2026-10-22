# HuntID landing

Public marketing site for the HuntID Chrome extension: explains the product, lets visitors try a tracklist search without installing, and sends them to the Chrome Web Store or a paid plan.

## Language

**Search hero**:
The first screen of the landing, where a visitor pastes a SoundCloud mix link and gets its tracklist without installing the extension.
_Avoid_: hero-cta, paste box

**Featured mix**:
A mix picked from the latest top-rated tracklists and shown inside the **Search hero** as a one-click example search.
_Avoid_: Recommended mix, pick

**Tracklist**:
The ordered list of tracks in a mix, with timecodes where known.

**Search**:
One lookup of a mix's **Tracklist**, and the unit that plans are metered in ("10 searches free").
_Avoid_: sync, lookup, scan

**Free plan**:
The no-card plan every account starts on, with a capped number of searches.

**Pro plan**:
The paid plan with unlimited searches, billed monthly or annually. Its prices always come from the live pricing source, never from page copy.
_Avoid_: Hunter, Scout, subscription tier

**Analyse**:
A feature in development that identifies tracks from a mix's audio when no **Tracklist** exists anywhere. On the site it is announced as "launch soon" only; it has no plan, price or tokens yet.
_Avoid_: Audio recognition tokens, analysis credits

## Relationships

- The **Search hero** shows a strip of **Featured mixes**; clicking one runs the same search as pasting its link.
- A search returns a **Tracklist**.
- An account is on exactly one of **Free plan** or **Pro plan**. A future plan will ship together with **Analyse**.

## Example dialogue

> **Dev:** "Does the Recommended block from the design become its own section?"
> **Domain expert:** "No — those are **Featured mixes**, and they stay in the **Search hero**. Only their card look comes from the design."

## Flagged ambiguities

- The design labels **Featured mixes** "Recommended" — resolved: same concept, canonical name is **Featured mix**.
- The design names plans Scout/Hunter in places and sells recognition tokens — resolved: only **Free plan** and **Pro plan** exist; **Analyse** has no pricing yet.
- The design meters usage in "syncs" — resolved: the unit is **Search**, matching the legal pages.
