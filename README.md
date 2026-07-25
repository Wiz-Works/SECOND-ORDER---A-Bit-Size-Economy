# Second Order - A Bit Size Economy

In this game, you are a trader in an emerging economy starting with just $1. Watch markets and monetary systems develop from their infancy as you speculate on different commodities, sectors, and biomes.  The autonomous agents have unique genetic combinations, but overall they are programmed with simple logic: they move, eat, harvest, reproduce, trade items, and buy, rent, or build houses. From those simple rules, second-order phenomena like wealth inequality, housing crises, and inflation emerge.  The economy constantly reacts to its own ripples, agents will attempt to produce scarce commodities, deploy machinery to boost output, and respond to price signals. Meanwhile, the Fed attempts to keep the economy under control through interest rates, mintage rates, taxation, welfare, and gold manipulation.

---

## The Objective

You are a spectator to this world, starting with an initial capital of **1.00$**. Your primary goal is to turn that initial dollar into as much wealth as you possibly can by playing the simulation's markets. You do not control the agents directly; instead, you read the trends, anticipate shortages, and invest your money to grow your portfolio.

<img width="1264" height="842" alt="image" src="https://github.com/user-attachments/assets/36b53347-d8d8-4b5a-9d0c-812641e54445" />

---

## How to Use

*   Download the HTML file "Second Order 0.0.1.html".
*   Open it on a browser (Most modern mainstrean browsers should work, in both PC and Mobile. Tested on Brave and Chrome).
*   Play the game.

---


## How to Play

*   **Wait for the economy to emerge:** Trading is halted for the first 5000 ticks to allow the economy to emerge and prices to stabilize.
*   **Use the Trading Dashboard:** Monitor your investments, cash, and overall win rate, and track your equity curve over time.
*   **Trade Commodities:** Buy and sell exposure to physical goods like oil, iron, or glass as their prices fluctuate.
*   **Invest in Macro Trends:** Buy shares in specific **Sectors** or entire **Biomes** to bet on the broader success of certain industries or geographic regions.
*   **Watch the Signals:** The market dashboard provides indicators for scarcity pressure and production pull to help guide your trading decisions.

---

## The World

<img width="712" height="668" alt="image" src="https://github.com/user-attachments/assets/150617e5-0837-4aa9-b4dd-a0a2c1920082" />

*   **Biomes:** The map features 3 different biomes: Deserts, Steppes, and Lowlands. Each favors the development of different sectors and contain different levels of resources.
*   **Resources & Agriculture:** Agents autonomously gather raw materials and farm crops based on their needs.
*   **Dynamic Events:** The world is unpredictable and subject to events like natural disasters, food trends, supply disruptions and a Fed/Central bank that will try to control inflation in more or less drastic ways.
*   **The Economy:** Agents interact with a fully functioning open market, organically dividing into distinct comodities and sectors.
*   **The Fed:** A central banking authority dynamically adjusts interest rates, manages the money supply, and fights inflation based on shifting policy stances.

---


## The Industries

<img width="979" height="860" alt="image" src="https://github.com/user-attachments/assets/ca97173a-11c7-41ab-aabf-681be81237c9" />

* **Miners:** Dig gold and sand straight out of the ground, and turn pumped oil into liquid gold at oil rigs.
* **Collectors:** Crush mined stone into iron—by hand, or faster with a crusher(W.I.P) or a fueled tractor.
* **Glassmakers:** Smelt sand into glass and sell it.
* **Landlords:** Own the land or housing others use—take a cut of tenants' crop harvests and lease payments from anyone renting a home from them.
* **Lenders:** Rich folks that esentially turn into private banks, they issue coin loans to other agents and collect the interest.
* **Oil Producers:** Pump crude oil out of the ground and sell it.
* **Farmers:** Work claimed farmland to harvest sugar, potatoes, lettuce, or rice.
* **Retailers:** Buy goods off the open market to resell, and list their own goods for sale to other agents.
* **Traders:** Buy and sell commodities purely to profit from price swings, not to use what they buy.

---

## The Resources

<img width="654" height="351" alt="image" src="https://github.com/user-attachments/assets/22d88dec-9db9-432f-830b-e94b27e2067a" />

* **Sugar:** An imperishable, high-energy crop harvested from farmland, it also results as a low rate byproduct in some farmland.
* **Potato:** A slow-rotting crop grown on farmland.
* **Lettuce:** A fast-rotting crop grown on farmland, it also results as a high rate rate byproduct in most farmland.
* **Rice:** An imperishable, low-energy crop grown on farmland.
* **Stone:** A common material gathered from the ground or surface stone tiles.
* **Glass:** A refined material created by smelting sand.
* **Oil:** Raw fossil fuel pumped from underground deposits, used as energy for machinery.
* **Iron:** A metal obtained from crushing stone either by hand or using a tractor.
* **Gold:** The resource used for coin mintage mined from deposits or mined via drills.
* **Sand:** A cyclical granular mineral gathered from desert deposits (finite) or mined by mining drills, used primarily to smelt glass.

---

## The Machinery

* **Greenhouses:** Placed on land you own, greenhouses boost crop fertility caps and production capabilities. They come in tiers: Tier 1 and Tier 2 use glass to multiply fertility capacity, while Tier 3 uses gold and oil so the tile keeps producing off-season instead of stalling at zero.
* **Tractors:** Crafted using iron, tractors move faster than agents, vacuum up stone across a wide radius while roaming, and crush stone into iron at machine speed while parked. They run on refined oil as fuel and automatically refuel from the market when running low.
* **Mining Drills:** Permanent structures built on owned land that produce gold and sand indefinitely at a distinct rate per tile, depending on the quality of the underground deposit. They start at a lower efficiency and can be upgraded using iron and oil to increase their output. They run on their own oil tanks, which are refueled from the market.
* **Oil Drills:** Permanent structures built on owned land that pump crude oil out of the ground. Unlike mining drills, they run on hired workers whose efficiency scales linearly with headcount. Owners must pay their workers ongoing wages based on the oil's market value.

---

## The Fed

<img width="969" height="881" alt="image" src="https://github.com/user-attachments/assets/afa7a351-8d03-48fe-9dba-16e80ad3da07" />


* **Policy Stance:** A randomized policy stance reshuffled every 50,000 ticks like a new administration, featuring independent axes including hawkishness, pro-people lean, money supply growth targets, and gold alignment.
* **Policy Reviews:** The Fed head reviews policy every 5,000 ticks, incrementally nudging its stances in response to real-time economic conditions like inflation, coin velocity, and gold prices.
* **Dynamic Minting Rate:** Controls currency creation through a velocity-dampened mint rate, burning gold from the treasury to back new coins while managing a structural mint cost target that ratchets during reviews.
* **Money Supply & OMOs:** The Fed targets money supply growth per capita using a smoothed population index, conducting Open Market Operations (OMOs) every 1,000 ticks to drain excess money by selling treasury gold during inflation or inject money by buying gold asks during deflation.
* **Interest Rate Controls:** Sets a base interest rate that shifts between dovish and hawkish stances, forming the foundation that private lenders build upon with their own spreads.
* **Taxation & Welfare Slants:** Influences fiscal policy by applying Fed multipliers to landlord rent taxes and production sales taxes, while skimming a percentage of welfare doles directly into the state reserve based on its gold alignment stance.
* **Emergency Levers:** Under severe inflation, a hawkish head can enforce a hard minting halt for the remainder of their term, or launch emergency gold dump campaigns onto the open market to aggressively sell state gold and permanently burn circulating coins.
* **Drill Loans:** Issues specialized infrastructure loans directly from state reserves to owners of gold and oil drills to keep energy production active when the reserve is flush.
