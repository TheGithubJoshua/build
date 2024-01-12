# dragon-build

Github action to build a `dragon` package

## Usage

`dragon-build` Just use
the action like any other action under any workflow job. If you want a rootless build make sure rootless is ser to 'yes'

```yaml
steps:
    - name: Build packages
      uses: DragonBuild/build@master
      with:
       rootless: 'yes' #optional
    ```

*You can also refer to any of the release tags, rather than using the
master version of the action.*
