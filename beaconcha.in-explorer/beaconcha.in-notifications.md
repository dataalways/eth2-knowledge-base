# beaconcha.in notifications

This article provides a tutorial on setting up and debugging notifications using beaconcha.in's web and mobile platforms.&#x20;

It's worth noting that the current notification center will undergo an upgrade in late 2023 to upgrade its user-friendliness.

#### Enabling notifications via web

1. Head over to [https://beaconcha.in/user/notifications](https://beaconcha.in/user/notifications) and log in with your e-mail address.
2. Click on "Notifications Channels" and make sure the desired channels are active\
   ![](<../.gitbook/assets/image (22).png>)
3. Scroll down to the **Validators** table and add your validators. Once added you can _select all_ and bulk edit the notifications by clicking _Manage selected_.\
   ![](<../.gitbook/assets/image (14).png>)
4. Enable the desired notification(s) and press _Save_.\
   \
   ![](<../.gitbook/assets/image (24).png>)
5. Verify that the subscriptions are enabled\
   ![](<../.gitbook/assets/image (23) (1).png>)
6. If a notification was triggered it will show up in the Most recent column\
   ![](<../.gitbook/assets/image (13).png>)\

7. Done!

{% hint style="info" %}
You may have noticed that the Notification Center allows you to configure _**Push notifications**_ for the mobile app. This is crucial since some users may not receive any push notifications if it is disabled.
{% endhint %}



#### Mobile app

1. Download the app for iOS and Android here [https://beaconcha.in/mobile](https://beaconcha.in/mobile)
2. Create an account and log in with your e-mail address\
   \
   _**Note**: If you added validators to your Notification center through_ [_https://beaconcha.in/user/notifications_](https://beaconcha.in/user/notifications) _they will **not** appear in your mobile app automatically._\
   _If push notifications were enabled in the web notification center, the mobile app push the notifications through even if the validators are not visible in your app._\
   __\
   _This UX issue will be part of the improvements later this year._\
   __
3. Add validators to your mobile app dashboard&#x20;
4. Head over to the settings and enable the desired notifications\
   ![](<../.gitbook/assets/image (30).png>)\

5. Click the "Sync" button in the Validator section\
   &#x20; ![](<../.gitbook/assets/image (25).png>)\
   \

6. Done!\
   \
   Verify that the notifications were added successfully by logging in at [https://beaconcha.in/user/notifications](https://beaconcha.in/user/notifications) and scrolling to the Validator table at the bottom of the page\
   \
   ![](<../.gitbook/assets/image (23).png>)



#### Webhooks

1. Follow the steps as described [above](https://kb.beaconcha.in/beaconcha.in-explorer/beaconcha.in-notifications#enabling-notifications-via-web).
2. Double-check that webhooks are enabled\
   ![](<../.gitbook/assets/image (11).png>)
3. Add a webhook via [https://beaconcha.in/user/webhooks](https://beaconcha.in/user/webhooks)
4. Done
