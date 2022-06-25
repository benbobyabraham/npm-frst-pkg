# This is my first package

### Author: Ben Boby

> This package was made for testing out how packages were created and deployed to the npm package registry. It will be deleted at a later time.

> Removes duplicate array entities

## Sample Usage

```
const removeArrayDuplicates = require('rem-arr-dups') 
let myNums = [1,2,3,1,4,1,2,5,3,4]
let uniqueNums = removeArrayDuplicates(myNums)
console.log(uniqueNums)
```