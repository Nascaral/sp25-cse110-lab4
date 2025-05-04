1. the output is 3 because the length of the price is 3 and using var, it is accessible outside of the loop.
2. The output is 150since it is declared with var which is function-scoped and is accessible outside the loop
3. The output is 150 since again it is declared with var making it accessable anywhere
4. Returns [50,100,150] since is the array discounted discounts all the prices and returns them
5. Returns error since let is block-scoped and i is declared in the for loop making it undefined outside of it
6. Returns error since discountedPrice is declared using the let and again making it undefiend outside of it
7. Returns 150 because finalrpice was declared outside the scope using let so its accessible in line 14
8. Returns [50,100,150] since the logic of the discount remains the same
9. Returns an errorbecause i is unaccessible outside the for loop
10. Returns 3 because it is accessible and hold the same value of 3 from prices.length
11. Returns [50,100,150] The logic does not change, it still returns the array of the discounted prices.

12. a. student.name
b. student["Grad Year"]
c. student.greeting()
d. student["Favorite Teacher"].name
e. student.courseLoad(0)

13. a. 32 since + with a string becomes a concatenation, 2 becomes a string and forms 32
b. 1 since - is only numeric, 3 becomes an integer and 3-2 = 1
c. 3, null is treating like 0 integer wise
d. 3null, since '3' is a string, + concatenates and null becomes treated like a string making 3null
e. 4, true = 1 as integer so 3+1 = 4
f. 0, since false = 0 and null =0 as integers
g. 3undefined, since 3 is a string whole thing concatenates
h. NaN since 3-NaN = NaN

14. a. true, since 2 is greated than 1
b. false since it is compared as strings and 2 is > 1.
c. true since == checks if there both equal (type)
d. false since === checks both type and value and 2 is not valued the same as '2'
e. false since true becomes a 1 and 1!=2
f.true since boolean 2 is true and true === true.

15. == checks the values after converting types if they differ, if they dont then its just checking if the type is true but === checks both value and type so no conversion is happeping and for example 2 is not the same as '2'.

17. The output is [2,4,6] this is because for each element that gets looped in the input array, it is getting told to be multiplied by 2 in the callback, and is getting pushed into the newArr function.

18. The output is 1,4,3,2 because console.log runs immediately and settimeout(1000) delays by 1 second and setTimeout(0) runs after the call stack is empty. 