Harvest Records
========

Data Source:<br>

These datasets come from DFO's summary commercial statistics page. DFO presents the data by year; these files contain data by data type.<br>
http://www.pac.dfo-mpo.gc.ca/stats/comm/summ-somm/index-eng.htm
<br>
<br>

Files and Column headers:<br>

<b>AllSpp_weight_monthly_kg.csv</b>
<li>
<ul><b>SPECIES_GROUP</b> - category of species harvested (e.g. herring spawn on kelp is listed under herring)</ul>
<ul><b>SPECIES</b> - species that was harvested</ul>
<ul><b>GEAR</b> - type of gear used to harvest the fish</ul>
<ul><b>MONTH</b> - month of harvest</ul>
<ul><b>VALUE</b> - weight harvested, in kilograms</ul>
<ul><b>YEAR</b> - year of harvest</ul>
</li>
<br><br>
<b>Salmon_value_weekly.csv</b>
<li>
<ul><b>WEEK</b> - original DFO date listing</ul>
<ul><b>GEAR</b> - type of gear used to harvest the fish</ul>
<ul><b>SPECIES</b> - species harvested</ul>
<ul><b>VALUE</b> - value of harvest, in dollars (unadjusted)</ul>
<ul><b>WEEKSTART</b> - start date of week (not part of original dataset)</ul>
<ul><b>DFOWEEKNUM</b> - DFO code for the week in question, taken from the WEEK column - first digit is month (2 digits if Oct-Dec), last digit is week in that month</ul>
<ul><b>YEAR</b> - year of harvest</ul>
<ul><b>MONTH</b> - month of harvest (not part of original dataset)</ul>
</li>
<br><br>
<b>Salmon_weight_annual_1000tonnes.csv</b>
Post-1950 data come from "<a href="http://www.pac.dfo-mpo.gc.ca/stats/comm/summ-somm/index-eng.htm">Landed Weight by Species and Gear, 1951-1995</a>"<br>
Data to 1950 come from "<a href="http://www.statcan.gc.ca/pub/11-516-x/sectionn/N12_24-eng.csv">Statistics Canada Series N12-24: Quantities of fish landed, by region and major species, 1869 to 1975</a>"
<li>
<ul><b>YEAR</b> - year of harvest</ul>
<ul><b>VALUE</b> - weight harvested, in thousands of metric tonnes</ul>
<ul><b>WHAT</b> - species harvested</ul>
</li>
<br><br>
<b>Salmon_weight_weekly_kg.csv</b>
<li>
<ul><b>WEEK</b> - original DFO date listing</ul>
<ul><b>GEAR</b> - type of gear used to harvest the fish</ul>
<ul><b>SPECIES</b> - species harvested</ul>
<ul><b>WEIGHT</b> - weight harvested, in kilograms</ul>
<ul><b>START</b> - start date of week (not part of original dataset)</ul>
<ul><b>DFOWEEKNUM</b> - DFO code for the week in question, taken from the WEEK column - first digit is month (2 digits if Oct-Dec), last digit is week in that month</ul>
<ul><b>YEAR</b> - year of harvest</ul>
<ul><b>MONTH</b> - month of harvest (not part of original dataset)</ul>
</li>
