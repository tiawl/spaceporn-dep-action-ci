# spaceporn-action-ci

A composite action triggered on pull request event. It clones the users of the currently modified repository, change its build.zig.zon with the SHA of the tested commit and run integration tests.

## Disclaimer

This package is not intented to be used outside of the [tiawl/spaceporn](https://github.com/tiawl/spaceporn) dependencies chain. For this reason, there are no contributing file/rules on this repository. However feel free to open an issue if you have a question. We will be happy to answer.

## CICD reminder

These repositories are automatically updated when a new release is available:
* [tiawl/toolbox](https://github.com/tiawl/toolbox)
* [tiawl/vulkan.zig](https://github.com/tiawl/vulkan.zig)
* [tiawl/wayland.zig](https://github.com/tiawl/wayland.zig)
* [tiawl/X11.zig](https://github.com/tiawl/X11.zig)
* [tiawl/glfw.zig](https://github.com/tiawl/glfw.zig)
* [tiawl/cimgui.zig](https://github.com/tiawl/cimgui.zig)
* [tiawl/spirv.zig](https://github.com/tiawl/spirv.zig)
* [tiawl/glslang.zig](https://github.com/tiawl/glslang.zig)
* [tiawl/shaderc.zig](https://github.com/tiawl/shaderc.zig)

This repository is automatically updated when a new release is available from these repositories:
* [tiawl/spaceporn-action-env](https://github.com/tiawl/spaceporn-action-env)
* [tiawl/spaceporn-action-cd-ping](https://github.com/tiawl/spaceporn-action-cd-ping)
* [tiawl/spaceporn-action-cd-pong](https://github.com/tiawl/spaceporn-action-cd-pong)
