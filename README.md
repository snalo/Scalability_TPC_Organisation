# Scalability_TPC_Organisation
This repo contains code for three common TPC organisation types: AMW, MAW &amp; MWA
Gen_Arch also handles all the conditions as defined below.
# Define the conditions
Tier_1 = org_mode == 'AMW' and tpe == 'N=M'
Tier_2 = org_mode == 'AMW' and tpe == 'NnotM'
Tier_3 = org_mode == 'MAW' and tpe == 'N=M'
Tier_4 = org_mode == 'MAW' and tpe == 'NnotM'
Tier_5 = org_mode == 'MWA' and tpe == 'N=M'
Tier_6 = org_mode == 'MWA' and tpe == 'NnotM'
