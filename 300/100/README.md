# 100 - Getting Started

The following commands are meant to be run in **both** the ```/app``` and ```/studio``` folders.

1. ```npm install``` to install dependencies
2. ```npx -y sanity@latest init --env```, this will:
- ask you to select or create a Sanity project and dataset, use the same Sanity project and dataset in both folders.
- output a .env file with appropriate variables
- (or use sanity init --env if you have the CLI installed)
3. Prefix your environment variables in the SvelteKit /app folder with PUBLIC_, they should be PUBLIC_SANITY_DATASET and PUBLIC_SANITY_PROJECT_ID.
4. npm run dev to start the development server

Your SvelteKit app should now be running on http://localhost:5173/ and Studio on http://localhost:3333/.

*Feel free to move each of the folders to their own location and check them into version control.*

## 100 - Add content

See [README.md](./100/README.md)
