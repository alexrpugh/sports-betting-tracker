# sports-betting-tracker
Excel-based tool for analyzing betting trends and profits across variables

## How To Use

1. Download from this repository
2. Hit "Enable Macros" upon opening
3. Begin logging your sports bets in the appropriate month from which the bet was placed (i.e., a January 10th bet would go in the "Jan 2025" sheet)
5. Log bets into appropriate monthly sheets according to date placed.

## Column Descriptions

- Date placed: The month/day/year in which the bet was placed (not the date of the event)
- Sportsbook: the sportsbook in which the bet was placed
- League: the league in which the bet was placed
- Compositin: framework of the bet:
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
- Teams Bet On: a comma seperated list of all teams included in the bet
  - Include repeat values to ensure "Number of Legs" is correct
- Players Bet On: a comma seperated list of all players included in the bet
  - Include repeat values to ensure "Number of Legs" is correct
- Reason for Loss: a comma seperated list of all teams or legs that led to the bet to lose
  - Leave empty if the bet was a win
- Source: From whom the inspiration for the bet was derived (i.e., a sports betting influencer; a friend)
- Notes: Any optional notes to add

 
## Notes

- Hit UPDATE on Master sheet to view all bets on one sheet / use pivot tables.
- Search for Player/Team on Master sheet, not on monthly sheets.
- Hit % on Team/Player search encompasses all bets.
- Profit on Team/Player search only encompasses straight bets.
- Futures sheet does not automatically populate; bets must be re-entered.
- Leave day-by-day data will automatically populate in the monthly sheets.					
- Leave ' (an apostrophe) in cell A2 of future monthly sheets (makes the master sheet prettier upon compiling).

