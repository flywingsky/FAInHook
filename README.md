Android So Inline hook.

You can add FAInHook in your project by adding follow
cmake config in your CMakeLists.txt

set(FA_STATIC on)       # set this if you want to build FAGotHook as a static library

add_directory(path/to/FAInHook)

target_link_libraries( ${ProjectName} FAGotHook)

see main.cpp to find how to use

This project is still in developed.