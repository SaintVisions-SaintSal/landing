# Public portfolio update workflow

Site: appgprj_6ada3955f6ec8191b85136405d7bec50
URL: https://ryan-capatosto.saintcap-sai-2777.chatgpt.site/
Feed repository: SaintVisions-SaintSal/landing
Branch: main
Path: portfolio/updates.json

## Each run
1. Fetch the current feed through the connected GitHub app. Retain its exact current SHA.
2. Review public first-party sources: https://www.saintsal.ai/; https://www.saintsal.ai/download; https://www.saintsal.ai/pricing; https://saintsallabs.com/; and public posts at https://www.linkedin.com/in/ryan-capatosto-saintsallabs and https://www.linkedin.com/company/saintsalai. GitHub public releases may be checked in the connected SaintVisions-SaintSal repositories, but a commit is not evidence of a production deployment. Do not rely on earlier conversation claims or source snippets when the underlying page is needed.
3. Update the current focus and up to six relevant update cards only with supported public material. Keep each card’s `kind`, `title`, `body`, `url`, and `link_label`. `date` is optional and must be the verified event/publication date, never guessed from relative timestamps. `reviewed_at` is the actual Los Angeles calendar date after a successful source review. `content_updated_at` changes only when substantive content changes.
4. Preserve schema_version=1 and all required fields. Do not add unaudited metrics, fabricated growth, testimonials, customer counts, guaranteed returns, patent scope or legal ownership conclusions. A rollout target is not activated users; a signed-client announcement is not revenue. Do not publish private repositories, internal logs, contracts or financing details. Use SaintSal™ and HACP™. Product differences remain described as design and capability, not unmeasured superiority.
5. Persist via GitHub update_file with the current blob SHA and a clear commit message. On a SHA conflict, refetch, reconcile, then retry once. On source access failure, preserve existing content and review date and report the blocker. Never publish an empty replacement or silently overwrite another change.
6. Read the file back through GitHub and confirm exact content and new SHA. The public page fetches the raw feed when opened. Report the Site link and meaningful changes in the automation result. If no substantive changes, report that it was reviewed without new public milestones.

## Scope
Routine runs update the public JSON only; source/design revisions use the Sites workflow. This permanent Site URL can be featured on both LinkedIn personal and business pages. Updating its feed updates the destination for both links. Do not create daily LinkedIn posts or claim to have changed LinkedIn profile fields. Those profile placements require a verified signed-in LinkedIn session.
