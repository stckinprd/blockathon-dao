# Blockathon Bounties
These are the available blockathon bounties for the 2022 Blockathon Hack

## Submission
Please sign up here: [https://blockathon.devpost.com/](https://blockathon.devpost.com/) for the DevPost Submissions. Submissions will begin on the 18th of March 2022. Only new projects will be assessed. 

## Hypercore	
Prize: 2 KSM, 3 winners	

Dynamic storage	

Use hypercore's mutable, append-only, nature to store and propagate dynamic content among users of your project. You may use "hyperdrives" to store file-like content in a filesystem-like way, or directly work with hypercores or hyperbees - raw append-only logs and trees respectively - to store data more directly. Using the hyper* stack for longer term storage purposes qualifies for this bounty. As a prerequisite, If storing user owned data or content, ensure that users store data in hypercores/drives that they control personally. Projects can claim this bounty alongside others from DatDot, and maybe other sponsors as well, depending on their criteria.


## Hypercore
Prize: 3 KSM, 3 winner

Caching	

Use hyper* (cores, drives, swarms, bees, etc.) as a decentralized caching/access layer for an api you use or provide. API request responses can be stored and retrieved like files in a hyperdrive, or key value entries in a hyperbees. Those stored API responses can then be retrieved in a decentralized manner by querying the swarm, instead of connecting to a central API endpoint. Populate and update your hypercore-based storage as appropriate for your usecase and use it for DDoS protection, cost reduction, and performance improvements for your API endpoints. Projects can claim this bounty alongside others from DatDot, and maybe other sponsors as well, depending on their criteria.

## Hypercore	
Prize: 2 KSM, 3 winners

Live Content

Make use of hypercores' dynamic nature to share live or streaming data - this includes usecases as simple as chat or more complex usecases like streaming video, audio, or complex data/state. Hypercores are very performant in terms of update propagation, (in comparison to primitives like IPNS, using a blockchain, or propagating updates via a DHT,) among their peer swarms, and can be used for near-realtime communication among small swarms of peers (and automagic load balancing for heavier usecases or larger amounts of peers). Take advantage of this property to allow live communication between peers in your project. An example quick and dirty submission could automatically record your screen or webcam into many small video files in a designated folder, and automatically play back video files in sequence from another designated folder as new ones are added, you could then use hyperdrive or hyperspace to sync folders between peers for a rudimentary p2p video chat. Projects can claim this bounty alongside others from DatDot, and maybe other sponsors as well, depending on their criteria.

## Cryptosat.io	
Prize: 500 USDC (TBC)	

Space Inventor: 

Propose ways to use crypto satellites and extend the Cryptosat Simulator with new use-cases.

## Cryptosat.io	
Prize: 100 USDC (TBC)	

Space Debugger	

Help us find and fix bugs in the Cryptosat Simulator.

## Cryptosat.io
Prize: 500 USDC (TBC)	

Space Designer

Design a cool new theme (or improve the current) for the Cryptosat Simulator.

## Talisman
Prize: 500 USDC

Integrate Talisman

Build a dapp on any Parachain which leverages Talisman

## Metis
Prize: $500

Build your DAO Tooling DApps on the EVM-equivalent Metis Layer 2
Decentralized Autonomous Organization (DAO) Management Tooling Track: Build a Bounty Platform, Voting Tools, Payroll Management, Timelock, Knowledge Management Tools, or related DAO Tooling on the EVM-equivalent Metis Layer 2

## Metis
Prize: $500

We are looking for projects that deliver value to a DAO. In this case, solutions that make participating in a DAO easier to do, more transparent, and/or more rewarding.	

## SmartTokenLabs
Prize: $3000 USD

1 bounty $1500 USD
5 bounties $300 ea

Judging Criteria: Creativity, Use case, Collaboration with other projects

Entry Submission
Create a PR against our examples repository https://github.com/TokenScript/token-negotiator-examples, then add to the DevPost. Our judging panel will review your concept 🚀

## Deep DAO 
Prize: $1000 between 3 winners.

This one goes to all the DAO people, researchers, governance nerds

If you’re a DAO enthusiast at heart, and have the connections and drive to change the state of governance in the world. In a word, it's for DAOists. The top 3 people who onboard the most users to DeepDAO's governance profiles will win the prize. 

How to win?
Search on our site for anyone in the top 10,000 ranked profiles of DAO activity, and have them log in with their wallet and write in their description that they were onboarded by you. 

Tip on how to find the top 10k users: 

Head over to DeepDAO.io main Organizations dashboard, browse the organizations members tab, and find the people who are the most involved, those who created the most proposals and voted the most. They are the most active people, and the ones you're looking for. Go to their profiles, and then find them where they are: in their DAO's discords, on twitter, in Snapshot or Aragon or DAOhaus. In the process you will learn the ecosystem and gain the knowledge of the early adaptors and innovators in the field. 

Good DAO luck!

## Algorand
Prize: 1st Prize 2500 Algos; 2nd Prize 1500 Algos; 3rd Prize 1000 Algos (up to 3 winners only)

Overview

Category: Development

Experience Level: Intermediate / Advanced

Mode: Cooperative

Description / What is this task?
For anyone who'd like to participate, please sign up at https://blockathon.xyz/. Only the signups via this website can be acknowledged as a successful application.

1. Blockathon Completion
Participate and complete the Blockathon DAO weekend, build on Algorand and present your team idea on demo day (Sunday 20 March) and win a prize.

## Aleph.im network Stats dashboard Project
Prize: TBC

Idea
The idea is to have an Aleph Stats web application, which would show all available info on aleph network and running nodes. All available public data would be used to compile and track aleph network usage.

Possible data to be used
- Aleph network
- Core channel nodes stats (total, active)
- Compute resource nodes stats (total, linked)
- Staked info (stakers, node operators)
- Staking APY
- Core channel node reward
- Compute resource node reward
- List of core channel nodes and their parameters
- List of compute resource nodes and their parameters
- Staking/unstaking actions history
- Storage usage: visualize the consumption/usage of storage on Aleph network 
- Visualize the compute resources consumption / usage 

Core channel nodes metrics
Scrape metrics from all nodes (if metrics endpoint is available for the given node)
- pyaleph_build_info
- pyaleph_status_peers_total
- pyaleph_status_sync_messages_total
- pyaleph_status_sync_permanent_files_total
- pyaleph_status_sync_pending_messages_total
- pyaleph_status_sync_pending_txs_total
- pyaleph_status_chain_eth_last_committed_height
- pyaleph_processing_pending_messages_seen_ids_total
- pyaleph_processing_pending_messages_gtasks_total
- pyaleph_processing_pending_messages_tasks_total
- pyaleph_processing_pending_messages_action_total
- pyaleph_processing_pending_messages_messages_actions_total
- pyaleph_processing_pending_messages_i_total
- pyaleph_processing_pending_messages_j_total
- pyaleph_status_chain_eth_height_reference_total
- Pyaleph_status_chain_eth_height_remaining_total

Compute resource nodes metrics
- Scrape status pages from all nodes
- Deploy test application that exposes available host info and call it on all nodes

Expose grafana charts
- Expose grafana charts for public info available from all nodes and private info from partnering nodes.

Additional utility
- Set alarms for nodes going inactive/offline, used by:
- Stakers, to see if node they are staking is active/inactive/fully linked
- Core channel node operators, to see if their node is active/inactive/fully linked
- Core channel node operators, to see if their node is critical on a metric
- Compute resource node, to see if their node is operating and linked

