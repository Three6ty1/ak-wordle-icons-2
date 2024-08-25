# Instructions

## Expected results as of 25/08/2024
There 340 Icons, 25 missing entries database due to icons being from CN.

2 Icons are the alt amiya versions.

There are total 315 operators in the database excluding IS and Amiya forms.

The database is up to date with **Shus banner**. The next banner (not included) is **R6 banner**

## Update Database
Download [handbook_info_table.json](https://github.com/Kengxxiao/ArknightsGameData_YoStar/blob/main/en_US/gamedata/excel/character_table.json) and [character_table.json](https://github.com/Kengxxiao/ArknightsGameData_YoStar/blob/main/en_US/gamedata/excel/handbook_info_table.json) from ~~Aceship~~ Gamedata datamined github. Can double check race with [handbook_team_table.json](https://github.com/Kengxxiao/ArknightsGameData_YoStar/blob/main/en_US/gamedata/excel/handbook_team_table.json)
Thank you to NikitaZero from the Arknights wiki.gg team for pointing me in the right direction.

Replace local files if applicable

Run build_db.py in root file (I hard coded the paths)

## Update Icons
(Optional) Use git sparse checkout to get the icons and clean.py to remove non-operator artworks.

Need to download cwebp and put /bin/.exe into the avatar directory https://developers.google.com/speed/webp/download 
Need to run in the same directory as avatars

convert.sh the files from png to webp and make into 180x180 to conserve space

Copy and paste the UL element from ace ship when searching all operators

Use sanity_check wiki.gg site https://arknights.wiki.gg/wiki/Operator/List

## Update site
Move updated operator db into correct directory

Seed database