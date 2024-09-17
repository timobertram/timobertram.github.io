---
title: "Learning With Generalised Card Representations for “Magic: The Gathering”"
date: 2024-08-05
---
A defining feature of collectable card games is the deck building process prior to actual gameplay, in which players form their decks according to some restrictions. Learning to build decks is difficult for players and models alike due to the large card variety and highly complex semantics, as well as requiring meaningful card and deck representations when aiming to utilise AI. In addition, regular releases of new card sets lead to unforeseeable fluctuations in the available card pool, thus affecting possible deck configurations and requiring continuous updates. Previous Game AI approaches to building decks have often been limited to fixed sets of possible cards, which greatly limits their utility in practice. In this work, we explore possible card representations that generalise to unseen cards, thus greatly extending the real-world utility of AI-based deck building for the game “Magic: The Gathering”. We study such representations based on numerical, nominal, and text-based features of cards, card images, and meta information about card usage from third-party services. Our results show that while the particular choice of generalised input representation has little effect on learning to predict human card selections among known cards, the performance on new, unseen cards can be greatly improved. Our generalised model is able to predict 55% of human choices on completely unseen cards, thus showing a deep understanding of card quality and strategy.


[Link to PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10645602)