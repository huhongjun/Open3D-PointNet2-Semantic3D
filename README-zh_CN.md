

1. 采用open3d做电点云文件预处理；
	open3d先将txt转换为pts，再讲pts转换为pcd，转换完成后删除中间临时文件pts；

2. Pointnet2 点云语义分割

3. 环境安装
	安装open3d
    
    conda install -c open3d-admin open3d

4. 数据文件目录需要150G空间
