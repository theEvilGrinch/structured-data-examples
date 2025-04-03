# Structured Data Examples

This repository provides practical examples of structured data markup using [Schema.org](https://schema.org) and [Open Graph](https://ogp.me/) protocols. These examples are designed to help developers implement structured data on their websites to improve search engine optimization (SEO), enable rich snippets in search results, and enhance social media sharing.

## Table of Contents

- [Introduction](#introduction)
- [Included Files](#included-files)
  - [Product Landing Page](#product-landing-page)
  - [Service Landing Page](#service-landing-page)
- [Usage](#usage)
- [Validation](#validation)

## Introduction

Structured data markup helps search engines and social platforms understand the content of web pages more effectively. By implementing Schema.org and Open Graph protocols, developers can:
- Boost SEO with rich snippets (e.g., product prices, ratings, or business details in search results).
- Ensure proper rendering of shared links on platforms like Facebook, Twitter, and LinkedIn.

This repository contains two example files demonstrating structured data for common use cases: a product landing page and a service landing page.

## Included Files

### Product Landing Page

- **File**: `product-landing-page.html`
- **Description**: This example showcases structured data for an e-commerce product page using Schema.org's `Product` type and Open Graph's `product` type.
- **Key Features**:
  - **Schema.org**: Includes product details such as name, image, description, brand, SKU, offers (with pricing and availability), shipping details, return policy, and reviews.
  - **Open Graph**: Uses `og:type="product"` with properties like `og:price:amount`, `og:price:currency`, and `og:brand`.
- **Use Case**: Perfect for online stores or product-focused landing pages aiming to display rich snippets and improve social sharing.

### Service Landing Page

- **File**: `service-landing-page.html`
- **Description**: This example demonstrates structured data for a local service provider (e.g., computer repair) using Schema.org's `LocalBusiness` type and Open Graph's `website` type.
- **Key Features**:
  - **Schema.org**: Provides business details like name, address, phone, email, opening hours, services offered, pricing range, and customer reviews.
  - **Open Graph**: Uses `og:type="website"` с общими метаданными вроде заголовка, описания и изображения.
- **Use Case**: Ideal for local businesses or service providers looking to enhance local SEO and social media visibility.

## Usage

To use these examples:
1. Clone or download this repository:  
```bash
  git clone https://github.com/theEvilGrinch/structured-data-examples.git  
```
2. Open the HTML files (`product-landing-page.html` or `service-landing-page.html`) in a text editor or browser to review the markup.
3. Customize the structured data by replacing placeholder values (e.g., URLs, names, prices) with your own content.
4. Embed the modified markup into the `<head>` section of your web page.

## Validation

After implementing the structured data, validate it using these tools:
- **[Google Rich Results Test](https://search.google.com/test/rich-results)**: Checks Schema.org markup for errors and eligibility for rich snippets.
- **[Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/)**: Verifies Open Graph metadata for social media sharing.
- **[Twitter Card Validator](https://cards-dev.twitter.com/validator)**: Ensures Twitter Card markup works correctly.

Test your pages to resolve any warnings or errors before deployment.

## ⚖️ License

MIT Licensed - See [LICENSE](LICENSE) for details.

---

⚡ Maintained by [@theEvilGrinch](https://github.com/theEvilGrinch)