
# MTCNN Comparasing 

We will be testing how much affect a stride of 2 on the kernel on the first will have on the overall performance.
## Getting Started

Download the Jupitor notebook on this repository.

### Prerequisites

all the Prerequitsites are install on Google Colab. I suggest running  it on Google colab.
```
Upload to Google colab
```




## Running the tests

you  will have to upload and image name test1.jpg into the Content/mtcnn directory.


### Break down into end to end tests

The first test will run the image on the MTCNN but the kernal will have a stride of two. the kernal will be skiping two pixels every time it scans for a face.

The second test will perform the original MTCNN with no stride at all. This will have more computations but should perform better depending on the image.

### after running both test on one image. Run the command !cd .. to back to the mtcnn directory

Upload another image name test1.jpg to replace the first image.
rerun the tests.


## Built With

* [TesnsorFlow](https://www.tensorflow.org) - Machine Learning Library
* [ipacc MTCNN repository](https://github.com/ipazc/mtcnn) - Implementation model and motified version

## Contributing




## Authors

* **Marco Mercado** - *Initial work* - [PurpleBooth](https://github.com/marcomerc)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.


## Acknowledgments

* ipacc

