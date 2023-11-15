# CollectionExtensions.ToListAsync&lt;TSource&gt; method

Creates an IEnumerable from an IAsyncEnumerable.

```csharp
public static ValueTask<IEnumerable<TSource>> ToListAsync<TSource>(
    this IAsyncEnumerable<TSource> source, CancellationToken cancellationToken = default)
```

| parameter | description |
| --- | --- |
| TSource | The type of the elements of |
| source | The IAsyncEnumerable to create a IEnumerable from. |
| cancellationToken | A token that can be used to request cancellation of the asynchronous operation. |

## Return Value

An IEnumerable that contains elements from the input sequence.

## See Also

* class [CollectionExtensions](../CollectionExtensions.md)
* namespace [TinyHelpers.Extensions](../../TinyHelpers.md)

<!-- DO NOT EDIT: generated by xmldocmd for TinyHelpers.dll -->