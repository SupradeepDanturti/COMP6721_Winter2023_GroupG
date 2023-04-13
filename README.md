# **COMP6721_Winter2023_GroupG**
> *Project:- Age Classification Using Convolutional Neural Networks*

- [**Team Details**](#team-details)
- [**High level description/presentation of the project**](#high-level-description-presentation-of-the-project)
- [**Requirements**](#requirements)
- [**Instruction on how to train/validate the model**](#instruction-on-how-to-train-validate-the-model)
- [**Instructions on how to run the pre-trained model on the provided sample test dataset**](#instructions-on-how-to-run-the-pre-trained-model-on-the-provided-sample-test-dataset)
- [**Your source code package in PyTorch**](#source-code-package-in-pytorch)
- [**Description on how to obtain the Dataset from an available download link**](#description-on-how-to-obtain-the-dataset-from-an-available-download-link)
  * [*Original Dataset Link*](#original-dataset-link)
  * [*Dataset link after Splitting*](#dataset-link-after-splitting)






## **Team Details**
1. Nika Behjati (40154815)
2. Anahita Jabbari (40204349)
3. Supradeep Danturti (40226103)

## **High level description/presentation of the project**
- 
-
- 
- 
## **Requirements**
- PIL                 9.2.0
- cv2                 4.7.0
- matplotlib          3.5.2
- numpy               1.21.5
- sklearn             1.0.2
- torch               1.8.1+cu111
- torchvision         0.9.1+cu101
- cuda -> V11.1 
## **Instruction on how to train/validate the model**
- To train or validate the code use the 3 ipynb files mentioned in the first point of Source Code Package.
- Before running any of those 3 files please change the directory path in cell 4. [Link to cell 4 of UTKFaceipynb file](./Code/UTKFace/AllUTKFace/AllModelsOnUTKFaceDataset.ipynb#cell-4)
## **Instructions on how to run the pre-trained model on the provided sample test dataset**
- [Random Test Sample of 100 images from each dataset](https://drive.google.com/file/d/1Lsw0U2c2BQMXjaWgyLWOQG9oaGjfiTPm/view?usp=sharing)
- Use the [TestSampleOnPreTrainedModel file](./Code/TestSampleOnPreTrainedModel.ipynb) to run the pretrained models.
## **Source Code Package in PyTorch**
- There are 3 ipynb files of eaach dataset containing the initial 9 models which can be found here with their saved model files. [Dataset-1 UTKFace](./Code/UTKFace/AllUTKFace/) | [Dataset-2 Adience](./Code/Adience/AdienceAllModels/) | [Dataset-3 Appa-Real](./Code/AppaReal/AllModelsAppa-Real/)
- The 2 Transfer Learning models can be found here with their respective saved model files. [Transfer Learning Files](./Code/TransferLearning/)
- Preprocessing steps can be found [here](./Code/Preprocessing/).
- Dataset Study can be found [here](./Code/DatasetStudy.ipynb).
- **Note**- Other ipynb files and Saved models which are available in the code are mentioned under the Ablative Study section in results.
## **Description on how to obtain the Dataset from an available download link**
 - ### *Original Dataset Link*
- [Dataset 1 (APPA-REAL)](https://www.kaggle.com/datasets/abhikjha/appa-real-face-cropped)
- [Dataset 2 (UTKFace)](https://www.kaggle.com/datasets/jangedoo/utkface-new) 
- [Dataset 3 (Adience)](https://www.kaggle.com/datasets/arcarcarc/adience-dataset-preprocessed)

 - ## *Dataset link after Splitting*

- [Dataset 1 (APPA-REAL)](https://drive.google.com/file/d/1RH7qDhMHaoc-geTPYyFOaTCSz55t6ujb/view?usp=sharing)
- **Note** -  Used UTKFace BinarySplit for the final submission.
- [Dataset 2 (UTKFace)](https://drive.google.com/file/d/1xnCpeLVD-DQ0t3-ePJqSBOy6Fh5QMy_v/view?usp=sharing)
- [Dataset 2 UTKFace BinarySplit](https://drive.google.com/file/d/14uKBJwUZgMKRXsVvDAXk8dFjbYpmyPMb/view?usp=share_link)
- [Dataset 3 (Adience)](https://drive.google.com/file/d/1dKqpyg99OyuGnwvJTskDpps1HaUcjs2G/view?usp=sharing)
