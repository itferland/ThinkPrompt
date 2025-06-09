# ThinkPrompt

ThinkPrompt is a curated library of powerful AI prompts designed for creators, marketers, developers, and dreamers. Our goal is to help you supercharge your workflow with ready-to-use commands for various AI tools and platforms.

## ✨ Features

*   A growing collection of prompts across diverse categories:
    *   Text Prompts (Copywriting, Idea Generation, SEO, etc.)
    *   Image Prompts (Midjourney, DALL·E, Firefly, etc.)
    *   Music Prompts (Suno, Boomy, AIVA, etc.)
    *   Video Prompts (Runway, Pika, etc.)
    *   Project Builders & How-to Guides
    *   Instructional Prompts
    *   Prompt Gems (Journals, World-Builders, Games, etc.)
*   Organized by categories and tags for easy discoverability.
*   Includes guidance on prompt engineering (see `about.md`).

## 🛠 Tech Stack

This website is built as a static site using [Jekyll](https://jekyllrb.com/). Prompts are stored as Markdown files.

## 🚀 Getting Started

To get a local copy up and running:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/thinkprompt.git
    cd thinkprompt
    ```
2.  **Serve the site (requires Ruby and Jekyll):**
    *   Install Bundler: `gem install bundler`
    *   Install dependencies: `bundle install`
    *   Serve the site: `bundle exec jekyll serve`
    The site will typically be available at `http://localhost:4000`.

If you don't have Ruby/Jekyll set up, you can still browse the prompts directly in the `_prompts/` directory and view the main page by opening `index.html` in your browser (though Jekyll-specific features won't work).

## ✍️ Adding New Prompts

We welcome contributions! To add a new prompt:

1.  Create a new Markdown file (e.g., `my-new-prompt.md`) in the `_prompts/` directory.
2.  Add Jekyll frontmatter at the top of the file. Ensure you include:
    *   `title`: A descriptive title for your prompt.
    *   `tool`: The AI tool(s) the prompt is best suited for (e.g., `ChatGPT`, `Midjourney`, `Suno`).
    *   `tags`: A list of relevant tags (lowercase, use existing tags from `_data/tags.yml` if applicable, or suggest new ones).
    *   `category`: The main category for the prompt (e.g., `text`, `image`, `instructional`, `gem`).

    Example frontmatter:
    ```yaml
    ---
    title: Generate a Python Script for Web Scraping
    tool: ChatGPT-4
    tags: [code, python, webscraping, instructional]
    category: instructional
    ---
    ```
3.  Write the body of your prompt in Markdown below the frontmatter. Be clear and concise.

## 🏷 Adding New Tags

If your prompt requires a new tag:

1.  Edit the `_data/tags.yml` file.
2.  Add your new tag with a `name` (lowercase, hyphenated if needed) and a user-friendly `label`.
    ```yaml
    - name: my-new-tag
      label: My New Tag
    ```

## 📄 License

This project is licensed under the MIT License - see the `LICENSE.md` file for details. (Note: `LICENSE.md` to be added separately).

---

Happy Prompting!
