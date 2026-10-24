# VideoExpress browser adapter

Use https://app.videoexpress.ai/ in the user's in-app browser. Reuse the authenticated production tab. This adapter starts from the prior playbook's controls; **it has not been independently live-validated for v1.0**. Read the current interface, adapt to visible labels, and record meaningful differences. Never invent unavailable features or model capabilities.

## Generation

1. Open Create with AI → Create Video From Prompt, or its visible equivalent.
2. Set ratio explicitly. Default is Vertical 9:16.
3. Select the image type matching the actual medium. Prior mapping: Photorealistic (Cinematic) for live action; 3D or 2D for those media; Other for remaining styles. Prior playbook uses Creative mode off for realistic and on for stylized. Treat this as a starting configuration, not a claim that current app behavior is verified. Recheck visible options.
4. Create reference images and save named Consistent Characters if available. Inspect reference use and character selection for every shot. If references are unavailable, use stable text and inspect continuity; disclose limitations when material.
5. Enter starting-frame prompt in Image Prompt; enter numbered motion/audio prompt in Video and Audio Prompt. Use S01, S02, etc. to track clips. Disable automatic prompt enhancement when available to preserve deliberate directions.
6. Use Advanced Mode and manual duration where supported. Choose a supported duration sufficient for the planned action, delivery, and editing handles. Do not force a universal 4/5-second generation or infer supported values from this document.
7. For native dialogue/effects, ensure sound is enabled and select the appropriate visible generation mode. The old playbook used Lipsync HD and Narration Video off with Video Only (No Sound) off. Verify the current mode actually produces the required result. If it cannot, use available audio tools or redesign coverage; do not claim unsupported native audio.
8. Uncheck Share this in the public gallery. Recheck after dialog reopening or rerender settings changes. Recheck ratio, style, duration, reference selection, enhancement, and sound each time.
9. Create Image once, wait for completion, confirm the correct image is selected, and inspect it. Submit Create Video once. Record job ID and actual status before any retry. A timeout may follow a successful submission; inspect before clicking again.
10. Follow the visible concurrency limit. A rejected submission is not a job. Record rendering/complete/failed states independently; existing usable clips survive a failed new shot.

## Assembly and finishing

- Find generated clips in Media Library → My Media → My AI Videos, or current equivalent. Identify by shot cue/job ID, not card position.
- Place clips in narrative order on the main video track. Use Auto Align Clips if available to close unintended gaps, then recheck order and joins.
- Inspect actual preview and sound to select cut points. Use Cut/split and the clip's delete command, or edge trims supported by the interface. Do not use a whole-track trash button to remove one clip.
- Re-read the timeline after trimming, moving, or alignment. Do not assume ruler pixels correspond to a fixed duration. Calibrate the current visible scale if a drag requires it.
- Never apply blind default start/end trims when playback cannot be judged. Preserve usable material and report the review limitation.
- Add supported audio, captions, or graphics only when required by the film plan. Keep important action readable within the final platform layout.
- Save under a versioned name, e.g. “[Title] — Review v01”. Revisions use Save As/new version where available.
- Export intended aspect ratio, High/FullHD/mp4 when supported. Verify displayed settings rather than assuming FullHD equals vertical.
- A queue acknowledgment is not delivery. Wait for the completed entry in My Videos, obtain its actual export link, and review the exported file. If still queued, report queued status and exact project location.

## Recovery and boundaries

Read the screen after consequential actions. If an element changes, inspect fresh state before trying another locator. If the browser session fails, reconnect and inspect actual saved state; never diagnose every automation failure as a permissions problem without evidence.

On login, leave the tab open for the user. On terms or purchases, ask the user to complete the required step. Do not enter credentials or accept legal terms. If out of credits, preserve the plan and ledger before requesting a top-up. If playback is unavailable, separate technical completion from full sound-on review.
