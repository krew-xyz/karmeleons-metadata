# karmeleons-metadata

##Official Metadata of the Karmeleons NFT collection on Ethereum

Help us keep track of the 2,000 Karmeleon NFTs being burned by updating metadata of burnt assets. Burned Karmeleons belong to a `BurnAddress` wallet and are no longer purchasable/tradable on the secondary market.

The contract this collection minted from does not have a public burn method, so although the NFTs get transferred to the burn wallet, they are not physically removed from the total supply.

The goal of this repo is to crowdsource updates and curate the collection's metadata so it is easy to see which Karmeleons were burned when browsing marketplaces.

To make updates, pull down this repo and update the `.json` files belonging to the burned assets. Here's an example of a burned asset, and the changes that need to be made to its metadata:


###Example of current metadata of Karmeleon #1:

```
{
    "name": "Karmeleon #1",
    "description": "The year is 3333. Humankind has vanished. Reptiles appear to be the new sole inhabitants of earth. An abandoned city, aka Karma City, fueled by a mysterious karmic power source sustained only by good vibes has been claimed by a group of chill lizards known as the Karmeleons, hellbent on looking dope and paying it forward.",
    "image": "ipfs://QmWxKBgV4ACXbhAJBs8iojGSzYEVJw1ashCZvMYGXAq4Sf/1.png",
    "dna": "87faa6a64b333c8f892951884c6008398ed4fe03",
    "edition": 1,
    "date": 1639109768323,
    "attributes": [
        {
            "trait_type": "Background",
            "value": "Light Yellow"
        },
        {
            "trait_type": "Skin",
            "value": "Metagold Black Tats"
        },
        {
            "trait_type": "Clothing",
            "value": "Black Tee"
        },
        {
            "trait_type": "Necklace",
            "value": "Gold Chain"
        },
        {
            "trait_type": "Eyes",
            "value": "Scar"
        },
        {
            "trait_type": "Earring",
            "value": "Diamond Stud"
        },
        {
            "trait_type": "Headwear",
            "value": "Swarm Halo"
        },
        {
            "trait_type": "Mouth",
            "value": "Karmic"
        }
    ],
    "compiler": "Karmeleons Art Engine"
}
```

###Example of updating the metadata of Karmeleon #1 if the asset was burned:

```
{
    "name": "Karmeleon #1",
    "description": "This Karmeleon has transcended. To gain access to The KREW community, visit https://thekrew.xyz for more info.",
    "image": "ipfs://__CID__/1.png",
    "edition": 1,
    "attributes": [
        {
            "trait_type": "Transcended",
            "value": "Yes"
        }
    ]
}
```

I will update the `__CID__` values shortly. Thanks fam!