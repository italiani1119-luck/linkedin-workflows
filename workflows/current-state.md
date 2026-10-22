# LinkedIn workflows — current configuration

This is a snapshot of the active Lindy routines as of 2026-10-22. The GitHub repository is private.

## LinkedIn remote job matches
- Lindy routine ID: `6ad9735a0ae39154de1432b7`
- Enabled: yes
- Schedule: daily at 05:00, 09:00, 13:00, 17:00, and 22:00 Asia/Jakarta.
- Scope: procurement, executive assistance, personal assistance, virtual assistance, and administrative support roles.
- Eligibility: listing must be active and explicitly open worldwide or to applicants in Indonesia/Asia; do not infer eligibility from the employer's global presence.
- Posting age: verifiably between 24 hours and 7 days at run time. Exclude newer, older, or unverifiable postings.
- Deduplication: do not repeat URLs in `/agent/user/Routines/linkedin-remote-jobs/seen_urls.txt`.
- Delivery: Resend from `Ita Liani <reminder@r2studio.my.id>` to `italiani1119@gmail.com`; send only when new verified matches are found. Do not contact employers or apply.

## LinkedIn post drafts
- Lindy routine ID: `6ad96931eb9db68c86c18bd9`
- Enabled: yes
- Schedule: daily at 08:00 Asia/Jakarta.
- Drafts an English personal-branding post (150–250 words) on rotating procurement, executive-assistant, or personal-assistant topics, then emails the preview to `italiani1119@gmail.com` for review before the 10:00 posting routine.

## Daily LinkedIn post
- Lindy routine ID: `6ad967f22e49feeef81fc557`
- Enabled: yes
- Schedule: daily at 10:00 Asia/Jakarta.
- Publishes the approved/pending post publicly on the user's personal LinkedIn profile, records the post URN for comment tracking, and removes the pending draft file after posting.

## LinkedIn comment reply drafts
- Lindy routine ID: `6ad96be3d837bde634e51fc2`
- Enabled: yes
- Schedule: Monday–Friday at 08:00, 10:00, 12:00, 14:00, 16:00, and 18:00 Asia/Jakarta.
- Creates English reply drafts for new comments on the user's posts and emails them to `italiani1119@gmail.com`; it never posts replies.

## Sync limitation
This file is a manual snapshot. Lindy does not expose a trigger for routine-configuration changes, so it cannot automatically sync edits to GitHub in real time. Update this file manually whenever the Lindy routine configuration changes, unless an external sync mechanism is added.
