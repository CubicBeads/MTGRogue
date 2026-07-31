# MTGRogue

**Release: v1.0**

MTGRogue is a free, unofficial fan-made roguelite campaign framework for **Magic: The Gathering**. A player develops a persistent card pool across repeated runs, builds a deck around a changing Command Zone, and faces a sequence of increasingly powerful decks from across Magic's history.

The software does not play Magic for you. It manages the campaign structure, progression, rewards, events, shops, card pools, random draws, and optional deckbuilding assistance. The games themselves are played normally with physical cards or on the platform of your choice.

## Package contents

Keep the files together in one folder. The complete public package is intended to contain:

- `MTGRogue_Quick_Start_v1.0.pdf` — the shortest path to starting a campaign.
- `MTGRogue_GM_Guide_v1.0.pdf` — preparation, rulings, and guidance for the Game Master.
- `MTGRogue_Reference_and_Appendices_v1.0.pdf` — detailed rules and reference material.
- `MTGRogue_Campaign_Start_Assistant_v1.0.html` — creates the player's initial permanent card pool.
- `MTGRogue_Run_Assistant_v1.0.html` — manages the campaign and each run.
- `MTGRogue_Deck_Draw_Assistant_v1.0.html` — draws the opponent deck for each encounter and supports the Hunter reward.

## What you need

- A recent version of Firefox, Chrome, or Edge on a desktop computer.
- An internet connection for card searches, card images, and online deckbuilding data.
- A way to play Magic and maintain decklists, such as paper cards, proxies where appropriate, or a digital platform.
- One player and one Game Master. The GM prepares and pilots the opposing decks and resolves the few effects that are intentionally manual.

No installation is required. Download the files and open each HTML assistant directly in your browser.

## Starting a campaign

1. Read `MTGRogue_Quick_Start_v1.0.pdf`.
2. Open `MTGRogue_Campaign_Start_Assistant_v1.0.html` and generate the initial card pool.
3. Copy the generated card list into `MTGRogue_Run_Assistant_v1.0.html` when starting a new campaign.
4. At the beginning of a run, select the Command Zone and deckbuilding style.
5. Use `MTGRogue_Deck_Draw_Assistant_v1.0.html` whenever the run assistant tells you which encounter category to draw.
6. Play the match, record the result in the run assistant, and continue through rewards, events, and shops.

The assistants open in English by default. French can be selected from their language settings.

## Saving your progress

The HTML assistants save their data in the browser's local storage. A save belongs to the browser profile and device on which it was created.

Use the **Export JSON** option regularly, especially before:

- opening a new version of an assistant;
- clearing browser or site data;
- changing browser, browser profile, or computer;
- making a large manual correction to the campaign.

Keep the exported JSON until you have imported it and checked the card pool, currencies, skills, current encounter, and active run state.

## Online services and privacy

The supplied v1.0 HTML files do not require an MTGRogue account or an MTGRogue server. Campaign and decklist data are stored locally in your browser.

Some features contact third-party services directly from the browser:

- [Scryfall](https://scryfall.com) for card data, legality, searches, and images;
- [EDHREC](https://edhrec.com) for Instant Deckbuilding recommendations;
- [Commander Spellbook](https://commanderspellbook.com) for compatible combo information.

Those features depend on the availability, data, rate limits, and privacy policies of the relevant services. A temporary service failure should not erase locally saved campaign data, but it may prevent a card draw or deckbuilding operation until the service is available again.

## Instant Deckbuilding

Instant Deckbuilding is designed to accelerate construction, not to replace player judgment. Review the generated list before playing, particularly its mana base, curve, interaction, and any combo package.

- **Mixed mode** combines owned cards with temporary EDHREC suggestions according to the campaign rules.
- **Card Pool Only mode** ranks and uses owned cards without adding nonbasic cards that are absent from the permanent or run card pools.
- Basic lands remain freely available.

After editing a generated list, update the copy maintained in your deckbuilding tool.

## Troubleshooting

**The assistant opens with an error or a blank screen**  
Download the file again, open it in a current desktop browser, and make sure it was saved as an `.html` file rather than opened from a preview page.

**A card draw takes a long time or fails**  
Wait a moment and retry once. Repeated rapid retries can make a temporary third-party rate limit last longer.

**Card images do not appear**  
Check the internet connection and try opening Scryfall in the same browser.

**My campaign is missing**  
Confirm that you are using the same browser, device, and browser profile. Otherwise, import the most recent JSON backup.

**A French card image is unavailable**  
Not every printing has a French image on Scryfall. Depending on the selected French mode, the assistant may use another French printing or keep the English image.

## Reporting a bug

When reporting a problem in the release thread, include:

- the assistant filename;
- browser name and version;
- selected interface language;
- the screen and action that triggered the problem;
- exact steps that reproduce it;
- a screenshot or the displayed error message.

An exported save can be very helpful for state-specific bugs, but only share it when you are comfortable doing so and keep your own untouched backup.

## Sharing MTGRogue

MTGRogue must remain freely accessible. When sharing the files or a modified version, preserve the About section, credits, and legal notice, and make it clear when changes are not part of the original v1.0 release.

## Credits and legal notice

MTGRogue uses data and services provided by Scryfall, EDHREC, and Commander Spellbook. These services are not responsible for MTGRogue.

MTGRogue is unofficial Fan Content permitted under the [Wizards of the Coast Fan Content Policy](https://company.wizards.com/en/legal/fancontentpolicy). It is not approved or endorsed by Wizards. Some materials belong to Wizards of the Coast. © Wizards of the Coast LLC.

Magic: The Gathering and related properties belong to Wizards of the Coast.
