🧥 Fashion MNIST Classifier
This project builds and trains a simple neural network using TensorFlow and Keras to classify images of clothing items from the Fashion MNIST dataset.

🚀 Features
Loads and preprocesses the Fashion MNIST dataset.

Builds a neural network with:

Input layer (flattening 28x28 images)

One hidden dense layer with 128 neurons and ReLU activation

Output layer with 10 neurons and softmax activation.

Compiles the model with the Adam optimizer and sparse categorical crossentropy loss.

Trains the model on the training set for 5 epochs.

Evaluates the model on the test set.

📂 Project Structure
css
Copy
Edit
fashion_mnist_classifier/
├── main.py
├── requirements.txt
├── README.md
└── LICENSE
🛠 Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/keviacs/fashion_mnist_classifier.git
cd fashion_mnist_classifier
(Optional) Create and activate a virtual environment:

bash
Copy
Edit
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
requirements.txt

txt
Copy
Edit
tensorflow
⚙️ Usage
Run the script to train the model and evaluate its performance:

bash
Copy
Edit
python main.py
Example output:

yaml
Copy
Edit
Epoch 1/5
1875/1875 [==============================] - 4s 2ms/step - loss: 0.4940 - accuracy: 0.8277
...
313/313 [==============================] - 0s 1ms/step - loss: 0.3857 - accuracy: 0.8604
Test accuracy: 86.04%
You can also use your own images for predictions by adding:

python
Copy
Edit
predictions = model.predict(my_images)
📝 License
This project is licensed under the MIT License. See the LICENSE file for details.

🙋‍♂️ Author
Kevin Carrasco Salazar
