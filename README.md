# QAssist



## How To Use

### Installation

No local Installation or Environment preparation is required. You can use [Google Colab](https://colab.research.google.com/) to run the jupyter notebook we provide here. All you need is a valid Google account.

At the beginning of each notebook, there are a set of commands to install the required libraries and prepare the environment.

The provided notebooks require the objects within the main folder. So if you end up using Colab, you will need to [upload them in your environment](https://neptune.ai/blog/google-colab-dealing-with-files)

### IR_notebook

For the IR notebook, you can put the connect the environment with your Google Drive, if not you can remove the last two lines from the second cell.
This notebook requires **GTv6.obj** and **dexV2.obj** to run, which are found in the main folder. 
Adjust the path to these objects when loading them in cell 5 and 12.

The results of each step are saved in the *results* dictionnary object which you can call anytime to see the saved results.

At the end of the notebook, the *results* object can be visualized as a Pandas table.

### MRC_notebook

Similar to the IR notebook, you connect to Google Drive, or remove the last two line of the second cell. 
This notebook requires **GTv6.obj** to run, which can be found in the *main* folder. 
Adjust the path to this object when loading it in cell 5.

This notebook runs an ElasticSearch server, this server may stop for various reasons. 
When this happens a *ConnectionError* is raised. If you encounter this error, you can solve it by restarting the Elastic server (cell 15).

## License

This project is open-source under MIT license
