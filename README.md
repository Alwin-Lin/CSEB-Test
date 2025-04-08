# CS Equity AI Charter Website

A professional website for Computer Science Equity AI Charter (CSEB), built with Jekyll and the Minimal Mistakes theme, hosted on GitHub Pages.

## Project Overview

This website serves as the online presence for CS Equity AI Charter, an organization dedicated to democratizing computer science and AI education for students from diverse backgrounds. The site showcases the organization's mission, educational programs, events, team members, and contact information.

## Features

- Responsive design that works on mobile, tablet, and desktop
- Clean, professional aesthetic using the Minimal Mistakes Jekyll theme
- Blog functionality for event updates and announcements
- Dedicated pages for various aspects of the organization
- Easy to update using Markdown and simple front matter

## Getting Started

### Prerequisites

- GitHub account
- Basic knowledge of Markdown
- Git (optional for local development)
- Ruby and Jekyll (optional for local testing)

### Quick Start (GitHub Only)

1. Fork this repository to your GitHub account
2. Enable GitHub Pages in your repository settings
3. Edit the content files in the `_pages` directory to update your website
4. Add blog posts to the `_posts` directory following the existing naming format

### Local Development

If you want to test changes locally before pushing to GitHub:

1. Install Ruby and Jekyll (follow instructions at [jekyllrb.com](https://jekyllrb.com/docs/installation/))
2. Clone this repository to your local machine
3. Run `bundle install` to install dependencies
4. Run `bundle exec jekyll serve` to start a local server
5. Visit `http://localhost:4000` to see your site

## Website Structure

The website consists of the following main sections:

- **Home**: Landing page introducing the organization
- **Events**: Upcoming and featured events
- **Educational Programs**: Overview of courses and learning opportunities
- **Past Events**: Archive of previous events and activities
- **Team Members**: Information about leadership and staff
- **About Us**: The organization's story, mission, and objectives
- **Contact**: Ways to get in touch with the organization

## Customizing Content

### Pages

All main pages are located in the `_pages` directory and are written in Markdown. To edit a page:

1. Find the corresponding `.md` file in the `_pages` directory
2. Edit the content using Markdown syntax
3. Save the file and commit changes

### Blog Posts

Event announcements and news are managed as blog posts:

1. Create new `.md` files in the `_posts` directory
2. Follow the naming convention: `YYYY-MM-DD-title.md`
3. Include the appropriate front matter at the top of the file
4. Write your content using Markdown

### Navigation

To update the navigation menu:

1. Edit `_data/navigation.yml`
2. Follow the existing format to add, remove, or rearrange menu items

### Configuration

Site-wide settings are controlled in `_config.yml`. Here you can change:

- Site title and description
- Contact information
- Social media links
- Theme settings and appearance

## Youtube Demo Link

[Demo Link](https://www.youtube.com/watch?v=1L509JK8p1I)

## License

This project is available as open source under the terms of the [MIT License](LICENSE).

## Contact

For questions or support regarding this website, contact CSEquityAI@gmail.com.
