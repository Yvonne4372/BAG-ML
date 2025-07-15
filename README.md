# Brain-Age-Helsa


In this project, we aim to calculate the Brain Age Gap with traditional Machine Learning algorithms.

To achieve the goal, here are several steps to use this projects:

1. Running the Fastsurfer file, copy them to the commomd--Linux prompt.
2. Idealy the features are stored in a .txt file.
3. Now browsing the entire folder's structure, to check the path of the dataset, feature file, and demongraphic file.
4. Running the Machien Learning Algorithms: Regression, XGBoost, LightGBM, Supportvector, Randomforests
5. Check the results! Also, MAE values are provided.



For the Fastsurfer, here is a notification:

File Format: FAST requires input images in NIfTI format (.nii or .nii.gz). If your MRI data is in DICOM format, convert it to NIfTI using tools like dcm2nii (from MRIcron) or dcmstack. Example command:

         dcm2nii -o output_directory input_dicom_folder
