# Commit Message Template

Please write a commit message that follows the conventional commit format with gitmoji:

**Format:** `<gitmoji> <type>(<scope>): <description>`

## Types:
- **feat**: A new feature
- **fix**: A bug fix
- **docs**: Documentation only changes
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **perf**: A code change that improves performance
- **test**: Adding missing tests or correcting existing tests
- **chore**: Changes to the build process or auxiliary tools and libraries

## Common Gitmojis:
- ✨ `:sparkles:` - Introduce new features
- 🐛 `:bug:` - Fix a bug
- 📝 `:memo:` - Add or update documentation
- 💄 `:lipstick:` - Add or update the UI and style files
- ♻️ `:recycle:` - Refactor code
- ⚡️ `:zap:` - Improve performance
- ✅ `:white_check_mark:` - Add, update, or pass tests
- 🔧 `:wrench:` - Add or update configuration files
- 🎨 `:art:` - Improve structure/format of the code
- 🔥 `:fire:` - Remove code or files
- 🚀 `:rocket:` - Deploy stuff
- 🔒️ `:lock:` - Fix security issues

## Examples:
- `✨ feat(auth): add OAuth2 authentication`
- `🐛 fix(api): resolve null pointer exception in user service`
- `📝 docs(readme): update installation instructions`
- `♻️ refactor(utils): simplify date formatting logic`
- `🔧 chore(deps): update dependencies to latest versions`

Please include:
1. A gitmoji that represents the change
2. The conventional commit type
3. An optional scope in parentheses
4. A clear, concise description in present tense
5. Keep the first line under 50 characters when possible
6. Add a longer description in the body if needed (after a blank line)