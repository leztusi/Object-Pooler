# Object Pooler

Object Pooling help optimizing games by instantiating all the recycable prefabs on limited amount then calling them when needed instead of instantiating and destroy.

# Usage

* Make sure you have the Object Pooler Prefab located at 'Resources' folder.
* You can add prefabs on Object Pooler Prefab to call later.
* each pooled prefabs should have "ObjectPoolerPoolBack" script to Pool back the object.
* You Grab the pooled object with

`GrabObject(int Index, Vector3 Position, Quaternion Rotation)`

`GrabObject(string Name, Vector3 Position, Quaternion Rotation)`
