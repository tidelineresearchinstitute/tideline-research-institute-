# Tideline Research Institute Website

## Free deployment using GitHub + Cloudflare Pages

1. Create a public GitHub repository named `tideline-research-institute`.
2. Upload every file from this folder to the repository root.
3. In Cloudflare, open **Workers & Pages**.
4. Choose **Create application** → **Pages** → **Connect to Git**.
5. Select the GitHub repository.
6. Choose framework preset **None**. No build command is required for this plain HTML site.
7. Deploy the project.
8. Open the project's **Custom domains** section and add:
   - `tidelineresearchinstitute.org`
   - `www.tidelineresearchinstitute.org`
9. Choose one as the main address and redirect the other.

Every new GitHub commit will automatically publish the updated site.
