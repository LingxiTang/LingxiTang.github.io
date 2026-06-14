---
layout: page
title: No GRCs
description: What if Singapore never had GRCs?
img: assets/img/2020_NoGRC_ProPAP.png
importance: 1
category: for fun
related_publications: false
---

*June 2026 Update: Added 2025 GE results.*

Data and code used for this article are [here](https://github.com/LingxiTang/NoGRCExperiment).

This post summarises the main findings from a experiment I conducted and there will also be a rant on the GRC system at the end. 

__DISCLAIMER__: <br>
This is an experiment. All scenarios are purely hypothetical. I have 0 background in political science. As such, the scenarios are based on extremely crude assumptions, and so are quite flawed. *Gahmen, pls don't pofma.*

____________________________________________________________________________________________________________________________________________________________________________________

__BACKGROUND__

The Members of Parliament (MPs) of Singapore are elected on a five-year cycle based on a first-past-the-post Westminster system, i.e. in each constituency, the MP(s) that get the most votes wins. In all countries that follow this system, each constituency only has one MP, until 1988.

In the 1988 Singaporean General Election (GE), the GRC system was introduced. Group Representative Constituencies, or GRCs, are constituencies which have multiple seats. i.e. the party which has the most votes in a GRC wins all the seats in the GRC. A key feature of GRCs was that at least one MP in each GRC must be from a minority community, or simply, non-Chinese.

Why introduce GRCs? Officially, it was to guarantee a multiracial parliament. After all, SMCs do run the risk of having a Parliament full of Chinese MPs.

Unofficially, many accuse the GRC system of a being a gerrymandering system (See graphic below). 

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

To answer this question, I looked at the GE results from 1988 to 2010, and applied hypothetical changes based on the following assumptions:

- Seats in GRCs split proportionally based on votes. E.g. If a 4-member GRC had a vote split of 75:25, the seats would be split 3:1.

- Results of SMCs remain the same.

- PAP gets the rounded up number of seats based on the vote proportion. e.g. If PAP wins 51-75% of votes in a 4-member GRC, they win 3 seats. (This is the 'Pro-PAP' scenario. More scenarios will be explored later.)

____________________________________________________________________________________________________________________________________________________________________________________

__RESULTS__

Alright, let's look at how many seats each party would have gained/lost in this PURELY HYPOTHETICAL SCENARIO, as compared to reality.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SeatChanges_ProPAP.png" title="Seat Changes (Pro PAP)" class="img-fluid rounded z-depth-1"%}
    </div>
</div>
<div class="caption">
    Fig 1: Seat changes for parties if GRCs were not implemented.<br>
    Oof. Big losses for PAP.
</div>

As expected, if GRCs had been proportionally represented, we see the winning party (historically PAP) losing their seats. Because the votes that had gone unrepresented are now actually translating to seats won.

Interestingly, in 2020, even WP benefitted from the GRC system because they, well, won GRC seats, in Aljunied and Sengkang.

I know what you're thinking. *Bruh, where's the label for 2011* (*June 2026 Update: Previously, the x-axis label for 2011 was missing due to a code bug. I've fixed it now*)

Turns out it’s a bug caused by the fact that WP didn’t contest any GRCs in 2001.  This then led me to realise that WP was not the main opposition party until relatively recently. In fact, between 1988 and 2001, WP only won 1 seat, on par with the Chiam See Tong/Chee Soon Juan parties of SDP, SPP and SDA.

*What happened in 2011? Why the big spike in seat changes?*

To answer this, I thought it might be because GRC seat numbers jumped in 2011 and so, to confirm this, I plotted the % of seats which were in GRCs vs SMCs since 1988 (See Left below).

Anddd I was wrong: % of seats in GRCs were pretty stable since 1997. So, this couldn’t have been the reason behind the 2011 spike in seat changes.

I looked bit deeper and alas, 2011 was the first year since 1988 that all seats were contested. As in, between 1988 and 2006, PAP won a bunch of uncontested seats (See Fig on the right below). 

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
    Right: PAP grabbing ez seats until 2011. This explains the results in Fig 1.
</div>

____________________________________________________________________________________________________________________________________________________________________________________

__RESEARCH DESIGN 2__

Going back to __RESEARCH DESIGN__, I made the generous assumption that the PAP gets rounded up seats in our hypothetical scenario.

But WHAT IF the assumption didn't skew towards PAP? To answer this, I tested 2 more scenarios, for a total of 3 scenarios:

1. <u>Pro PAP</u> (what we’ve seen so far): PAP gets the rounded up seat number. e.g. In a 4-seat GRC, PAP gets 3 seats if they win 51-75% of votes.

2. <u>Anti PAP</u>: PAP gets the rounded down seat number. e.g. In a 4-seat GRC, PAP gets 2 seats if they win 50-74% of votes.
   
3. <u>Pro Winner</u>: The actual winner gets the rounded up seat number. e.g. In a 4-seat GRC, the actual winner gets 3 seats if they win 51-75% of votes.

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

The differences are minimal. The simple reason is that the PAP had been winning and so, they’re practically the same scenario. The main differences between these 2 scenarios happen when opposition actually won GRC seats (i.e. WP in 2011 - 2025).

Comparing 'Anti-PAP' and 'Pro-PAP':

Now this is where it gets interesting. Basically, what happens is that seat changes doubled in 'Anti-PAP' compared to 'Pro-PAP'. For e.g., if the seat change for PAP was -10 in 'Pro-PAP', it would be roughly -20 in 'Anti-PAP'. 
These two scenarios could be interpreted as the “best case” and “worst case” for the PAP.

In the worst case, oof, 30 SEATS LOST from the PAP, had there been no GRC. Hm, but would they still have had a supermajority, in the 'Anti-PAP' scenario?

____________________________________________________________________________________________________________________________________________________________________________________
*Supermajority?*

A party holds a supermajority of the parliament if they have more than 2/3 of seats. This gives them the power to make changes to the CONSTITUTION, which PAP has done so. Most notably, 
the [2016 minority president amendment](https://web.archive.org/web/20190606165027/https://www.channelnewsasia.com/news/singapore/elected-presidency-amendments-to-constitution-passed-in-parliame-7719282) 
& [2022 marriage definition amendment](https://www.channelnewsasia.com/singapore/s377a-repeal-constitution-amendment-marriage-definition-creative-arguments-3108831).

____________________________________________________________________________________________________________________________________________________________________________________

At this stage, I invite you to play with the interactive dashboard below, where you can compare actual and hypothetical GE results. The dashed lines mark the simple majority and supermajority thresholds.

{% raw %}
<style>
  .nogrc-dash { border: 1px solid var(--global-divider-color); border-radius: 12px; padding: 1rem 1rem 0.5rem; margin: 1.5rem 0; background: var(--global-card-bg-color, var(--global-bg-color)); position: relative; }
  .nogrc-controls { display: flex; flex-wrap: wrap; gap: 0.75rem; align-items: center; margin-bottom: 0.5rem; }
  .nogrc-group { display: flex; flex-wrap: wrap; gap: 0.25rem; align-items: center; }
  .nogrc-group-label { font-size: 0.8rem; font-weight: 600; opacity: 0.7; margin-right: 0.25rem; }
  .nogrc-btn { border: 1px solid var(--global-divider-color); background: transparent; color: var(--global-text-color); border-radius: 999px; padding: 0.15rem 0.6rem; font-size: 0.8rem; cursor: pointer; line-height: 1.4; }
  .nogrc-btn:hover { border-color: var(--global-theme-color); }
  .nogrc-btn.active { background: var(--global-theme-color); border-color: var(--global-theme-color); color: #fff; }
  .nogrc-charts { display: flex; flex-wrap: wrap; gap: 0.5rem; justify-content: center; }
  .nogrc-chart { flex: 1 1 320px; max-width: 420px; min-width: 280px; }
  .nogrc-chart h4 { text-align: center; font-size: 0.95rem; margin: 0.25rem 0 0; }
  .nogrc-legend { display: flex; flex-wrap: wrap; gap: 0.2rem 0.7rem; justify-content: center; font-size: 0.75rem; margin: 0.25rem 0 0.75rem; }
  .nogrc-legend span { white-space: nowrap; }
  .nogrc-dot { display: inline-block; width: 0.6em; height: 0.6em; border-radius: 50%; margin-right: 0.25em; }
  .nogrc-tip { position: absolute; pointer-events: none; background: var(--global-text-color); color: var(--global-bg-color); font-size: 0.75rem; padding: 0.25rem 0.5rem; border-radius: 6px; opacity: 0; transition: opacity 0.1s; z-index: 10; white-space: nowrap; }
  .nogrc-note { font-size: 0.7rem; opacity: 0.6; text-align: center; margin: 0 0 0.5rem; }
  .nogrc-seg { stroke: var(--global-bg-color); stroke-width: 1; cursor: pointer; }
  .nogrc-seg:hover { opacity: 0.8; }
  .nogrc-thresh { stroke: var(--global-text-color); stroke-dasharray: 4 4; stroke-width: 1; opacity: 0.5; }
  .nogrc-threshlabel { fill: var(--global-text-color); font-size: 11px; opacity: 0.6; }
  .nogrc-total { fill: var(--global-text-color); font-weight: 700; font-size: 22px; }
  .nogrc-totalsub { fill: var(--global-text-color); font-size: 11px; opacity: 0.6; }
</style>

<div class="nogrc-dash" id="nogrc-dash">
  <div class="nogrc-controls">
    <div class="nogrc-group" id="nogrc-years"><span class="nogrc-group-label">Year</span></div>
  </div>
  <div class="nogrc-controls">
    <div class="nogrc-group" id="nogrc-scens"><span class="nogrc-group-label">Scenario</span></div>
  </div>
  <div class="nogrc-charts">
    <div class="nogrc-chart">
      <h4 id="nogrc-title-l"></h4>
      <svg id="nogrc-svg-l" viewBox="0 0 400 215" width="100%" role="img" aria-label="Actual parliament seat distribution"></svg>
      <div class="nogrc-legend" id="nogrc-leg-l"></div>
    </div>
    <div class="nogrc-chart">
      <h4 id="nogrc-title-r"></h4>
      <svg id="nogrc-svg-r" viewBox="0 0 400 215" width="100%" role="img" aria-label="Hypothetical parliament seat distribution"></svg>
      <div class="nogrc-legend" id="nogrc-leg-r"></div>
    </div>
  </div>
  <p class="nogrc-note">Elected seats only (no NCMPs).</p>
  <div class="nogrc-tip" id="nogrc-tip"></div>
</div>

<script>
(function () {
  var DATA = {"1988": {"Actual": {"People's Action Party": 80, "Singapore Democratic Party": 1}, "AntiPAP": {"National Solidarity Party": 2, "People's Action Party": 63, "Singapore Democratic Party": 3, "Singapore Justice Party": 1, "United People's Front": 1, "Workers' Party": 11}, "ProPAP": {"National Solidarity Party": 1, "People's Action Party": 73, "Singapore Democratic Party": 2, "Workers' Party": 5}, "ProWinner": {"National Solidarity Party": 1, "People's Action Party": 73, "Singapore Democratic Party": 2, "Workers' Party": 5}}, "1991": {"Actual": {"People's Action Party": 77, "Singapore Democratic Party": 3, "Workers' Party": 1}, "AntiPAP": {"National Solidarity Party": 4, "People's Action Party": 68, "Singapore Democratic Party": 3, "Singapore Justice Party": 1, "Workers' Party": 5}, "ProPAP": {"National Solidarity Party": 1, "People's Action Party": 73, "Singapore Democratic Party": 3, "Workers' Party": 3}, "ProWinner": {"National Solidarity Party": 2, "People's Action Party": 73, "Singapore Democratic Party": 3, "Workers' Party": 3}}, "1997": {"Actual": {"People's Action Party": 81, "Singapore People's Party": 1, "Workers' Party": 1}, "AntiPAP": {"National Solidarity Party": 2, "People's Action Party": 68, "Singapore Democratic Party": 4, "Singapore People's Party": 1, "Workers' Party": 8}, "ProPAP": {"National Solidarity Party": 1, "People's Action Party": 74, "Singapore Democratic Party": 2, "Singapore People's Party": 1, "Workers' Party": 4}, "ProWinner": {"National Solidarity Party": 1, "People's Action Party": 74, "Singapore Democratic Party": 2, "Singapore People's Party": 1, "Workers' Party": 5}}, "2001": {"Actual": {"People's Action Party": 82, "Singapore Democratic Alliance": 1, "Workers' Party": 1}, "AntiPAP": {"People's Action Party": 74, "Singapore Democratic Alliance": 5, "Singapore Democratic Party": 4, "Workers' Party": 1}, "ProPAP": {"People's Action Party": 78, "Singapore Democratic Alliance": 2, "Singapore Democratic Party": 2, "Workers' Party": 1}, "ProWinner": {"People's Action Party": 78, "Singapore Democratic Alliance": 3, "Singapore Democratic Party": 2, "Workers' Party": 1}}, "2006": {"Actual": {"People's Action Party": 82, "Singapore Democratic Alliance": 1, "Workers' Party": 1}, "AntiPAP": {"People's Action Party": 66, "Singapore Democratic Alliance": 7, "Singapore Democratic Party": 2, "Workers' Party": 9}, "ProPAP": {"People's Action Party": 73, "Singapore Democratic Alliance": 4, "Singapore Democratic Party": 1, "Workers' Party": 6}, "ProWinner": {"People's Action Party": 73, "Singapore Democratic Alliance": 4, "Singapore Democratic Party": 1, "Workers' Party": 6}}, "2011": {"Actual": {"People's Action Party": 81, "Workers' Party": 6}, "AntiPAP": {"National Solidarity Party": 10, "People's Action Party": 51, "Reform Party": 4, "Singapore Democratic Alliance": 3, "Singapore Democratic Party": 4, "Singapore People's Party": 3, "Workers' Party": 12}, "ProPAP": {"National Solidarity Party": 6, "People's Action Party": 65, "Reform Party": 2, "Singapore Democratic Alliance": 2, "Singapore Democratic Party": 2, "Singapore People's Party": 2, "Workers' Party": 8}, "ProWinner": {"National Solidarity Party": 6, "People's Action Party": 64, "Reform Party": 2, "Singapore Democratic Alliance": 2, "Singapore Democratic Party": 2, "Singapore People's Party": 2, "Workers' Party": 9}}, "2015": {"Actual": {"People's Action Party": 83, "Workers' Party": 6}, "AntiPAP": {"National Solidarity Party": 4, "People's Action Party": 57, "People's Power Party": 1, "Reform Party": 3, "Singapore Democratic Alliance": 2, "Singapore Democratic Party": 4, "Singapore People's Party": 2, "Singaporeans First": 4, "Workers' Party": 12}, "ProPAP": {"National Solidarity Party": 2, "People's Action Party": 73, "Reform Party": 1, "Singapore Democratic Alliance": 1, "Singapore Democratic Party": 2, "Singapore People's Party": 1, "Singaporeans First": 2, "Workers' Party": 7}, "ProWinner": {"National Solidarity Party": 2, "People's Action Party": 72, "Reform Party": 1, "Singapore Democratic Alliance": 1, "Singapore Democratic Party": 2, "Singapore People's Party": 1, "Singaporeans First": 2, "Workers' Party": 8}}, "2020": {"Actual": {"People's Action Party": 83, "Workers' Party": 10}, "AntiPAP": {"National Solidarity Party": 4, "People's Action Party": 53, "Peoples Voice": 3, "Progress Singapore Party": 9, "Red Dot United": 2, "Reform Party": 2, "Singapore Democratic Alliance": 2, "Singapore Democratic Party": 4, "Singapore People's Party": 2, "Workers' Party": 13}, "ProPAP": {"National Solidarity Party": 2, "People's Action Party": 70, "Peoples Voice": 1, "Progress Singapore Party": 5, "Red Dot United": 1, "Reform Party": 1, "Singapore Democratic Alliance": 1, "Singapore Democratic Party": 2, "Singapore People's Party": 1, "Workers' Party": 9}, "ProWinner": {"National Solidarity Party": 2, "People's Action Party": 68, "Peoples Voice": 1, "Progress Singapore Party": 5, "Red Dot United": 1, "Reform Party": 1, "Singapore Democratic Alliance": 1, "Singapore Democratic Party": 2, "Singapore People's Party": 1, "Workers' Party": 11}}, "2025": {"Actual": {"People's Action Party": 87, "Workers' Party": 10}, "AntiPAP": {"People's Action Party": 61, "People's Alliance for Reform": 2, "People's Power Party": 1, "Progress Singapore Party": 5, "Red Dot United": 5, "Singapore Democratic Alliance": 2, "Singapore Democratic Party": 4, "Singapore People's Party": 1, "Singapore United Party": 1, "Workers' Party": 15}, "ProPAP": {"People's Action Party": 78, "Progress Singapore Party": 3, "Red Dot United": 2, "Singapore Democratic Alliance": 1, "Singapore Democratic Party": 2, "Singapore United Party": 1, "Workers' Party": 10}, "ProWinner": {"People's Action Party": 76, "Progress Singapore Party": 3, "Red Dot United": 2, "Singapore Democratic Alliance": 1, "Singapore Democratic Party": 2, "Singapore United Party": 1, "Workers' Party": 12}}};

  var PARTY = {
    "People's Action Party":          { abbr: "PAP", color: "#2563eb" },
    "Workers' Party":                 { abbr: "WP",  color: "#dc2626" },
    "Singapore Democratic Party":     { abbr: "SDP", color: "#eab308" },
    "Singapore People's Party":       { abbr: "SPP", color: "#7c3aed" },
    "Progress Singapore Party":       { abbr: "PSP", color: "#0891b2" },
    "National Solidarity Party":      { abbr: "NSP", color: "#16a34a" },
    "Reform Party":                   { abbr: "RP",  color: "#f97316" },
    "People's Power Party":           { abbr: "PPP", color: "#db2777" },
    "Red Dot United":                 { abbr: "RDU", color: "#8b5a2b" },
    "Singapore Democratic Alliance":  { abbr: "SDA", color: "#6b7280" },
    "Singaporeans First":             { abbr: "SF",  color: "#8b4513" },
    "Peoples Voice":                  { abbr: "PV",  color: "#ca8a04" },
    "United People's Front":          { abbr: "UPF", color: "#57534e" },
    "Singapore Justice Party":        { abbr: "SJP", color: "#ec4899" },
    "People's Alliance for Reform":   { abbr: "PAR", color: "#ff7f50" },
    "Singapore United Party":         { abbr: "SUP", color: "#4682b4" },
    "Independent":                    { abbr: "IND", color: "#737373" }
  };

  var YEARS = Object.keys(DATA);
  var SCENS = [["ProPAP", "Pro-PAP"], ["AntiPAP", "Anti-PAP"], ["ProWinner", "Pro-Winner"]];
  var state = { year: "2025", scen: "ProPAP" };

  var tip = document.getElementById("nogrc-tip");
  var dash = document.getElementById("nogrc-dash");

  function seatList(d) {
    return Object.keys(d).map(function (p) { return [p, d[p]]; })
      .sort(function (a, b) { return b[1] - a[1] || a[0].localeCompare(b[0]); });
  }

  function polar(cx, cy, r, ang) { return [cx + r * Math.cos(ang), cy - r * Math.sin(ang)]; }

  function segPath(cx, cy, r1, r2, a0, a1) {
    var large = (a0 - a1) > Math.PI ? 1 : 0;
    var p1 = polar(cx, cy, r2, a0), p2 = polar(cx, cy, r2, a1);
    var p3 = polar(cx, cy, r1, a1), p4 = polar(cx, cy, r1, a0);
    return "M" + p1[0].toFixed(2) + " " + p1[1].toFixed(2) +
      " A" + r2 + " " + r2 + " 0 " + large + " 1 " + p2[0].toFixed(2) + " " + p2[1].toFixed(2) +
      " L" + p3[0].toFixed(2) + " " + p3[1].toFixed(2) +
      " A" + r1 + " " + r1 + " 0 " + large + " 0 " + p4[0].toFixed(2) + " " + p4[1].toFixed(2) + " Z";
  }

  function showTip(evt, html) {
    tip.innerHTML = html;
    var rect = dash.getBoundingClientRect();
    tip.style.left = (evt.clientX - rect.left + 12) + "px";
    tip.style.top = (evt.clientY - rect.top - 10) + "px";
    tip.style.opacity = 1;
  }
  function hideTip() { tip.style.opacity = 0; }

  function draw(svgId, legId, titleId, title, dist, ref) {
    var svg = document.getElementById(svgId);
    var leg = document.getElementById(legId);
    document.getElementById(titleId).textContent = title;
    svg.innerHTML = ""; leg.innerHTML = "";
    var cx = 200, cy = 185, r1 = 78, r2 = 160;
    var list = seatList(dist);
    var total = list.reduce(function (s, x) { return s + x[1]; }, 0);
    var ang = Math.PI;
    list.forEach(function (item) {
      var party = item[0], seats = item[1];
      var meta = PARTY[party] || { abbr: party, color: "#999" };
      var a1 = ang - Math.PI * seats / total;
      var path = document.createElementNS("http://www.w3.org/2000/svg", "path");
      path.setAttribute("d", segPath(cx, cy, r1, r2, ang, a1));
      path.setAttribute("fill", meta.color);
      path.setAttribute("class", "nogrc-seg");
      var delta = "";
      if (ref && ref[party] !== seats) {
        var d = seats - (ref[party] || 0);
        delta = " (" + (d > 0 ? "+" : "") + d + " vs actual)";
      }
      var tipHtml = "<b>" + party + "</b><br>" + seats + " of " + total + " seats" + delta;
      path.addEventListener("mousemove", function (e) { showTip(e, tipHtml); });
      path.addEventListener("mouseleave", hideTip);
      svg.appendChild(path);
      ang = a1;
      var span = document.createElement("span");
      span.innerHTML = "<span class='nogrc-dot' style='background:" + meta.color + "'></span>" + meta.abbr + " " + seats;
      span.title = party + delta;
      leg.appendChild(span);
    });
    // majority and supermajority threshold lines (measured from the left, where the largest party starts)
    [[0.5, "½"], [2 / 3, "⅔"]].forEach(function (t) {
      var a = Math.PI * (1 - t[0]);
      var pA = polar(cx, cy, r1 - 4, a), pB = polar(cx, cy, r2 + 6, a);
      var line = document.createElementNS("http://www.w3.org/2000/svg", "line");
      line.setAttribute("x1", pA[0]); line.setAttribute("y1", pA[1]);
      line.setAttribute("x2", pB[0]); line.setAttribute("y2", pB[1]);
      line.setAttribute("class", "nogrc-thresh");
      svg.appendChild(line);
      var pT = polar(cx, cy, r2 + 16, a);
      var txt = document.createElementNS("http://www.w3.org/2000/svg", "text");
      txt.setAttribute("x", pT[0]); txt.setAttribute("y", pT[1]);
      txt.setAttribute("text-anchor", "middle");
      txt.setAttribute("class", "nogrc-threshlabel");
      txt.textContent = t[1];
      svg.appendChild(txt);
    });
    var tot = document.createElementNS("http://www.w3.org/2000/svg", "text");
    tot.setAttribute("x", cx); tot.setAttribute("y", cy - 18);
    tot.setAttribute("text-anchor", "middle");
    tot.setAttribute("class", "nogrc-total");
    tot.textContent = total;
    svg.appendChild(tot);
    var sub = document.createElementNS("http://www.w3.org/2000/svg", "text");
    sub.setAttribute("x", cx); sub.setAttribute("y", cy - 2);
    sub.setAttribute("text-anchor", "middle");
    sub.setAttribute("class", "nogrc-totalsub");
    sub.textContent = "seats";
    svg.appendChild(sub);
  }

  function scenLabel(key) {
    for (var i = 0; i < SCENS.length; i++) { if (SCENS[i][0] === key) return SCENS[i][1]; }
    return key;
  }

  function render() {
    var actual = DATA[state.year]["Actual"];
    var hypo = DATA[state.year][state.scen];
    draw("nogrc-svg-l", "nogrc-leg-l", "nogrc-title-l", state.year + " — Actual", actual, null);
    draw("nogrc-svg-r", "nogrc-leg-r", "nogrc-title-r", state.year + " — " + scenLabel(state.scen) + " (no GRCs)", hypo, actual);
    document.querySelectorAll("#nogrc-years .nogrc-btn").forEach(function (b) { b.classList.toggle("active", b.dataset.v === state.year); });
    document.querySelectorAll("#nogrc-scens .nogrc-btn").forEach(function (b) { b.classList.toggle("active", b.dataset.v === state.scen); });
  }

  function addBtns(holderId, values, key) {
    var holder = document.getElementById(holderId);
    values.forEach(function (v) {
      var val = Array.isArray(v) ? v[0] : v, label = Array.isArray(v) ? v[1] : v;
      var b = document.createElement("button");
      b.type = "button"; b.className = "nogrc-btn"; b.textContent = label; b.dataset.v = val;
      b.addEventListener("click", function () { state[key] = val; render(); });
      holder.appendChild(b);
    });
  }

  addBtns("nogrc-years", YEARS, "year");
  addBtns("nogrc-scens", SCENS, "scen");
  render();
})();
</script>
{% endraw %}


Using this dashboard, I compiled the following results regarding PAP's supermajority.

Pro-PAP: 

- 1988-2025: PAP holds a supermajority.

Anti-PAP:

- 1988-2006:    PAP holds a supermajority.
- 2011:         PAP misses supermajority by 7 seats, but wins 7 seats above majority.
- 2015:         PAP misses a supermajority by 3 seats, but wins 12 seats above majority.
- 2020:         PAP misses supermajority by 9 seats, but wins 6 seats above majority.
- 2025:         PAP misses supermajority by 4 seats, but wins 12 seats above majority.

So, even without GRCs, PAP would still have a supermajority in the best case, and still have a safe majority in the worst case.

____________________________________________________________________________________________________________________________________________________________________________________

__DISCUSSION__

*So, how well did the GRC system gerrymander?*
  - First set of results kinda showed that the GRC system tend to favour the winning party which, historically, has mostly been the PAP. So yes, the GRC system has been a good gerrymandering tool, which is inherently unfair.

*But an efficient one-party system is good for Singapore! If it means a stable government, gerrymandering can stay.*
  - Well, as we saw in the 'Pro-PAP' and 'Pro-Winner' scenarios, PAP would have been the ruling party with a supermajority anyway, even without GRCs.
  - So, yes, the PAP might have won extra seats due to the GRC system but they're kinda unnecessary, in terms of helping PAP maintain power.
  - Worst case ('Anti-PAP'), PAP might have lost their supermajority since 2011, but they would still have a majority and be able to pass laws easily. 
  - Sure, PAP wouldn't have been able to amend the constitution so easily. To that, I ask, should our Constitution be amended so easily? But that's for another time.

*Ok, what about the intended purpose of the GRC system? Has it ensured minority representation in parliament?*
  - Yes indeed, accusing the GRC system to only be a gerrymandering tactic isn't fair. We need to see if it did what it was designed to do. But how might we assess that? A good start would be to look at minority MPs before and after 1988 and see how that changed.
  - Looking at the 1984 GE results (right before GRCs were implemented), I count about 14 minority MPS out of 79 elected seats (17.72%), including ex-WP leader JB Jeyeratnam (more on this later...)
  - For comparison, there were 17 GRCs in 2020. So, effectively, GRCs guaranteed 17 minority MPs out of 93 elected seats (18.28%) in 2020, that’s barely an improvement from 1984 with no GRCs. To be fair, the 2020 GE saw 25 minority MPs out of 93. But still, the necessity of GRCs to ensure minority representation is questionable.
  - So… it didn’t seem like minorities had a problem of a lack of representation in parliament?

In short, I'd argue that the GRC system is not particularly helping PAP in retaining its seats, nor is it making a big difference in minority representation.

____________________________________________________________________________________________________________________________________________________________________________________

__FURTHER RANTS ABOUT GRC__
  
While writing this, I've thought of a few more issues with the GRC system.

*Complacent politicians*
- In GRCs, MPs can piggyback off political powerhouses. Going back to SMCs ensures competition for each and every seat, leading to more engaged and competent MPs.

*No. of seats*
- Number of seats in GRC is completely random and arbitrary. Like, if you're gerrymandering, at least make it less obvious; make the number of seats in each GRC the same.

*On minority quotas*
  - Also, do we really still need a quota to ensure minority representation in parliament? Some of our best politicians today are from the minority communities. Most notably, Tharman, Shanmugan, Pritam Singh and even historically, JB Jeyeratnam. It’s almost abit insulting to the minority community to say that affirmative action are needed to guarantee minority MPs. If anything, i think we can agree that these powerhouse ‘minority’ politicians had been hard-carrying their fellow Chinese GRC mates.
  - I think Singapore has moved past voting on racial grounds. Singaporeans can be trusted to look past race and vote based on merit.
  - The existence of a minority quota in parliament is admitting that power in government is still unfairly concentrated in the Chinese community, and I think that is not true.


____________________________________________________________________________________________________________________________________________________________________________________

__CONCLUSION__

For the record, I am supportive of the PAP. I highly value our unique “democratic one-party system”. Singapore is super lucky to have proper unrigged elections, while enjoying the efficiency of a one-party state.

Even so, I still think that the GRC system needs to go. It's unnecessarily unfair, and it's not even helping in promoting minority representation in parliament. 

Even if we still want a form of minority quota as a safeguard, why not mandate parties to have at least 20% of their candidates to be non-Chinese or something.

Removing or reforming the GRC system is a step Singapore can take towards a fairer democracy, without radically changing the status quo. 

And finally,

This is really not priority. I wrote this because I was bored.

Climate change and sustainable development are my priorities. My vote will go to the party with the better Net Zero Strategy for Singapore. 

