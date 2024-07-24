# Ordinals Collections Standards

#### A place for creators &amp; builders to organize ordinal collections

⚠️ This repository is now deprecated, please submit your collections to the creator dashboard for prompt listing

- [Bitcoin Creator Dashboard](https://ordinalswallet.com/creator-dashboard)
- [Doge Creator Dashboard](https://dpge.ordinalswallet.com/creator-dashboard)
- [Bells Creator Dashboard](https://bells.ordinalswallet.com/creator-dashboard)


## Inscription Data `inscriptions.json`

```
[
  {
    "id": "",                    # inscription id
    "meta": {
      "name": ""                 # inscription name
    }
  },
  ...
]
```

Artists can assign unqiue traits to ordinals with `attributes`

```
[
  {
    "id": "",
    "meta": {
      "name": ""
      "attributes": [
        {
          "trait_type": "",        # trait category
          "value": "",             # trait value
        },
        ...
      ]
    }
  },
  ...
]
```
Your inscriptions.json file will look like this:

```
[
  {
    "id": "c387a2656ef973a55df57edd3ac4b26b09865cc3fcb21cfaa4921ead1363f53ai0",
    "meta": {
      "name": "Bitcoin Frog #2989",
      "attributes": [
        {
          "trait_type": "Background",
          "value": "Black",
        },
        {
          "trait_type": "Body",
          "value": "Tron",
        },
        {
          "trait_type": "Clothing",
          "value": "Green Hoodie",
        },
        {
          "trait_type": "Mouth",
          "value": "Cigar",
        },
        {
          "trait_type": "Eyes",
          "value": "Visor",
        }

      ]
    }
  }
]
```
