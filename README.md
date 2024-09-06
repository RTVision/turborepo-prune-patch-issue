To repro the issue run
`pnpm turbo prune --scope=web`
and then open up out/pnpm-lock.yaml and see the next patch is no longer present
even though it is the base pnpm-lock.yaml file and web depends on next
