# Deps
[Devbox](https://www.jetpack.io/devbox)

# Dev flow
```sh
# enter into dev shell
# will install all dev dependencies automatically
devbox shell

# once in the shell, use `bazelisk` instead of `bazel`

# compile all assets and start the dev server
bazelisk build //py_server:server