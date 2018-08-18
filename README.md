# Features of c²engine
- 数据驱动，减少逻辑层面荷藕，也可以更方便多线程/进程/多物理机联合的体系。
- 模块边界清晰。层次清晰。
- 用户接口精简。
- 尽可能的stateless。
- occlusion culling。
- voxel平滑。
- terrain。
- 材质模板化，二次元/物理海浪/3A材质等。
- 并不打算面向普通用户提供shader扩展或者material编辑工作，因为这不符合用户画像，做出来也是个半吊子。而且现在shader规范还没有形成国际统一标准。不过会给有经验开发人员提供扩展shader的机制，就如同我们的Director里的Action/Unit的扩展机制一样。
- Director with NLP ready。
- 坐标空间扭曲后处理。
- 支持webassembly。
- webgl/webgpu/vukan/directx12图形API无关。
- 三角图元优化。
- DR/MRT/PBR/GI/OA。
- Click-to-Play/streaming。支持unity3d/cocos/ue等任意产品。
