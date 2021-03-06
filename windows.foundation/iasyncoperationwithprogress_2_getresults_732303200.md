---
-api-id: M:Windows.Foundation.IAsyncOperationWithProgress`2.GetResults
-api-type: winrt method
---

<!-- Method syntax
public TResult GetResults()
-->

# Windows.Foundation.IAsyncOperationWithProgress<TResult, TProgress>.GetResults

## -description
Returns the results of the operation.

## -returns
The results of the operation.

## -remarks
### Notes to implementers

Implementers should return the specific value that the operation type should return to callers upon completion. When the method that uses the custom operation type returns, while using an awaitable syntax (the usual usage) this provides the return value of the operation to the method caller.

## -examples

## -see-also
[IAsyncOperationWithProgress&lt;TResult, TProgress&gt;](iasyncoperationwithprogress_2.md)