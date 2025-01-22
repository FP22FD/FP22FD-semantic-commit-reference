# Semantic Commit Messages

A guide to semantic commit messages with examples and best practices. Simplify version control and ensure a clear, consistent commit history for better collaboration.
See how a minor change to your commit message style can make you a better programmer.

Format: `<type>(<scope>): <subject>`

`<scope>` is optional

## Example

```![IA-commit](https://github.com/user-attachments/assets/51b0a6dc-5341-43fc-97ae-bdd8ab9f1111)

feat: add hat wobble
^--^  ^------------^
|     |
|     +-> Summary in present tense.
|
+-------> Type: chore, docs, feat, fix, refactor, style, or test.
```

More Examples:

- `feat`: (new feature for the user, not a new feature for build script)
- `fix`: (bug fix for the user, not a fix to a build script)
- `docs`: (changes to the documentation)
- `style`: (formatting, missing semi colons, etc; no production code change)
- `refactor`: (refactoring production code, eg. renaming a variable)
- `test`: (adding missing tests, refactoring tests; no production code change)
- `chore`: (updating grunt tasks etc; no production code change)

## Using AI Copilot for Commit Suggestions

To make your commit process smoother, you can leverage AI tools like GitHub Copilot to suggest meaningful commit titles:

1. Enable GitHub Copilot in your repository: Ensure Copilot is activated and configured in your environment.
2. Make your changes: Work on your code or documentation as usual.
3. Use AI suggestions:
   - When creating a commit, start typing your message.
   - Copilot will automatically suggest semantic commit titles based on the changes made.
   - Examples:
     - `resolve null pointer exception in user service`
     - `update README with usage examples`
     - `implement user authentication with OAuth`
4. Edit suggestions and add semantic keywords before the title suggestion.
5. Always review the AI-generated commit messages for accuracy and clarity before committing.

![AI Copilot Image](https://github.com/FP22FD/semantic-commit-reference/blob/main/IA-commit.jpeg)

## ReferencesFD

- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html

