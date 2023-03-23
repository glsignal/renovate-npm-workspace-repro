# synthesized dependency reproduction

Issue link: https://github.com/renovatebot/renovate/issues/20469

In this repo, a lockfile-only update triggered by renovate incorrectly lists
`autonumeric` as a dependency in [the root workspace's
dependencies](https://github.com/glsignal/renovate-npm-workspace-repro/pull/5/files#diff-053150b640a7ce75eff69d1a22cae7f0f94ad64ce9a855db544dda0929316519L12-R15)

The expected behaviour is for this area of the lockfile to be unchanged
