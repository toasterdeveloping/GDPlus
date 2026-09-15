# GDPlus (Geometry Dash Plus)

<img width="1858" height="179" alt="image" src="https://github.com/user-attachments/assets/faebf77b-afac-404f-bb3e-e346085dfd52" />

GDPlus is a recreation of Geometry Dash starting from the 1.0 version of GD.

The project is based on the OpenGD source code (using C++20 and the Axmol engine)

### Build
Since this is based on OpenGD/Axmol, the setup requirements are pretty much the same:
* Windows
* PowerShell & CMake
* C++20 compatible compiler (MSVC, clang, or gcc)

You'll need to drop your GD resources into the Content folder to run it.

Windows:
```
cmake -B build -G "Visual Studio 17 2022" -A x64

cmake --build build --config Debug
```

Linux:
```
cmake -B build -G Ninja -DCMAKE_BUILD_TYPE=Debug

cmake --build build
```

### Discord
We have an official Discord server too!

Join here: https://discord.gg/GnbswNdu9D

### Members
[ToasterDev](https://github.com/toasterdeveloping) - Owner of GDPlus

[Salty](https://www.youtube.com/channel/UC100gvEayeKCSffz2y1FnKA) - Staff (also support their music!)

## Credits
* OpenGD
* Axmol
* wyliemaster
* camila314

### License
* Distributed under the GPL v3 License.

image because someguyondlsc kept ragebaiting me:
<img width="813" height="306" alt="image" src="https://github.com/user-attachments/assets/fd9d5fcb-17ff-48ce-8439-c65b61a04340" />
