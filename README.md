# CSGOProPlayersAnalysis

Problem Statement
---------------------------
Given a dataset containing detailed statistics of CS:GO professional players across various matches, including metrics such as kills, deaths, assists, headshot percentage, accuracy, round win rate, and match outcomes, develop a predictive model to forecast individual player performance or team success in future MAJOR matches. Additionally, identify key performance indicators (KPIs) that strongly correlate with overall player or team effectiveness, and provide actionable insights to coaches and players for optimizing strategies, player roles, and training regimens based on data-driven analysis.

Dataset Source
---------------------------
https://www.kaggle.com/datasets/naumanaarif/csgo-pro-players-dataset

Column Description
---------------------------
| Column |                                                              Description                                                             |
| :-: | :------------------------------------------------------------------------------------------------------------------------------------: |
| player_id | Player's ID on HLTV |
| nickname | In-game name of the player |
| real_name | Name of the player |
| age | Age of the player |
| country | Country of the player |
| current_team | Current team of the player |
| teams | All teams of the player, including previous and current teams |
| total_kills | Total in-game kills by the player |
| headshot_percentage | Headshot percentage of the player |
| damage_per_round | Damage inflicted per round by the player |

	
11		
12	grenade_dmg_per_round	Damage inflicted per round with grenade by the player
13	maps_played	Total maps played by the player
14	rounds_played	Total rounds played by the player
15	kills_per_death	Kill(s) per death ratio of the player
16	kills_per_round	Kill(s) per round ratio of the player
17	assists_per_round	Assists per round by the player
18	deaths_per_round	Deaths per round of the player
19	saved_teammates_per_round	Average number of teammates saved per round by the player
20	saved_by_teammate_per_round	Average number of times the player was saved by the teammates
21	rounds_with_kills	Number of rounds in which the player got a kill
22	kill_to_death_diff	Kill-death difference
23	total_opening_kills	Total number of opening kills by the player
24	total_opening_deaths	Total number of opening deaths of the player
25	opening_kill_ratio	Opening kill ratio of the player
26	opening_kill_rating	Opening kill rating of the player
27	team_win_percent_after_first_kill	Win percentage of the team after first kill by the player
28	first_kill_in_won_rounds	Percentage of rounds won in which the player got first kill
29	0_kill_rounds	Number of rounds with 0 kills by the player
30	1_kill_rounds	Number of rounds with 1 kill by the player
31	2_kill_rounds	Number of rounds with 2 kills by the player
32	3_kill_rounds	Number of rounds with 3 kills by the player
33	4_kill_rounds	Number of rounds with 4 kills by the player
34	5_kill_rounds	Number of rounds with 5 kills by the player
35	rifle_kills	Number of rifle kills by the player
36	sniper_kills	Number of sniper kills by the player
37	smg_kills	Number of SMG kills by the player
38	pistol_kills	Number of pistol kills by the player
39	grenade_kills	Number of grenade kills by the player
40	other_kills	Number of other weapon kills by the player
41	rating	Rating of the player with 1.00 being the average
