# python_AR_LA_PL_course
#处理芝加哥某街区地图数据
##裁切方法是使用osmosis命令行工具，查询osmosis给出的案例，寻找应用polygon提取数据的代码为：osmosis --read-xml file="planet-latest.osm" --bounding-polygon file="country2pts.txt" --write-xml file="germany.osm"，共涉及到三个参数，原始.osm数据；裁切边界polygon（.txt数据格式），
目视粗略判断点集聚的范围，在QGIS中绘制常规的polygon边界，编写polygon到osmosis格式的polygon代码
![得出地图图片]（C:\Users\97505\Desktop）
##用osm2sqlite把osm格式的文件转化成sqlite格式
#GHPYTHON中读取sqlite格式的文件，得出分析结果
##选取交通数据进行分析，从sqlite中导出csv格式的交通数据，得出excel数据表格

