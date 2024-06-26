---
aliases: "Menu"
cssclasses: hide-title
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[`Menu`](Menu)

## Menu class


**Signature:**

```typescript
export class Menu extends Component implements CloseableComponent 
```
**Extends:** [`Component`](Component)

**Implements:** [`CloseableComponent`](CloseableComponent)

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [`(constructor)()`](Menu/(constructor).md) |  | Constructs a new instance of the <code>Menu</code> class |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [`addChild(component)`](Component/addChild) |  | <p>Adds a child component, loading it if this component is loaded</p><p>(Inherited from [Component](Component)<!-- -->)</p> |
|  [`addItem(cb)`](Menu/addItem) |  | Adds a menu item. Only works when menu is not shown yet. |
|  [`addSeparator()`](Menu/addSeparator) |  | Adds a separator. Only works when menu is not shown yet. |
|  [`close()`](Menu/close) |  |  |
|  [`hide()`](Menu/hide) |  |  |
|  [`load()`](Component/load) |  | <p>Load this component and its children</p><p>(Inherited from [Component](Component)<!-- -->)</p> |
|  [`onHide(callback)`](Menu/onHide) |  |  |
|  [`onload()`](Component/onload) |  | <p>Override this to load your component</p><p>(Inherited from [Component](Component)<!-- -->)</p> |
|  [`onunload()`](Component/onunload) |  | <p>Override this to unload your component</p><p>(Inherited from [Component](Component)<!-- -->)</p> |
|  [`register(cb)`](Component/register) |  | <p>Registers a callback to be called when unloading</p><p>(Inherited from [Component](Component)<!-- -->)</p> |
|  [`registerDomEvent(el, type, callback, options)`](Component/registerDomEvent) |  | <p>Registers an DOM event to be detached when unloading</p><p>(Inherited from [Component](Component)<!-- -->)</p> |
|  [`registerDomEvent(el, type, callback, options)`](Component/registerDomEvent_1) |  | <p>Registers an DOM event to be detached when unloading</p><p>(Inherited from [Component](Component)<!-- -->)</p> |
|  [`registerDomEvent(el, type, callback, options)`](Component/registerDomEvent_2) |  | <p>Registers an DOM event to be detached when unloading</p><p>(Inherited from [Component](Component)<!-- -->)</p> |
|  [`registerEvent(eventRef)`](Component/registerEvent) |  | <p>Registers an event to be detached when unloading</p><p>(Inherited from [Component](Component)<!-- -->)</p> |
|  [`registerInterval(id)`](Component/registerInterval) |  | <p>Registers an interval (from setInterval) to be cancelled when unloading Use  instead of  to avoid TypeScript confusing between NodeJS vs Browser API</p><p>(Inherited from [Component](Component)<!-- -->)</p> |
|  [`removeChild(component)`](Component/removeChild) |  | <p>Removes a child component, unloading it</p><p>(Inherited from [Component](Component)<!-- -->)</p> |
|  [`setNoIcon()`](Menu/setNoIcon) |  |  |
|  [`setUseNativeMenu(useNativeMenu)`](Menu/setUseNativeMenu) |  | Force this menu to use native or DOM. (Only works on the desktop app) |
|  [`showAtMouseEvent(evt)`](Menu/showAtMouseEvent) |  |  |
|  [`showAtPosition(position, doc)`](Menu/showAtPosition) |  |  |
|  [`unload()`](Component/unload) |  | <p>Unload this component and its children</p><p>(Inherited from [Component](Component)<!-- -->)</p> |

