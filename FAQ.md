## Why does my Nexo model appear as PODZOL?
Set `Pack.import.model_engine.import_pack` to false in your `Nexo/settings.yml`,

then reload your server and resourcepack. This should resolve the issue.

```
    model_engine:
      import_pack: false
      exclude_shaders: false
```