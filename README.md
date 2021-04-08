# Fixed-Effect-Panel-Regression-Model

Fixed Effect Algorithm Design for San Francisco urban traffic data

The Fixed Effects Regression Model has the following mathematical model:
Y it = β 1 X (1, it) + …..... + β k X (k,it) + α i + u it
With i = 1, ......, n and t = 1, ......, T. The α i are entity-specific intercepts that capture
heterogeneities across entities. An equivalent representation of this model is given by
Y it = (β 0 + β 1 X (1,it) + …... + β k X (k,it) ) + (γ 2 D2 i + γ 3 D3 i + ….. + γ n Dn i + u it )
where the D2i, D3i, all the way to Dn i are dummy variables.
The Fixed Effects model can be generalized to contain more than just one determinant of Y
that is correlated with X and changes over time.
