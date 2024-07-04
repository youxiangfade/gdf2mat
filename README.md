# gdf2mat
The BIOSIG plug-in of eeglab in MATLAB is used to extract valid data and labels from .gdf files in BCICIV_2a datasets   
Only three parameters need to be configured: [folderPath], [savefolderPath], [isTrain]   
    
isTrain == ture extracts the training set data, and isTrain == false extracts the test set data.   

利用MATLAB中eeglab的BIOSIG插件，把BCICIV_2a数据集中的.gdf文件提取出有效数据及标签   
只需要配置folderPath,savefolderPath,isTrain三个参数，isTrain=ture提取训练集数据，isTrain=false提取测试集数据。   
