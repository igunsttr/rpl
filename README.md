cd d:
mkdir skripsi
cd skripsi
pip install --upgrade pip
pip install django (gk usah)
pip install pymysql  (gk usah)
pip install --only-binary :all: mysqlclient  (gk usah)
pip install django-admin 
pip install django-ai
django-admin startproject namaproject

conda install -c conda-forge imbalanced-learn
conda install -c conda-forge/label/gcc7 imbalanced-learn
conda install -c conda-forge/label/cf201901 imbalanced-learn

python manage.py createsuperuser
python manage.py makemigrations namaproject
python manage.py migrate namaproject
python manage.py runserver

http://localhost:8000

pip install scikit-learn numpy pandas matplotlib
