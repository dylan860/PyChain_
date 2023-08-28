![image](https://github.com/dylan860/PyChain_/assets/127907809/d2ef1f4f-8bbf-4b93-b88f-78516945d37a)
# PyChain_
The purpose of this challenge to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.
# Technologies
The credit risk resampling analysis leverages Python 3.8+ and utilizes the following project libraries and dependencies:

- Streamlit - a Python library that turns Python scripts into shareable web apps
- Pandas - a software library designed for open source data analysis and manipulation
- dataclasses
- typing
- hashlib

# Installation Guide
Download Anaconda for your operating system and the latest Python version, run the installer, and follow the steps. Restart the terminal after completing the installation. Detailed instructions on how to install Anaconda can be found in the Anaconda documentation.

This challenge utilizes Streamlit to create a user-friendly webpage interface for a blockchain. To import Streamlit, run the following command:
- pip install streamlit

# Usage
The analysis is hosted on the following GitHub repository at: 

# Run instructions:
To run this analysis, simply clone the repository or download the files. Open a terminal instance and navigate to the directory that contains the pychain.py file, and then run the following command:
- streamlit run pychain.py

# Streamlit User Interface
Utilizing the Streamlit interface, the user is able to enter sender, receiver, and amount details and click on 'Add Block' to create a new block. A block inspector is available on the left-hand side to verify the block has been added or to review all blocks stored in the ledger.
![image](https://github.com/dylan860/PyChain_/assets/127907809/e67fea96-c504-4e28-a67a-8231f1cc769d)
The Streamlit interface also allows the user to test the blockchain validation process by clicking on the 'Validate Chain' button. Once doing so, a 'True' response should be returned.
![image](https://github.com/dylan860/PyChain_/assets/127907809/dcd313bc-e268-4ec0-8c23-96d0afdc62fb)

# License
MIT

