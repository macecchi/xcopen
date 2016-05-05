# xcopen

__xcopen__ is a shortcut to open the Xcode workspace or project in the current directory.

__xcopen__ will try to open the `.xcworkspace` file of the directory. If one is not found, it will then look for a `.xcodeproj` file.


### Before `xcopen`

```bash
open -a Xcode "My Awesome App.xcworkspace"
```


### After `xcopen`

```bash
xcopen
```


## Usage

```bash
xcopen
```

That's all you need to open the workspace/project in the current directory. If you want to specify a different directory, just pass it as an argument:

```bash
xcopen /path/to/MyAwesomeApp/
```


## License

This project is licensed under the terms of the GNU GPL v3 license. See the LICENSE file.