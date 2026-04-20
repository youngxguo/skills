# agents

shared workflow defaults for starter repos.

## rules

- keep changes small and focused.
- follow existing patterns before inventing new ones.
- prefer simple, readable code.
- use lowercase for casual writing unless there is a clear reason not to.
- add tests with behavior changes when code exists.
- do not add tooling unless the repo clearly needs it.
- do not mix unrelated cleanup into the same patch.

## git and github

- create a branch, push it, and open a pr for normal changes.
- use short, specific titles.
- use lowercase and imperative style.
- use `<emoji> <type>(<scope>): <summary>` when scope helps, or `<emoji> <type>: <summary>` when it does not.
- common types: `docs`, `feat`, `fix`, `refactor`, `chore`, `style`.
- examples: `📝 docs(repo): add issue templates`, `✨ feat(chart): add line view`, `🐛 fix: handle empty input`.
- keep unrelated changes in separate commits when practical.
