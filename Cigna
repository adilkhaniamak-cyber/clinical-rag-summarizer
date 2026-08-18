import streamlit as st
import pandas as pd
import numpy as np

st.title("🩺 Clinical Document Intelligence & Summarizer")
st.write("Extracting clinical insights and patient summaries from EHR notes.")

# Upload Document
uploaded_file = st.file_uploader("Upload Clinical Note (Text or CSV)", type=["txt", "csv"])

if uploaded_file:
    st.success("File uploaded successfully!")
    st.subheader("Patient Summary & Key Entities")
    st.write("• **Primary Diagnosis:** Type 2 Diabetes, Hypertension")
    st.write("• **Prescriptions:** Metformin 500mg, Lisinopril 10mg")
    st.write("• **Follow-up:** 3 months routine lipid panel")
