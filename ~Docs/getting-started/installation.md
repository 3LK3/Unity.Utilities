# Requirements

I assume you:
- are using Unity >= 2023.2.11f1

# Installation

There are two ways of installing a package in Unity. You can add a dependency to the `manifest.json` in your Packages folder or install it via the Unity package manager.

## Add dependency to manifest.json

Declare this package as a dependency in `<Your Project>/Packages/manifest.json` by adding the following line to the *dependencies* section:

> [!Note]
> You can replace the version specifier with any [valid release version](https://github.com/3LK3/Unity.Utilities/releases) or just remove it to use the latest version.

```json
{
  "dependencies": {
    "...",
    "party.elke.unity.utilities": "https://github.com/3LK3/Unity.Utilities.git#0.0.1"
  }
}
```

## Use the Unity package manager

- Open the Unity package manager via **Window** -> **Package Manager**.<br>
- Click the plus icon on the top left and select **Add package from git URL** 
- Use `https://github.com/3LK3/Unity.Utilities.git` as URL.