#1
#請將「imdb_top_1000.xlsx」檔案存到你的Google雲端硬碟中，並分享檔案權限的方式讀取檔案中『Data』工作表中的資料，並命名為imdb1000資料集。(10%)
import pandas as pd
imdb_1000=pd.read_excel("https://drive.google.com/uc?id=1JmQOnDyv57UakbhZb7iVbzlyZNV4OJSa&export=download",header=0,thousands=",")
