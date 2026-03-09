[back to assessments](https://github.com/dr-matt-smith/FEDev---assessment-samples-and-walkthroughs?tab=readme-ov-file) <<<

[Question 1](https://github.com/dr-matt-smith/FEDev---sample-lab-test-question-1)
| 
Question 2
| [Question 3](https://github.com/dr-matt-smith/FEDev---sample-lab-test-question-3)
| [Question 4](https://github.com/dr-matt-smith/FEDev---sample-lab-test-question-4)
| [Question 5](https://github.com/dr-matt-smith/FEDev---sample-lab-test-question-5)
| [Question 6](https://github.com/dr-matt-smith/FEDev---sample-lab-test-question-6)


# FEDEv - SAMPLE lab test question 2

The "brief" for the test is a PDF file in directory "brief"

NOTE:
**no use of AI is permitted in the lab test**

There are videos for each of the 6 questions:


The files in this repo are the solution I created to this sample test
- you may use any editor available on the university PCs
  - I used Celbridge, which you may install on the lab PCs if you wish

## Question 2 - video

- question 2
  - https://go.screenpal.com/watch/cOeh0anZFk6
  - 2mins 42secs


## Question 2a `isEven()`

We need to create a directory `/src/lib/util`

In the new directory we need a function to test if a number is even - a simple way to do this is to check if integer division (`%`) by 2 leaves zero remainder:

`/src/lib/util/useful_functions.js`

```javascript
export function isEven(n) {
    if(n % 2 == 0){ 
        return true;
    }

    return false;
}
```

## Question 2b `isNeutral()`

In the new directory we need a function to test if a number is equals 7 or not:

`/src/lib/util/useful_functions.js`

```javascript
export function isNeutral(ph) {
  if(ph == 7){
    return true;
  }

  return false;
}
```