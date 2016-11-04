# Cardiff Go Meetup's (http://www.meetup.com/Cardiff-Go-Meetup/) November Code Dojo Exercise

We were tasked with making some kind of rest API that consumed other rest APIs and then split up into groups.

Our team decided we would:
 
* Set up a web server that would:
    * get a picture from the Cat api
    * Convert it to ascii
    * Upload it to github as an anonymous gist
    * redirect the user to one of the above gists on every request
 
On the night, just before demonstrating the app I managed to delete the source code with git. I have reconstructed the code here for posterity.

* _Gist code based on: https://gist.github.com/minikomi/2861097_
* _Ascii code based on: https://github.com/stdupp/goasciiart_