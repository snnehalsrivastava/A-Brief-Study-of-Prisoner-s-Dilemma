# A Brief Study of Prisoner's Dilemma: Strategic Choices and Human Behavior

## Project Overview

This research project delves into **Game Theory**, specifically focusing on the **Prisoner's Dilemma**, to analyze interactive choices where outcomes for each player are determined by the actions of all participants. Through data analysis of 56 players across 5 rounds per game, the study examines player behavior when faced with choices to cooperate or compete, revealing trends in payoffs and the prevalence of self-interested motives.

## Key Concepts

### Game Theory
Game theory is the study of **interactive choices**, where the outcomes for any player are determined by the actions of all others. This necessitates that players consider the preferences of all other participants when deciding on their strategy.

### Nash Equilibrium
**Nash equilibrium** is a state where the strategy chosen by one player yields the highest payoff, given the other player's strategy, and vice versa. In the context of a single round of the Prisoner's Dilemma, the Nash equilibrium is achieved when **both players choose to compete**, resulting in a payoff of 1 for each.

### Prisoner's Dilemma
The Prisoner's Dilemma is a situation named after a scenario involving two crime suspects offered incentives to confess against each other. It presents a choice between **cooperating and competing**, with specific payoffs associated with each outcome:
*   **Both Cooperate**: Payoff of 3 for each player.
*   **Both Compete**: Payoff of 1 for each player.
*   **One Competes, One Cooperates**: The competing player gets a payoff of 5, while the cooperating player gets -1.

The goal in this game is to **maximize individual payoff**, not merely to outperform the opponent. While the socially optimal decision is for both players to cooperate (yielding 3 each), the dominant strategy for each individual player is to compete, as it ensures a better or equal payoff regardless of the opponent's choice, leading to the Nash equilibrium where both compete and get 1 each. Players are often **tempted to defect** for the highest individual payoff if the opponent cooperates, or a decent payoff even if the opponent competes.

## Data Analysis and Methodology

The project analyzed data from **56 players** who played a game with two players each for **5 rounds per game**.
*   The raw data was manually organized using MS-Excel, dividing it into two datasets for Player A and Player B to study individual behavior.
*   Values of 'Cpt' (Compete) and 'Coop' (Cooperate) were replaced by 1 and 0 respectively for analysis.
*   Players who consistently chose to compete in every round were highlighted; there were 24 such players in Player A's dataset and 23 in Player B's.

### Key Observations from Data Analysis:

*   **Downward Trend in Cooperation, Upward Trend in Competition**:
    *   **Cooperation** declined significantly from **33.04% in Round 1 to 11.61% in Round 5**.
    *   **Competition** increased from **66.96% in Round 1 to 88.39% in Round 5**.
    *   More than half of the players chose to compete even in the first round.
*   **Decline in Average Profit**: The average profit declined through consecutive rounds, mirroring the decline in cooperation. This occurs because higher payoffs are achieved when players cooperate, and as cooperation decreases, so do the chances of higher payoffs.
*   **Prevalence of Nash Equilibrium**: Towards the later rounds (especially **Rounds 4 & 5**), the majority of players opted to compete, leading to the game frequently achieving the Nash equilibrium where both players gain a payoff of 1 each.
*   **Selfish Motives**: The findings suggest that participants often have **selfish motives rather than altruistic ones**. Players are tempted to defect to gain a higher payoff if the opponent cooperates.
*   **Probing Strategy**: Many players employed a "probing strategy," playing the same strategy for 2-3 rounds to observe the opponent's behavior before adapting their own strategy.
*   **Risk Aversion**: Even though the maximum payoff can be achieved by cooperating and taking a slight risk, humans often **choose to minimize the risk of loss and play safe** by competing.

## Real-World Applications

The Prisoner's Dilemma provides a framework for understanding strategic interactions in various real-world scenarios:

*   **OPEC (Organization of the Petroleum Exporting Countries)**:
    *   OPEC members form a cartel to control oil prices, making choices to cheat or collude on oil production quantities.
    *   If a country like Saudi Arabia cheats by selling more oil, it can gain significant profit and market share, but this lowers global oil prices and revenues for the entire group, making OPEC worse off.
    *   If Saudi Arabia cooperates and reduces production, oil prices and everyone's revenues would increase, improving the group's overall utility. This highlights the dilemma between individual gain and collective benefit.

*   **Tinder (Dating App)**:
    *   **Deliberate Strategy (Cooperation)**: Users right-swipe only for people they genuinely like, leading to genuine matches if reciprocated.
    *   **Corrupt Strategy (Competition/Defection)**: Users right-swipe on everyone and decide on interest only after a match.
    *   **Mutual Cooperation**: Both play deliberated, resulting in genuine, activated matches.
    *   **Mutual Defection**: Both play corrupt, leading to potentially meaningless matches where little effort is invested.
    *   **Asymmetric Play (A Deliberate, B Corrupt)**: If A plays deliberate and B plays corrupt, B knows A likes them, giving B an advantage. A, having invested interest, receives silence if B isn't interested, leading to a bad experience.
    *   Users often adopt the corrupt strategy due to frustration from unactivated matches, creating a snowball effect of more inactive matches for others.

---
