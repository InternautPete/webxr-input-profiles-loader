# WebXR Input Profiles Loader

WebXR Input Profiles Loader in Unity. Based on [WebXR Input Profiles](https://immersive-web.github.io/webxr-input-profiles/)

The package is intended to be used with WebXR exporters in general, and not only with [WebXR Export](https://github.com/De-Panther/unity-webxr-export)

The package uses [glTFast](https://github.com/atteneder/glTFast) to load the models, and Unity's package of Newtonsoft Json.NET to parse the profiles.

You might need to add Shader Variants of the Input Profiles Models to the build for the shaders to work. More info about that can be found at the glTFast docs.

## Setting package using OpenUPM

Set a `Scoped Registry` in `Project Settings > Package Manager` for OpenUPM.

```
Name: OpenUPM
URL: https://package.openupm.com
Scope(s): com.de-panther
          com.atteneder
```

Then in `Window > Package Manager` selecting `Packages: My Registries` and the WebXR Input Profiles Loader package would be available for install.
