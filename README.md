# Vulkan App
- Learning with Vulkan, C++17. For use with Windows based machines.

<h2>
<img src="https://em-content.zobj.net/source/microsoft-teams/400/bar-chart_1f4ca.png" height="25" align="center">
Preview
</h2>
<div style="display: flex;">
    <img src="./gif/.gif" height="360"/>
</div>

<h2>
<img src="https://lh4.googleusercontent.com/proxy/4_Zan5D7FOYcviw14ecpCpx8Tvq-ii1DoLIe15O2eDy9INbz2mhP-27Z3HCWby3EaQned-UF-1n4zFzbkSEFt9p7sOQUnsX-q_GyjI4C1-bSIVXTG0z0dugD" height="30" align="center">
Requirements
</h2>

> - [Download](https://visualstudio.microsoft.com/vs/community/) Visual Studio 2022 Community Edition.
> -- Install workloads: *Desktop development with C++*.
> - [Download](https://cmake.org/download/) and install CMake (>= v3.20).
> - [Download](https://vulkan.lunarg.com/) and install Vulkan SDK(>= v1.4.321.1). 


<h2>
<img src="https://em-content.zobj.net/source/microsoft-teams/337/hammer-and-wrench_1f6e0-fe0f.png" height="30",align = "center">
Build
</h2>

- Clone repo:
```
git clone https://github.com/RobRob7/OWiseVulkan.git
```
- Then run commands:
```
cd OWiseVulkan
mkdir build
cd build
cmake ..
cmake --build . --config Release
```
<h2>
<img src="https://cdn-icons-png.freepik.com/512/8964/8964273.png" height="30",align = "center">
Run
</h2>

```
cd Release
/MyVulkanApp.exe
```


<h2>
<img src="https://em-content.zobj.net/source/microsoft-3D-fluent/406/package_1f4e6.png" height="30",align = "center">
Dependencies
</h2>

Libraries already provided, the following are used:
|Library|Usage|Version|
|-------|-------|-----|
|[tinyobjloader](https://github.com/tinyobjloader/tinyobjloader)|Image loader|v1.0.6|
|[stb_image](https://github.com/nothings/stb/blob/master/stb_image.h)|Image loader|N/A|
|[GLFW](https://www.glfw.org/download.html)|API for creating windows, contexts and surfaces, receiving input and events|v3.4|
|[GLM](https://github.com/g-truc/glm/releases/tag/1.0.1)|Header only C++ mathematics library|v1.01|
|[FreeType](https://freetype.org/download.html)|Font rendering|v2.10.0|


<h2>
<img src="https://www.traptct.com/wp-content/uploads/2020/04/file-folder-png-1.png" height="30",align = "center">
Project Structure
</h2>

Project layout:


