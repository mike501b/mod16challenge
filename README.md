# mod16challenge

![Streamlit image](https://github.com/mike501b/mod16challenge/blob/main/Screenshot%202023-04-06%20142731.png)


This program runs a blockchain that can be visualized in Streamlit. To run the program, navigate to your directory and run "streamlit run pychain.py". In streamlit the user can add sender, receiver, and amount information and click "add block". The information will be added to the block chain.
---
## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For access to Pandas series and dataframes.

* [streamlit](https://docs.streamlit.io/) - For streamlit presentation.

* [hashlib](https://docs.python.org/3/library/hashlib.html) - To use Sha256 hash function.

* [datetime](https://docs.python.org/3/library/datetime.html) - To timestamp block entries

---


## Installation Guide
Before running the application first install the following dependencies.

import streamlit as st
import datetime as datetime
from dataclasses import dataclass
from typing import Any, List
import pandas as pd
import datetime as datetime
import hashlib