# Task 2 Result

Equality Score was classified into:
- **Fair**: absolute score <= 10
- **Unfair**: absolute score > 10 and <= 20
- **Highly Discriminative**: absolute score > 20

Excel formula used:
`=IF(ABS(C2)<=10,"Fair",IF(ABS(C2)<=20,"Unfair","Highly Discriminative"))`
