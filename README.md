# Flutter Week 10 – Testing and Debugging

This repository contains two coursework examples focused on validating UI behavior and diagnosing Flutter application issues.

## Exercises

| File | Description |
|---|---|
| `10(a)` | Written code sample for a counter widget and unit/widget tests covering the initial value, increment and decrement behavior |
| `10(b)` | Debugging demonstration with a counter, conditional status message, `debugPrint` output and Flutter's performance overlay |

## Topics covered

- Separating counter logic from UI rendering
- Writing tests with `flutter_test`
- Verifying widget content and button interactions
- Using stable widget keys in tests
- Inspecting console output with `debugPrint`
- Enabling the performance overlay to inspect rendering behavior
- Reproducing and correcting UI state issues

## Run in a Flutter project

The two files are saved as coursework text files; this repository does not include a complete Flutter project scaffold.

1. Create a project: `flutter create testing_debugging_demo`.
2. Copy the counter widget into `lib/counter_widget.dart` and place the test code in the project's `test/` directory.
3. Replace the placeholder package import in the sample test with the actual package name from the generated `pubspec.yaml`.
4. Run the tests:

   ```bash
   flutter test
   ```

5. Copy the debugging example into `lib/main.dart` and run `flutter run`.

## Learning objective

Build confidence in checking UI behavior with automated tests and use Flutter's debugging tools to locate rendering and state-management problems.
