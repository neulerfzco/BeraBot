# 🐻⛓ Berachain Telegram Bot

Hot line for Berachain node validator health.  
Can be used with public RPC endpoints as long as they allow websocket connections. 

## Prerequisites
go 

## Installation
```bash
git clone https://github.com/neulerfzco/BeraBot.git
cd BeraBot
go mod tidy
```

Variables settings: Double check your validator address
```bash
cp .env.example .env
```

compile and run:
```bash
make build
bin/beraBot
```

## Features  
- [X] Consecutive Missed blocks alert
- [X] Node Down alert
- [ ] New Proposals 
- [ ] Software updates
- [ ] Stake changes

