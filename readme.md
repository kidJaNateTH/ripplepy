# RipplePy
RipplePy is a osu!ripple third party API written in Python by NateTH. Easy to use and have performance

## Installion
Open cmd and type `pip install ripplepy`

## Examples
Returns beatmap
```py
"""Get beatmaps"""
x = ripplepy.ripplepy.get.beatmaps(2365680)
print(x["title"])
print(x["artist"])
print(x["beatmap_id"])
"""
There are results below

    Anoyo-iki no Bus ni Notte Saraba.
    TUYU
    2365680
"""
```
Returns user
```py
"""Get user"""
y = ripplepy.ripplepy.get.user("NateTH")
print(y["username"])
print(y["total_score"])
print(y["country"])
"""
There are results below

    NateTH
    2650460
    TH
"""
```
