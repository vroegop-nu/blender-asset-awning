# Awning Node Group

A Blender 3D geometry nodes node group for generating awnings.

## Parameters

| Parameter               | Description                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------- |
| Width                   | Total width of the awning                                                                    |
| Cloth Width Reduction   | The total amount that will subtracted from the total Width to use for the width of the cloth |
| Bend                    | The amount of sag in the cloth                                                               |
| Resolution              | Affects the number of horizontal subdivisions in the cloth                                   |
| Angle                   | The opening angle (0 - 180 degrees) of the awning                                            |
| Horizontal Bar Diameter | Diameter of the horizontal bar                                                               |
| Valance height          | The height of the valance                                                                    |
| Valance wave length     | The wave length of the valance                                                               |
| Cloth Vertex Color      | The vertex color for all of the cloth vertices                                               |
| Cloth Material          | The material to be used for the cloth                                                        |
| Arm Length              | The length of the (meassured between the pivot points)                                       |
| Arm Width               | The width of the arms                                                                        |
| Arm Thickness           | The thickness of the arms                                                                    |
| Arm Vertex Color        | The vertex color of all the arms, brackets and horizontal bar vertices                       |
| Arm Material            | The material applied to the arms, brackets and the horizontal bar                            |
| Box depth               | The depth of the cover box on top of the awning                                              |
| Box Height              | The height of the cover box on top of the awning                                             |
| Box Vertex Color        | The vertex color for all the box vertices                                                    |
| Box Material            | The material applied to the box on top of the awning                                         |

## Attributes

| Attribute  | Type    | Description                                                 |
| ---------- | ------- | ----------------------------------------------------------- |
| is_arm     | boolean | Applied to the vertices of the arms                         |
| is_cloth   | boolean | Applied to the vertices of the cloth                        |
| is_valance | boolean | Applied to the vertices of the valance                      |
| is_box     | boolean | Applied to the vertices of the box on top of the awning     |
| is_left    | boolean | Applied to the vertices of a left part (arms and brackets)  |
| is_right   | boolean | Applied to the vertices of a right part (arms and brackets) |