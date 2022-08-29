# OCR-website
This project is an OCR (tesseract) web interface to upload images. The idea of this project is to study technologies like Python, Django, Tesseract(OCR), Continuous Integration, Celery, etc...

How to install and Run
After activate your Python Virtual Environment (venv) run the below command:

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver
So you can access in the local URL: localhost:8000

Inside the requirements.txt there are a package called pytesseract. It´s the wrapper to communicate with the Tesseract library (C/C++ code). So, the next step is to install the Tesseract itself.

For this, please follow the below instructions for your SO:

Windows
Mac and Linux
If an additional language is required, is necessary to download it from here and move it to $TESSERACT_PATH/tessdata/

How to use
TBD
Libraries
Django
Pillow
Bootstrap
JQuery
Tesseract (pytesseract)
Celery
