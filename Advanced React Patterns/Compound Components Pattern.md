Example: Expandable component
Goal: Make it as reusable as possible

1. The child components can only be used under the corresponding parent
2. Use context to hold the component state and share with the children
3. Managable styling for reusable components

```
<Expandable>
  <Expandable.Header></Expandable.Header>
  <Expandable.Icon/>
  <Expandable.Body></Expandable.Body>
</Expandable>
```
