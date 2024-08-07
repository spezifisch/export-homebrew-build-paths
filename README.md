# export-homebrew-build-paths

This GitHub Action sets up environment variables for library paths and include paths on macOS. It is particularly useful for projects that depend on Homebrew-installed libraries.

## Inputs

### `C_INCLUDE_PATH`

**Optional**: The include paths. Default is `/usr/local/include:/opt/homebrew/include`.

### `LIBRARY_PATH`

**Optional**: The library paths. Default is `/usr/local/lib:/opt/homebrew/lib`.

## Example Usage

```yaml
      - name: Export paths
        uses: spezifisch/export-homebrew-build-paths@v0.1.0
```
