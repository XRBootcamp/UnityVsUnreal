# Unity vs Unreal 2022
(Original article can be found here: https://xrbootcamp.com/unity-vs-unreal-engine-for-xr-development/)
### This is the open source version of the comparison table of the two most powerful game engines out there.
### Everyone is invited to contribute and to suggest changes.
#
| Feature/Criteria | Unity  | Unreal  |
| ------- | --- | --- |
| Visual Scripting | Unity visual scripting (formerly Bolt). Complements C# scripting, but with less documentation. Easily extendable. | Blueprint. The focus of scripting documentation. Powerful, but siloed from C++ scripting. More challenging to extend. |
| XR Integrations | ARFoundation, OpenXR, Oculus VR, Steam VR, Vive Wave, UWP for Hololens, Lumin OS for Magic Leap, Pico SDK**, WebXR. | OpenXR, Oculus VR*, Steam VR, Vive Wave**, UWP for Hololens, Lumin OS for Magic Leap, Pico SDK**. |
| Native Virtual Collaboration Tools (Source Control) | Perforce, Unity Teams / Plastic SCM. | Perforce, SVN. |
| Photogrammetry | Documented external pipeline | RealityScan (coming soon) |
| Stock Art Assets | Unity asset store, Sketchfab, Unity Art Engine. | Unreal marketplace, Sketchfab, Quixel Bridge. |
| Physics-Based Interactions for XR | PhysX, VR template, more 3rd-party plugins. | PhysX /Chaos, VR template, fewer 3rd-party plugins. |
| Native IK Based Interactions | Two-bone IK, Chain solver, FABRIK solver. | Two-bone IK, Trail solver, CCDIK, FABRIK solver, Full body IK. |
| Asset Management Pipeline | Original Asset + Metadata file.  You’ll still need to export from your authoring platform of choice, but there’s one less step to worry about when transferring assets, within the engine. | Asset converted to Unreal-specific format during import. This eliminates the need for a separate metadata file, but if an asset becomes corrupt, or is moved outside of its correct location, then it may be hard to recover. In addition, the linking system for assets is highly dependent. You must understand file-redirectors fully if you are going to frequently move or rename assets and folders. |
| Source Code Access | Read-only access to engine source. | Read/write access to engine source (after compiling from GitHub repo). |
| Rendering Capabilities | Efficient/moderate quality by default. High quality is attainable with greater effort. | High quality by default. Performance may suffer for mobile devices without optimization. |
| Animation Framework | State-machines, timelines/sequences, script-based animation. With enough time and effort, just about any feature visible to the end player/viewer of an Unreal product can see the same results produced with Unity. The limiting factor is the time it takes to reach these end results due to the requirement to build animation systems up from scratch. | State-machines, timelines/sequences, script-based animations, animation post-processing, in-engine rigging, live-link. The Blueprint a unique derivative: the Animation Blueprint. The ability to rapidly composite animations does not necessarily extend the functionality far beyond what Unity can provide, but it does provide a faster pipeline. |
| Shaders and Materials | HLSL, and Visual Material Scripting. Requires greater understanding of Shader programming. | Visual Material Scripting. Requires less understanding of Shader programming. |
| VFX Pipeline | VFX Graph. | Cascade (Legacy System), Niagra. |
| Networking Framework | Some built-in support, but mostly third party plugins are used, like Photon, Normcore or Mirror. | Built-in support out of the box is very good and battle tested in games as Fortnite. |
| WebXR | HTML5 build supported | Not Supported |
| Performance | Smaller distributions by default. less complex render pipelines result in fewer performance bottlenecks. | Larger distributions by default. Performance may suffer if the wrong features are left enabled for less capable hardware. |
| Samples and templates | Over 40 unique starting templates and samples supplied by Unity. | Over 30 unique starting templates and samples supplied by Unreal. |
| Documentation | More comprehensive. | More fragmented. Not all systems are documented in a central repository. |
| Support | Unity has a large community of developers, if you are stuck it is easy to find someone with a similar problem. | Unreal has a smaller community, if you are not an experienced developer it is easy to be stuck when developing. |
| License Costs | Start without fees, $ 399 per year/user for studios. No royalties. | Start without fees, 5% royalties for off-the-shelf products that exceed $1M gross profit over the lifetime of the product. |
| Target Industries | Cross-platform gaming, entertainment, and education. | AAA gaming, industrial engineering, medical device, and pharmaceuticals. |
| Learning Curve | More accessible for programmers. Unity has fewer bells and whistles by default, which enables learning fundamentals without being faced with challenging complex systems. | More accessible for artists. The wide range of systems, plugins, and tools make advanced work faster, but learning these systems will take longer. |
| Cross-Platform Deployment | Unity has wider cross-platform support, and with the URP pipeline, it is easy to deploy across multiple platforms without overhauling your projects. | Unreal has cross-platform deployment, but it requires more manual setup and application compilation knowledge. |

* Engine compilation required
** External download
