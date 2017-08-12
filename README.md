# cloudstorage
Various techniques for communicating with popular cloud sources
I need to find a reliable way of storing non-authenticating URLs to images I would like a specific set of users to view. The management of which users can view what is out of scope for this discussion at this time. I want to concentrate on the mechanics of aquiring these shareable URLs and the subsequent steps necessary to arrive an individual file (to start with, pictures).

# Facebook
I have found the URLs in facebook to be most stable (long expiration time):
https://scontent.xx.fbcdn.net/v/t1.0-9/3329_1135523581189_4919553_n.jpg?oh=7fb3ae770944a57fb16276c3e215f9aexxx
(a sample with a bit removed in the end so it does not actually work, I am not publishing my pictures publicly)

# Google Drive
https://drive.google.com/open?id=125Y3g0tPTYRE1ES88GrGAmTAmp-ZIm1Hog
(I don't mind sharing this picture)
This is a simple "shareable link". I will need to describe the API calls required to derive this. From here, I think I need to request the page and extract the <img src=> tag. Plus the added metadata which is the filename if desired.


# One Drive
https://1drv.ms/i/s!AiLMt6p0OOthgbgYVLrqhMZivmTPTg

I think the below has an expiration: ( raw JPG )
https://tt4ggq-bn1305.files.1drv.com/y4mMc9SheQwjELV2prKhwFQoYPsR0U-OBasDDXUYatb3zwjCSo9WH4Wbjkf1nTusMvLz3hEtU-OZRCjnUvdjFnLRJEWZ7xBCKlf3PL5iI5uLSOkVgMJjs2c_WQqvqZ7rSF1jTnFqNg1cEAUaBxMttABqKlE2SVx9yNK21cU12w4mUY9LROq1zBo8KLg1gwFstaJFnv-2wDqw4CCMpVeYLrKSA/DSC_0796.JPG?psid=1
