# Hello
This is my **first Docusaurus document**!

Let's see how to [Create a page](/create-a-page).

Let's see how to [Create a page](./create-a-page.md).

![Docusaurus logo](/img/docusaurus.png)

![Docusaurus logo](/img/docusaurus.png)

```jsx title="src/components/HelloDocusaurus.js"
function HelloDocusaurus() {
  return <h1>Hello, Docusaurus!</h1>;
}
```

:::tip[Мои рекомендации следущие]

Use this awesome feature option

:::

:::danger[Будь осторожен обращаясь с огнем]

This action is dangerous

:::
export const Highlight = ({children, color}) => (
<span
style={{
backgroundColor: color,
borderRadius: '20px',
color: '#fff',
padding: '10px',
cursor: 'pointer',
}}
onClick={() => {
alert(`You clicked the color ${color} with label ${children}`)
}}>
{children}
</span>
);

This is <Highlight color="#25c2a0">Docusaurus green</Highlight> !

This is <Highlight color="#3257F2">Голубая история</Highlight> !