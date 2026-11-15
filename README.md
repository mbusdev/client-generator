# Generater of Clients for Calling the Backend from Flutter

```bash
dart pub install
rm -rf lib/generated/**.dart
dart run swagger_parser
dart run build_runner build
git push --recurse-submodules=on-demand
```
