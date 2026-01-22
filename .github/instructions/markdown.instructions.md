---
description: 'Documentation and content creation standards'
applyTo: '**/*.md'
---

## Markdown Content Rules

These rules apply to markdown files in general. Technical documentation (PRDs, architecture specs, READMEs) should follow their own respective instruction files.

### General Markdown Guidelines

1. **Headings**: Use appropriate heading levels (H2, H3, etc.) to structure your content. H1 headings are typically generated from the title metadata.
2. **Lists**: Use bullet points or numbered lists with proper indentation and spacing.
3. **Code Blocks**: Use fenced code blocks with language specification for syntax highlighting.
4. **Links**: Use proper markdown syntax with descriptive link text. Ensure links are valid and accessible.
5. **Images**: Include alt text for accessibility.
6. **Tables**: Use markdown table syntax with proper alignment.
7. **Readability**: Keep line length reasonable (under 400 characters) for readability.

### Front Matter (Optional)

For markdown files that require metadata, you may include YAML front matter with these fields:

- `post_title`: The title of the post
- `author1`: The primary author
- `post_slug`: The URL slug
- `categories`: Post categories
- `tags`: Post tags
- `summary`: Brief summary
- `post_date`: Publication date

Additional fields may be added based on your publishing platform requirements.

### Best Practices

- Use clear, hierarchical heading structure
- Include code examples where appropriate with proper syntax highlighting
- Add alt text to images for accessibility
- Keep paragraphs focused and concise
- Use whitespace to improve readability
