```typescript
const books:string[] = ['Scrum for all ages','Nancy Drew','Hardy Boyz','Atomic Habits',
                        'Thinking like a UX Researcher']
const authors:string[] = ['Johnson','Sperry','Red','Michael','Jingo']
const laneNumber:number[] = [1,2,3,4,5,6,7]
const bookstore = [
    {book:'Christmas in our hearts',price: 230},
    {book:'Santa and his gifts',price: 240},
    {book:'Merry O Christmas',price: 210},
    {book:'Jose Mari Chan Memes',price: 220},
    {book:'Christmas Village',price: 254},
    {book:'Hanzel and Gretel',price: 230},
    {book:'The Grinch',price: 230}
] 
```
- Use <b>forEach</b> to console log each book in the books array
- Use <b>map</b> to create a new array by transforming the text to lowercase in the authors and books array (make sure to make it in such way that you can easily use it to other arrays)
- Use <b>map</b> to create a new array by transforming each number in the lane aray to its cube equivalent
- Use <b>map</b> to map the book with their corresponding prices
- Use <b>filter</b> to filter out authors with more than 5 characters
- Use <b>filter</b> to filter out book starting with 'C' in the bookstore array 