<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneOneOne, oneTwo, oneTwoOne, oneTwoTwo, oneTwoThree, oneTwoFour, oneTwoFive, oneThree;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne;
    let four, fourOne, fourTwo;
    let five, fiveOne;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree;
    let eight, eightOne, eightTwo, eightThree;
    let append, appendOne, appendTwo, appendThree, appendFour;

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
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
    <h1 class="noUnderscore">RUGGS & RICE DRIVING ACADEMY LEAGUE CONSTITUTION</h1>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(one)}>Section 1: Roster</h3>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneOne)}>1.1 Positional Breakdown</h4>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneOneOne)}>1.1.1 Position Maximums</h5>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneTwo)}>1.2 Trading</h4>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneTwoOne)}>1.2.1 Trade Collusion</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneTwoTwo)}>1.2.2 Lending Players Prohibition</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneTwoThree)}>1.2.3 Trade Deadline</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneTwoFour)}>1.2.4 Trade Restrictions</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneTwoFive)}>1.2.5 Veto/Trade Process</h5>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneThree)}>1.3 Waiver Wire</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(two)}>Section 2: Drafting</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoOne)}>2.1 Draft Order</h4>
<!--        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoTwo)}>2.2 Rookie Drafts</h4>   -->
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoTwo)}>2.2 Draft Day Trades</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(three)}>Section 3: Scoring System</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeOne)}>3.1 Voting on Scoring System</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>Section 4: Postseason</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourOne)}>4.1 Playoffs</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourTwo)}>4.2 Playoff Tiebreakers</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>Section 5: Tanking Policy</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>5.1 League Tanking Policy</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>Section 6: Replacing Managers</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixOne)}>6.1 Removing Managers</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>6.2 Replacing Managers</h4>
<!--        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixThree)}>6.3 Replacement Incentive</h4>   -->

    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 7: League Finances</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenOne)}>7.1 League Dues</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenTwo)}>7.2 Payout</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenThree)}>7.3 Raising Dues</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(eight)}>Section 8: Keeper Rules</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightOne)}>8.1 Declaring Keepers</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightTwo)}>8.2 Keeper Values</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightThree)}>8.3 Keeper Eligibility</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(append)}>Appendix: Amendments</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(appendOne)}>A.1 IR Expansion</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(appendTwo)}>A.2 Draft Pick Trade Deadline</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(appendThree)}>A.3 Keeper Pick Designation</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(appendFour)}>A.4 Offseason Keeper Trade Ban</h4>


    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>Section 1 Roster Breakdown</h2>
    
    <h3 class="subSectionHeading" bind:this={oneOne}>1.1 Positional Breakdown</h3>
    
    <p>28 Total Players</p>
    
    <p class="underscore">Starters</p>
    <ul>
        <li>QB</li>
        <li>RB</li>
        <li>RB</li>
        <li>WR</li>
        <li>WR</li>
        <li>TE</li>
        <li>FLEX (RB/WR/TE)</li>
        <li>FLEX (RB/WR/TE)</li>
        <li>D/ST</li>
        <li>K</li>
    </ul>
    
    <p>6 Bench</p>

    <p>2 IR Spots (Player must be labeled as IR, Out, or Covid in the Sleeper App)</p>
    
        <h4 bind:this={oneOneOne}>1.1.1 Position Maximums</h4>
        <div class="subBlock">
            <p>There will be no positional limits for rosters as a whole. If a manager wants to hold 6 QBs and limit their own RB/WR depth, they are free to do so (at their own detriment).</p>
        </div>
<!--
        <div class="subBlock">
            <table class="positionMaximums">
                <tr><td>QB</td><td class="right">3 active, 5 total</td></tr>
                <tr><td>RB</td><td class="right">20</td></tr>
                <tr><td>WR</td><td class="right">20</td></tr>
                <tr><td>TE</td><td class="right">10</td></tr>
                <tr><td>D/ST</td><td class="right">3</td></tr>
                <tr><td>K</td><td class="right">3</td></tr>
            </table>
        </div>
-->

    <h3 class="subSectionHeading" bind:this={oneTwo}>1.2 Trading</h3>
    
    <p>Trading of players and draft picks are allowed. Draft picks can only be included in trades if participating parties are paid in for the year(s) in which draft picks are included. This will prevent anyone from nuking their team (and the league) with no intentions of returning. Trades will process after 24 hours and will be canceled if vetoed or under investigation for collusion. Tradable assets include players, draft picks, and FAAB $. If you would like a trade to be expedited, message in the league chat and the commissioner may push the trade through after a league vote.</p>
    
    <h4 bind:this={oneTwoOne}>1.2.1 Trade Collusion</h4>
    <div class="subBlock">
        <p>If any owners are suspected of accepting bribes/offering bribes to enhance their/another owners team via trade, trading any assets other than fantasy players, draft picks, FAAB $, or otherwise found guilty of engaging in any form of collusion*, all parties involved in the trade will be susceptible to punishment. The punishments will go as followed:</p>
        
        <ul>
            <li>First Offense – Immediate reduction of FAAB budget by 80%</li>
            <li>Second Offense – Immediate freeze on all transaction types for the next 18 weeks of regular season and playoff fantasy football games, including trades and waiver wire bids</li>
            <li>Third Offense – A league meeting of all members not involved in any of the improper trades/activity in question will take place to discuss next steps.</li>
        </ul>

        <p>All trades that are found guilty of collusion, will be reversed/denied. If the trade had affected the outcome of previous games, the results of those games will be revised.  </p>

        <p>*Collusion includes the organizing of veto votes against an acceptable trade.</p>

        <p>The commissioner will err on the side of letting owners manage their teams the way they see fit. Any collusion will need to be clear. The commissioner reserves the right to step in and at the very least assess the thinking of any team involved in a heavily lop-sided trade. </p>
    </div>

    <h4 bind:this={oneTwoTwo}>1.2.2 Lending Players Prohibition</h4>
    <div class="subBlock">
        <p>Any player traded from a team may not be re-acquired via trade within 3 weeks of the original trade. Any teams involved in this behavior will be subject to the aforementioned collusion punishments.</p>
    </div>
    
    <h4 bind:this={oneTwoThree}>1.2.3 Trade Deadline</h4>
    <div class="subBlock">
        <p>The trade deadline will be set for the kickoff of week 11 games of the NFL season. Additionally, draft pick trading will maintain an in-season deadline at the kickoffof week 7 games. Off-season draft pick trading is allowed without restriction so long as all parties involved have paid league dues for the draft picks exchanged. Managers are NOT permitted to trade keeper rights to another manager during the offseason in exchange for draft picks or other eligible keepers.</p>
    </div>
    
    <h4 bind:this={oneTwoFour}>1.2.4 Trade Restrictions</h4>
    <div class="subBlock">
        <p>As previously stated, trades involving draft picks can only be made for years in which league dues are currently paid. You may only trade FAAB $ from the current season.</p>
    </div>
    
    <h4 bind:this={oneTwoFive}>1.2.5 Veto/Trade Process</h4>
    <div class="subBlock">
        <p>A total of 6 veto votes are required to veto a trade. Vetoes are only appropriate in instances of collusion or an egregious mismatch of value (i.e. CMC for a backup kicker). Not liking a trade does not warrant a veto.</p>
    </div>
    
    
    
    <h3 bind:this={oneThree}>1.3 Waiver Wire</h3>
    
    <p>FAAB Waiver wire system. Each team will begin the season with $100. $0 bids are allowed. Bids will process Wednesdays 2AM CST.</p>

    <p>FAAB budgets will reset each season.</p>
    
    
    <h2 class="sectionHeading" bind:this={two}>Section 2 Drafting</h2>
    
    <h3 bind:this={twoOne}>2.1 Draft Order</h3>
    <p>The draft order each year will be a lottery system (NBA Draft style) based on reverse order of the previous year’s regular season standings (with the exception of the Champion, who will have the lowest odds regardless of regular season finish). The winner of the previous season's consolation championship will be awarded first selection of draft order position.</p>

    <div class="subBlock">
            <table class="draftOdds">
                <thead>
                    <tr><th><u>Previous Year Finish</u></th><th class="right"><u>Lottery Entries</u></th></tr>
                </thead>
                <tbody>
                    <tr><td>Consolation Champion</td><td class="right">Automatic First Selection</td></tr>
                    <tr><td>Lowest Remaining Regular Season Rank (10th or 9th)</td><td class="right">300 Entries</td></tr>
                    <tr><td>Lowest Remaining Regular Season Rank (9th or 8th)</td><td class="right">250 Entries</td></tr>
                    <tr><td>Lowest Remaining Regular Season Rank (8th or 7th)</td><td class="right">200 Entries</td></tr>
                    <tr><td>Lowest Remaining Regular Season Rank (6th or 5th)</td><td class="right">150 Entries</td></tr>
                    <tr><td>Lowest Remaining Regular Season Rank (5th or 4th)</td><td class="right">125 Entries</td></tr>
                    <tr><td>Lowest Remaining Regular Season Rank (4th or 3rd)</td><td class="right">100 Entries</td></tr>
                    <tr><td>Lowest Remaining Regular Season Rank (3rd or 2nd)</td><td class="right">75 Entries</td></tr>
                    <tr><td>Lowest Remaining Regular Season Rank (2nd or 1st)</td><td class="right">50 Entries</td></tr>
                    <tr><td>Champion</td><td class="right">10 Entries</td></tr>
                </tbody>
            </table>
        </div>

<!--
    <h3 bind:this={twoTwo}>2.2 Rookie Drafts</h3>
    <p>Rokkie drafts will consist of 3 round of drafting, with 5 minutes alotted for each pick. To make room for the incoming players, benches will be expanded by (5) spots. These spots will be removed in mid-August, at which point you will need to have cut the necessary players.</p>
    <p>Any spots not filled during the draft, can be filled immediately afterwards from the waiver wire.</p>
-->

    <h3 bind:this={twoTwo}>2.2 Draft Day Trades</h3>
    <p>If a trade is being made during the draft, one or both parties can alert the commissioner to pause the draft to allow for extra time to negotiate the trade.</p>
    
    <h2 class="sectionHeading" bind:this={three}>Section 3 Scoring System</h2>

    <h3 bind:this={threeOne}>3.1 Scoring System</h3>
    <p>The league scoring system breakdown is listed on the Sleeper fantasy app (for the most part, it follows typical .5PPR Scoring). The scoring system will never change without a majority league vote.</p>
    
    <h2 class="sectionHeading" bind:this={four}>Section 4 Postseason</h2>
    
    <h3 bind:this={fourOne}>4.1 Playoffs</h3>
    <p>At the end of the season 6 teams will make the playoffs. The first round of playoffs will commence in week 15. The top 2 teams will receive a bye week in the first round of the playoffs. Each playoff matchup will only last one week and the winner will advance. Week 18 will not be used.</p>
    
    <h3 bind:this={fourTwo}>4.2 Seeding Tiebreakers</h3>
    <p>If two teams finish with the same record the tiebreakers will go as followed:</p>

    <ol>
        <li>Points For</li>
        <li>Head 2 Head Record</li>
        <li>Total Points Against</li>
        <li>Coin Flip</li>
        <li>Duel to the death</li>
    </ol>

    <h2 class="sectionHeading" bind:this={five}>Section 5 Tanking Policy</h2>
    
    <h3 bind:this={fiveOne}>5.1 League Tanking Policy</h3>
    <p>No team may intentionally leave starting roster spots empty. Any evidence of intentionally leaving roster spots empty in order to improve your draft position may be subject to punishment, including but not limited to the forfeiture of draft selections.</p>

    <h2 class="sectionHeading" bind:this={six}>Section 6 Replacing Managers</h2>
    
    <h3 bind:this={sixOne}>6.1 Removing Managers</h3>
    <p>Short of continuously failing to set a valid lineup, or confirmed collusion, no manager can be removed against their will. Participation, through the league chat, trade offers, and the waiver wire, is strongly encouraged but not generally grounds for removal.</p>
    
    <h3 bind:this={sixTwo}>6.2 Replacing Managers</h3>
    <p>When a manager needs to be replaced, the commissioner(s) will try to find a suitable candidate with some connection to at least a portion of the existing managers. Priority will be placed on managers who are eager to take on a keeper commitment and will be very active within the league.</p>

<!--
    <h3 bind:this={sixThree}>6.3 Replacement Incentive</h3>
    <p>In the event that a manager chooses to quit the league or is removed by a comissioner, an incoming manager is offered a 50% reductioon on their first year buy-in.</p>
-->

    <h2 class="sectionHeading" bind:this={seven}>Section 7 League Finances</h2>
    
    <h3 bind:this={sevenOne}>7.1 League Dues</h3>
    <p>League dues are set at {dues}$. Dues are collected through the commissioner. All managers must be fully paid up before the start of regular season.</p>
    
    <h3 bind:this={sevenTwo}>7.2 Payout</h3>
    <p>League payout is structured as follows:</p>
    <ul>
        <li>1st place: {dues * 7.5}$</li>
        <li>2nd place: {dues * 1.5}$</li>
        <li>3rd place: {dues}$</li>
    </ul>
    
    
    <h3 bind:this={sevenThree}>7.3 Raising Dues</h3>
    <p>A ⅔ majority vote is required in order to raise league dues. In the event that a manager is no longer financially comfortable with the buyin, finding a co-manager to split the cost is reccomended.</p>


    <h2 class="sectionHeading" bind:this={eight}>Section 8 Keeper Rules</h2>

    <h3 bind:this={eightOne}>8.1 Declaring Keepers</h3>
    <p>A maximum of 3 players can be kept for the next season. Keeper selections must be declared one week before the draft as a soft deadline. The keeper selections may be amended up to one hour before the draft.</p>

    <h3 bind:this={eightTwo}>8.2 Keeper Values</h3>
    <p>Keeper value will be determined by their draft capital from the previous draft, subtracting one round from the previous draft, and then an additional round for each year the player is kept.</p>
    <ul>
        <li>For example, a player chosen in the 4th round of the 2024 draft that is declared as a keeper in 2025 will take place of that team’s 3rd round pick. In 2026, that player will cost a 1st round pick if kept.</li>
    </ul>
    <p>A player will retain their draft capital, as well as any multi-year keeper premium, if they are traded. A player will also retain their draft capital if they are dropped and subsequently picked up off of waivers/free agency.</p>
    <p>Players that were not drafted and picked up off free agency/waivers may be kept as a 7th round pick.</p>
    <p>In the event that a manager would like to keep two players that hold the same draft capital for the upcoming season (and he has less picks in the round in question), he may elect to keep a player at his next, more-valuable draft pick.</p>
    <p>Keepers may only be attached to a team's own draft picks. Any drafts picks that are obtained via trade with another team are not allowed to be used for a keeper draft pick designation.</p>

    <h3 bind:this={eightThree}>8.3 Keeper Eligibility</h3>
    <p>Players taken in the 1st or 2nd rounds are not eligible to be kept the following season.<p>
    <p>Players picked up off of waivers or free agency must be acquired prior to the Trade Deadline and held through the remainder of the season (postseason included) in order to be Keeper eligible.</p>

    <h2 class="sectionHeading" bind:this={append}>Appendix Amendments</h2>

    <h3 bind:this={appendOne}>A.1 IR Expansion</h3>
    <p>This amendment increases the number of IR slots on each roster from 1 to 2.</p>
    <p>Date Effective: 7/24/25</p>
    <p>Sections Updated:</p>
    <ul>
        <li class="noUnderscore clickable" on:click={() => goToSection(oneOne)}>Section 1.1</li>
    </ul>


    <h3 bind:this={appendTwo}>A.2 Draft Pick Trade Deadline</h3>
    <p>This amendment adds an additional trade deadline that applies to trades involving draft picks.</p>
    <p>Date Effective: 7/24/25</p>
    <p>Sections Updated:</p>
    <ul>
        <li class="noUnderscore clickable" on:click={() => goToSection(oneTwoThree)}>Section 1.2.3</li>
    </ul>

    <h3 bind:this={appendThree}>A.3 Keeper Pick Designation</h3>
    <p>This amendment forces keeper designations to be assigned solely to a team's own draft picks rather than any picks that are acquired via trade.</p>
    <p>Date Effective : 8/18/25</p>
    <p>Sections Updated:</p>
    <ul>
        <li class="noUnderscore clickable" on:click={() => goToSection(eightTwo)}>Section 8.2</li>
    </ul>

   <h3 bind:this={appendFour}>A.4 Offseason Keeper Trade Ban</h3>
    <p>This amendment explicitly bans the trading of keeper eligble players during the offseason.</p>
    <p>Date Effective: 8/18/25</p>
    <p>Sections Updated:</p>
    <ul>
        <li class="noUnderscore clickable" on:click={() => goToSection(oneTwoThree)}>Section 1.2.3</li>
    </ul>

</div>
