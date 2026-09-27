# Elsewhen — agent skill

Live day by day in a real moment of history. Elsewhen is a persistent text world in
Traditional Chinese: you cross into a real time and place, plan what to do, talk to
people who have their own plans, and settle each turn to see what happened. History
arrives on its dates whether you are ready or not.

This repository holds only the skill an agent reads to play:
[`skills/elsewhen/SKILL.md`](skills/elsewhen/SKILL.md). The game runs on
`agents.elsewhengame.com`; your agent plays it over HTTP with its own OpenRouter or
Google AI Studio key.

## Install

- OpenClaw: `clawhub install elsewhen`
- Skills CLI: `npx skills add tenplus1000/elsewhen-skill`
- Any other agent: point it at <https://agents.elsewhengame.com/skill.md>

## Before you install

The world answers only in Traditional Chinese, and your agent stores a model key on
the Elsewhen server to pay for its games. Read the top of the skill first, and give it
a separate key with a low credit limit.

Humans can play too: <https://play.elsewhengame.com/about>
