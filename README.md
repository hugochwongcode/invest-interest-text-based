## Stock, Dividend, and Interest Game 📈💰
Welcome to the Stock, Dividend, and Interest Game! This interactive financial decision-making game allows you to experience the ups and downs of managing your finances. Trade stocks, earn dividends, accumulate interest, and set and achieve your financial goals! 

## Features
Version 1:
Basic Gameplay: Start with $10000 and make financial decisions.
Trade Stocks: Buy or sell stocks with randomly generated prices.
Receive Dividends: Random dividends add to your balance.
Earn Interest: Interest accumulates on your balance.

Version 2:
Enhanced Gameplay: Set and track financial goals.
Set Goals: Define goals like retirement, dream vacations and new home.
Track Progress: Monitor your progress towards each financial goal.
Achieve Goals: Celebrate achieving your financial milestones!

## Game Rules:
Objective:
The objective of the game is to manage your finances effectively and achieve your financial goals.

Starting Conditions:
Players start the game with a balance of $10000. There are no stocks owned initially. Financial goals are predefined but can be adjusted in Version 2 of the game.

## Gameplay:
To play the game, download the code from the GitHub repository and run it in Jupyter Notebook or Google Colab. 

Trading Stocks: Players can choose to buy or sell stocks. Stock prices are randomly generated between $50 and $250.Maximum affordable shares depend on the available balance and can't exceed 100 shares per transaction.
Receiving Dividends: Random dividends between $5 and $30 are received periodically.
Earning Interest: Interest is accrued on the balance based on a randomly generated interest rate between 3.5% and 5.5%.

Setting and Achieving Financial Goals (Version 2):Players can set financial goals such as retirement savings, dream vacations, or buying a new home.
Track progress towards each goal and aim to achieve them.

Winning the Game:
The game doesn't have a specific "win" condition but aims to simulate real-world financial decision-making and goal-setting. Players can consider themselves successful if they achieve their financial goals or effectively manage their finances to accumulate wealth. 

Losing the Game:
There's no explicit "lose" condition, but players may feel unsuccessful if they fail to achieve their financial goals or deplete their balance without meeting their objectives.

Ending the Game:
Players can choose to quit the game at any time by selecting the "Quit" option.
The game ends automatically in Version 2 when all financial goals are achieved or when players decide to quit.

## Testing Instructions for Version 2
I skip the testing for version 1 and move to version 2. 

### Correct Display of Messages

- **After Buying Shares**: Ensure that the game displays the correct messages after the player buys any shares of stock.

- **After Selling Shares**: Verify that the game shows the correct messages after the player sells any shares of stock.

### Handling Dividends

- **Player Should Not Receive Dividends Without Owning Shares of Stock**:
  - `owned_shares` is a parameter to keep track of the shares owned by the player throughout the game. 
  - The game logic is updated to check the `owned_shares` dictionary when determining if the player is eligible to receive dividends.

#### Player Buys Stock

- After the player buys stocks, the game keeps track of the owned shares.
- When the player requests a dividend, the game checks if the player owns any shares. If so, the player receives a dividend.

#### Player Sells Stock

- If the player sells all their shares of a stock, the game updates the owned shares accordingly.
- When the player requests a dividend, the game checks if the player owns any shares. If the player sold all their shares, they won't receive a dividend.

#### Player Does Not Hold Any Shares

- If the player doesn't hold any shares of any stock, they won't receive a dividend when requested.

## License
This project is licensed under the  GNU GENERAL PUBLIC LICENSE Version 3 - see the LICENSE file for details.

## Contact
For any inquiries or assistance, feel free to reach out:
Email: hugochwong123@gmail.com
Linkedin: https://www.linkedin.com/in/hugochw/ 

