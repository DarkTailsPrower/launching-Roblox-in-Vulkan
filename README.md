# launching-Roblox-in-Vulkan
launching Roblox in Vulkan Copy ClientSettings Folder on Roblox Directory


win+r write %localappdata%\Roblox\logs to vefiry is working vulkan or not

```
2026-09-15T20:57:25.832Z,0.832607,3670,6 [FLog::Output] LoadClientSettingsFromLocal: "{
  "FFlagDebugGraphicsPreferVulkan": "true"
}
```
```
2026-09-15T20:57:27.050Z,2.050643,37ac,6 [FLog::Graphics] Vulkan: Using extension: VK_KHR_surface
2026-09-15T20:57:27.050Z,2.050643,37ac,6 [FLog::Graphics] Vulkan: Using extension: VK_KHR_get_physical_device_properties2
2026-09-15T20:57:27.050Z,2.050643,37ac,6 [FLog::Graphics] Vulkan: Using extension: VK_KHR_win32_surface
2026-09-15T20:57:27.284Z,2.284634,37ac,6 [FLog::Graphics] VULKAN heapIndex = 0, heapFlags = 1 (device), heapSize = 4107571200
2026-09-15T20:57:27.284Z,2.284634,37ac,6 [FLog::Graphics] VULKAN unifiedMemory = true, device memory = 4107571200, host memory = 0, setting caps.videoMemory = 67108864
2026-09-15T20:57:27.284Z,2.284634,37ac,6 [FLog::Graphics] Vulkan Device: Intel(R) Iris(R) Xe Graphics
2026-09-15T20:57:27.284Z,2.284634,37ac,6 [FLog::Graphics] Vulkan Device: Vendor 8086 Device 9a49
2026-09-15T20:57:27.284Z,2.284634,37ac,6 [FLog::Graphics] Vulkan Device: Driver 0.402.1763 (1648355)
2026-09-15T20:57:27.284Z,2.284634,37ac,6 [FLog::Graphics] Vulkan Device: API 1.2.190

2026-09-15T20:57:27.286Z,2.286634,37ac,6 [FLog::Graphics] Vulkan: Loaded pipeline cache (79444 bytes, hash 53ae0d6f)
2026-09-15T20:57:27.286Z,2.286634,37ac,6 [FLog::Graphics] Vulkan: creating framebuffer 784x561
2026-09-15T20:57:27.444Z,2.444632,37ac,6 [FLog::Graphics] Vulkan: swapchain images 2 present mode 0 format 44 size 784x561
2026-09-15T20:57:27.445Z,2.445632,37ac,6 [FLog::Graphics] Video memory size: 67108864

2026-09-15T20:57:27.749Z,2.749654,37ac,6 [FLog::Graphics] Vulkan: resizing window framebuffer to 1920x1017
2026-09-15T20:57:27.826Z,2.826628,37ac,6 [FLog::Graphics] Vulkan: swapchain images 2 present mode 0 format 44 size 1920x1017
```
