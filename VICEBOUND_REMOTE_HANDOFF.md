# VICEBOUND Android Foundation — Remote Handoff

Status date: 2026-11-24

## GitHub connection verified

- ChatGPT Codex Connector GitHub App installation is now present on the personal account `mujahidahmeds-debug`.
- The installation is visible to the connected GitHub integration.
- Repository access is visible for `mujahidahmeds-debug/GT-caliber-clone`.
- A working branch was created: `vicebound/android-foundation`.

## Important scope note

This branch currently starts from the upstream repository's `main` branch. The locally prepared VICEBOUND Android Foundation bundle has **not yet been synchronized into this remote branch**. Do not treat this handoff file or the branch creation as a completed code migration.

## Local foundation bundle

The local working bundle contains VICEBOUND branding, an Android touch-control layer, mobile renderer defaults, provisional Android export settings, a provider-neutral monetization boundary, a missing-Git-LFS asset inventory, and a commercial asset-release checklist.

Local status: source preparation only. No Godot import, GDScript parse, Android device test, APK/AAB export, signing, ad integration, or Play Billing integration has been verified.

## Blocking items before a commercial release

1. Synchronize and review the actual VICEBOUND source changes on this branch.
2. Restore all required Git LFS objects and the pinned `engine/godot-cpp` submodule.
3. Resolve evaluation-only assets and missing attributions.
4. Run Godot 4.6 import, parser, automated tests, and Android export.
5. Test touch controls and performance on physical low/mid-range Android devices.
6. Integrate and test AdMob and Google Play Billing; implement server-side purchase verification and offline entitlement handling.
7. Complete privacy, consent, store listing, signing, and Play Console checks.

**No APK is attached to this repository yet.**