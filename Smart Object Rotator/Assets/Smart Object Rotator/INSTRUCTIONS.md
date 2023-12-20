
# Smart Object Rotator for Unity Instructions
Attach the _SmartObjectRotator_ script in the Scripts folder to any GameObject and adjust the settings to suit your needs.

### Settings

#### Rotation Speed
The speed at which the object will rotate.

#### Time Before Initial Rotation
Set this to `0` to see the object begin rotating on start. Higher values will pause the initial rotation.

#### Destination Duration
The amount of time the object will retain its current rotation values.

#### Transition Duration
The amount of time it takes to transition from one set of rotation values to the next.

#### Randomize Start Rotation
If `true`, the object will start with random rotation values. If `false`, the object will use the rotation values set in the Unity Inspector.

#### Transition Type
Set to `Linear` for a constant transition between rotation values. Set to `Exponential Logarithmic` to initiate ramping transitions between rotation values.

#### Logarithmic Rolloff
Adjusts the Exponential Logarithmic ramp. Smaller values decrease the exponential ramp.

#### Rotation Ranges (XYZ)
Set a range between `-1` (Low) and `1` (High) to allow the script to randomly adjust the values of the rotation axes. For example, you could set the X Range to `-0.2, 0` to only choose rotation values between those two values.

#### Rotation Values (XYZ)
This is purely to allow you to view how the rotation values are changing.

### Created By
Tim Samoff (https://samoff.com)

### License
[GNU Lesser General Public License](https://www.gnu.org/licenses/lgpl-3.0.en.html)
