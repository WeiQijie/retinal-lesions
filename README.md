# fundus-dr1593

Fundus-dr1593 containing 1593 color fundus images with expert labels. 
Each image is labeled with a diabetic retinopathy (DR) grade and segmentations of related lesions.
DR grades follow the [American Academy of Ophthalmology (AAO) guidelines for DR grading](https://www.aao.org/preferred-practice-pattern/diabetic-retinopathy-ppp-updated-2017).
For lesion segmentation, eight lesions are included: **microaneurysm**, **intraretinal hemorrhage**, **hard exudate**, **cotton-wool spot**, **vitreous hemorrhage**, **preretinal hemorrhage**, **neovascularization** and **fibrous proliferation**.

For expert labeling, a panel of 45 experienced ophthalmologists was formed. Each annotator marks out lesions in a given 
image using either ellipses or polygons and accordingly grade the image. Lesion annotation and DR grading from a single 
image are somewhat subjective. So for quality control, each image was assigned to at least three annotators. 
Images receiving consistent DR grades, i.e., the majority vote for a specific grade, are preserved.

For the preserved images, all the lesions labeled are preserved. Notice that the lesions and DR grades may not complied to the AAO guidelines (For example, a image is labeled with microaneurysm for lesion and DR0 for grading). The lesions not complied to the AAO guidelines are specially marked. 

Since all the images are from the [Kaggle Diabetic Retinopathy Detection challenge](https://www.kaggle.com/c/diabetic-retinopathy-detection), which originally provides DR grades for each image, DR grades from kaggle may have some differences with DR grades from us.
All the following statistics and examples are based on our labels.

![examples](examples)

Basic statistics of fundus-dr1593 are summarized as:

| | DR0 | DR1 | DR2 | DR3 |DR4 |
| :--   | --: | --:  | --:  | --:  | --:  |
| # Images | 116 | 337 | 929 | 99 | 62 |

## Downloads


## Reference

