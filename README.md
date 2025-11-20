# Dance Pinoy Blogger Theme

This is the Dance Pinoy Blogger Theme, a customized template for the Dance Pinoy blog. This theme has been updated to improve its Search Engine Optimization (SEO), social media sharing capabilities, and structured data implementation.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Customization](#customization)
- [Author](#author)

## Features

This updated theme includes the following enhancements:

-   **Improved SEO (Search Engine Optimization):**
    -   Refined title tag logic to ensure accurate and dynamic page titles across all page types (homepage, posts, static pages, archives, search results). This helps search engines better understand the content of each page.
-   **Enhanced Social Media Sharing:**
    -   Comprehensive Open Graph (for platforms like Facebook, LinkedIn) and Twitter Card meta tags have been implemented. This ensures that when your articles are shared, they display with rich previews including correct titles, descriptions, and images.
    -   Dynamic descriptions and images are used based on the page content, with a fallback for when specific post images are not available.
-   **Better Website Schema (Structured Data):**
    -   Implemented JSON-LD structured data (Schema.org) for `WebSite` and `BlogPosting`. This provides search engines with detailed information about your site and its content, which can improve visibility in search results and enable rich snippets.
    -   The schema now accurately reflects the subdomain's content and title, resolving issues where the main domain title was incorrectly displayed.

## Installation

To install this theme on your Blogger blog:

1.  **Backup your current theme:** Always download a backup of your existing theme from the Blogger dashboard (`Theme` -> `Backup / Restore` -> `Download theme`).
2.  **Edit HTML:** In your Blogger dashboard, navigate to `Theme` and then click on `Edit HTML`.
3.  **Replace Theme Code:** Select all the existing code in the editor and replace it with the content of this `theme.xml` file.
4.  **Save Theme:** Click the "Save theme" button.

## Customization

-   **Default Social Sharing Image:** The theme includes a fallback image for social media sharing (`URL_TO_DEFAULT_IMAGE`). It is highly recommended to replace `URL_TO_DEFAULT_IMAGE` in the `theme.xml` file with a URL to a default image that represents your blog (e.g., your blog's logo or a generic banner). This ensures an image is always displayed when a post doesn't have one.

## Author

This Blogger theme was originally authored by Nash Ang under PinoySeoul Media Enterprise.
