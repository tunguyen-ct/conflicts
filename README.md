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

What is conflict in Git?

Phần "file changes" trong Github tab chính là phần so sánh giữa phiên bản "tôi của hiện tại" so với "tôi của ngày hôm qua".

Tuy nhiên, ký ức về tôi của ngày hôm qua được lưu giữ trong tôi là một snapshot, là một thứ cố định.

Khi tôi muốn nhập tôi của hiện tại với tôi của ngày hôm qua, thì tôi không thể làm được => CONFLICTS.

Bởi vì một ai đó, đã thay đổi "tôi của ngày hôm qua", khiến cho snapshot tôi đang có, khác đi so với cái real. Giờ tôi phải RESOLVE CONFLICTS.

Cách 1: Rebase
Đây là cách mà tôi sẽ cập nhật lại snapshot của mình. Để cho snapshot đó trùng khớp với cái thực.

Cách 2: Merge
Như thế này, thì cái snapshot của tôi cũng sẽ giống như thực, nhưng sẽ có khác đôi chút về history.
