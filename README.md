# Dog-Cat-classification
### About Dataset :

the dataset used in this project is : https://www.kaggle.com/datasets/tongpython/cat-and-dog

This dataset is for running the code from this site: https://becominghuman.ai/building-an-image-classifier-using-deep-learning-in-python-totally-from-a-beginners-perspective-be8dbaf22dd8.

This is how to show a picture from the training set: display(Image('../input/cat-and-dog/training_set/training_set/dogs/dog.423.jpg'))

From the test set: display(Image('../input/cat-and-dog/test_set/test_set/cats/cat.4453.jpg'))

See an example of using this dataset. https://www.kaggle.com/tongpython/nattawut-5920421014-cat-vs-dog-dl

### Notes :

1) *bring in the API of kaggle.json, you can use the following steps*:

     1) Create a new file called kaggle.json in your home directory.

     2) Copy and paste the API key that you generated from the Kaggle website into the kaggle.json file.

     3) Save the kaggle.json file.

Once you have done this, you can import the Kaggle API into your Python code using the following code:

    **import kaggle**

2) *import the dataset from Kaggle, you can use the following steps*:

     1) Go to the Kaggle website and find the dataset that you want to import.

     2) Click on the "Download" button and select the "API" option.

     3) Copy and paste the API key that you generated from the Kaggle website into the "API Key" field

     4) Click on the "Download" button.

       **!kaggle datasets download -d tongpython/cat-and-dog**

The dataset will be downloaded to your computer in a ZIP file. You can then unzip the file and import the data into your Python code using the following code:

    **df = pd.read_csv("data.csv")**

3) *About the zipfile* :

The zipfile library in Python is used to create, read, and write ZIP files. It can be used to compress and decompress files, as well as to extract files from a ZIP archive.

To use the zipfile library, you first need to import it into your Python code. You can do this by using the following code:

      **import zipfile**

To read a ZIP file, you can use the following code:


     **with zipfile.ZipFile('my_zip_file.zip', 'r') as zip_file:**
 
    **zip_file.extractall()**
