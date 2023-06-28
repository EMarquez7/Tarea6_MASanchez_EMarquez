## **Inverse Transform & Rejection Sampling** <br><br>

<Details>
<Summary> <i>Repository Tools:</i> </Summary>
  
##### Actions:  [![Repo-Visualization-Badge](https://img.shields.io/badge/Action-Visualization-020521?style=square&logo=github&logoColor=white)](https://githubnext.com/projects/repo-visualization)<br>
##### Main Text-Editor:  [![VSCode-Badge](https://img.shields.io/badge/VSCode-007ACC?style=square&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)  [![Jupyter-Badge](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white)](https://jupyter.org/try)<br>
##### Language:  [![Python-Badge](https://img.shields.io/badge/Python-2b6dd6.svg?style=square&logo=Python&logoColor=green)](https://www.python.org)  [![LaTeX-Badge](https://img.shields.io/badge/LaTeX-white.svg?style=square&logo=LaTeX&logoColor=008080)](https://www.latex-project.org)  [![Markdown-Badge](https://img.shields.io/badge/Markdown-000000.svg?style=square&logo=Markdown&logoColor=white)](https://www.markdownguide.org)  [![yaml-Badge](https://img.shields.io/badge/YAML-000000?style=square&logo=yaml&logoColor=red)](https://yaml.org)<br>
##### Libraries:[![Numpy-Badge](https://img.shields.io/badge/Numpy-013243?style=flat-square&logo=numpy&logoColor=white)](https://numpy.org)[![Pandas-Badge](https://img.shields.io/badge/Pandas-150458?style=square&logo=pandas&logoColor=white)](https://pandas.pydata.org)  [![Scipy-Badge](https://img.shields.io/badge/Scipy-darkblue?style=square&logo=scipy&logoColor=white)](https://www.scipy.org)  [![Matplotlib-Badge](https://img.shields.io/badge/Matplotlib-000000?style=flat-square&logo=Matplotlib&logoColor=white)](https://matplotlib.org)<br>
##### Web-Interface:  [![React-Badge](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)](https://create-react-app.dev)<br>
##### Version Control:  [![GitHub-Badge](https://img.shields.io/badge/GitHub-100000?style=square&logo=github&logoColor=white)](https://github.com)  [![Git-Badge](https://img.shields.io/badge/Git-F05032.svg?style=square&logo=Git&logoColor=white)](https://git-scm.com)<br>
[![Git-Commads](https://img.shields.io/badge/Git%20Commands-gray?style=square&logo=git&logoColor=white)](https://github.com/EstebanMqz/Git-Commands)<br><br>

##### License:&nbsp;[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
</Details>

<Details>
<Summary> <i>Contact:</i> </Summary>

[![Website](https://img.shields.io/badge/Website-ffffff?style=square&logo=opera&logoColor=red)](https://estebanmqz.com) [![LinkedIn](https://img.shields.io/badge/LinkedIn-041a80?style=square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/esteban-m65381722210212839/) [![Portfolio](https://img.shields.io/badge/Github-Portfolio-010b38?style=square&logo=github&logoColor=black)](https://estebanmqz.github.io/Portfolio/) [![E-mail](https://img.shields.io/badge/Business-Mail-052ce6?style=square&logo=mail&logoColor=white)](mailto:esteban@esteban.com)

![GitHub Logo](https://github.com/EstebanMqz.png?size=50) [![Github](https://img.shields.io/badge/Github-000000?style=square&logo=github&logoColor=white)](https://github.com/EstebanMqz)
</Details>

<Details>
<Summary> <i>Repository Visualization:</i> </Summary>
  
[![Repository](https://img.shields.io/badge/Repository-0089D6?style=square&logo=microsoft-azure&logoColor=white)](https://mango-dune-07a8b7110.1.azurestaticapps.net/?repo=EstebanMqz%2FInv.Transform-and-Rejection-Sampling) [![Jupyter](https://img.shields.io/badge/Render-nbviewer-000000?style=square&logo=jupyter&logoColor=orange)](https://nbviewer.org/github/EstebanMqz/Inv.Transform-and-Rejection-Sampling/blob/main/Inv.T-Rejection-Sampling.ipynb)

<img src="diagram.svg" width="280" height="280"><br><br>

![Alt text](images/Description_Obj.jpg)
</Details>

<Details>
<Summary> <b>Results:</b> </Summary>

1. $f_1(x)$ over validation function $t_1(x)$ with *scipy* `optimize.fmin`.<br>
<img src="/images/maxtx-fx.png" width="365" height="250">
<br><br>

<i>(see nbviewer in <b>Repo Visualization 2-3</b>)</i><br>
2. Maximization arg max. in LaTeX <br>
3. Inverse Transform Method in LaTeX.<br><br>
4. Inverse Transform Method with `matplotlib`.<br>
<img src="/images/Inv.T-sampling.png" width="365" height="250">

5. Acceptance-Rejection Method within $f_1(x)$ over $t_1(x)$.<br>
<img src="/images/ARf1-t1.png" width="365" height="250">

<b>Rejected values are: 0.256</b><br><br>

6. Acceptance-Rejection Method of $f_1(x)$ over $t_2(x)$.<br>
<img src="/images/ARf1-t2.png" width="365" height="250">

<b>Rejected values are: 0.486</b><br><br>

7. Acceptance-Rejection Method of $f_2(x)$ over $t_1(x)$ and $f_2(x)$ over $t_3(x)$.<br>
<img src="/images/ARf2-t1.png" width="365" height="250">
<br>
<b>Rejected values are: 0.446</b><br>
<br><br>
<img src="/images/ARf2-t3.png" width="365" height="250">
<br>
<b>Rejected values are: 0.506</b><br>
<br>
<i>Note: Random values generated are slightly different per execution. </i>
</Details>

###### Considerations:
+ <i>Rejection sampling can be used with any $f(x)$.</i>
+ <i>Proposing $t(x)$ can be hard.</i><br>


#### References:<br>
[`scipy.optimize.fmin`](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.fmin.html) <br>
[`np.random.rand`](https://numpy.org/doc/stable/reference/random/generated/numpy.random.rand.html) <br>
[`np.random.uniform`](https://numpy.org/doc/stable/reference/random/generated/numpy.random.uniform.html) <br>
[Inverse-transform-sampling](https://en.wikipedia.org/wiki/Inverse_transform_sampling)<br>
[Rejection-sampling](https://en.wikipedia.org/wiki/Rejection_sampling) <br>


