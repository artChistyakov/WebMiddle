# This is my repository
## My name is Artem
![this is img](https://cdn-icons-png.flaticon.com/512/4123/4123763.png)

**I`m javascript devoloper.**
*There is Example of my code:*
```javascript
$("input").on("change", function () {
  let user = $("input").val();
  $.ajax(`https://api.github.com/users/${user}`, {
    success: function (result) {
      $("#result").html(`
        <h3>${result.login}</h3>
        <img src="${result.avatar_url}">
        <a href="${result.html_url}">link</a>
      `);
    },
  });
});
```
This is Unordered list:
* [my facebook](https://facebook.com/)
* [my instagram](https://instagram.com/)
