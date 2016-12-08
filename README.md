# cc.fire.utils
Utilities for Cocos Creator scene files (*.fire)

# Usage

If you get the error message:

    TypeError: children[i]._onBatchCreated is not a function at cc_Node.cc.Class._onBatchCreated

then it means that your VCS merge broke your scene file. In this case you can manual merge scene files. Save two versions of the same scene file in directory and run:

    cc.fire.merge the_scene.fire the_same_scene_from_another_branch.fire

It will generate merge_out.fire in the current directory. Then you can move it to your project work copy.
