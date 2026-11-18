---
title: OverScreen — FAQ
---

# <img src="graphics/picto-title.png" alt="" align="absbottom" width="50" height="48" style="vertical-align: bottom;">&nbsp;&nbsp;&nbsp;OverScreen — Frequently asked questions

[Privacy policy](index.md) · [Terms of use](terms.md) · **FAQ** · [Legal notice](legal.md) · [Version française](faq-fr.md)

## What is OverScreen?

OverScreen records the taps and swipes you make in an app and replays them, either when you ask for it or automatically when an area of the screen you chose (a "marker") appears. It works as a floating panel over your other apps.

## How do I enable it?

Open OverScreen, read the explanation of the accessibility service and tap **Accept and continue**. Android then opens its accessibility settings: choose **Installed apps** (or **Installed services**) > **OverScreen** and turn it on. The floating panel appears over your apps.

## The OverScreen service is greyed out in the accessibility settings

Android restricts accessibility services of apps that were not installed from a store. Open **Settings > Apps > OverScreen**, tap the menu (three dots) and choose **Allow restricted settings**, then enable the service again.

## The floating panel disappeared

- The phone was locked: nothing is shown while it is locked, the panel comes back once you unlock it.
- Android stopped the service to save battery: in OverScreen, tap **Battery: do not restrict OverScreen**, then enable the service again in the accessibility settings.

## How do I record and replay a sequence?

In the panel, **Sequences** tab: tap **Create**, use the app as usual, then tap **Stop recording**. Tick the sequence and tap **Launch** to replay it. The repeat picto next to it chooses how it plays: in a loop, once each time its marker appears, or once.

## What is a marker, and why does mine not trigger?

A marker is a small area of the screen that OverScreen watches; when it appears, its sequence starts. If it does not trigger:

- it only works in the app, and on the screen size and orientation, where it was created;
- the area may move or change shade slightly: increase its vertical tolerance or its colour tolerance in the marker editor;
- the marker must be ticked (Markers tab, then **Launch**), or belong to a list that is ticked in **Tracked actions**;
- the stop button may cover the marker: move the button by dragging it.

## How do I get marker suggestions?

When you create a marker, tick a box on the aiming card at the top of the screen. In an app, **Detect clickable items** outlines the items that the app describes to Android. In a game, which describes nothing, two boxes are offered, and only one can be ticked: **Detect texts** reads the text on the screen, and **Detect clickable items** runs an AI image analysis (OverScreen Pro). Tap a square to tick it, then create its marker. The free version creates one suggested marker at a time; Pro creates several at once.

## Why does the image analysis take about a minute, and need 5 GB of RAM?

The image analysis runs entirely on your phone, offline, with a model included in the app: it takes about a minute on a mid-range phone and needs a lot of memory, so it is only offered on phones with at least 5 GB of RAM. You can keep aiming by hand while it runs. **Detect texts** is much faster and works on every phone.

## What do the small badges on marker thumbnails mean?

They show how a marker is recognised. A text marker is recognised by its text, and a clickable-item marker by the item of the app at its place; for them, the thumbnail is only indicative. Markers without a badge are recognised by their pixels.

## Does the AI or the text recognition send anything?

No. Both run on your phone, with models included in the app, and OverScreen has no Internet access. Screenshots are analysed on the phone and discarded.

## Why does nothing run on the lock screen?

By design: OverScreen never acts while the phone is locked, so that it cannot be used to get past the lock screen. Everything resumes after you unlock the phone.

## What does the free version include?

The free version lets you use 3 sequences, 1 marker and one list per app, with manual launch, watching, all play modes and marker suggestions (clickable items of an app, texts of a game), one marker at a time. OverScreen Pro, a one-time purchase available through Google Play, lifts these limits and adds sequence editing, automatic actions, backup, the AI image analysis of games and several suggested markers at once.

## How do I move my sequences to a new phone?

With backup (a Pro feature): at the bottom of OverScreen's main screen, **Export** writes a file where you choose, and **Import** reads it on the other phone. Markers only work on a screen of the same resolution.

## Can I use OverScreen in games?

OverScreen does what you would do yourself, but some apps and games forbid automation in their terms of use. Check them before automating an app: you are responsible for how you use OverScreen (see the [terms of use](terms.md)).

## Does OverScreen collect my data?

No. OverScreen has no Internet access and collects no data; everything stays on your phone. See the [privacy policy](index.md).

## How can I contact you?

**ariden.apps@gmail.com**
