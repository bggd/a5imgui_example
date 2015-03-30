
example of allegro 5 with ImGui (https://github.com/ocornut/imgui)

# How to Build

```bash
git clone git://github.com/ocornut/imgui
git clone git://github.com/bggd/a5imgui_example
cd a5imgui_example
```

- On Ubuntu 14.04+

```bash
g++ -I ../imgui ../imgui/imgui.cpp main.cxx imgui_impl_a5.cxx -lallegro -lallegro_primitives
```

- On Windows with Visual Studio's CLI

\<a5path\> is your allegro5 folder.

```
cl /MD /I <a5path\include> /I ..\imgui ..\imgui\imgui.cpp main.cxx imgui_impl_a5.cxx /link /LIBPATH:<a5path\lib> allegro-5.0.10-monolith-md.lib user32.lib
```

public domain.
