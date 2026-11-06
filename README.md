# AI Engineering Notes

A proof of concept for creating and distributing structured technical learning materials through a version-controlled website using GitHub Pages.

**Live Website:** https://sivasindhuja.github.io/Ai-Engineering-Notes/

## Overview

This project explores an alternative to distributing technical learning materials through traditional documents such as Google Docs and Microsoft Word.

The idea was developed while working on an educational initiative involving student AI projects and automated project evaluation.

Alongside the project evaluation workflow, I proposed delivering learning notes through a simple, navigable website.

Instead of sharing multiple documents with students, the content can be organized into a structured HTML page with sections, subsections, and a table of contents.

The website can be hosted using GitHub Pages, providing students with a single public link to access the material.

## Why This Approach?

Traditional document-sharing approaches work, but they have some limitations when learning material grows.

- Students may receive multiple documents for different topics.
- Organizing sections and subsections across documents can become inconvenient.
- Updating content requires ensuring students have access to the latest version.
- Maintaining a consistent structure across multiple documents takes additional effort.

This proof of concept explores a simpler alternative.

### Proposed Approach

- Write and organize learning material in HTML.
- Use a table of contents and internal links to navigate between topics and subtopics.
- Keep the content in a GitHub repository.
- Deploy the repository using GitHub Pages.
- Share one public URL with students.

### Why HTML Instead of Multiple Markdown Files?

Markdown is also a good option for writing technical notes.

However, when content is divided into many topics and nested subsections, maintaining a large collection of individual files can introduce additional organization and navigation overhead.

For this proof of concept, a single HTML page provides:

- A centralized content structure.
- A navigable table of contents.
- Internal links between sections.
- Custom styling for headings, tables, examples, and code blocks.
- A straightforward deployment process through GitHub Pages.

This is a design choice for the current prototype, not a claim that HTML is universally better than Markdown.

## How It Works

1. Learning material is created and organized in the repository.
2. HTML provides the page structure, navigation, and presentation.
3. Changes are committed and tracked through Git.
4. GitHub Pages publishes the website.
5. Students access the latest published material through a shared public link.

```text
Learning Content
       |
       v
  HTML Page
       |
       v
 GitHub Repository
       |
       v
   GitHub Pages
       |
       v
 Public Student Link
       |
       v
 Students Access Notes
```

## Current Content

The repository currently contains learning material and practical exercises in three areas.

### 1. Python Fundamentals

A structured Python study guide covering:

- Python syntax and identifiers
- Variables and data types
- Operators and expressions
- Strings and collections
- Conditional statements and loops
- Functions and recursion
- Object-oriented programming
- The four pillars of OOP
- Decorators and special methods

The guide includes explanations, examples, code snippets, and a sidebar table of contents.

### 2. Data Structures and Algorithms



## Technology

- **HTML** – Structuring learning material.
- **CSS** – Styling and layout.
- **JavaScript** – Table-of-contents navigation and interactions.
- **Git and GitHub** – Version control and content management.
- **GitHub Pages** – Public website hosting.

## Repository Structure

```text
Ai-Engineering-Notes/
│
├── index.html       # Main published Python study guide
├── draft1.html      # Earlier HTML draft
├── DSA.ipynb        # Data Structures and Algorithms exercises
└── mllab.ipynb      # Machine Learning exercises
```

## Deployment

The website is hosted using GitHub Pages.

To publish the repository:

1. Open the repository's **Settings**.
2. Navigate to **Pages**.
3. Select **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder.
5. Save the configuration.

GitHub Pages publishes the website at:

https://sivasindhuja.github.io/Ai-Engineering-Notes/

No separate backend or application server is required for this static website.

## Version Control and Maintenance

One of the main advantages of this approach is that learning content is maintained in GitHub.

This makes it possible to:

- Track changes to learning material.
- Maintain an update history.
- Correct or improve explanations over time.
- Publish updated content through the same public link.
- Keep the learning material accessible without repeatedly sharing new document attachments.

## Project Status

**Proof of Concept (POC)**

The current implementation demonstrates how structured technical notes can be organized into a navigable website and published through GitHub Pages.

It is an initial exploration of a lightweight, maintainable way to distribute learning resources to students.

The approach can be extended to additional subjects, modules, and learning resources as the content grows.

## Key Idea

**Treat learning material as version-controlled content rather than a collection of documents that need to be shared repeatedly.**

A simple HTML page, a GitHub repository, and GitHub Pages are enough to create a public, navigable learning resource.
