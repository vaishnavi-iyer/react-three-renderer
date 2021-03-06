> [Wiki](Home) » [[Internal Components]] » [[Materials]] » **lineBasicMaterial**

# lineBasicMaterial

Creates a [THREE.LineBasicMaterial](http://threejs.org/docs/#Reference/Materials/LineBasicMaterial)

## Attributes
### slot
``` string ```: This decides which property of the mesh the material should be assigned to.

Defaults to `material`. Other example values:
- customDepthMaterial
- customDistanceMaterial
- and so on

### transparent
``` bool ```

### alphaTest
``` number ```

### side
``` one of [THREE.FrontSide, THREE.BackSide, THREE.DoubleSide] ```

### opacity
``` number ```

### visible
``` bool ```

### color
``` one of types [THREE.Color, number, string] ```

### linewidth
``` number ```

### linecap
``` one of [round] ```

### linejoin
``` one of [round] ```

### vertexColors
``` one of [THREE.NoColors, THREE.FaceColors, THREE.VertexColors] ```

### fog
``` bool ```

### resourceId
``` string ```: The resource id of this object, only used if it is placed into [[resources]].

This component can be added into [&lt;resources/&gt;](resources)! See [[Resource Types]] for more information.

===

|**[View Source](../blob/master/src/lib/descriptors/Material/LineBasicMaterialDescriptor.js)**|
 ---|
