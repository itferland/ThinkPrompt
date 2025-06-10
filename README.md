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
