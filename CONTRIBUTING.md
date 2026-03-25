# Contributing Guidelines

Thank you for considering contributing to the **AI Roadmap**! Every contribution helps make this a better resource for the AI/ML community.

## Ways to Contribute

There are many ways to help, regardless of your experience level:

- **Add or update resource links** — found a great course, paper, or tool? Add it to the relevant track or resource file
- **Suggest new project ideas** — add practical project ideas to any track
- **Improve track content** — expand explanations, add missing topics, update outdated information
- **Fix errors** — typos, broken links, incorrect information
- **Propose new tracks** — if an important area of AI isn't covered, suggest it
- **Translate content** — help make the roadmap accessible in other languages

## Repository Structure

Before contributing, understand how the repo is organized:

```
AI-Roadmap/
  README.md                      # Main roadmap overview
  CONTRIBUTING.md                # This file
  LICENSE                        # MIT license
  tracks/                        # Learning tracks (the core content)
    01-foundations/README.md
    02-classical-ml/README.md
    03-deep-learning/README.md
    04-nlp-and-llms/README.md
    05-computer-vision/README.md
    06-generative-ai/README.md
    07-ai-agents/README.md
    08-mlops-production/README.md
    09-ai-safety-ethics/README.md
    10-emerging-frontiers/README.md
  resources/                     # Curated resource lists
    tools.md
    papers.md
    courses.md
    books.md
    datasets.md
```

## How to Contribute

1. **Fork the repository**

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR-USERNAME/AI-Roadmap.git
   cd AI-Roadmap
   ```

3. **Create a new branch**
   ```bash
   git checkout -b add-resource-langchain-course
   ```
   Use descriptive branch names like `add-resource-X`, `fix-typo-in-track-03`, `update-agents-section`.

4. **Make your changes** following the guidelines below

5. **Commit and push**
   ```bash
   git add .
   git commit -m "Add LangChain course to NLP track resources"
   git push origin add-resource-langchain-course
   ```

6. **Open a Pull Request** with a clear description of what you changed and why

## Content Guidelines

### Adding Resources (courses, papers, tools, books)

- Verify the resource is **high quality and currently available**
- Include a **working link**
- Add a **brief description** of what it covers
- Place it in the **correct category and track**
- Follow the existing **table format** used in each file

### Adding Project Ideas

- Include the **project name**, **difficulty level** (Beginner / Intermediate / Advanced / Expert), and a **one-line description**
- The project should be **practical and achievable** — someone should be able to build it
- Match the project to the **correct track**

### Updating Track Content

- Keep explanations **concise** — this is a roadmap, not a textbook
- Use **tables** for structured information (concept | description format)
- Maintain the existing **section structure**: Core Concepts, Recommended Resources, Project Ideas, What's Next
- Link to **external resources** rather than writing lengthy explanations

### General Rules

- Use **Markdown** formatting consistently
- Keep **links working** — no dead links
- Don't add **promotional or low-quality** content
- Respect the existing **tone**: informative, practical, no hype
- When in doubt, **open an issue first** to discuss your proposed change

## Reporting Issues

Found a problem? Open an issue with:
- A clear **title** describing the problem
- The **file and section** where the issue is
- A **suggested fix** if you have one

---

Questions? Open an issue and we'll help you get started.
