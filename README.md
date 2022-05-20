# 2021
## December (12)
24/12/2021
- Finished NFT Launchpad contracts + Loan Market contracts.
- Started reviewing old Erc20 Launchpad contracts.
- Applied for Sigma Prime Internship (pending).
- Purchased Rust course for Javascipt devs (https://rustforjs.dev/). Kind of want to build all my contracts in Rust and be a first mover on Sol, KSM + Dot.

25/12/2021
- Researching erc20 launchpad protocols (Lukso: rICO, Sushi: MISO) to start building v2 contracts, similar to the NFT launchpad w/ multiple model selectors (much excite!).
- Began building tutorial game (https://www.youtube.com/watch?v=b8YUfee_pzc). Very refreshing to learn something new.
- Started building DutchAuction contract (erc20 launchpad, nft launchpad models, nft marketplace)

29/12/2021
- Reworked NFT Launchpad after reading MISO's factory + model deployment strategy (uses clones). So, made a factory that uses EIP-1167 cloning system and is catered to adding new models later on.
- Learned some assembly when deploying clones w/ the EIP-1167 clone factory contract. (https://blog.openzeppelin.com/deep-dive-into-the-minimal-proxy-contract/)
- Thinking of applying for OpenZeppelin Security Analyst. Probs will get denied but why not apply (.__.).

30/12/2021
- Applied at: OpenZeppelin, Halborn Security (https://twitter.com/HalbornSecurity), Solidity Finance (https://solidity.finance/), Tob: Summer Internship 2022, Certik, Hexens (https://hexens.io/) + Immunefi. Lets see how this goes :O
- Talking at first AMA in the Diversifi discord at 9am (._.) wen lambo?
- Rereading NFT Launchpad contracts for logic bugs

31/12/2021 - 01/01/2022
- Started line-by-line review of NFT Launchpad for B:BC + discovered an on-chain verification method thanks to being inspired by Nil DAO's frontend (https://twitter.com/Nil__dao).
- Started learning Rust! (Up to: https://www.youtube.com/watch?v=n3bPhdiJm9I&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&index=5).

## End Of Year Review

---

# 2022
## Goals
### Career
- Build a bot: MEV, trading, nft bridge, autocompounder/auto-reinvestor, etc.
- Build a web3 game: learn Unity + pixel art.
- Finish building: NFT Objectifier, P2P Flashloans, NFT Staking (?), Erc20 Launchpad.
- Build something new + innovative (maybe in Hackathon).
- Get into blockchain security formally (internship, apprenticeship, etc).
- ~~Get good at testing .-. (JS/Solidity).~~
- Learn Typescript properly.
- Build a mobile web3 app.
- Redo CTFs (D.V.D, Ethernaut, etc).

### Psychological
- Stop being so introverted: Network + make more frens ;-;
- Focus more, stop letting stress drag you down.
- Be more thankful of those around me.
- Don't be so fast to criticise (do it after complimenting on something done well), think about how it makes others feel.

## January (1)
02/01/2022
- Line-by-line review of 3 price models in NFT Launchpad (B:T, B:CC + B:RC).
- Pilled my roommate to learn programming (.<.)

03/01/2022
- Line-by-line review of 2 price models in NFT Launchpad (A:T + A:BC).
- Reading articles on web3 security from Immunifi (Bug bounty article + why it's beneficial!).

03/01/2022 - 04/02/2022
- Sigma Prime internship denied (Applicants had really strong knowledge :o)
- Reading articles on MEV and being more active in the Flashbots discord. Going to learn rust instead of go b/c I think performance is better and I can do more with rust when i learn the language (e.g., rust-based smart contracts).
- Reading some MEV bots (subway, cake_sniper) + learned more assembly and how opcodes work at the low level - especially w/ minimal proxy cloning. 
- Want to watch this (simple arb walkthrough)[https://www.youtube.com/watch?v=wn8r674U1B4&t=1s] but i've had no time b/c of building TheaterDAO. I really want to release it and help everyone! Maybe i'll watch it when i release v1 buyout: fixed UI + cards.
- Reviewing UniswapV2 + V3 create pool func - very interesting how using `salt` can change the created address
- Learned foundry's forge! (lfg, solidity testing!)
- Released token factory on TheaterDAO!
- Finished create buyout: fixed UI on TheaterDAO
- Finished coding the NFT launchpad's first model + wrote tests for 9 dif models
- Created https://theaterdao.xyz from scratch (as of 05/02/2022 working on the card rendering for each sale)
- Started dev'in an airdropper contract for TheaterDAO
- Learning how FNAFs uses sound to envoke fear (horror game study) + how they keep players fearful, avoiding conditioning of the game's horror elements (uses chances + prevents reusable strategies - creating a permanent unknown scenario)
- Studying strategies game devs use to retain retention that psychologically hook players to keep coming back and how it makes them feel (e.g, look boxes, close misses, long term + short term progression) - very interesting b/c there were laws created as a result from this since they use techniques from casinos 
- Started writing up NFT AMM, onchain nft creator + selector concepts. The NFT AMM forced me to learn (UniswapV2's code)[https://ethereum.org/en/developers/tutorials/uniswap-v2-annotated-code/] in depth. This will help w/ creating MEV bots too (super excited .<.)
- Created a community dev chat, very nice to hang out in and surround myself w/ some like-minded-people (connecting more)
- Learning more about IPFS + how ERC721s are actually created (https://www.youtube.com/watch?v=fzH7Gjadmj0)

05/02/2022
- Determined to learn Rust but have no clue where to start.
- Studied 1inch + other mev bots for a bit.
- Wrote sudocode for Charles (my lil arb bot) - a todo + workflow. Now I know what I need to do and how to start developing him. Gameplan: write in js for v0, get it working the way I want it to, try to optimise it + make it faster or update strategies -> optimise it by turning into Rust +/or add new features over time.

06/02/2022
- Started building monitoring system. Learned a lot more about UniswapV2 code - line by line (path[], reserves, kLast)
- Watched (Flashbots: simple arbitrage repo walkthrough)[https://www.youtube.com/watch?v=wn8r674U1B4]. Learned a lot and recommend to anyone.

19 - 21/02/2022
- Completed 7hr Rust Udemy course (Learn by building examples, or something)
- Read learn Rust in 30min article
- Watched (Crust of Rust: Lifetime Annotations)[https://www.youtube.com/watch?v=rAl-9HwD858]

21/05/2022 
> Been a while since I last updated and a lot has happened, including getting depressed for 2 weeks and bouncing into MEV :D
- I have been working on a long-tail mev bot, for a searcher team as a skill demonstration, w/ mempool monitoring, decoding, block refreshing and my first arb algorithm to generate every possible path with a set of predefined paths (e.g, wETH -> USDC -> STAKE -> wSTAKE -> wBTC -> wETH). I literally have no background knowledge for Rust/MEV/Backend but my learning skills are pretty good so thats why I was given a chance (and my Solidity experience, almost 2 yr now). For anyone wanting to get into MEV, my recommendation is build a bot in rust that creates simulations, precomputes incoming txs and determines optimal profit pathways. The majority of profit for us lil guys will be with long-tail opportunities. MEV is such a selfish space so you need to learn by yourself and filter out the psyops (is this psyops? :0). Getting into MEV is so hard but it's so worth it. Just persist and build every day and try to break down everything in a very simple way.
- Launched @TheaterDAO + made a basic website (do need to update to make way more user friendly) - currently requires technical knowledge to use and doesn't display all projects on a single page.
- Almost finish algorithmic auction house; finished semi-algorithmic auction house that just requires the auctioneer to start it.
- Optimised atomic swap contract (now atomic trade).
- Listened to (Permissionless FB founder)[https://m.youtube.com/watch?v=s4VFb9l9RmY&t=13441s&pp=2AGBaZACAQ%3D%3D] + (ETH Amsterdam)[https://www.youtube.com/watch?v=HYPGD2bOMOo&t=22079s].
- I went on anti-depressants but decided to get a gym membership and go everyday instead and it has completely fixed my depression (#fk_anti_depressants).
- Hopefully i'll finish my mev bot in the next couple of days (a simple version at least) and see where I go from there. There is only 1 competitor atm and basically for every day im not competing  is another day that person is making that $$$ (approve 4-5 txs every 20s - around $8-$30 - *cough* wtaf). Just for a simple arb + extra steps. Imagine a liquidation longtail or someshit. Anyway, not much has happened apart from my protocol development pause + beginning of MEV dev. Why? I prefer PvP over PvE ;) I'll finish off some of my old contracts after I get my bot up and running bc im learning so much. I stopped protocol dev bc i reached a point where i wasnt learning much at all. With mev im learning Rust, backend, bot creation, blockchain infrastructure (which is soooo interesting btw), Golang soon, and probs assembly and how shit works at a low level. Super valuable stuff to learn for all sectors of crypto. Anyway, ttyl log <3
- Ty to (swampstream)[https://github.com/swampstream] for keeping me accountable for this :P (hope this helps, fren).
