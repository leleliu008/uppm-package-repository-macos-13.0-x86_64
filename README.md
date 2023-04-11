# uppm-package-repository-macos13.0-x86_64

these packages are created by [xcpkg](https://github.com/leleliu008/xcpkg).

these packages have no dependencies other than `/usr/lib/lib*.dylib` and `/System/Library/Frameworks/*.framework`.

these packages are relocatable which means that you can install them to anywhere.

## Environment Variables

**following environment variables should be set for `git` package**

```bash
export GIT_EXEC_PATH="$GIT_INSTALL_DIR/libexec/git-core"
export GIT_TEMPLATE_DIR="$GIT_INSTALL_DIR/share/git-core/templates"
```

**following environment variables should be set for `file` package**

```bash
export MAGIC="$FILE_INSTALL_DIR/share/misc/magic.mgc"
```

