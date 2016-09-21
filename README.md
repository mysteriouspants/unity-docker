# Unity3D on Docker

Puts the Unity3D editor on Ubuntu Linux in a Docker image, suitable for

* running continuous integration tasks
* and building your release artefacts.

If you need another version of Unity, check that a Linux version exists
on the [Unity3D forums][uty0], then copy the nearest version directory
and modify the `Dockerfile` to match the version you want. Try building
the image - if it works, make a pull request. If it doesn't, you might
make one anyway so we can all work through the problem.

If you have a better method of making these images, make a pull request.

[uty0]: http://forum.unity3d.com/threads/unity-on-linux-release-notes-and-known-issues.350256/
