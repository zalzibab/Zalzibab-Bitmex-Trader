# Zalzibab-Bitmex-Trader

## What It Is

Basic Trading Functions For Bitmex

## Bot Commands

choose_account - select saved account to manage
balance - current wallet balances
open_position - open XBTUSD position
cancel_orders - cancel XBTUSD orders
short - 1x short
long - 1x long
close_position - close XBTUSD position

### One-Liner 1st Time VPS Setup

Copy/Paste the following one-liner

sudo apt update && sudo apt upgrade -y && sudo apt install python3.7 -y && sudo apt-get install python3-pip -y && sudo apt-get install python3-venv -y && git clone https://github.com/zalzibab/Zalzibab-Bitmex-Trader.git && cd Zalzibab-Bitmex-Trader && python3 -m venv env && source env/bin/activate && python -m pip install -r requirements.txt && python Credentials.py

Once credentials are saved, run the following
python bitmex_bot.py





