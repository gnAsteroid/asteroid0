# Asteroids

**Asteroids** gravitate around [gno.land](wiki/gnoland.md). 

They can be thought of as markdown wikis that are aware of GNO [realms](wiki/realm.md).

<!--Use them for scribbles, casual-blogging about crypto, notes, scratches, demo, etc.-->

## comparison

| gno.land                                                       | Asteroids                                            |
| -----------------                                              | ------------------                                   |
| main land of GNO                                               | blogs, personal pages, small websites                |
| has its own chain                                              | use gno.land for realms                              |
| operated by the GNO team                                       | operated individually                                |
| homepage is a realm ([/r/gnoland/blog](/r/gnoland/blog)) | markdown wikis                                       |
| can link and render realms                                     | can link and render realms from gno.land<sup>1</sup> |
| provides a helper to do transactions                           | wallet transactions redirect to gno.land             |
| fixed styling                                                  | interchangeable styling (`-style-dir <dir>`)         |
| imports `pkg/gnoweb`                                           | import `pkg/gnoweb`                                  |
| run with `cmd/gnoweb`                                          | run with `gnAsteroid`                                |

<sup>1</sup>: you may be curious how<!--(how they can render realms)-->. <!--It's explained on this [page](usage.md) (look for "gnoface").--> Consider this snippet in Markdown: `[try tic-tac-toe](/r/demo/games/tictactoe)`; it renders as: [try tic-tac-toe](/r/demo/games/tictactoe) ← Clicking this will show that realm rendering *right* on this asteroid (even though it runs on the gno.land chain). 

---------

<img src=/svg/alien-4.svg hspace=5 align=left />**Warning**: When security matters always check things on gno.land. Even though you can not run wallet transactions on asteroids, you should never trust them. The point of asteroids is to provide rich blogging and reading experience. As soon as you want to check or do something that matters, do it directly on https://gno.land.


