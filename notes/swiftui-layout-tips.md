# SwiftUI Layout Tips

- Use `ViewThatFits` for responsive layouts before jumping to custom `Layout`.
- `containerRelativeFrame` is handy for evenly sized items inside a scroll view.
- Prefer `Grid` over nested `HStack`/`VStack` for tabular data.
- Keep custom `Layout` for exotic arrangements; measure children with `SizeThatFits`.
