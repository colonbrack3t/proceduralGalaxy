# proceduralGalaxy
Prodcedurally generated galaxy, using a custom built PRNG algorithm with inexpensive runtimes and random results for consecutive seeds.

Open Generation.html in any browser. Use Arrow keys to move around the universe. Click on stars to view systems

I implemented a Lehmer Algorithm to create random numbers that have random results for consecutive seeds. Simply using the JS random algorithm would create very ordered results. By using seeds, the application can generate any place in the whole galaxy, given coordinates, with consistency (wont ever change whenever you load the same area).

Focus was on light work load for the computer, so things are only generated if theyre needed (e.g. planets are not generated until displayed)


![image](https://user-images.githubusercontent.com/26506402/182030852-3427b683-eb55-45ca-9cd8-d8510e7753e5.png)
