# first commit

```js
function greet(name) {
  console.log("Hello " + name);
}
```

# sprint planning

There are two members in the team.

First member is assigned a feature to support Vietnamese, he make a copy of the codebase at the moment and start to implementing.

```js
function greet(name) {
  console.log("Xin chào " + name);
}
```

Second member is assigned a feature to show care for the greeted person, such as asking "How are you?". He also based on the current code base and start to implement.

```js
function greet(name) {
  console.log("Hello " + name);
  console.log("How are you?");
}
```

The first member is merged first because their feature can be done faster. The second go after and encounter merge-conflicts.

...
