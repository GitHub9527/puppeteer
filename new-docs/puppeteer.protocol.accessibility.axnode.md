<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Accessibility](./puppeteer.protocol.accessibility.md) &gt; [AXNode](./puppeteer.protocol.accessibility.axnode.md)

## Protocol.Accessibility.AXNode interface

A node in the accessibility tree.

<b>Signature:</b>

```typescript
export interface AXNode 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [backendDOMNodeId](./puppeteer.protocol.accessibility.axnode.backenddomnodeid.md) | [DOM.BackendNodeId](./puppeteer.protocol.dom.backendnodeid.md) | The backend ID for the associated DOM node, if any. |
|  [childIds](./puppeteer.protocol.accessibility.axnode.childids.md) | [AXNodeId](./puppeteer.protocol.accessibility.axnodeid.md)<!-- -->\[\] | IDs for each of this node's child nodes. |
|  [description](./puppeteer.protocol.accessibility.axnode.description.md) | [AXValue](./puppeteer.protocol.accessibility.axvalue.md) | The accessible description for this <code>Node</code>. |
|  [ignored](./puppeteer.protocol.accessibility.axnode.ignored.md) | boolean | Whether this node is ignored for accessibility |
|  [ignoredReasons](./puppeteer.protocol.accessibility.axnode.ignoredreasons.md) | [AXProperty](./puppeteer.protocol.accessibility.axproperty.md)<!-- -->\[\] | Collection of reasons why this node is hidden. |
|  [name](./puppeteer.protocol.accessibility.axnode.name.md) | [AXValue](./puppeteer.protocol.accessibility.axvalue.md) | The accessible name for this <code>Node</code>. |
|  [nodeId](./puppeteer.protocol.accessibility.axnode.nodeid.md) | [AXNodeId](./puppeteer.protocol.accessibility.axnodeid.md) | Unique identifier for this node. |
|  [properties](./puppeteer.protocol.accessibility.axnode.properties.md) | [AXProperty](./puppeteer.protocol.accessibility.axproperty.md)<!-- -->\[\] | All other properties |
|  [role](./puppeteer.protocol.accessibility.axnode.role.md) | [AXValue](./puppeteer.protocol.accessibility.axvalue.md) | This <code>Node</code>'s role, whether explicit or implicit. |
|  [value](./puppeteer.protocol.accessibility.axnode.value.md) | [AXValue](./puppeteer.protocol.accessibility.axvalue.md) | The value for this <code>Node</code>. |

