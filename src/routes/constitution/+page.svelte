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
        color: #FFFFFF;
    }
</style>

<div class="constitution">
    <h1 class="noUnderscore">BOYS CLUB CONSTITUTION</h1>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" onclick={() => goToSection(one)}>Article I: League Structure and Membership</h3>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneOne)}>Section 1.1 League Format</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneTwo)}>Section 1.2 Number of Teams</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneThree)}>Section 1.3 Membership</h4>

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
    
    <h2 class="sectionHeading" bind:this={one}>Article I: League Structure and Membership</h2>
    
    <h3 class="subSectionHeading" bind:this={oneOne}>Section 1.1 League Format</h3>
    
    <p>This is a dynasty league. Each team owner has the right to retain their entire roster from year to year. The annual rookie draft is the primary method for new players to enter the league.</p>
    
    <h3 class="subSectionHeading" bind:this={oneTwo}>Section 1.2 Number of Teams</h3>
    
    <p>The league shall consist of 12 teams.</p>    
    
    <h3 bind:this={oneThree}>Section 1.3 Membership</h3>
        <ol>
            <li>The commissioner, or a majority vote of the league, reserves the right to invite new members to fill any vacated spots.</li>
            <li>Membership can be expanded with a majority vote.</li>
            <li>All members are expected to be active participants throughout the year, including setting a full lineup each week and engaging in league communications and votes.</li>
        </ol>

    <h2 class="sectionHeading" bind:this={two}>Article II: Financials</h2>
    
    <h3 bind:this={twoOne}>Section 2.1 Annual Buy-In</h3>
    <p>The annual buy-in is $50 per team.</p>

    <h3 bind:this={twoTwo}>Section 2.2 Payment Deadline</h3>
    <p>All buy-in fees are due prior to the first kickoff of the NFL regular season. Failure to pay on time may result in the forfeiture of a future draft pick, as determined by the commissioner and a league vote.</p>
    
    <h3 bind:this={twoThree}>Section 2.3 Payouts</h3>
    <p>The distribution of the prize pool will be determined by a league vote at the start of each season.</p>
    
    <h2 class="sectionHeading" bind:this={three}>Article III: League Governance and Rule Changes</h2>

    <h3 bind:this={threeOne}>Section 3.1 The Commissioner</h3>
    <p>The Commissioner is responsible for the day-to-day operation of the league, including but not limited to:</p>
        <ol>
            <li>Enforcing the rules outlined in this Constitution,</li>
            <li>Managing the Sleeper fantasy app settings,</li>
            <li>Facilitating the annual rookie draft and offseason, and</li>
            <li>Acting as the final arbiter in any disputes.</li>
        </ol>

    <h3 bind:this={threeTwo}>Section 3.2 Rule Changes</h3>
        <ol>        
            <li>Any proposed rule change must be submitted to the league for a vote.</li>
            <li>All rule changes, with the exception of those related to collusion as detailed in Article VIII, require a majority approval vote (7 out of 12 teams) to be enacted.</li>
            <li>Rule changes will not take effect until the start of the following season, unless a time-sensitive issue requires an immediate vote and implementation (e.g., an unforeseen rule discrepancy).</li>
        </ol>

    <h2 class="sectionHeading" bind:this={four}>Article IV: Roster and Lineups</h2>
    
    <h3 bind:this={fourOne}>Section 4.1 Roster Size</h3>
    <p>Each team's total roster size is a maximum of 30 players, with 22 of those players being considered active. The breakdown is as follows:</p>
    <p>    Starting Lineup:</p>
        <ul>
            <li>1 QB</li>
            <li>2 RB</li>
            <li>2 WR</li>
            <li>1 TE</li>
            <li>4 Flex (RB/WR/TE)</li>
        </ul>

    <p>    Bench: 15 players</p>
    <p>    Injured Reserve (IR): 3 spots for players with an official IR designation.</p>
    <p>    Taxi Squad: 2 spots reserved for players with 1 year of less of NFL experience. Once a player is moved off the Taxi Squad, they cannot be returned.</p>
    
    <h3 bind:this={fourTwo}>Section 4.2 Active Roster</h3>
    <p>All teams must set a complete starting lineup each week of the regular season and playoffs. Intentionally leaving a starting roster spot empty to improve a draft position (tanking) is not permitted. Any evidence of such behavior may result in a punishment, including but not limited to the forfeiture of draft selections, as determined by the commissioner and a league vote.</p>

    <h2 class="sectionHeading" bind:this={five}>Article V: Draft</h2>
    
    <h3 bind:this={fiveOne}>Section 5.1 Annual Rookie Draft</h3>
    <p>The annual rookie draft will be a linear draft consisting of 4 rounds.</p>

    <h3 bind:this={fiveTwo}>Section 5.2 Draft Order</h3>

    <p>Picks 7-12: The draft positions for the top six finishers in the regular season (teams that did not make the playoffs) will be determined in reverse order of their final regular season standings.</p>

    <p>Picks 1-6: The draft order for the six playoff teams will be determined by a weighted, yet random process. This process will be selected each year by the team that finished last in the regular season and is subject to a league vote for approval. The process is intended to emulate an NBA-style draft lottery to maintain competitive balance among top teams.</p>

    <h2 class="sectionHeading" bind:this={six}>Article VI: Waivers and Free Agency</h2>
    
    <h3 bind:this={sixOne}>Section 6.1 Waiver Wire</h3>
    <p>The waiver wire is continually open.</p>
    
    <h3 bind:this={sixTwo}>Section 6.2 FAAB</h3>
    <p>Each team is issued $100 in FAAB (Free Agent Acquisition Budget) at the beginning of each season.</p>

        <ul>
            <li>FAAB budgets reset when the league is renewed each year.</li>
            <li>There is no minimum bid amount.</li>
            <li>Bids of $0 are permitted.</li>
            <li>FAAB dollars can be traded as a tradable asset.</li>
        </ul>
    
    <h2 class="sectionHeading" bind:this={seven}>Article VII: Trading</h2>
    
    <h3 bind:this={sevenOne}>Section 7.1 Tradable Assets</h3>
    <p>Tradable assets include players, draft picks, and FAAB dollars.</p>
    
    <h3 bind:this={sevenTwo}>Section 7.2 Draft Pick Trading</h3>
    <p>Teams are permitted to trade draft picks up to 3 drafts away (e.g., in 2025, you can trade picks for the 2026, 2027, and 2028 drafts).</p>
    
    <h3 bind:this={sevenThree}>Section 7.3 Trade Processing</h3>
        <ol>
            <li>Trades will process immediately upon acceptance by all parties.</li>
            <li>The commissioner reserves the right to reverse a trade if it is under investigation for collusion.</li>
        </ol>

    <h3 bind:this={sevenFour}>Section 7.4 Player Re-Acquisition</h3>
    <p>Any player traded from a team may not be re-acquired via trade by the original team within 6 weeks of the original trade date. Any teams involved in this behavior will be subject to collusion punishments.</p>
    
    <h2 class="sectionHeading" bind:this={eight}>Article VIII: Collusion and Penalties</h2>
    
    <h3 bind:this={eightOne}>Section 8.1 Definition of Collusion</h3>
        <ol>
            <li>Collusion is defined as an act where two or more owners work together to unfairly enhance a single team's chances of winning, or otherwise disrupt the integrity of the league.</li>
            <li>Examples include, but are not limited to: accepting bribes, offering bribes, trading assets other than fantasy players, draft picks, or FAAB dollars, or organizing veto votes against a fair and acceptable trade.</li>
        </ol>

    <h3 bind:this={eightTwo}>Section 8.2 Commissioner Discretion</h3>
    <p>The commissioner will err on the side of allowing owners to manage their teams as they see fit. Any accusation of collusion must be clear and supported by evidence. The commissioner reserves the right to investigate and assess the thinking of any team involved in a heavily lop-sided trade.</p>
    
<h3 bind:this={eightTwo}>Section 8.2 Collusion Penalties</h3>
    <p> If any owner is found guilty of engaging in any form of collusion, the following penalties will be applied:</p>
        <ol>
            <li>First Offense: Immediate reduction of the team's FAAB budget by 80%.</li>
            <li>Second Offense: Immediate freeze on all transaction types for the next 18 weeks of fantasy football games (regular season and playoffs), including trades and waiver wire bids.</li>
            <li>Third Offense: A league meeting of all members not involved in the improper activity will take place to discuss next steps, which may include suspension or removal from the league.</li>
        </ol>

    <h3 bind:this={eightFour}>Section 8.4 Trade Reversal</h3>
    <p>All trades found to be the result of collusion will be reversed. If the trade had affected the outcome of previous games, the results of those games will be revised.</p>

    <h2 class="sectionHeading" bind:this={nine}>Article IX: Playoffs</h2>
    
    <h3 bind:this={nineOne}>Section 9.1 Playoff Structure</h3>
        <p>The playoffs will consist of 6 teams, beginning in Week 15 of the NFL season.</p>

    <h3 bind:this={nineTwo}>Section 9.2 Seeding and Byes</h3>
        <ol>
            <li>The top 2 teams based on regular season standings will receive an automatic bye in Week 15.</li>
            <li>The remaining 4 teams will be seeded 3 vs. 6 and 4 vs. 5 for Week 15 matchups.</li>
        </ol>
    
    <h3 bind:this={nineThree}>Section 9.3 Tiebreakers</h3>
    <p>In the event of a tie in the regular season standings, the following tiebreakers will be used to determine playoff seeding, in order:</p>
        <ol>
            <li>Head-to-Head record between the tied teams.</li>
            <li>Total Points For (PF) for the season.</li>
            <li>Total Points Against (PA) for the season.</li>
        </ol>

</div>
