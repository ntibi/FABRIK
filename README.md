# bevy_2d_inverse_kinematics

a [bevy](https://bevyengine.org/) plugin for 2d [inverse kinematics](https://en.wikipedia.org/wiki/Inverse_kinematics) solved by [FABRIK](http://www.andreasaristidou.com/FABRIK.html)


2d meaning it has 3 degrees of freedom (XY translation, Z rotation)

## FABRIK
Forward And Backward Reaching Inverse Kinematics

description [here](http://www.andreasaristidou.com/FABRIK.html)

## examples
basic IK arm that follows the mouse cursor
```
cargo run --example arm
```

cute frog procedurally walking with IK animated legs
```
cargo run --example frog
```

human looking voxel model with arms that follows the mouse
```
cargo run --example model
```
<p align="center">
<img src="https://raw.githubusercontent.com/ntibi/bevy_2d_inverse_kinematics/refs/heads/master/misc/arm.gif" alt="arm" />
<img src="https://raw.githubusercontent.com/ntibi/bevy_2d_inverse_kinematics/refs/heads/master/misc/frog.gif" alt="frog" />
</p>
