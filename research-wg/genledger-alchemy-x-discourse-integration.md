# genLedger - Alchemy x Discourse integration

### Summary

Create a connection between Alchy Dapp and DAOtalk Discourse forum.

Effectively, the genDAO corner of DAOtalk should include space for a proposal ledger / repository. Archiving proposals, having project hubs for: goals, preProposals, comments, deliverables. Signaling, QA and Accountability could also find their place there.

### Rationale \(WIP\)

* ease of use, scalable solution for proposals lifecycles
* All-in-one tagging system, search engine, accountability, alacrity visualization

### TODO

* Research 
* [ ] Discourse to Git? 
* [ ] Decentralization of hosting, backups
  * Filecoin, IPFS, git repo..., anything else?
* [ ] Ways to bridge Alchy to Discourse? 
  * besides manual effort, bots, APIs, anything else?
* Elaborate
* [ ] Rationale 
* [ ] Tokens & Rep
* [ ] Next steps
* [ ] Implementation
* [ ] Responsibilities 
* [ ] List QAA opportunities 

### MVP - Stage I

#### option A

* no more gdocs but daotalk posts
  * when submitting a proposal, instead of a gdocs, we either create a post just for that and link it or to an updated preProposal post

#### option B

* Submit a proposal however you like,
  * A bot could crawl the dapp for new proposals and its state changes 
    * when a proposal gets submited a new post is created by this bot

#### either way

* When a proposal changes state \(boosting, flagging...\) we manualy update it
* New, manually assigned tags: proposals by entities/ teams \(dOrg, Greatherthan, DANk, other WGs\)
* New, manually assigned, categories\(subcategories\): preProposals -&gt; Proposals\(internal or external x financial or nonFinancial\) -&gt; passedProposals \(executing x non executing\) -&gt; Archive
  * When it passes we manually move to a new category 
  * preProposals posts could be archived after having its proposals submited to Alchy, avoiding duplicates and for decluttering purposes

### ??? - Stage II

### luxury space communism - Stage III

* In the future, an API should streamline and automate most things for us
  * Allowing for integrations with other platforms and clients
  * Realtime state changes upgrades
    * when a proposal gets pre-boosted it earns a tag/label, when boosted the tag/label changes.
* Different proposal titles could trigger different actions in the forum 
  * Tags, categories, taxonomy, notifications...
* More optional fields when submitting proposals on Alchy
  * Like time! 
    * Dynamic checkpoints and deadlines: countdowns updated after special interactions

### References

{% embed url="https://www.discourse.org/integrations" %}

{% embed url="https://meta.discourse.org/t/events-plugin-calendar/69776" %}

{% embed url="https://github.com/angusmcleod/discourse-elections" %}

{% embed url="https://github.com/angusmcleod/discourse-moderator-extension" %}









