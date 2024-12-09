# DSC210 Group 1 Fall '24
## Data Mining Project: Recommendation Systems
### From SVD to BPR and T4Rec 

Group 1:
Joel Polizzi, Antariksha Ray, Lora Khatib, Jemin Vagadia

Examining recommendation systems past and present. We begin with a historical introduction into basic rating systems utilizing Single Value Decomposition of a matrix to provide item ratings, to evaluating a linear algebraic approach of Bayesian Personalized Ranking, and ending with a state-of-the-art approach leveraging Transformers for recommendation. 

We have chosen to use the McAuley-Lab/Amazon-Reviews-2023 dataset focusing the Musical Instruments subset. The dataset set is loaded from HuggingFace.

The repo contains all our final project material including our Project Report Latex and PDF, our slides, and our jupyter notebook containing the coding portions of the project.

## Table of Contents
- [Coding: Notebook Instructions](#coding-notebook-instructions)
- [Project Report](#project-report)
- [Slides](#Slides)
- [Rehearsal Feedback](#rehearsal-feedback)

## Coding: Notebook Instructions
In order to run our notebook the following requirements must be met:
- Verified Kaggle Account with P100 GPU

We are leveraging Kaggle for two key resons. 
1) Ability to easily connect the notebook
2) Free access with GPU availability. **NOTE**: GPU is free on Kaggle *** for 30 hours***. You will need to have GPU access to run out notebook. 

_This notebook was tested using the free P100 GPU Runtime in Kaggle. Please use the P100 GPU Runtime._

#### Step 1: Download the Group_1_DataMining.ipynb fro the repository
In the right hand corner you will want to "Download raw file" to download the notebook
![Download Notebook](images/kaggle/github1.png) <br>
Take note of where your download location is. 
![Download Location](images/kaggle/downloaded_nb.png)

#### Step 2: Navigate to Kaggle
Select Sign In or Register for an account if you do not have one
Navigate to Kaggle: ![https://www.kaggle.com/](https://www.kaggle.com/)
![Open Kaggle](images/kaggle/kaggle1.png)

#### Step 3: Sign in if you have already registered and account
Sign in with your preferred method. I used Google.<br>
![kaggle_sing_in](images/kaggle/kaggle2.png) <br>

Choose the account you wish to use<br>
![kaggle_sing_in_2](images/kaggle/kaggle3.png)

#### Step 4: Ensure you have verified your account with Phone Verification - REQUIRED FOR GPU ACCESS
Navigate tou your settings by clicking on the "Goose Head" icon in the upper right hand corner
![kaggle_goose](images/kaggle/kaggle4.png)<br>
![kaggle_set](images/kaggle/kaggle5.png)<br>
![kaggle_phone](images/kaggle/kaggle6.png)<br>
![kaggle_phone2](images/kaggle/kaggle7.png)<br>

_Access to GPU may take several minutes, we can now move to loading our notebook then enabling GPU_

#### Step 5: Create "New" Notebook
Navigate back to your front page and in the left hand pane select "Create" then in the drop down select "New Notebook" <br>
![kaggle8](images/kaggle/kaggle8.png)

#### Step 6: Load the notebook that you downloaded in Step 1
In the upper left open the File menu and select "Import Notebook" <br>
![kaggle9](images/kaggle/kaggle9.png) <br>

In the upload window select "Browse Files"<br>
![kaggle10](images/kaggle/kaggle10.png) <br>

Browse to the Downloaded notebook, and import it <br>
![kaggle11](images/kaggle/kaggle11.png) <br>



#### Step 2: Open the github repository directly from Colab
When You navigate to Google Colab you will be prompted to open a notebook. On the left hand side there is a link to open from Github. <br>
*Note: If you are not logged into github already then you may be prompted by colab to login in order for you to connect to the repo.<br>
You will need to enter in our github URL into the search field: https://github.com/joelpolizzi/DSC210-group_proj
![Open Github](images/colab2.png)

#### Step 3: Select the Group_1_DataMining.ipynb
Select the Group_1_DataMining.ipynb notebook and the project will open
![Open datamine](images/colab3.png)

#### Step 4: Select the T4 GPU Runtime
- In the upper right hand corner we will change the runtime. If the runtime states "T4" then you can skip to [Step 5](#step-5-sequentially-run-the-notebook-cells) <br>
 ![current-runtime](images/colab5.png) <br>
- To change the runtime open the "Connect" dropdown Menu: <br>
 ![change-runtime](images/colab6.png) <br>
- Select "Change Runtime Type" and select "T4 GPU". Make sure you Save. <br>
![change-runtime2](images/colab8.png) <br>
- Then Select "Connect" and the Runtime will connect to the T4 GPU Runtime. <br>
![connect](images/colab9.png) <br>
- In the upper right hand side you should now see a green check mark with "T4" <br>
![connected](images/colab10.png) <br>

#### Step 5: Sequentially Run The Notebook Cells

**For convience, in the first two cells of our notebook we are handeling the installation of python-pip dependencies for our project.**
- Outputs in our cells have been pre-run. When a cell is re-run the outputs will be re-written.
- Cells should be ran sequentially
- Run the cells to get the outputs!


## Project Report
Project report Latex and PDF can be found [HERE](./DSC210_Project_Report).

## Slides
Slides can be found [HERE](./slides)

## Rehearsal Feedback
Rehearsal feedback can be found [HERE](./rehearsal)
