A set of opinionated analyzer rules and lints for Dart and Flutter apps.


### Installation

Add following to the `pubspec.yaml`:

```yaml
dev_dependencies:
  custom_lints:
    git: https://github.com/SkinnyMind/custom_lints
```

Change `analysis_options.yaml`:

```yaml
include: package:custom_lints/custom_lints.yaml
```