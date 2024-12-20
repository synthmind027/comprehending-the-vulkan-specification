# Comprehending the vulkan specification

[Vulkan documentation](https://docs.vulkan.org/spec/latest/index.html)  
**Todo**: Comprehend [registry](https://registry.khronos.org/vulkan/)

## Contents of text
[Introduction](#Introduction)  
[Fundamentals](#fundamentals)  
[Initialization](#initialization)  
[Devices and Queues](#devices-and-queues)  
[Command Buffers](#command-buffers)  
[Synchronization and Cache Control](#synchronization-and-cache-control)  
[Render Pass](#render-pass)  
[Shaders](#shaders)  
[Pipelines](#pipelines)  
[Memory Allocation](#memory-allocation)  
[Resource Creation](#resource-creation)  
[Samplers](#samplers)  
[Resource Descriptors](#resource-descriptors)  
[Shader Interfaces](#shader-interfaces)  
[Image Operations](#image-operations)  
[Fragment Density Map Operations](#fragment-density-map-operations)  
[Queries](#queries)  
[Clear Commands](#clear-commands)  
[Copy Commands](#copy-commands)  
[Drawing Commands](#drawing-commands)  
[Fixed-Function Vertex Processing](#fixed-function-vertex-processing)  
[Tessellation](#tessellation)  
[Geometry Shading](#geometry-shading)  
[Mesh Shading](#mesh-shading)  
[Cluster Culling Shading](#cluster-culling-shading)  
[Fixed-Function Vertex Post-Processing](#fixed-function-vertex-post-processing)  
[Rasterization](#rasterization)  
[Fragment Operations](#fragment-operations)  
[The Framebuffer](#the-framebuffer)  
[Dispatching Commands](#dispatching-commands)  
[Device-Generated Commands](#device-generated-commands)  
[Sparse Resources](#sparse-resources)  
[Window System Integration (WSI)](#window-system-integration)  
[Deferred Host Operations](#deferred-host-operations)  
[Private Data](#private-data)  
[Acceleration Structures](#acceleration-structures)  
[Micromap](#micromap)  
[Ray Traversal](#ray-traversal)  
[Ray Tracing](#ray-tracing)  
[Memory Decompression](#memory-decompression)  
[Video Coding](#video-coding)  
[Optical Flow](#optical-flow)  
[Execution Graphs](#execution-graphs)  
[Extending Vulkan](#extending-vulkan)  
[Features](#features)  
[Limits](#limits)  
[Formats](#formats)  
[Additional Capabilities](#additional-capabilities)  
[Debugging](#debugging)  
[Vulkan Environment for SPIR-V](#vulkan-environment-for-spir-v)  
[Memory Model](#memory-model)  
[Compressed Image Formats](#compressed-image-formats)  
[Core Revisions (Informative)](#core-revisions)  
[Layers & Extensions (Informative)](#layers-&-extensions)  
[Vulkan Roadmap Milestones](#vulkan-roadmap-milestones)  
[API Boilerplate](#api-boilerplate)  
[Invariance](#invariance)  
[Lexicon](#lexicon)  
[Credits (Informative)](#credits)



## Introduction  
[Link](https://docs.vulkan.org/spec/latest/chapters/introduction.html)  
- The "Vulkan Specification" describes the Vulkan API.
- Vulkan is C99 API



## Fundamentals  
[Link](https://docs.vulkan.org/spec/latest/chapters/fundamentals.html)  
- All objects are created from VkDevice.
- Object creation: vkCreate* / vkAllocate*
- Object destruction: vkDestroy* / vkFree*
- Structure of object is immutable  
- Object creation is low-frequency in runtime
  - Allocate / free **can** occur high frequency.
    - Pool objects help its performance.
- Lifetime tracking responsibility: application
- Parent-child relations
    - VkCommandPool - VkCommandBuffer
    - VkDescriptorPool - VkDescriptorSet
    - VkDevice - _many object_



## Initialization  
- vkGetInstanceProcAddr
- vkGetDeviceProcAddr
- vkEnumerateInstanceVersion
- vkCreateInstance
  - VkInstanceCreateInfo
- vkDestroyInstance
- With callback



## Devices and Queues  
## Command Buffers  
## Synchronization and Cache Control  
## Render Pass  
## Shaders  
## Pipelines  
## Memory Allocation  
## Resource Creation  
## Samplers  
## Resource Descriptors  
## Shader Interfaces  
## Image Operations  
## Fragment Density Map Operations  
## Queries  
## Clear Commands  
## Copy Commands  
## Drawing Commands  
## Fixed-Function Vertex Processing  
## Tessellation  
## Geometry Shading  
## Mesh Shading  
## Cluster Culling Shading  
## Fixed-Function Vertex Post-Processing  
## Rasterization  
## Fragment Operations  
## The Framebuffer  
## Dispatching Commands  
## Device-Generated Commands  
## Sparse Resources  
## Window System Integration   
## Deferred Host Operations  
## Private Data  
## Acceleration Structures  
## Micromap  
## Ray Traversal  
## Ray Tracing  
## Memory Decompression  
## Video Coding  
## Optical Flow  
## Execution Graphs  
## Extending Vulkan  
## Features  
## Limits  
## Formats  
## Additional Capabilities  
## Debugging  
## Vulkan Environment for SPIR-V  
## Memory Model  
## Compressed Image Formats  
## Core Revisions 
## Layers & Extensions 
## Vulkan Roadmap Milestones  
## API Boilerplate  
## Invariance  
## Lexicon  
## Credits
