# NATS Account Configuration

NATS account configurations are built using the `nsc` tool. The NSC tool allows you to:

- Create and edit Operators, Accounts, Users
- Manage publish and subscribe permissions for Users
- Define Service and Stream exports from an account
- Reference Service and Streams from another account 
- Generate Activation tokens that grants access to a private service or stream
- Generate User credential files
- Describe Operators, Accounts, Users, and Activations
- Push and pull account JWTs to an account JWTs server

## Installation

Installing `nsc` is easy:

```text
curl -L https://raw.githubusercontent.com/nats-io/nsc/master/install.py | python
```

The script will download the latest version of `nsc` and install it into your system. 

## Tutorials

You can find various task-oriented tutorials to working with the tool here:

- [Basic Usage](nsc.md)
- [Configuring Streams](streams.md)
- [Configuring Services](services.md)
- [Signing Keys](signing_keys.md)
- [Revoking Users or Activations](revocation.md)
- [Working with Managed Operators](managed.md)

## Tool Documentation

For more specific browsing of the tool syntax, check out the `nsc` tool documentation.
It can be found within the tool itself:

```text
> nsc help
```

Or an online version [here](https://nats-io.github.io/nsc).
