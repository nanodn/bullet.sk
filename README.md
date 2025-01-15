# bullet.sk

A Skript + Libbulletjme integration example.

<video src="example.mp4" controls></video>

## Setup

> Tested with Skript 2.9.4 and Paper 1.20.4. Skript 2.10 and above will have quaternion support so things will break.

- Download Skript and skript-reflect, run your server with them installed at least once.

- Download the release jar file and native sp library matching your system from [Libbulletjme's releases page](https://github.com/stephengold/Libbulletjme/releases/latest).
  - Example: For 64-bit Windows, you'd download the jar file `Libbulletjme-<version>.jar` and `Windows64ReleaseSp_bulletjme.dll`. Same goes for the other platforms.
- Put both Libbulletjme files into `plugins/skript-reflect/`.
- Place the scripts from this repository into your scripts folder.

`10_example.sk` file has some usage examples. Check it out.
