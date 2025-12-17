# Collaborative

THOTH takes after ATON in that it allows for multi-user collaborative sessions in a single scene. In addition to ATON's interactive viewing, THOTH allows for users to view changes made to **layers and models** inside a scene in real-time. 

<p align="center">
    <img src="../../assets/icons/vrc.png" alt="Collab" width="50"/>
</p>

## Collaborative scenes

For project-specific implementation purposes, defining a scene as collaborative is achieved through specifically alterring the scene's json object with the following field:

```
"collaborative": true
```

Any scene with this attribute will automatically enable **Photon**, ATON's collaborative service, uppon successfully **logging in** a loaded scene. This is done to prevent conflicts between edits performed by multiple users in a given scene. 

Excluding that line from the scene object will simply launch the scene in a non-collaborative (singleplayer) environment.