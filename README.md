# bioJanitors: We crunch data fast, to make plastic’s the past! 

A project to discover novel high-efficiency plastic-degrading enzymes to solve the world's plastic pollution problem.

### GOAL:  Discover new PETase, and prioritize stable, high-activity enzymes for industrial application.

There are 400 Million tons of Plastic Waste piling up annually. We can help solve this problem by discovering a more Efficient Plastic-Digesting Enzymes.

The global plastic crisis isn’t just an environmental crisis, it is also a health crisis as microplastics are found throughout the human body, even in the brain where it is suspected of unbalancing the endocrine system. This is the PETase enzyme, it was discovered in a groundbreaking 2016 paper, and it can be found ubiquitously, in plastic bottle recycling plants, at the bottom of the Labrador sea and even in the very soil we walk on everyday. In nature, this enzyme is very slow at breaking down plastics, so if we want any hope of making any dent in the 400 million tons of annual plastic waste, we would need to find and make a more efficient PETase.

To address the inefficiency of PETase in breaking down plastics, we are employing a cutting-edge approach by reconstructing the evolutionary history of reference PETase enzymes (MUSCLE-3D, IQTREE). We used this phylogenetic tree (a type of graph) to trace the relationships between known PETases. Since meta-data describing these enzymes is sparse, we invented a new algorithm `PhyloDiffuse` to propegate quantitative meta-data (such as Temperature) across the phylogenetic network, and impute missing temperature values. This helps us identify versions of the enzyme that may have evolved to work more efficiently under specific environmental conditions,  such that we can select enzymes tailor-fit to function in given environments such as higher temperatures or extreme pH levels.

To focus validation and assay of PETase on thermo-stable enzyme candidates, we deployed the large-language model, TemBERTure,  to predict thermostability (melting temperature) form amino acid sequence alone. a BERT-based model for protein sequence analysis, we predict the stability of each variant by estimating its melting temperature—a critical factor for enzyme efficiency in breaking down plastic under various environmental conditions. To select optimal enzymes further, we created a heuristic measurement called the `Cleft Distance` to approximate the accessibility of the PETase catalytic site. This will allow us to test if more "open" catalytic sites will be able to target high-crystalline PET (i.e. plastic waterbottles) and thereby be a more efficient recycling enzyme.  We evaluated this metric by utilizing molecular docking simulations (ChimeraX), to study how the PET plastic ligand binds into the PETase catalytic pocket.

Ultimately, our goal is to find and engineer the most efficient PETase variant, one capable of significantly reducing global plastic waste.

By leveraging phylogenetic analysis, predictive modeling, and molecular docking, we aim to discover and optimize PETase variants that can degrade plastic more efficiently. This innovative approach offers a promising solution to the global plastic crisis, paving the way for more effective biotechnological interventions in tackling plastic pollution.

## Deliverables
- [GitHub Protocols + Data](https://github.com/ababaian/bioJanitors)
- [BioJanitors Excel Data]()
- [bioJanitor Final Slide Presentation](https://docs.google.com/presentation/d/1_GvFtgDqDqraPgKuhtO-sfDDGfQaLnmtQj8p1yDaBA0/edit?usp=sharing)


## Contribute

Contributions are welcome! If you'd like to contribute, please open an issue or submit a pull request. See the [contribution guidelines](CONTRIBUTING.md) for more information.
