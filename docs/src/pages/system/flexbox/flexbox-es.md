# Caja flexible

<p class="description">Quickly manage the layout, alignment, and sizing of grid columns, navigation, components, and more with a full suite of responsive flexbox utilities.</p>

If you are **new to or unfamiliar with flexbox**, we encourage you to read this [CSS-Tricks flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) guide.

## Properties for the Parent

### display

{{"demo": "pages/system/flexbox/Display.js", "defaultCodeOpen": false}}

```jsx
<Box display="flex">…
```

### flex-direction

{{"demo": "pages/system/flexbox/FlexDirection.js", "defaultCodeOpen": false}}

```jsx
<Box flexDirection="row">…
<Box flexDirection="row-reverse">…
```

### flex-wrap

{{"demo": "pages/system/flexbox/FlexWrap.js", "defaultCodeOpen": false}}

```jsx
<Box flexWrap="nowrap">…
<Box flexWrap="wrap">…
```

### justify-content

{{"demo": "pages/system/flexbox/JustifyContent.js", "defaultCodeOpen": false}}

```jsx
<Box justifyContent="flex-start">…
<Box justifyContent="flex-end">…
<Box justifyContent="center">…
```

### align-items

{{"demo": "pages/system/flexbox/AlignItems.js", "defaultCodeOpen": false}}

```jsx
<Box alignItems="flex-start">…
<Box alignItems="flex-end">…
<Box alignItems="center">…
```

### align-content

{{"demo": "pages/system/flexbox/AlignContent.js", "defaultCodeOpen": false}}

```jsx
<Box alignContent="flex-start">…
<Box alignContent="flex-end">…
```

## Properties for the Children

### order

{{"demo": "pages/system/flexbox/Order.js", "defaultCodeOpen": false}}

```jsx
<Box order={2}>Item 1</Box>
<Box order={3}>Item 2</Box>
<Box order={1}>Item 3</Box>
```

### flex-grow

{{"demo": "pages/system/flexbox/FlexGrow.js", "defaultCodeOpen": false}}

```jsx
<Box flexGrow={1}>Item 1</Box>
<Box>Item 2</Box>
<Box>Item 3</Box>
```

### flex-shrink

{{"demo": "pages/system/flexbox/FlexShrink.js", "defaultCodeOpen": false}}

```jsx
<Box width="100%">Item 1</Box>
<Box flexShrink={1}>Item 2</Box>
<Box flexShrink={0}>Item 3</Box>
```

### align-self

{{"demo": "pages/system/flexbox/AlignSelf.js", "defaultCodeOpen": false}}

```jsx
<Box>Item 1</Box>
<Box alignSelf="flex-end">Item 2</Box>
<Box>Item 3</Box>
```

## API

```js
import { flexbox } from '@material-ui/system';
```

| Nombre del import | Prop             | Propiedad CSS     | Clave del tema |
|:----------------- |:---------------- |:----------------- |:-------------- |
| `flexDirection`   | `flexDirection`  | `flex-direction`  | none           |
| `flexWrap`        | `flexWrap`       | `flex-wrap`       | none           |
| `justifyContent`  | `justifyContent` | `justify-content` | none           |
| `alignItems`      | `alignItems`     | `align-items`     | none           |
| `alignContent`    | `alignContent`   | `align-content`   | none           |
| `order`           | `order`          | `order`           | none           |
| `flex`            | `flex`           | `flex`            | none           |
| `flexGrow`        | `flexGrow`       | `flex-grow`       | none           |
| `flexShrink`      | `flexShrink`     | `flex-shrink`     | none           |
| `alignSelf`       | `alignSelf`      | `align-self`      | none           |