# Loops

Defition: 
- Loops check conditions. If it returns **true**, a code block will run. Then the condition will be checked again and if it still is true, the code blok will run again. It repeats until the condition return **false**. 

Three common types of loops:
- for

```
for (var i=0; i<10; i++) {
  document.write(i)
}
```
var i=0 - initialization
i<10 - condition
i++ - update (ads 1) 

- while 

```
while(numberOFRooms > 0) {
  console.log("vacuum");
  console.log("dust");
  console.log("put things away");
  // numberOFRooms = numberOFRooms - 1
  numberOFRooms --;
}

console.log("I'm done cleaning!")
```

- do while  - similar to `while` loop; one difference: it will always run the statement inside the curly brackets at least once, even if the condcition evaluates to **false**