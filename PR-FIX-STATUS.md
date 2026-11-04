# Marketplace PR fixes and validation

Reviewed and prepared November 3, 2026 (America/New_York).

All 18 open PRs were checked independently. Each branch passed its full test suite with zero failures and zero skips. These branches have not been merged together; this is not a combined integration result. The original PRs and production marketplace have not been modified.

Thirteen branches contain prepared changes. Five preserve the existing contributor changes after validation. Registry corrections and the GaugeDB/DB Studio changes are based on current upstream main; the other follow-ups retain their contributor-branch base.

## Submitted draft pull requests

These requests have been opened for review. The original requests remain open; no changes have been merged or deployed.

| Original marketplace PR | Submitted draft | Destination |
| --- | --- | --- |
| [#10894](https://github.com/omacom/omarchy-plugin-marketplace/pull/10894) | [Open draft](https://github.com/omacom/omarchy-plugin-marketplace/pull/13822) | `omacom/omarchy-plugin-marketplace` → `main` |
| [#11100](https://github.com/omacom/omarchy-plugin-marketplace/pull/11100) | [Open draft](https://github.com/omacom/omarchy-plugin-marketplace/pull/13823) | `omacom/omarchy-plugin-marketplace` → `main` |
| [#11858](https://github.com/omacom/omarchy-plugin-marketplace/pull/11858) | [Open draft](https://github.com/omacom/omarchy-plugin-marketplace/pull/13824) | `omacom/omarchy-plugin-marketplace` → `main` |
| [#12653](https://github.com/omacom/omarchy-plugin-marketplace/pull/12653) | [Open draft](https://github.com/omacom/omarchy-plugin-marketplace/pull/13825) | `omacom/omarchy-plugin-marketplace` → `main` |
| [#13074](https://github.com/omacom/omarchy-plugin-marketplace/pull/13074) | [Open draft](https://github.com/dagelf/omarchy-plugin-marketplace/pull/1) | `dagelf/omarchy-plugin-marketplace` → `plugin-archive-guide` |
| [#13359](https://github.com/omacom/omarchy-plugin-marketplace/pull/13359) | [Open draft](https://github.com/silversword411/omarchy-plugin-marketplace/pull/1) | `silversword411/omarchy-plugin-marketplace` → `feat/search-bar-help` |
| [#13496](https://github.com/omacom/omarchy-plugin-marketplace/pull/13496) | [Open draft](https://github.com/omacom/omarchy-plugin-marketplace/pull/13826) | `omacom/omarchy-plugin-marketplace` → `main` |
| [#13547](https://github.com/omacom/omarchy-plugin-marketplace/pull/13547) | [Open draft](https://github.com/OnurByte/omarchy-plugin-marketplace/pull/1) | `OnurByte/omarchy-plugin-marketplace` → `codex/fit-wide-preview` |
| [#3062](https://github.com/omacom/omarchy-plugin-marketplace/pull/3062) | [Open draft](https://github.com/JoeJoeflyn/omarchy-plugin-marketplace/pull/1) | `JoeJoeflyn/omarchy-plugin-marketplace` → `feature/page-input` |
| [#5697](https://github.com/omacom/omarchy-plugin-marketplace/pull/5697) | [Open draft](https://github.com/omacom/omarchy-plugin-marketplace/pull/13827) | `omacom/omarchy-plugin-marketplace` → `main` |
| [#6403](https://github.com/omacom/omarchy-plugin-marketplace/pull/6403) | [Open draft](https://github.com/riccardolanza05/omarchy-plugin-marketplace/pull/1) | `riccardolanza05/omarchy-plugin-marketplace` → `fix/restart-shell-for-clonedfrom-installs` |
| [#6513](https://github.com/omacom/omarchy-plugin-marketplace/pull/6513) | [Open draft](https://github.com/itsgg/omarchy-plugin-marketplace/pull/1) | `itsgg/omarchy-plugin-marketplace` → `fix/pip-install-mention-without-a-package` |
| [#8905](https://github.com/omacom/omarchy-plugin-marketplace/pull/8905) | [Open draft](https://github.com/omacom/omarchy-plugin-marketplace/pull/13828) | `omacom/omarchy-plugin-marketplace` → `main` |

## Results

| PR | Result | Tests passed | Prepared branch |
| --- | --- | ---: | --- |
| [#13549: Resolve standard installation approval using the actual label event time](https://github.com/omacom/omarchy-plugin-marketplace/pull/13549) | Validated existing change | 370 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-13549) |
| [#13547: Fit wide preview banners inside marketplace cards](https://github.com/omacom/omarchy-plugin-marketplace/pull/13547) | Changes prepared | 370 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-13547) |
| [#13496: Restore standard installation for Loadlet](https://github.com/omacom/omarchy-plugin-marketplace/pull/13496) | Changes prepared | 367 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-13496) |
| [#13359: Feat/search bar help](https://github.com/omacom/omarchy-plugin-marketplace/pull/13359) | Changes prepared | 386 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-13359) |
| [#13351: Add maintenance signal and search terms](https://github.com/omacom/omarchy-plugin-marketplace/pull/13351) | Validated existing change | 385 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-13351) |
| [#13167: Add a finance tag](https://github.com/omacom/omarchy-plugin-marketplace/pull/13167) | Validated existing change | 367 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-13167) |
| [#13074: Document and validate optional export-ignore plugin packages](https://github.com/omacom/omarchy-plugin-marketplace/pull/13074) | Changes prepared | 368 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-13074) |
| [#12653: Restore standard installation for Restic Backups](https://github.com/omacom/omarchy-plugin-marketplace/pull/12653) | Changes prepared | 367 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-12653) |
| [#12164: Show loading placeholders while the catalog loads](https://github.com/omacom/omarchy-plugin-marketplace/pull/12164) | Validated existing change | 367 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-12164) |
| [#11858: Add a manual-installation override for Omagram](https://github.com/omacom/omarchy-plugin-marketplace/pull/11858) | Changes prepared | 367 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-11858) |
| [#11100: Show a separate GaugeDB header logo and prioritize game discovery](https://github.com/omacom/omarchy-plugin-marketplace/pull/11100) | Changes prepared | 369 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-11100) |
| [#10894: Add the explicit manifestPath for oma.nearby](https://github.com/omacom/omarchy-plugin-marketplace/pull/10894) | Changes prepared | 367 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-10894) |
| [#10114: Use a 1200×630 card for Open Graph previews](https://github.com/omacom/omarchy-plugin-marketplace/pull/10114) | Validated existing change | 368 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-10114) |
| [#8905: Clarify DB Studio manual installation](https://github.com/omacom/omarchy-plugin-marketplace/pull/8905) | Changes prepared | 369 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-8905) |
| [#6513: Treat a bare "pip install" as a mention, not as package management](https://github.com/omacom/omarchy-plugin-marketplace/pull/6513) | Changes prepared | 320 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-6513) |
| [#6403: Append shell restart to install command for clonedFrom plugins](https://github.com/omacom/omarchy-plugin-marketplace/pull/6403) | Changes prepared | 322 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-6403) |
| [#5697: Clarify required OmaCalendar app installation](https://github.com/omacom/omarchy-plugin-marketplace/pull/5697) | Changes prepared | 367 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-5697) |
| [#3062: Add type-to-jump page input in pagination](https://github.com/omacom/omarchy-plugin-marketplace/pull/3062) | Changes prepared | 223 | [View](https://github.com/BraveHart911/omarchy-plugin-marketplace/tree/codex/fix-pr-3062) |

## Work completed

- **#13549:** Existing event-time fix passed. Maintainer must merge and remove/reapply the approval label on #13539.
- **#13547:** Add a Chromium rendering regression for contain/cover and unchanged card frames. Test detects removal of the class or CSS rule.
- **#13496:** Recreate the Loadlet correction on current main and regenerate only its listing at the existing observed commit. Maintainer installation decision remains required.
- **#13359:** Carry forward the parent sort fix, reposition help on scroll, document time-based sorts, and refresh coupled cache keys.
- **#13351:** Author already fixed sort-chip replacement in 80d23e60d. Full suite and real browser sort sequence passed.
- **#13167:** No further source change needed. Submission/parser/documentation consistency passed. Retagging existing plugins is a separate maintainer choice.
- **#13074:** Isolate Git exports from local attributes; reject reserved paths before entry-type checks; add real Git regressions.
- **#12653:** Recreate the Restic correction on current main and regenerate only its listing, preserving newer-upstream and verification state.
- **#12164:** No further source change needed. Delayed catalog, 503 failure cleanup, reduced-motion behavior, and responsive layout passed.
- **#11858:** Recreate the Omagram manual override on current main, preserving current version and upstream observation rather than reverting to the approved older snapshot.
- **#11100:** Rebase logo presentation onto current main, fix the stale cache assertion, regenerate bounded output, and verify native image loading and initials fallback.
- **#10894:** Recreate the root manifest-path correction on current main. Preserve manual setup; enabling standard installation remains a separate authorized decision.
- **#10114:** No further source change needed. The committed image dimensions and metadata passed tests. Public hosting of the new asset remains a post-merge check.
- **#8905:** Rebase the installation-note/link change onto current main, preserve author links, reconcile asset versions, and regenerate bounded output.
- **#6513:** Retain the prose false-positive fix while detecting quoted, variable, home-directory, and continued pip operands.
- **#6403:** Retain service-replacement metadata under manual overrides so later approval still includes a restart; add promotion coverage and bump source validation version.
- **#5697:** Recreate the OmaCalendar setup correction on current main, preserving current snapshot observations and verification state.
- **#3062:** Repair cache consistency; add Enter submission, strict integer validation, and width for larger page numbers; preserve bounds and focus behavior.

## Verification

- Reproducible npm installation and full tests for every branch; relevant staged/uncommitted whitespace checks passed.
- Chromium checks for eight frontend branches across 320, 375, 760, 761, 800, 850, 879, 880, 1024, and 1440 CSS pixels, in light and dark themes: 160 horizontal-overflow measurements passed.
- Browser interactions covered recommitting sort terms, help placement while scrolling, Escape, page-number Enter/blur and invalid input, catalog loading/error cleanup, reduced motion, and logo load/failure fallback.
- The five rebased registry corrections preserve displayed versions, observed upstream commits, verification states, and all unrelated plugin records. Existing builder discovery/projection functions generated their outputs; Explorer output was regenerated with complete Git history.
- No plugin code was executed and no native plugin was installed. Fresh installation, real clipboard behavior, production deployment, and social crawler refresh are not claimed.

## Maintainer handoff

1. Review the prepared branches. The authenticated account has no write access to the upstream repository or contributors’ branches. A prepared branch does not update or resolve the original PR discussion.
2. Apply follow-up commits to the respective contributor branches. For corrections based on current main, use the refreshed proposal rather than restoring stale generated JSON from the older PR.
3. Process #13351 before #13359. When combining frontend proposals, reconcile coupled cache keys and rerun the combined tests/browser checks.
4. Review installation-policy decisions without altering snapshot attestations. After merging #13549, an authorized maintainer must remove and reapply the approval label on #13539; retrying the old run uses the old workflow.
5. Authorize pending hosted checks, merge accepted changes, and confirm deployed cards, commands, notes, logos, and social metadata. These actions require repository maintainers and remain outstanding.

## Exact prepared commits

| PR | Base | Prepared commit |
| --- | --- | --- |
| #13549 | `7e0b241c184dbeb1b140f2bb265ba01f26f13ca2` | `7e0b241c184dbeb1b140f2bb265ba01f26f13ca2` |
| #13547 | `cd53ffdd7ba535ae244f60484c3085bc0cc30c42` | `2a528977af15d590e43eab64ad237187926a8333` |
| #13496 | `9455d96579b47f88850cf0addeebb58799cb5022` | `79cf664ece8fcd0b7d3c46c553765074381457ce` |
| #13359 | `43b9244a1de13466c08c9a8dfe59b12f76075db3` | `77449db13534560d410c2cb9369ac34537fb4dca` |
| #13351 | `80d23e60d6093985f79f4eb68abdb5ae94fb57f6` | `80d23e60d6093985f79f4eb68abdb5ae94fb57f6` |
| #13167 | `6300a27d51cc0936961734e51c75b8d5dfc72057` | `6300a27d51cc0936961734e51c75b8d5dfc72057` |
| #13074 | `4eb9f27bcb92d0632255fe4b9ae7773e92872e81` | `4e10ca2f9b3879c96f486cd4f0b5e0330de8dd5a` |
| #12653 | `9455d96579b47f88850cf0addeebb58799cb5022` | `87b5d601cdc1b58552e13e2f0b3b3f358bf20777` |
| #12164 | `fdd698c9550ede8b9783eb66a83484a74f475efc` | `fdd698c9550ede8b9783eb66a83484a74f475efc` |
| #11858 | `9455d96579b47f88850cf0addeebb58799cb5022` | `2b0a431d2534dc401fcff7b1cf09b2adbe66b91a` |
| #11100 | `9455d96579b47f88850cf0addeebb58799cb5022` | `7c85e6917baf146779c802eeafbd63967e3400c4` |
| #10894 | `9455d96579b47f88850cf0addeebb58799cb5022` | `183779ff8769bc7c2585716c01933c9e879191b3` |
| #10114 | `499b05f58651efbe8982ca95e555ccecbdc9f156` | `499b05f58651efbe8982ca95e555ccecbdc9f156` |
| #8905 | `9455d96579b47f88850cf0addeebb58799cb5022` | `796a94620a0bac1d8546458ed7e122aa755319dc` |
| #6513 | `8cf3b90611471aa72ae1874abe3409314b4f51b0` | `d2123fc71e52c317623ec1e5c26c5e285801c1f1` |
| #6403 | `c0426c4b4575fe41770b2341e9f7fdaebc418917` | `a4b7a7535db61c2ac3cf9523426885aef1128f88` |
| #5697 | `9455d96579b47f88850cf0addeebb58799cb5022` | `47915b3da69dc2fc5da3af26a0905c4ac1483046` |
| #3062 | `7ca9926f406224255b152b6f2daf100e83874b7b` | `48c0197286f8b98cb4265b1ba77c1f976e6960bb` |
