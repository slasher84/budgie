# Budgie

# Budgie the DLL injector is about to be superseded by Budgie the Mod. If you're a Steam User, you want the mod.

Budgie is a DLL injector for DCS World. This application is designed to inject specified DLL files into DCS World, enabling enhanced functionality, modifications or software fixes.

## Important Notice

Using Budgie to cheat in DCS World is a violation of the terms under which this software is provided. Any use of Budgie for cheating purposes is strictly prohibited.

## Features

- **DLL Injection**: Inject custom DLLs into DCS World for enhanced functionality.
- **Configuration Options**: Configure base path and multithreading through `config.json`.
- **Command Line Arguments**: Pass command line arguments to DCS via Budgie.

## Configuration

Budgie uses a `config.json` file for its configuration. The file contains the following options:

- `dcsBasePath`: A string pointing to the DCS World installation directory.
- `useMultithreaded`: A boolean determining if DCS should be launched in multithreaded mode.
- `notice`: A boolean, the purpose of which is further explained in the application, setting to false implies acceptance of terms.

Example `config.json`:

```json
{
    "dcsBasePath": "C:/Program Files/Eagle Dynamics/DCS World",
    "useMultithreaded": true
}
```

NB: Forward slashes are used in dcsBasePath due to the config file format, Windows typically uses backslashes. If you copy and paste the directory, you will need to change them around.

## Usage

To use Budgie, simply run the executable with any desired command line arguments. These arguments will be passed through to DCS World. As an example:

```sh
budgie.exe --force_disable_vr
```

If you don't need command line arguments, just run Budgie.exe.

## Disclaimer

Budgie is provided "as is", without warranty of any kind. No promise of support is offered. Use at your own risk.

---

Slasher84
