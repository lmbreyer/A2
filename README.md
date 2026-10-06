# Git Collaboration Practice

## Pair Information

- Student A: Lily Breyer
- GitHub username: lmbreyer
- Student B: Alexia Ruiz
- GitHub username: ruiz27-afk

## Branch Work

- Feature branch created:
- What changed on the branch:
- Who merged it into `main`:

## Conflict Reflection

1. Why did the intentional conflict happen?
   Both students attempted to edit the same line in the same file and git didn’t know which change to implement for the header. Even though Student A’s change occurred first, Student B did not pull/sync before making their own heading change.

2. How did you resolve it?
   We used VSCode’s built-in conflict resolution tools. We reviewed the incoming changes against the current local changes, cleared out the Git conflict markers, and typed in the unified compromise text before staging, committing, and pushing the fix.

3. ## Give two practices that can reduce unnecessary Git conflicts on a real team.
   -Pull the latest version of main at the start of every work session so both teammates are working from the same code. For example, if one partner pushed a fix last night and the other never pulled it, their work would clash when they try to push.
   -Talk with your teammate about who is working on which part before starting. For example, if both people edit the same heading and one pushes first, the other person's push gets rejected and they have to fix the conflict by hand.
