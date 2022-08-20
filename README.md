<H1>Spredictor-Stock-price-recommender</H1>

1. Recommend creating a virtual environment with python 3.8.10 using the command:<br>
    <code>virtualenv -p <interpreter-path> <my_env_name></code>
  
2. Activate the virtualenv:<br>
    <code>source <my_env_name>/bin/activate</code>
  
3. Use pip/pip3 and requirements.txt to install required packages:<br>
    <code>pip install -r requirements.txt</code>
  
4. Manually install other missing packages using pip command:<br>
    <code>pip install <package-name></code>
<br>
<h3>Project Directory after successful installation:</h3>        
<br><img src="https://github.com/luvsurve/Spredictor-Stock-price-recommender/blob/main/Post%20Installation.JPG">
5. Edit app.py and update news-api credentials(api-key)(generate at https://newsapi.org/)
  
6. Run the streamlit webserver using the commmand:<br>
    <code>streamlit run app.py</code>
