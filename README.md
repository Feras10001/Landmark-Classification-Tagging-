
Title: Classifying Landmark using Convolutional Neural Network CNN
---------------------------------------------------------

**Project motivation:** Photo sharing and photo storage services like to have location data for each photo that is uploaded. With the location data, these services can build advanced features, such as automatic suggestion of relevant tags or automatic photo organization, which help provide a compelling user experience. Although a photo's location can often be obtained by looking at the photo's metadata, many photos uploaded to these services will not have location metadata available. This can happen when, for example, the camera capturing the picture does not have GPS or if a photo's metadata is scrubbed due to privacy concerns.

If no location metadata for an image is available, one way to infer the location is to detect and classify a discernable landmark in the image. Given the large number of landmarks across the world and the immense volume of images that are uploaded to photo sharing services, using human judgement to classify these landmarks would not be feasible.

In this notebook, the first steps towards addressing this problem by building models to automatically predict the location of the image based on any landmarks depicted in the image. 

----------------------------------------------------------

**Requirements:**
The following libraries are included:
* numpy
* torch
* matplotlib

----------------------------------------------------------

**Files in the repository:**
* [Landmark.ipynb]: containes the full code
* [Landmark HTML]: Code viewed from browser
* [Test file]: contains picture used to test the algorithem

*data used:* it was provided by Udacity

-----------------------------------------------------------------

**Results:**
You can find a summary of my result either at the presentation, report, of my blog post.

-------------------------------------------------------------------

**Acknowledgement:**
This project was built over the data availed from Udacity.


