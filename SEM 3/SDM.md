# SDM

<table>
  <tr>
    <td>Unit</td>
    <td>Topics</td>
    <td>Status</td>
  </tr>
  <tr>
    <td rowspan=9>Graph theory</td>
  </tr>
    <tr>
    <td>Definition and types</td>
    <td>✔️</td>
  </tr>
    <tr>
    <td>Handshaking lamma</td>
    <td>✔️</td>
  </tr>
    <tr>
    <td>Isomorphism</td>
    <td>✔️</td>
  </tr>
    <tr>
    <td>Matrix represenation</td>
    <td>✔️</td>
  </tr>
    <tr>
    <td>Theorem</td>
    <td>✔️</td>
  </tr>
    <tr>
    <td>Kruskal</td>
    <td>✔️</td>
  </tr>
    <tr>
    <td>Dijkstra</td>
    <td>✔️</td>
  </tr>
    <tr>
    <td>Euler and hamilton</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td rowspan=7>Probability</td>
  </tr>
    <tr>
    <td>Poisson distribution</td>
    <td>✔️</td>
  </tr>
    <tr>
    <td>Geometric distribution</td>
    <td>✔️</td>
  </tr>
    <tr>
    <td>Uniform distribution</td>
    <td>✔️</td>
  </tr>
    <tr>
    <td>Exponential distribution</td>
    <td>✔️</td>
  </tr>
    <tr>
    <td>Normal distribution</td>
    <td>✔️</td>
  </tr>
    <tr>
    <td>Gamma distribution</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td rowspan=4>Joint probability</td>
  </tr>
  <tr>
    <td>Discrete</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td>Continous</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td>Markov chain</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td rowspan=6>Statistical interface</td>    
  </tr>
  <tr>
    <td>Large sample(z)</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td>Small sample(t)</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td>Paired t</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td>F distribution</td>
    <td>✔️</td>
  </tr>
      <tr>
    <td>Chi-square distribution</td>
    <td>❌</td>
  </tr>
  <tr>
    <td rowspan=5>Combinations</td>
  </tr>
  <tr>
    <td>Bionomial and polynomial theorem</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td>Inclusion Exclusion</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td>Catalan number</td>
    <td>✔️</td>
  </tr>
  <tr>
    <td>Deaarangement</td>
    <td>✔️</td>
  </tr>
</table>


## Joint Probability Distribution Formulas


| Expression | Discrete | Continuous |
|-----------|----------|------------|
| p(x,y) | P(x=x, y=y) | f(x,y) |
| f(x) | ∑ᵧ p(x,y) | ∫ f(x,y) dy |
| f(y) | ∑ₓ p(x,y) | ∫ f(x,y) dx |
| E(x) | ∑ₓ x f(x) | ∫ x f(x) dx |
| E(y) | ∑ᵧ y f(y) | ∫ y f(y) dy |
| E(xy) | ∑ₓ ∑ᵧ x y p(x,y) | ∫∫ x y f(x,y) dx dy |
| V(x) | E(x²) − [E(x)]² | E(x²) − [E(x)]² |
| V(y) | E(y²) − [E(y)]² | E(y²) − [E(y)]² |
| COV(x,y) | E(xy) − E(x)E(y) | E(xy) − E(x)E(y) |
|ρ(x,y)|COV(x,y)/[σ(x)σ(y)]|COV(x,y)/[σ(x)σ(y)]|

## Markov Chain
1. Identify states
2. Build the transition matrix
3. Identify the initial state
4. Compute pⁿ
5. Compute Fixed Probability Vector V

