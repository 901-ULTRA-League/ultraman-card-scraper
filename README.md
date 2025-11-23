# ULTRAMAN Card Game Database

![ULTRAMAN Card Game logo](./logo_ucg.png)

## Scraped from the Official [Cardlist](https://ultraman-cardgame.com/page/us/card/card-list)

### Autoruns every week

CHANGELOG:

11/16/25: Had to update, new API changes include new BP scale, and details

9/30/2025: Added image downloader, fixed error that allowed linebreaks in cards CSV

The two scripts, [card-db-api.py](./card-db-api.py) and [card-db-meta.py](card-db-meta.py) output two sets of data, arguably one being more interesting than the other. The 'api' file will output the entire ULTRAMAN card catalog, promos and all into [this csv](./ultraman_cards.csv), and the 'meta' file will output additional data like different sets, types, grades, e.g. into different CSVs.

Have fun, Buddies! Build something cool with it!

Dedicated to the Buddy who got me into ULTRAMAN ;)
