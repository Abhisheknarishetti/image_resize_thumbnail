# image_resize_thumbnail
Sometimes you need to process the image once someone upload it to cloud storage, so anyone can upload any image and you will create a thumbnail from it,
here we use cloud functions to resize the image and add thumbnails to it.

here we use cloud storage bucket to store objects .
//gsutil mb gs://Bucket-name/  => in the place of bucketname we create our bucket
we use cloud functions and events and triggers to process the images
 //const gcs = require("@google-cloud/storage")();
//const PubSub = require("@google-cloud/pubsub");
 here "require"function is the easiest way to include modules that exist in separate files. The basic functionality of require is that it reads a JavaScript file, executes the file, and then proceeds to return the exports object.
require allows you to include modules in your programs. You can add built-in core Node.js modules, community-based modules (node_modules), and local modules.
