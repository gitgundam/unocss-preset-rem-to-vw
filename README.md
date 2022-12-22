# unocss-preset-rem-to-vw

## Installation

```
npm i -D unocss-preset-rem-to-vw
```

```ts
import presetUno from "@unocss/preset-uno"
import presetRemToVw from "unocss-preset-rem-to-vw"

Unocss({
	presets: [presetUno(), presetRemToVw()],
})
```

## Usage

### without

```css
.m-2 {
	margin: 0.5rem;
}
.m-8px {
	margin: 8px;
}
```

</td><td width="500px" valign="top">

### with

```css
.m-2 {
	margin: 2.1333vw;
}

.m-8px {
	margin: 2.1333vw;
}
```

</td></tr></table>
