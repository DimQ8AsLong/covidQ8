<h1>MAIN DATABASE</h1>
<h6>q8covid19-d071c</h6>

<h1>PART I -- DATA</h1>
this can be found in:
<h6>"NEWSOURCE"</h6>
<h6>......|__ 20200422 <- key is date formatted yyyyMMdd __STRING__</h6>
<h6>................|__ sdclsdcmncfd <- random key generated for each case based on nationality on same day __STRING__</h6>
<h6>.............................|__ count total number of affected __INT__</h6>
<h6>.............................|__ country country he/she came from __STRING__</h6>
<h6>.............................|__ isKuwaiti if 1 means kw if 0 nkw* __INT_</h6>
<h6>.............................|__ isTravelled if 1 means first catcher to COVID19 if 0 he contacted some1 with covid19 __INT__</h6>
<h6>.............................|__ nationality nationality of patient __STRING__</h6>
  
  <h2> for each day there is one key only but inside each day there might be several keys so you need to count them</h2>
  <h2> also you need to count each case based on nationality, isKuwaiti, isTravelled, country</h2>

<h2> i will provide the list of countries so you can make and array of and update values based on country name then removing the zero values from it. </h2>

<h1> PART II -- DATA </h1>
this can be found in:
<h6>"GENERAL"</h6>
<h6>active total remaining cases __INT__</h6>
<h6>deceased total dead ppl __INT__</h6>
<h6>icu total ppl in intensive care unit __INT__</h6>
<h6>lastUpdate date and time __STRING__</h6>
<h6>recovered total recovered ppl __INT__</h6>
<h6>checker 1 is on 0 is of (this for ANDROID push to playstore) __INT__ </h6>
<h6>newChecker 1 is on 0 is of (this for IOS push to Appstore) __INT__ </h6>

<h2>to get the percentage formula indicator / total number </h2>
<h2>only icu indicator is divided by active cases</h2>
