# proceduralGalaxy
Prodcedurally generated galaxy, using a custom built PRNG algorithm with inexpensive runtimes and random results for consecutive seeds.

Open Generation.html in any browser. Use Arrow keys to move around the universe. Click on stars to view systems

I implemented a Lehmer Algorithm to create random numbers that have random results for consecutive seeds. Simply using the JS random algorithm would create very ordered results. By using seeds, the application can generate any place in the whole galaxy, given coordinates, with consistency (wont ever change whenever you load the same area).

Focus was on light work load for the computer, so things are only generated if theyre needed (e.g. planets are not generated until displayed)

<img width="905" alt="Screenshot 2022-09-06 at 10 44 55" src="https://user-images.githubusercontent.com/26506402/188603423-f5677905-0f66-4ff5-8c5d-4e592a8e9ab1.png">
