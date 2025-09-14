<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneTwo, oneThree;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne, threeTwo;
    let four, fourOne, fourTwo;
    let five, fiveOne, fiveTwo;
    let six, sixOne, sixTwo;
    let seven, sevenOne, sevenTwo, sevenThree, sevenFour;
    let eight, eightOne, eightTwo, eightThree, eightFour;
    let nine, nineOne, nineTwo, nineThree;

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
    <h1 class="noUnderscore">BOYS CLUB CONSTITUTION</h1>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" onclick={() => goToSection(one)}>Article I: League Structure and Membership</h3>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneOne)}>Section 1.1 League Format</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneTwo)}>Section 1.2 Number of Teams</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneThree)}>Section 1.3 Membership

    <h3 class="noUnderscore clickable" onclick={() => goToSection(two)}>Article II: Financials</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(twoOne)}>Section 2.1 Annual Buy-In</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(twoTwo)}>Section 2.2 Payment Deadline</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(twoThree)}>Section 2.3 Payouts</h4>
    
    <h3 class="noUnderscore clickable" onclick={() => goToSection(three)}>Article III: League Governance and Rule Changes</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(threeOne)}>Section 3.1 The Commissioner</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(threeTwo)}>Section 3.2 Rule Changes</h4>
    
    <h3 class="noUnderscore clickable" onclick={() => goToSection(four)}>Article IV: Roster and Lineups</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fourOne)}>Section 4.1 Roster Size</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fourTwo)}>Section 4.2 Active Roster</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(five)}>Article V: Draft</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fiveOne)}>Section 5.1 Annual Rookie Draft</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fiveTwo)}>Section 5.2 Draft Order</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(six)}>Article VI: Waivers and Free Agency</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sixOne)}>Section 6.1 Waiver Wire</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sixTwo)}>Section 6.2 FAAB</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(seven)}>Article VII: Trading</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sevenOne)}>Section 7.1 Tradable Assets</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sevenTwo)}>Section 7.2 Draft Pick Trading</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sevenThree)}>Section 7.3 Trade Processing</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sevenFour)}>Section 7.4 Player Re-Acquisition</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(eight)}>Article VIII: Collusion and Penalties</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(eightOne)}>Section 8.1 Definition of Collusion</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(eightTwo)}>Section 8.2 Commissioner Discretion</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(eightThree)}>Section 8.3 Collusion Penalties</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(eightFour)}>Section 8.4 Trade Reversal</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(nine)}>Article IX: Playoffs</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(nineOne)}>Section 9.1 Playoff Structure</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(nineTwo)}>Section 9.2 Seeding and Byes</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(nineThree)}>Section 9.3 Tiebreakers</h4>

    
    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>Article 1 League Structure and Membership</h2>
    
    <h3 class="subSectionHeading" bind:this={oneOne}>Section 1.1 League Format</h3>
    
    <p>This is a dynasty league. Each team owner has the right to retain their entire roster from year to year. The annual rookie draft is the primary method for new players to enter the league.</p>
    
    <h3 class="subSectionHeading" bind:this={oneTwo}>Section 1.2 Number of Teams</h3>
    
    <p>The league shall consist of 12 teams.</p>    
    
    <h3 bind:this={oneThree}>1.3 Waiver Wire</h3>
    
    <p>FAAB Waiver wire system. Each team will begin the season with $100. $0 bids are allowed. Bids will process Thursdays and Sundays at 9AM EST.</p>

    <p>FAAB budgets will reset each season in January.</p>
    
    
    <h2 class="sectionHeading" bind:this={two}>Section 2 Drafting</h2>
    
    <h3 bind:this={twoOne}>2.1 Draft Order</h3>
    <p>The draft order each year will be a linear draft in reverse order of the previous year’s regular season standings.</p>

    <h3 bind:this={twoTwo}>2.2 Rookie Drafts</h3>
    <p>Rokkie drafts will consist of 3 round of drafting, with 5 minutes alotted for each pick. To make room for the incoming players, benches will be expanded by (5) spots. These spots will be removed in mid-August, at which point you will need to have cut the necessary players.</p>
    <p>Any spots not filled during the draft, can be filled immediately afterwards from the waiver wire.</p>
    
    <h3 bind:this={twoThree}>2.3 Draft Day Trades</h3>
    <p>If a trade is being made during the draft, one or both parties can alert the commissioner to pause the draft to allow for extra time to negotiate the trade.</p>
    
    <h2 class="sectionHeading" bind:this={three}>Section 3 Scoring System</h2>

    <h3 bind:this={threeOne}>3.1 Scoring System</h3>
    <p>The league scoring system breakdown is listed on the Sleeper fantasy app (for the most part, it follows typical .5PPR Scoring). The scoring system will never change without a majority league vote.</p>
    
    <h2 class="sectionHeading" bind:this={four}>Section 4 Postseason</h2>
    
    <h3 bind:this={fourOne}>4.1 Playoffs</h3>
    <p>At the end of the season 6 teams will make the playoffs. The first round of playoffs will commence in week 15. Each team that wins their division and the 4 wild card teams that finish with the best records, will receive a playoff berth. The 2 teams that win their division will receive a bye week in the first round of the playoffs. Each playoff matchup will only last one week and the winner will advance. Week 18 will not be used.</p>
    
    <h3 bind:this={fourTwo}>4.2 Seeding Tiebreakers</h3>
    <p>If two teams finish with the same record the tiebreakers will go as followed:</p>

    <ol>
        <li>Points For</li>
        <li>Head 2 Head Record</li>
        <li>Division Record</li>
        <li>Total Points Against</li>
        <li>Coin Flip</li>
        <li>Duel to the death</li>
    </ol>

    <h2 class="sectionHeading" bind:this={five}>Section 5 Tanking Policy</h2>
    
    <h3 bind:this={fiveOne}>5.1 League Tanking Policy</h3>
    <p>No team may intentionally leave starting roster spots empty. Any evidence of intentionally leaving roster spots empty in order to improve your draft position may be subject to punishment, including but not limited to the forfeiture of draft selections.</p>

    <h2 class="sectionHeading" bind:this={six}>Section 6 Replacing Managers</h2>
    
    <h3 bind:this={sixOne}>6.1 Removing Managers</h3>
    <p>Short of continuously failing to set a valid lineup, or confirmed collusion, no manager can be removed against their will. Participation, through the league chat, trade offers, and the waiver wire, is strongly encouraged but generally grounds for removal.</p>
    
    <h3 bind:this={sixTwo}>6.2 Replacing Managers</h3>
    <p>When a manager needs to be replaced, the commisiooners will try to find a suitable candidate with some connection to at least a portion of the existing managers. Priority will be placed on managers who are eager to take on a dynasty commitment and will be very active within the league.</p>
    
    <h3 bind:this={sixThree}>6.3 Replacement Incentive</h3>
    <p>In the event that a manager chooses to quit the league or is removed by a comissioner, an incoming manager is offered a 50% reductioon on their first year buy-in.</p>

    <h2 class="sectionHeading" bind:this={seven}>Section 7 League Finances</h2>
    
    <h3 bind:this={sevenOne}>7.1 League Dues</h3>
    <p>League dues are set at {dues}$. Dues are collected through <a href="https://www.leaguesafe.com/league/3949641">LeagueSafe</a> and collection will be sent out no later than the first of August. All managers must be fully paid up before the start of regular season. In the event that a manager fails to pay before the deadline, a 10% penalty will be addd to their payment and will go towards the payouts at the end of the year.</p>
    
    <h3 bind:this={sevenTwo}>7.2 Payout</h3>
    <p>League payout is structured as follows:</p>
    <ul>
        <li>1st place: {dues * 8}$</li>
        <li>2nd place: {dues * 3}$</li>
        <li>3rd place: {dues}$</li>
    </ul>
    <p>In the event that a manager was fined due to late payment, their extra fee will be added to the winner's payout. Similarly, if new managers come into the league and the payout is smaller, the difference will come out of the winner's prize.</p>
    
    <h3 bind:this={sevenThree}>7.3 Raising Dues</h3>
    <p>A ⅔ majority vote is required in order to raise league dues. In the event that a manager is no longer financially comfortable with the buyin, finding a co-manager to split the cost is reccomended.</p>

</div>
