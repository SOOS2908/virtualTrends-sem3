# virtualTrends-sem3
Getting started

clone this repository using vs code or any other method

then give the following commmands to terminal:

virtualenv env                  // create a virtual environment named env

env/Scripts/activate             // activate virtual environment (the command is for windows-based, it may be different for linux/unix based

pip install -r requirements.txt // automatically install all the required files and software to run the program
                                // ***if there is still something missing then use the same command "pip install file_name"

python manage.py migrate        // something like compilation, just to check if everything is in order

python manage.py runserver      // creates a link to open the website and view the functionalities

