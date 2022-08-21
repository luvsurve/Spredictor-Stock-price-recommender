<H1>Spredictor-Stock-price-recommender</H1>
<H4>A web application that analyses real-time data such as news, twitter tweets regarding particular stocks alongside it’s previous history to produce a consolidated prediction with impressive accuracy.</H4>

<img src="Repository_extra/Architecture.JPG" align="middle">


1. Recommend creating a virtual environment with python 3.8.10 using the command:<br>
    <code>virtualenv -p <interpreter-path> <my_env_name></code>
  
2. Activate the virtualenv:<br>
    <code>source <my_env_name>/bin/activate</code>
  
3. Use pip/pip3 and requirements.txt to install required packages:<br>
    <code>pip install -r requirements.txt</code>
  
4. Manually install other missing packages using pip command:<br>
    <code> pip install <module> </code> 
<h3>Project Directory after successful installation:</h3>        
<br><img src="Repository_extra/Post Installation.JPG">
        
5. Edit app.py and update news-api credentials(api-key)(generate at https://newsapi.org/)
  
6. Run the streamlit webserver using the commmand:<br>
    <code>streamlit run app.py</code>

<h3>Project Dashboard Preview:</h3>        
<a href="Repository_extra/project_dashboard.pdf">Click for Preview</a>
