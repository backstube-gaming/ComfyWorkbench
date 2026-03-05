# Compliance/Privacy Guide

## Some professionals may use ComfyUI in their daily work and require extra steps to ensure full privacy/data cleanup.

A Non-Disclosure Agreement might apply when creating advertisements for not-yet-released products.
GDRP is a european personal data compliance regulation. For both of these use cases, you should be fine without in ComfyWorkbench without doing anything!

There are a few rare cases in which you would need extra percautions, e.g. when working with a personal photo of a person (you would need written consent by them to do this with AI!) and the person requests full data deletion according to GDRP.
Usually normal data deletion is enough, but if not, ComfyWorkbench takes care to encrypt all generated local files
-> SSD drives cannot permanently/savely delete data, but if you throw away the encryption key, it cannot be restored.

For full compliance, simply:

1. encrypt the HDD/SSD the images are stored on (this is only to fully cleanup the original images, if they are deleted. It has nothing to do with ComfyWorkbench itself)
2. (optional) Set an external key file location in ComfyWorkbench
3. Set a manual password in ComfyWorkbench

!Important! if you lose the key file or password, you will lose tags (full version only) placed on images and some settings.
