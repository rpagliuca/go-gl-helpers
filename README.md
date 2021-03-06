# Author
* Forked from: https://github.com/cstegel/opengl-samples-golang/materials
* Original author: cstegel

# About
This repo provides the following helper packages to be used in go-gl projects:
* `github.com/rpagliuca/go-gl-helpers/pkg/cam`: movable camera
* `github.com/rpagliuca/go-gl-helpers/pkg/gfx`: shader and texture compiling and handling
* `github.com/rpagliuca/go-gl-helpers/pkg/win`: glfw window and input handling

# Code snippet
```
import (
    "github.com/rpagliuca/go-gl-helpers/pkg/cam"
    "github.com/rpagliuca/go-gl-helpers/pkg/gfx"
    "github.com/rpagliuca/go-gl-helpers/pkg/win"
)
```

# Compatibility

Your program **MUST** depend on the following versions of OpenGL and GLFW for compatibility:
* `github.com/go-gl/gl/v4.1-core/gl`
* `github.com/go-gl/glfw/v3.1/glfw`

Mixing up different versions of OpenGL and GLFW will throw you compile-time or run-time errors.
