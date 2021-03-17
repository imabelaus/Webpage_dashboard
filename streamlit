import streamlit as st 

st.title('Streamlit Example')

# use markdown syntax
st.write("""
# Explore different classifier and datasets
Which one is the best?
""")

# selectbox (move it to the sidebar with .sidebar)
dataset_name = st.sidebar.selectbox(
    'Select Dataset',
    ('Iris', 'Breast Cancer', 'Wine')
)

# widgets can be assigned to variables, 
# which obtain the value of the selection
K = st.sidebar.slider('K', 1, 15)

# plot
fig = plt.figure()
plt.scatter(x1, x2)
st.pyplot()
