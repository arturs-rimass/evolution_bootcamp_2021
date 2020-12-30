# Texas hold 'em and Omaha hold 'em hand evaluator

This is a small algorithm to analyse hands in Texas hold 'em and sort from the weakest to the strongest.

## Installation

The only import that is needed in this project is a library to work with lists.

```scala
import scala.collection.mutable.ListBuffer
```

## Example

Input:
```
texas-holdem 4cKs4h8s7s Ad4s Ac4d As9s KhKd 5d6d
texas-holdem 2h3h4h5d8d KdKs 9hJh
omaha-holdem 3d3s4d6hJc Js2dKd8c KsAsTcTs Jh2h3c9c Qc8dAd6c 7dQsAc5d
five-card-draw 7h4s4h8c9h Tc5h6dAc5c Kd9sAs3cQs Ah9d6s2cKh 4c8h2h6c9c
```
Output:
 ```
Ac4d=Ad4s 5d6d As9s KhKd
KdKs 9hJh
Qc8dAd6c KsAsTcTs Js2dKd8c 7dQsAc5d Jh2h3c9c
Five card draw is not yet supported
```
## Drawbacks

Algorithm cannot provide 100% functionality, since it doesn't support Five Card Draw.


