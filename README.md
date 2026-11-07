![Mrittika](assets/banner.svg)

# Mrittika

> A modern content-driven web platform with a dedicated local admin panel and GitHub-powered publishing workflow.

Mrittika is a lightweight web platform designed to provide a simple and efficient way to manage website content without requiring a traditional backend CMS.

The project separates the public-facing website from the administration and publishing interface. Website content is maintained through a structured `store.json` data file, while the local admin panel allows authorized users to manage products, categories, blog content, hero sections, and site settings and publish changes directly to GitHub.

## Key Features

- Modern public-facing website
- Dedicated local administration panel
- Product and category management
- Blog/content management
- Hero section management
- Site settings management
- Structured JSON-based content storage
- GitHub-based publishing workflow
- Local admin authentication
- GitHub repository configuration stored locally
- No GitHub credentials exposed in the public website

## Project Structure

```text
mrittika/
├── index.html
├── admin.html
└── data/
    └── store.json
