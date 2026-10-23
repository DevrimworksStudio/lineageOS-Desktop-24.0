# lineageOS-Desktop-24.0

A open-source and a desktop interface for computers/tablets based on the lineageOS project

Actually, I wasn't the first to come up with the idea of ​​an "Android for PC." Such projects have existed before and continue to exist today. Google even created a version of Android for PC called "Googlebook OS." In fact, much of our current project is based on Googlebook OS. However, Googlebook OS is closed-source, which means you cannot use it as a foundation for your own projects. While one could try to copy it—much like how macOS is replicated—that is not the right path to take if we want a true, streamlined version of LineageOS.

So, what is the purpose of this project? Or, how does it differ from Google's OS?

The goal is simple: to create an open-source, performance-oriented operating system—free of any unnecessary software and suitable for daily use—and to make it available to a wide range of computers and tablets. Much like LineageOS.

 So, what exactly is the design language like?

While developing the design language, I kept the project's identity in mind and preserved the established design style of LineageOS. The result is a clean, lightweight experience—a blend of Android and Googlebook OS—entirely free from unnecessary visual clutter. In crafting the system, I largely adhered to the design principles of Googlebook OS. This approach maintains the simplicity of a design language like "Material You," prevents software bloat (since this language is the Android default), and ensures a smooth, balanced transition for users moving from Googlebook OS to LineageOS. I believe this is the best possible direction for LineageOS.

*This is not an advertisement. However, I would like to take this opportunity to thank the creator of gbos-vm. Thanks to this software, I had the chance to examine GoogleBook OS directly.

So, what are the differences between LineageOS Desktop and Google's GooglebookOS?

1: A system completely free from AI

In my opinion, this is the most important point—because AI is *everywhere*. If you’ve ever tried Googlebook OS, you’ll likely understand what I mean: Gemini is treated as a core system application, and you’re nudged—or rather, pushed—to use it for almost every task (much like the Copilot situation in Windows). Want to add a widget? There’s AI. Searching for something? AI. Setting a wallpaper? AI. Even just moving your mouse around—or using "Circle to Search" (that feature everyone talks about but no one actually uses)—it’s all "AI-powered." As you might have guessed, none of this exists in LineageOS Desktop; you aren’t forced to use any artificial intelligence.

2: terminal (but one that functions without unnecessary pretension)

I want to address Google here: "Man, setting up a terminal shouldn't be this serious." Have you ever had to run a Debian virtual machine just to use a terminal? Yes, really! That’s exactly what Google required me to do just to access a terminal. And what makes this terminal—which took so much effort to set up—any different from others? I have no idea, because it wouldn't even open! XD Jokes aside, 8 GB of RAM wasn't enough to get the terminal running. So, what should Google have done instead?

<img width="400" height="200" alt="termux" src="https://github.com/user-attachments/assets/7a4f55fc-f2da-4e0f-81b9-9a289e473d0b" />


That’s it! No need for applause—this is the first thing that would come to anyone’s mind, and it actually works! So, no problem there. Of course, just leaving Termux in its basic, superficial state isn’t enough; we complete this masterpiece by granting Termux kernel-level privileges. Honestly, Google, there’s no need to be so uptight about it!

3: dependence on Google services

It might seem like I already covered this in the first part, but if I hadn’t gone into more detail, something like "Lineage AI" could have ended up being the result. I also wanted to elaborate further on the dependency on Google. Lately, Google has started to resemble Apple on the Android front and Microsoft on the desktop side—think Windows and ChromeOS. They belong to different worlds, yet they share a common thread: "Hey, buddy, you can’t delete this browser. Why? Because this whole place would be nothing without it—nothing else could ever take its place! Besides, if this browser goes, your computer will crash, start acting weird, and—who knows—maybe someone will even order 300 pizzas to your house!" Okay, jokes aside—seriously, Google, I get it, Chrome is a fine browser, but why can’t I delete it? What if I want to use Firefox or Opera instead? Even if I do, I still can’t get rid of Chrome. Sure, you can disable it, but Google Play Services is so deeply integrated that you can’t even do that. Does this mean I can’t use a "de-Googled" device? Funnily enough, yes. I don’t even want to talk about this anymore. And no, there won’t be a "LineageOS for Desktop" either—why would there be? Why am I even talking about this? What is the meaning of life?

By the way, the default browser should be Firefox. It’s the default browser for Linux, and it’s open source. Also, to be brutally honest: the AOSP browser is absolute garbage. I think we should start using Firefox as the default.

4: (completely optional, as it is very difficult) x64 support

Fair enough. Let’s agree on this: you’re probably thinking, "No way!" And I have to admit, you’re right—this is a very ambitious request, perhaps beyond my reach. However, the fact that such support is possible has already been proven by operating systems like Bliss OS. Since it’s open-source, I figured you could potentially use their code as a reference to implement this. Besides, this is the one thing that would truly transform it into a proper PC operating system—which is why I wanted to bring it up.

List of devices I’m considering (simplified, simplified, and simplified further)

What the artist is explaining here is that the exact list of devices is not yet determined. They only know which types of devices it will be available for; the final list of supported devices is left up to you.

Tablets

A suggestion from @wkn000 on Reddit. Testing this PC version directly on an Android device would provide a solid foundation, while also bringing the PC experience to tablets. Thanks again for the suggestion!

Computers (ARM64)

This is the primary focus for LineageOS Desktop and my initial target. Examples include "Copilot+" PCs (Windows laptops with ARM64 processors), Apple Silicon Macs, and Google Chromebooks.

Computers (x64)

I’ve already discussed this at length. For those who aren't aware, computers with Intel or AMD processors use this architecture.

Sample screenshots

I mentioned gbos-vm to you right at the beginning; now it’s time to reap the benefits. I’ve prepared some photos that will serve as a perfect reference for you. You can find screenshots of all my designs below.

<img width="1470" height="956" alt="lineageos_desktop_diagnostics2" src="https://github.com/user-attachments/assets/585b5f1c-54c6-41bd-8b5d-2b28f4d2e940" />
<img width="1470" height="956" alt="lineageos_desktop_wallpapers" src="https://github.com/user-attachments/assets/ae1c6cba-ca28-4004-be9a-1bbf7c85d143" />
<img width="1470" height="956" alt="lineageos_desktop_main_screen" src="https://github.com/user-attachments/assets/0ac7ebbb-8b6d-42ba-a984-eb20ff5b478f" />
<img width="1470" height="956" alt="lineageos_desktop_aurorastore" src="https://github.com/user-attachments/assets/0b7d56f1-e72a-4a4f-b242-51d66aba6037" />
<img width="1470" height="956" alt="lineageos_desktop_split_screen_menu" src="https://github.com/user-attachments/assets/129d65c7-3b73-4e4a-9821-4f77091bba64" />
<img width="1470" height="956" alt="lineageos_desktop_aboutmenu" src="https://github.com/user-attachments/assets/946a020a-b4fe-4206-8f17-9a470ad6efbe" />
<img width="1470" height="956" alt="lineageos_desktop_diagnostics1" src="https://github.com/user-attachments/assets/5b31dba7-f697-4316-a00c-ff0f9abc2a75" />
<img width="1470" height="956" alt="lieageos_desktop_files" src="https://github.com/user-attachments/assets/6b566a36-cce4-4337-b828-daa267243d73" />
<img width="1470" height="956" alt="lineageos_desktop_taskmanager" src="https://github.com/user-attachments/assets/b8f1bddf-12f4-4362-982c-119a050da2c1" />
<img width="1470" height="956" alt="lineageos_desktop_lockscreen" src="https://github.com/user-attachments/assets/72808ef0-7e34-45f7-ac03-75e2aaf0a2dc" />
<img width="1470" height="956" alt="lineageos_desktop_controlpanel" src="https://github.com/user-attachments/assets/3cb0c8e0-9e3c-4f89-a911-23ca1740789b" />
<img width="1470" height="956" alt="lineageos_dsktop_calendar_and_notifications" src="https://github.com/user-attachments/assets/7c619b6f-4aa8-4f08-b9ef-ee7cd433e8d0" />
<img width="1470" height="956" alt="lineageos_desktop_one_app_wiew" src="https://github.com/user-attachments/assets/3f1f0e36-b2b5-42b9-9368-b7720147b6e1" />
<img width="1470" height="956" alt="lineageos_desktop_2_app_wiew" src="https://github.com/user-attachments/assets/6231e8b9-c093-4d6c-ba1e-0d509e971da5" />
<img width="1470" height="956" alt="lineageos_desktop_overlapping" src="https://github.com/user-attachments/assets/03aa3d80-8e59-47a0-ba0f-3b5470fe9dec" />
<img width="1470" height="956" alt="lineageos_desktop_rightclick_menu" src="https://github.com/user-attachments/assets/491c71e8-c2f6-412a-b9a6-5dc6bb016c23" />
<img width="1470" height="956" alt="lineageos_desktop_folder" src="https://github.com/user-attachments/assets/fa2a33ee-755b-4563-bb3d-7798a32313bd" />
<img width="1470" height="956" alt="lineageos_desktop_diagnostics3" src="https://github.com/user-attachments/assets/397f192a-3b0c-4c95-b0f3-b043fcbace4b" />


However, please keep in mind that this is a design project. I am currently actively looking for developers. If you would like to help me bring this project to life, please feel free to share your thoughts in the "issues" section here, or in the comments section on the platform where you found this.

Naturally, both parties are open to questions regarding the project.

Thank you for taking the time to look at my project. I hope you liked it!
