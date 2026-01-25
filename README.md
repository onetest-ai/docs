# OneTest Documentation

This directory contains the OneTest documentation built with [Mintlify](https://mintlify.com).

## Local Development

To run the documentation locally:

```bash
# Install Mintlify CLI
npm install -g mintlify

# Start the dev server
cd docs
mintlify dev
```

The documentation will be available at `http://localhost:3000`.

## Deployment

This documentation is automatically deployed to Mintlify hosting when pushed to the main branch.

To deploy:
1. Push changes to the `main` branch
2. Mintlify will automatically build and deploy

## Structure

```
docs/
├── ai/                    # AI Assistant documentation
├── getting-started/       # Getting Started guides
├── oql/                   # OQL query language docs
├── ui/                    # UI feature documentation
├── workflows/             # Workflow guides
├── resources/             # FAQ and best practices
├── logo/                  # Logo files
├── introduction.mdx       # Home page
├── favicon.png           # Site favicon
└── mint.json             # Mintlify configuration
```

## Making Changes

1. Edit MDX files directly
2. Test locally with `mintlify dev`
3. Commit and push to trigger deployment
4. Changes will be live in ~1 minute

## Configuration

All documentation settings are in `mint.json`:
- Navigation structure
- Branding (colors, logo)
- Social links
- Tabs and groups

## Learn More

- [Mintlify Documentation](https://mintlify.com/docs)
- [OneTest Website](https://onetest.ai)
- [OneTest GitHub](https://github.com/onetest-ai)
