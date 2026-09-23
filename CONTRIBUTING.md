# Contributing to Really Artificial

This guide applies to every repository in the [ReallyArtificial](https://github.com/ReallyArtificial) org unless a repository has its own CONTRIBUTING.md that says otherwise.

## Before you write code

- Try the software first. Bug reports from real use are the most useful thing you can send us.
- For anything beyond a small fix, open an issue before a pull request so we can agree on the shape.
- Issues labeled `good first issue` are scoped to be finishable without understanding the whole codebase.

## Pull requests

1. Fork, branch from `main`, keep the change focused on one thing.
2. Run the repository's tests and add one for the behavior you changed.
3. Fill in the pull request template, including the AI assistance field.
4. Sign off your commits (`git commit -s`). This is the [Developer Certificate of Origin](https://developercertificate.org/): you certify that you have the right to submit the change under the project's license.

We aim to respond to every issue and pull request within 48 hours. If we miss that, ping the thread.

## AI assistance policy

This org is built by a human and an AI collaborator, so we are not against AI-written code. We are against code nobody has read.

**What we do ourselves**

- A named human reads and can defend every line that gets merged. AI collaborators never merge and never sign off.
- Commits with meaningful AI involvement carry an `Assisted-by:` trailer naming the tool and model, following the [Linux kernel convention](https://github.com/torvalds/linux/blob/master/Documentation/process/coding-assistants.rst), for example `Assisted-by: Claude Code:claude-fable-5-1`.
- Prose is written by humans: READMEs, issues, release notes, and comments in review threads.

**What we accept from you**

- AI-assisted code is welcome when you disclose it in the pull request template and you have personally read, run, and understood every line. "I asked a model and it worked" is not enough; you need to be able to answer review questions about it.
- Write your pull request description, issue text, and review replies yourself. AI-generated prose in the discussion is the fastest way to have a PR closed.
- Fully autonomous agents opening issues or pull requests without a human in the loop are not accepted. We close them without review.
- `good first issue` is reserved for humans learning the codebase. Do not point an agent at those issues.
- Undisclosed AI-generated pull requests will be closed when we notice, and repeat cases lose the ability to contribute.

**Why stricter than average**

We build infrastructure that agents run on. If our own review bar is loose, nothing we say about dependable agent systems is credible.

## Security issues

Do not open a public issue. Follow [SECURITY.md](SECURITY.md).

## Code of conduct

Everyone participating is expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## License

By contributing you agree that your contribution is licensed under the license of the repository you contribute to (MIT unless stated otherwise).
