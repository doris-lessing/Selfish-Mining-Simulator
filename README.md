# Selfish-Mining-Simulator

## inportant terms in blockchain security

- Incentive compatible
- Block race
- Profit threshold: minimal 𝛼 for which employing dishonest mining strategies becomes profitable.
- Block propagation 
- Block withholding

## Markov Chain Model

*Reference: Majority is not Enough* ![link](https://www.cs.cornell.edu/~ie53/publications/btcProcFC.pdf)

![alt markov_chain_model_1](./pictures/markov_chain_model.png)

## Markov Decision Process Model

Reference: 

### A simple Upper bound for profit of Selfish Mining 

Consider an extreme case: If every block mined by the selfish miner could override one block of honest miner, the revenue of selfish miner would be:

```math
\frac{\alpha}{1−\alpha}
```

This is an upper bound for profit of selfish mining.


