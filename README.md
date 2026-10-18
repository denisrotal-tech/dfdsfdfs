# FreeOrders

Free DonutSMP-style /order plugin for Paper 1.21+. Needs Vault + an economy plugin (e.g. EssentialsX).

## Commands
- /order                          open the board with all orders (click one to deliver items)
- /order create <amount> <price>  create an order for the item in your hand (price per item)
- /order my                       your orders: left click = collect delivered items, right click = cancel + refund

Money for the order is taken when it is created (escrow) and paid to whoever delivers items.
Only plain items (no custom name/enchants/damage) can be ordered.

## Build
- With Maven:  mvn package   ->  target/FreeOrders.jar
- Without installing anything: upload this folder to a GitHub repo, open Actions -> Build -> download the FreeOrders artifact.
