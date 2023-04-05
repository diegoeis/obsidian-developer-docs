<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [obsidian](./obsidian.md) &gt; [Workspace](./obsidian.workspace.md) &gt; [on](./obsidian.workspace.on_15.md)

## Workspace.on() method

Triggered when the app is about to quit. Not guaranteed to actually run. Perform some best effort cleanup here.

**Signature:**

```typescript
on(name: 'quit', callback: (tasks: Tasks) => any, ctx?: any): EventRef;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  name | 'quit' |  |
|  callback | (tasks: [Tasks](./obsidian.tasks.md)<!-- -->) =&gt; any |  |
|  ctx | any | _(Optional)_ |

**Returns:**

[EventRef](./obsidian.eventref.md)
