# Trakt Source Mapping Draft

Updated: 2026-02-23T10:41:40

## Locked Rules
- Livetv is intentionally skipped.
- Magllentv is normalized to MagellanTV.
- Decades, Awards, and Directors are movies-only tables.
- Decades use snoak for 1960s+; 1930s/1940s/1950s use ravynloony as provided.
- Kids uses split mapping: movies from snoak, shows from tvgeniekodi.
- If movie and show use the same URL/source, it is shown once and `Total Lists` is `1`.
- Genres are split into two sections: non-dannyrutledge and dannyrutledge, with overlap shown in both.

## Streaming (23)

| Term | Movies | Movies Source | Shows | Shows Source | Total Lists | Status | Notes |
|---|---|---|---|---|---|---|---|
| Angel | — | — | — | — | 0 | skip | No source mapping yet. |
| Apple TV+ | https://trakt.tv/users/snoak/lists/top-apple-tv-movies | snoak | https://trakt.tv/users/snoak/lists/top-apple-tv-shows | snoak | 2 | mapped | — |
| BBC | — | — | — | — | 0 | skip | No source mapping yet. |
| Bet | https://trakt.tv/users/tvgeniekodi/lists/bet-movies | tvgeniekodi | https://trakt.tv/users/tvgeniekodi/lists/bet-shows | tvgeniekodi | 2 | mapped | — |
| Crunchyroll | https://trakt.tv/users/frostypolicia/lists/crunchyroll-movies | search (frostypolicia) | https://trakt.tv/users/frostypolicia/lists/crunchyroll-shows | search (frostypolicia) | 2 | mapped | — |
| Curiositystream | https://trakt.tv/users/mgperdices/lists/curiosity-stream | search (mgperdices) | — | — | 1 | mapped | — |
| Discovery+ | https://trakt.tv/users/moviemankev79/lists/discovery | search (moviemankev79) | — | — | 1 | mapped | — |
| Disney | https://trakt.tv/users/snoak/lists/top-disney-movies | snoak | https://trakt.tv/users/snoak/lists/top-disney-shows | snoak | 2 | mapped | — |
| HBO Max | https://trakt.tv/users/snoak/lists/top-hbo-max-movies | snoak | https://trakt.tv/users/snoak/lists/top-hbo-max-shows | snoak | 2 | mapped | — |
| Hidive | — | — | — | — | 0 | skip | No source mapping yet. |
| Hulu | https://trakt.tv/users/snoak/lists/top-hulu-movies | snoak | https://trakt.tv/users/snoak/lists/top-hulu-shows | snoak | 2 | mapped | — |
| KDrama+ | https://app.trakt.tv/users/snoak/lists/popular-kdrama-movies?mode=media | snoak | https://app.trakt.tv/users/snoak/lists/popular-kdrama-shows?mode=media | snoak | 2 | mapped | — |
| Livetv | — | — | — | — | 0 | skip | Skipped by request. |
| MagellanTV | https://trakt.tv/users/steffe73/lists/magellantv-list-by-steffe73 | search (steffe73) | — | — | 1 | mapped | Name normalized from magllentv asset slug to MagellanTV. |
| Max | https://trakt.tv/users/tvgeniekodi/lists/max-movies | tvgeniekodi | https://trakt.tv/users/tvgeniekodi/lists/max-shows | tvgeniekodi | 2 | mapped | — |
| Netflix | https://trakt.tv/users/snoak/lists/top-netflix-movies | snoak | https://trakt.tv/users/snoak/lists/top-netflix-shows | snoak | 2 | mapped | — |
| Paramount | https://trakt.tv/users/snoak/lists/top-paramount-movies | snoak | https://trakt.tv/users/snoak/lists/top-paramount-shows | snoak | 2 | mapped | — |
| Peacock | https://trakt.tv/users/tvgeniekodi/lists/peacock-movies | tvgeniekodi | https://trakt.tv/users/tvgeniekodi/lists/peacock-shows | tvgeniekodi | 2 | mapped | — |
| Plex | — | — | — | — | 0 | skip | No source mapping yet. |
| Prime Video | https://trakt.tv/users/snoak/lists/top-amazon-prime-movies | snoak | https://trakt.tv/users/snoak/lists/top-amazon-prime-shows | snoak | 2 | mapped | — |
| Shudder | https://app.trakt.tv/users/snoak/lists/latest-shudder-movies?mode=media | snoak | — | — | 1 | mapped | — |
| SkyShowtime | https://trakt.tv/users/certefied/lists/skyshowtime | search (certefied) | — | — | 1 | mapped | — |
| Videoland | https://trakt.tv/users/certefied/lists/videoland | search (certefied) | — | — | 1 | mapped | — |

## Decades (10)

| Term | Movies | Movies Source | Total Lists | Status | Notes |
|---|---|---|---|---|---|
| 1930S | https://trakt.tv/users/ravynloony/lists/1930-films | search (ravynloony) | 1 | mapped | Movies only. |
| 1940S | https://trakt.tv/users/ravynloony/lists/1940-films | search (ravynloony) | 1 | mapped | Movies only. |
| 1950S | https://trakt.tv/users/ravynloony/lists/1950-films | search (ravynloony) | 1 | mapped | Movies only. |
| 1960S | https://trakt.tv/users/snoak/lists/popular-1960s-movies | snoak | 1 | mapped | Movies only. |
| 1970S | https://trakt.tv/users/snoak/lists/popular-1970s-movies | snoak | 1 | mapped | Movies only. |
| 1980S | https://trakt.tv/users/snoak/lists/popular-1980s-movies | snoak | 1 | mapped | Movies only. |
| 1990S | https://trakt.tv/users/snoak/lists/popular-1990s-movies | snoak | 1 | mapped | Movies only. |
| 2000S | https://trakt.tv/users/snoak/lists/popular-2000s-movies | snoak | 1 | mapped | Movies only. |
| 2010S | https://trakt.tv/users/snoak/lists/popular-2010s-movies | snoak | 1 | mapped | Movies only. |
| 2020S | https://trakt.tv/users/snoak/lists/popular-2020s-movies | snoak | 1 | mapped | Movies only. |

## Awards (6)

| Term | Movies | Movies Source | Total Lists | Status | Notes |
|---|---|---|---|---|---|
| The British Academy Film Awards | https://trakt.tv/users/foux72/lists/bafta-best-film-award-winners | search (foux72) | 1 | mapped | — |
| Film Independent Spirit Awards | https://trakt.tv/users/victorchagas/lists/film-independent-spirit-awards-best-feature | search (victorchagas) | 1 | mapped | — |
| The Golden Globes | https://trakt.tv/users/danielle0412/lists/rotten-tomatoes-golden-globes-best-picture-winners-by-tomatometer-copy | search (danielle0412) | 1 | mapped | — |
| The Cannes Film Festival | https://trakt.tv/users/pierredurrr/lists/festival-de-cannes-palme-d-or-winners | search (pierredurrr) | 1 | mapped | — |
| The Academy Awards (Oscars) | https://trakt.tv/users/jackrabbitslim/lists/the-oscars-best-picture-nominees | search (jackrabbitslim) | 1 | mapped | — |
| The Venice Film Festival | https://trakt.tv/users/zorge88/lists/venice-film-festival | search (zorge88) | 1 | mapped | — |

## Directors (10)

| Term | Movies | Movies Source | Total Lists | Status | Notes |
|---|---|---|---|---|---|
| Anderson | https://trakt.tv/users/mawsa/lists/paul-thomas-anderson | search (mawsa) | 1 | mapped | — |
| Carpenter | https://trakt.tv/users/mawsa/lists/john-carpenter | search (mawsa) | 1 | mapped | — |
| Depalma | https://trakt.tv/users/mawsa/lists/brian-de-palma | search (mawsa) | 1 | mapped | — |
| Fincher | https://trakt.tv/users/mawsa/lists/david-fincher | search (mawsa) | 1 | mapped | — |
| Hitchcock | https://trakt.tv/users/mawsa/lists/alfred-hitchcock | search (mawsa) | 1 | mapped | — |
| Kubrick | https://trakt.tv/users/mawsa/lists/stanley-kubrick | search (mawsa) | 1 | mapped | — |
| Nolan | https://trakt.tv/users/mawsa/lists/christopher-nolan | search (mawsa) | 1 | mapped | — |
| Scorsese | https://trakt.tv/users/mawsa/lists/martin-scorsese | search (mawsa) | 1 | mapped | — |
| Spielberg | https://trakt.tv/users/mawsa/lists/steven-spielberg | search (mawsa) | 1 | mapped | — |
| Villeneuve | https://trakt.tv/users/mawsa/lists/denis-villeneuve | search (mawsa) | 1 | mapped | — |

## Genres - Non dannyrutledge (29)

| Term | Movies | Movies Source | Shows | Shows Source | Total Lists | Status | Notes |
|---|---|---|---|---|---|---|---|
| Animation2 | https://trakt.tv/users/snoak/lists/popular-animated-movies | snoak | https://trakt.tv/users/snoak/lists/popular-animated-shows | snoak | 2 | mapped | — |
| Family | https://trakt.tv/users/rizreflects/lists/family-movies | search (rizreflects) | — | — | 1 | mapped | — |
| History | https://trakt.tv/users/garycrawfordgc/lists/history | garycrawfordgc | — | — | 1 | mapped | — |
| Imdb | https://trakt.tv/users/snoak/lists/top-250-movies-imdb | snoak | https://trakt.tv/users/snoak/lists/top-250-shows-imdb | snoak | 2 | mapped | — |
| Imdb2 | https://trakt.tv/users/snoak/lists/top-250-movies-imdb | snoak | https://trakt.tv/users/snoak/lists/top-250-shows-imdb | snoak | 2 | mapped | — |
| Imdb3 | https://trakt.tv/users/snoak/lists/top-250-movies-imdb | snoak | https://trakt.tv/users/snoak/lists/top-250-shows-imdb | snoak | 2 | mapped | — |
| Korean | https://trakt.tv/users/snoak/lists/popular-kdrama-movies | snoak | https://trakt.tv/users/snoak/lists/popular-kdrama-shows | snoak | 2 | mapped | — |
| Korean2 | https://trakt.tv/users/snoak/lists/popular-kdrama-movies | snoak | https://trakt.tv/users/snoak/lists/popular-kdrama-shows | snoak | 2 | mapped | — |
| Miniseries | https://trakt.tv/users/snoak/lists/popular-miniseries | snoak | — | — | 1 | mapped | — |
| Miniseries2 | https://trakt.tv/users/snoak/lists/popular-miniseries | snoak | — | — | 1 | mapped | — |
| Miniseries3 | https://trakt.tv/users/snoak/lists/popular-miniseries | snoak | — | — | 1 | mapped | — |
| Narrative | https://trakt.tv/users/snoak/lists/top-250-narrative-feature-films-letterboxd-official | snoak | — | — | 1 | partial | — |
| Narrative2 | https://trakt.tv/users/snoak/lists/top-250-narrative-feature-films-letterboxd-official | snoak | — | — | 1 | partial | — |
| Scifi | https://trakt.tv/users/snoak/lists/popular-sci-fi-movies | snoak | https://trakt.tv/users/snoak/lists/popular-sci-fi-shows | snoak | 2 | mapped | — |
| Action | https://trakt.tv/users/snoak/lists/popular-action-movies | snoak | https://trakt.tv/users/snoak/lists/popular-action-shows | snoak | 2 | mapped | — |
| Adventure | https://trakt.tv/users/rizreflects/lists/adventures | search (rizreflects) | — | — | 1 | mapped | — |
| Animation | https://trakt.tv/users/snoak/lists/popular-animated-movies | snoak | https://trakt.tv/users/snoak/lists/popular-animated-shows | snoak | 2 | mapped | — |
| Anime | https://trakt.tv/users/snoak/lists/popular-animation-anime-movies | snoak | https://trakt.tv/users/snoak/lists/popular-animation-anime-shows | snoak | 2 | mapped | — |
| Comedy | https://trakt.tv/users/snoak/lists/popular-comedy-movies | snoak | https://trakt.tv/users/snoak/lists/popular-comedy-shows | snoak | 2 | mapped | — |
| Crime | https://trakt.tv/users/garycrawfordgc/lists/crime | garycrawfordgc | https://trakt.tv/users/garycrawfordgc/lists/crime-shows | garycrawfordgc | 2 | mapped | — |
| Documentary | https://trakt.tv/users/snoak/lists/popular-documentary-movies | snoak | https://trakt.tv/users/snoak/lists/popular-documentary-shows | snoak | 2 | mapped | — |
| Drama | https://trakt.tv/users/snoak/lists/popular-drama-movies | snoak | https://trakt.tv/users/snoak/lists/popular-drama-shows | snoak | 2 | mapped | — |
| Fantasy | https://trakt.tv/users/rizreflects/lists/fantasy-movies | search (rizreflects) | — | — | 1 | mapped | — |
| Horror | https://trakt.tv/users/snoak/lists/popular-horror-movies | snoak | https://trakt.tv/users/snoak/lists/popular-horror-shows | snoak | 2 | mapped | — |
| Kids | https://trakt.tv/users/snoak/lists/trending-kids-movies | snoak | https://trakt.tv/users/tvgeniekodi/lists/trending-kids-shows | tvgeniekodi | 2 | mapped | Explicit split mapping from user instruction. |
| Nature | — | — | https://trakt.tv/users/tvgeniekodi/lists/top-nature-shows | tvgeniekodi | 1 | partial | — |
| Reality | — | — | https://trakt.tv/users/snoak/lists/popular-reality-shows | snoak | 1 | partial | — |
| Romance | https://trakt.tv/users/snoak/lists/popular-romance-movies | snoak | https://trakt.tv/users/snoak/lists/popular-romance-shows | snoak | 2 | mapped | — |
| Thriller | https://trakt.tv/users/snoak/lists/popular-thriller-movies | snoak | https://trakt.tv/users/snoak/lists/popular-thriller-shows | snoak | 2 | mapped | — |

## Genres - dannyrutledge (56)

| Term | Movies | Movies Source | Shows | Shows Source | Total Lists | Status | Notes |
|---|---|---|---|---|---|---|---|
| Action | https://trakt.tv/users/snoak/lists/popular-action-movies | snoak | https://trakt.tv/users/snoak/lists/popular-action-shows | snoak | 2 | mapped | — |
| Action Adventures | https://trakt.tv/users/rizreflects/lists/action-adventures | search (rizreflects) | — | — | 1 | mapped | — |
| Action Thrillers | https://trakt.tv/users/rizreflects/lists/action-thrillers | search (rizreflects) | — | — | 1 | mapped | — |
| Adult Animation | — | — | https://trakt.tv/users/rizreflects/lists/adult-animation | search (rizreflects) | 1 | mapped | — |
| Adventure | https://trakt.tv/users/rizreflects/lists/adventures | search (rizreflects) | — | — | 1 | mapped | — |
| Aliens | https://trakt.tv/users/rizreflects/lists/aliens-monsters | search (rizreflects) | — | — | 1 | mapped | — |
| Animated Comedies | https://trakt.tv/users/snoak/lists/popular-animated-movies | snoak | https://trakt.tv/users/snoak/lists/popular-animated-shows | snoak | 2 | mapped | — |
| Animation | https://trakt.tv/users/snoak/lists/popular-animated-movies | snoak | https://trakt.tv/users/snoak/lists/popular-animated-shows | snoak | 2 | mapped | — |
| Anime | https://trakt.tv/users/snoak/lists/popular-animation-anime-movies | snoak | https://trakt.tv/users/snoak/lists/popular-animation-anime-shows | snoak | 2 | mapped | — |
| Arthouse Animation | https://trakt.tv/users/rizreflects/lists/stop-motion-animation | search (rizreflects) | — | — | 1 | mapped | — |
| Classics | https://trakt.tv/users/rizreflects/lists/cult-classics | search (rizreflects) | — | — | 1 | mapped | — |
| Comedy | https://trakt.tv/users/snoak/lists/popular-comedy-movies | snoak | https://trakt.tv/users/snoak/lists/popular-comedy-shows | snoak | 2 | mapped | — |
| Creature Features | https://trakt.tv/users/rizreflects/lists/occult-horrors | search (rizreflects) | — | — | 1 | mapped | — |
| Crime | https://trakt.tv/users/garycrawfordgc/lists/crime | garycrawfordgc | https://trakt.tv/users/garycrawfordgc/lists/crime-shows | garycrawfordgc | 2 | mapped | — |
| Dark Fantasy | https://trakt.tv/users/rizreflects/lists/dark-fantasy-movies | search (rizreflects) | — | — | 1 | mapped | — |
| Disaster Epics | https://trakt.tv/users/rizreflects/lists/disaster-movies | search (rizreflects) | — | — | 1 | mapped | — |
| Documentary | https://trakt.tv/users/snoak/lists/popular-documentary-movies | snoak | https://trakt.tv/users/snoak/lists/popular-documentary-shows | snoak | 2 | mapped | — |
| Drama | https://trakt.tv/users/snoak/lists/popular-drama-movies | snoak | https://trakt.tv/users/snoak/lists/popular-drama-shows | snoak | 2 | mapped | — |
| Dystopian Futures | https://trakt.tv/users/rizreflects/lists/dystopian-future | search (rizreflects) | — | — | 1 | mapped | — |
| Family Movie Night | https://trakt.tv/users/rizreflects/lists/family-movies | search (rizreflects) | — | — | 1 | mapped | — |
| Fantasy | https://trakt.tv/users/rizreflects/lists/fantasy-movies | search (rizreflects) | — | — | 1 | mapped | — |
| Fantasy Adventures | https://trakt.tv/users/rizreflects/lists/action-fantasy | search (rizreflects) | — | — | 1 | mapped | — |
| Favorite Cartoons | https://trakt.tv/users/rizreflects/lists/hand-drawn-animation | search (rizreflects) | — | — | 1 | mapped | — |
| Frontier Grit | https://trakt.tv/users/madmapper/lists/neo-western | search (madmapper) | — | — | 1 | partial | — |
| High Seas Heroics | https://trakt.tv/users/rizreflects/lists/sea-adventures | search (rizreflects) | — | — | 1 | mapped | — |
| Historical Blockbusters | https://trakt.tv/users/sp1ti/lists/directory-of-world-cinema-american-hollywood | search (sp1ti) | — | — | 1 | partial | — |
| Horror | https://trakt.tv/users/snoak/lists/popular-horror-movies | snoak | https://trakt.tv/users/snoak/lists/popular-horror-shows | snoak | 2 | mapped | — |
| Independent | https://trakt.tv/users/pastican/lists/indie-movies | search (pastican) | — | — | 1 | partial | — |
| International | https://trakt.tv/users/rizreflects/lists/critically-acclaimed-foreign-movies | search (rizreflects) | — | — | 1 | mapped | — |
| Kids | https://trakt.tv/users/snoak/lists/trending-kids-movies | snoak | https://trakt.tv/users/tvgeniekodi/lists/trending-kids-shows | tvgeniekodi | 2 | mapped | Explicit split mapping from user instruction. |
| Learning Corner | https://trakt.tv/users/enverkolsuzoglu/lists/history-politics | search (enverkolsuzoglu) | — | — | 1 | partial | — |
| Lovable Monsters | https://trakt.tv/users/rizreflects/lists/animal-tales | search (rizreflects) | — | — | 1 | mapped | — |
| Music | https://trakt.tv/users/kirky62/lists/music | search (kirky62) | — | — | 1 | partial | — |
| Music Movies | https://trakt.tv/users/jiobiee/lists/music-movies | search (jiobiee) | — | — | 1 | partial | — |
| Myths And Legends | https://trakt.tv/users/kristaeglover/lists/myths-and-legends | search (kristaeglover) | — | — | 1 | partial | — |
| Nature | — | — | https://trakt.tv/users/tvgeniekodi/lists/top-nature-shows | tvgeniekodi | 1 | partial | — |
| Psychological Terror | https://trakt.tv/users/rizreflects/lists/psychological-thrillers | search (rizreflects) | — | — | 1 | mapped | — |
| Reality | — | — | https://trakt.tv/users/snoak/lists/popular-reality-shows | snoak | 1 | partial | — |
| Robots And Ai | https://trakt.tv/users/rizreflects/lists/artificial-intelligence | search (rizreflects) | — | — | 1 | mapped | — |
| Romance | https://trakt.tv/users/snoak/lists/popular-romance-movies | snoak | https://trakt.tv/users/snoak/lists/popular-romance-shows | snoak | 2 | mapped | — |
| Sci Fi | https://trakt.tv/users/snoak/lists/popular-sci-fi-movies | snoak | https://trakt.tv/users/snoak/lists/popular-sci-fi-shows | snoak | 2 | mapped | — |
| Short Films | https://trakt.tv/users/justfrank/lists/short-films | search (justfrank) | — | — | 1 | partial | — |
| Space Epics | https://trakt.tv/users/rizreflects/lists/astronomy-space | search (rizreflects) | — | — | 1 | mapped | — |
| Spies | https://trakt.tv/users/rizreflects/lists/spy-espionage-movies | search (rizreflects) | — | — | 1 | mapped | — |
| Super Shocks | https://trakt.tv/users/rizreflects/lists/supernatural-horrors | search (rizreflects) | — | — | 1 | mapped | — |
| Superheroes | https://trakt.tv/users/rizreflects/lists/superhero-movies | search (rizreflects) | — | — | 1 | mapped | — |
| Tearjerkers | https://trakt.tv/users/rizreflects/lists/melodramas | search (rizreflects) | — | — | 1 | mapped | — |
| Techno Thrillers | https://trakt.tv/users/acanas/lists/recommended-techno-cyber-thrillers | search (acanas) | — | — | 1 | partial | — |
| Thriller | https://trakt.tv/users/snoak/lists/popular-thriller-movies | snoak | https://trakt.tv/users/snoak/lists/popular-thriller-shows | snoak | 2 | mapped | — |
| Treasure Hunts | https://trakt.tv/users/waynecity/lists/treasure-hunts | search (waynecity) | — | — | 1 | partial | — |
| Vhs Era Frightmares | https://trakt.tv/users/mmagtech/lists/vhs-nightmares | search (mmagtech) | — | — | 1 | mapped | — |
| War Stories | https://trakt.tv/users/garycrawfordgc/lists/war | garycrawfordgc | https://trakt.tv/users/azodath/lists/popular-war-shows | search (azodath) | 2 | mapped | — |
| Westerns | https://trakt.tv/users/tvgeniekodi/lists/top-westerns | tvgeniekodi | — | — | 1 | mapped | — |
| Whodunits | https://trakt.tv/users/j-cao/lists/whodunit | search (j-cao) | https://trakt.tv/users/midnitewolf/lists/cozy-mysteries-whodunit-cozies-family-friendly-mystery-movies-and-shows | search (midnitewolf) | 2 | mapped | — |
| Workplace Comedies | https://trakt.tv/users/jarvis-8243417/lists/top-20-workplace-comedies | search (jarvis-8243417) | — | — | 1 | mapped | — |
| Zombie Orama | https://trakt.tv/users/emsishere/lists/zombie-movies | search (emsishere) | https://trakt.tv/users/qcnate/lists/zombie-shows | search (qcnate) | 2 | mapped | — |
