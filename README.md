# Games privacy policy

One public privacy policy shared by all of Hashaam Shahid Yousafzai's mobile games
(Sort Squad, Arrow Out, Cannon Smash, and any later ones), served through GitHub Pages.

`index.html` is the page itself. It is self contained: no scripts, no fonts, no
external requests of any kind.

## Publishing

1. Pushed to <https://github.com/rhpshanks/privacyPolicy>. Keep it public.
2. Settings, then Pages, then set Source to `Deploy from a branch`, branch `main`,
   folder `/ (root)`.
3. The policy appears at `https://rhpshanks.github.io/privacyPolicy/`.

That one URL goes in every game: the store listing, and the game's privacy link
(`GameConfig.PrivacyPolicyUrl` in each Unity project).

## Keeping it true

The policy splits the games into two groups, listed in the table under "Who this policy
covers":

- **Without ads** (Sort Squad, Arrow Out): collect nothing, use no network, show no ads.
- **With ads** (Cannon Smash): Google AdMob, with Google's consent form (UMP) and an
  in-game Privacy Options button. The "Advertising" section describes what the Google
  Mobile Ads SDK collects.

It stays accurate only while every game is in the right row. Before shipping a game, or
an update that adds ads, analytics, purchases or any networking, add it to the table and
the relevant section first. Also change the effective date and the "Last change" line.
A game listed for children under Google Play's Families policy must request child-directed
ads, and the "Children's privacy" section must say so.
