# Development and deployment of a histopathology-based deep learning algorithm for patient prescreening in a clinical trial

## Overview
This is the primary code repository for reproducing analyses in Juan Ramon, Parmar, and Carrasco-Zevallos et al. 2024: "Development and deployment of a histopathology-based deep learning algorithm for patient prescreening in a clinical trial".

You can read the full publication in Nature (publication pending)

## Contents
1. `/scripts` contains all Python code used to produce content in `/figures` from `/data`
2. `/data` contains data tables with model outputs needed to reproduce the analysis from scratch
3. `/figures` contains plots in primary figures in .png

## Installation
1. Pull repository from ...
2. pip install -r requirements.txt

## Version and package requirements 
- Python version: 3.8.8
    - `pandas`
    - `numpy`
    - `matplotlib`
    - `seaborn`
    - `sklearn`
    
## Abstract 

Accurate identification of genetic alterationsin tumors, such as Fibroblast Growth Factor Receptor (FGFR+), is crucial
for treating with targeted therapies; however, molecular testing can delay patient care due to the time and tissue
required. Successful development, validation, and deployment of an AI-based, biomarker-detection algorithm could
reduce screening cost and accelerate patient recruitment. We developed a deep-learning algorithm using >3000
H&E-stained whole slide images from patients with advanced urothelial cancers, optimizing for high sensitivity to
avoid ruling out trial-eligible patients. The algorithm was validated on a dataset of 350 patients, achieving an area
under the curve of 0.75,specificity of 31.8% at 88.7% sensitivity, and projected 28.7% reduction in molecular testing.
We successfully deployed the system in a non-interventional study comprising 89 global study clinical sites and
demonstrate its potential to prioritize/deprioritize molecular testing resources and provide substantial cost savings
in the drug development and clinical settings.






## ########################
## License and Terms of Use
## ########################

Copyright 2023 Janssen Research and Development, Ltd. 

This is the License and Terms of Use (the “Terms of Use”) relating to Your use of the materials made available to You by the Licensor. Capitalized terms are as defined inline or in Section 4. 

The materials include two components: (a) the software and associated documentation files (the “Software”) and (b) one or more provided datasets (the “Data”).  Together the Software and the Data make up the “Licensed Material”.  

Licensor and You agree as follows:

1.	Provision of the Data

1.1	Subject to the terms and conditions of these Terms of Use, including the restrictions set forth in Section 2, You may, free of charge, Use the Licensed Material and/or any Results solely for the purpose of reproducing the results of the Study as part of Your internal research.

1.2	Licensor will not sue You for any claim arising out of the Use of the Licensed Material provided you meet the terms of these Terms of Use.

1.3	These Terms of Use do not restrict Your use, modification, or distribution of any portions of the Licensed Material that are in the public domain or that may be used, modified, or distributed under any other legal exception or limitation.

2.	 Restrictions on Use of the Software, Data, and Results

2.1	No Sharing of Software or Data.  You may NOT Share the Software or the Data, or any copies, reproductions, or derivatives thereof, with any third party, whether in modified or unmodified form.  You may Share any Results, to the extent that such Results do not themselves include any Data.

2.2	No reidentification of data.  You may NOT take any steps, or instruct or permit any individual or entity to take any steps on your behalf, to recreate or re-identify from the Data or the Results any information relating to an individual or set of patients.

2.3	No commercialization.  You may NOT use the Software, the Data, or any Results for any Commercial purpose whatever.

2.4	No non-Study use of Data.  You may NOT use the Data to generate, improve, or validate any Non-Licensed Material.  

2.5	The copyright notice included at the top of these Terms of use, the language of these Terms of Use, and a link to the repository from which You obtained the Software shall be included in all copies or substantial portions of the Software.

3.	 No Warranty, Limitation of Liability

3.1	THE SOFTWARE AND DATA IS PROVIDED ON AN “AS IS” BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, EITHER EXPRESS OR IMPLIED INCLUDING, WITHOUT LIMITATION, ANY WARRANTIES OR CONDITIONS OF TITLE, NON-INFRINGEMENT, MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.

3.2	LICENSOR SHALL NOT HAVE ANY LIABILITY FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING WITHOUT LIMITATION LOST PROFITS), HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE DATA OR RESULTS, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.

4.	 Definitions

4.1	“Commercial” means intended for or directed towards commercial advantage or monetary compensation.  “Commercialization” means any Commercial activity or any activity done in preparation for a Commercial activity.

4.2	“Data” means any material you receive under these Terms of Use in modified or unmodified form, but not including Results.

4.3	“Licensor” means the source from which you receive the Software and/or Data and with whom you enter into the Terms of Use.

4.4	“Non-Licensed Material” means (a) anything that you develop or improve from your Use of Data, or (b) any software other than the Software received under these Terms of Use. Artificial intelligence models trained on the Data are Non-Licensed Material.

4.5	“Result” means any output or outcome resultant from Using the Software with the Data or Using the Software with any dataset that You may own or may license from a third party. Results may include de minimis portions of the Data to the extent necessary to report on or explain aspects of the Study, such as figures in scientific papers, but do not include more.

4.6	Share means to provide material to the public or to any third party by any means or process that requires permission under the Terms of Use, such as reproduction, public display, publication, presentation, public performance, distribution, dissemination, communication, or importation, and/or to make material available to the public including in ways that members of the public may access the material from a place and at a time individually chosen by them.  Sharing includes any provision of the material even if under a non-disclosure or confidentiality agreement. 

4.7	“Use” means to use (or have used), copy (or have copied), modify (or have modified), and/or merge (or have merged). 

4.8	“You” means any individual or entity obtaining a copy of the Software and/or the Data and exercising any rights under these Terms of Use.  Your has a corresponding meaning.
# FGFR_Device_Review
