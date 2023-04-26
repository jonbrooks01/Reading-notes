# Class 04 Reading Notes

## React Docs - Forms

1) A controlled component is a way for the state to be controlled by the form allowing react to update that form whenever there is user input, instead of updating it only with setState

2) The state should store the information when the user enters them because there will be less lag between other components since the state is updated as the user inputs information.

3) We can target what the user is inputting by using the event.target.name to specify what value we want to target.

## The Conditional (Ternary) Operator Explained 

1) We can use a Ternary operator to shorten the amount of code we need to write in order to accomplish the same thing. with this operator we can make a if statement turn into a one line code that reads easier then the if statement.

2)if(x===y){
  console.log(true);
} else {
  console.log(false);
}

Turns into;

x === y ? 'true' : 'false'
