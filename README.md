# meu_app_streamlit
import streamlit as st

st.title("Meu Primeiro App Streamlit")
st.write("Olá! Este é meu app Python rodando no Streamlit Cloud.")

nome = st.text_input("Digite seu nome:")
if st.button("Enviar"):
    st.success(f"Olá, {nome}! 👋")
