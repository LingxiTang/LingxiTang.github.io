---
layout: page
title: No GRCs
description: What if Singapore never had GRCs?
img: assets/img/2020_NoGRC_ProPAP.png
importance: 1
category: politics
related_publications: false
---

Data and code used for this article are [here](https://github.com/LingxiTang/NoGRCExperiment).

This post summarises the main findings from a experiment I conducted and there will also be a rant on the GRC system at the end. 

__DISCLAIMER__: <br>
This is an experiment. All scenarios are purely hypothetical. I have 0 background in political science. As such, the scenarios are based on extremely crude assumptions, and so are quite flawed. *Gahmen, pls don't pofma.*

____________________________________________________________________________________________________________________________________________________________________________________

__BACKGROUND__

The Members of Parliament (MPs) of Singapore are elected on a five-year cycle based on a first-past-the-post Westminster system, i.e. in each constituency, the MP(s) that get the most votes wins. In all countries that follow this system, each constituency only has one MP, until 1988.

In the 1988 Singaporean General Election (GE), the GRC system was introduced. Group Representative Constituencies, or GRCs, are constituencies which have multiple seats. i.e. the party which has the most votes in a GRC wins all the seats in the GRC. A key feature of GRCs was that at least one MP in each GRC must be from a minority community, or simply, non-Chinese.

Why introduce GRCs? Officially, it was to guarantee a multiracial parliament. After all, SMCs do run the risk of having a Parliament full of Chinese MPs.

Unofficially, many accuse the GRC system of a being a gerrymandering system. 

That led me to the question: *How well did the GRC system gerrymander? How different would the Singapore Parliament have been if GRCs were never implemented?*

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/gerrymandering.png" title="Gerrymandering" class="img-fluid rounded z-depth-1" style="width: 10%;"%}
    </div>
</div>
<div class="caption">
    Best graphic to explain gerrymandering. The main idea is that you draw constituency boundaries so that you win more votes in each constituency.
</div>
____________________________________________________________________________________________________________________________________________________________________________________

__RESEARCH DESIGN__

To answer this question, I looked at the GE results from 1988 to 2010, and made changes based on the following assumptions:

- Seats in GRCs split proportionally based on votes. E.g. If a 4-member GRC had a vote split of 75:25, the seats would be split 3:1.

- Results of SMCs remain the same.

- PAP gets the rounded up seat split. e.g. PAP wins 100% of seats in a GRC as long as they win >= 75% of votes. (This is the Pro-PAP scenario. More scenarios later.)

____________________________________________________________________________________________________________________________________________________________________________________

__RESULTS__

Alright, let's look at how many seats each party would have gained/lost in this PURELY HYPOTHETICAL SCENARIO, as compared to reality.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SeatChanges_ProPAP.png" title="Seat Changes (Pro PAP)" class="img-fluid rounded z-depth-1"%}
    </div>
</div>
<div class="caption">
    Fig 1: Oof. Big losses for PAP. Luckily, we've got GRCs! Whew.
</div>

As expected, if GRCs had been proportionally represented, we see the winning party (historically PAP) losing their seats. Because the votes that had gone unrepresented are now actually translating to seats won.

Interestingly, in 2020, even WP benefitted from the GRC system because they, well, won GRC seats, in Aljunied and Sengkang.

I know what you're thinking. *Bruh, where's the label for 2011*

Turns out it’s a bug caused by the fact that WP didn’t contest any GRCs in 2001. This then led me to realise that WP was not the main opposition party until relatively recently. In fact, between 1988 and 2001, WP only won 1 seat, on par with the Chiam See Tong/Chee Soon Juan parties of SDP, SPP and SDA.

*What happened in 2011? Why the big spike in seat changes?*

To answer this, I thought it might be because GRC seat numbers jumped in 2011 and so, to confirm this, I plotted the % of seats which were in GRCs vs SMCs since 1988 (See Left below).

Anddd I was wrong: % of seats in GRCs were pretty stable since 1997. So, this couldn’t have been the reason behind the 2011 spike in seat changes.

I looked bit deeper and alas, 2011 was the first year since 1988 that all seats were contested. As in, between 1988 and 2006, PAP won a bunch of uncontested seats (See Right below). 

Under my scenario assumptions, these seats would not change since there were no opposition votes. Thus, it makes sense that 2011 would see a spike in the seat change.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/GRCvSMCShare.png" title="GRCvsSMC Share" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Uncontested.png" title="Uncontested seats" class="img-fluid rounded z-depth-1" %}
    </div>

</div>
<div class="caption">
    Fig 2:<br> 
    Left: Parliament seats from GRCs rose quite quickly up till 1997.<br>
    Right: PAP grabbing ez seats, with no contests. This explains the results in Fig 1.
</div>

____________________________________________________________________________________________________________________________________________________________________________________

__RESEARCH DESIGN 2__

Going back to __RESEARCH DESIGN__, I made the generous assumption that the PAP gets rounded up seats in our hypothetical scenario.

But WHAT IF the assumption didn't skew towards PAP? To answer this, I tested 2 more scenarios, for a total of 3 scenarios:

1. <u>Pro PAP</u> (what we’ve seen so far): PAP gets the rounded up seat split. e.g. In a 4-seat GRC, PAP gets 4 seats in an 80:20 vote split.
   
2. <u>Anti PAP</u>: PAP gets the rounded down seat split. e.g. PAP gets 3 seats in an 80:20 vote split.
   
3. <u>Pro Winner</u>: The actual winner gets the rounded up seat split. e.g. If opposition actually won the GRC, opposition gets the 4 seats in this scenario, else if PAP won it, PAP gets them.

____________________________________________________________________________________________________________________________________________________________________________________

__RESULTS 2__

Alright again, let's look at how many seats each party would have gained/lost in these PURELY HYPOTHETICAL SCENARIOs, as compared to reality. *Sorry for making you squint* 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SeatCha_ProPAP_2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SeatCha_AntiPAP.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SeatCha_ProWin.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fig 3:     Seat changes for all 3 scenarios
</div>


Comparing 'Pro-Winner' and 'Pro-PAP':

The differences are minimal. The simple reason is that the PAP had been winning and so, they’re practically the same scenario. The main differences between these 2 scenarios happen when opposition actually won GRC seats (i.e. WP in 2011 - 2020).

Comparing 'Anti-PAP' and 'Pro-PAP':

Now this is where it gets interesting. Basically, what happens is that seat changes doubled in 'Anti-PAP' compared to 'Pro-PAP'. For e.g., if the seat change for PAP was -10 in 'Pro-PAP', it would be roughly -20 in 'Anti-PAP'. 
These two scenarios could be interpreted as the “best case” and “worst case” for the PAP.

In the worst case, oof, 30 SEATS LOST from the PAP, had there been no GRC. Hm, would they still have had a supermajority?

____________________________________________________________________________________________________________________________________________________________________________________
*Supermajority?*

A party holds a supermajority of the parliament if they have more than 2/3 of seats. This gives them the power to make changes to the CONSTITUTION, which PAP has done so. Most notably, 
the [2016 minority president amendment](https://web.archive.org/web/20190606165027/https://www.channelnewsasia.com/news/singapore/elected-presidency-amendments-to-constitution-passed-in-parliame-7719282) 
& [2022 marriage definition amendment](https://www.channelnewsasia.com/singapore/s377a-repeal-constitution-amendment-marriage-definition-creative-arguments-3108831).

____________________________________________________________________________________________________________________________________________________________________________________

At this stage, I invite you to check out an [interactive dashboard](https://mybinder.org/v2/gh/LingxiTang/NoGRCExperiment/HEAD?labpath=Results_Visualisation_interactive.ipynb), where you can compare actual and hypothetical
GE results. Using this dashboard, I compiled the following results regarding PAP's supermajority.

Pro-PAP: 

- 1988-2020: PAP holds a supermajority.

Anti-PAP:

- 1988-2006:    PAP holds a supermajority.
- 2011:         PAP misses supermajority by 7 seats, but wins 7 seats above majority.
- 2015:         PAP misses a supermajority by 3 seats, but wins 12 seats above majority.
- 2020:         PAP misses supermajority by 9 seats, but wins 6 seats above majority.

So, even without GRCs, PAP would still have a supermajority in the best case, and still have a safe majority in the worst case.

____________________________________________________________________________________________________________________________________________________________________________________

__DISCUSSION__

*So, how well did the GRC system gerrymander?*
  - First set of results kinda showed that the GRC system tend to favour the winning party which, historically, has mostly been the PAP. So yes, the GRC system has been a good gerrymandering tool. 
  - But at the same time, we show that, without GRCs, the PAP would hold a supermajority anyway, so effectively, our government would have functioned the same. At worst (Anti-PAP scenario), PAP is still popular enough to hold a majority in parliament. So, GRC system has been a good but also unnecessary tool for gerrymandering?


*Ok, what about the intended purpose of the GRC system? Has it ensured minority representation in parliament?*
  - Yes indeed, accusing the GRC system to only be a gerrymandering tactic isn't fair. We need to see if it did what it was designed to do. But how might we assess that? A good start would be to look at minority MPs before and after 1988 and see how that changed.
  - Looking at the 1984 GE results (right before GRCs were implemented), I count about 14 minority MPS out of 79 elected seats (17.72%), including ex-WP leader JB Jeyeratnam. 
  - For comparison, there were 17 GRCs in 2020. So, effectively, GRCs guaranteed 17 minority MPs out of 93 elected seats (18.28%) in 2020, that’s barely an improvement from 1984 with no GRCs. To be fair, the 2020 GE saw 25 minority MPs out of 93. But still, the necessity of GRCs to ensure minority representation is questionable.
  - So… it didn’t seem like minorities had a problem of a lack of representation in parliament?

  - Also, do we really need a quota to ensure minority representation in parliament? Some of our best politicians today are from the minority communities. Most notably, Tharman, Shanmugan, Pritam Singh. I’d say it’s almost abit insulting to the minority community to say that GRCs are needed to guarantee minority MPs. If anything, i think we can agree that these powerhouse ‘minority’ politicians had been hard-carrying their fellow Chinese GRC mates.

* But an efficient one-party system is good for Singapore! If it means a stable government, gerrymandering can stay. *
- Well, as we saw in the 'Pro-PAP' and 'Pro-Winner' scenarios, PAP would have been the ruling party with a supermajority. 
- Worst case ('Anti-PAP'), PAP might have lost their supermajority since 2011, but they would still have a majority and be able to pass laws easily. 
- Sure, PAP wouldn't have been able to amend the constitution so easily. To that, I ask, should our Constitution be amended so easily? But that's for another time.

____________________________________________________________________________________________________________________________________________________________________________________

__RANT ABOUT __