<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [vue-router](./vue-router.md) &gt; [stringifyQuery](./vue-router.stringifyquery.md)

## stringifyQuery() function

Stringifies a [LocationQueryRaw](./vue-router.locationqueryraw.md) object. Like `URLSearchParams`<!-- -->, it doesn't prepend a `?`

<b>Signature:</b>

```typescript
export declare function stringifyQuery(query: LocationQueryRaw): string;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  query | <code>LocationQueryRaw</code> | query object to stringify |

<b>Returns:</b>

`string`

string verion of the query without the leading `?`
