# sports-betting-tracker
This self-made Excel tool analyzes betting trends and profits across various variables, providing valuable insights into your betting history. By logging bets into the appropriate monthly sheet, you can track many valuable metrics - such as profitability by sportsbook, assess hit rates for individual players and teams, and identify the odds ranges where your bets most frequently fall. This tracker helps you make more informed decisions and bet responsibly.

## How To Use

1. Download from this repository.
2. Hit "Enable Macros" upon opening.
3. Begin logging your sports bets in the appropriate month from which the bet was placed (i.e., a January 10th bet on the Super Bowl in February would go in the "Jan 2025" sheet).
5. Log bets into appropriate monthly sheets according to date placed.
6. Select columns A-S and sort by Date Placed (oldest to newest).

## Column Descriptions

- Date placed: the month/day/year in which the bet was placed (not the date of the event)
- Sportsbook: the sportsbook in which the bet was placed
- League: the league(s) in which are included in the bet
- Composition: framework of the bet
  - "Straight" if only one thing has to happen to win
  - "Parlay" if multiple things have to happen to win
  - "Boost" if the sportsbook offered a pre-made bet for you to take with enhanced odds
- Odds: the odds of the bet that impact payout (put a negative sign for minus-money bets)
- Number of Legs: the number of things that have to happen for the bet to win
  - This can be autofilled by entering all teams and players in later columns (INCLUDING repeats)
- Moneyline: if the bet includes a moneyline selection (a team to win)
  - "Yes" if TRUE
  - "No" is FALSE
- Spread/Total: if the bet includes a spread or a total selection (i.e., a team to win by x much; over/under x total points to be scored)
  - "Yes" if TRUE
  - "No" is FALSE
- Player Prop: if the bet includes a wager on player performance
  - "Yes" if TRUE
  - "No" is FALSE
- Live: if the bet was placed during the event
  - "Yes" if TRUE
  - "No" is FALSE
- Wager: the amount risked on the bet
- Payout: the total compensation if the bet wins, including the wager
  - Autofilled if the "Odds" and "Wager" columns are manually filled
- Win: if the bet was won and profit was made
  - "Yes" if TRUE
  - "No" is FALSE
- Profit: the amount gained or lost after accounting for the amount wagered
  - Autofilled if the "Wager" and "Win" columns are manually filled
- Teams Bet On: a comma-separated list of all teams included in the bet
  - Include repeat values to ensure "Number of Legs" is correct
- Players Bet On: a comma-separated list of all players included in the bet
  - Include repeat values to ensure "Number of Legs" is correct
- Reason for Loss: a comma-separated list of all teams or legs that led to the bet losing
  - Leave empty if the bet was a win
- Source: Where the inspiration for the bet came from (e.g., a sports betting influencer, a friend)
  - To change source options to specific people or organizations, alter cells F50:F58 on the 'Master' sheet
- Notes: Any optional notes to add

 
## Notes

- Hit UPDATE on Master sheet to view all bets on one sheet / use pivot tables.
- Search for Player/Team on Master sheet, not on monthly sheets.
- Hit % on Team/Player search encompasses all bets.
- Profit on Team/Player search only encompasses straight bets.
- Futures sheet does not automatically populate; bets must be re-entered.
- Day-by-day data will automatically populate in the monthly sheets.					
- Leave ' (an apostrophe) in cell A2 of future monthly sheets (makes the master sheet prettier upon compiling).

