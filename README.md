<h1> AI & Machine Learning Fundamentals </h1>

Repository show the sample and easy structure to construct the image classification pipeline in pytorch.

<h4> Good Luck </h4>

<h2>Installation</h2>

Just run:

    pip install -r requirements.txt

If you are using Python environments, it is highly recommended to initiate the environment with system-site packages access to use GPU-related technologies without problems (e.g.: CUDA):

    python3 -m venv env --system-site-packages

In the command above, env is the name of the environment. You can change it to any name you want.

Then, activate the environment:

- <h5>Linux/macOS:</h5>

  source env/bin/activate

- <h5>Windows:</h5>

  env\Scripts\activate

<h2>TensorBoard</h2>

To visualize the training process, run the following command:

    tensorboard --logdir=runs

Then, open the browser and go to http://localhost:6006/ to see the training process.
