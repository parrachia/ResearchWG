# Report

## What is Budgeting?

Budgeting is an essential part of nearly every for-profit and non-profit organization on the planet. At its core, budgeting is about creating a plan in regards to where to allocate resources during a future period of time.

There are three main roles of budgeting within these organizations \[1\], including:

* A forecast of expenditure \(and thereby profitability when combined with income forecasts\)
* A tool for decision making / alignment building
* A means to monitor business performance

Budgeting processes have existed in one form or another for centuries, rooted in helping monarchs manage their funds \[2\]. As the modern Corporation came to be, new tools and processes were created to manage funds and budget effectively towards a shared goal.

However, the nature of how we organize is shifting. Decentralized Autonomous Organizations \(DAOs\) with new governance models have the potential to completely shift the way budgets are created and the way budgets are managed. Note that as of this date of publishing, there do not seem to be any DAOs that follow a community governed budgeting process. Although projects like Aragon and Giveth do indeed have internal budgets, numbers are not determined and agreed upon by the community. DAOs researched include: Giveth, Dash, Decred, MolochDAO, ZenCash.

This document hopes to shed light on how DAOs might be able to budget their funds. Note that this document assumes that having a budget is a useful thing, and does not consider crowdfunding, bounties, grant programs, or other mechanisms to allocate capital \[3\].

The budgeting process is cyclical in nature with the following three characteristics:

1. Deciding on budgeting frequency
2. Creating / updating the budget
3. Following the budget

The sections below are divided into these three sections.

## Deciding on budgeting frequency

Traditional organizations create a budget at a minimum of once per year. Throughout the year, businesses usually track “actual” expenditures to their budget, and may modify the budget if needed. Every businesses’ budgeting process varies slightly, and I would imagine the same will occur within the DAO ecosystem.

Because of the rapidly evolving blockchain landscape, it might make sense to have shorter budgeting periods to start \(4 months, 8 months?\) and sticking to a plan and learning from it is likely good practice.

## Creating / updating the budget

Budgeting within a traditional organization is usually performed via either a top-down approach, a bottom up approach, or some form of collaborative approach. In a top-down approach, executives create the budget. In a bottom-up approach, business leaders submit forecasted expenditures to executives. In a collaborative approach, budgets are passed back and forth until agreement is reached.

Regardless of the process, the important thing to note is that budgets are usually created by individuals with deep subject matter knowledge of both projected funds available, planned objectives, as well as strategies required to achieve those objectives. I would expect DAOs to follow a similar pattern.

Below are two examples that outline how a budget for a DAO could be created, as well as two examples of how a DAO could choose between a set of created budgets.

#### Enspiral

* Enspiral is a decentralized coop \(not based on blockchain\) which has been experimenting with governance models since 2010
* Enspiral has a budgeting process for core expenses which occurs via a collaborative process between a small board and other members.
* A similar type of process could occur for a DAO, wherein an elected group of members are responsible to creation of a high level budget which would then be agreed upon by the community.

#### That Planning Suite \(TPS\), an Aragon project \[5\]

* Overview
  * TPS is a budgeting tool for DAOs and consists of 5 Aragon Apps
  * Proposals are submitted to a DAO, and members of the community can use Dot Voting \(formerly called Range Voting\) to vote on how funds should be allocated. The spreadsheet below helped me understand a bit better \(thanks Yalda!\): [https://docs.google.com/spreadsheets/d/1HzFBF2eKnToqs1c-X0rHUxNNl5SKPqO6K\_71tNkZEaU/edit\#gid=0](https://docs.google.com/spreadsheets/d/1HzFBF2eKnToqs1c-X0rHUxNNl5SKPqO6K_71tNkZEaU/edit#gid=0) \)
  * TPS allows for recurring expenditures, proposals, bounties, as well as one-off expenditures
  * Voting is weighted by member token holdings, but Reputation weighting could also be used at some point in the future
* Thoughts
  * You could in theory use this process to create accounts for different business units, and allocate funds to each of them respectfully using Dot Voting
  * This kind of voting is not likely a good mechanism to agree on a budget as the majority of members within a DAO do not have enough information to make an informed decision on the best budget numbers. Restrictions could be used to limit the number of individuals able to vote to generate more accurate budget numbers.

#### BudgetBox, a Colony initiative \[4\]

* Overview
  * Budget Box is a curation process to determine where capital should be allocated
  * It allows proposals to “compete” 1:1 against each other, whereby participants of a community select their preferred proposal for every combination of work proposals
  * Once proposals have finished competing, it is possible to create a ranking of all proposals
  * It could be incorporated with a reputation system giving certain community members more voting power
  * The initial application of this tool will be to allocate a recurring funding to projects within Colony, with top ranked projects receiving funding
* Thoughts
  * BudgetBox is an innovative way to rank / curate projects with low cognitive load
  * This tool could be used to determine the optimal budget for a decentralized organization: all you would need to do is to create various budgets, then let them compete to determine what budget the community likes best.
  * I personally doubt good results would come of this process, as the majority of members within a DAO do not have enough information to make an informed decision on the best budget numbers.
  * Who will create these budgets to be ranked?

#### Prediction Markets

* PM platforms could be used to determine which budget is best for the community. A market could be created for each budget proposal, and the budget proposal with highest value wins at some date in the future.
  * Once again: who will create these budgets to be bet on?

#### Alchemy \(DAOstack\)

* Alchemy could be used to propose various budgets, with only the budget with the highest voting power winning.
  * Once again: who will create these budgets to be voted on?

The examples above highlight a few ways in which a Budget could be agreed upon. Enspiral and TPS are ways in which a budget could be initially created. BudgetBox, PMs, and Alchemy are ways to determine the best budget from a pool of already created budgets.

The mechanism which likely makes the most sense is a budgeting process similar to traditional businesses / Enspiral, wherein a group is selected within the community to agree on a high level budget, which would then be voted and agreed on by the community. Ultimately, those with the most knowledge of current and future affairs are likely the ones with the best forecasting ability.

Agreeing and updating a Budget for a DAO would likely be done via the submission of a proposal, which would then be agreed upon by the community.

## Following the budget

In traditional bottom-up budgeting, each business unit creates a budget. Actual expenditures are then tracked to those forecasted in the budget. Each manager is incentivized to be as accurate as possible in forecasting, as well as in their spending - since this will help them get promoted.

Expenditures for all business units come from the company’s bank account, and are tracked to each business unit via the help of accountants and spreadsheets. Business units usually have spending limits on items \(over which approval is required\) to maintain a certain level of control.

There are a few differences between traditional organizations and a DAO when it comes to following a budget:

* Incentive mechanisms to create “accurate” budgets do not exist within a DAO since you can not get promoted or fired.
* Unlike a traditional organization, a DAO is able to easily create separate accounts with funds available for every business unit which could put a limit on what they can spend. It could also be possible to allow business units to go into debt. This kind of configuration could look similar to a hub and spoke model, with each business unit having a separate DAO, and internal budgeting process.

Both of these differences suggest DAOs budget enforcement will look different than those within a traditional organization.

## GenDAO Budgeting: Next Steps

A Budget is important for planning purposes, and it is my belief that budgeting will be required for DAOs to effectively tackle their vision and objectives. I also believe that a budgeting process should be trialed and experimented with from an early stage in order to learn and adapt the process, while also aiming to keep the process decentralized and fluid.

Below are some ideas on next steps in relationship to GenDAO:

* Decide whether or not a budget planning/formalization would be useful for longer term planning purposes. If so...
  * Agree on [vision and objectives.](https://docs.google.com/document/d/10-0ppf_QpYdlBC_AFWt-QhJWyUpBRl5zU9bU1AWXUqU/edit) This is critical to help understand what GenDAO plans to accomplish in the short/medium/long term, and helps clarify what the budget might look like
  * Create a cross-functional group which will be tasked with creating a high level budget based on these objectives. I would imagine this would consist of DAOstack members, pollinators, as well as GEN stakeholders including DAOs. The output of this cross-functional team would likely consist of a budget breakdown by functional area \(%\) over the next 6 to 12 months.
  * Create a simple mechanism to track which objectives or which business unit a proposal is associated with. In this manner, “actual” expenditures could be tracked to “budgeted”
* A longer term solution might be to allow a DAO to create working groups / sub-DAOs, and allocate them a % or fixed amount of funding. Although having this kind of mechanism might be useful, it is not required to start to learn from a budgeting process.

## References

\[1\] - [http://www.leoisaac.com/budget/bud031.htm](http://www.leoisaac.com/budget/bud031.htm)

\[2\] - [https://www.telegraph.co.uk/finance/2953319/A-Budget-history.html](https://www.telegraph.co.uk/finance/2953319/A-Budget-history.html)

\[3\] - [https://github.com/nayafia/lemonade-stand](https://github.com/nayafia/lemonade-stand)

\[4\] - [https://colony.io/budgetbox.pdf](https://colony.io/budgetbox.pdf)

\[5\] - [https://github.com/AutarkLabs/planning-suite](https://github.com/AutarkLabs/planning-suite)

