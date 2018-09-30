### Harbour MVP Call 0

- https://youtu.be/tKOtWPopl8Q

- Notes are timestamped on the youtube link. This is found in the youtube comment section.

### Notes

Notes for the meeting:

8:08 Discussion starts about Meta-tx MVP

- Trusted parties (design assumption for MVP), we take care of game theory and economics later

10:21 Feedback on Meta-tx project so far and on MVP + acknowledges the need for standards

12:00 Discussion around the need for standards: smart contract signing, smart contract interface

- Only trust contract with a certain byte code?
- How to trust code? Contract factory?

15:00 Starts talking about collision problem / meta-tx propagation amongst service nodes

- Cryptoeconomic design
- Need consensus on who will execute meta-tx
- Service nodes need to be incentivised to share messages as well - routing?
- Transaction rules for rewards -

25:30 Still talking about game theory incentives for service nodes to share network meta-tx messages with each other

-> Need to figure what what we want to incentivise using cryptoeconomic design

-> Design decisions about whether dapps can setup their own service network and prioritise the use of it - implications?

28:00 MVP still requires collision resistance, just simple design with trusted parties. Something that just works.

- Concerns about how designing for trusted party MVP will be completely different to open protocol (need to be careful with previous engineering biases when tackling the problem of open participation)

- 1 hr split up into network participants, participants stake and get a chunk of the meta-txs during their allocated time?

35:00 ~ varied discussion about things - not too important

- token access to use service node network?
- ux problems on paying for service

41:20 Talk about next steps: Sharing standards

- video demo, contract interfaces
- share demo asynchronously 

- Build docker scafolding for the service node network

- Goal to standardise on DEVCON
- Admin of the keys need to be standardised as well
- Any in-person meetings: berlin, prague before devon, devcon

- We need to check out messages and calls -> differences and similarities eg. I want this argument to be here and in this order and this is why

- Involvement of other standards eg. ERC191, identity ERC standards

- Gnosis safe has upgradeable contracts, wants to follow standards though, preferably to be compatible.
