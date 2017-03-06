# gatsby-typegen-remark-expo-autolink

Adds Github-style links to `MarkdownRemark` headers and list items.

## Install

`npm install --save gatsby-typegen-remark-expo-autolink`

## How to use

```javascript
// In your gatsby-config.js
plugins: [
  {
    resolve: `gatsby-typegen-remark`,
    options: {
      plugins: [
        `gatsby-typegen-remark-expo-autolink`,
      ]
    }
  }
]
```
