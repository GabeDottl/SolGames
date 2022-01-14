Note: If you're curious to see existing SOTA game ergonomics on Solana: https://learn.figment.io/tutorials/pay-to-play-gaming-on-solana


# TODO
 * Review Unity Multiplay API as an API starting point.
 * MVP use-case:
 * Propose Game Developer-oriented APIs for proposed features
 * https://heroiclabs.com/docs/nakama/client-libraries/unity-client-guide/ & https://www.photonengine.com/en/PUN
 * Check vulnerabilities: https://github.com/project-serum/sealevel-attacks/tree/master/programs
 * Much Later: Anti-cheating mechanics
 * 

Core features:
Wallet web integration plugin (solana unity plugin?)
Create in-game currency
Create in-game character NFT (using NFT art generator)
Transfer account NFT (some royalty mechanisms)
Decentralized asset serving

Choose your order of operations - bid on execution
GameSolPool? executes (free) as long as Pool has money. Pool used to run game executions.
Invite stick + group ban (off-chain vote)




More interesting on-chain features:
Affect character gameplay state
Affect environment gameplay state
Triggered-effects
Define game mechanics
Define transition rules
Run rule over environment for each character

On-chain reputation for Solana apps
* Reputation systems 
https://fatboardgames.com/5-most-common-game-mechanic/
* Worker placement, engine building, Card Draft, Tile Placement, Cooperative

* On-chain moderation
battle resolution system: bfs attacks

Breed character NFT
3D generative in-game NFTs?

CI/CD for Solana Devnet?

Straightforward add-ons:
Wallet custodianship
Online/Offline (and other) bit flips
Create New Coins
Transfer In/Out coins

External References:
* https://www.soldev.app/
* Candy Machine v2 (Multiplex NFT minter): https://twitter.com/marcelc63/status/1480570145193951234
* Excellent Anchor IDL Tweet thread: https://twitter.com/jozanza/status/1481098724008992772