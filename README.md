# Financial Stock Portfolio Generative AI Chatbot

## Introduction
This project aims to develop a Generative AI Chatbot that assists investors in managing their stock portfolios. The chatbot allows investors to easily monitor, buy, and sell stocks, providing responsive and accurate actions based on user commands. This tool simplifies portfolio management, ensuring investors can make informed decisions efficiently.

## Objectives
1. **Define Functions**: Implement various functions to manage the stock portfolio, including showing, adding, and removing stocks, calculating portfolio worth and gains, and plotting stock performance charts.
2. **Mapping JSON File**: Create a JSON file to map user queries to appropriate responses and actions, enabling the chatbot to understand and respond to investor commands effectively.

## Description

### Define Functions
- **show_portfolio**:
  - **Task**: Display the current stock portfolio of the investor.
  - **Outcome**: Investors can view a detailed list of all stocks in their portfolio, including the number of shares and current market value.
- **remove_portfolio**:
  - **Task**: Remove specified stocks from the portfolio.
  - **Outcome**: Investors can efficiently manage their portfolios by removing underperforming or unwanted stocks.
- **add_portfolio**:
  - **Task**: Add new stocks to the portfolio.
  - **Outcome**: Investors can expand their portfolios by adding new stocks, specifying the stock ticker and the number of shares to purchase.
- **portfolio_worth**:
  - **Task**: Calculate and display the total worth of the portfolio.
  - **Outcome**: Investors receive real-time updates on the overall value of their investments.
- **portfolio_gains**:
  - **Task**: Calculate and display the gains or losses of the portfolio.
  - **Outcome**: Investors can track the performance of their investments, identifying overall gains or losses.
- **plot_chart**:
  - **Task**: Generate and display performance charts for stocks in the portfolio.
  - **Outcome**: Investors can visually analyze the performance trends of their stocks, aiding in data-driven decision-making.

### Mapping JSON File
- **Task**: Create a JSON file to map user queries to corresponding functions and responses.
- **Structure**: The JSON file contains key-value pairs where the key is the user query and the value is the function or response.
- **Outcome**: The JSON file enables the chatbot to understand and process user commands accurately, mapping each query to the appropriate action or response.

## Implementation
1. **Set Up Environment**: Configure the development environment with necessary libraries and dependencies.
2. **Define Functions**: Implement each function to handle specific portfolio management tasks.
3. **Create JSON Mapping**: Develop the JSON file to map user queries to functions.
4. **Integrate Chatbot**: Combine the functions and JSON mapping into a chatbot framework.
5. **Testing**: Test the chatbot with various scenarios to ensure accurate responses and actions.
6. **Deployment**: Deploy the chatbot for investor use, ensuring it is accessible and user-friendly.

## Conclusion
This project successfully develops a Generative AI Chatbot for financial stock portfolio management, providing investors with a powerful tool to monitor and manage their portfolios. By implementing key functions and mapping user queries, the chatbot delivers efficient, real-time responses, enhancing the investment decision-making process.
