# Review of JavaScript .map() statements

`const numbers = [0, 1, 2, 3, 4]`

`let newNumbers = []`

`for (let i = 0; i < numbers.length; i++) {
  newNumbers.push(numbers[i] * 10)
}`

``numbers``

``newNumbers``

# with .map()
`numbers.map((num) => {
  return num * 10
})`

# with React
`numbers.map(num => <div>{num}</div>)`
