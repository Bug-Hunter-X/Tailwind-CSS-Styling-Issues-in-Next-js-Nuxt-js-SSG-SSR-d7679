# Tailwind CSS Styling Issues in Next.js/Nuxt.js SSG/SSR

This repository demonstrates a common issue encountered when using Tailwind CSS within frameworks like Next.js or Nuxt.js that utilize Static Site Generation (SSG) or Server-Side Rendering (SSR). The problem often manifests as missing or incorrect styling, despite seemingly correct Tailwind class usage.

## Bug Description:

The `bug.js` file contains a Next.js component where a simple Tailwind class (`bg-blue-500`) is applied.  In environments with SSG/SSR, the expected blue background might not render.

## Solution:

The `bugSolution.js` file demonstrates solutions for resolving this issue, which typically involve ensuring Tailwind's CSS is correctly injected during the build process. The specific solution will depend on the framework used and its configuration.