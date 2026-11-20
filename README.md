# SeedBox Worlds

供交互角色读取的世界示例。plaza.json 是一个原创广场的步行路网。

版本 1 使用 UTF-8 JSON。version 为整数 1，places 把唯一地点 ID 映射为显示名称。paths 中每项包含两个已声明的地点 ID，代表可双向步行的连接，每条连接的代价相同。没有路径连接的地点也可以存在。

贡献示例时，附上场景文件、起点、终点和预期路线。配套读取器见 [seedbox-agents](../../../seedbox-agents)。
