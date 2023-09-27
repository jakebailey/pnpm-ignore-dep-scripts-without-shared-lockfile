# pnpm-ignore-dep-scripts-without-shared-lockfile

```
$ pnpm i
Scope: all 2 workspace projects
Already up to date
packages/a                               | +119 ++++++++++++
packages/a                               | Progress: resolved 119, reused 119, downloaded 0, added 119, done
. postinstall$ echo it worked
│ it worked
└─ Done in 9ms
packages/a/node_modules/.pnpm/re2@1.20.3/node_modules/re2: Running install script...

$ git clean -fdx .
# uncomment ignore-scripts in .npmrc
Scope: all 2 workspace projects
Already up to date
packages/a                               | Progress: resolved 119, reused 118, downloaded 0, added 0, done
Done in 959ms
```
