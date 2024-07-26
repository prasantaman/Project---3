git clone https://github.com/yourusername/lottery-contract.git
cd lottery-contract
aptos move compile

aptos move publish --package-dir path/to/package
Lottery::initializing(&signer)
Lottery::placing_bet(&signer, to_address, amount)
let balance = Lottery::getBalance(&signer)
let total_players = Lottery::allPlayers(store_addr)
Lottery::pickingWinner(&signer)
aptos move test
