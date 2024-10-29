# WordPress Custom Hover Effects

This repository contains custom CSS code for adding hover effects to icon cards in the "Category" section of a WordPress site. The code customizes background colors, border colors, and icon colors on hover to create a visually appealing user experience.

## Preview

![Hover Effect Preview](hover-effect-preview.png)

## Purpose

Some WordPress themes and plugins don't offer advanced options for customizing hover effects, especially for individual elements like icon cards. This custom CSS helps achieve the desired styling by setting specific colors on hover states, aligning the section with the brand’s color scheme.

## Usage

1. **Add the CSS**: Copy the content from `custom-hover.css`.
2. **Implement in WordPress**: Paste the code into your theme’s `style.css` file or use the WordPress Customizer’s custom CSS section.

### Code Explanation

- `.cards-for-custom-hover .agni-block-icon-card:nth-child(1):hover`: Targets the first child of `.cards-for-custom-hover`, applying a unique background and border color on hover.
- `.agni-block-icon-card-icon__container`: Sets the icon container’s background and border on hover.
- `.ionicon`: Changes the icon color to white when hovering.
- `path` (optional): Uncomment to customize the `path` color if needed.
