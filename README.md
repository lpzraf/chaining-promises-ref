# Chaining Promises - Reference
In the example, we are calling getPromise which returns a promise that will resolve in at least 2000 milliseconds. From there, because .then will return a promise, we can continue to chain our .thens together until we throw a new Error which is caught by the .catch method.

Source: tylermcginnis.com