# app

To run a Streamlit app, you can use the following command in your terminal: streamlit run <filename>.py. Make sure you navigate to the directory where the Python script is saved. Otherwise, you’ll have to specify the full path to the file1.

If you’re using VSCode, you can configure it to run Streamlit apps. First create an app — something simple like this will do:

import streamlit as st 
st.write ("Hello from Streamlit")
When you first create this and save it as, for example, myapp.py, VSCode thinks it is just a normal Python file and if you try and run it from the Run menu it won’t do very much. To fix this, you need to tell VSCode that this is a Streamlit app by adding a configuration file
