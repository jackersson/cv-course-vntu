### Install

    git clone https://github.com/jackersson/cv-course-vntu.git
    cd cv-course-vntu

    virtualenv -p python3 venv
    source venv/bin/activate
    pip install -r requirements.txt

    # Make Venv Visible in jupyter notebook
    python3 -m ipykernel install --user --name venv --display-name "cv_course"



### Syllabus

1. [Image Processing Basics](https://github.com/jackersson/cv-course-vntu/tree/master/image-processing-basics)

    jupyter notebook


### [Help](https://docs.google.com/document/d/1DoLfSMpU2_sZILJTonsvdk7ku7Jf6BdJCvfAZJJ96nY)


### Enable Python Widgets
- [IPython Widgets](https://ipywidgets.readthedocs.io/en/stable/user_install.html)

    pip install ipywidgets
    jupyter nbextension enable --py widgetsnbextension