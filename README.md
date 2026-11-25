# Hi, I'm Khang Đào

**Frontend developer · React, TypeScript, Next.js**

I build storefronts and interactive web experiences. My projects cover browsing and checkout flows, responsive interfaces, and custom interaction logic.

## Selected projects

| Project | What to look at | Source |
| --- | --- | --- |
| **FORMA** | A UI template storefront prototype with a searchable catalog, interactive previews, simulated checkout, and customer and admin views. Built with Next.js and TypeScript. | [Repository and setup](https://github.com/khangdaodao/selling-temp#readme) |
| **Puzzle Gift** | A React jigsaw puzzle with generated SVG pieces and snapping logic. The TypeScript puzzle engine is separate from the UI, with Vitest coverage for piece geometry and game state. | [Repository](https://github.com/khangdaodao/puzzle_gift) · [Engine tests](https://github.com/khangdaodao/puzzle_gift/blob/main/src/engine/engine.test.ts) |
| **Web of Us** | A web design studio site built with React, TypeScript, and Vite. The project includes motion, form validation, and metadata for individual pages. | [Repository](https://github.com/khangdaodao/mywebsite) |

### Start with FORMA

Run the storefront locally from the setup guide, then try **Library → Product preview → Checkout → My Library**. The prototype uses sample data and browser storage. Sign-in and payment are simulated.

### A closer look at the code

In Puzzle Gift, adjacent pieces share the same edge in opposite directions. The [geometry tests](https://github.com/khangdaodao/puzzle_gift/blob/main/src/engine/engine.test.ts) check that neighboring edges match and that each piece forms a closed outline.
