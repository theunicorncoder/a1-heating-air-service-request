# A1 Mechanical — October 14, 2026 visual update

## Production source
This is the intended source repository: `theunicorncoder/a1-heating-air-service-request` on branch `main`. The original approved compact-site reference commit is `e51219084a59c6b2d57e20f931e2d8fa9c399683`.

The public Pages URL is https://a1-mechanical-site.pages.dev/ .

**Important:** A successful GitHub commit does not imply that the Cloudflare Pages URL has been updated. The Cloudflare page was still showing the earlier design at the end of this edit session. The latest GitHub `main` should be deployed to the Pages project and its render checked.

## Changes in this update
- Keep the existing classic ivory, red and navy styling from `assets/a1-classic.css` and its small button typography.
- Homepage hero and six service thumbnails: HVAC equipment and tools, not repeated owner portraits.
- Other services, field-work, residential, commercial, and contact pages: equipment imagery; about portrait kept.
- Preserve original A1 field video, embedded Atlanta area map, customer inquiry FormSubmit action, and phone/email.
- New `assets/a1-motion.css`: gentle hero camera motion, restrained card hover and scroll reveals, and reduced-motion support.
- Equipment photography is representative, not claimed as actual A1 customer jobs.
- Separate reusable transparent image packet prepared for future native web asset integration.

## Cloudflare Pages publication checklist
1. Open Cloudflare dashboard > Workers & Pages and locate the Pages project whose public URL is `a1-mechanical-site.pages.dev`.
2. Verify the project type, deployment mode and linked production repository/branch. The intended repository is `theunicorncoder/a1-heating-air-service-request`, production branch `main`.
3. If it uses Git integration, configure/deploy the correct production source. If the project is Direct Upload, use the supported Pages upload method for the latest repository build rather than assuming GitHub commits trigger it. Keep the existing public hostname.
4. After deployment, inspect the homepage, mobile navigation, cooling/heating thumbnails, video controls, About portrait, map, telephone links, and request form. Avoid submitting a fake customer lead for testing.
5. Check that external Commons media loads; source and license acknowledgments appear in the footer. Consider hosting optimized approved assets locally to remove external-photo dependencies.
6. The separately named GitHub repo `theunicorncoder/a1-mechanical-site` is **not** the source with the original compact-site commit and should not be substituted without verifying which Cloudflare project it deploys.

## Service contact
- Phone: (404) 200-5932
- Email: Talexander.a1mechanical@gmail.com
