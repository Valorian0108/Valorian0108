# Ifeoluwa Oludemi

I build the rule layer for AI agents that spend money. The limits are
enforceable, the agent cannot exceed them, and the owner does not have to
trust anyone for them. I live in Nigeria. I work solo and in public.

## The position

An AI agent can hold real spending power without being trusted with a wallet.
Code on a public network enforces the limit. Instructions in a prompt do not.
Every decision leaves a readable record that cannot be tampered with.

Four separable parts make up the primitive. Everything I build is some
combination of them.

- A policy engine evaluates rules in a fixed order and returns a readable
  reason for every refusal.
- A scoped identity gives the agent a key that reaches exactly one door, so a
  leaked key is contained before policy matters.
- An escalation path lets small amounts flow and makes large amounts wait for
  a human who can refuse them.
- An audit log writes every decision down permanently with its reason.

The design is chain-agnostic on purpose. NEAR and Starknet are reference
implementations rather than the product.

## The method

The method has two stages and both are written down.

Discovery comes first. I enter a domain I do not know and I question an LLM as
a teacher. I ask questions only and I build nothing until a thesis emerges
that I can hold. I do not build on a stimulus or a mood.

The gate comes second. The AI advises and drafts while I decide. Nothing is
built until it is written down and approved. Every decision is logged with its
reason, the alternatives considered, and the person who decided. Open
questions stay visible until I close them.

[link to AGREEMENT.md, the decision log, or the methodology essay]

## Selected work

- mandate-near is a spending vault on the NEAR testnet. An agent can ask it to
  pay, but it cannot withdraw money, change the rules, or approve itself. A
  scoped key and the vault rules form two independent walls. Five attack
  scenarios predict their own outcome, and anyone can read the receipts.
- mandate is the same policy layer on Starknet. It has 378 passing tests and
  live proofs that anyone can verify.
- zarcade is an arcade that teaches Zcash privacy with real testnet money. A
  reader can check every claim on the explorer.
- permanence-protocol timestamps content hashes on chain. It ships with a
  Limits table that states exactly what it cannot prove.

Every repository ships with its limits. That means what it proves and what it
does not prove. If a claim cannot be checked, I do not make it.

## Writing

- The methodology essay explains how a solo builder keeps an AI accountable.
- Tutorials and paid writing live here.

## Open to

I welcome grants and funded work on agent-policy infrastructure. I welcome
documentation and tutorial bounties. I welcome collaboration on the rule layer
for autonomous spenders.

ifeoluwaoludemi34@gmail.com | @ifeteddy0108 | [Zcash forum profile]
