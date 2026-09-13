<div align="center">

```mermaid
flowchart TD

    DATA[Security Telemetry]

    DATA --> AUTH[Authentication Logs]
    DATA --> NET[Network Traffic]
    DATA --> PROC[Process Activity]
    DATA --> DNS[DNS Logs]

    AUTH --> FEAT[Feature Extraction]
    NET --> FEAT
    PROC --> FEAT
    DNS --> FEAT

    FEAT --> MODEL[Time Series Model]

    MODEL --> FCAST[Forecasting]
    MODEL --> ANOM[Anomaly Detection]

    ANOM --> ALERT[Security Alerts]
    FCAST --> CAP[Capacity Planning]

    style DATA fill:#333333,stroke:#000000,color:#ffffff
    style MODEL fill:#674ea7,stroke:#351c75,color:#ffffff
    style ANOM fill:#990000,stroke:#660000,color:#ffffff
    style ALERT fill:#f1c232,stroke:#bf9000,color:#000000
```

# [Time Series](https://www.ibm.com/think/topics/time-series-model) Toolkit
</div>

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]()
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)]()

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

## 📖 Contents
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)

<details>
 
 <summary>Install required tools on Linux</summary>
 
 ### For Ubuntu 18.04, 20.04, 22.04
 
 ```bash
 sudo apt-get update
 ```
 </details>
 
 
 <details>
 
 <summary>Install required python libs</summary>
 
 ### pip install
 ```bash
 pip install -r requirements.txt
 python3 setup.py install
 ```
 
 ### conda install
 ```bash
 conda config --add channels conda-forge
 conda install --file requirements_conda.txt
 python3 setup.py install
 ```
 
 </details>


##

### My Awesome Lists
You can access the my awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/Time-Series-Toolkit/graphs/contributors)!

[🔼 Back to top](#time-series-toolkit)
