# spaceporn-action-ci

A composite action triggered on pull request event. It clones the users of the currently modified repository, change its build.zig.zon with the SHA of the tested commit and run integration tests.

## Disclaimer

This package is not intented to be used outside of the [tiawl/spaceporn][1] dependencies chain. For this reason, there are no contributing file/rules on this repository. However feel free to open an issue if you have a question. We will be happy to answer.

## CICD reminder

These repositories are automatically updated when a new release is available:
* [tiawl/toolbox][2]
* [tiawl/vulkan.zig][3]
* [tiawl/wayland.zig][4]
* [tiawl/X11.zig][5]
* [tiawl/glfw.zig][6]
* [tiawl/cimgui.zig][7]
* [tiawl/spirv.zig][8]
* [tiawl/glslang.zig][9]
* [tiawl/shaderc.zig][10]

This repository is automatically updated when a new release is available from these repositories:
* [tiawl/spaceporn-action-env][11]
* [tiawl/spaceporn-action-cd-ping][12]
* [tiawl/spaceporn-action-cd-pong][13]

[1]:https://github.com/tiawl/spaceporn
[2]:https://github.com/tiawl/toolbox
[3]:https://github.com/tiawl/vulkan.zig
[4]:https://github.com/tiawl/wayland.zig
[5]:https://github.com/tiawl/X11.zig
[6]:https://github.com/tiawl/glfw.zig
[7]:https://github.com/tiawl/cimgui.zig
[8]:https://github.com/tiawl/spirv.zig
[9]:https://github.com/tiawl/glslang.zig
[10]:https://github.com/tiawl/shaderc.zig
[11]:https://github.com/tiawl/spaceporn-action-env
[12]:https://github.com/tiawl/spaceporn-action-cd-ping
[13]:https://github.com/tiawl/spaceporn-action-cd-pong
