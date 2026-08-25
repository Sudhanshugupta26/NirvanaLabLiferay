# Nirvana Lab

This repository contains a Liferay site export (LAR) for the **Nirvana Lab** site.

## Export

- **File:** `Nirvana_Lab_25th_August_2026.lar`
- **Site friendly URL:** `/nirvana-lab`
- **Layout type:** Public site
- **Export date:** 25 August 2026
- **Liferay export build:** `7413`

The archive contains the site configuration and content needed to recreate the
site, including:

- Public site pages and page layouts
- Documents and Media files
- Web Content articles
- Forms and form data
- Fragments, templates, navigation, assets, and portlet configuration

## Importing the Site

1. Sign in to the target Liferay instance as a user with site administration
	 permissions.
2. Open **Control Panel** and go to **Sites**.
3. Create a new site, or open the site that should receive the export.
4. Open the site menu and select **Publishing** > **Import**.
5. Upload `Nirvana_Lab_25th_August_2026.lar`.
6. Review the selected data and dependencies, then start the import.
7. Open the imported site and verify the pages, content, forms, documents,
	 navigation, and theme settings.

The exact menu labels can vary slightly by Liferay version. The LAR should be
imported into a Liferay environment compatible with the export build and with
the applications used by the site enabled.

## Important Notes

- A LAR is a site-content export, not a full Liferay backup. It does not replace
	the target server database, portal configuration, users, or installed modules.
- Back up the target site before importing when importing into an existing site.
- Review missing dependencies reported by the import wizard. The export
	manifest references the Classic theme, so install or select a compatible
	theme if the target instance does not already provide it.
- Check permissions and links after import, especially links to files or other
	sites that may not exist in the target environment.

## Repository Contents

| File | Description |
| --- | --- |
| `Nirvana_Lab_25th_August_2026.lar` | Liferay site export archive |
| `README.md` | Export and import documentation |
| `LICENSE` | Repository license |
