# Box Joint

This is a [Fusion 360](https://www.autodesk.com/products/fusion-360/overview) Add-In for creating CNC friendly box/finger joints.

## Editable Feature

The Box Joint appears as a single Feature in the Timeline.

* The Box Joint Feature can be edited after creation just like any other built-in feature.
* The joint will be automatically recomputed if any of the dependent bodies earlier in the Timeline are changed.

## CNC Friendly

The joint has been designed to be cuttable on a CNC machine.

* Can be cut flat from a single side on an 3-axis CNC machine.
* No voids are visible even though inside corners are rounded.

## Screen Shots

![BoxJoint1](https://github.com/EvilHacker/BoxJoint/assets/6175398/30556d0e-5731-4d13-a690-e96b2998a220)

![BoxJoint2](https://github.com/EvilHacker/BoxJoint/assets/6175398/3521f3d9-5d79-48d2-96bd-85b8eeb5541f)

![BoxJoint3](https://github.com/EvilHacker/BoxJoint/assets/6175398/80d32152-d66f-4f07-979a-e63abc7cafd5)

![BoxJoint4](https://github.com/EvilHacker/BoxJoint/assets/6175398/05f251b6-883c-4303-a9a6-cdd9a2b7ca23)

## Installation

This Add-In can be installed by either:

* Using [GitHubToFusion360](https://apps.autodesk.com/FUSION/en/Detail/Index?id=789800822168335025). Paste the github link `https://github.com/EvilHacker/BoxJoint` into the [GitHubToFusion360](https://apps.autodesk.com/FUSION/en/Detail/Index?id=789800822168335025) Add-In.
* Downloading the Add-In zip file from [github](https://codeload.github.com/EvilHacker/BoxJoint/zip/refs/heads/main) and extract to:
	* `~/Library/Application Support/Autodesk/Autodesk Fusion 360/API/AddIns` (Mac OS)
	* `%appdata%\Autodesk\Autodesk Fusion 360\API\AddIns` (Windows)
