create env
'''bash
conda create -n wineq python=3.8 -y
'''
acrivate env
''' bash
 conda activate wineq
 '''
 creata a req file
 '''
 bash
  conda activate wineq
  '''
  download data
  "https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5"
  git init
  dvc init
  dvc add data_given/winequality.csv
  git add .
  git commit -m "first commit"



