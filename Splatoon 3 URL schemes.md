# Splatoon 3 URL schemes

Tested on [Nintendo Switch Online](https://apps.apple.com/app/id1234806557).

Starts with ` com.nintendo.znca://znca/game/4834290508791808?p=<url encoded path> `, `:` indicates that it's a parameter.

| Path                                                 | Notes                             |
|------------------------------------------------------|-----------------------------------|
| /                                                    | SplatNet 3                        |
| /friends                                             | Friends list                      |
| /gesotown                                            | Shop                              |
| /gesotown/:saleGearID                                | Gear in shop                      |
| /my_outfits                                          | Freshest Fits                     |
| /my_outfits/create                                   | Creat new Fits                    |
| /my_outfits/:outfitsID                               | View saved Fits                   |
| /history_record                                      | History                           |
| /x_ranking                                           | X match                           |
| /x_ranking/:SeasonID/ar                              | X Rank in Splat Zones             |
| /x_ranking/:SeasonID/lf                              | X Rank in Tower Control           |
| /x_ranking/:SeasonID/gl                              | X Rank in Rainmaker               |
| /x_ranking/:SeasonID/cl                              | X Rank in Clam Blitz              |
| /event_match_ranking                                 | Event Challenge                   |
| /challenge                                           | Wandercrust                       |
| /challenge/:JourneyID/:ChallengeID [1](#JourneyID)   | Specific challenge in Wandercrust |
| /catalog_record                                      | Catalog                           |
| /photo_album                                         | Photo Album                       |
| /tournament                                          | Tournaments Manager               |
| /weapon_record                                       | Weapon Record                     |
| /stage_record                                        | Stage Record                      |
| /fest_record                                         | Splatfest Record                  |
| /fest_record/ranking/:festID [2](#festID)            | Ranking in specific Splatfest     |
| /fest_record/voting/:festID [2](#festID)             | Voting in specific Splatfest      |
| /coop_record                                         | Salmon Run Record                 |
| /hero_record                                         | Hero Mode Record                  |
| /replay                                              | Replays                           |
| /room_creator                                        | Room Creator                      |
| /checkin                                             | QR code Reader                    |
| /setting                                             | Settings                          |
| /schedule                                            | Schedule                          |
| /schedule/fest                                       | Schedule for Splatfest            |
| /schedule/regular                                    | Schedule for Regular              |
| /schedule/bankara                                    | Schedule for Anarchy              |
| /schedule/xmatch                                     | Schedule for X match              |
| /schedule/event                                      | Schedule for Event Challenge      |
| /schedule/coop                                       | Schedule for Salmon Run           |
| /history                                             | Battles                           |
| /history/detail/:ResultID                            | Details in specific battles       |
| /history/latest                                      | Latest battles                    |
| /history/regular                                     | Regular battles                   |
| /history/bankara                                     | Anarchy battles                   |
| /history/xmatch                                      | X match battles                   |
| /history/event                                       | Event Challenge battles           |
| /history/private                                     | Private room battles              |
| /coop                                                | Salmon Run                        |
| /coop/:coopID                                        | Details in specific Salmon Run    |

## JourneyID

| JourneyID                            | Notes                            |
|--------------------------------------|----------------------------------|
| Q2hhbGxlbmdlSm91cm5leS1qb3VybmV5XzE= | Journey 1: The Journey Begins    |
| Q2hhbGxlbmdlSm91cm5leS1qb3VybmV5XzI= | Journey 2: The Journey Continues |
| Q2hhbGxlbmdlSm91cm5leS1qb3VybmV5XzM= | Journey 3: The Journey Ends      |
| Q2hhbGxlbmdlSm91cm5leS1qb3VybmV5XzQ= | Journey 4: A Journey Reborn      |

## festID

| festID                   | Notes                            |
|--------------------------|----------------------------------|
| RmVzdC1KUDpKVUVBLTAwMDEy | 休みの日は？                     |
| RmVzdC1KUDpKLTAwMDEx     | コレなんて呼ぶ？                 |
| RmVzdC1KUDpKVUVBLTAwMDEw | 友だちにするなら？               |
| RmVzdC1KUDpKVUVBLTAwMDA5 | リーダーにふさわしいのは？       |
| RmVzdC1KUDpKVUVBLTAwMDA4 | 人生で大事なのは？               |
| RmVzdC1KUDpKVUVBLTAwMDA3 | アイスといえば？                 |
| RmVzdC1KUDpKVUVBLTAwMDA2 | 汝、何を求める？                 |
| RmVzdC1KUDpKVUVBLTAwMDA1 | 実在するのは？                   |
| RmVzdC1KUDpKVUVBLTAwMDA0 | チョコレートはやっぱりコレ！     |
| RmVzdC1KUDpKVUVBLTAwMDAz | 好みの味は？                     |
| RmVzdC1KUDpKVUVBLTAwMDAy | パートナーに選ぶならどのタイプ？ |
| RmVzdC1KUDpKVUVBLTAwMDAx | 無人島に持っていくなら？         |
