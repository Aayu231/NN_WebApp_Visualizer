# NN_WebApp_Visualizer
A peek into how Neural Networks classify images from the MNIST dataset.

**MNIST** is the de facto _"Hello World"_ of image processing.

## Steps to run:
1. Run the Learner's Notebook(ipynb file) which will create the files necessary for visualization of a neural ntwork.
2. Train the model by running ```python train_model.py```. 20 epochs, takes about 5 minutes on a CPU with average processing power.
3. model.h5 is created.
4. Run the ml_server by executing ```python ml_server.py```.
5. With the flask server running, execute the virtual environment(Visualize) and start streamlit server using ```run streamlit run app.py```.

## Look and Feel:

