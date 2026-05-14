# MetricFlow — AI-Generated Product Walkthrough

> Built with Claude AI to demonstrate how a product marketer can create interactive product tours with AI assistance.

A live demoable site showing how Rebrandlys Conversion Tracking attributes clicks, page views, and revenue back to the marketing channel that generated them.

The site mocks a fictional analytics SaaS product (**MetricFlow**) so the demo feels like attribution working on a real customers site — independent of Rebrandlys own product.

## Live URLs

- **Demo site:** https://acharles-dev.github.io/metricflow-demo/
- **Tour mode (auto-starts the guided tooltip walkthrough):** https://acharles-dev.github.io/metricflow-demo/?tour=1

## Interactive tour

The site includes a tooltip walkthrough that overlays on the actual pages and explains the conversion tracking setup flow step by step. Click the **Start Demo Tour** button (bottom right) or append `?tour=1` to any page to auto-start.

## What gets tracked

| Event | Where it fires |
|---|---|
| `page_view` | Every page (auto from Rebrandly SDK) |
| `cta_click` | Hero CTAs across the site |
| `pricing_viewed` | Pricing page |
| `signup` | Free signup form |
| `purchase` | Plan checkout |

## Stack

Static HTML/CSS/JS, no build step. Rebrandly SDK loaded via CDN.
