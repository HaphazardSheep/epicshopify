# Shopify Theme Repository

This repository is prepared for Shopify's GitHub theme integration.

## Theme branch
Connect the `shopify-theme` branch in Shopify.

## Required structure
The connected branch must contain the Shopify buildless theme structure at the repository root:

- assets/
- config/
- layout/
- locales/
- sections/
- snippets/
- templates/

## Connect in Shopify
1. Install/connect the Shopify GitHub app.
2. In Shopify admin, go to **Online Store → Themes**.
3. Choose **Add theme → Connect from GitHub**.
4. Select the GitHub account **HaphazardSheep**.
5. Select **epicshopify**.
6. Select the **shopify-theme** branch.

Shopify will sync commits between this branch and the connected theme.

## Theme source
The source theme export is the Horizon theme export for the Spectral Co. store. The ZIP supplied separately contains the theme files and should be unpacked at the repository root before connecting the branch.

## Important
Do not put the ZIP itself inside the repository as the theme source. Shopify expects the theme folders/files directly in the branch root.
