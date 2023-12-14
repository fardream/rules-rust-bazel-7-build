# Failure on linux host

Use `bazelisk` (or use `bazel` 7.0) to run the below

```
bazel build @crate_vendor__libffi-sys-2.3.0//:libffi_sys
```

This will fail on a linux box with error message
