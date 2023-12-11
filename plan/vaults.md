# banana vaults

* initial launch on osmosis concentrated liquidity pools
* deposits are capped and gated by banana nft ownership
* deposits and withdrawals are processed on a scheduled basis
* banana vault token(BVT, name tbd) tokenizes vault shares:
    * deposits to a vault will mint an equivalent share of BVT-<vault_id>
    * BVT will be redeemable for a proportional share of the vault's assets
    * establish BVT/USDC liquidity pools with vaults to manage them
* a management/commission fee will be paid to the dao
    * initially to be split between the treasury and dao members