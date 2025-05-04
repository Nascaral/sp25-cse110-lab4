1. The output is 20 since var is a function scope
2. The output is 20 since var is a function scope, it doesnt matter if its inside the if block
3. You should avoid using var because it causes naming conflicts since it is named across the whole function and also lead to accidental bugs because of its scoping issues.
4. The output is 20 since let is block scoped and line 9 is in the same block
5. The output is error because let is inside the if block making it unaccessable to the outside scope
6. The output is error because if you assign const to a value it cannot be reassigned
7. The output is error because the const is block-scoped and it isnt accessable outside the if.