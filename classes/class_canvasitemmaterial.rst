.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the CanvasItemMaterial.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_CanvasItemMaterial:

CanvasItemMaterial
==================

**Inherits:** :ref:`Material<class_material>` **<** :ref:`Resource<class_resource>` **<** :ref:`Reference<class_reference>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

A material for :ref:`CanvasItem<class_canvasitem>`\ s.

Member Variables
----------------

  .. _class_CanvasItemMaterial_blend_mode:

- :ref:`BlendMode<enum_canvasitemmaterial_blendmode>` **blend_mode** - The manner in which a material's rendering is applied to underlying textures.

  .. _class_CanvasItemMaterial_light_mode:

- :ref:`LightMode<enum_canvasitemmaterial_lightmode>` **light_mode** - The manner in which material reacts to lighting.


Enums
-----

  .. _enum_CanvasItemMaterial_LightMode:

enum **LightMode**

- **LIGHT_MODE_NORMAL** = **0** --- Render the material using both light and non-light sensitive material properties.
- **LIGHT_MODE_UNSHADED** = **1** --- Render the material as if there were no light.
- **LIGHT_MODE_LIGHT_ONLY** = **2** --- Render the material as if there were only light.

  .. _enum_CanvasItemMaterial_BlendMode:

enum **BlendMode**

- **BLEND_MODE_MIX** = **0** --- Mix blending mode. Colors are assumed to be independent of the alpha (opacity) value.
- **BLEND_MODE_ADD** = **1** --- Additive blending mode.
- **BLEND_MODE_SUB** = **2** --- Subtractive blending mode.
- **BLEND_MODE_MUL** = **3** --- Multiplicative blending mode.
- **BLEND_MODE_PREMULT_ALPHA** = **4** --- Mix blending mode. Colors are assumed to be premultiplied by the alpha (opacity) value.
- **BLEND_MODE_DISABLED** = **5** --- Disable blending mode. Colors including alpha are written as is. Only applicable for render targets with a transparent background. No lighting will be applied.


Description
-----------

``CanvasItemMaterial``\ s provide a means of modifying the textures associated with a CanvasItem. They specialize in describing blend and lighting behaviors for textures. Use a :ref:`ShaderMaterial<class_shadermaterial>` to more fully customize a material's interactions with a :ref:`CanvasItem<class_canvasitem>`.

