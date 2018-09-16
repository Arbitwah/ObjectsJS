# ObjectsJS
Improve our example RPG program to add an experience property named xp to the character. Its initial value is 0. Experience must appear in character description.
// TODO: create the character object here

// Aurora is harmed by an arrow
aurora.health -= 20;

// Aurora equips a strength necklace
aurora.strength += 10;

// Aurora learn a new skill
aurora.xp += 15;

console.log(aurora.describe());
Modeling a dog
Complete the following program to add the dog object definition.
// TODO: create the dog object here

console.log(`${dog.name} is a ${dog.species} dog measuring ${dog.size}`);
console.log(`Look, a cat! ${dog.name} barks: ${dog.bark()}`);
 
Modeling a bank account
Write a program that creates an account object with the following characteristics:
•	A name property set to "Alex".
•	A balance property set to 0.
•	A credit method adding the (positive or negative) value passed as an argument to the account balance.
•	A describe method returning the account description.
Use this object to show its description, crediting 250, debiting 80, then show its description again.
