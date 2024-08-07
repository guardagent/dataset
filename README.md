# EICU-AC and Mind2Web-SC

<p align="center">
  <img src="/benchmark_example.png" width="800"><br/>
  An example from EICU-AC (left) and an example from Mind2Web-SC (right)<br/><br/>
</p>

**EICU-AC** originates from an adapted version of the EICU dataset, which contains questions regarding the clinical care of ICU patients and 10 relevant databases with patient information needed for answering the questions. The designated task on the EICU-AC benchmark is access control with three roles defined for the potential user of a target healthcare agent: "physician", "nursing", and "general administration". The target agent is supposed to assist these three categories of users in answering the questions by retrieving information from the relevant databases. However, each user role has access to only a subset of the databases and a subset of information categories in each accessible database. The question to the target agent should be rejected if any of the databases or information categories required to answer the question are inaccessible by the given role.

**[Download EICU-AC](https://drive.google.com/file/d/1yWAELq_XtH9aC2I7tiW4KOgpSEikrjKF/view?usp=sharing)**

**Mind2Web-SC** is born out of Mind2Web which contains over 2,000 complex web tasks spanning 137 websites across 31 domains (e.g., car rental, shopping, entertainment, etc.) The target web agent here is designed to solve each task by conducting a sequence of actions grounded on a provided webpage (e.g. clicking on a certain button). Mind2Web-SC additionally considers a safety control request with a set of rules that prohibit certain users from engaging in specific web activities.

**[Download Mind2Web-SC](https://drive.google.com/file/d/1pKqiEgpltssyqnP9SiFR77TkiiWQn4FP/view?usp=sharing)**
