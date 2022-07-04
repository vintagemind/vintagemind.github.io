
Firefox browser interestingly doesn't give the options to change the background into your desired wallpaper unlike Chrome. This works for macOS but not sure about others. Below are a few simple steps on how to do so. But I must warn you it is best to use addons because if something goes wrong, it will be a huge mess.


Step 1: 
Go to **about:support** in your search bar. Your screen should look like the following:

![image](https://user-images.githubusercontent.com/63845509/176843102-8ce5d09a-5050-4545-b664-bac7f5c97554.png)


Step 2:

Click the Show in Finder button next to Profile Folder. Create a folder called **Chrome** in the **nhtg6jgg.default-release** folder. Your screen should look like the below:

![image](https://user-images.githubusercontent.com/63845509/176843195-39c978fb-d516-4320-a790-ebc9005225c9.png)


Step 3: 

Inside the Chrome folder create a folder called **img** and a file called _userContent.css_. This img folder will store whatever picture you want as your wallpaper for your homepage. And the userContent.css file will contain the required code to allow the image to be displayed on your homepage. Your screen should look like the below:

![image](https://user-images.githubusercontent.com/63845509/176843383-be7d0313-f604-4bac-84d7-0582ecf12e91.png)


Step 4:

Inside the userContent.css file copy and paste in the following code:
Code for userContent.css:

```
@-moz-document url(about:home), url(about:newtab), url(about:privatebrowsing) {
    .click-target-container *, .top-sites-list * {
        color: #fff !important ;
        text-shadow: 2px 2px 2px #222 !important ;
    }

    body::before {
        content: "" ;
        z-index: -1 ;
        position: fixed ;
        top: 0 ;
        left: 0 ;
        background: #f9a no-repeat url(img/your_image_name_here.jpg)center;
        background-size: cover ;
        width: 100vw ;
        height: 100vh ;
    }
}
```

Step 5:

![image](https://user-images.githubusercontent.com/63845509/176843543-7b47ea7e-17e8-4710-9930-6250b14684c1.png)

Go to **about:config**, your screen should like the following: Next search for **toolkit.legacyUserProfileCustomizations.stylesheets** and set it to **true**.


![image](https://user-images.githubusercontent.com/63845509/176843619-22324020-0967-4e78-a666-e3d48dc0b38a.png)


Completion:

Once you've done all of the above, quit Firefox browser and open it again. You then should see your desired image (which should be in the img folder) as your background on the homescreen. You can put gif, jpeg, png, and jpg as the format of your image. But once again, it is best to use addons because if something goes wrong, it will be a huge mess.

Now enjoy your browser's new look and celebrate!!!



