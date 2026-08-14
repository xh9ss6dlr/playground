# Flutter Tips

- Use `const` constructors whenever possible to reduce rebuilds.
- Prefer `ListView.builder` for long lists.
- Wrap async calls in `FutureBuilder` or use `async/await` carefully.
- For simple state, `setState` is fine; reach for Provider only when needed.
- Test widgets with `tester.pumpAndSettle` after animations.