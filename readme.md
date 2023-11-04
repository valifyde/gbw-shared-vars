## Paket installieren:

`pnpm i gbw-shared-vars`

## Regular (Stencil):

`@import '~gbw-shared-vars';`

## Vite:

`@import 'gbw-shared-vars';`

## Stencil:

```
import { options } from 'gbw-shared-vars';
console.log(options.res.lg);
```

## Media-Queries: (md = 768px)

```
@include breakpoint(md) { // min:md ~ max:lg
@include breakpoint-down(md) {
@include breakpoint-up(md) {
```

## SCSS Vars:

```
$bpSm: 375px;
$bpMd: 768;
$bpLg: 1024;
$bpXl: 1280;
$bpXxl: 1440;
$bpXxxl: 1920;
```

```
$bpSmDownPx:  374px
$bpMdDownPx: 767px
$bpLgDownPx:  1023px
$bpXlDownPx:  1279px
$bpXxlDownPx:  1439px
$bpXxxlDownPx:  1919px
```
