# Layers

<p align="center">
    <img src="../../assets/icons/layers.png" alt="Layers" width="50"/>
</p>

## Layer Overview

Each layer can be thought of as a different annotation object, in other words a structured descriptor for a specific selection. Visually, it is represented by the selected faces on the object. As an entity, it can be described by its name and metadata.

The user can create new layers, as well as modify and delete existing layers. This can be achieved from the layer panel accessed from the Layers button.

## Creating a new layer

You can create a new layer by pressing the **Create New Layer** button in the **Layer panel** or by pressing **Shift + N**.

<p align="center">
    <img src="../../assets/icons/add.png" alt="Add Layer" width="50"/>
</p>

This will automatically assign an id to the new layer as well as a default name and color. The user can **select the created layer** by pressing its name on the layer panel, or by pressing the **number button** corresponding to its id.


## Modifying a layer

For any layer, the user can directly alter any of its attributes with the corresponding tools and ui elements. Specifically, the attributes a user can modify are:

* **Color**: You can edit the color of a layer from pressing the **color selection button** on the layer controller.

* **Visibility**: You can toggle the visibility of a layer by pressing the visibility icon on the right of the layer controller. 

* **Name and metadata**: You can edit the name and metadata of a layer using the **edit metadata** button, or by pressing **Shift + the corresponding layer id**. For more information in metadata, refer to the [metadata section](). 

## Deleting layers

The user can delete a layer by pressing the **Delete button** on the layer's controller. This action is reversable. 

## Scene Layer

<p align="center">
    <img src="../../assets/icons/scene.png" alt="Scene Layer" width="50"/>
</p>

The scene layer is a special layer which corresponds to the entire scene. Unlike other layers, the only attribute you can alter is the **scene metadata**. You can do that by pressing the **edit scene metadata button** or using the shortcut **Shift + S**.