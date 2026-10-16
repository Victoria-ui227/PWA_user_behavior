## AGENTS/USER BEHAVIOR SINCE SEPTEMBER 30TH
This analysis examines 420 agents on the *Low Frequency (Browse Over Buy)* tab of the warehouse-verified extract dated October 8, 2026, identifying those who browse products on PWA but create relatively few policies, and distinguishing declining business from consistently low sales.

Since PWA product-view tracking began around September 30, 2026, sales before this date represent historical performance, while sales since then indicate recent activity.

Browsing, quotes, policies created, and paid business are treated as separate signals. Viewing products or creating a policy does not necessarily mean a sale was completed or paid.

#### *Activity versus business*

• Activity: 5,773 view events. Shows interest only.

• Intent: 176,636 lifetime quotes. Undated, and 180 agents have more sales than quotes, so quotes do not capture every sale.

• Policies created: 2,967 since Sep 30. The tab does not say whether they were paid or which platform they came from.

• Paid business: not on this tab. Hand checks from Oct 3 cover 34 of these agents: 301 sales, 53 unpaid, 268 on the PWA and 33 on the old platform.  


### PROBLEM STATEMENT 

LAMI cannot yet tell which agents are losing business and which are still producing, because the data mixes browsing, quotes and policies written, and does not record payment or platform. Every agent on this tab sold at least once since Sep 30, so the risk is a slowdown, not a full stop: an agent who sold hundreds of policies before Sep 30 and only 1 or 2 since looks active on a simple "has sales" check.


The analysis needs to answer five questions:


1. Which agents browse heavily on the PWA but write few policies since Sep 30?

2. Which agents are selling far below their own history before Sep 30?

3. Which agents are actively generating business, and what share of recent sales do they account for?

4. How much of each agent's recorded activity is actual business: policies created, and of those, how many are paid?

5. Where is platform attribution unclear, so that an apparent drop may be selling on the old platform instead?

A good result is a named, prioritised list of slowing and non-converting agents for follow-up, with each classification shown alongside the evidence behind it and its known gaps.


## FINDINGS
### Sales share before and since September 30th
![Share Before and Since](plots/share_before_since.png)

• Slowing agents are the clear drop. They hold more past business than the browsing and steady groups combined, but now write about 4 policies per 1,000 past sales, a quarter of the overall 15.8.

• Producing agents carry the book in both periods. Their share rises slightly, from 78.8% to 81.6%.

• Browsing and low-but-steady agents gained share. They are small sellers with short histories, so even a few recent policies lift their ratio; this does not mean they are strong performers.

• New agents have no history, so they cannot be compared this way.

Limits: The window since Sep 30 is about 8 days, which is short for agents who sell weekly or monthly.

### Sales since Sep 30th
The 420 agents wrote 2,967 policies between Sep 30 and Oct 8, but half of them came from just 58 agents (14%). The typical agent wrote 4 policies, about one every two days, while the top agent wrote 170.

<p align="center">
  <img src="plots/sales_band_table.png" width="48%" />
  <img src="plots/sales_since_sep30_bands.png" width="48%" />
</p>

• The average agent wrote 7.1 policies, but the typical agent wrote only 4. This is because a small number of high-performing agents wrote many more policies than everyone else. 134 agents (32%) wrote only 1–2 policies. Together, they contributed just 6.9% of all policies.77 agents (18%) wrote 10 or more policies and accounted for 57% of all policies. This shows that policy production is concentrated among a relatively small group of agents.
- A small group accounts for a large share of sales:The top 10 agents produced 21.6% of all policies written since September 30.The top 42 agents (10% of the agents analysed) produced 43.5% of all policies.Just 181 agents (43%) accounted for 80% of all policies.
- The five highest-producing agents were:

Warfa & Associates Agency — 170 policies

Leila Chebet — 103

Khaira Ali — 62

Ann Kimani — 61

Michael Ndungu — 55

All five also have more than 4,000 lifetime sales, suggesting that the strongest recent performers are also experienced agents with substantial sales histories.

#### *How browsing relates to selling* 

-Agents who sell more also tend to browse products more frequently. The relationship between product-view events and policies was moderately positive (correlation of 0.5).However, high-performing agents appear to convert their browsing into policies more efficiently:

Agents who wrote 50 or more policies averaged approximately 1.2 views per policy.Agents who wrote only one policy averaged around 6 views per policy.Agents with stronger recent sales also had much higher lifetime sales. The median lifetime sales increased from 54 among agents who wrote one recent policy to 5,870 among those who wrote 50 or more.

This suggests that experienced, established agents may be better at turning product interest into business. However, browsing activity alone does not tell us whether an agent will make a sale.

*Where the policies come from*
Nairobi City contributed the largest share of policies, accounting for 44% of the total, from 198 agents. The median was 3 policies per agent.

The next-largest contributors were:

Mombasa: 10.0% of policies, with a median of 6 per agent.

Kiambu: 9.6% of policies, with a median of 5.5 per agent.

Kericho contributed 3.5% of all policies, but this came from just one agent, Leila Chebet. This means Kericho's contribution reflects one individual's performance rather than broad activity across multiple agents.

![Snapshot of Business Activity](plots/agent_funnel.png)
