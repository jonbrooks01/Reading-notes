# Class 02 Reading Notes

## An introduction to NodeJS and Express

1) Middle ware is like a bridge between different applications or systems. You can think of middleware as a translator helping bridge the gap so that communications is easier for everyone.

2) Node web framework

3)Unopinionated frameworks, by contrast, have far fewer restrictions on the best way to glue components together to achieve a goal, or even what components should be used. They make it easier for developers to use the most suitable tools to complete a particular task, albeit at the cost that you need to find those components yourself.

4)A module is a javaScript library/file that is imported using the node's require() function. Developers find modules useful due to the fact that all your code doesn't need to be in one file. Developers can separate their code into several files and then import them to the main file. This allows the code to be read more clearly

## What is NPM?

1) What version am I running? 9.6.7
2) npm install jshint

## What is TDD

1) Tests are small programs that are designed to verify that the software works as intended. They simulate various scenarios and check if the software is suppose to behave like it should.

2) There are significant reductions in defects, tests can lead to improved design qualities in the code and a higher degree of technical quality with the code.

3)forgetting to run tests frequently, writing to many tests at once. Some team pitfalls are partial adoption(only a few developers will use them) and poor maintenance of the test suit.

## CI/CD

1) Three benefits of Continuous integrations are Early detection of issues, since the team uploads to the same repo there is a test whenever there is a change to the repository. There is faster feedback with a faster feedback loop, as soon as there is an issue with a commit the developers are notified that there is an issue enabling them to fix the issue right away. Continuous integration also gives confidence with the code that is written since there are tests that happen every time there is a commit.

2) Continuous delivery is an extension of continuous integration. It allows the software to be ready to deploy whenever needed it stages the software for the next phase, Continuous deployment is where the product is ready for the production phase and passes all the checks needed.

3)Github serves as a collaboration tool between developers that integrates CI/CD. it allows developers to manage their code, perform test and integrate the deployments process.
