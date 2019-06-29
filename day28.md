# Objects and Arrays

## Objects group together  a set of variables and functions to create a model of something recognizable in real world. In an object varialbes and functions take on new names.

- in an object: variable becomes known as property; properties tell as things about objects
- in object: functions are known as methods; task assosiated with object
- object in curly braces `{}`
- properties nad functions have name (key) and value
- value of property - string, number, Boolean, array, another object
- value of method - a function

#### creating an object - literal notation:
```
var hotel = {
  name: "Quay",
  rooms: 40,
  booked: 25,
  checkAvailability: function() {
    return this.rooms- this.booked;
  }
}
```

Accessing an object: 
- name of the object, period, name of the property or methos we want to access
```
var hotelNAme = hotel.name;
var roomsFree = hotel.checkAvailability();
```
or
```
var hotelNAme = hotel['name'];
var roomsFree = hotel['checkAvailability']();
```

Construction notation: 
- **new** keyword and the object constructot create a blank object; then we can add properties and methods;

```
var hotel = new Object();

hotel.name = 'Quay';
hotel.rooms = 40;
hotel.bookes = 25;

hotel.checkAvailability = function () {
  return this.romm - this.bookes;
};
```
Update of propeeties values:
```
hotel.name = 'PArk';
hotel['name'] = 'PArk';
```

Clearing property value:
```
hotel.name = ''
```

Deleting:

```
delete hotel.name;
```