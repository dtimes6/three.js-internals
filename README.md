# three.js-internals
three.js 的中文注解

# three.js src目录的结构
math：提供数学支持
object：主要功能是渲染，包含Mesh相关，Points，Line相关，Sprite，Lens相关，Skeleton，Group，Bone
core：核心数据框架

# core是最核心的模块。

# geometry是几何图形库。
里面所有的对象都是Geometry对象的子类。
新增加一个Geometry对象，需要修改 type，parameters setIndex 修改属性：position（位置） normal （法线） uv （分段信息）
