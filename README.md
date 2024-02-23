# Terracon Hex Quest

Terracon Hex Quest is set to be a 4 player deathmatch strategy game.

<h2>Project Economy & Foundation</h2>

<ul>
<li>Terracon Hex Quest minigame</li>
<li>Prestige Token (ERC721)</li>
<li>Master tax vault</li>
<li>Master game development fund vault</li>
</ul>

<b>Prestige meaning:</b> Based off this you will be ranked in games leaderboard. The top players will receive larger % of fees that are split in between. The better you are at this game, the more revenue your $THEXQ tokens will generate.

<h2>Terracon Hex Quest minigame</h2>

Terracon Hex Quest is going to be minigame that will act as prelude for our grand strategy game Terracon Quest.

In Terracon Hex Quest Players will participate in a buy-in system where 4 players contributes a set amount of $ETH to the game round, creating a total vault. The winner, who successfully dominates the map, claims the entire vault as their reward. Additionally, free play servers are available for casual gameplay. Users set their own round prices when they host lobby rounds.

<ul>
<li>5% of the deposits is taxed to the <b>master tax vault.</b></li>
<li>5% of the deposits is taxed to the <b>master game development fund vault</b></li>
</ul>

Accumulated <b>master tax vault</b> deposits are split throughout the Terracon Hex Quest prestige card holders.

<h2>Prestige Token (ERC721)</h2>

Players will be able to mint the first evert Terracon Quest autonomous world token that will act as your entry point to the unvierse. An ancient greek general.

It will have General name, region where general was born and ethnicity in it's metadata.

All the basic Core functionality of ER721 contract:

- Minting: Functionality to mint new tokens with unique metadata (General name, region, ethnicity)
- Metadata Storage: Efficient storage of token metadata within the smart contract or through a decentralized storage system (e.g., IPFS). <b>Maybe we can store simple String metadata directly on chain for each token? I prepared JSON for this for all tokens </b>
- Transferability: Enabling secure transfers of tokens between addresses.
- Ownership Tracking: Keeping track of who owns which token at any given time.
- Interoperability: Ensuring the token adheres to the ERC721 standard for compatibility with wallets and marketplaces.

Custom functionality needed:

- Storage for Prestige Points: Each token will have associated points that can be updated. Use a mapping structure to associate each token ID with its points.
- Update Function for Prestige Points: A function that allows updating the points of a specific token. This function should be restricted so that only an authorized contract (such as your future game round manager contract) can call it.

![prestige 7](https://github.com/Agathonas/terracon-hex-quest/assets/158577277/60b48d72-124c-43a1-b8f0-205e53490910)
