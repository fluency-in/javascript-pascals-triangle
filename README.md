# JavaScript: Pascals Triangle

Write a program that computes Pascal's triangle up to a given number of rows.

In Pascal's Triangle each number is computed by adding the numbers to
the right and left of the current position in the previous row.

```plain
    1
   1 1
  1 2 1
 1 3 3 1
1 4 6 4 1
# ... etc
```

These tests use jasmine-node, which is a testing framework written for Node.js.

You will need:

* Node.js
* The Node Package Manager (NPM)
* jasmine-node

You can install both Node.js and NPM with a download from nodejs.org: https://nodejs.org/en/download

Use NPM to install jasmine-node:

    npm install jasmine-node -g

To work on an exercise, change to the directory of the exercise:

    cd hello-world

This contains the files for the exercise.

    .
    ├── README.md
    └── hello-world.spec.js

To run a test file, pass it as an argument to the `jasmine-node` command:

    jasmine-node hello-world.spec.js

## Source

Pascal's Triangle at Wolfram Math World [http://mathworld.wolfram.com/PascalsTriangle.html](http://mathworld.wolfram.com/PascalsTriangle.html)

This exercise is from the [JavaScript][javascript] track on [Exercism][exercism]

[exercism]: http://exercism.io
[javascript]: http://exercism.io/languages/javascript



