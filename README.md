# Golden Rabbit Trade Guardian

A MetaTrader 5 trading discipline and risk management indicator designed to help traders follow their trading plan, control risk, prevent overtrading, and maintain execution discipline in real time.

## 🚀 Overview

Golden Rabbit Trade Guardian acts as a protective layer between the trader and impulsive trading decisions.

Instead of simply displaying trading information, the indicator continuously monitors your trading activity and compares it with the rules defined in your trading plan.

It is designed to help prevent:

- Overtrading
- Excessive risk per trade
- Moving or removing Stop Loss
- Trading during cooldown periods
- Exceeding daily risk limits
- Breaking daily trading limits
- Repeated violations of the trading plan

## 🛡️ Key Features

### Risk Management

- Real-time monitoring of active trade risk
- Monitoring planned maximum risk
- Monitoring actual Stop Loss risk
- Detection of excessive position risk
- Protection against increasing risk by moving the Stop Loss
- Monitoring combined risk across active positions

### Trading Plan Protection

The indicator allows traders to define rules for their trading plan and monitors compliance in real time.

It can monitor:

- Maximum daily trades
- Maximum daily loss
- Maximum allowed risk
- Trading cooldown periods
- Stop Loss requirements
- Daily profit targets
- Trading restrictions after violations

### ⏱️ Cooldown System

Golden Rabbit Trade Guardian includes a multi-level cooldown system designed to prevent emotional and revenge trading.

#### Code 1

After a closed losing trade:

20 minutes cooldown

After a closed profitable trade:

10 minutes cooldown

If the trader respects the restriction, normal trading resumes automatically.

#### Code 2

If the trader opens a new trade during a Code 1 restriction, the violation escalates the protection level.

After a violation:

- Losing trade → 1 hour restriction
- Profitable trade → 30 minutes restriction

#### Code 3 — Emergency Protection

Repeated violations can activate the emergency protection system.

The trader can be locked until the end of the trading day.

Repeated violations can increase the restriction period.

The purpose is simple:

> Stop the trading session before one emotional decision turns into a chain of losses.

## 🚨 Emergency Protection

The indicator can detect critical violations such as:

- Excessive open risk
- Stop Loss risk exceeding the allowed plan
- Missing Stop Loss
- Removing an existing Stop Loss
- Breaking daily risk limits
- Breaking trading frequency rules
- Trading during a restricted period

Emergency protection can prevent further trading until the violation is resolved or the restriction period expires.

## 📊 Trading Dashboard

The dashboard provides a real-time overview of the trading session.

Depending on the selected mode, it can display:

- Account balance
- Daily P&L
- Daily trades
- Wins
- Losses
- Active trade information
- Current risk
- Planned maximum risk
- Stop Loss risk
- Risk-to-Reward
- Daily target progress
- Daily loss progress
- Trading restrictions
- Next available trading time

## 🎯 Daily Target Protection

When the predefined daily profit target is reached, the indicator can enter a protected state.

The trader can choose whether to:

- Continue trading
- Wait until the trading day ends

This is designed to help protect profitable trading days from unnecessary additional risk.

## 🔒 Stop Loss Protection

Golden Rabbit Trade Guardian continuously monitors Stop Loss conditions.

If a position is opened without a Stop Loss, the indicator can provide a warning and countdown.

If the Stop Loss remains missing, repeated warnings are triggered until the required protection is restored.

The same protection can be applied if an existing Stop Loss is removed.

## 📈 Performance Monitoring

The dashboard provides a summary of the current trading day, including:

- Total trades
- Winning trades
- Losing trades
- Net P&L
- Daily target progress
- Daily loss progress
- This allows the trader to understand the current state of the trading session without manually calculating the numbers.

## 🖥️ Dashboard Modes

The indicator supports different dashboard display modes to provide flexibility between detailed monitoring and a more compact chart layout.

### Full Mode

Provides detailed information about:

- Risk
- Active trades
- Daily performance
- Trading plan
- Restrictions
- Protection status

### Compact Mode

Provides the essential information while occupying less chart space.

## ⚡ Lightweight Design

Golden Rabbit Trade Guardian is designed as a MetaTrader 5 indicator rather than an Expert Advisor.

Its purpose is monitoring, protection and visual guidance without executing trades automatically.

## 📦 Installation

1. Download the latest .ex5 file from the Releases section.
2. Open MetaTrader 5.
3. Go to:

File → Open Data Folder

4. Open:

MQL5 → Indicators

5. Copy GoldenRabbitTradeGuardian.ex5 into the folder.
6. Restart MetaTrader 5 or refresh the Navigator.
7. Open the indicator from:

Navigator → Indicators

8. Attach it to a chart.

## ⚠️ Important

Golden Rabbit Trade Guardian is a trading discipline and risk-management tool.

It does not guarantee profitable trading and does not provide financial advice.

The trader remains responsible for all trading decisions and account risk.

## 👤 Author

Reza Noroozi

Golden Rabbit Trading System

---

⭐ If you find this project useful, consider giving the repository a Star.

More updates and trading tools will be released in future versions.
