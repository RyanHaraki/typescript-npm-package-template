(repo generated using claude code for me to bootstrap npm packages)

# TypeScript NPM Package Template

A simple TypeScript NPM package template ready for publishing.

## Getting Started

1. **Install dependencies:**

   ```bash
   npm install
   ```

2. **Build the package:**

   ```bash
   npm run build
   ```

3. **Customize the package:**
   - Update `package.json` with your package name, description, and author
   - Modify `src/index.ts` with your actual code
   - Add keywords relevant to your package

## Publishing to NPM

1. **Create an NPM account** at [npmjs.com](https://www.npmjs.com) if you don't have one

2. **Login to NPM:**

   ```bash
   npm login
   ```

3. **Update package name** in `package.json` to ensure it's unique on NPM

4. **Publish:**
   ```bash
   npm publish
   ```

The build process runs automatically before publishing thanks to the `prepublishOnly` script.

## Scripts

- `npm run build` - Compile TypeScript to JavaScript
- `npm publish` - Build and publish to NPM

## Package Structure

- `src/` - TypeScript source files
- `dist/` - Compiled JavaScript output (auto-generated)
- `package.json` - Package configuration
- `tsconfig.json` - TypeScript configuration
# typescript-npm-package-template
