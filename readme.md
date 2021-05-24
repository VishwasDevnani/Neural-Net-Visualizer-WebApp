# Neural-Net-Viusalizer-Webapp
It is a simple web-app that is trained on famous MNIST dataset on tensorflow using `keras` and `streamlit`
![](https://github.com/VishwasDevnani/Neural-Net-Visualizer-WebApp/blob/main/images/working%20example.png)

# Initial Setup:
1. Clone this repo: git clone [https://github.com/VishwasDevnani/Neural-Net-Visualizer-WebApp.git](https://github.com/VishwasDevnani/Neural-Net-Visualizer-WebApp.git)
2. open Anaconda Prompt/Command Prompt
3. Change your directory to the place where you cloned the repository, `` **ex**: cd C:\\User\\Acer\\**Example**\\NeuralNetVisulaizerApp ``
4. Either insall all libraries seprately or ` pip install -r requirements.txt `

# To Run the Program follow the steps below:
1. Train the model using ` python train_model.py `\ you can train the model yourself and save the weights as `model.hs`.
2. Start the flask server using `python ml_server.py`.
3. Now open another `cmd` and run `streamlit run app.py`(cd this to the same repo)
