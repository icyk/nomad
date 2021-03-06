---
layout: "docs"
page_title: "Commands: node"
sidebar_current: "docs-commands-node"
description: >
  The node command is used to interact with nodes.
---

# Command: node

The `node` command is used to interact with nodes.

## Usage

Usage: `nomad node <subcommand> [options]`

Run `nomad node <subcommand> -h` for help on that subcommand. The following
subcommands are available:

- [`node config`][config] - View or modify client configuration details

- [`node drain`][drain] - Set drain mode on a given node

- [`node eligibility`][eligibility] - Toggle scheduling eligibility on a given
  node

- [`node status`][status] - Display status information about nodes

[config]: /docs/commands/node/config.html "View or modify client configuration details"
[drain]: /docs/commands/node/drain.html "Set drain mode on a given node"
[eligibility]: /docs/commands/node/eligibility.html "Toggle scheduling eligibility on a given node"
[status]: /docs/commands/node/status.html "Display status information about nodes"
