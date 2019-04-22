# SAM 和 BAM 格式数据

---

BAM是序列比对/图谱（SAM）格式的压缩二进制版本，是核苷酸序列比对的紧凑且可索引的表示。 许多新一代测序和分析工具与SAM / BAM配合使用。 对于自定义轨道显示，索引BAM优于PSL和其他人类可读对齐格式的主要优点是只有显示特定区域所需的文件部分才会传输到UCSC。 这样就可以显示文件中的对齐方式，这些文件非常大，以至于在尝试将整个文件上传到UCSC时，与UCSC的连接会超时。 BAM文件及其关联的索引文件都保留在Web可访问的服务器（http或ftp）上，而不是UCSC服务器上。 UCSC临时缓存文件的访问部分以加速交互式显示。