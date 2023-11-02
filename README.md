# Moral Reasoning and Interaction Design

Welcome to the repository for our **Moral Reasoning and Interaction Design** course website. This repository contains all the necessary files and resources to set up and maintain our course website. Whether you are a student looking to make contributions or an instructor managing the content, this guide will help you get started.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Local Development](#local-development)
- [Making Changes](#making-changes)
  - [Folder Structure](#folder-structure)
  - [Adding Content](#adding-content)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Link to installation guide: [https://jekyllrb.com/docs/installation/](https://jekyllrb.com/docs/installation/)

Before you can build and serve the course website locally, you need to ensure that you have the following prerequisites installed on your system:

- [Ruby](https://www.ruby-lang.org/en/documentation/installation/): Jekyll is a Ruby gem, so make sure you have Ruby installed. You can check your Ruby version with the following command:

  ```sh
  ruby --version
  ```

- [Bundler](https://bundler.io/): Install Bundler, which is used to manage Ruby gem dependencies, by running:

  ```sh
  gem install bundler
  ```

- [Jekyll](https://jekyllrb.com/docs/installation/): To build and serve the website, you need Jekyll. Install it with Bundler:

  ```sh
  bundle install
  ```

## Getting Started

### Installation

1. Clone this repository to your local machine using the following command:

   ```sh
   git clone https://github.com/yourusername/course-website.git
   ```

2. Change into the project directory:

   ```sh
   cd course-website
   ```

3. Install project dependencies using Bundler:

   ```sh
   bundle install
   ```

### Local Development

To serve the website locally, use the following command:

```sh
bundle exec jekyll serve
```

You can then access the website in your browser at `http://localhost:4000`.

## Making Changes

### Folder Structure

The important directories and files in this repository are organized as follows:

- `_includes`: Stores HTML code snippets and includes.
- `_layouts`: Contains layout templates for pages.
- `_sass`: Sass stylesheets for customizing the site's design.
- `_site`: The generated website content (automatically created when building).
- `_config.yml`: The site's main configuration file. Edit this YAML file to customize the website's settings, including site title, description, navigation menus, and more.
- `assets`: For storing static assets like images, CSS, and JavaScript.
- `docs`: Markdown files for website pages (e.g., syllabus).

### Adding Content

To add or modify content, edit the appropriate Markdown files in the `docs` directory or create new ones.

Make sure to follow Jekyll conventions, including using Liquid tags for dynamic content and Markdown for text formatting.

Whenever you commit changes to this repository, GitHub Pages will automatically run Jekyll to rebuild the website from your Markdown files.

## Deployment

This repository is configured to deploy the website using GitHub Pages. When you push changes to the `main` branch, GitHub Pages will automatically build and update the live website. You can access the live site at `https://uelab.github.io/`.

## Contributing

We welcome contributions from students and instructors. To contribute, please:
1. **Submit Issues:** If you encounter bugs, have suggestions for enhancements, or want to discuss any aspect of the website, you can open an issue in our repository. Please make sure to provide as much detail as possible.

2. **Contribute Code:** To directly contribute to the codebase, please fork this repository, create a feature branch, and submit a pull request. Additionally, when creating a pull request, consider linking it to the issue you're addressing. This helps us understand the context and purpose of your pull request.

---

If you have any questions or feedback, please feel free to reach out to [Prof. Alexis Hiniker](https://www.alexishiniker.com/) via email (alexisr@uw.edu).
