Adds the option to turn animation keyframes into a sequence of block/item models based on the Java Block codec.
This will not export any item definition files for the exported models, so these must be referenced manually in a resource pack.
Requires Minecraft 1.21.11 or later.

# How it works
The Java Block Sequencer (JBS) introduces a format which combines the Blockbench `resolve` and modified `Bake Animation Pose To Model` functions into a single 'Export Java Block Sequence' button. These models will be stored into a zip archive under the name of the selected animation. The JBS exports Java Block models similar to how the OBJ Animation Exporter tool by JannisX11 exports OBJ models. 

## How to use
Start by creating a new model or converting an existing cube-based project into a **Java Block Sequence**. Create an animation. Right-click your animation. Click **Export Java Block Sequence** from the drop-down menu. Each model will be displayed in-game based on settings in the Display tab.

# Troubleshooting
- If the exported models aren't getting rotated or positioned properly, make sure the groups/bones used in your animation have been checked (`Export: On`) in the `Edit` tab.
