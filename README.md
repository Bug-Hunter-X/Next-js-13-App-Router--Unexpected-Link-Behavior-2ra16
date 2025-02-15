# Next.js 13 App Router: Unexpected Link Behavior

This repository demonstrates a common issue encountered when migrating from the Pages Router to the App Router in Next.js 13. The issue involves the `next/link` component behaving unexpectedly within the new app directory structure.

## Bug Report

The provided `bug.js` file contains a simple component that uses the `next/link` component.  In the App Router, this will either cause a runtime error or simply not navigate to the correct page.

## Solution

The `bugSolution.js` file shows how to fix the issue by correctly placing the link component within the page's layout and ensuring the correct path.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`
3. Run `npm run dev`
4. Observe the broken link behavior in `bug.js`
5. Compare with the working link in `bugSolution.js`