# COPPERLAND NEWSWIRE FEED

<!-- ============================================================================
  COPPERLAND COMMAND DASHBOARD // NEWSWIRE SOURCE FILE

  This file feeds the newswire ticker of the Copperland Command Dashboard.
  Edit, add or remove bulletins below — the dashboard reloads this file on
  every page load. If the file cannot be reached or contains no valid
  bulletins, the dashboard falls back to its built-in messages.

  FORMAT:
    ## category            <- section header, ONE word, lowercase or uppercase
    - [TAG | tone] Text    <- one bulletin per line, always starts with "- "

  CATEGORIES (use exactly these names):
    market       <- trade lanes, commodity prices, freight
    regional     <- Coronado / Independent Worlds news
    security     <- patrols, inspections, threats
    operations   <- Copperland docks, refinery, engineering
    corporate    <- Deep Space Engineering corporate bulletins

  TONES (controls the color of the bulletin):
    lore    <- neutral copper/amber (default, use for most)
    good    <- green, positive news
    warn    <- amber/yellow, caution
    danger  <- red, alerts and emergencies
    remote  <- teal, external/far-away sources
    muted   <- dim grey, low-priority filler

  RULES:
    - TAG max ~40 characters, shown in brackets before the text
    - Text is automatically displayed in UPPERCASE
    - Tone must be a single word from the list above (no underscores);
      lines with an invalid format are skipped silently
    - Empty categories are fine, they are simply ignored
    - Lines starting with # or <!-- are comments and ignored
============================================================================= -->

## market
- [DSE MARKET WATCH | lore] Copper futures firm as Coronado refinery throughput holds steady.
- [CORONADO EXCHANGE | lore] Refined metals open strong on sustained component demand.
- [DSE COMMODITIES | lore] Copper premiums hold above the weekly average ahead of the next freight window.
- [INDEPENDENT TRADE | lore] Bulk freight bookings rise across the Coronado industrial lanes.

## regional
- [CORONADO DESK | lore] Ore traffic through the Independent Worlds continues to climb.
- [FREEPORT WIRE | remote] Independent haulers report steady contract flow out of Coronado.

## security
- [DSE SECURITY BRIEF | warn] Randomized cargo inspections continue at local trade lanes.
- [LANE PATROL REPORT | lore] Escort wing begins a routine perimeter sweep.
- [DSE SECURITY BRIEF | warn] All non essentials personel got to move to civilian quarters.
- [DSE SECURITY BRIEF | red] All civilians in the shipyard are to be arrested. Use of lethal force is advised.
- [DSE SECURITY BRIEF | warn] Private military contractors have been stationed on Copperland to ensure operational security.

## operations
- [COPPERLAND DOCKS | lore] Pier two opens for the next bulk freight window.
- [COPPERLAND ENGINEERING | good] Refinery line one cleared for scheduled coolant service.

## corporate
- [DSE CORPORATE | lore] Refining output forecast revised upward for the current quarter.
- [DSE LOYALTY | lore] Forged by Deep Space Engineering.
