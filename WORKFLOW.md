# A small, repeatable GitHub routine

## Choose a home

- Related automation: use the existing Python, Bash, or PowerShell collection.
- C++ practice: use `programming-foundations/cpp/<descriptive-name>/`.
- Python practice: use the existing learning collections and label book/course sources.
- A project with its own purpose, dependencies, and development path: consider a separate repository.
- Raw captures, VM images, backups, and large datasets: keep them in suitable storage; use safe examples and references in Git.
- Credentials and unsanitized operational material: keep them in appropriate secure storage pending a release decision.

## Start small

A short README can answer four questions: what does it do, how do I run it, what is its current status, and what should I know about its limits? Keep related code beside that explanation. Add tests when there is meaningful behavior to protect; add result notes when you run an experiment.

## Record meaningful progress

From the relevant local repository:

```bash
git status
git diff
```

Inspect both before selecting files to commit. For a specific intended file, a normal local change looks like:

```bash
git add path/to/intended-file
git commit -m "Describe the concrete change"
```

Push to the intended remote/branch when you are ready to share the change and have reviewed its contents. A private repository is useful for ordinary work that is not ready for public release; it is not a place to store credentials.

Useful commit boundaries include an initial implementation, a fixed behavior, a meaningful test, or a recorded result. Commit descriptions should explain the change rather than aim for a daily activity count.

## Review occasionally

At a natural milestone, decide whether to keep developing the work, clarify its status, combine related material, or preserve it as history. A small useful script can stay in its collection indefinitely. Promotion to a portfolio flagship depends on clear implementation and evidence, not repository size or branding.

[Back to the profile](README.md).
