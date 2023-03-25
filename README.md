# RiverMaker
Script to draw river in Unity Editor


Create River easily directly in the editor using Control Points. To create a River Maker, just right click in the Hierarchy and go to Custom/ . You can change where the instancier is RiverMaker.cs line 76. The structure will appears. Don't change the parenting, only add or remove Control Node. Try to always have one Control Node. If you delete all the Control Nodes, just create an other empty child of Control Points and add directly the script RiverMakerNode.cs.

You control the river by moving or rotating the Control Nodes and changing the RiverWidth at each Control Node.

You can change the material directly in the Renderer component on the object River. If your material is not double sided, care about the rotation of the Control Node since the river could be facing the ground instead of the sky. 

On play all will be deleted instead of the RIver to try to optimize a little bit so the River is in Global transform instead of Local, hence optimizing a little bit if you have complex Shader calculations.

Feel free to 
