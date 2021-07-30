# bug-hide-n-seek
> Just a challenge for my coding partner 🤓

## Hello partner 🖐

This is just a little challenge I did when I was studying for the Micorverse Program admissions.

The function in the code is golf-result-giver, that means that depending on the parameters given to that function (strokes, par) you will have different results:

`score = 1`	"Hole-in-one!"

`score <= par - 2`	"Eagle"

`score = par - 1`	"Birdie"

`score = par`	"Par"

` score = par + 1`	"Bogey"

`score = par + 2`	"Double Bogey"

`score >= par + 3`	"Go Home!"

Anyway... one of the test cases is `strokes = 1` and `par = 1`. It should return "Hole-in-one!", but it's returning "Par". Let's see if you can find the problem. 🤞
