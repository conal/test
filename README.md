# Misc experiments


$$V(s) \, = \max_a \left\{ \sum_{s'} P_a(s,s') \left( R_a(s,s') + \gamma V(s') \right) \right\}$$

The monad-parametrized representation is isomorphic to a state transition function together with an initial state $s$, i.e., $(a \times s \to b \times s) \ \times \  s$ (where $a$ and $b$ are the input and output value types, respectively).
