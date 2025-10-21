# Collaborative usage

<p align="center">
    <img src="/assets/icons/vrc.png" alt="Collab" width="50"/>
</p>

THOTH allows for collaborative sessions, where multiple users can cooperate on the same scene. 

When multiple users operate on a scene, the changes done by one user will be broadcasted to all other users who have joined the collaborative session.

History operations like undo/redo affect only each individual user's actions. For example, if user 1 paints over an area A and user 2 paints over a different area B, if user 1 presses undo, only area 1 will be affected and not area 2. **However note that conflicts between different operations can occur if multiple users operate in the same areas.**