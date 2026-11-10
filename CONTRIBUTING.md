# Contributing Guidelines

Please see the [Servo contributing guidelines](https://book.servo.org/contributing/getting-started).

## paid issues

paid issues have the field `Bounty` with a nonzero number. they may optionally
have the `paid` label as well for discoverability, though it is not required

they are assigned to the first contributor that appears around, though giving
priority if someone was recommended before

all bounties are paid through github sponsors, you need to have it set up
before your PR with the changes gets merged. the PR won't get merged until you
have it set up or you give up the money

bounties are one-time and specified in united states dollars (USD).

code reviews may be exhaustive for those kinds of issues. that is part of the
bounty. all feedback must be addressed.

## running commands

most of our repositories have a `justfile` that contains command recipes

we recommend you install the `just` command dispatcher with:
- macos: `brew install just`
- linux: `sudo apt install just`
- windows: `winget install Casey.Just`

and use the command dispatcher which has many useful commands

you may find as well that there's an special `just setup` command which will
install the required development tools in your machine
