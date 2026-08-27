# Python and Machine Learning Learning Documentation

A comprehensive, structured learning resource for Python programming and machine learning, built with Mintlify.

## 📚 Documentation Structure

This documentation covers two main learning paths:

### Python Fundamentals (17 modules)
- Python Overview & Setup
- Project Folder Structure
- pip & Package Management
- Virtual Environments & requirements.txt
- Variables, Data Types & Basic Data Structures
- Loops & Conditionals
- Functions & Docstrings
- Reading & Writing Files
- JSON Basics
- Environment Variables & .env Files
- Making API Calls with requests
- Stack Traces & Debugging Basics
- Logging Basics
- AI/ML Libraries Overview
- Jupyter Notebooks Basics
- Git Usage with Python Projects
- NumPy and DataFrames

### Machine Learning and Generative AI (23 modules)

**ML Basics:**
- What is Machine Learning?
- Key ML Terminology
- ML Workflow Overview
- Model Evaluation & Metrics

**Hugging Face:**
- HF Ecosystem Overview
- pipeline() & Common Tasks
- Model Cards & Documentation

**NLP and Deep Learning:**
- NLP Tasks at a Glance
- Tokenization & Embeddings
- Prompt Engineering Basics
- PyTorch Overview
- PyTorch Training Scripts
- Model Save/Load & Deployment

**AI Fundamentals:**
- How AI Models Are Built & Trained
- AI Model Types at a Glance

**Generative AI:**
- Large Language Models (LLMs)
- Tokens & Context Windows
- LLM APIs & How They Work
- Advanced Prompt Engineering
- RAG Architecture & Components
- Vector Databases & Embeddings

## 🚀 Local Development

### Prerequisites
- Node.js 18+
- npm or yarn
- Mintlify CLI

### Installation

```bash
# Install Mintlify CLI
npm install -g @mintlify/cli

# Navigate to project directory
cd path/to/this/project
```

### Running locally

```bash
# Start the development server
mint dev
```

The documentation will be available at `http://localhost:3000`

### Hot reload

The documentation automatically reloads as you edit files. Just save and refresh your browser.

## 📝 Creating/Editing Content

### File structure

- `index.mdx` - Landing page with course overview
- Each course module is a `.mdx` file (Markdown + JSX)
- Files use YAML frontmatter for metadata:

```yaml
---
title: "Topic Name"
description: "Brief description of the topic"
sidebarTitle: "Short label for navigation"
icon: "font-awesome-icon-name"
keywords: ["search", "terms", "here"]
---
```

### Example page structure

```markdown
---
title: "Topic Name"
description: "What students will learn"
sidebarTitle: "Navigation label"
icon: "book"
keywords: ["key", "terms"]
---

## Topic

Overview and context for the topic.

## Key concepts / How to implement it

Practical explanation with code examples.

## Output / Examples

Show what the result looks like.

<Note>
  Important context or learning point.
</Note>

## Reference

[Link to official documentation]

**Estimated time: 1-2 hours**
```

## 🎨 Customization

### Edit site settings

Modify `docs.json` to change:
- Site name and branding
- Color scheme (primary, light, dark)
- Navigation structure
- Logo and favicon
- Global anchors and links

### Navigation structure

Navigation groups are defined in `docs.json`. Each group can contain multiple pages.

Example:
```json
{
  "group": "Python Fundamentals",
  "pages": [
    "python-overview-setup",
    "project-folder-structure",
    ...
  ]
}
```

## 🌐 Deployment

### Deploy to Mintlify Cloud

1. Push changes to your git repository
2. Connect repository to Mintlify at [mintlify.com/dashboard](https://mintlify.com/dashboard)
3. Documentation deploys automatically on push

### Deploy to custom domain

See [Mintlify deployment guide](https://mintlify.com/docs/deployment/overview)

## 📖 Components and Formatting

Mintlify supports rich components:

- **Callouts**: `<Note>`, `<Tip>`, `<Warning>`
- **Code blocks**: Syntax highlighting for multiple languages
- **Cards**: `<Card>` and `<CardGroup>` for visual navigation
- **Tabs**: `<Tabs>` for toggled content
- **Steps**: `<Steps>` for procedural content

## ✅ Best Practices

1. **Keep explanations clear**: Use simple language, explain concepts from first principles
2. **Include examples**: Provide code examples and real-world usage
3. **Show outputs**: When relevant, show what the result looks like
4. **Link to resources**: Provide references to official documentation
5. **Use consistent icons**: Choose relevant Font Awesome icons for topics
6. **Add metadata**: Always include title, description, and keywords for discoverability

## 📚 Learning Path Recommendations

**For beginners:**
1. Start with Python Fundamentals (modules 1-17)
2. Continue with ML Basics (4 modules)
3. Explore Hugging Face (3 modules)

**For intermediate learners:**
1. Review Python Fundamentals as needed
2. Study all ML sections
3. Dive deep into Generative AI and RAG

**For advanced learners:**
1. Focus on Generative AI and RAG architecture
2. Implement projects combining multiple concepts
3. Refer to PyTorch and API documentation for specific tasks

## 🔗 Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [Python.org](https://python.org)
- [Hugging Face Hub](https://huggingface.co)
- [PyTorch Documentation](https://pytorch.org)
- [OpenAI Documentation](https://platform.openai.com/docs)

## 📄 License

This documentation is provided as-is for educational purposes.

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
