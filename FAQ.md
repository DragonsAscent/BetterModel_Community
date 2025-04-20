## I'm using Nexo, but my model textures show up as PODZOL. How can I fix this?
Set `Pack.import.model_engine.import_pack` to false in your `Nexo/settings.yml`,

then reload your server and resourcepack. This should resolve the issue.

```
    model_engine:
      import_pack: false
      exclude_shaders: false
```