# shuilibu
'''
1. 需要打开一个基础的xls表格，读取同一个xls表中别的表格，然后把别的表格中的标准号对应的格填入基础xls表格中；
# 以下的操作都是对1的细分
2. 打开xls表
3. 打开xls种第一个表格，该表格为基础表格，第一列为化合物名称，第二列等都只有列头，没有内容，以后将会轮番打开子表格填入内容
4. 打开第一个子表格，读取子表格的名称（标准号），然后读取子表格对应行列的化合物名称。（化合物名称都从A4开始，然后A5，A6....）
5. 每在子表格中读取到一个非空化合物名称，都把化合物对应的“标准编号，标准名称，检测方法条款号，评价内容条款号，限制范围，适用范围 ”保存起来
6. 然后去基础表格中找化合物名称，找到标准编号，然后把“标准编号，标准名称，检测方法条款号，评价内容条款号，限制范围，适用范围 ”填入基础表格
7. 打开下一个表格，重复4-6
'''
