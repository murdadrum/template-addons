# Add-on: Node + Vite/React

# template-addons

A collection of stack add-ons to apply to new repos created from your lean template.

## Add-ons
- `addons/node-vite-react` — pnpm workspace + Vite/React + formatting/lint + CI
- `addons/python` — pyproject + ruff + pytest + CI (add next)

## How to apply
Copy the folder contents into your target repo root, then commit.

Example:
cp -R ../template-addons/addons/node-vite-react/* .


## Apply
Copy this folder’s contents into your repo root.

## Scaffold app
```bash
pnpm dlx create-vite@latest apps/web --template react-ts
pnpm install
pnpm dev


# Notes

## Root uses pnpm workspaces

## CI runs only if package.json exists


✅ After you apply the add-on in a new project:
```bash
pnpm dlx create-vite@latest apps/web --template react-ts
pnpm install
pnpm dev
