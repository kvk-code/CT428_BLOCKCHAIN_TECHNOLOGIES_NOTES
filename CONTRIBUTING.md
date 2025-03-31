# Contributing to CT428 Blockchain Technologies Notes

Thank you for considering contributing to this project! This document outlines the process for contributing to the CT428 Blockchain Technologies Notes repository and helps ensure consistency across contributions.

## Contribution Guidelines

### Scope of Contributions

All contributions should be aligned with the [CST 428 Blockchain Technologies syllabus](./Syllabus_sample_questions%20.md) of APJ Abdul Kalam Technological University (APJAKTU). Please review the syllabus before making contributions to ensure your content is relevant to the course.

### AI-Generated Content Policy

AI-generated content (using tools like ChatGPT, Claude, etc.) is acceptable, provided:
1. The contributor has thoroughly reviewed the content for accuracy
2. Any technical information has been verified against reliable sources
3. The content is properly structured and formatted according to our style guide
4. The contributor takes full responsibility for the correctness of the content

Remember that AI tools can sometimes generate plausible but incorrect information. It is your responsibility to verify all information before submitting.

## How to Contribute

You can contribute in two ways: through GitHub's web interface or using git on your local machine.

### Option A: Contributing directly through GitHub (Recommended for beginners)

1. **Create a GitHub account** if you don't already have one
2. **Navigate to the repository** on GitHub
3. **Fork the repository** by clicking the "Fork" button in the top-right corner
4. **Make your changes** directly in your forked repository:
   - To edit an existing file: Navigate to the file and click the pencil icon
   - To add a new file: Use the "Add file" dropdown and select "Create new file"
   - To upload images: Use the "Add file" dropdown and select "Upload files"
5. **Propose changes**:
   - When editing files, scroll to the bottom and fill in the "Commit changes" form
   - Add a descriptive title and explanation of your changes
   - Select "Create a new branch for this commit and start a pull request"
   - Click "Propose changes"
6. **Create a Pull Request (PR)**:
   - After proposing changes, you'll be directed to the PR creation page
   - Fill in a descriptive title and provide details about your changes
   - Click "Create pull request"

### Option B: Contributing using local git workflow

#### 1. Set up your local environment

1. Fork the repository on GitHub
2. Clone your fork locally
   ```
   git clone https://github.com/YOUR-USERNAME/CT428_BLOCKCHAIN_TECHNOLOGIES_NOTES.git
   ```
3. Add the original repository as an upstream remote
   ```
   git remote add upstream https://github.com/ORIGINAL-OWNER/CT428_BLOCKCHAIN_TECHNOLOGIES_NOTES.git
   ```

#### 2. Create a new branch

Create a new branch for your contribution:
```
git checkout -b feature/your-feature-name
```

Use a descriptive name that reflects the content you're adding or modifying.

#### 3. Add or modify content

Make your changes locally, then:

```
git add .
git commit -m "Description of changes"
git push origin feature/your-feature-name
```

#### 4. Create a Pull Request

Go to GitHub and create a Pull Request from your branch to the original repository.

### What to Contribute

#### Adding new topic notes
1. Create a new Markdown file with a clear, descriptive name (e.g., `Consensus_Algorithms.md`)
2. Use proper Markdown formatting
3. Include a table of contents for longer documents
4. Add appropriate references and citations
5. Include diagrams or images if they help explain concepts (place them in the `images/` directory)

#### Improving existing content
1. Correct factual errors
2. Clarify explanations
3. Add examples or use cases
4. Update content to reflect recent developments
5. Fix typos and grammatical errors

## Style Guide

### Document Structure
- Start with a descriptive title using `# Title`
- Include a brief introduction explaining the topic's relevance
- Organize content with clear headings using `##`, `###`, etc.
- Use code blocks for examples
- End with references/further reading

### Formatting
- Use **bold** for key terms and important concepts
- Use *italics* for emphasis
- Use `code formatting` for technical terms, code snippets, or blockchain addresses
- Use numbered lists for sequential steps
- Use bullet points for non-sequential items
- Use blockquotes for definitions or important notes

### Content Guidelines
- Write in clear, concise language
- Explain technical concepts in an accessible way
- Provide examples to illustrate complex ideas
- Define acronyms and technical terms when first used
- Cite sources for facts, quotes, and statistics
- Focus on educational value over personal opinions

## Review Process

All contributions will be reviewed by maintainers before merging. The review process ensures:

1. Content accuracy
2. Adherence to style guidelines
3. Educational value
4. Clarity and organization

Reviewers may request changes or clarifications before merging your contribution.

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## Questions?

If you have any questions or need clarification, please open an issue on GitHub or reach out to the project maintainer:

**Kiran V K**  
Assistant Professor  
Department of Computer Science and Engineering  
NSS College of Engineering Palakkad, Kerala  
 [mail@kiranvk.me](mailto:mail@kiranvk.me)  
 [LinkedIn](https://www.linkedin.com/in/kiranvk-kvk)

Thank you for helping make blockchain education more accessible!
