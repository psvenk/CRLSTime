# Contributing to CRLSTime

Thank you for your interest! Before you contribute, we would like you to know the following things:

## License

By contributing to this project, you agree to release your contributions under the software license described in the file `LICENSE.md` and you affirm that you have the legal right to release the contributed code under that license.

## Code style

This project follows the [Java Coding Style Guide](https://web.archive.org/web/20060228095122/http://developers.sun.com/prodtech/cc/products/archive/whitepapers/java-style.pdf), but with 2 spaces for indentation. More information can be found on [Wikipedia](https://en.wikipedia.org/w/index.php?title=Indentation_style&oldid=908510214#Variant:_Java). It is recommended to read the hyperlinked style guide before contributing code, so that your code will be consistent with the rest of the codebase. While the style guide was written for Java, the same general principles can be applied to JavaScript syntax. Here are some examples of this style:

```js
if (a === b) {
  doSomething();
}
else if (a === 2) {
  doSomethingElse();
}
else {
  document.getElementById("subscribeBtn").addEventListener("click", function() {
    alert("hello");
  });
}

for (var i = 0; i < 5; i++) {
  console.log("hello");
}

function myFunc(arg) {
  if (2 + 2 === 4) {
    return true;
  }
  else {
    return false;
  }
}
```

## Other things to keep in mind

CRLSTime aims for compatibility with old browsers, so please refrain from ES6+ syntax and/or syntax that is not supported on iOS 9 mobile Safari (e.g. [arrow functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions) and [`let`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let)).
