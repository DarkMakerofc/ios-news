## <u> IOS NEWS SCRAPER <u> 
🍎 The UnOfficial ios News Scraper By [Mr Nima](https://github.com/DarkMakerofc). <br>
#### ✅ How To Use
```
const { iosNews } = require('ios-news')
const result = await iosNews()

console.log(result)
```
<br> 
You Can Get Apple News Updates Using This. 

<br>

#### 🔍 Result 

```
{
  creator: 'MR NIMA',
  status: true,
  result: [
    {
      title: 'Top Stories: visionOS SDK, iOS 17 Beta 2, and More',
      time: 'Saturday June 24 |  2023 6:00 am PDT',
      img: 'https://images.macrumors.com/t/vN6lkL6_8txA8C3lTew1EU5oJxM=/400x0/article-new/2023/06/top-stories-24jun2023.jpg?lossy',
      link: 'https://www.macrumors.com/2023/06/24/top-stories-visionos-sdk/',
      desc: "It's been two weeks since WWDC wrapped up, and this week saw Apple release the second round of betas of its upcoming operating system updates introduced at the conference, plus the initial release of developer tools and a simulator needed to allow developers to build apps for the Vision Pro headset."
    },
    {
      title: 'HyperPack Pro Tech Backpack With Find My Integration Now Available',
      time: 'Friday June 23 |  2023 1:05 pm PDT',
      img: 'https://images.macrumors.com/t/lqif3K36N3hd4kf_J6V4ycKvXSI=/400x0/article-new/2022/12/hyperpack-pro-feature.jpg?lossy',
      link: 'https://www.macrumors.com/2023/06/23/hyperpack-backpack-find-my/',
      desc: 'Popular accessory maker Hyper this week announced the launch of its HyperPack Pro backpack, which has built-in Find My functionality. Hyper has been working on the backpack since last year, launching it via a crowdfunding campaign on Indiegogo, but it now has wide availability from the Hyper website.'
    },
    {
      title: "LG Offering Two Free Months of Apple's MLS Season Pass",
      time: 'Friday June 23 |  2023 10:37 am PDT',
      img: 'https://images.macrumors.com/t/Iyv_8A5UBVhibaA0jLabEJCu3OE=/400x0/article-new/2023/06/lg-mls-trial.jpg?lossy',
      link: 'https://www.macrumors.com/2023/06/23/lg-mls-season-pass-deal/',
      desc: 'LG today announced that LG Smart TV owners in the United States can sign up for two free months of Major League Soccer Season Pass using the Apple TV app, allowing access to every live Major League Soccer match, including Leagues Cup, All-Star games, and playoffs.'
    },
    {
      title: 'Best Apple Deals of the Week: 10.2-Inch iPad Hits All-Time Low Price of $249.99 Amid Sales on Apple Watch and MacBook Pro',
      time: 'Friday June 23 |  2023 10:12 am PDT',
      img: 'https://images.macrumors.com/t/uQQoYVQJJT_A9MAU9Gv77ThOXXo=/400x0/article-new/2022/06/Hero0001.jpg?lossy',
      link: 'https://www.macrumors.com/2023/06/23/best-apple-deals-of-the-week-6-23-23/',
      desc: "This week we got news about Amazon's upcoming Prime Day 2023 sale and tracked a few deals on Apple products including the 10.2-inch iPad, M2 MacBook Pro, and Apple Watch Series 8. We also have an exclusive promo code running at Satechi through the end of the weekend. "
    },
    {
      title: 'The MacRumors Show: Two Weeks Using watchOS 10, iOS 17, and macOS Sonoma',
      time: 'Friday June 23 |  2023 9:20 am PDT',
      img: 'naN',
      link: 'https://www.macrumors.com/2023/06/23/the-macrumors-show-ios-17-macos-sonoma-betas/',
      desc: "After spending two weeks using the beta versions of watchOS 10, iOS 17, iPadOS 17, macOS Sonoma, and tvOS 17, we discuss our experiences and highlight our favorite new features from each of the updates on this week's episode of The MacRumors Show.‌iOS 17‌ introduces features like StandBy mode, Contact Posters, and Live Voicemail, while ‌iPadOS 17‌ makes some meaningful enhancements to Stage Manager, introduces external camera support, and brings over Lock Screen customization, Live Activities, and the Health app from the iPhone.‌macOS Sonoma‌ adds an integrated video screen saver and wallpaper experience, desktop widgets, Safari web apps, and Game Mode. tvOS 17 is a modest update that redesigns the Control Center and introduces FaceTime via Continuity Camera.A large number of new features, like interactive widgets, improved autocorrect, the Messages redesign, offline maps, authentication code autofill, Apple Music crossfade, Note links, support for multiple timers, video call reactions and presenter overlays, and improved PDF support, come to several of Apple's updated operating systems.Listen to The MacRumors Show in Apple Podcasts, Spotify, Overcast, Pocket Casts, Castro, Google Podcasts, or your preferred podcasts app. You can also copy our RSS feed directly into your podcast player. Watch a video version of the show on the MacRumors YouTube channel.Subscribe to ‌The MacRumors Show‌ for more episodes, where we discuss some of the topical news breaking here on MacRumors, often joined by exciting guests like Andru Edwards, Kevin Nether, Arnold Kim, Ben Sullins, Mark Gurman, Marcus Kane, Christopher Lawley, Frank McShan, David Lewis, Tyler Stalman, Jon Prosser, Sam Kohl, Quinn Nelson, John Gruber, Federico Viticci, Sara Dietschy, Luke Miani, Thomas Frank, Jonathan Morrison, iJustine, Ross Young, Ian Zelbo, Jon Rettinger, and Rene Ritchie. You can also head over to The MacRumors Show forum thread to engage with us directly. Remember to rate and review the show, and let us know what subjects you would like the podcast to cover in the future."
    },
    {
      title: 'Apple Reportedly Planning to Switch Technology Behind A17 Bionic Chip to Cut Costs Next Year',
      time: 'Friday June 23 |  2023 7:27 am PDT',
      img: 'https://images.macrumors.com/t/BiHMvqQvo_J7IN1du_3rAwnXV4Y=/400x0/article-new/2023/06/A17-Feature-Dark.jpg?lossy',
      link: 'https://www.macrumors.com/2023/06/23/apple-to-switch-tech-behind-a17-to-cut-costs/',
      desc: 'The A17 Bionic chip initially used in the iPhone 15 Pro and ‌iPhone 15 Pro‌ Max later this year will fundamentally differ from a version of the same chip set to be manufactured in 2024, a new rumor claims.'
    },
    {
      title: "Here's How Interactive Widgets Work in macOS Sonoma",
      time: 'Friday June 23 |  2023 3:38 am PDT',
      img: 'https://images.macrumors.com/t/p4vx_bzr1H9LNIrfy3P-CRRj9b0=/400x0/article-new/2023/04/Widgets-on-Your-Mac-Thumb-3.jpg?lossy',
      link: 'https://www.macrumors.com/guide/how-widgets-work-macos-sonoma/',
      desc: "In macOS Sonoma, Apple has changed the widgets landscape. No longer do widgets have to be hidden offscreen and largely forgotten in the Notifications Center panel. Now they live right on your desktop – and they're interactive, too."
    },
    {
      title: 'Apple Reportedly in Discussions With Banks to Launch Apple Card in India',
      time: 'Friday June 23 |  2023 3:04 am PDT',
      img: 'https://images.macrumors.com/t/Wo8aSfwZPT12DsGvZbW_c_WLyF8=/400x0/article-new/2023/06/Apple-Card-Balance.jpeg?lossy',
      link: 'https://www.macrumors.com/2023/06/23/apple-seeks-apple-card-launch-india/',
      desc: 'Apple is in talks with banks to launch Apple Card in India, claims a report by local finance website Moneycontrol. '
    },
    {
      title: 'LG to Bring AirPlay to Hotel Room TVs Later This Year',
      time: 'Thursday June 22 |  2023 4:31 pm PDT',
      img: 'https://images.macrumors.com/t/g8_OtdTt_9g4tapRYLwBhOegWLI=/400x0/article-new/2023/06/airplay-hotels.jpg?lossy',
      link: 'https://www.macrumors.com/2023/06/22/lg-airplay-hotel-room-tvs/',
      desc: "LG Electronics will be one of the first TV manufacturers to support Apple's AirPlay expansion, which will see Apple bringing easy access ‌AirPlay‌ to hotel room TVs."
    },
    {
      title: 'Video: A First Look at visionOS for the Apple Vision Pro',
      time: 'Thursday June 22 |  2023 10:42 am PDT',
      img: 'naN',
      link: 'https://www.macrumors.com/2023/06/22/visionos-hands-on/',
      desc: `Apple yesterday released the first ever beta of visionOS and the SDK that will allow developers to create apps for the Apple Vision Pro headset. visionOS can only be explored through Xcode right now, but we thought we'd take a hands-on look to see what we can glean about the headset experience from the operating system.You can only see the operating system on the screen of your Mac, so it's not what the headset will really be like, and you can't experience the same level of immersion. That said, you can see what ‌visionOS‌ will look like, including the Home View and app windows, plus you can see how 2D iPad and iPhone apps will look.Webpages can be loaded into a ‌visionOS‌ version of Safari so website developers can see what their webpages will look like and what needs to be tweaked. Everything looks a lot like iOS, but if iOS were in your living room or kitchen.There's a Control Center with customizable options for things like light and dark mode, and there's a Guest Mode, which is how you'll be able to let curious people try out the headset without access to your sensitive data. Spotlight is available for searches, and you can set up a range of "Environments" that block out the world around you.From the ‌visionOS‌ Xcode experience and ‌visionOS‌ code we know there are over a dozen Environments you can select, such as Joshua Tree, Yosemite, Mount Hood, and even the moon. There's a Visual Search feature that will be able to identify items around you, copy printed text from the real world, translate languages in real time, and more, plus Apple has designed a Travel Mode that can be activated when you're on an airplane.Travel Mode ensures that you're stationary while you're wearing the Vision Pro, and it blocks out distractions around you. Certain sensors are turned off, perhaps for the privacy of other passengers or because close proximity to a number of other people can cause the sensors to malfunction.Apple will provide Vision Pro testing labs to developers in several locations worldwide starting next month, plus the company is going to open up applications for a hardware-based Vision Pro developer kit that will allow developers to test their apps right on the Vision Pro itself.Make sure to watch our full video to get a closer look at the early stages of ‌visionOS‌.`
    },
    {
      title: 'Latest iOS 17 Beta Makes Haptic Touch Faster',
      time: 'Thursday June 22 |  2023 9:52 am PDT',
      img: 'https://images.macrumors.com/t/LMqmshPGGuq8MGnTuTrQM7e_uDE=/400x0/article-new/2023/06/haptic-touch-ios-17-fast.jpg?lossy',
      link: 'https://www.macrumors.com/2023/06/22/ios-17-haptic-touch-faster/',
      desc: 'The second beta of iOS 17 that Apple released to developers yesterday includes a setting that makes the haptic feedback feature activate faster than before, which some users may prefer.'
    },
    {
      title: "Apple Vision Pro to Feature 'Travel Mode' for Better In-Flight Experience",
      time: 'Thursday June 22 |  2023 9:10 am PDT',
      img: 'https://images.macrumors.com/t/EZ7NZyKdMADPUJ41f72JXA5-8C0=/400x0/article-new/2023/06/apple-vision-pro-airplane.jpg?lossy',
      link: 'https://www.macrumors.com/2023/06/22/apple-vision-pro-travel-mode/',
      desc: 'Apple has an intriguing hidden feature for its Apple Vision Pro spatial computer in the first developer beta of visionOS. The feature, termed "Travel Mode," is specifically aimed at enhancing the user experience while on board an airplane.'
    },
    {
      title: 'Deals: Apple Watch Series 8 Models Drop to Best-Ever Prices on Amazon, Starting at $329',
      time: 'Thursday June 22 |  2023 7:51 am PDT',
      img: 'https://images.macrumors.com/t/5771NA4FQ_0y1hxcm7zfPt0oG2U=/400x0/article-new/2023/06/series-8.jpg?lossy',
      link: 'https://www.macrumors.com/2023/06/22/deals-apple-watch-series-8-amazon/',
      desc: 'Amazon today has a few deals on the Apple Watch Series 8, including all-time low prices on both 41mm and 45mm GPS models. All of the watches mentioned below are in stock and ready to ship, with delivery dates around June 24 in most cases.'
    },
    {
      title: "Apple Vision Pro 'Visual Search' Feature Can Identify Items, Copy Printed Text, Translate and More",
      time: 'Wednesday June 21 |  2023 5:39 pm PDT',
      img: 'https://images.macrumors.com/t/vSE1u3hvNu7GljTpULoIhbYQd_U=/400x0/article-new/2023/06/vision-pro-headset-1.jpg?lossy',
      link: 'https://www.macrumors.com/2023/06/21/vision-pro-visual-search-feature/',
      desc: `The Apple Vision Pro headset's visionOS operating system includes a feature called "Visual Search," which sounds like it is similar to the Visual Lookup feature on the iPhone and the iPad.`
    },
    {
      title: "Here Are All the 'Environments' You Can Experience in visionOS",
      time: 'Wednesday June 21 |  2023 4:00 pm PDT',
      img: 'https://images.macrumors.com/t/4kBysEnG1JthJKbqoub3P4x9u6E=/400x0/article-new/2023/06/vision-pro-environments.jpg?lossy',
      link: 'https://www.macrumors.com/2023/06/21/visionos-environments/',
      desc: 'With the Vision Pro headset, there is an option to activate an Environment that allows you to shut out the world around you. While Apple has mentioned Mount Hood as an Environment you can visit and use as a backdrop, there are several others.'
    },
    {
      title: 'Everything New in iOS 17 Beta 2',
      time: 'Wednesday June 21 |  2023 3:16 pm PDT',
      img: 'https://images.macrumors.com/t/DYgTbekf1q7MbWVjJvQU-HP48oo=/400x0/article-new/2023/06/General-iOS-17-Feature-Blue-Green.jpg?lossy',
      link: 'https://www.macrumors.com/2023/06/21/everything-new-in-ios-17-beta-2/',
      desc: "Apple today released the second beta of upcoming iOS 17 and iPadOS 17 updates to developers for testing purposes, and like all new betas for a major point update, the software includes a number of small tweaks and changes as Apple refines the operating systems ahead of launch. We've aggregated everything new that we've found in the second beta so far. "
    },
    {
      title: 'Apple Releases Second Studio Display 17 Firmware Beta',
      time: 'Wednesday June 21 |  2023 2:30 pm PDT',
      img: 'https://images.macrumors.com/t/7_ElUchup9rSyqAyn-MJoME4jF0=/400x0/article-new/2022/03/apple-studio-display-blue.jpg?lossy',
      link: 'https://www.macrumors.com/2023/06/21/apple-studio-display-17-firmware-beta-2/',
      desc: 'Apple today released a second Studio Display 17 firmware beta, with the update coming two weeks after the release of the first beta.'
    },
    {
      title: 'Apple Releases First Ever visionOS Beta',
      time: 'Wednesday June 21 |  2023 1:48 pm PDT',
      img: 'https://images.macrumors.com/t/0vVmKZANO7EIaoIfc_CpDGvNkBg=/400x0/article-new/2023/06/visionos-home-screen-mt-hood.jpg?lossy',
      link: 'https://www.macrumors.com/2023/06/21/apple-releases-first-ever-visionos-beta/',
      desc: 'Apple today introduced the first version of the visionOS software, debuting the ‌visionOS‌ 1.0 Developer Beta. The introduction of the beta comes as Apple has announced the launch of the ‌visionOS‌ software development kit (SDK) that will allow third-party developers to build apps for the Vision Pro headset.'
    }
  ]
}
```

<br><br>

All news rights belong to [macrumors.com](https://www.macrumors.com) site 
