# Social Media Embed iFrames

Small security first wrapper for social media embeds.

The advantage of the implementation is that the embeds are not integrated via JavaScript but via an iFrame. 
Also it is easier to implement such an embed.  
The consequence of this is that the respective provider does not know which page the user has accessed.   
Because of that I created this repository. 

So you just include a iFrame like that.

## Usage
iFrame:
```html
<iframe src="https://internetztube.github.io/social-embed-iframe/facebook?slug=microsoft" style="width: 100%;, height: 100%"; border: 0;></iframe>
``` 

## Provider
Facebook  Page
[https://internetztube.github.io/social-embed-iframe/embeds/facebook-page?slug=microsoft](https://internetztube.github.io/social-embed-iframe/embeds/facebook-page?slug=microsoft)  

Twitter  Profile
[https://internetztube.github.io/social-embed-iframe/embeds/twitter-profile?slug=microsoft](https://internetztube.github.io/social-embed-iframe/embeds/twitter-profile?slug=microsoft)