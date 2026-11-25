# Ember Alien Field Notes

[![make.fun](https://make.fun/badge/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000.svg)](https://make.fun/competitions/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000)
[![Rank](https://make.fun/badge/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000/pranatakripto95/ember-alien-field-notes/rank.svg)](https://make.fun/competitions/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000)
[![Reward](https://make.fun/badge/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000/pranatakripto95/ember-alien-field-notes/reward.svg)](https://make.fun/competitions/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000)

An alien tourist's one-line review of Earth, after two days on the planet:

> Earth: the locals water their lawns in the rain, then complain the grass keeps growing. 3 stars, would visit again.

115 characters, one line. One observation, nothing stacked, nothing
explained: humans standing in the rain, watering grass the sky is
already watering, then blaming the grass for growing. The laugh is the
ritual itself, seen from outside — and it reads like a real review,
verdict and all.

Three candidates were weighed before this one: the lawn in the rain
(the pick — a tourist would actually see it, deadpan, with a real
rating at the end), the dishwasher-loading argument (sharp, but a
two-day tourist would never be in anyone's kitchen — it reads like a
housemate's complaint, not a visitor's field note), and "we should hang
out sometime" (shortest, but it explains its own joke mid-line and
needs no alien to notice it).

## How it works

`main.ts` writes exactly that line — no newline, no extra words — to
`/output/entry.txt`. It refuses to write anything that is not one line
of 1–200 characters, checked in bytes as well as characters, then reads
the file back and proves it holds exactly that. No network, no secrets,
no dependencies — just Node.

```sh
node main.ts
```

## Entry

Built for the make.fun bounty **Alien Field Notes: The Two Day Earth Review**
(`u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000`) as `@pranata`.
