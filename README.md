# upload-image-backend
Web API to upload images made in PHP, using Silex.


Check [api.php](https://github.com/BoldijarPaul/upload-image-backend/blob/master/api.php) and [FileHelper.php](https://github.com/BoldijarPaul/upload-image-backend/blob/master/FileHelper.php) to see how you can do it.
Also check the [android app client](https://github.com/BoldijarPaul/upload-image-android-client) that consumes this API. 


You can test your client on 
'http://boldijar.esy.es/api.php/

You need to do a POST request to /upload, using form data, where 'image' is the actual file (image).

Response example:
```javascript
{
  "success": true,
  "message": "Image successfully uploaded!",
  "imagePath": "oQkBWU6Qav.jpg"
}
```


Your image will be on http://boldijar.esy.es/images/oQkBWU6Qav.jpg .

You can use [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en) to test this.

![img1](http://i.imgur.com/hJbyhMT.png)
