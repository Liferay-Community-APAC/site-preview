# site-preview

The permanent preview site for Liferay Community APAC, published at
<https://liferay-community-apac.github.io/site-preview/>.

It shows a combined build of the Liferay Community APAC website, the Liferay Forums docs and the Solution
Recipes, so changes can be reviewed together on a live address before they go to `main`. Every page is marked
`noindex`, so search engines leave it out. Please keep this repository.

## How to preview a change

1. **Work on a branch** in the repository you're changing:
   [liferay-community-apac.github.io](https://github.com/Liferay-Community-APAC/liferay-community-apac.github.io),
   [liferay-forums](https://github.com/Liferay-Community-APAC/liferay-forums) or
   [solution-recipes](https://github.com/Liferay-Community-APAC/solution-recipes).
2. **Publish it here.** Rebuild the combined site from that branch (and `main` of the other two), add
   `<meta name="robots" content="noindex, nofollow">` to every page, commit the result to `main` of this
   repository, and update **Currently showing** below.
3. **Review** at <https://liferay-community-apac.github.io/site-preview/>, on desktop and phone.
4. **Merge** the branch into `main` of its own repository, then delete the branch.

For a quick check that only you need to see, open the site locally instead of publishing it here.

## Currently showing

- [liferay-community-apac.github.io](https://github.com/Liferay-Community-APAC/liferay-community-apac.github.io), branches `forums-logo` at 9390b7d and `community-online` at 16afcfc, combined
- [liferay-forums](https://github.com/Liferay-Community-APAC/liferay-forums): `main` at d2297d2
- [solution-recipes](https://github.com/Liferay-Community-APAC/solution-recipes): `main` at 32f5cd6
