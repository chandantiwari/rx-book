# flatMapLatest

`Rx.Observable.prototype.flatMapLatest(selector, [thisArg])`
<a href="#rxobservableprototypeflatmplatestaselector-thisArg">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/flatmaplatest.js "View in source") 

This is an alias for the `selectSwitch` method.

 Projects each element of an observable sequence into a new sequence of observable sequences by incorporating the element's index and then transforms an observable sequence of observable sequences into an observable sequence producing values only from the most recent observable sequence.

#### Arguments
1. `selector` *(`Function`)*:  A transform function to apply to each source element.  The callback has the following information:
    1. the value of the element
    2. the index of the element
    3. the Observable object being subscribed
2. `[thisArg]` *(`Any`)*: Object to use as `this` when executing the predicate.
 
#### Returns
*(`Observable`)*: An observable sequence whose elements are the result of invoking the transform function on each element of source producing an Observable of Observable sequences and that at any point in time produces the elements of the most recent inner observable sequence that has been received.    

#### Example

[](http://jsbin.com/vigofe/1/embed?js,console)

### Location

File:
- [`/src/core/observable/flatmaplatest.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/flatmaplatest.js)

Dist:
- [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js)
- [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js)
- [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js)
- [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

Prerequisites:
- None

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`RxJS-Main`](http://www.nuget.org/packages/RxJS-Main/)
- [`RxJS-Lite`](http://www.nuget.org/packages/RxJS-Lite/)

Unit Tests:
- [`/tests/observable/flatmaplatest.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/flatmaplatest.js)