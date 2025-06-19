import streamlit as st

# Set page title
st.set_page_config(page_title="Suzhen's Portfolio", page_icon="🌟", layout="centered")

# Header
st.title("Hi, I'm Suzhen 👋")
st.subheader("Aspiring Cybersecurity Analyst & Creative Designer")

# About Me
st.header("About Me")
st.write("""
I am a professional with experience in overseas purchasing and a strong passion for cybersecurity. 
Currently seeking entry-level opportunities in cybersecurity or penetration testing.
I also enjoy creating digital art under my brand 'Mint Super Arts'.
""")

# Projects
st.header("Projects")
st.write("- **Cybersecurity Simulation**: Ransomware Defense Strategy Project")
st.write("- **Procurement System Improvement**: Reduced lead times by 20%")
st.write("- **Mint Super Arts**: Chibi-style Digital Art Collection")

# Contact
st.header("Contact")
st.write("📧 Email: youremail@example.com")
st.write("[LinkedIn Profile](https://linkedin.com/in/yourprofile)")

# Footer
st.write("---")
st.write("© 2025 Suzhen's Portfolio. All rights reserved.")
