
example of allegro 5 with ImGui (https://github.com/ocornut/imgui)

# How to Build

- Ubuntu 14.04+

```bash
git clone git://ocornut/imgui
git clone git://bggd/a5imgui_example
cd a5imgui_example
g++ -I ../imgui ../imgui/imgui.cpp main.cxx imgui_impl_a5.cxx -lallegro -lallegro_primitives
```

public domain.
