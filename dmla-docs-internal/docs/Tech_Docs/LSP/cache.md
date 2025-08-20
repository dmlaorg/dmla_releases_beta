# The LSP Cache

The LSP cache in its current state is far from being a trivial component.

LSP features are to be provided using `ILSPCacheItem<T>` implementations. Cache items are constructed on a per-document and per-feature basis (e.g. an item could handle CodeLens items for a specific document). Cache items can register event handlers for SymbolDB pass lifecycle hooks that can update the 

LSP requests are completed through the cache. If the associated cache item of a specific feature has a valid cached value, the request is served immediately using the cached value. When a cached value is not available, a completable future is returned, that completes as soon as the pass lifecycle hook produces a valid value for the cache item.



State machine diagrams are WIP
Docs are WIP