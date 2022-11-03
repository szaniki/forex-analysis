# Trend Analysis on British Pound

into will come her

## Usage  
   
some extra info my come here  **06 - Recommender.** plus info 

## Developer instructions

### Files included
   
- **0 - Obtaining data.** This notebook contains all the web scraping to get all the artists by movement from the web and the usage of the Chicago museum to build a dataset of images to recommend in the end.
- **1 - Identifying the classes and final image EDA.** As the name suggests in this notebook I identify the top classes to include in the classification model and fill in some missing values, also checking for invalid files.
- **2 - Model.** Building the first model as a baseline using fastai, a fantastic library that makes the process of building neural networks really simple. I will use this just as a baseline of performance and to learn some parameters to use further ahead.
- **2_1 - Resnet.** Modeling of the final model, tested 2 CNN architectures: VGG19 and RESnet50. As the name implies, the best was RESnet50, so I used it ahead. All processes explained in detail inside the notebook
- **3 - Building color palettes.** In this notebook I create color palettes for all images in our datasets. Used knn to cluster all colours in the image array and then picked up the centroid colours.
- **4 - Palette Classifying.**In the previous step I calculated all color palettes, here I'm making clusters of those palettes, so we are making groups of similar palettes.
- **5 - Deep color analysis.**I do a lot of plots here and I calculate the most influential color for each movement. The process is described in detail inside the notebook.
- **6 - Recomender.**Just run it, change your desired file to classify in the code and let the magic happen!
- **Recomender.py.** Using a Streamlit instance you can run this script and run the project as a nice web-based app that has a lot more info and detail than the jupyter notebook. Run first a terminal with the code
''' 
streamlit run Recomender.py
'''

### Folders and files

- **CSV's.** All the CSV’s used on the project. 
- **Images.** All the graphes obtained during the analsis, plus one image downloaded from Google.
- **Movement Plots.** Repository for all the plots I did, check them out to see the evolution of colour usage through time.
- **Presentation.pptx** Presentation based on the graphes plotting as part of the analysis, plus the output of my time series analysis - deep learning machine learning model. 

## Used technologies

- Yahoo Finance API
- Python
- Keras
- Matplotlib/Seaborn


## License

This is an educational project, all materials can be used freely. Reference to the project is welcome
