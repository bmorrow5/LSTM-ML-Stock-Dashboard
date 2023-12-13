This stock market dashboard needs to be run in jupyter notebook or jupyter lab, and will not work in most other IDEs due to how the packages run on jupyter notebook to host the dashboard localhost server. (Probably because Panel is owned by Anaconda)

To run the stock dashboard navigate to the folder bmorrow_final_project. We need to set up the environment to make sure this easily runs. 
Next run the commands:

conda env create -f environment.yaml
python -m ipykernel install --user --name=stock_dash

Now navigate to the jupyter notebook and you will now be able to run it. 


To remove this environment you can run:
conda env remove — name stock_dash
jupyter kernelspec uninstall stock_dash


The csv files are in the folder to ensure it runs if a new error occurs while web scraping.
** Disclamer do not use this model to actually predict the stock market. 