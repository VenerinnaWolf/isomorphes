# This program simulates an evolution, using a genetic algorithm
## Isomorphes
Meet the `Isomorphes`, organisms that live in my program. They are not very smart, but they are beautiful. Each `Isomorph` has a rectangular shape and a bright coloring, and can look like anything. Its bizarre coloring consists of multi-colored spots - graphic primitives (ellipses, triangles, rectangles). The color, shape, size and position of each spot are encoded in the `genes` of the organism.

The life of the `Isomorphes` would've been beautiful and carefree if not for a super-predator named `Criticus Vulgaris`. `Criticus` is also not distinguished by intelligence, but he has a subtle artistic taste and violently eats all the `Isomorphes` that do not correspond to his ideals of beauty.

## The work of a Criticus
`Criticus` determines which of the `Isomorphes` are worthy of remaining in the population, and which ones should be eaten. But how? Let's take an example.

`Criticus` likes the specific picture of a cat - this is his ideal. The other picture is one of the `Isomorphes`, awaiting its fate. `Critikus` calculates the "divergence" between the picture-organismus and the ideal.
`Critikus` immediately eats the ugly `Isomorphes` with a high divergence to the ideal for breakfast, and leaves the prettier ones for lunch. Now, the survivors have time to reproduce and restore the population. Moreover, reproduction is the only thing they can do.

## Evolution
Such simple behavior of the predator and victims is enough to launch a real digital evolution. During the evolution, the Isomorph populations go through all of the following stages:
1. **Reproduction**, and the program has two options - **cloning** or **sexual reproduction**, in which the child receives a combination of the parents' genes.
2. Then some genes of the child may **mutate** with a certain chance - randomly change the color, shape, size or position on the `Isomorph's` body.
3. Then comes the stage of **natural selection**. `Criticus` examines two randomly selected organisms from the population, compares them and eats the one with the highest divergence.
4. ...And finally comes the turn of the **next generation**, in which exactly the same thing happens, and so on, and so on until we stop the program, satisfied with the result.

## Download
To see, what's happening here: 
1. Download processing (the official page -> https://processing.org/download/)
2. Download everything from **folder** `evolution` in this repository
3. Run **file** `evolution.pde` and watch the evolution by your own eyes (`Isomorph` on right will try to mimic the ideal `Criticus` picture as on left). You can play with some settings in... "settings". To exit click esc.

For mobile you can download and install `evolution.apk` file.
