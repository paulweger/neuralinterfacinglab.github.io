---
title: Publication
permalink: /publication/
---

<hr>
<head>
<style>
<!-- styling for the cards -->
table {
  font-family: arial, sans-serif;
  border-collapse: collapse;
  width: 100%;
}

td, th {
border: 1px solid #dddddd;
text-align: left;
padding: 8px;
}

tr:nth-child(even) {
background-color: #dddddd;
}

td {
font-size: 14px;
}

a {
font-size: 16px;
line-height: 1px;
}

i {
font-size: 12px;
line-height: 1px;
padding-top: 5px
}

.well {
background-color: white;
border-radius: 30px;
}

.well:hover{
  background-color: #f5f5f5;
}

.search-container {
margin-bottom: 20px;
margin-left: 35%;

}

h4{
font-size: medium;
}

</style>
</head>

<!-- pasting all publications from _publications folder -->
### Recent Publications
<div id="publications-container">
{% for publication in site.publications %}
  <div class="col-sm-6 card-item">
    <div class="well">
      <a style="text-decoration: none; color: black; font-size: medium;" href="{{ publication.link }}">{{ publication.title }}</a>
      <p><img src="{{site.baseurl}}{{ publication.image }}" class="img-responsive" width="40%" style="float:left" alt=""></p>
      <p>{{ publication.description }}</p>
      <p><em>{{ publication.authors }}</em></p>
      <p><strong><a href="{{ publication.link }}">{{ publication.journal }}, {{ publication.year }}</a></strong></p>
    </div>
  </div>
{% endfor %}
</div>

<div class="col-sm-12" style="width: 100%;"></div>

<!-- group photo to be on the meet our team -->
<!-- img/peope/nh1--> 






<!-- <table>
 <tr><td><a href="https://www.biorxiv.org/content/10.1101/2022.07.04.498676v1">Executed and imagined grasping movements can be decoded from lower dimensional representation of distributed non-motor brain areas</a><br>
<i>Maarten C Ottenhoff, Maxime Verwoert, Sophocles Goulis, Albert Colon, Louis Wagner, Simon Tousseyn, Johannes P van Dijk, Pieter Kubben, Christian Herff</i><br>
bioRxiv, 2022</td></tr>
 <tr><td><a href="https://www.biorxiv.org/content/10.1101/2022.08.04.502829v1">The Nested Hierarchy of Overt, Mouthed, and Imagined Speech Activity Evident in Intracranial Recordings</a><br>
<i>Pedram Z Soroush, Christian Herff, Stephanie K Ries, Jerry J Shih, Tanja Schultz, Dean J Krusienski</i><br>
bioRxiv, 2022</td></tr>
  <tr><td><a href="https://www.cambridge.org/core/services/aop-cambridge-core/content/view/58CF5C42C9821AFF2092137B424884A7/S0033291722002367a.pdf/div-class-title-designing-daily-life-research-combining-experience-sampling-method-with-parallel-data-div.pdf">Designing daily-life research combining experience sampling method with parallel data</a><br>
<i>Joana De Calheiros Velozo, Jeroen Habets, Sandip V George, Koen Niemeijer, Olga Minaeva, Noëmi Hagemann, Christian Herff, Peter Kuppens, Aki Rintala, Thomas Vaessen, Harriëtte Riese, Philippe Delespaul</i><br>
Psychological Medicine, 2022</td></tr>
  <tr><td><a href="https://ieeexplore.ieee.org/abstract/document/9747300">Towards Closed-Loop Speech Synthesis from Stereotactic EEG: A Unit Selection Approach</a><br>
<i>Miguel Angrick, Maarten Ottenhoff, Lorenz Diener, Darius Ivucic, Gabriel Ivucic, Sophocles Goulis, Albert J Colon, Louis Wagner, Dean J Krusienski, Pieter L Kubben, Tanja Schultz, Christian Herff</i><br>
ICASSP 2022-2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2022</td></tr>
  <tr><td><a href="https://www.nature.com/articles/s41597-022-01542-9">Dataset of Speech Production in intracranial Electroencephalography</a><br>
<i>Maxime Verwoert, Maarten C Ottenhoff, Sophocles Goulis, Albert J Colon, Louis Wagner, Simon Tousseyn, Johannes P van Dijk, Pieter L Kubben, Christian Herff</i><br>
Scientific Data, 2022</td></tr>
<tr><td><a href="https://www.tandfonline.com/doi/abs/10.1080/2326263X.2021.2009654">Workshops of the eighth international brain–computer interface meeting: BCIs: the next frontier</a><br>
<i>Jane E Huggins, Dean Krusienski, Mariska J Vansteensel, Davide Valeriani, Antonia Thelen, Sergey Stavisky, James JS Norton, Anton Nijholt, Gernot Müller-Putz, Nataliya Kosmyna, Louis Korczowski, Christoph Kapeller, Christian Herff, Sebastian Halder, Christoph Guger, Moritz Grosse-Wentrup, Robert Gaunt, Aliceson Nicole Dusang, Pierre Clisson, Ricardo Chavarriaga, Charles W Anderson, Brendan Allison, Tetiana Aksenova, Erik Aarnoutse</i><br>
Brain-Computer Interfaces, 2022</td></tr>
</table>
### 2021
<table>
<tr><td><a href="https://arxiv.org/abs/2111.01457">Synthesizing Speech from Intracranial Depth Electrodes using an Encoder-Decoder Framework</a><br>
<i>Jonas Kohler, Maarten C Ottenhoff, Sophocles Goulis, Miguel Angrick, Albert J Colon, Louis Wagner, Simon Tousseyn, Pieter L Kubben, Christian Herff</i><br>
arXiv, 2021</td></tr><br>
<tr><td><a href="https://ieeexplore.ieee.org/abstract/document/9629639">Continuously Decoding Grasping Movements using Stereotactic Depth Electrodes</a><br>
<i>Maarten C Ottenhoff, Sophocles Goulis, Louis Wagner, Simon Tousseyn, Albert Colon, Pieter Kubben, Christian Herff</i><br>
2021 43rd Annual International Conference of the IEEE Engineering in Medicine & Biology Society (EMBC), 2021</td></tr>
<tr><td><a href="https://ieeexplore.ieee.org/abstract/document/9629711">Speech Synthesis from Stereotactic EEG using an Electrode Shaft Dependent Multi-Input Convolutional Neural Network Approach</a><br>
<i>Miguel Angrick, Maarten Ottenhoff, Sophocles Goulis, Albert J Colon, Louis Wagner, Dean J Krusienski, Pieter L Kubben, Tanja Schultz, Christian Herff</i><br>
2021 43rd Annual International Conference of the IEEE Engineering in Medicine & Biology Society (EMBC), 2021</td></tr>
<tr><td><a href="https://iopscience.iop.org/article/10.1088/1741-2552/ac2c9f/meta">Decoding four hand gestures with a single bipolar pair of electrocorticography electrodes</a><br>
<i>Maxime Verwoert, Mariska J Vansteensel, Zachary V Freudenburg, Erik J Aarnoutse, Frans S S Leijten, Nick F Ramsey, Mariana P Branco</i><br>
Journal of Neural Engineering, 2021</td></tr>
<tr><td><a href="https://www.nature.com/articles/s42003-021-02578-0">Real-time synthesis of imagined speech processes from minimally invasive recordings of neural activity</a><br>
<i>Miguel Angrick, Maarten C Ottenhoff, Lorenz Diener, Darius Ivucic, Gabriel Ivucic, Sophocles Goulis, Jeremy Saal, Albert J Colon, Louis Wagner, Dean J Krusienski, Pieter L Kubben, Tanja Schultz, Christian Herff</i><br>
Communications Biology, 2021</td></tr>
<tr><td><a href="https://www.sciencedirect.com/science/article/pii/S2213158221002734">Variability in subthalamic nucleus targeting for deep brain stimulation with 3 and 7 Tesla magnetic resonance imaging</a><br>
<i>Bethany R Isaacs, Margot Heijmans, Mark L Kuijf, Pieter L Kubben, Linda Ackermans, Yasin Temel, Max C Keuken, Birte U Forstmann</i><br>
NeuroImage: Clinical, 2021</td></tr>
<tr><td><a href="https://bmjopen.bmj.com/content/bmjopen/11/7/e047347.full.pdf">Predicting mortality of individual COVID-19 patients: A multicenter Dutch cohort*</a><br>
<i>Maarten C Ottenhoff, Lucas A Ramos, Wouter Potters, Marcus LF Janssen, Deborah Hubers, Shi Hu, Egill A Fridgeirsson, Dan Piña-Fuentes, Rajat Thomas, Iwan CC van der Horst, Christian Herff, Pieter Kubben, Paul WG Elbers, Henk A Marquering, Max Welling, Suat Simsek, Martijn D de Kruif, Tom Dormans, Lucas M Fleuren, Michiel Schinkel, Peter G Noordzij, Joop P van den Bergh, Caroline E Wyers, David TB Buis, W Joost Wiersinga, Ella HC van den Hout, Auke C Reidinga, Daisy Rusch, Kim CE Sigaloff, Renee A Douma, Lianne de Haan, Niels C Gritters van den Oever, Roger JMW Rennenberg, Guido A van Wingen, Marcel JH Aries, Martijn Beudel</i><br>
BMJ open, 2021</td></tr>
<tr><td><a href="https://www.frontiersin.org/articles/10.3389/fdgth.2021.618959/full?utm_source=S-TWT&utm_medium=SNET&utm_campaign=ECO_FDGTH_XXXXXXXX_auto-dlvrit">Digital health integration with neuromodulation therapies: the future of patient-centric innovation in neuromodulation</a><br>
<i>Yagna J Pathak, Walter Greenleaf, Leo Verhagen Metman, Pieter Kubben, Sridevi Sarma, Brian Pepin, Douglas Lautner, Scott DeBates, Alex M Benison, Binesh Balasingh, Erika Ross</i><br>
Frontiers in Digital Health, 2021</td></tr>
<tr><td><a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0249920">Can predicting COVID-19 mortality in a European cohort using only demographic and comorbidity data surpass age-based prediction: An externally validated study</a><br>
<i>Avishek Chatterjee, Guangyao Wu, Sergey Primakov, Cary Oberije, Henry Woodruff, Pieter Kubben, Ronald Henry, Marcel JH Aries, Martijn Beudel, Peter G Noordzij, Tom Dormans, Niels C Gritters van den Oever, Joop P van den Bergh, Caroline E Wyers, Suat Simsek, Renée Douma, Auke C Reidinga, Martijn D de Kruif, Julien Guiot, Anne-Noelle Frix, Renaud Louis, Michel Moutschen, Pierre Lovinfosse, Philippe Lambin</i><br>
PloS one, 2021</td></tr>
<tr><td><a href="https://link.springer.com/article/10.1186/s12859-021-03961-8">Tremor assessment using smartphone sensor data and fuzzy reasoning</a><br>
<i>Caro Fuchs, Marco S Nobile, Guillaume Zamora, Aurélie Degeneffe, Pieter Kubben, Uzay Kaymak</i><br>
BMC bioinformatics, 2021</td></tr>
<tr><td><a href="https://www.mdpi.com/2306-5729/6/2/22/pdf">A Long-Term, Real-Life Parkinson Monitoring Database Combining Unscripted Objective and Subjective Recordings</a><br>
<i>Jeroen GV Habets, Margot Heijmans, Albert FG Leentjens, Claudia JP Simons, Yasin Temel, Mark L Kuijf, Pieter L Kubben, Christian Herff</i><br>
Data, 2021</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:mvPsJ3kp5DgC">Clinical course of COVID-19 in the Netherlands: an overview of 2607 patients in hospital during the first wave</a><br>
<i>Marcel JH Ariës, Joop P van den Bergh, Martijn Beudel, Wim Boersma, Tom Dormans, Renee Douma, Annet Eerens, Paul WG Elbers, Lucas M Fleuren, L de Haan, IJCC van der Horst, S Hu, D Hubers, MLF Janssen, M de Kruif, PL Kubben, SMJ van Kuijk, PG Noordzij, M Ottenhoff, DAI Piña-Fuentes, WV Potters, AC Reidinga, RSC Renckens, S Rigter, D Rusch, M Schinkel, KCE Sigaloff, S Simsek, P Stassen, R Stassen, RM Thomas, GA van Wingen, M Welling, WJ Wiersinga, MDJ Wolvers, CE Wyers</i><br>
Nederlands Tijdschrift Voor Geneeskunde, 2021</td></tr>
<tr><td><a href="https://www.biorxiv.org/content/10.1101/2021.09.03.458142.full.pdf">Rapid dynamic naturalistic monitoring of bradykinesia in Parkinson’s disease using a wrist-worn accelerometer</a><br>
<i>Jeroen GV Habets, Christian Herff, Pieter L Kubben, Mark L Kuijf, Yasin Temel, Luc JW Evers, Bastiaan R Bloem, Philip A Starr, Simon Little</i><br>
bioRxiv, 2021</td></tr>
<tr><td><a href="https://www.sciencedirect.com/science/article/pii/S0303846720306843">The association between surgical characteristics and cognitive decline following deep brain stimulation of the subthalamic nucleus in Parkinson’s disease</a><br>
<i>Anne EP Mulders, Yasin Temel, Mehmet Tonge, Frédéric LWVJ Schaper, Vivianne van Kranen-Mastenbroek, Linda Ackermans, Pieter Kubben, Marcus LF Janssen, Annelien Duits</i><br>
Clinical Neurology and Neurosurgery, 2021</td></tr>
</table>
### 2020
<table>
  <tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:4fKUyHm3Qg0C">Adaptive median feature baseline correction for improving recognition of epileptic seizures in ICU EEG</a><br>
<i>Shivarudhrappa Raghu, Natarajan Sriraam, Erik D Gommer, Danny MW Hilkman, Yasin Temel, Shyam Vasudeva Rao, Pieter L Kubben</i><br>
Neurocomputing, 2020</td></tr>
<tr><td><a href="https://bmjopen.bmj.com/content/bmjopen/10/9/e040175.full.pdf">Serial measurements in COVID-19-induced acute respiratory disease to unravel heterogeneity of the disease course: design of the Maastricht Intensive Care COVID cohort (MaastrICCht)</a><br>
<i>Jeanette Tas, Rob JJ Van Gassel, Serge JH Heines, Mark MG Mulder, Nanon FL Heijnen, Melanie J Acampo-de Jong, Julia LM Bels, Frank C Bennis, Marcel Koelmann, Rald VM Groven, Moniek A Donkers, Frank Van Rosmalen, Ben JM Hermans, Steven JR Meex, Alma Mingels, Otto Bekers, Paul Savelkoul, Astrid ML Oude Lashof, Joachim Wildberger, Fabian H Tijssen, Wolfgang Buhre, Jan-Willem EM Sels, Chahinda Ghossein-Doha, Rob GH Driessen, Pieter L Kubben, Marcus LF Janssen, Gerry AF Nicolaes, Ulrich Strauch, Zafer Geyik, Thijs SR Delnoij, Kim HM Walraven, Coen DA Stehouwer, Jeanine AMCF Verbunt, Walther NKA Van Mook, Susanne Van Santen, Ronny M Schnabel, Marcel JH Aries, Marcel CG Van De Poll, Dennis Bergmans, Iwan CC Van Der Horst, Sander Van Kuijk, Bas CT Van Bussel</i><br>
BMJ open, 2020</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:08ZZubdj9fEC">Cross-database evaluation of EEG based epileptic seizures detection driven by adaptive median feature baseline correction</a><br>
<i>S Raghu, Natarajan Sriraam, Erik D Gommer, Danny MW Hilkman, Yasin Temel, Shyam Vasudeva Rao, Alangar Satyaranjandas Hegde, Pieter L Kubben</i><br>
Clinical Neurophysiology, 2020</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:abG-DnoFyZgC">Automated detection of epileptic seizures using successive decomposition index and support vector machine classifier in long-term EEG</a><br>
<i>Shivarudhrappa Raghu, Natarajan Sriraam, Shyam Vasudeva Rao, Alangar Sathyaranjan Hegde, Pieter L Kubben</i><br>
Neural Computing and Applications, 2020</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/pmc7405071/">Prefrontal High Gamma in ECoG tags periodicity of musical rhythms in perception and imagination</a><br>
<i>Steffen A Herff, Christian Herff, Andrew J Milne, Garett Johnson, Jerry J Shih, Dean J Krusienski</i><br>
eNeuro, 2020</td></tr>
<tr><td><a href="https://www.frontiersin.org/articles/10.3389/fnhum.2020.00144/full">Brain-computer interfaces and augmented/virtual reality</a><br>
<i>Felix Putze, Athanasios Vourvopoulos, Anatole Lécuyer, Dean Krusienski, Sergi Bermúdez i Badia, Timothy Mullen, Christian Herff</i><br>
Frontiers in human neuroscience, 2020</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7324271/">Complexity analysis and dynamic characteristics of EEG using MODWT based entropies for identification of seizure onset</a><br>
<i>Shivarudhrappa Raghu, Natarajan Sriraam, Yasin Temel, Shyam Vasudeva Rao, Alangar Sathyaranjan Hegde, Pieter L Kubben</i><br>
Journal of biomedical research, 2020</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:sSrBHYA8nusC">Mobile apps for neuroscience</a><br>
<i>Albert-Jan Plate, Pieter Kubben</i><br>
Neurotechnology: Methods, advances and applications, 2020</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:738O_yMBCRsC">EEG based multi-class seizure type classification using convolutional neural network and transfer learning</a><br>
<i>Shivarudhrappa Raghu, Natarajan Sriraam, Yasin Temel, Shyam Vasudeva Rao, Pieter L Kubben</i><br>
Neural Networks, 2020</td></tr>
<tr><td><a href="https://www.frontiersin.org/articles/10.3389/fnins.2020.00123/full">The potential of stereotactic-EEG for brain-computer interfaces: current progress and future directions</a><br>
<i>Christian Herff, Dean J Krusienski, Pieter Kubben</i><br>
Frontiers in Neuroscience, 2020</td></tr>
<tr><td><a href="https://peerj.com/articles/10317/">Machine learning prediction of motor response after deep brain stimulation in Parkinson’s disease—proof of principle in a retrospective cohort</a><br>
<i>Jeroen GV Habets, Marcus LF Janssen, Annelien A Duits, Laura CJ Sijben, Anne EP Mulders, Bianca De Greef, Yasin Temel, Mark L Kuijf, Pieter L Kubben, Christian Herff</i><br>
PeerJ, 2020</td></tr>
<tr><td><a href="https://mhealth.jmir.org/2020/5/e15628/">Mobile health daily life monitoring for Parkinson disease: development and validation of ecological momentary assessments</a><br>
<i>Jeroen Habets, Margot Heijmans, Christian Herff, Claudia Simons, Albert FG Leentjens, Yasin Temel, Mark Kuijf, Pieter Kubben</i><br>
JMIR mHealth and uHealth, 2020</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/pmc7526030/">Protocol: Serial measurements in COVID-19-induced acute respiratory disease to unravel heterogeneity of the disease course: design of the Maastricht Intensive Care COVID cohort (MaastrICCht)</a><br>
<i>Jeanette Tas, Rob JJ van Gassel, Serge JH Heines, Mark MG Mulder, Nanon FL Heijnen, Melanie J Acampo-de Jong, Julia LM Bels, Frank C Bennis, Marcel Koelmann, Rald VM Groven, Moniek A Donkers, Frank van Rosmalen, Ben JM Hermans, Steven JR Meex, Alma MA Mingels, Otto Bekers, Paul HM Savelkoul, Astrid ML Oude Lashof, Joachim E Wildberger, Fabian H Tijssen, Wolfgang FFA Buhre, Jan-Willem EM Sels, Chahinda Ghossein-Doha, Rob GH Driessen, Pieter L Kubben, Marcus LF Janssen, Gerry AF Nicolaes, Ulrich Strauch, Zafer Geyik, Thijs SR Delnoij, Kim HM Walraven, Coen DA Stehouwer, Jeanine AMCF Verbunt, Walther NKA Van Mook, Susanne van Santen, Ronny M Schnabel, Marcel JH Aries, Marcel CG van de Poll, Dennis CJJ Bergmans, Iwan CC van der Horst, Sander MJ van Kuijk, Bas CT van Bussel</i><br>
BMJ Open, 2020</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:D_sINldO8mEC">A Smartphone-Based Clinical Decision Support System for Tremor Assessment</a><br>
<i>Pieter Kubben, Uzay Kaymak</i><br>
Computational Intelligence Methods for Bioinformatics and Biostatistics: 16th International Meeting, CIBB 2019, Bergamo, Italy, September 4-6, 2019, Revised Selected Papers, 2020</td></tr>
<tr><td><a href="https://mededu.jmir.org/2020/2/e17030?utm_source=TrendMD&utm_medium=cpc&utm_campaign=JMIR_TrendMD_0">Understanding Medical Students’ Attitudes Toward Learning eHealth: Questionnaire Study</a><br>
<i>Kjeld Vossen, Jan-Joost Rethans, Sander MJ van Kuijk, Cees P van der Vleuten, Pieter L Kubben</i><br>
JMIR medical education, 2020</td></tr>
</table>
### 2019
 <table>
  <tr><td><a href="https://www.nature.com/articles/s41531-019-0093-5">Monitoring Parkinson’s disease symptoms during daily life: a feasibility study</a><br>
<i>Margot Heijmans, Jeroen GV Habets, Christian Herff, Jos Aarts, An Stevens, Mark L Kuijf, Pieter L Kubben</i><br>
npj Parkinson's Disease, 2019</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:cFHS6HbyZ2cC">A novel approach for classification of epileptic seizures using matrix determinant</a><br>
<i>Shivarudhrappa Raghu, Natarajan Sriraam, Alangar Sathyaranjan Hegde, Pieter L Kubben</i><br>
Expert Systems with Applications, 2019</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/pmc7539697/">Workshops of the seventh international brain-computer interface meeting: not getting lost in translation</a><br>
<i>Jane E Huggins, Christoph Guger, Erik Aarnoutse, Brendan Allison, Charles W Anderson, Steven Bedrick, Walter Besio, Ricardo Chavarriaga, Jennifer L Collinger, An H Do, Christian Herff, Matthias Hohmann, Michelle Kinsella, Kyuhwa Lee, Fabien Lotte, Gernot Müller-Putz, Anton Nijholt, Elmar Pels, Betts Peters, Felix Putze, Rüdiger Rupp, Gerwin Schalk, Stephanie Scott, Michael Tangermann, Paul Tubig, Thorsten Zander</i><br>
Brain-Computer Interfaces, 2019</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:D03iK_w7-QYC">Performance evaluation of DWT based sigmoid entropy in time and frequency domains for automated detection of epileptic seizures using SVM classifier</a><br>
<i>Shivarudhrappa Raghu, Natarajan Sriraam, Yasin Temel, Shyam Vasudeva Rao, Alangar Satyaranjandas Hegde, Pieter L Kubben</i><br>
Computers in biology and medicine, 2019</td></tr>
<tr><td><a href="https://link.springer.com/article/10.1007/s10143-017-0941-x">Deep brain stimulation of the anterior nucleus of the thalamus for drug-resistant epilepsy</a><br>
<i>Tim AM Bouwens Van Der Vlis, Olaf EMG Schijns, Frédéric LWVJ Schaper, Govert Hoogland, Pieter Kubben, Louis Wagner, Rob Rouhl, Yasin Temel, Linda Ackermans</i><br>
Neurosurgical review, 2019</td></tr>
<tr><td><a href="https://www.sciencedirect.com/science/article/am/pii/S092523121930133X">Interpretation of convolutional neural networks for speech spectrogram regression from intracranial recordings</a><br>
<i>Miguel Angrick, Christian Herff, Garett Johnson, Jerry Shih, Dean Krusienski, Tanja Schultz</i><br>
Neurocomputing, 2019</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/pmc6822609/">Speech synthesis from ECoG using densely connected 3D convolutional neural networks</a><br>
<i>Miguel Angrick, Christian Herff, Emily Mugler, Matthew C Tate, Marc W Slutzky, Dean J Krusienski, Tanja Schultz</i><br>
Journal of neural engineering, 2019</td></tr>
<tr><td><a href="https://www.frontiersin.org/articles/10.3389/fnins.2019.01267/full">Generating natural, intelligible speech from brain activity in motor, premotor, and inferior frontal cortices</a><br>
<i>Christian Herff, Lorenz Diener, Miguel Angrick, Emily Mugler, Matthew C Tate, Matthew A Goldrick, Dean J Krusienski, Marc W Slutzky, Tanja Schultz</i><br>
Frontiers in Neuroscience, 2019</td></tr>
<tr><td><a href="https://www.frontiersin.org/articles/10.3389/fnhum.2019.00401/full">Estimating cognitive workload in an interactive virtual reality environment using EEG</a><br>
<i>Christoph Tremmel, Christian Herff, Tetsuya Sato, Krzysztof Rechowicz, Yusuke Yamani, Dean J Krusienski</i><br>
Frontiers in Human Neuroscience, 2019</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/pmc6744823/">Stereotactic accuracy and frame mounting: A phantom study</a><br>
<i>Onur Alptekin, Felix S Gubler, Linda Ackermans, Pieter L Kubben, Mark L Kuijf, Ersoy Kocabicak, Yasin Temel</i><br>
Surgical neurology international, 2019</td></tr>
<tr><td><a href="https://library.oapen.org/bitstream/handle/20.500.12657/22918/1007243.pdf?sequence=1#page=170">Mobile apps</a><br>
<i>Pieter Kubben</i><br>
Fundamentals of Clinical Data Science, 2019</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/pmc6416754/">Feasibility of using a low-cost head-mounted augmented reality device in the operating room</a><br>
<i>Pieter L Kubben, Remir SN Sinlae</i><br>
Surgical neurology international, 2019</td></tr>
<tr><td><a href="https://library.oapen.org/bitstream/handle/20.500.12657/22918/1007243.pdf?sequence=1#page=10">Data Sources</a><br>
<i>Pieter Kubben</i><br>
Fundamentals of Clinical Data Science, 2019</td></tr>
</table>
### 2018
<table>
  <tr><td><a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0208119">Predicting altcoin returns using social media</a><br>
<i>Lars Steinert, Christian Herff</i><br>
PloS one, 2018</td></tr>
<tr><td><a href="https://onlinelibrary.wiley.com/doi/pdf/10.1002/mds.115">An update on adaptive deep brain stimulation in Parkinson's disease</a><br>
<i>Jeroen GV Habets, Margot Heijmans, Mark L Kuijf, Marcus LF Janssen, Yasin Temel, Pieter L Kubben</i><br>
Movement Disorders, 2018</td></tr>
<tr><td><a href="http://www.neurosurgery.dergisi.org/pdf.php?&id=2097">Management of hardware related infections after DBS surgery: a cost analysis</a><br>
<i>Pim Wetzelaer, Tim Vlis, Mehmet Tonge, Linda Ackermans, Pieter Kubben, Silvia Evers, Ersoy Kocabicak, Yasin Temel</i><br>
Turk Neurosurg, 2018</td></tr>
<tr><td><a href="http://neurosurgery.dergisi.org/pdf.php?&id=2029">Perioperative Technical Complications in Deep Brain Stimulation Surgeries</a><br>
<i>Onur Alptekin, Ersoy Kocabicak, Felix S Gubler, Linda Ackermans, Pieter L Kubben, Yasin Temel</i><br>
Turkish neurosurgery, 2018</td></tr>
<tr><td><a href="https://www.frontiersin.org/articles/10.3389/fnhum.2018.00440/abstract">Detection and Estimation of Working Memory States and Cognitive Functions Based on Neurophysiological Measures</a><br>
<i>Felix Putze, Christian Mühl, Fabien Lotte, Stephen Fairclough, Christian Herff</i><br>
Frontiers in Human Neuroscience, 2018</td></tr>
<tr><td><a href="https://csl.uni-bremen.de/cms/images/documents/publications/angrick_2018esann.pdf">interpretation of convolutional neural networks for speech regression from electrocorticography.</a><br>
<i>Miguel Angrick, Christian Herff, Garett Johnson, Jerry Shih, Dean Krusienski, Tanja Schultz</i><br>
ESANN 2018 - 26th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, 2018</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6293600/">Comparing deep brain stimulation in the ventral intermediate nucleus versus the posterior subthalamic area in essential tremor patients</a><br>
<i>Aurélie Degeneffe, Mark L Kuijf, Linda Ackermans, Yasin Temel, Pieter L Kubben</i><br>
Surgical neurology international, 2018</td></tr>
</table>
### 2017
 <table>
  <tr><td><a href="https://link.springer.com/article/10.1007/s00701-017-3242-9">Methodology, outcome, safety and in vivo accuracy in traditional frame-based stereoelectroencephalography</a><br>
  <i>Lars E van der Loo, Olaf EMG Schijns, Govert Hoogland, Albert J Colon, G Louis Wagner, Jim TA Dings, Pieter L Kubben</i><br>
Acta neurochirurgica, 2017</td></tr>
<tr><td><a href="https://core.ac.uk/download/pdf/189934577.pdf#page=73">Evaluating fNIRS-based workload discrimination in a realistic driving scenario</a><br>
<i>Christian Herff, Felix Putze, Tanja Schultz</i><br>
The First Biannual Neuroadaptive Technology, Conference (Berlin:), 2017</td></tr>
<tr><td><a href="https://www.researchgate.net/profile/Pieter-Kubben-2/publication/321391079_Teaching_Computer_Programming_to_Medical_Doctors_Nurses_and_Hospital_Staff_A_Pilot_Study/links/5bad103c92851ca9ed2a4bc1/Teaching-Computer-Programming-to-Medical-Doctors-Nurses-and-Hospital-Staff-A-Pilot-Study.pdf">Teaching computer programming to medical doctors, nurses and hospital staff: a pilot study</a><br>
<i>Pieter L Kubben, Pepijn Looije, Albert Scherpbier, Frits van Merode</i><br>
Open Acces J Neurol Neurosurg, 2017</td></tr>
<tr><td><a href="https://www.tandfonline.com/doi/pdf/10.1080/2326263X.2016.1275488">Workshops of the Sixth International Brain–Computer Interface Meeting: brain–computer interfaces past, present, and future</a><br>
<i>Jane E Huggins, Christoph Guger, Mounia Ziat, Thorsten O Zander, Denise Taylor, Michael Tangermann, Aureli Soria-Frisch, John Simeral, Reinhold Scherer, Rüdiger Rupp, Giulio Ruffini, Douglas KR Robinson, Nick F Ramsey, Anton Nijholt, Gernot Müller-Putz, Dennis J McFarland, Donatella Mattia, Brent J Lance, Pieter-Jan Kindermans, Iñaki Iturrate, Christian Herff, Disha Gupta, An H Do, Jennifer L Collinger, Ricardo Chavarriaga, Steven M Chase, Martin G Bleichner, Aaron Batista, Charles W Anderson, Erik J Aarnoutse</i><br>
Brain-Computer Interfaces, 2017</td></tr>
<tr><td><a href="https://drive.google.com/file/u/0/d/1xWc_8af9oZtyvlbEYhd1rIa4FivyiiC3/view">Biosignal-based spoken communication: A survey</a><br>
<i>Tanja Schultz, Michael Wand, Thomas Hueber, Dean J Krusienski, Christian Herff, Jonathan S Brumberg</i><br>
IEEE/ACM Transactions on Audio, Speech, and Language Processing, 2017</td></tr>
<tr><td><a href="https://www.csl.uni-bremen.de/cms/images/documents/publications/Herff2017MusicBCI.pdf">Signal Characterization for a Musical Rhythm BCI</a><br>
<i>Steffen A Herff, GD Johnson, Andrew J Milne, Christian Herff, J Kim, JJ Shih, DJ Krusienski</i><br>
Proceedings of 39th Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC'17): International Convention Centre, Jeju Island, Korea, July 11 to 15, 2017, 2017</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/pmc5502297/">Delayed cerebral ischemia after subarachnoid hemorrhage: Comparing and integrating classification systems</a><br>
<i>Pieter L Kubben, Menno R Germans, Ramazan Jabbarli</i><br>
Surgical neurology international, 2017</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5609441/">NeuroMind: Past, present, and future</a><br>
<i>Pieter L Kubben</i><br>
Surgical neurology international, 2017</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5655757/">Infections in deep brain stimulation: Shaving versus not shaving</a><br>
<i>Felix S Gubler, Linda Ackermans, Pieter L Kubben, Aysun Damci, Mark L Kuijf, Mayke Oosterloo, R Jeroen Vermeulen, Sarah Hescham, Ersoy Kocabicak, Erkan Kurt, Yasin Temel</i><br>
Surgical neurology international, 2017</td></tr>
<tr><td><a href="https://pdfs.semanticscholar.org/31c6/b3b68b280ee3c55be5df5332116010885782.pdf">Introducing “computational neurosurgery”</a><br>
<i>Pieter L Kubben</i><br>
Surgical neurology international, 2017</td></tr>
</table>
### 2016
<table>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:4JMBOYKVnBMC">EP 13. Tailored anesthetic techniques in patients with severe Tourette Syndrome undergoing surgery for Deep Brain Stimulation</a><br>
<i>M Bos, L Ackermans, A Smeets, P Kubben, V van Kranen-Mastenbroek, A Leentjens, W Buhre, V Visser-Vandewalle, Y Temel</i><br>
Clinical Neurophysiology, 2016</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:RHpTSmoSYBkC">EP 12. TREMOR12: An open-source mobile app for tremor quantification</a><br>
<i>P Kubben, M Kuijf, L Ackermans, A Leentjens, Y Temel</i><br>
Clinical Neurophysiology, 2016</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:R3hNpaxXUhUC">Technical feasibility of integrating 7 T anatomical MRI in image-guided radiotherapy of glioblastoma: a preparatory study</a><br>
<i>Inge Compter, Jurgen Peerlings, Daniëlle BP Eekers, Alida A Postma, Dimo Ivanov, Christopher J Wiggins, Pieter Kubben, Benno Küsters, Pieter Wesseling, Linda Ackermans, Olaf EMG Schijns, Philippe Lambin, Aswin L Hoffmann</i><br>
Magnetic Resonance Materials in Physics, Biology and Medicine, 2016</td></tr>
<tr><td><a href="https://www.thieme-connect.com/products/ejournals/html/10.1055/s-0035-1564419">Neurosurgical videos on YouTube</a><br>
<i>Julio Leonardo Barbosa Pereira, Felipe Batalini, Pieter L Kubben, Lucas Alverne Freitas de Albuquerque, Bernardo Andrada, Pollyana Magalhães, Gervásio Teles C de Carvalho, Eberval Gadelha Figueiredo</i><br>
Arquivos Brasileiros de Neurocirurgia: Brazilian Neurosurgery, 2016</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:iH-uZ7U-co4C">TREMOR12: an open-source mobile app for tremor quantification (vol 94, pg 182, 2016)</a><br>
<i>PL Kubben, ML Kuijf, L Ackermans, AFG Leentjens, Y Temel</i><br>
STEREOTACTIC AND FUNCTIONAL NEUROSURGERY, 2016</td></tr>
<tr><td><a href="https://www.csl.uni-bremen.de/cms/images/documents/publications/Interspeech2016_WeinerEtAl.pdf">Speech-Based Detection of Alzheimer's Disease in Conversational German.</a><br>
<i>Jochen Weiner, Christian Herff, Tanja Schultz</i><br>
Interspeech 2016, 2016</td></tr>
<tr><td><a href="https://www.frontiersin.org/articles/10.3389/fnins.2016.00429/full">Automatic speech recognition from neural signals: a focused review</a><br>
<i>Christian Herff, Tanja Schultz</i><br>
Frontiers in Neuroscience, 2016</td></tr>
<tr><td><a href="https://www.karger.com/Article/PDF/446610">TREMOR12: an open-source mobile app for tremor quantification</a><br>
<i>Pieter L Kubben, Mark L Kuijf, Linda PCM Ackermans, Albert FG Leentjes, Yasin Temel</i><br>
Stereotactic and functional neurosurgery, 2016</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4828953/">Programming for physicians: A free online course</a><br>
<i>Pieter L Kubben</i><br>
Surgical neurology international, 2016</td></tr>
</table>
### 2015
<table>
<tr><td><a href="https://www.frontiersin.org/articles/10.3389/fnint.2015.00046/full">Is there still need for microelectrode recording now the subthalamic nucleus can be well visualized with high field and ultrahigh MR imaging?</a><br>
<i>Ersoy Kocabicak, Onur Alptekin, Linda Ackermans, Pieter Kubben, Mark Kuijf, Erkan Kurt, Rianne Essselink, Yasin Temel</i><br>
Frontiers in integrative neuroscience, 2015</td></tr>
<tr><td><a href="https://www.frontiersin.org/articles/10.3389/fnins.2014.00373/full">Hybrid fNIRS-EEG based classification of auditory and visual perception processes</a><br>
<i>Felix Putze, Sebastian Hesslinger, Chun-Yu Tse, YunYing Huang, Christian Herff, Cuntai Guan, Tanja Schultz</i><br>
Using Neurophysiological Signals that Reflect Cognitive or Affective State, 2015</td></tr>
<tr><td><a href="https://link.springer.com/article/10.1007/s10143-015-0641-3">The start and development of epilepsy surgery in Europe: a historical review</a><br>
<i>Olaf EMG Schijns, Govert Hoogland, Pieter L Kubben, Peter J Koehler</i><br>
Neurosurgical review, 2015</td></tr>
<tr><td><a href="https://www.researchgate.net/profile/Vivianne-Van-Kranen-Mastenbroek/publication/283282101_A_detailed_analysis_of_intracerebral_hemorrhages_in_DBS_surgeries/links/5a25342da6fdcc8e86693785/A-detailed-analysis-of-intracerebral-hemorrhages-in-DBS-surgeries.pdf">A detailed analysis of intracerebral hemorrhages in DBS surgeries</a><br>
<i>Mehmet Tonge, Linda Ackermans, Ersoy Kocabicak, Vivianne van Kranen-Mastenbroek, Mark Kuijf, Mayke Oosterloo, Pieter Kubben, Yasin Temel</i><br>
Clinical neurology and neurosurgery, 2015</td></tr>
<tr><td><a href="https://europepmc.org/articles/4314833">Programming for physicians: A crash course.</a><br>
<i>Pieter L Kubben</i><br>
Surgical neurology international, 2015</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4352633/">E-learning for neurosurgeons: Getting the most from the new web tools</a><br>
<i>Julio Leonardo Barbosa Pereira, Pieter Leonard Kubben, Lucas Alverne Freitas de Albuquerque, Felipe Batalini, Gervásio Teles Cardoso de Carvalho, Atos Alves de Sousa</i><br>
Asian journal of neurosurgery, 2015</td></tr>
<tr><td><a href="https://internal-journal.frontiersin.org/articles/10.3389/fnins.2015.00217/full">Brain-to-text: decoding spoken phrases from phone representations in the brain</a><br>
<i>Christian Herff, Dominic Heger, Adriana De Pesters, Dominic Telaar, Peter Brunner, Gerwin Schalk, Tanja Schultz</i><br>
Frontiers in Neuroscience, 2015</td></tr>
<tr><td><a href="https://www.frontiersin.org/articles/10.3389/fnhum.2015.00617/full">Toward a wireless open source instrument: functional near-infrared spectroscopy in mobile neuroergonomics and BCI applications</a><br>
<i>Alexander Von Lühmann, Christian Herff, Dominic Heger, Tanja Schultz</i><br>
Frontiers in Human Neuroscience, 2015</td></tr>
</table>
### Older
<table>
<tr><td><a href="https://csl.uni-bremen.de/cms/images/documents/publications/BCI_Heger2014.pdf">Continuous affective states recognition using functional near infrared spectroscopy</a><br>
<i>Dominic Heger, Christian Herff, Felix Putze, Reinhard Mutter, Tanja Schultz</i><br>
Brain-Computer Interfaces, 2014</td></tr>
<tr><td><a href="https://internal-journal.frontiersin.org/articles/10.3389/fnhum.2013.00935/full">Mental workload during n-back task—quantified in the prefrontal cortex using fNIRS</a><br>
<i>Christian Herff, Dominic Heger, Ole Fortmann, Johannes Hennrich, Felix Putze, Tanja Schultz</i><br>
Frontiers in Human Neuroscience, 2014</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:ZeXyd9-uunAC">Intraoperative MRI versus standard neuron-avigation for the neurosurgical treatment of glioblastoma: a randomized controlled trial.</a><br>
<i>PL Kubben, Félix Scholtes, OEMG Schijns, Ter Laak-Poort, OPM Teernstra, AGH Kessels, JJ Van Overbeeke, Didier MARTIN, H Van Santbrink</i><br>
Surgical Neurology, 2014</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/pmc4078446/">Intraoperative magnetic resonance imaging versus standard neuronavigation for the neurosurgical treatment of glioblastoma: a randomized controlled trial</a><br>
<i>Pieter L Kubben, Felix Scholtes, Olaf EMG Schijns, Mariël P ter Laak-Poort, Onno PM Teernstra, Alfons GH Kessels, Jacobus J van Overbeeke, Didier H Martin, Henk Van Santbrink</i><br>
Surgical neurology international, 2014</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:roLk4NBRz8UC">The Use of Smartphones and Mobile Clinical Decision Support Systems in Clinical Clerkships.</a><br>
<i>AMR Schols, HHLM Donkers, Manuela Voorend, DML Verstegen, Henk Hoogland, Pieter Leonard Kubben</i><br>
International Journal of Interactive Mobile Technologies, 2013</td></tr>
<tr><td><a href="https://cyberleninka.org/article/n/1053140.pdf">Intraoperative magnetic resonance imaging for high grade glioma resection: Evidence-based or wishful thinking</a><br>
<i>Pieter L Kubben, Henk Van Santbrink</i><br>
Surg Neurol Int, 2013</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:4TOpqqG69KYC">Windows 8: A promise for tablet computers in the hospital?</a><br>
<i>Pieter L Kubben</i><br>
Surgical neurology international, 2013</td></tr>
<tr><td><a href="https://pdfs.semanticscholar.org/02f5/34e1475d3df90a9b00505c0637aeaf5dfbb2.pdf">Why physicians might want to learn computer programming</a><br>
<i>Pieter Kubben</i><br>
Surgical neurology international, 2013</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:mVmsd5A6BfQC">P. 298 MOBILE CLINICAL DECISION SUPPORT SYSTEMS FOR IMPLEMENTATION OF NEUROONCOLOGICAL GUIDELINES</a><br>
<i>P Kubben</i><br>
Neuro-oncology, 2012</td></tr>
<tr><td><a href="https://link.springer.com/content/pdf/10.1007/s00381-012-1815-8.pdf">Implementation of a mobile 0.15-T intraoperative MR system in pediatric neuro-oncological surgery: feasibility and correlation with early postoperative high-field strength MRI</a><br>
<i>PL Kubben, H Van Santbrink, M ter Laak-Poort, JW Weber, JSH Vles, B Granzen, JJ van Overbeeke, EMJ Cornips</i><br>
Child's Nervous System, 2012</td></tr>
<tr><td><a href="https://is.ieis.tue.nl/staff/pvgorp/research/VanGorpEtAl2012FHIESpreproceedings.pdf">MDE support for process-oriented health information systems: from theory to practice</a><br>
<i>Pieter Van Gorp, Irene Vanderfeesten, Willem Dalinghaus, Josh Mengerink, Bram van der Sanden, Pieter Kubben</i><br>
Pre-proceedings of FHIES 2012, 2012</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:qjMakFHDy7sC">Letter to the editor: Glioblastoma resection</a><br>
<i>Pieter Kubben, Henk van Santbrink</i><br>
Journal of neurosurgery, 2012</td></tr>
<tr><td><a href="https://cyberleninka.org/article/n/1173051.pdf">SLIC 2: Improved decision support for subaxial cervical spine injury</a><br>
<i>Pieter L Kubben</i><br>
Surg Neurol Int, 2012</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:r0BpntZqJG4C">Blogs for neurosurgeons</a><br>
<i>Pieter Kubben, Lucas Freitas De Albuquerque, Atos De Sousa</i><br>
Surgical Neurology International, 2012</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/pmc3551496/">An open-source and cross-platform framework for Brain Computer Interface-guided robotic arm control</a><br>
<i>Pieter L Kubben, Nader Pouratian</i><br>
Surgical neurology international, 2012</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:MXK_kJrjxJIC">Brain mapping: from neural basis of cognition to surgical applications</a><br>
<i>Pieter L Kubben</i><br>
Surgical Neurology International, 2012</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/pmc3551502/">Correlation between contrast enhancement on intraoperative magnetic resonance imaging and histopathology in glioblastoma</a><br>
<i>Pieter L Kubben, Pieter Wesseling, Martin Lammens, Olaf EMG Schijns, Mariël P ter Laak-Poort, Jacobus J van Overbeeke, Henk van Santbrink</i><br>
Surgical neurology international, 2012</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3385064/">Blogs for neurosurgeons</a><br>
<i>Júlio Leonardo Barbosa Pereira, Pieter L Kubben, Lucas Alverne Freitas de Albuquerque, Gervásio Teles C de Carvalho, Atos Alves de Sousa</i><br>
Surgical neurology international, 2012</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:YOwf2qJgpHMC">Online conferencing: Less CO 2, more effective?</a><br>
<i>Pieter Kubben</i><br>
Surgical neurology international, 2012</td></tr>
<tr><td><a href="https://pdfs.semanticscholar.org/e022/d11b95a862706685c8a141d8ceea54f9ce19.pdf">NeuroMind 2: Interactive decision support for neurosurgery</a><br>
<i>Pieter Kubben</i><br>
Surgical neurology international, 2012</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/pmc3551502/">Correlation between contrast enhancement on intraoperative magnetic resonance imaging and histopathology in glioblastoma</a><br>
<i>Pieter L Kubben, Pieter Wesseling, Martin Lammens, Olaf EMG Schijns, Mariël P ter Laak-Poort, Jacobus J van Overbeeke, Henk van Santbrink</i><br>
Surgical neurology international, 2012</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:u5HHmVD_uO8C">Intraoperative MRI-guided resection of glioblastoma multiforme: a systematic review</a><br>
<i>Pieter L Kubben, Karlien J ter Meulen, Olaf EMG Schijns, Mariel P ter Laak-Poort, Jacobus J van Overbeeke, Henk van Santbrink</i><br>
The lancet oncology, 2011</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/pmc3157090/">QR codes in neurosurgery</a><br>
<i>Pieter L Kubben</i><br>
Surgical neurology international, 2011</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/pmc3062806/">Twitter for neurosurgeons</a><br>
<i>Pieter L Kubben</i><br>
Surgical neurology international, 2011</td></tr>
<tr><td><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/pmc3086168/">An evidence-based mobile decision support system for subaxial cervical spine injury treatment</a><br>
<i>PL Kubben, H Van Santbrink, EMJ Cornips, Alex R Vaccaro, MF Dvorak, LW Van Rhijn, AJJA Scherpbier, H Hoogland</i><br>
Surgical neurology international, 2011</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=100&pagesize=100&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:QIV2ME_5wuYC">CONTRAST ENHANCEMENT ON INTRAOPERATIVE MRI: IS IT TUMOR?: P. 068.</a><br>
<i>P Kubben, H van Santbrink, M Lammens, M ter Laak-Poort, OEMG Schijns</i><br>
Neuro-oncology, 2010</td></tr>
<tr><td><a href="https://www.academia.edu/download/46045627/Transsphenoidal_Treatment_of_Secondary_E20160529-29428-17mt2mw.pdf">Transsphenoidal treatment of secondary empty sella syndrome using low field strength intraoperative MRI: case report</a><br>
<i>PL Kubben, EMJ Cornips, B-J Looij, EAM Beuls</i><br>
min-Minimally Invasive Neurosurgery, 2010</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=100&pagesize=100&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:d1gkVwhDpl0C">Intraobserver and interobserver agreement in volumetric assessment of glioblastoma multiforme resection</a><br>
<i>Pieter L Kubben, Alida A Postma, Alfons GH Kessels, Jacobus J van Overbeeke, Henk van Santbrink</i><br>
Neurosurgery, 2010</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=100&pagesize=100&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:Wp0gIr-vW9MC">A Collaborative Webbased Framework with Optimized Mobile Synchronisation: Upgrading to Medicine 2.0.</a><br>
<i>Pieter Leonard Kubben</i><br>
International Journal of Interactive Mobile Technologies, 2008</td></tr>
<tr><td><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=qJ8121AAAAAJ&cstart=100&pagesize=100&sortby=pubdate&citation_for_view=qJ8121AAAAAJ:u_35RYKgDlwC">Intraoperatieve MRI bij hersenchirurgie</a><br>
<i>PL Kubben, H Van Santbrink, GHJJ Spincemaille, WP Vandertop</i><br>
Nederlands Tijdschrift voor Geneeskunde, 2007</td></tr>
<tr><td><a href="https://europepmc.org/article/med/18257432">Intraoperative MRI in brain surgery</a><br>
<i>PL van Kubben, H van Santbrink, GH Spincemaille, WP Vandertop</i><br>
Nederlands tijdschrift voor geneeskunde, 2007</td></tr>
</table> -->


### Copyright Notice

The documents listed here are available for downloading and have been provided as a means to ensure timely dissemination of scholarly and technical work on a noncommercial basis. Copyright and all rights therein are maintained by the authors or by other copyright holders, notwithstanding that they have offered their works here electronically. It is understood that all persons copying this information will adhere to the terms and constraints invoked by each author's copyright. These works may not be re-posted without the explicit permission of the copyright holder.
