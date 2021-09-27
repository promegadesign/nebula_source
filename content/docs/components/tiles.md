---
title: "Tiles"
description: ""
lead: ""
date: 2021-09-01
draft: false
images: []
menu:
  docs:
    parent: "components"
weight: 100
toc: true
---

## Page Status

This page is currently under construction. Use our [Contact Form](https://promega.formstack.com/forms/nebula_contact) if you have questions or feedback.

## Overview

Tiles are large, clickable elements. They are usually used in a group of related items, such as child items under a parent item or resources for the same product/topic. They are distinct from {{< red-link title="Cards" url="#" >}} in that they only link to one target instead of multiple targets.

### Tile Types

#### Resource Tiles
- Tiles are built automatically using content stored on the linked item
  - Icon, label, heading, and background image can be changed by editing the linked item, but edits will be displayed everywhere the linked item is shown in a tile
- No control over styling (CSS, colors, etc.)
- Primarily used for sharing related resources to a central topic or theme
- Example: [Cell Biology Resources](https://www.promega.com/cell-biology/#related-resources)

#### Descendants Grid Tiles (v1)
- Built automatically based on children of parent item
- Content shown on tile is pulled from child item (heading and description)
- One color for background
- No control over styling
- Example: [Cell Biology Product Categories](https://www.promega.com/cell-biology/#descendants-grid)

#### Descendants Grid Tiles (v2)
- Use on the home page and promotions landing page
- 
- Example: [Promotional Offers](https://www.promega.com/products/promotional-offers/)

#### Custom-Built Tiles
-

#### Product Tiles
- Often referred to as "Product Cards" as the design is distinct from other tiles on the site


## Guidelines

### Use Tiles When
- Displaying child items (e.g., sub-pages or sub-categories under a parent category).
- Displaying related items/content under a specific topic or theme.
- Drilling down the path to product.
- Linking to a single destination.
- Displaying less content, including one of each:
  - Heading
  - Image
  - Icon
  - Paragraph text
  - CTA
-

### Don't Use Tiles When
- Linking to multiple destinations. Instead, use a {{< red-link title="link" url="#" >}} or [button](/docs/components/buttons).
- Linking to a file download. Instead, use a {{< red-link title="link" url="#" >}}, [button](/docs/components/buttons), or the {{< red-link title="File Download" url="#" >}} component.
- Displaying complex content, e.g., multiple paragraphs, images, headings and subheadings.


### Do / Don't

<!-- {{< columns >}}
{{< guidelines-correct >}}
{{< img-simple src="/images/components/buttons/do-bg-gradient.png" class="guideline-img">}}
Do make sure buttons are visible against backgrounds.
{{< guidelines-end >}}
{{< column >}}
{{< guidelines-incorrect >}}
{{< img-simple src="/images/components/buttons/dont-busy-bg.png" class="guideline-img">}}
Don't use an outline button on a busy background.
{{< guidelines-end >}}
{{< endcolumns >}}

{{< columns >}}
{{< guidelines-correct >}}
{{< img-simple src="/images/components/buttons/do-contrast.png" class="guideline-img">}}

Do check contrast between button and background.
{{< guidelines-end >}}
{{< column >}}
{{< guidelines-incorrect >}}
{{< img-simple src="/images/components/buttons/dont-contrast.png" class="guideline-img">}}

Don't use a button against a sol background.
{{< guidelines-end >}}
{{< endcolumns >}}

{{< columns >}}
{{< guidelines-correct >}}
{{< img-simple src="/images/components/buttons/do-align-1.png" class="guideline-img">}}
{{< img-simple src="/images/components/buttons/do-align-2.png" class="guideline-img">}}

Match button and text alignment.
{{< guidelines-end >}}
{{< column >}}
{{< guidelines-incorrect >}}
{{< img-simple src="/images/components/buttons/dont-align-1.png" class="guideline-img">}}
{{< img-simple src="/images/components/buttons/dont-align-2.png" class="guideline-img">}}

Don't vary alignment of content within a container.
{{< guidelines-end >}}
{{< endcolumns >}} -->
