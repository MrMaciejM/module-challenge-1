# Challenge 01 - Code Refactor

## Description

In this challenge I have been hired by a marketing company to refactor their existing code to make it more accessible and semantic. Additionally, I need to ensure I further clean up the code and make it more readable - especially CSS, where there is a lot of repeated code that can be consolidated.

## Examples of code consolidation and clean up

In this example I am demonstrating how I have consolidated and cleaned up some of the CSS code.

**Before**

```
.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}
.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}
.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}
```

**After**

```
.benefit-lead,
.benefit-brand,
.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}
```

## Link To The Deployed Application

(https://mrmaciejm.github.io/module-challenge-1/)
