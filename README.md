# Supporting Materials Folder Structure:

Note to Readers:
All the Jupyter Notebook (ipynb) files provided in this folder can be executed as-is in Google Colab.

Google Drive Link : https://drive.google.com/drive/folders/1kR85_1RHRHQEV5oNvKi61N1dsOSF9zbr?usp=drive_link

## 1. Experiments Folder:
   ### MobileNet:
     - Contains Jupyter Notebook (ipynb) files for the MobileNet model trained on hard targets.
     - Includes accuracy logs and loss curves.
   ### Resnet-18:
     - Contains Jupyter Notebook files for the Resnet-18 model trained on hard targets.
     - Includes accuracy logs and loss curves.
   ### Resnet-50:
     - Contains Jupyter Notebook files for the Resnet-50 model trained on hard targets.
     - Includes accuracy logs and loss curves.
   ### MobileNet_soft Folder:
     #### alpha Subfolder:
       - Contains Jupyter Notebook files with a fixed temperature value of 4.
       - Includes files for different distillation loss weight values.
     #### temp Subfolder:
       - Contains Jupyter Notebook files with different temperature values.
       - Includes files with a fixed distillation loss value of 0.9.
   ### resnet_18_soft Folder:
     #### temp Subfolder:
       - Contains Jupyter Notebook files with different temperature values.
       - Includes files with a fixed distillation loss value of 0.9.
     #### alpha Subfolder:
       - Contains Jupyter Notebook files with different distillation loss values.
       - Includes files with a fixed temperature value of 6.

## 2. Model Results:
   - An Excel file containing all the results for combinations of different distillation loss and temperature values, organized in rows.

### How to Run the Notebooks in Google Colab:
1. Click on the Google Drive link to access the folder.
2. Navigate to the desired notebook file.
3. Right-click on the file and select "Open with" > "Google Colab."
4. Once the notebook is open in Colab, click on the "Runtime" menu and select "Run all" to execute the entire notebook.
