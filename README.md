# OneTest Documentation

This directory contains the OneTest documentation built with [Mintlify](https://mintlify.com).

## Local Development

To run the documentation locally:

```bash
# Install project dependencies locally
npm install

# Start the local Mintlify preview
npm run dev
```

The documentation will be available at `http://localhost:3000`. Use `npm run dev:no-open` when you do not want the CLI to open a browser automatically.

## Deployment

This documentation is automatically deployed to Mintlify hosting when pushed to the main branch.

To deploy:
1. Push changes to the `main` branch
2. Mintlify will automatically build and deploy

## Structure

```
docs/
├── products/              # Applied AI product overviews
├── ai/                    # TMS AI Assistant documentation
├── getting-started/       # TMS getting-started guides
├── oql/                   # TMS query language docs
├── ui/                    # TMS feature documentation
├── workflows/             # TMS workflow guides
├── resources/             # TMS FAQ and best practices
├── logo/                  # Logo files
├── introduction.mdx       # OneTest home page
├── about.mdx              # Product principles and background
├── favicon.png            # Site favicon
└── docs.json              # Mintlify configuration
```

## Making Changes

1. Edit MDX files directly
2. Test locally with `npm run dev`
3. Commit and push to trigger deployment
4. Changes will be live in ~1 minute

## Configuration

All documentation settings are in `docs.json`:
- Navigation structure
- Branding (colors, logo)
- Social links
- Tabs and groups

## Learn More

- [Mintlify Documentation](https://mintlify.com/docs)
- [OneTest Website](https://onetest.ai)
- [OneTest GitHub](https://github.com/onetest-ai)
