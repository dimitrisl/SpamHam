SpamHam Classifier


# open terminal
$ git clone https://github.com/dimitrisl/SpamHam.git

$ cd SpamHam

# create a virtual env
$ python3.6 -m venv assignment2

$ source assignment2/bin/activate

$ pip install torch==1.7.1+cpu torchvision==0.8.2+cpu torchaudio===0.7.2 -f https://download.pytorch.org/whl/torch_stable.html

$(assignment2) pip3 install spacy

$(assignment2) python3 -m spacy download en_core_web_sm

$ pip install -r requirements.txt
