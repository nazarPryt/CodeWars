function sumTwoSmallestNumbers(numbers) {
var [ a, b ] = numbers.sort((a, b) => a - b)
return a + b
}