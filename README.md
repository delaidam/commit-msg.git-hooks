# commit-msg.git-hooks
### Commit Message Format Checker

This Git script is used to verify the format and length of commit messages.
Contributions to the project should have commit messages that start with specific types (feature, fix, refactor, wip) and follow the format `<type>:<description>`.
Additionally, the total length of the commit message, including the body, should be less than 50 characters.

These rules help maintain consistency and readability in commit messages.
The script automatically checks commit messages before they are executed and reports errors or warnings if the rules are not followed.

Store this file as .git/hooks/commit-msg in your repository in order to enforce checking for proper commit message format before actual commits.
You may need to make the script executable by 'chmod +x .git/hooks/commit-msg'.
