## Guidelines to get data and insight from Instagram

### Prerequisite
* Instagram Professional account
* Facebook Page Account
### Configuration
* Instagram
    * connect to fackbook page
* Facebook
    * [Create an app](https://developers.facebook.com/apps) --> add product "Facebook Login" -> save default settings
    * [Graph API Explorer](https://developers.facebook.com/tools/explorer/)
        * Get Access Token
        * Get User ID, Page ID, Instagram ID and Media object
            * <code>GET /me/accounts</code>
              ![img.png](picture/img_page_id.png)
            * <code>GET /{page-id}?fields=instagram_business_account</code>
              ![img.png](picture/img_ig_id.png)
            * <code>GET /{ig-user-id}/media</code>
              ![img.png](picture/img_data_id.png)
###Instagram Insights

![img.jpg](picture/photo_video_metrics.JPG)

* impression(#seen)
* reach accounts(#account seen)
* saved
* video_views
  

#### Reference
https://developers.facebook.com/docs/instagram-api/getting-started
https://developers.facebook.com/docs/instagram-api/reference/ig-media/insights/
https://developers.facebook.com/tools/explorer/
