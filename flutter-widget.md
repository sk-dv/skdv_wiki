Mover `bottom sheet` cuando se muestra el teclado

Widget que encapsula el `bottom sheet`

```dart
SingleChildScrollView(
  child: AnimatedPadding(
    padding: MediaQuery.of(context).viewInsets,
    duration: const Duration(milliseconds: 100),
    child: Column(...),
  ),
)
```

`bottom sheet`

```dart
showModalBottomSheet<T>(
  context: context,
  isScrollControlled: true,
  builder: (_) => Padding(
    padding: EdgeInsets.only(
      bottom: MediaQuery.of(context).viewInsets.bottom,
    ),
    child: child
  ),
);
```
