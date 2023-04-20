---
id: mk.event_target
title: event\_target class
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[mk](./mk.md) &gt; [event\_target](./mk.event_target.md)

## event\_target class

**Signature:**

```typescript
declare class mk_event_target<CT> extends cc.EventTarget 
```
**Extends:** cc.EventTarget

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [key](./mk.event_target.key.md) |  | { \[k in keyof CT\]: k; } |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [clear()](./mk.event_target.clear.md) |  |  |
|  [emit(type\_, args\_)](./mk.event_target.emit.md) |  |  |
|  [hasEventListener(type\_, callback\_, target\_)](./mk.event_target.haseventlistener.md) |  |  |
|  [off(type\_, callback\_, this\_)](./mk.event_target.off.md) |  |  |
|  [on(type\_, callback\_, this\_, once\_b\_)](./mk.event_target.on.md) |  |  |
|  [once(type\_, callback\_, this\_)](./mk.event_target.once.md) |  |  |
|  [request(type\_, args\_)](./mk.event_target.request.md) |  | 请求（等待返回） |