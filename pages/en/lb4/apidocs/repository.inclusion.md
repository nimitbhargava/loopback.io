---
lang: en
title: 'API docs: repository.inclusion'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.repository.inclusion.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [Inclusion](./repository.inclusion.md)

## Inclusion interface

Inclusion of related items

Note: scope means filter on related items

Example: `{relation: 'aRelationName', scope: {<AFilterObject>}}`

<b>Signature:</b>

```typescript
export interface Inclusion<MT extends object = AnyObject> 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [relation](./repository.inclusion.relation.md) | <code>string</code> |  |
|  [scope](./repository.inclusion.scope.md) | <code>Filter&lt;AnyObject&gt;</code> |  |


