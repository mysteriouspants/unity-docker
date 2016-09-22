# Unity3D on Docker

Puts the Unity3D editor on Ubuntu Linux in a Docker image, suitable for

* running continuous integration tasks
* and building your release artefacts.

Versions on Docker Hub:

* [5.4.1f1][541f1]

If you need another version of Unity, check that a Linux version exists
on the [Unity3D forums][uty0], then copy the nearest version directory
and modify the `Dockerfile` to match the version you want. Try building
the image - if it works, make a pull request. If it doesn't, you might
make one anyway so we can all work through the problem.

If you have a better method of making these images, make a pull request.

If you know how to set up an automated build on Docker Hub so that
pushes to this repo trigger new builds, and that's something important
to you, I'd love to pair with you for a half hour to set it up.

[uty0]: http://forum.unity3d.com/threads/unity-on-linux-release-notes-and-known-issues.350256/
[541f1]: https://hub.docker.com/r/mysteriouspants/unity-5.4.1f1/
