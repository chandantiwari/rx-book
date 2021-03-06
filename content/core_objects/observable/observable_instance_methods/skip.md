# skip

`Rx.Observable.prototype.skip(count)`
<a href="#rxobservableprototypeskipcount">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/skip.js "View in source") 

Bypasses a specified number of elements in an observable sequence and then returns the remaining elements.

#### Arguments
1. `count` *(`Number`)*: The number of elements to skip before returning the remaining elements.

#### Returns
*(`Observable`)*: An observable sequence that contains the elements that occur after the specified index in the input sequence.   

#### Example

[](http://jsbin.com/povos/1/embed?js,console)

### Location

File:
- [`/src/core/observable/skip.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/skip.js)

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
- [`/tests/observable/skip.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/skip.js)