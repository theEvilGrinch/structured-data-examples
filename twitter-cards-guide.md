# Twitter Cards Guide

This guide provides a detailed explanation of all Twitter Card fields and tags used in the `structured-data-examples` repository, specifically within `product-landing-page.html`, `service-landing-page.html`, `blog.html`, and `tech-blog.html`. Twitter Cards enhance the presentation of shared content on Twitter, such as displaying images or summaries. All descriptions are based on the official [Twitter Cards documentation](https://developer.twitter.com/en/docs/twitter-for-websites/cards) (last updated April 2025) and are crafted to be clear, detailed, and useful for beginners, adhering to modern web standards.

## Tags for `summary_large_image`

- **`twitter:card`**  
  This tag specifies the type of Twitter Card, set to "summary_large_image". It indicates that the card will feature a large image along with a title and description when shared on Twitter.

- **`twitter:site`**  
  This tag provides the Twitter handle of the website, prefixed with "@" (e.g., "@amazingbrand"). It identifies the account associated with the content.

- **`twitter:title`**  
  This tag contains the title displayed on Twitter. It should be kept to approximately 70 characters to avoid truncation and ensure full visibility.

- **`twitter:description`**  
  This tag provides a summary of the content, displayed on Twitter. It should be between 100 and 200 characters to fit well within the platform’s display limits.

- **`twitter:image`**  
  This tag contains the URL of the image to be displayed on the Twitter Card. It must be in JPEG, PNG, or WebP format, with a minimum resolution of 280 pixels in width and 150 pixels in height, though 1200 pixels in width and 628 pixels in height is recommended for optimal quality. The file size should not exceed 5MB to ensure efficient loading.

- **`twitter:image:alt`**  
  This tag provides a textual description of the image, such as "Photo of a product". It is essential for accessibility, helping users who cannot see the image understand its content.

- **`twitter:creator`**  
  This tag provides the Twitter handle of the content’s author, prefixed with "@" (e.g., "@authorTwitter"). It credits the individual who created the content, helping users identify the author on Twitter.

- **`twitter:image:width`**  
  This tag specifies the width of the image in pixels (e.g., "1200"). It provides Twitter with exact dimensions for proper rendering, though it is optional if the image meets minimum requirements.

- **`twitter:image:height`**  
  This tag specifies the height of the image in pixels (e.g., "630"). It ensures accurate display proportions on Twitter, though it is optional if the image meets minimum requirements.