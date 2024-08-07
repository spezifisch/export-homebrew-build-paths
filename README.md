# export-homebrew-build-paths

This GitHub Action sets up environment variables for library paths and include paths on macOS. It is particularly useful for projects that depend on Homebrew-installed libraries.

## Example Usage

```yaml
      - name: Export paths
        uses: spezifisch/export-homebrew-build-paths@v0.1.1
```

Then do `go build` or your usual build command which links against a library installed by Homebrew.
