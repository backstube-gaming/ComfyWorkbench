# COMFYWORKBENCH (BETA)

## Submit bug reports and feature requests here:

[Issue Tracker](https://github.com/backstube-gaming/ComfyWorkbench/issues)

  <br>                                                                                                                                                                                               
  <br>                                                                                                                                                                                               
  <br>

# Main Features

Next level of ComfyUI image collection organization.
(for now only for Windows)

<img src="screenshots/diff-overlay.png" alt="ComfyWorkbench showcase image" width="720">

## The tool you did not know you needed when working with many generated images in ComfyUI.

- Queued up 200+ image generations and not sure what changed between the good and bad ones afterwards?
- Want to delete, rename, sort, and compare without losing track?
- Trying to find a specific image based on its prompt?
- Scrolling forever just to clean up output folders?

Then ComfyWorkbench is built for you!

## Core features (all Free!)

### Workflow review and diffing

- Automatically track new images.
- Direct workflow insights.
- Diff Overlay: see model, prompt differences between successive images at a glance.
- LoRA values panel: easily see and compare LoRA settings between images.

<img src="screenshots/base-and-new_hint.png" alt="Marked new images and Workflow insights" width="400"  height="205">
<img src="screenshots/lora-values_hint.png" alt="LoRA values panel" width="400" height="205">
<img src="screenshots/diff-zoomed.png" alt="Diff overlay" width="400">

### Cleanup and organization

- Fast delete flow: clear weak generations quickly.
- Accident-safe multi-selection: never lose your selection again with an accidental misclick, including undo/redo your previous selections.
- Rename many files at once: re-organize your images, even supporting prefix or regex patterns.

<img src="screenshots/organize-mode.png" alt="Select and Delete" width="400" height="205">
<img src="screenshots/rename.png" alt="Advanced Batch Rename" width="400" height="205">

### Search, metadata, and workflow handling

- Search by name or automatically created name clusters.
- Full metadata access: view complete workflow information from any image.
- Customizable keybinds: rebind keyboard shortcuts to your preference.
- Drag and drop images directly from ComfyWorkbench into ComfyUI, a new folder, or other apps.
- Designed to handle large amounts of images (tested with 15k+).
- Manage multiple locations without losing your progress.
- Supports workflow extraction for: PNG, WEBP. Organization features support PNG, WEBP, JPG, JPEG, BMP, GIF, ICO, and WBMP.

<img src="screenshots/auto-groups.png" alt="Automatic groups" width="400">
<img src="screenshots/full-meta.png" alt="Full metadata" width="400" height="205">
<img src="screenshots/custom-rules.png" alt="Custom Rules" width="400" height="300">
<img src="screenshots/keybinds.png" alt="Keybind settings" width="400" height="300">

<br>
<br>
<br>

## Full version (one-time payment, lifetime unlock - including updates)

- Advanced search (full-text ComfyUI workflow search and tag search).
- Compare mode: Refine images by directly comparing them to a Base-image.
- Freely Pop-out images into picture frames (with slideshow support).
- Subfolder support.
- Tag your images.
- Favorite filename groups and tag groups.
- One-click move to Final folder.
- Adjustable slideshow timing.
- Buys us more coffee! ☕
- Priority bug-fix and feature-request consideration.

**Always try the Free Edition first to make sure ComfyWorkbench is fully compatible with your machine and workflows!**

<img src="screenshots/search-by-meta.png" alt="Workflow search" width="400" height="205">
<img src="screenshots/picture-frame.png" alt="Picture frames" width="400"  height="205">
<img src="screenshots/tags.png" alt="Tags" width="400">

### Compare mode (Full version only)

Compare candidates side-by-side and make faster decisions when refining images.

<img src="screenshots/compare-mode_hints.png" alt="Compare mode" width="400">

## 100% Local and Private

- Runs locally with no ads.
- GDPR-conscious approach. All App-managed cache data is fully encrypted. \*
- Designed to also support professional NDA-bound workflows without restrictions. \*

Note: \* drag and drop naturally exposes the full path of the dragged file to the OS and the target app. For full GDPR compliance, ensure the used hard drive is encrypted as well, for example with BitLocker.

## Current limitations

- Currently Windows only.
- Performance tests with low RAM PCs were limited.
- Some custom nodes may not work properly yet, though almost all should be possible to use with the custom extractions. Request specific node support via the GitHub issue tracker.

## Requirements

- Windows 10 or 11.
- 8 GB RAM minimum (lower amounts not fully tested).

## Just try it!

Start with the free version of ComfyWorkbench and see for yourself.

ComfyWorkbench © Backstube-Gaming 2026, all rights reserved.

# FAQ

## Is the full/paid version of ComfyWorkbench a subscription?

No! You just buy the full version once and it belongs to you forever, including any future updates.

## Why is ComfyWorkbench showing up as untrusted/unrecognized?

ComfyWorkbench is not backed by a large organization and acquiring a trusted certificate is quite expensive.
The only reason it shows up as "untrusted" is that Windows does not know us as a verified publisher.
If you trust our own certificate once, all updates should not show up as untrusted again.

## Why is ComfyWorkbench Windows only for now?

We are working on making ComfyWorkbench usable on MacOS and Debian/Ubuntu as well, just like ComfyUI does, however, we have not found a good approach that fulfills all our requirements yet.

## Is ComfyWorkbench private?

Yes. The only time ComfyWorkbench connects to the internet is to check for updates directly with itch.io. That can also be turned off in the settings.
No data is ever collected about the user, or usage. (The download/payment process on itch.io may collect some personal data, but that is never transferred to or used by us.)

## Do you support custom node XXX?

Yes. Almost any custom node works, if you add a custom diff extraction for it (under Settings > Diff Extractions).
We will try to support any widely used node out-of-the-box in the future. If something does not work, you can request support using [Issue Tracker](https://github.com/backstube-gaming/ComfyWorkbench/issues)

## Can I use ComfyWorkbench to organize non-ComfyUI image collections?

Yes. ComfyWorkbench's organizational features (delete, rename, move) work with many kinds of image files! (PNG, WEBP, JPG, JPEG, BMP, GIF, ICO, and WBMP)
The ComfyUI workflow features like diff-overlay and details inspections will just be empty.
Video formats and animated GIF are not supported though.

## What is the GDPR or NDA bound work you mentioned?

Some professionals may use ComfyUI in their daily work. A Non-Disclosure Agreement might apply when creating advertisements for not-yet-released products.
GDPR is a European personal data compliance regulation. For both of these use cases, you should be fine without in ComfyWorkbench without doing anything!
If you need to make absolutely sure or are working with extra sensitive cases, see this guide: [Compliance/Privacy guide](compliance-guide.md)

## What happens if I lose a manual password for a location?

Not much! Just delete the location and add the path again.
You will only lose any tags you have put on images (full version) and some location specific settings, nothing else.
The encryption is mostly used to encrypt thumbnails and workflow data, which is automatically re-generated the next time you start ComfyWorkbench.

## Does ComfyWorkbench prevent opening a location with a manual password?

No. It cannot be opened in ComfyWorkbench, making settings and tags inaccessible, but of course it is still possible to use Windows to open the folder itself.
