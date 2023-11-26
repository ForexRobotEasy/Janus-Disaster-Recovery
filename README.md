# Janus Disaster Recovery

Janus Disaster Recovery is an Expert Advisor developed by the Forex Robot Easy Team. This code is a sample implementation of the Expert Advisor and is provided for demonstration purposes. ForexRobotEasy is not the official developer of this product. To find the official developer of this product, please refer to the MQL5 website.

## Recovery Mode

The `RecoveryMode()` function is responsible for implementing the code to recover from existing drawdowns on the trading account. The following tasks need to be accomplished in this mode:

1. Implement code to recover from existing drawdowns on the trading account.
2. Ensure compatibility with trades executed by other Expert Advisors and manually opened trades.
3. Implement a mechanism to turn off other EAs and display the account at no loss when drawdown is reached for a specific trading instrument.
4. Aim to regain control and potentially reverse the drawdown situation.

## Protect Mode

The `ProtectMode()` function is responsible for implementing the code to provide online account control and protection. The following tasks need to be accomplished in this mode:

1. Implement code to provide online account control and protection.
2. Enable monitoring of trades and take necessary actions to safeguard the account.
3. Implement measures to prevent the account from being compromised or losing funds.
4. Prioritize account security and stability.

## Main Program

The `OnInit()` function is the entry point of the Expert Advisor. It is responsible for initializing necessary variables and settings. It also calls the `RecoveryMode()` function to initiate recovery mode and the `ProtectMode()` function to initiate protect mode.

The `OnTick()` function is called on every tick and is responsible for monitoring market conditions, making trading decisions, executing trades based on the trading strategy, managing open trades, calling the `RecoveryMode()` if drawdown is detected, and calling the `ProtectMode()` to ensure account security. It also logs account activities and performance.

The `OnDeinit()` function is called when the program is about to terminate. It is responsible for cleaning up resources and performing necessary actions before the program terminates.

For detailed reviews and trading results of this product, please visit the [Janus Disaster Recovery Expert Advisor for Account Drawdown Recovery MT5 Version Review & Download](https://forexroboteasy.com/forex-robot-review/janus-disaster-recovery-expert-advisor-for-account-drawdown-recovery-mt5-version-review-download/) page on the Forex Robot Easy website.

Note: This code is a sample implementation and may not reflect the complete functionality of the official Janus Disaster Recovery Expert Advisor. Please refer to the official developer for the complete version.
