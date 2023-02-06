# xcb-vulkan-template
A window creation template with xcb and vulkan
## Build
 * clang
 * glslc
 * Vulkan development files
 * XCB developmet files
 * make
 
Run `make`, then `cd build`, and finally `./xcb-window`
### Options 
`--max-frames-in-flight n`

Replace `n` with any number. This defines how many frames will be rendered at once before waiting for a frame to be presented.
