# itch compatibility watchlist

This repository is a public issue tracker that centralizes
problems encountered when running games through the [itch app][itch]

These problems may be caused by:

  * A bug in [itch][]
  * A bug in the game itself
  * A lacking [app manifest][] preventing the game from being launched correctly
  * A privilege required by a game but 

Resolving these is best-effort, and as the userbase continues to
expand, it's fully understood that the number of issues will grow.

The strategy for dealing with this repo is:

  * Identify similar reports
  * Open a corresponding issue in the [itch issue tracker][]
    * (This would generally be done by an itch app developer or QA tester)
  * Collect research on said issue tracker
  * Either
    * Implement, test, and ship a fix for [itch][], or
    * Get in touch with the game's developer and help them fix it, or
    * Exceptionally, fix it for them (if working closely with them already / just a checkbox away).
  * Close all related reports

Separating those two repositories is done because we want to keep
receiving reports of broken games and take care of it, whilst keeping
the traffic in the main issue tracker reasonable.

[itch]: https://github.com/itchio/itch
[itch issue tracker]: https://github.com/itchio/itch/issues
[itch.io sandbox]: https://itch.io/docs/itch/using/sandbox.html
[app manifest]: https://itch.io/docs/itch/integrating/manifest.html
