You cannot use try-catch statements to handle exceptions thrown asynchronously, as the function has "returned" before any exception is thrown. You should instead use the `promise.then` and `promise.catch` methods, which represent the asynchronous equivalent of the try-catch statement.

- REF: https://stackoverflow.com/a/24977580

