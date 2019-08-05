# TypeScript

## Tools

* <https://typedoc.org/guides/doccomments/>

## Syntax

Write comments are above of target(class/func)

```ts
/**
 * This is a doc comment for a file
 */


/**
 * This is a doc comment for "hoge" class
 */
class hoge() {
  constructor() {
    // ...
  }

  /**
    * description for a method
    * @param arg desc for arg
    * @typeparam T  Comment for type `T`.
    * @returns      Comment for special return value.
    */
  doSomething<T,S>(arg:T):S{
    // ...
  }
}

/**
* description for a func
* @param arg desc for arg
* @typeparam T  Comment for type `T`.
* @returns      Comment for special return value.
*/
function doSomething<T,S>(arg:T):S{
  // ...
}

```
