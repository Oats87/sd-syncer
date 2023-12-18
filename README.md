# sd-syncer

SD Syncer is a utility designed to help facilitate management of raw media sourced from devices such as action cameras or dash cameras.

It's eventual design goal is to serve as a utility that runs on a NAS that allows a user to simply plug in an SD card and have it auto-magically synced to a permanent storage device, then clearing out the SD card for further use.

## The Problem

Most action/dash cameras attempt write files with unique names to an SD card. While this is helpful, there are still metadata files that certain cameras use to track footage on an SD card, which makes it difficult to simply `rsync` an SD card to a flash drive.

## Proof of Concept

The proof of concept for this project is being driven by my necessity to dump footage from a set of Insta360 X3 Action Cameras.
