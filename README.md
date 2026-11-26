# S-A-J-W-A-L Uploader+ Web Edition

A mobile-friendly web conversion of the local MP4 patching portion of the original browser extension.

## Included
- Local MP4 container patching in the browser
- H.264/AVC and H.265/HEVC patching via the existing `mp4-container-patcher.js`
- `_rein.mp4` output download
- Android-friendly responsive UI
- S-A-J-W-A-L branding

## Important limitation
A normal website cannot install content scripts into TikTok, intercept TikTok's `fetch`/XHR publishing payloads, or programmatically control the TikTok upload page the way a Chrome extension can. The web edition therefore keeps the local MP4 processing workflow, while the TikTok upload step remains manual.
