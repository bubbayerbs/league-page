<script context="module">
	export const prerender = true;
</script>

<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneOneOne, oneTwo, oneTwoOne, oneTwoTwo, oneTwoThree, oneTwoFour, oneTwoFive, oneThree;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne;
    let four, fourOne, fourTwo;
    let five, fiveOne;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree;

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
<h1 class="noUnderscore"><span style="color: #000000;">Leage of Ordinary Gentlemen</span></h1>
<h2 class="noUnderscore"><span style="color: #000000;">TABLE OF CONTENTS</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Contents</span></p>
<ol>
<li><span style="color: #000000;"> CONTENTS</span></li>
<li><span style="color: #000000;"> LEAGUE OVERVIEW</span></li>
<li><span style="color: #000000;"> INAUGURAL DRAFT</span></li>
<li><span style="color: #000000;"> ANNUAL ROOKIE DRAFT</span></li>
<li><span style="color: #000000;"> &nbsp;FREE AGENT ACQUISITION BUDGET (FAAB) </span></li>
<li><span style="color: #000000;"> LEAGUE RESOURCES</span></li>
<li><span style="color: #000000;"> TEAMS, DIVISIONS &amp; OWNERSHIP</span></li>
<li><span style="color: #000000;"> DUES</span></li>
<li><span style="color: #000000;"> CURRENT-YEAR PRIZE PAYOUTS</span></li>
<li><span style="color: #000000;"> STARTING LINEUP &amp; ROSTERS</span></li>
<li><span style="color: #000000;"> SCORING</span></li>
<li><span style="color: #000000;"> PLAYOFFS</span></li>
<li><span style="color: #000000;"> WAIVERS and FREE AGENCY</span></li>
<li><span style="color: #000000;"> TRADES</span></li>
<li><span style="color: #000000;"> OFFICIAL STATISTICS AND SCORING CHANGE</span></li>
<li><span style="color: #000000;"> ORPHAN TEAMS</span></li>
<li><span style="color: #000000;"> CHANGING LEAGUE RULES</span></li>
<li><span style="color: #000000;"> OWNER RESPONSIBILITIES</span></li>
<li><span style="color: #000000;"> ANTI-COMPETITIVE CONDUCT</span></li>
<li><span style="color: #000000;"> OWNERS SANCTIONS</span></li>
<li><span style="color: #000000;"> COMMISSIONER</span></li>
</ol>
<p><span style="color: #000000;"><strong>&nbsp;</strong></span></p>
<p><span style="color: #000000;"><strong>&nbsp;</strong></span></p>
<h2><span style="color: #000000;">2.&nbsp; &nbsp;&nbsp; LEAGUE OVERVIEW</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The purpose of these bylaws is to (1) ensure a fair and fun league for all owners, (2) promote the long-term viability of the league. If a rule is not explicitly stated, interpretations will consider these criteria and new rules will be voted on and subsequently documented in these bylaws. If this document disagrees with league site settings, site settings will prevail until corrected.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<ul>
<li><span style="color: #000000;">12 teams in 1 division playing a 13-game schedule with 3 weeks of playoffs.</span></li>
<li><span style="color: #000000;">24 roster spots = 288 players on rosters at a time during the regular season.</span></li>
<li><span style="color: #000000;">9 starters - QB / 2RB / 2WR / TE / 3 Flex (RB/WR/TE)</span></li>
</ul>
<p><span style="color: #000000;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 15 bench spots</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<ul>
<li><span style="color: #000000;">An initial 24-round startup draft will be conducted for the inaugural season</span></li>
<li><span style="color: #000000;">In future years a four (4) round rookie and to be arranged the week following the NFL Draft.</span></li>
<li><span style="color: #000000;">A 0.5 PPR scoring system.</span></li>
<li><span style="color: #000000;">Free agents acquired by Blind Bid Auction processed on Wednesdays. Dropped players and all free agents after game start will be placed on waivers. Dropped players will spend a minimum of 48 hours on the waiver wire. After waivers, the remaining free agents are available by First Come First Serve claims.</span></li>
<li><span style="color: #000000;">Three-week, six-team playoff structure running NFL weeks 14-16. Two top teams by record get a bye.</span></li>
<li><span style="color: #000000;">Trading prohibited from end of NFL Week 10 to the start of NFL Week 17.</span></li>
<li><span style="color: #000000;">$50 annual league dues to be paid by the deadline set on league safe</span></li>
<li><span style="color: #000000;">Prize pools with 100% payouts.</span></li>
<li><span style="color: #000000;">The league is designed to run for decades with smooth ownership transitions if necessary. Rules may be modified by league vote to achieve overarching goals</span></li>
</ul>
<p><span style="color: #000000;"><strong>&nbsp;</strong></span></p>
<h2><span style="color: #000000;"><strong>3. </strong>INAUGURAL DRAFT</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The league will initially select players via a 24-round all-inclusive startup draft</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">All current NFL players will be available for selection</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Trading inaugural draft picks, players, and future draft picks is not allowed during the draft.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Initial draft position will be selected via randomization in Sleeper App</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The draft will be a snake style draft with 60 seconds per pick</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<h2 style="text-align: left;"><span style="color: #000000;">4.&nbsp;&nbsp; ANNUAL ROOKIE DRAFT</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Draft order for subsequent seasons will be set by reverse standings from the regular season for non-playoff teams. Draft order for the playoff teams will be reverse order of the final standings after the play-offs.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">League Winner is pick #12</span></p>
<p><span style="color: #000000;">League runner up is pick #11</span></p>
<p><span style="color: #000000;">Etc...</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Prior to the Rookie Draft, the rosters will be expanded by the amount of the highest number of picks owned by a team. They will be reduced after the final game of week 3 of the preseason. Teams without that many picks will have empty roster spots they can fill by bidding on free agents immediately following the conclusion of the draft.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">ROOKIE DRAFT</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The subsequent yearly rookie drafts will be completed within a month of the NFL draft.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Most league rosters will exceed the mandated roster limit at the end of the Rookie draft and free agent&nbsp; period. All teams are required to reduce their rosters to the mandated limit by the end of the final week 3 NFL preseason game.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;"><strong>&nbsp;</strong></span></p>
<p><span style="color: #000000;"><strong>&nbsp;</strong></span></p>
<h2><span style="color: #000000;">5. FREE AGENT ACQUISITION BUDGET (FAAB)</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The Free Agent Acquisition Budget system (also known as a FAAB) allocates a budget of fake "money" to each team before the season for them to spend on free agent players on waivers. Waiver claims are awarded to the highest bidder instead of the worst-ranked team. If there is a tie, the player will be awarded to the team with the worst rank. Each time a claim is processed, the bid amount is deducted from the remaining budget.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<ul>
<li><span style="color: #000000;">FAAB Implementation</span>
<ul>
<li><span style="color: #000000;">Each team will have a $100 budget per season for FAAB.</span></li>
<li><span style="color: #000000;">In the 2018-19 season, following the draft, all transactions will be FAAB.</span></li>
<li><span style="color: #000000;">In the 2019-20 season, there will be a separation between the rookie draft and FA acquisitions in the offseason. FA&rsquo;s will open for a blind bid period separately from the rookie draft and only rookies will be available to be drafted.</span></li>
</ul>
</li>
</ul>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<h2><span style="color: #000000;">6. LEAGUE RESOURCES</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<ul>
<li><span style="color: #000000;">Sleeper App</span></li>
</ul>
<p><span style="color: #000000;">o&nbsp;&nbsp; Chat client is integrated in sleeper</span></p>
<ul>
<li><span style="color: #000000;">League Dues <strong>https://www.leaguesafe.com/join/3873881 </strong></span></li>
</ul>
<h2><span style="color: #000000;">7. TEAMS, DIVISIONS &amp; OWNERSHIP</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The League will consist of 12 teams in 1 division. Schedule will be set by Sleeper app.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">If an owner should choose not to return, the Commissioner will find a replacement owner using whatever means necessary to keep the league stable.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<h2><span style="color: #000000;">8. DUES</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">League dues are $50 per season per team and are non-refundable.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">There will be a late fee of $20.00. $10.00 will go to league safe and $10.00 will go to the prize pool. Any additional prize money gained this way will go to the league champion.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">If the owner has traded away future picks beyond next season, 100% of those dues (for that advanced season) must be paid before the owner can participate in any draft. Dues must be paid by the league deadline.</span></p>
<p><span style="color: #000000;">If an owner leaves the league for any reason, his dues are forfeit to the prize pool and he will have no claim to them in any way. This includes if he finds a replacement owner, unless the replacement owner is willing to reimburse him and pay the dues required to join the league.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">If an owner cannot reasonably meet the dues deadline, they must notify the Commissioner and make alternate arrangements. Failure to do so will result in the forfeiture of their team at the end of the season currently paid up to and seeking of a replacement owner. Don&rsquo;t be that guy.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The league finances are tracked via league safe</span></p>
<p>&nbsp;</p>
<h2><span style="color: #000000;">9. CURRENT-YEAR PRIZE PAYOUTS</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The payout structure is based on dues of a $50 per team per season.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">League Champion&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $400</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">League Runner-Up&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $150</span></p>
<p><span style="color: #000000;">2<sup>nd</sup> Runner-Up&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $50</span></p>
<h2><span style="color: #000000;">10. STARTING LINEUP &amp; ROSTERS</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">League rosters will consist of no more than 24 players during a season. This will be extended by the appropriate amount prior to the Rookie draft and then reduced at the end of the final week 3 preseason game. The IR slots do not take up a roster slot, if you have IR eligible players.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Teams are required to set a full starting lineup each regular season week during the regular season and, if applicable, each playoff week.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">A starting lineup shall consist of 8 players:</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<ul>
<li><span style="color: #000000;">1 Quarterback (QB)</span></li>
<li><span style="color: #000000;">2 Running Back (RB)</span></li>
<li><span style="color: #000000;">2 Wide Receivers (WR)</span></li>
<li><span style="color: #000000;">1 Tight End (TE)</span></li>
<li><span style="color: #000000;">3 Flex (RB/WR/TE)</span></li>
</ul>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Player positions are determined by the Sleeper App. No restrictions are currently in place.</span></p>
<p><span style="color: #000000;">Owners should be aware that Sleeper may change a player&rsquo;s position at any time pursuant to that player&rsquo;s NFL team changing their position, e.g switching a player who was previously a wide receiver (WR) that of a running back (RB). These changes shall not be overruled by the League under any circumstances. These changes become effective when they are made by Sleeper.</span></p>
<p><span style="color: #000000;">Owners are responsible for assessing the possibility that a given player may change positions before acquiring the player.</span></p>
<p><span style="color: #000000;">Players are not locked into a team&rsquo;s starting lineup until the game in which the player is participating has kicked off, at which point they may not be removed.</span></p>
<p><span style="color: #000000;">Owners who know they will be unavailable to set their team&rsquo;s lineup are shall use their best efforts to inform the Commissioner and designate another owner or the Commissioner to set or change their team&rsquo;s lineup. Should a lineup not be set by a team, barring extreme circumstances, too bad, deal with it. In this case, the Commissioner reserves the right to submit an alternate competitive lineup if deemed necessary in order to maintain league integrity (ie: no team starting 5 injured players will be allowed)</span></p>
<p><span style="color: #000000;"><strong>&nbsp;</strong></span></p>
<h2><span style="color: #000000;">11. SCORING</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Regular season games that are tied will officially be recorded as a tie.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<h2><span style="color: #000000;">12. PLAYOFFS</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Playoffs will take place during Weeks 14-16 of the NFL season. The six playoffs teams will be seeded by the following:</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<ol>
<li><span style="color: #000000;">Overall Record</span></li>
<li><span style="color: #000000;">Points For</span></li>
</ol>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The two teams who make it to the final will face off in the championship to win the league and be crowned The Most Ordinary Gentleman.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Tiebreakers for all standings and playoff spots and will be determined by Sleeper App</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The top two seeds will receive a bye in NFL Week 14 / Playoff Round 1.There will be no ties in the Playoffs. Ties will be resolved by:</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<ol>
<li><span style="color: #000000;">Most Starter TDs</span></li>
<li><span style="color: #000000;">Highest Individual Starter Score</span></li>
<li><span style="color: #000000;">Bench Points Total</span></li>
</ol>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;"><strong>&nbsp;</strong></span></p>
<h2><span style="color: #000000;">13. WAIVERS and FREE AGENCY</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Any player not on a league roster is considered a free agent. Free agents may be claimed by owners during one of two periods each week: The Waivers Period and the First Come, First Served (FCFS) Period. Free agents whose NFL teams have participated in a game and players dropped since the last Waiver Period ended are not eligible to be claimed until the following Waiver Period.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The Waiver Period consists of owners placing Waiver Requests. This period begins after the end of the final NFL game of a week and the bidding is adjudicated Wednesdays at 3 AM ET (approximately). A player to be dropped (if desired or necessary to meet roster requirements) can be identified when the waiver request on a free agent is placed.</span></p>
<p>&nbsp;</p>
<h2><span style="color: #000000;">14. TRADES</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Trading is the lifeblood of a dynasty league. Limits on trading shall be rare, and when in doubt, a trade will be allowed.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Trading is only permitted by teams who are paid in full for the current season.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Trades will not be allowed from the end of week 10 until the start of week 17</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Once a trade has been proposed and accepted via the app or site, it cannot be rescinded except for owner error. If a trade was offered or accepted in error, the owner making the error must notify the Commissioner and the owner of the other team immediately (i.e. within 5 minutes of the trade's acceptance) to request that the trade be voided. Trades will only be revoked because of legitimate owner error that is reported in a timely manner; owners may not request that a trade be voided due to buyer&rsquo;s remorse, seller&rsquo;s remorse or failure to perform due diligence before proposing or accepting a trade. The Commissioner reserves the right to allow a trade to stand if an owner's claim of error is not deemed to be credible.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Conditional trades involving players or draft picks are not permitted.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Teams may not impose "post-trade conditions" where a team trades a player subject to a requirement that the other team perform or refrain from a performing a specified action relating to the player after the trade is completed.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Example: An owner may not trade a player with the condition that the player be waived immediately, or that the player must not be subsequently traded to a particular team, or that the player is benched when playing the team currently trading the player.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Teams may not make offseason trades unless they have paid their league fees for the upcoming season. Trades will not be processed unless all owners involved in the transaction have paid league fees.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Owners shall use their best efforts to respond promptly (within 24 hours) to trade offers from other owners. Owners are encouraged to check for trade offers every time they log on to the site, and owners should immediately reject a trade they deem unacceptable.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">All trades are subject to veto by a majority league vote. The period to vote will last two days and begin after a trade has been accepted.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Occasionally, rapidly changing information is not available to both sides of a trade, particularly when the trade was opened before the news was known. In this case, it is recommended that both sides of the trade inform each other of the material information that has changed before acting on the trade. While trading on rapidly changing information can benefit an owner short-term, it&rsquo;s a bush-league move and that owner will be surely be shunned.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<h2><span style="color: #000000;">15. OFFICIAL STATISTICS AND SCORING CHANGE</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Every week after all NFL games are played and all fantasy scores are calculated, the Elias Sports Bureau reviews all NFL games for the purposes of locating and calculating any necessary corrections to the official team and player statistics compiled during each game. These corrections will be applied to league scores when they are released by Elias and the NFL, which is usually on Wednesday morning.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Owners should be aware that the outcome of a game that was tied or won by a small margin may change after the Elias Sports Bureau&rsquo;s scoring corrections are applied. Sleeper App will apply the official scoring corrections without exception, and owners may not appeal the changed scoring, the changed outcome of a game, or request that the official scoring corrections be disregarded.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<h2><span style="color: #000000;">16. ORPHAN TEAMS</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">An owner may retire from the league in good standing. Retirement must be announced before the conclusion of Week 17 of the NFL season to retire in good standing. Upon announcement of an owner&rsquo;s retirement, a replacement owner will be sought and they will be responsible for the upcoming season&rsquo;s league fee if it has not already been paid by the retiring owner. Once an owner announces their retirement, they may not make any trades for the remainder of the season. A retirement announcement is irrevocable, but an owner who retires in good standing may be considered for reinstatement to the league after an absence of at least one full season.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Aside from retirement, orphan teams can be created through the following circumstances:</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<ul>
<li><span style="color: #000000;">Quitting owner: If an owner publicly declares they are quitting the league on the sleeper app chat, the team is immediately classified as an orphan team and the Commissioner will assume control of the team until a replacement owner is found. Public, written "I quit" declarations are permanent and irrevocable; quitting owners are permanently barred from seeking reinstatement to the league.</span></li>
<li><span style="color: #000000;">Abandoning owner: A team is considered abandoned during the season if an owner fails to set a lineup for two consecutive games.</span></li>
<li><span style="color: #000000;">Removal of an owner for failure to pay league fees by the deadline.</span></li>
<li><span style="color: #000000;">Removal of an owner for cheating or anti-competitive conduct</span></li>
<li><span style="color: #000000;">Removal of an owner or multiple owners for collusion between teams</span></li>
<li><span style="color: #000000;">Removal of an owner or owners for offering and/or accepting bribes (i.e. real-life money or any other real-life consideration) as an incentive to complete league trades, league transactions or influence league activity of any kind.</span></li>
<li><span style="color: #000000;">Removal of an owner for repeated failure to return league emails and trade offers in a timely manner.</span></li>
<li><span style="color: #000000;">Removal of an owner for conduct or transactions detrimental to the league</span></li>
<li><span style="color: #000000;">Removal of an owner for repeated failure to adhere to league rules or abide by Commissioner rulings.</span></li>
<li><span style="color: #000000;">Removal of an owner for repeated failure to communicate with owners or the Commissioner in a mature or respectful manner.</span></li>
</ul>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">If a team is orphaned during the season, the Commissioner will set that team&rsquo;s roster for the remainder of that season. The stated preference is that the Commissioner setting the orphan team&rsquo;s roster not be scheduled to play that orphan team during the season. In the event the Commissioner&rsquo;s team does play the orphan team during the season, another league member shall set the orphan team&rsquo;s lineup for that game.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Payouts won by a team orphaned during a regular season will be put into the following year&rsquo;s pool to be distributed as extra prize winnings.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<h2><span style="color: #000000;">17. CHANGING LEAGUE RULES</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Proposed rules or scoring changes must be communicated to all owners. This may be achieved by posting in Sleeper App league chat</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">For league changes: 7 of 12 owners voting in favor the change will result in a successful change.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">For votes with more than one option: If no majority is achieved, the option with the most votes will succeed. If no option receives the single most votes, the proposal will fail. The proposer will be given one additional opportunity to submit a variation of this rule change in this calendar year in order to achieve the required number of votes.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Changes will be implemented in the following league year unless otherwise specified.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;"><strong>&nbsp;</strong></span></p>
<p><span style="color: #000000;"><strong>&nbsp;</strong></span></p>
<p><span style="color: #000000;"><strong>&nbsp;</strong></span></p>
<p><span style="color: #000000;"><strong>&nbsp;</strong></span></p>
<p><span style="color: #000000;"><strong>&nbsp;</strong></span></p>
<h2><a name="_Toc78808194"></a><span style="color: #000000;">18. OWNER RESPONSIBILITIES</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Preparation is the key to short-term survival and long-term success in a dynasty league. Owners are expected to be prepared for the annual drafts and to monitor NFL activities throughout the regular season and offseason, including but not limited to up-to-date knowledge of player injuries and which players and coaches have changed teams or retired.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Participation is the lifeblood of this league, even more than rivalries, free agents, statistics or drafts. Maintaining a sense of community and respect among owners is vital to the league's long-term survival and owners&rsquo; long-term enjoyment.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">In addition to the above, owners are also required to adhere to the following responsibilities on behalf of their teams. An owner who fails to adhere to one or more of these responsibilities will be subject to Commissioner's sanctions:</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<ul>
<li><span style="color: #000000;">Owners are responsible for ensuring their team has current lineups</span></li>
<li><span style="color: #000000;">Owners are responsible for knowing and following the rules and schedule listed in these bylaw as well as on Sleeper App.</span></li>
<li><span style="color: #000000;">Owners are responsible for responding to emails or private messages from the Commissioner &amp; other owners in a timely manner.</span></li>
<li><span style="color: #000000;">Owners are responsible for taking part in league votes</span></li>
<li><span style="color: #000000;">Owners are responsible for regularly accessing Sleeper App or site.</span></li>
<li><span style="color: #000000;">Owners are responsible for responding to trade offers in a timely manner.</span></li>
<li><span style="color: #000000;">Owners are responsible for participating in all required league functions and scheduled events, whether they occur in the regular season or offseason.</span></li>
<li><span style="color: #000000;">Owners are responsible for submitting weekly lineups.</span></li>
<li><span style="color: #000000;">Owners are responsible for notifying a Commissioner if they will be away for an excessive period of time, so arrangements can be made to set lineups and/or manage the team during that owner&rsquo;s absence.</span></li>
</ul>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<h2><span style="color: #000000;">19. ANTI-COMPETITIVE CONDUCT</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Anti-competitive conduct is defined as owners or teams engaging in conduct that prevents, reduces or otherwise negatively affects the natural competition and well-being of the league. The following anticompetitive actions are strictly prohibited. Violations of these rules shall be determined by the Commissioner and the Commissioner may subject an owner or owners to sanctions, which may include immediate removal from the league.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;"><strong>Tanking:</strong> Owners are expected to use their best efforts to set their best available lineup every week of competition, even if they are well out of playoff contention. Tanking is defined as failing to submit their best available starting lineup either intentionally or through indifference. It is understood that owners may play hunches on who to start and won&rsquo;t always start the player who scores the most points.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">However, an owner who knowingly benches star players or obvious starting players in favor of players who are marginal, clearly injured, benched, suspended or on their bye weeks shall be subject to Commissioner's sanctions for a first offense. A second offense shall result in that owner&rsquo;s immediate removal from the league.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;"><strong>Anti-competitive Trades:</strong> Owners may not make trades that result in worsening their own team to stock another team playing a third team they want or need to lose. Owners may not make trades if they do not intend to return to the league for the next season. If an owner does not intend to return to the league, they should announce their retirement publicly and play out the season using their best efforts; the incoming replacement owner should be permitted to inherit an intact team and make their own trades and roster decisions. The Commissioner may retroactively void a trade if there is clear and convincing evidence that the trade was prohibited on anti-competitive grounds that were not apparent at the time of the trade.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;"><strong>Collusion:</strong> Collusion is defined as two or more owners deciding and/or acting in concert to influence the results of league activities such as game outcomes, draft standing or player availability. Any unsportsmanlike conduct coordinated between two or more owners is collusion, as is a team&rsquo;s trading to consolidate better players on one team and/or agreeing to share payouts by acting in concert. Trading a player with the condition that he be traded back would be considered collusion, and against the rules. Owners engaging in collusion are subject to penalties and/or immediate removal from the league.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;"><strong>Dumping:</strong> An owner who, without good reason, cuts players from their team who are obviously valuable is subject to Commissioner's sanctions. If an owner continues to dump players after sanctions are imposed, the owner shall be removed from the league. It is understood that teams can and will drop &ldquo;borderline&rdquo; players from their rosters but dropping obvious fantasy starters or large amounts of average players in an attempt to increase draft position, make players available to other by way of collusion or sabotage the integrity of the league shall not be tolerated.</span></p>
<p><span style="color: #000000;"><strong>Indifference:</strong> An owner who fails to submit a starting lineup or fails to replace inactive players who are injured, benched, suspended or on their bye week is subject to Commissioner&rsquo;s sanctions for a first offense. An owner who fails to set a starting lineup due to indifference twice in the same season is subject to removal from the league</span></p>
<p><span style="color: #000000;">The Commissioner will be the final authority on all sanctions only to be overturned by a unanimous vote by all other owners on a league wide poll.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<h2><span style="color: #000000;">20. OWNERS SANCTIONS</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">If at any time an owner violates league rules or engages in conduct judged by the Commissioner as detrimental to the league in any way, the Commissioner has both the authority and obligation to act to protect the league and to act in its best interests. The Commissioner may impose sanctions against an owner or team found to have violated league rules or conducted themselves in a manner detrimental to the league. All Commissioner Committee members are subject to the same penalties as the rest of the league. It is expected that Commissioner&rsquo;s use of sanctions will be rare, appropriate to the offense, proportionate to its severity, and not undertaken lightly.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Commissioner's sanctions include but are not limited to the following:</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<ul>
<li><span style="color: #000000;">Public warning</span></li>
<li><span style="color: #000000;">Deductions from overall and divisional point totals</span></li>
<li><span style="color: #000000;">Retroactive cancellation of trades, with the possibility of forfeits declared for any games affected by the cancelled trade</span></li>
<li><span style="color: #000000;">Suspension of waiver rights for a specified period</span></li>
<li><span style="color: #000000;">Suspension of trading rights for a specified period</span></li>
<li><span style="color: #000000;">Suspension or benching of players for a specified period</span></li>
<li><span style="color: #000000;">Suspension of an owner for a specified period, with their team forfeiting all games occurring during the suspension</span></li>
<li><span style="color: #000000;">Forced waiving of players</span></li>
<li><span style="color: #000000;">Loss of future draft picks</span></li>
<li><span style="color: #000000;">Loss of Waiver Priority</span></li>
<li><span style="color: #000000;">Removal of an owner from the league</span></li>
</ul>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">Any combination of the above sanctions deemed appropriate by the Commissioner.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The Commissioner may impose and enforce sanctions at any time, including retroactively. The Commissioner may use an owner&rsquo;s past record in considering the length or severity of sanctions.</span></p>
<p><span style="color: #000000;"><strong>&nbsp;</strong></span></p>
<h2><a name="_Toc78808197"></a><span style="color: #000000;">21. COMMISSIONER</span></h2>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The Commissioner will act in good faith and at all times in the best interest of the league to maintain a fun, fair, competitive environment.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The Commissioner will have the final authority over all actions, activities, votes, rule changes, and any other thing necessary to effectively run a good league while respecting the rights of its owners. In the rare instance that a situation arises which is not covered by the bylaws, the Commissioner reserves the right to rule on the issue in the best interest of the league. This includes times when a rule is not explicitly stated (such as a tiebreaker) but must be ruled on to move league business forward. Commissioner rulings are final, binding and cannot be appealed. The intent of this clause is not to grant arbitrary, unchecked Roger Goodell-like power, but rather to empower and require the Commissioner via these bylaws to take fair and necessary executive action for the good of the league.</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The league shall be governed by the Commissioner</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">The role of the Commissioner is to:</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
<ul>
<li><span style="color: #000000;">Maintain league logistics</span></li>
<li><span style="color: #000000;">Help set lineups and perform team/roster moves for owners if requested</span></li>
<li><span style="color: #000000;">Facilitate drafts</span></li>
<li><span style="color: #000000;">Collect league dues and facilitate payouts</span></li>
<li><span style="color: #000000;">Ensure that actions that require dues to be paid are completed only if dues are up to date</span></li>
<li><span style="color: #000000;">Ensure that the league dues are paid</span></li>
<li><span style="color: #000000;">Apply penalties for owner misconduct, rules violations, or actions against the league</span></li>
<li><span style="color: #000000;">Void trades if rules are clearly violated (trade backs, roster limits, etc.)</span></li>
<li><span style="color: #000000;">Control abandoned or otherwise orphaned franchises and seek new ownership</span></li>
</ul>
<p><span style="color: #000000;">&nbsp;</span></p>
<p><span style="color: #000000;">&nbsp;</span></p>
</div>
