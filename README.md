# Claude Game Studio

A modular Claude skill suite that helps turn an idea into a scoped, playable, testable game project. Use Claude as a coordinated game-development studio: design, narrative, systems, levels, engineering, art direction, audio, QA, production, and authorized modding support.

> Skills are focused playbooks, not autonomous agents. Ask Claude to combine only the disciplines needed for the task.

## Included

12 specialized skills in `.claude/skills/`, shared studio principles, an authorization policy, a starter project brief, and reusable templates for design, features, playtests, bug reports, and production planning.

## Install

Copy `.claude/` to your project root. Claude Code discovers project skills from `.claude/skills/<skill-name>/SKILL.md`. Copy all skills for the full studio setup, or just the skill folders you need. `docs/` and `templates/` are reference materials you can copy as needed.

## Skills

| Skill | Focus |
| --- | --- |
| `game-design` | Game concept, player fantasy, design pillars, MVP scope |
| `systems-design` | Mechanics, core loops, progression, feature specifications |
| `game-balance` | Difficulty, economies, rewards, tuning hypotheses |
| `narrative-design` | Story, characters, dialogue, narrative implementation |
| `level-design` | Levels, missions, encounters, tutorials, player flow |
| `game-programming` | Engine-aware code, debugging, architecture, tests |
| `art-direction` | Visual identity, readability, asset briefs |
| `game-audio` | Audio direction, adaptive music, sound event briefs |
| `qa-testing` | Test plans, reproducible bugs, regression, playtests |
| `production-planning` | Milestones, task breakdown, dependencies, risks |
| `game-modding` | Authorized, reversible, preferably offline modding |
| `game-analysis` | Ethical analysis of owned, permitted, or public material |

## Ask Claude

- “Use game-design to turn this idea into a one-page pitch and an MVP.”
- “Combine systems-design and game-balance to spec a 10-minute combat loop.”
- “Use level-design to plan a tutorial with teach, practice, and payoff beats.”
- “Inspect the existing project, then use game-programming to implement this feature and run available tests.”
- “Use qa-testing to create a risk-based test plan and bug report template.”
- “Use production-planning to break the vertical slice into milestones and tasks.”

For multidisciplinary tasks, name the skills you want combined and ask Claude to explain hand-offs and dependencies. Start a project with `templates/PROJECT_BRIEF.md`.

## Studio workflow

1. Discover the project and constraints; state assumptions.
2. Define player experience, pillars, and MVP.
3. Specify systems, content, and testable acceptance criteria.
4. Prototype the smallest useful slice in the existing stack.
5. Validate with tests and playtests; report evidence and limitations honestly.
6. Stabilize, document, and prepare release materials.

## Responsible use

Only analyze or modify games, files, tools, and services the user owns or is explicitly authorized to work with. No DRM/anti-cheat/access-control bypass, online cheats, credential theft, malware, or unauthorized extraction of proprietary materials. Prefer official APIs, mod kits, sandboxed local tests, and original or properly licensed assets. See [docs/AUTHORIZED_WORK.md](docs/AUTHORIZED_WORK.md).

## License

MIT. See [LICENSE](LICENSE).
