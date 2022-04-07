# Bounties

-   [**All Bounties**](https://github.com/near/bounties/issues)

This repository contains tasks that helps [Aurora](https://aurora.dev/) and its ecosystem to grow and improve. The [Issues tab](https://github.com/near/bounties/issues) will list each of these and their labels will help you search for what you want.

## Overview

Bounties are small and well defined tasks that have a clear goal, and could be done from start to finish in a short period of time. If you are looking to collaborate with Aurora in a larger project go ahead and check out the [Grants Program](https://aurora.dev/grants).

The main goal of the bounties are to encourage members of the community with unique skills to bring value to Aurora ecosystem while getting rewarded for doing it. Skills can go from developer to designer to writer to something else, so poke around and see if you see something that fits you.

The scope of the bounties goes beyond the tools and infrastructure built by Aurora Labs, and include everything related to projects and tooling that are part of Aurora ecosystem.

## How to get involved

Check if there is any task that is suited for you on the [Issues tab](https://github.com/near/bounties/issues).

Each bounty has an owner responsible for assigning the user working on the task, track progress, and sending the reward once completed.

When you find a good task, request to work on it to the owner on the same issue. You can try to get in touch directly with them through other channel. While usually the first requester will be preferred, it is up to the owner to make a decision in that regard.

## Other bounties

If you can't find any suitable task go to #bounties channel on [Aurora Discord](https://discord.gg/dEFJBz8HQV) and feel free to show which skill you have and how you can be helpful. For developers it is recommended to check issues in Aurora [public repositories](https://github.com/aurora-is-near/). If you think you are suited to solve an issue (which is currently not a bounty), get in touch with us in Discord and let's create one.

Some relevant repositories:

-   [Engine](https://github.com/aurora-is-near/aurora-engine)
-   [Relayer](https://github.com/aurora-is-near/aurora-relayer)
-   [Rainbow Bridge](https://github.com/aurora-is-near/rainbow-bridge)
-   [Fungible Token Connector](https://github.com/aurora-is-near/rainbow-token-connector)
-   [Documentation](https://github.com/aurora-is-near/doc.aurora.dev)

## How to propose a bounty

Each bounty is created as an issue within this repository. It should have an owner, clear goals of acceptance and the reward given upon completion. When creating the bounty use [the TEMPLATE](.github/ISSUE_TEMPLATE/bounty.md) provided for it.

-   Name: Bounty Name. Use the same name for the github issue.
-   Owner(s): Name and contact of the owner. Use the format `Name (@contact)`. If there are multiple owners separate them by commas.
-   Status: Current status of the bounty. It will be one of:
    -   PENDING: It is open and hasn't being assigned yet
    -   WORK-IN-PROGRESS: It was assigned, and it the work is development.
    -   IN-REVIEW: The work is finished and it is up to the owner to assign reviewers appropriately.
    -   FINISHED: The work was finished and the reward was payed.
    -   CANCELED: The bounty was cancelled
-   Reward: Amount of tokens and Token id. It is possible to denominate the value in dollars and specify that it will be paid in a particular cryptocurrency. It should be specified by the bounty writer which tokens (i.e USDT / DAI / AURORA / NEAR) and which networks are available.
-   Assigned: Contact of the user assigned to the bounty. Empty if status is `PENDING`
-   Gitcoin: [Optional] Link to [Gitcoin](https://gitcoin.co/explorer) issue in case it exists
-   Expected time: [optional] Expected time of completion denominated in hours or days. It could be an approximation, and it is mostly for reference.
-   Issue: [Optional] Links to existing issues or other relevant links.
-   Description: A single sentence describing the bounty.
-   Context: Some background, explanation and rationale on why this is important
-   Acceptance criteria: Every aspect that should

## Bounty Owner

The owner is responsible of reacting promptly to all events related to the bounty.

-   Answer users that are applying to the bounty. Either with yes or no. Elaborate in case of rejection.
-   Provide feedback to the assignee during development. Notice however that it is expected the assignee to work independently.
-   Updating fields of the bounty. In particular `Status` should reflect the current state at all time
-   Upon completion of the work review it (or assign proper reviewers) in a timely manner.
-   Make sure the reward is paid after the work is accepted.

## Repository Maintainer

The maintainer is responsible of making sure that all bounties created complies with the previous guidelines. In particular, they can close any bounty that is not relevant to Aurora Ecosystem. It will provide feedback to the bounty writers regarding formatting, and will ping relevant parties when active bounties are stalled; closing them in case of no feedback.

## Current Maintainers:

| Name           | Github   | Email              | Discord       |
| -------------- | -------- | ------------------ | ------------- |
| Marcelo Fornet | @mfornet | marcelo@aurora.dev | mnaeraxr#3685 |

---

This repository was inspired by [NEAR Bounties](https://github.com/near/bounties).
