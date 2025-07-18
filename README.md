# Contributing to AniQuotes API

Thank you for your interest in contributing to AniQuotes API! We welcome contributions from everyone, regardless of your experience level. This guide will help you get started with contributing to our project.

## Table of Contents
1. [Getting Started](#getting-started)
2. [Ways to Contribute](#ways-to-contribute)
3. [Adding New Quotes](#adding-new-quotes)
4. [Translating Quotes](#translating-quotes)
5. [Reporting Issues](#reporting-issues)
6. [Feature Requests](#feature-requests)
7. [Code Contributions](#code-contributions)
8. [Pull Request Guidelines](#pull-request-guidelines)
9. [Code of Conduct](#code-of-conduct)
10. [Community](#community)

## Getting Started <a name="getting-started"></a>
1. **Fork** the repository on GitHub
2. **Clone** your forked repository:
   ```bash
   git clone https://github.com/Username/AniQuotesAPI.git
   ```
3. **Install dependencies**:
   ```bash
   cd AniQuotesAPI
   npm install
   ```
4. **Create a branch** for your changes:
   ```bash
   git checkout -b your-feature-branch
   ```

## Ways to Contribute <a name="ways-to-contribute"></a>
You can contribute in several ways:
- 🌟 Add new anime quotes
- 🌐 Translate existing quotes
- 🐛 Report bugs
- 💡 Suggest new features
- 📝 Improve documentation
- 🛠 Fix issues and improve code
- 🎨 Enhance the homepage design

## Adding New Quotes <a name="adding-new-quotes"></a>
To add new quotes:

1. Open `data/quotes.json`
2. Add your quote using this format:
   ```json
   {
     "id": 123,
     "quote": "Your quote here",
     "anime": "Anime Title",
     "character": "Character Name",
     "language": "en"
   }
   ```
3. Guidelines:
   - Use the next available ID (check the last ID in the file and increment by 1)
   - Verify the anime title and character name are accurate
   - Keep quotes authentic (from actual anime)
   - Maintain consistent formatting
   - Add only one quote per pull request (unless they're related)

## Translating Quotes <a name="translating-quotes"></a>
To translate existing quotes:

1. Find the quote you want to translate in `data/quotes.json`
2. Open or create the appropriate language file in `data/languages/`
   - English: `en.json`
   - Japanese: `jp.json`
   - Hindi: `hi.json`
   - Create new files for additional languages
3. Add the translated quote with the **same ID** as the original
   ```json
   {
     "id": 123,
     "quote": "Translated quote here",
     "anime": "Anime Title (in target language)",
     "character": "Character Name",
     "language": "target-language-code"
   }
   ```
4. Language codes should follow [ISO 639-1](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) standards

## Reporting Issues <a name="reporting-issues"></a>
When reporting issues:
1. Check if the issue already exists
2. Use a clear, descriptive title
3. Include:
   - Steps to reproduce
   - Expected behavior
   - Actual behavior
   - Screenshots if applicable
   - Environment details

Example issue format:
```
**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Additional context**
Add any other context about the problem here.
```

## Feature Requests <a name="feature-requests"></a>
Suggest new features by:
1. Explaining the feature clearly
2. Describing why it would be valuable
3. Suggesting implementation approaches if possible
4. Providing examples of similar implementations

## Code Contributions <a name="code-contributions"></a>
1. Follow existing code style and patterns
2. Write clear commit messages
3. Add tests for new functionality
4. Update documentation when needed
5. Keep changes focused on a single purpose

### Development Setup
1. Install dependencies: `npm install`
2. Start development server: `npm run dev`
3. Run tests: `npm test`
4. Lint code: `npm run lint`

### Project Structure
```
AniQuotesAPI/
├── api/               # API endpoints
├── data/              # Quote database
│   ├── quotes.json    # Master English quotes
│   └── languages/     # Translations
├── utils/             # Helper functions
├── public/            # Static assets
├── vercel.json        # Deployment config
└── package.json       # Dependencies
```

## Pull Request Guidelines <a name="pull-request-guidelines"></a>
1. Keep PRs focused on a single feature/fix
2. Reference related issues in your PR description
3. Ensure all tests pass
4. Update documentation if needed
5. Use a descriptive title and detailed description
6. Allow edits from maintainers

After submitting your PR:
1. A maintainer will review your code
2. You may be asked to make changes
3. Once approved, your PR will be merged

## Code of Conduct <a name="code-of-conduct"></a>
We follow the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) Code of Conduct. Please:
- Be respectful and inclusive
- Use welcoming language
- Accept constructive criticism gracefully
- Focus on what's best for the community

Unacceptable behavior includes:
- Harassment or discrimination
- Insults or derogatory comments
- Publishing others' private information

## Community <a name="community"></a>
Join our community:
- [GitHub Discussions](https://github.com/AniQuotes/Discussions)
- [Telegram Channel](https://telegram.me/AniQuotesAPI)

---

Thank you for contributing to AniQuotes API! Your contributions help make this project better for everyone in the anime community. 🎉

---

<div align="center">
  
**AniQuotes** For inquiries or collaborations
     
[![Telegram Badge](https://img.shields.io/badge/-Telegram-2CA5E0?style=flat&logo=Telegram&logoColor=white)](https://telegram.me/Shineii86 "Contact on Telegram")
[![Instagram Badge](https://img.shields.io/badge/-Instagram-C13584?style=flat&logo=Instagram&logoColor=white)](https://instagram.com/ikx7.a "Follow on Instagram")
[![Pinterest Badge](https://img.shields.io/badge/-Pinterest-E60023?style=flat&logo=Pinterest&logoColor=white)](https://pinterest.com/ikx7a "Follow on Pinterest")
[![Gmail Badge](https://img.shields.io/badge/-Gmail-D14836?style=flat&logo=Gmail&logoColor=white)](mailto:ikx7a@hotmail.com "Send an Email")

<sup>Maintained by [Shinei Nouzen](https://github.com/Shineii86) © 2025 AniQuotes - All Rights Reserved</sup>

</div>
