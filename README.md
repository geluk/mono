This repository is a patched fork of the Unity Mono runtime.

The garbage collector has been patched to fix a bug that would cause a stack overflow during the mark phase.

This is the same fix as [Sparr's fork](https://github.com/sparr/Unity-Technologies_mono/releases),
but applied to Unity 2019.4.40f1 instead.
