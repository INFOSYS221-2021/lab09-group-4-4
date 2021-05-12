1:
Get just retrieves data from a server

https://deckofcardsapi.com/api/deck/new/shuffle/?deck_count=1

2:

Shuffle Cards,
Draw a card,
Reshuffle the cards,
Get a new deck,
Get partial decks (specific suits or cards),
Adding to piles,
shuffling piles,
Listing cards in a pile,
Drawing from pile

3:

https://deckofcardsapi.com/api/deck/new/?jokers_enabled=true

4:

a: 2 card: King of Hearts, 8 of Clubs
b: var deck = {
    "success": true,
    "cards": [
        {
            "image": "https://deckofcardsapi.com/static/img/KH.png",
            "value": "KING",
            "suit": "HEARTS",
            "code": "KH"
        },
        {
            "image": "https://deckofcardsapi.com/static/img/8C.png",
            "value": "8",
            "suit": "CLUBS",
            "code": "8C"
        }
    ],
    "deck_id":"3p40paa87x90",
    "remaining": 50
}

console.log(deck["deck_id"])

c: var deck = {
    "success": true,
    "cards": [
        {
            "image": "https://deckofcardsapi.com/static/img/KH.png",
            "value": "KING",
            "suit": "HEARTS",
            "code": "KH"
        },
        {
            "image": "https://deckofcardsapi.com/static/img/8C.png",
            "value": "8",
            "suit": "CLUBS",
            "code": "8C"
        }
    ],
    "deck_id":"3p40paa87x90",
    "remaining": 50
}

for (card in deck["cards"])
    console.log(deck["cards"][card])

