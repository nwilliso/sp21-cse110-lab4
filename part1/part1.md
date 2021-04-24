## Part 1a
1] values added: 20

2] final result: 20

3] values added: 20

4] ERROR because result is confined to the code block it was declared in (i.e. the if block) so it is not defined outside on line 13

5] ERROR because line 7 tries changing the value of result but you cannot reassign a const

6] ERROR because it does not make it past the line 7 error of trying to reassign a const (and if it did make it past, result is confined to the if code block and not defined outside it)

## Part 1b
1] 3 because the length of the prices array input is 3 and that is the last value i is updated to thus not meeting the condition of the for loop (var is not confined to the scope of a code block)

2] 150 because 300 * (1 - 0.5) = 150 which is the last value assigned to discountedPrice (var is not confined to the scope of a code block)

3] 150 because 150 * 100 / 100 = 150 which is the last value assigned to finalPrice

4] [50, 100, 150] because the original input is [100, 200, 300], so all those entries times 0.5 (1 minus the discount input) times 100 and divided by 100 is just the entries cut in half

5] ERROR because i is only defined in the for code block and not outside it on line 12 (let is  confined to the scope of a code block)

6] ERROR because discountedPrice is only defined in the for code block and not outside it on line 13 (let is confined to the scope of a code block)

7] 150 because 150 * 100 / 100 = 150 which is the last value assigned to finalPrice (this line is inside the same code block as finalPrice was declared)

8] [50, 100, 150] because the original input is [100, 200, 300], so all those entries times 0.5 (1 minus the discount input) times 100 and divided by 100 is just the entries cut in half

9]  ERROR because i is only defined in the for code block and not outside it on line 11 (let is confined to the scope of a code block)

10] 3 because that is the length of the input array and does not change

11] [50, 100, 150] because the original input is [100, 200, 300], so all those entries times 0.5 (1 minus the discount input) is just the entries cut in half (no error because despite the discounted being const, elements can be added, the array itself just cannot be reassigned)

12a] student.name

12b] student['Grad Year']

12c] student.greeting()

12d] student['Favorite Teacher'].name

12e] student.courseLoad[0]

13a] '32' because integers map to their exact string representation and concatenation is preformed

13b] 1 because numeric strings are converted into numbers for mathematical expressions

13c] 3 because null becomes 0 in mathematical expressions

13d] '3null' because null becomes the string 'null' and concatenation is preformed

13e] 4 because true becomes 1 in mathematical expressions

13f] 0 because false becomes 0 and null becomes 0 in mathematical expressions

13g] '3undefined' because undefined becomes the strinf 'undefined' and concatenation is preformed

13h] NaN because undefined becomes NaN when converting to a number

14a] true because '2' becomes the number 2

14b] false because the first character of '2' is greater than the first character of '12' (i.e. '2' > '1')

14c] true because '2' becomes the number 2

14d] false because strict equality checks equality without type conversion and they are not equal if they are different types

14e] false because true becomes the number 1 which is not equal to 2

14f] true because Boolean(2) = true

15] == checks equality with type conversion whilst === is strict equality which checks equality without type conversion (so items not of the same type will always not be equal)

16] part1b-question16.js

17] [2, 4, 6] because in the for loop looping over the input array [1, 2, 3], callback is called on each element of the array. callback in this code is doSomething which doubles a number, so each element of the original array is doubled and pushed onto our return newArr.

18] part1b-question18.js

19] 1, 4, 3, 2 (where ", " denotes a linebreak) because setTimeout runs after the console logs and 2 has a 1000ms delay while 3 has a 0ms delay