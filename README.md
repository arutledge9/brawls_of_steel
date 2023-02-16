# brawls_of_steel
Python code in Jupyter Notebook to produce summary report in markdown format

## Description

Splinterlands (https://www.splinterlands.com) is a unique, card deck-building blockchain game which draws inspiration from Magic: The Gathering, Yu-Gi-Oh!, and Pokémon. While the game's play is always 1-1, players have the option to join "guilds" of like-minded players for additional playing options, rewards, and for a greater feeling of community. 

Guilds battle other Guilds in regularly-scheduled card matches called Brawls, which pit the majority of a Guild's members against the members of up to nine other Guilds. Naturally, winning, or even performing well in Brawls gives Splinterlands players major bragging rights. Brawls are divided into a total of five tiers, based on the development of the participating Guilds - with the idea that the older, more established Guilds fall into the highest tiers so as to not discourage (or not wipe the floor with) the newer, less established Guilds. 

This project performs a number of API calls to the Splinterlands game to summarize the top performing Guilds and Players per Brawl tier, per Splinterlands "season". A Splinterlands season typically lasts for two weeks, and there are usually three Brawls per season. The code currently needs minimal tweaking per season to perform its summaries (adjusting the three brawl cycle numbers in Cell 3). In subsequent versions, I would like to revise the code to compare Brawl dates vs. Season dates and detect the cycle numbers automatically. 

The code exports 8 tables in markdown format - a guild summary and a player summary for tiers 1-4, as currently no Guilds compete in tier 5. The markdown tables are then published, along with descriptive text, as blog posts to the Hive Blockchain on which the Splinterlands operates. 
