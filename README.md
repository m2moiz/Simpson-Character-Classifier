This is repo contains a classifier that can predict the simpsons character given an input image. It is done by fine-tuning a pre-trained classifier, originally trained on Imagenet, on the Simpsons character dataset. The [Simpsons character dataset](https://www.kaggle.com/datasets/alexattia/the-simpsons-characters-dataset "Simpsons character dataset") is sourced from Kaggle and contains a total of 43 classes. Due to a class imbalance, the dataset requires specific data augmentation techniques to improve model accuracy.
## Requirements
- Python 3.6 or higher
- TensorFlow 2.x
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

You can install these dependencies using the following command:

```bash
pip install -r requirements.txt
```


## Running the Notebook 
1. Download the Simpsons character dataset from Kaggle and extract the files to a directory named `simpsons_dataset`. 
2. Open a terminal and navigate to the directory where the Jupyter notebook file is located. 
3. Run the following command to start Jupyter Notebook:

```bash
jupyter notebook
``` 
4. In your web browser, open the `Simpsons_Character_Classifier.ipynb` file. 
5. Follow the instructions in the notebook to fine-tune the pre-trained classifier on the Simpsons character dataset and evaluate its performance.
## Customization

You can customize the notebook by modifying the following files: 
- `Simpsons_Character_Classifier.ipynb`: This file contains the code for fine-tuning the pre-trained classifier on the Simpsons character dataset. You can modify the code to change the data augmentation techniques used or to use a different pre-trained classifier.
## To-Do
- Try other architectures to improve model accuracy.
- Turn this into a webapp using Streamlit or Rodeo to make it more accessible to non-technical users.
## Want to Contribute?

If you find a bug or would like to suggest a new feature, please feel free to open an issue or submit a pull request.
## License

This project is licensed under the MIT License
