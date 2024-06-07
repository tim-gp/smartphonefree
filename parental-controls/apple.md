# Screen Time

[Screen Time](https://support.apple.com/en-us/108806) is Apple’s parental controls system and once configured it can be set to apply to all devices using the same Apple ID.

Start by [creating Apple IDs for any children under 13](https://support.apple.com/en-gb/HT201084) and then setup Family Sharing by [creating a family group](https://support.apple.com/en-gb/108380). This will enable you (and other family members you appoint as organisers) to manage screen time for your child remotely from your devices.

To enable Screen Time, on your child’s device go to **⚙️ Settings**, then **Screen Time** and choose **Turn On Screen Time**, then **This is my child’s…**

Once enabled you can configure many [different settings](https://support.apple.com/en-us/105121), ad this unofficial guide provides suggested initial settings **for a new iPhone** that are as restrictive as possible. If you apply these settings to an existing child’s iPhone, you should expect some things to stop working, so make sure you warn them and explain why you are making changes before you do.

> 💡 Apple refers to time when you are allowed to use the device Screen Time, and time when you are not allowed to use the device Downtime
>
> 💡 Sometimes these sections get renamed or moved around when software updates are applied.
>
> 💡 If you want to successfully manage your child using Screen Time we strongly recommend enabling it on your own device and seeing if you can prevent yourself from performing certain tasks

## Downtime

Limits usage to only the apps you choose and phone calls.

1. Toggle Scheduled to on and start with an Every Day schedule of 08:00 - 18:00
2. Ensure toggle Block at Downtime to on

>💡 **You must enable “Block at Downtime” for these limits to be enforced, otherwise your child can just press Ignore…**

## App Limits

Limit the amount of time that can be spent each day per app (or website) or group of apps. The minimum limit is 1 minute and there is a “One more minute” button which can be used each day on each app.

1. Create a 1 minute, Every day limit and add all apps that you do not want your child to be using to this group. Unfortunately you have to select each one individually
2. Next create limits for the apps that you do want your child to use


> 💡 **You must enable “Block at End of Limit”, otherwise your child can just press Ignore…**
>
> 💡 When you select more than one app in a limit, the total time can be used flexibly by your child, but not exceeded.

## Always Allowed

Select contacts and apps that can be used even when Downtime is enabled. Any apps you leave in the Allowed Apps section will be usable even when the device is in downtime.

1. In Allowed Contact, chose Specific Contacts and select the yourself
2. In Allowed Apps, remove all Apps

> 💡 The Phone app is always allowed

## Screen Distance

Warns your child if their device is too close to their face, required a device with Face ID.

1. Enable this

## Communications Limits

Control who your child can communicate with in Phone, Messages and FaceTime both during Screen Time and during Down Time.

1. In Allowed Communication, select Contacts Only
2. Enable Manage <name>’s Contacts
3. Ensure Contact Editing is disabled

> 💡 This suggestion is very restrictive. It means that only people that exist in your child’s Contacts can communicate with them. Messages from unknown number will not appear and if your child is in any group chats, if there is even a single unknown number the entire group will not appear. Disabling Contact Editing means they will have to talk with you to add someone to their address book.

## Communication Safety

Can detect nude photos and videos before they are viewed (or sent) in Messages

1. Enable Communication Safety
2. Disable Improve Communication Safety

## Content and Privacy Restrictions

1. Enable Content & Privacy Restrictions
2. Configure each section as follows
    
### iTunes & App Store Purchases
    
#### Store Purchases & Re-Downloads
    
1. Set **Installing Apps** to Don’t Allow
1. Set **Deleting Apps** to Don’t Allow
1. Set **In-app Purchases** to Don’t Allow
    
#### Require Password*
    
1. Set to Always Require
    
### Allowed Apps & Features
    
1. Disable everything apart from Camera
    
> 💡 Disabling Apps here does **not** prevent them from being used    
    
### Store, Web, Siri and Game Center Content

> 💡 If you want to install any apps from the App Store on your child’s phone, you will need to edit these settings
    
#### Allowed Store Content
    
1. Set **Music, Podcasts, News, Fitness** to Clean
1. Set **Music Videos** to Off
1. Set **Music Profiles** to Off
1. Set **Movies** to Don’t Allow
1. Set **TV Shows** to Don’t Allow
1. Set **Books** to Clean
1. Set **Apps** to Don’t Allow

#### Web Content

1. Set **Web Content** to Only Approved Websites

> 💡 This means your child cannot visit ANY websites, explain this to them and have them come and chat with you when they need access to something

#### Siri

1. Set **Web Search Content** to Don’t Allow
2. Set **Explicit Language** to Don’t Allow

#### Game Center

1. Set ALL settings to Don’t Allow

#### Privacy
    
1. Set **Share My Location** to Allow

> 💡 This is set to Allow so you can use Find My to see your child’s location

#### Allow Changes To

1. Set ALL to Don’t Allow

> 💡 Congratulations! You've got to the end of the Content and Privacy Restrictions section.

Enable **Include Website Data** so you can apply time limits to individual websites.

# Other Settings

These settings can only be configured on your child’s phone, but are worth considering.

## Notifications

Notifications will interrupt your child even when they’re not using their phone. We suggest turning off almost all notifications apart from the **Phone** app, and then building up slowly from there.

In **Settings**, go to **Notifications** and then for each app in the *Notification Style* section:

1. Disable **Allow Notifications**

For any apps where you would like your child to see there is new activity but not be interrupted, in the *Notification Style* section:

1. Enable **Allow Notifications**
1. In *Alerts*, untick *Lock Screen*, *Notification Centre* and *Banners*
1. In *Alerts*, disable *Sounds*

> 💡 For adults and older children we strongly recommend [scheduling a notification summary](https://support.apple.com/en-gb/guide/iphone/iph6534c01bc/17.0/ios/17.0#iphb9de540c3)

## Mobile Data

The **Mobile Data** section in **⚙️ Settings** lets you control which applications can access the internet using mobile data. Disabling an application means that it can only access the internet when your child's device is connected to a WiFi network.

> 💡 If you followed our Screen Time guide, you will need to *Allow Changes To* *Mobile Data* in the Content and Privacy Restrictions section of your child's screen time.

## Focus Modes
[Focus Modes](https://support.apple.com/en-gb/guide/iphone/iphd6288a67f/ios) let you control which contacts and apps are allowed to notify you. You can also customise the Lock and Home screens and Apple Watch face, and set the Focus to enable automatically on a schedule (perfect for school)

## Notes for Apple
Hi Apple! If you ever read this, please could you please improve Screen Time in the following ways so that your devices can be made safer for chldren and adolescents. 

Currently Screen Time feels like it's designed to be permissive by default, but on a device for children restrictive settings should be the default. 

Here's are my most wanted improvements.
1. Make it more responsive, often it takes more than 10s for the acitivy report to refresh and you have to go in and out of the screen to cause a refresh
1. Support Face ID / Touch ID for unlocking Screen Time rather than a passcode. Much harder for my child to bypass a biometric
1. Provide a Control Center widget to enable / disable Downtime quickly, one per child
1. Add a feature where only **Allowed** apps appear on the home screen and app library, include the ability to make any default Apple app inaccessible, including ⚙️ Settings
1. Make the "One more minute" feature configurable, default to off.
1. Make it possible to disable group chats in Messages
1. Allow multiple Downtime schedules in a day, I would like 18:30 - 08:00 AND 08:30 - 14:55 to cover overnight AND my child's school day.
1. In Always Allowed, provide seperate sets of Specific Contacts for Phone, Messages and Facetime. I want to have a different list of people for each of those apps that my child can contact during Downtime
1. Provide a ready-made child profile that uses Screen Time to make a restricted iPhone that only contains the following apps: Phone, Messages (no groups), Facetime, Camera, Photos, Maps and Find My. From this starting point, the Screen Time settings could be adjusted to add more features and functions as needed. 
1. Make is possible to prevent changes all aspects of ⚙️ Settings