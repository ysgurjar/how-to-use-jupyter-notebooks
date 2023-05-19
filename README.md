# How to use jupyter notebooks?

* Edit a jupyter notebook
* Create a new jupyter notebook in a cloud IDE

## How to use this repo

1. Log into <a href="https://app.codeanywhere.com/" target="_blank" rel="noreferrer">CodeAnywhere</a> with your GitHub account.

1. On your Dashboard, click on the New Workspace button

1. Copy the https URL of this repo and paste it into the new workspace input

1. Click Create

1. Wait for the workspace to open. This can take a few minutes.

1. Open a new terminal and type <code>pip3 install jupyter</code>

1. In the terminal type <code>jupyter notebook --NotebookApp.token='' --NotebookApp.password=''</code> to start the jupyter server.

1. Open port 8888 preview or browser

1. Open the jupyter_notebooks directory in the jupyter webpage that has opened and click on the notebook you want to open.

1. Click the button Not Trusted and choose Trust.

Note that the kernel says Python 3. It inherits from the workspace so it will be Python-3.8.12 as installed by our template. To confirm this you can use <code>! python --version</code> in a notebook code cell.

## Other resources

The Python - Get started tab from the Python Extension also has a sample notebook to show off jupyters features. It also has a shortcut key combination to create new notebooks. 
