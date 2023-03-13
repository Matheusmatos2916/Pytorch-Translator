# Pytorch Translator
This is a translator project using PyTorch, a popular Python machine learning library. The goal is to create a translation model capable of converting sentences in one language to another.

To start, we chose the WMT14 dataset, which contains English and German sentence pairs. We then create the neural network model using PyTorch. The model consists of an encoder layer and a decoder layer. The encoder takes input, in this case an English sentence, and converts it into a feature array. The decoder then takes this vector and outputs a German sentence.

After creating the model, we train with the WMT14 dataset. We used a GPU to speed up the training process, which took a few hours. We tested the model with a different test dataset to verify its accuracy and corrected any errors found.

We created a repository on GitHub to host our code. The repository includes model code, dataset files, and code to run the model. We also document the code with comments and clear instructions so others can understand and use the template.

With this project, we hope to provide a useful tool for language translation and encourage other developers to contribute to improving the model.
