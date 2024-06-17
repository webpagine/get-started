# Get started with Pagine

This is an example template for getting started with [Pagine](https://github.com/webpagine/pagine) and template [Genesis](https://github.com/webpagine/genesis).
View [Documentation](https://pagine.symboltics.com/docs).

## Run Pagine in server mode

```shell
$ pagine --serve :12450
```

Open browser and go to `http://127.0.0.1:12450`

## Features Demo of Genesis

> [!TIP]
> Only available features are shown below.

### Dark mode

The button in the upper right corner is used to toggle between light (sun) and dark (moon) mode.

*You may notice it.*

### MathJax

$$
\left[ \begin{array}{a} a^l_1 \\ ⋮ \\ a^l_{d_l} \end{array}\right]
= \sigma(
\left[ \begin{matrix}
w^l_{1,1} & ⋯  & w^l_{1,d_{l-1}} \\
⋮ & ⋱  & ⋮  \\
w^l_{d_l,1} & ⋯  & w^l_{d_l,d_{l-1}} \\
\end{matrix}\right]  ·
\left[ \begin{array}{x} a^{l-1}_1 \\ ⋮ \\ ⋮ \\ a^{l-1}_{d_{l-1}} \end{array}\right] +
\left[ \begin{array}{b} b^l_1 \\ ⋮ \\ b^l_{d_l} \end{array}\right])
$$

### Code highlight

```rust
#[derive(Default)]
pub struct Demo {
    pub highlight: bool,
}
```
