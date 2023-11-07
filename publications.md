---
layout: page
title: Publications
permalink: /publications.html
ref: publications
order: 2
---

- ## BETA-FL: Blockchain-Event Triggered Asynchronous Federated Learning in Supply Chains
    Mayank Gulati, Narges Dadkhah, Benedikt Groß, Gerhard Wunder, Jovan Glavonjic, Aleksandar Pavlovic and Aleksandar Tomcic

    ### Abstract
    ---
    BETA-FL provides a distributed federated learning framework implemented for supply chains by tightly integrating private-permissioned blockchain for the trusted alliance among various actors involved in the supply chain. With a trusted ledger as the moderator in federated learning workflow, our approach ensures protection against malicious backdoor attacks on performance from both server and clients. Additionally, our asynchronous training regime allows scalability to a large number of federated clients with small and constant delay caused due to an event-triggering scheme. We showcase the milk powder classification task as a potential use-case in the food supply chain to avoid food wastage. Finally, we facilitate a dedicated channel for regulatory bodies in our blockchain environment for inspections and audits pertaining to the functioning of the supply chain.

    Keyphrases: Asynchronous Training, Blockchain, Decentralized Machine Learning, Federated Learning (FL), Hyperledger Fabric (HLF), supply chains

    Links:	[https://easychair.org/publications/preprint/pZdN](https://easychair.org/publications/preprint/pZdN)

- ## Differentially Private Synthetic Data Generation via Lipschitz-Regularised Variational Autoencoders
    Benedikt Groß, Gerhard Wunder

    ### Abstract
    --- 
    Synthetic data has been hailed as the silver bullet for privacy preserving data analysis. If a record is not real, then how could it violate a person's privacy? In addition, deep-learning based generative models are employed successfully to approximate complex high-dimensional distributions from data and draw realistic samples from this learned distribution. It is often overlooked though that generative models are prone to memorising many details of individual training records and often generate synthetic data that too closely resembles the underlying sensitive training data, hence violating strong privacy regulations as, e.g., encountered in health care. Differential privacy is the well-known state-of-the-art framework for guaranteeing protection of sensitive individuals' data, allowing aggregate statistics and even machine learning models to be released publicly without compromising privacy. The training mechanisms however often add too much noise during the training process, and thus severely compromise the utility of these private models. Even worse, the tight privacy budgets do not allow for many training epochs so that model quality cannot be properly controlled in practice. In this paper we explore an alternative approach for privately generating data that makes direct use of the inherent stochasticity in generative models, e.g., variational autoencoders. The main idea is to appropriately constrain the continuity modulus of the deep models instead of adding another noise mechanism on top. For this approach, we derive mathematically rigorous privacy guarantees and illustrate its effectiveness with practical experiments.

    Links: [https://arxiv.org/abs/2304.11336](https://arxiv.org/abs/2304.11336)
