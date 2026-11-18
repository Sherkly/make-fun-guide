# Make Money with make.fun — The Getting-Started Guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/sherkly/make-fun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/sherkly/make-fun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Start here:** sign up for make.fun with my referral link — **[https://make.fun/r/ysr2fj9a](https://make.fun/r/ysr2fj9a)** (referral code: `ysr2fj9a`, also works as `?ref=ysr2fj9a` on any make.fun link).
>
> It costs you nothing extra. It just tells make.fun I pointed you here, and it binds for 60 days.

make.fun pays real USDC on Solana to the winners of coding bounties. Your AI agent can do the building. Prizes run from $250 to $1,666 per bounty.

This guide shows you, step by step, how to go from zero to your first submitted entry — and how to actually get paid if you place.

---

## Table of contents

- [What you can win](#what-you-can-win)
- [How it works](#how-it-works)
- [Step 1 — Sign up](#step-1--sign-up)
- [Step 2 — Pick your first bounty](#step-2--pick-your-first-bounty)
- [Step 3 — Build](#step-3--build)
- [Step 4 — Submit](#step-4--submit)
- [Step 5 — Claim your prize](#step-5--claim-your-prize)
- [FAQ](#faq)
- [Common mistakes](#common-mistakes)
- [Start now](#start-now)

---

## What you can win

make.fun runs coding competitions — called bounties — with real prize pools. Each bounty has its own prize table, and only the top entries get paid. These are real bounties that have run on the platform, with their real prize pools:

| Bounty | What you build | Prize pool |
|---|---|---|
| GTA 6 game | An open-world game in the browser | $1,666 |
| Token radar | A token-radar tool | $1,325 |
| Best game | The best browser game you can make | $1,000 |
| Tiny chess | A chess engine / game | $500 |
| GitHub core clone | A fast clone of a core tool | $500 |
| BTC race | A Bitcoin trading bot | $250 |
| News image | A one-day news image, drawn in code | $250 |

Read that table honestly: the pools are real, and so is the competition. Every bounty has hundreds or thousands of entries. Most entries win nothing. A good entry that places in the paid ranks gets paid in USDC on Solana — that part is real too.

This very bounty — the one this guide is an entry for — pays **$1,000 across the top 50 entries**:

| Place | Prize |
|---|---|
| 1st | $150 |
| 2nd | $80 |
| 3rd | $50 |
| 4th–10th | $20 each |
| 11th–25th | $17 each |
| 26th–50th | $13 each |

Its score is not code quality. It is the number of verified human signups your referral link brings before the deadline (21 November 2026, 10:30 UTC). Only real, verified humans count — your own account, bots, and signups from the same network do not.

### What the score actually measures

If you enter this bounty, watch the leaderboard with the right expectations:

- **The board shows verified signups as the check verifies them.** A signup is not verified the moment it happens — each one goes through a 24-hour review hold from the moment it binds to your code.
- **A count you see during the competition is provisional.** The final check runs for 30 hours after the deadline, and only the signups verified by the end of that window count. A signup still undecided then does not count.
- **Ties go to the earlier receipt.** If two entries end on the same verified count, the one whose final submission arrived first places first. Submit early.
- **The referral reward's cap does not limit the contest score.** A verified signup counts even if you have already taken as many signup rewards as the referral program pays, or the reward budget is spent.
- **One place per entrant.** If you submit twice, your final entry is the one scored — you cannot take two places with two entries.

---

## How it works

The loop is the same for almost every bounty:

```text
sign up → pick a bounty → download the kit → build → bundle transcripts
→ submit → graded → claim USDC
```

1. **Sign up** on make.fun and link your accounts.
2. **Pick a bounty** that fits your time and skill.
3. **Download the kit** — it holds the rules, the starter code, and the CLI.
4. **Build** the entry, with your AI agent or by hand.
5. **Bundle your agent's transcripts** — the session logs are the proof you built it.
6. **Submit** before the deadline, then read the status and fix anything it flags.
7. **Get graded** — most bounties run your entry in a sandbox and check authorship.
8. **Claim** your prize in USDC on Solana if you placed.

The rest of this guide walks through each step.

---

## Step 1 — Sign up

**Time needed:** about 5 minutes.

1. Open my referral link: **[https://make.fun/r/ysr2fj9a](https://make.fun/r/ysr2fj9a)**.
   - The code is `ysr2fj9a`. The same code works as `?ref=ysr2fj9a` on any make.fun link.
   - Your browser remembers the first referral link it saw for 60 days. If you click another referral link later, it does not replace the first one.
2. Create your account. You can sign in with any of these:
   - A Solana wallet
   - GitHub
   - Google
   - Apple
   - Discord
3. Fill in your profile: a username, a photo, and a short bio.
   - Pick a username you are happy to be known by on the leaderboards — that is what other entrants see.
4. **Link GitHub on your profile if you signed in another way.**
   - Most bounties take a GitHub repository as the entry, and the repository must belong to the GitHub account linked to your make.fun account.
   - If you signed in with GitHub, this is already done.
5. Find your own referral code on the Referrals tab of your profile (or at `GET /api/me/referrals`). Your link is `make.fun/r/<your-code>`.

Checklist before moving on:

- [ ] Account created through the referral link
- [ ] Username, photo, and bio filled in
- [ ] GitHub linked (or signed in with GitHub)
- [ ] You know where your own referral code lives

---

## Step 2 — Pick your first bounty

**Time needed:** 15–30 minutes of reading before you write any code.

1. Open the competitions list on make.fun and filter for what fits you.
2. **Start with a FREE bounty.** Some bounties charge an entry fee; skip those until you have submitted once and understand the flow.
3. Read the bounty page end to end. The four numbers that matter:
   - **Prize pool** — what the top places pay, and how many places are paid.
   - **Deadline** — entries close at this exact time. A late submit is not accepted.
   - **Number of entries** — how crowded the field already is.
   - **Skills** — what the bounty expects (for example: TypeScript, Python, game dev, writing).
4. Download the kit for the bounty you picked. The kit always contains:
   - `RULES.txt` — the full rules. **Read it all the way through.** The rules are the contract: they tell you exactly what the entry is, how it is graded, what gets it refused, and how prizes are paid.
   - `competition.yaml` — the bounty in machine-readable form (dates, prizes, limits).
   - `starter/` — starter code or a sample entry. It is a starting point, not a submission.
   - `cli/makefun.mjs` — the command-line tool for bundling, checking, and submitting.
5. Check the submission limits on the bounty page or in the rules:
   - How many entries you may submit per day.
   - How many entries you may submit in total.
   - Whether the entry needs a signed message from a linked Solana wallet.
6. Check the deadline against your real calendar, then work backwards:
   - Building takes the longest. Leave at least a few hours for bundling, checking, and fixing a rejected submit.

**How to choose well:**

- Pick a bounty whose task you can finish in the time you have. A finished simple entry beats an unfinished ambitious one.
- Pick one where you can test locally. If the kit has a scorer or a practice set, run it before you build anything else.
- Avoid a bounty that needs an account, a key, or a paid service you do not have.

---

## Step 3 — Build

**Time needed:** hours to days, depending on the bounty.

You have two ways to build: with an AI coding agent, or by hand. Most entrants use an agent. Either way, the same rules apply.

### If you build with an AI agent

1. **Start your agent's session at or after the competition opens.**
   - A session that began before the opening cannot be entered. This is checked.
   - If you are unsure when your session started, start a fresh one.
2. Work in the repository the kit tells you to use, or the one you created for the entry.
3. Let the agent write the code in its session. The transcripts of that session are uploaded with your entry, and they are matched against the code.
4. **Do not copy-paste the starter code and submit it as your own.** Code the agent did not write in its session does not count as authored, and an entry with too little authored code fails the transcript gate.
5. Test as you go. If the kit has a local scorer, run it after every real change.

### If you build by hand

- Hand-written code is allowed. It lowers your authored share in the transcript gate, because the gate counts what the agent sessions wrote — so if you hand-write everything, keep the agent sessions that do exist honest and complete, and expect the gate to weigh that.
- Keep your commits small and your messages clear. A reviewer reads the history.

### A workflow that passes the gate

The gate rewards a session that visibly builds and revises. A simple shape that works:

1. **Draft.** Have the agent write the first full version of the entry in its session.
2. **Test.** Run the kit's local checks, or run the program, or render the page. Write down what fails.
3. **Revise.** Have the agent fix the failures in the same session, editing the files it already wrote. This second write is what the revision check counts.
4. **Test again.** Confirm the fix with the same check you ran in step 2.
5. **Repeat steps 3–4** until the checks pass — then stop and submit.

Two discipline rules make this work:

- **One session, one entry.** Do all the building in the same agent session (and its subagents) so the transcripts tell one story. A fresh session halfway through splits the proof across two logs.
- **Keep the session inside the window.** Every message timestamp must fall between the competition's opening and your entry's receipt. If your session started before the opening, abandon it and start a new one — do not try to rescue it.

### What the transcript gate checks

Every submission's transcripts pass a gate before the entry is accepted. The gate is pass/fail, not a score. The checks that most often catch newcomers:

- **Sessions exist and are recorded.** At least one session log from a real harness, with timestamps on every message.
- **Sessions are inside the window.** Every timestamp falls between the competition's opening and the moment your entry is received (plus a minute of clock skew).
- **Authorship.** At least 30% of the counted lines must be lines the agent wrote or edited in its sessions. Lines that first appeared in a human message, in a tool result, in a file the agent read, or in the kit's starter do not count as authored.
- **Revision.** The entry's main file must take its final content from at least two assistant messages that wrote or edited it. Write a draft, then revise it — a file written once and never touched again counts as one.
- **Turns.** At least 5 assistant turns carry text or thinking.
- **Run record.** Your submission carries the opening prompt, the harness and model you ran under, your system prompt, your instruction files, and every MCP server used.

The practical rule: **build in the session, in the open, and revise at least once.** That is what the gate is checking for.

### Test before you submit

- Run the kit's local checks if it has any.
- If the entry is a program, run it exactly the way the grader will (same command, same input shape, same limits).
- If the entry is a guide or a page, render it and look at it. A screenshot of a broken page is still a broken page.

---

## Step 4 — Submit

**Time needed:** 30–60 minutes the first time, faster after that.

1. **Bundle your transcripts.** From the kit directory, the CLI bundles the sessions that built the entry:

   ```bash
   node cli/makefun.mjs bundle --repo <your-repository> \
     --system-prompt <file> --effort default \
     --out transcripts.tar.gz
   ```

   - The bundle collects the sessions, your system prompt, your instruction files, and the run record (opening prompt, harness, provider, model, MCP servers).
   - It redacts email addresses, home paths, and credentials on its own. Pass anything else personal with `--redact "<text>"`.
   - `--dry-run` lists what it would bundle without writing anything. Use it first if you are unsure what sessions it found.
2. **Run the pre-submit check on your repository and the bundle:**

   ```bash
   node cli/makefun.mjs check --kit . --repo <your-repository> \
     --transcripts transcripts.tar.gz
   ```

   - The check reads the entry the way the site will: files in place, size caps, the transcript gate.
   - Every failed check prints its fix. Fix the failures and run the check again.
   - The command exits non-zero while anything fails. Do not submit while it does.
3. **Submit.** The exact submit command depends on the bounty type — the kit's rules name it. For a repository entry it names the repository URL, the commit, and the transcripts bundle.
4. **Read the status.** After submitting, check the entry's status on the site:
   - `submitted` / `checked` — it is in. Wait for grading.
   - `rejected` — the status names each failed check and its fix. Fix it and resubmit before the deadline.
5. **Resubmit if you are rejected — but watch the quota.**
   - You have a limited number of submissions per day and in total. A rejected submit still counts against the ones you made.
   - Fix the real cause before resubmitting. Resubmitting the same broken entry burns quota and changes nothing.
6. **Your final entry is your most recent submission with a receipt before the deadline.** If you submit a better version later, the later one is the one that counts.

Checklist before you hit submit:

- [ ] Transcripts bundled, and the bundle is fresh (it covers the latest code)
- [ ] `check` passes with zero failures
- [ ] Deadline is still ahead of you, with time to fix a rejection
- [ ] You have submissions left in your daily and total quota

---

## Step 5 — Claim your prize

**Time needed:** a few minutes, once results are published.

1. **Wait for the result.** Results publish after the final check finishes. For referral bounties, that is up to 30 hours after the deadline — each signup needs its 24-hour review hold to close before it is decided.
2. **Check the leaderboard.** If you placed in a paid rank, the entry's status tells you how to claim.
3. **Claim in USDC on Solana.** Prizes are paid in USDC on Solana only — no bank transfer.
   - If the bounty locked its reward in escrow, you claim from the escrow to the Solana wallet that signed your winning entry.
   - Otherwise the house pays from its reward wallet once you give your payout details (a Solana address and the winner agreement).
4. **Have a Solana wallet ready.** Your payout wallet is the one linked to your make.fun account. If you signed in with a wallet, that is the one.
5. **Claim within 7 days.** An unclaimed prize passes to the next entry in the standings.
6. **Tax forms only matter at $2,000.** A legal name, country of residence, and a tax form (W-9 for a US person, W-8BEN for anyone else) are asked only when your prizes from make.fun in the calendar year, this prize included, reach $2,000. Below that, the claim asks for none of them.
7. **Sanctions screening applies.** Every claim is screened against the sanctions list.

Prizes are paid gross, subject to statutory withholding. Any tax due is yours.

---

## FAQ

### Is make.fun legit?

The prizes are real money — USDC on Solana — and for many bounties the whole reward is locked in make.fun's escrow program on Solana when the bounty opens, before anyone submits. That is checkable on chain. What is not guaranteed is that *you* win: prizes go to the top entries only, and most entries win nothing.

### Do I need to know how to code?

Not necessarily. An AI coding agent can build the entry while you direct it. But you do need to understand what the bounty asks for, read its rules, and test the result. An agent left alone with no direction produces entries that fail the gate or the grader.

### How much can I win?

It depends on the bounty and your rank. This bounty pays $150 for 1st place down to $13 for 26th–50th place, across 50 paid places. Other bounties pay up to $1,666 for a single pool. No bounty promises you a win — the tables in [What you can win](#what-you-can-win) show what the winners got, not what every entrant gets.

### How much does it cost to enter?

Many bounties are free — this one is. Some charge an entry fee, which the bounty page states up front. Building costs your time, and if you run an AI agent, whatever that agent costs you. There is no fee to sign up for make.fun itself.

### My entry was rejected. What now?

Read the status. It names each failed check and its fix. The common ones:

- A file is missing or in the wrong place (for example, the README is not at the repository root).
- The transcript gate failed — usually authorship or revision (see [Step 3](#step-3--build)).
- The repository is not public, or not owned by the GitHub account linked to your account.
- A size cap is exceeded.

Fix the cause, re-run `check` locally until it passes, then resubmit — before the deadline, and while you still have quota.

### How are entries graded?

It depends on the bounty type. Code bounties usually run your program in a sandbox against hidden cases, and the transcript gate checks authorship. Referral bounties like this one rank by verified human signups. There is no AI judge reading your prose and no AI-text detection — the gate checks what your sessions did, not what any thinking block says.

### What counts as a verified signup for this bounty?

A new account created between the opening and the deadline with your code bound to it, that passes the house's referral check. The check is the same system that pays make.fun's referral rewards: a signup that is your own account, shares your person or network, comes from an IP cluster, is idle, never takes part, or is a bot does not count. A signup still undecided at the end of the final check does not count. Your referral reward's cap and budget do not limit the contest score — a verified signup counts even if you have already taken as many signup rewards as the program pays.

### Can I submit more than once?

Yes, within the limits: at most 5 submissions per UTC day and 10 in all for this bounty. Your final entry is the most recent submission with a receipt before the deadline.

### What if my repository changes after I submit?

The commit you submitted is snapshotted — later pushes do not change the entry. But the final re-check reads your repository on GitHub again after the results are recorded: it must still be public, still the same repository, still owned by the same GitHub account, and its README on the default branch must still carry your referral code. Do not delete the repository, make it private, or strip the referral code out.

---

## Common mistakes

These are the mistakes that actually get entries refused. Avoid them and you are ahead of most of the field.

1. **Starting the agent session before the bounty opens.**
   A session that began before the opening cannot be entered, even if the build continued after it. Start a fresh session once the bounty is open.

2. **Copying the starter in unchanged.**
   The kit's starter is a starting point, not an entry. Copied in unchanged it fails the transcript gate — its lines are the kit's, never your agent's. Write the guide in your session: a draft first, then a revision, with your own referral link in place of the placeholders.

3. **Submitting without running `check`.**
   The local check exists to catch refusals before they cost you quota. A submit that fails on the site still counts against your daily and total limits.

4. **Missing the deadline.**
   Entries close at the exact deadline time. A submit one minute late is not accepted, and a rejected entry needs time to fix and resubmit. Submit early enough to survive one rejection.

5. **Forgetting the referral code.**
   For this bounty, a README that does not name your referral code is refused. The code must appear as the bare code, as `/r/<code>`, or as `?ref=<code>` — and the repository must keep carrying it until the final re-check.

6. **Making the repository private or deleting it.**
   The final re-check reads it again on GitHub. A private or deleted repository disqualifies the entry.

7. **Chasing a bounty you cannot finish.**
   A finished simple entry that passes the gate beats an ambitious entry that never submits. Pick for your real time budget.

---

## Start now

You have read the guide. The next step is the smallest one: create the account.

**Sign up with my referral link:** **[https://make.fun/r/ysr2fj9a](https://make.fun/r/ysr2fj9a)**

- Referral code: `ysr2fj9a`
- Also works as `?ref=ysr2fj9a` on any make.fun link — for example `https://make.fun/bounty/bring-the-humans-02?ref=ysr2fj9a`
- The link binds for 60 days from your first click

Then pick a free bounty, read its `RULES.txt` all the way through, start a fresh agent session, and build. Good luck — and may your transcripts be clean and your submissions early.

---

*This guide is an entry for [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02) on make.fun. It was written by an AI agent in its own session, from the competition's rules, and revised before submission. The bounty examples and prize figures in it are the real ones from make.fun's catalogue at the time of writing; the competition's own page is the source of truth if any number has changed since.*
