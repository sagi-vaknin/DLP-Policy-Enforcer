<a name="readme-top"></a>

<h3 align="center">DLP Policy Enforcer</h3>

  <p align="center">
   DLP Policy Enforcer for Email Classification
    <br />
    <a href="https://github.com/YOUR_USERNAME/dlp-policy-enforcer"><strong>Explore the docs »</strong></a>
  </p>
</div>

## About The Project
This project implements a DLP (Data Loss Prevention) policy enforcer for classifying emails as ALLOW or BLOCK based on predefined rules. It processes email data from the ENRON dataset, performs data preprocessing, content and topic analysis using Named Entity Recognition (NER), key-based topic analysis, and rule-based content analysis. Additionally, it creates a custom Enron personnel dataframe to classify individuals based on email metadata. The project validates emails against predefined rules and determines whether to allow or block them, providing explanations for blocked emails based on the applied rules. Performance evaluation metrics such as confusion matrix are included for evaluation.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### File Structure
* DLP_Enforcer.ipynb: Main Jupyter Notebook containing the project code and analysis.
* workers_model.pkl: Pickle file containing the custom Enron personnel dataframe.
* README.md: Project documentation and instructions.

### Instructions
* Ensure you have Jupyter Notebook installed on your system.
* Open and run the DLP_Enforcer.ipynb notebook to execute the project code and analysis.

## Built With
* Python
* Jupyter Notebook

## Contact

Your Name - your.email@example.com<br>
LinkedIn  - https://www.linkedin.com/in/sagi-vaknin-sv <br>
Project Link: [https://github.com/sagi-vaknin/dlp-policy-enforcer](https://github.com/sagi-vaknin/dlp-policy-enforcer)


<p align="right">(<a href="#readme-top">back to top</a>)</p>
