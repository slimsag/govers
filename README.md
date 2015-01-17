A fork of @rogpeppe's govers tool that can be used to migrate from the old `vN-dev` import paths to the new `vN-unstable` import paths.

For all other purposes: use @rogpeppe's govers tool instead!

See https://github.com/azul3d/semver/issues/7 for more details.

To switch to the new `vN-unstable` paths:

```
# Crucial(!):
cd my/pkg/path

# Install my fork:
go get -u github.com/slimsag/govers

# Switch from v2-dev to v2-unstable:
govers azul3d.org/gfx.v2-unstable
govers azul3d.org/mouse.v2-unstable
govers azul3d.org/keyboard.v2-unstable

# Install real govers:
go get -u github.com/rogpeppe/govers
```
