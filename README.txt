iBOUNCE MUSIX V4 - COMPLETE STATIC WEBSITE\n\nOpen index.html to test. Deploy the contents of this folder to GitHub Pages.\nPages: index.html, privacy.html, terms.html, contact.html.\nNavigation and footer links connect the pages.\nContact form opens a pre-filled email in the visitor email app; no backend and no guarantee of delivery.\nBefore launch: review and customize legal drafts to match actual app permissions, SDKs, data handling, business information, and applicable law.\nReplace illustrative app previews and add verified app download URL when available.\n
V5: Real screenshots added in interactive cinematic gallery with next/previous buttons and thumbnails. Ringtone section remains an illustrative concept; no screenshot is claimed. Replace download placeholder before public launch.

V6: Embedded real Android video screen recording at #video-demo. Watch Demo and Fullscreen controls; no autoplay. 15 MB MP4 bundled. IMPORTANT: verify promotional rights to any third-party video/audio content before publishing publicly.

V7: Bootstrap 5.3.3 CDN added to all pages; feature and preview grids use responsive Bootstrap classes. Existing cinematic style, app screenshots, video demo and legal pages preserved. Bootstrap CDN requires internet; original layout CSS remains for offline fallback.

CINEMATIC SPLASH: 9-second muted montage made from the three supplied video files; skip button; African geometric SVG overlay; responsive cover video; reduced-motion fallback. Ensure you have rights to publicly distribute the source footage before publishing.


CLOUD BACKUP STUDIO (NEW): cloud-backup.html and cloud-backup.js are a browser-only Google Drive integration.
SETUP: Create a Google Cloud project, enable Google Drive API, configure OAuth consent screen, create OAuth 2.0 Web application client, add the exact deployed website origin (e.g. https://www.ibouncemusix.com) to Authorized JavaScript origins, and put its PUBLIC client ID in cloud-config.js. No client secret belongs in a public static website. Test users must be added while OAuth app is in Testing mode. Publish/verify the OAuth app as required by Google before broad public use.
Serve on HTTPS; opening via file:// is not supported for Google OAuth.
This implementation uses the limited drive.file permission, so it can restore only files created/accessible to this website's Google OAuth app. It does not access Android-created backup folders automatically, nor does it sync playlists or settings.
Backups are user-selected and manually uploaded; restores download through the browser (they do not directly insert files into the Android media library). Uploads should stay on the page until complete. Browser downloads may need permission for multiple files. No automatic sync, resumable uploads, cancellation, or duplicate detection.
Do not upload copyright-protected media without appropriate rights.

CURRENT APP SHOWCASE UPDATE: Replaced the featured screenshot gallery with four user-provided current Android screenshots, retaining Sound Studio and Playlists screenshots. Current navigation is Home, Music, Videos, Playlists; Magazine and Charts are deferred. Cloud Backup Studio and cinematic splash remain.
