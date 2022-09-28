# Mexican_government-s_report_wordcloud

This is a short exercise to plot the 4th government report by the president of Mexico AMLO.

## Introduction
In this project, python web scraping tools are used to have a simple sight of the most common words used in 4th government report by the president of Mexico, the speech can be found on [president's website](https://lopezobrador.org.mx/2022/09/01/discurso-del-presidente-andres-manuel-lopez-obrador-en-el-cuarto-informe-de-gobierno/).

After retrieving our data set using **BeautifulSoup**,  **word_cloud** is used to  convert our obtained text into a word cloud image in order to focus on the words used on it.  

In addition some repeated and not relevant words are included in the "exclusion" word list, 

## Result

Here is the *.png* plot image result with 20.000 words:
![enter image description here](https://raw.githubusercontent.com/Osvajorge/Mexican_government-s_report_wordcloud/main/index.png)

###  Notes
Original idea from [Luis Jorge Nobelo](https://github.com/PhinanceScientist/AMLO_Wordcloud), Platzi teacher in: [Curso de Business Intelligence: Utilidad y Áreas de Oportunidad](https://platzi.com/cursos/business-intelligence/).
