# State-of-the-art Question Answering With Streamlit and HuggingFace

This is the code accompanying [this post](https://www.mihaileric.com/posts/state-of-the-art-question-answering-streamlit-huggingface/). You can try the app [here](https://wikipedia-transformers-qa.herokuapp.com/). Built using Streamlit and deployed on Heroku

**Note**: Heroku app is deployed using *tensorflow* framework, which doesn't play nicely with streamlit caching. For best experiences use *pytorch* framework. I have added a conditional decorator to avoid model reloading & effecient caching. However, the slug size for pytorch is above 850MB which far exceeds heroku's allowed slug size (500MB).

![qa_streamlit](resources/qa_streamlit.gif)

## Libraries Used
* Transformers
* Streamlit
