## Which mutation is most dangerous and why? Provide quantitative evidence.

As per attractor analysis, the most dangerous mutation is p53 loss (Mutation A) because it leads to the largest proportion of initial states converging to cancer-like states. In healthy cells, p53 stops division or initiates apoptosis when DNA damage is detected. By removing it, we eliminate the main 'safety brake', leaving the cells to grow even with DNA damage.

## Explain the role of feedback loops. (e.g., MYC → MDM2 → p53)

In short, a feedback loop is when the result of a process loops back to regulate its own activity. In our network, MYC activates MDM2, and MDM2 shuts down p53. It creates a feedback loop: the more growth signals (MYC), the weaker the brakes (p53). That makes the system a self-reinforcing cycle: growth lessens the amount of p53, and even fewer brakes lead to even more growth. It locks the entire system into a self-propagating cancer-like state. That makes it very difficult for the cell to return to a healthy state.

## What are the limitations of this Boolean network model? Discuss 3 specific limitations.

1. **Binary representation** - our model only allows nodes to be “on” or “off.” It cannot express any middle states, which are necessary for correct representation. Realistic gene activity is more akin to a gradient, where expression can be low, medium, or high.
2. **No scale in terms of timing** - the genes are all updated at once, deterministically. In reality, most processes happen at a different speed, and delays can significantly affect the outcome.
3. **Limited scope** - the network is small scale, and only includes a small subset of regulators. It ignores a lot of other contributing variables - for example, we can't predict E2F's role in cancer, because it's missing from our model.