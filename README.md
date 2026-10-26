# ios-demo

Demo iOS mínima (SwiftUI, bundle `com.example.iosdemo`) para validar
`MobAI-App/ios-builder` desde Windows sin Mac.

Flujo:

```sh
builder auth github
builder init
builder ios build --unsigned
```

El IPA queda en `./dist/`. Build sin firma: no instala en iPhone físico,
sirve para validar el pipeline y para `builder ios share` (simulador MobAI).
