---
cover: .gitbook/assets/road.jpeg
coverY: -9.967999999999996
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🛣 The Node Less Traveled By: The Road to Ethereum Independence

## Phase 1: Hardware

<figure><img src=".gitbook/assets/everything-rotated Large.jpeg" alt=""><figcaption><p>All of our boxed components</p></figcaption></figure>

### Gather the Things

Pictured above are the hardware components needed to setup our node:

{% hint style="info" %}
It's okay if your specific components don't look like what's pictured above, the important thing is you have one of each: a SSD, RAM, and a computer to run the node
{% endhint %}

* The black box in the top left is called an NVME SSD
  * You may already be familiar with an SSD, it's commonly known as a "hard drive"
  * This SSD is where all the data for our node is going to be stored, from the actual operating system to each block our node receives as part of the blockchain
* Below it, in the bottom left, is our RAM which is also called "memory"
  * RAM is used by our computer to hold information that doesn't need to be permanently stored on the SSD
    * For example, the actual software we're going to be running for syncing the blockchain is going to be loaded into memory while it's running
* The big box to the right is our Intel NUC, the actual computer that's going to be running the node software to sync us with the blockchain

Aside from what's pictured above, we need two more items: A small screwdriver and at least a 32 GB USB

<figure><img src=".gitbook/assets/screwDriveAndUsb Large.jpeg" alt=""><figcaption><p>A USB and a small screwdriver</p></figcaption></figure>

### Unbox the Things

#### The Intel NUC

<figure><img src=".gitbook/assets/IMG_4497 Large.jpeg" alt=""><figcaption><p>This is everything included in the box</p></figcaption></figure>

Starting with the Intel NUC, let's go over everything included in the box (ignoring the actual box 😉):

* All the way to the left is a black metal plate
  * This plate is would allow you to mount the Intel NUC onto the back of a computer monitor that supports [VESA mounting](https://www.ergotron.com/en-us/support/vesa-standard)
* In the middle is our Intel NUC
* To the top right of the NUC is what I believe is a standoff screw, but it's not mentioned in the included manual and I'm not sure where it even goes. It's okay though, we're not going to use it 🙂
* To the bottom right of the NUC are some extra screw that I believe are for mounting the NUC to the back of a computer monitor using the included metal plate
* In the top right is our power supply used to power the NUC
* And below it is our standard instruction manual and safety precautions

For this guide you can ignore everything but the NUC and the power supply:

<figure><img src=".gitbook/assets/IMG_4499 Large.jpeg" alt=""><figcaption><p>Our Intel NUC and our power supply</p></figcaption></figure>

#### The RAM

<figure><img src=".gitbook/assets/IMG_4500 Large.jpeg" alt=""><figcaption><p>Our RAM (a.k.a. memory)</p></figcaption></figure>

Your exact RAM packaging may differ, but this one is pretty nonsense and only contains two RAM sticks

{% hint style="info" %}
You may only have a single RAM stick and that's fine. Pictured below are two 16 GB sticks of RAM, but they come in various configurations e.g. one stick that's 32 GB, one stick that's 64 GB, etc.
{% endhint %}

<figure><img src=".gitbook/assets/IMG_4501 Large.jpeg" alt=""><figcaption><p>Two 16 GB sticks of RAM</p></figcaption></figure>

#### The SSD

<figure><img src=".gitbook/assets/IMG_4502 Large.jpeg" alt=""><figcaption><p>Our NVME SSD</p></figcaption></figure>

Your SSD packaging may also differ, but it's probably going to contain the same as pictured below:

<figure><img src="broken-reference" alt=""><figcaption><p>Our opened NVME SSD</p></figcaption></figure>

Included in the box is:

* In the top left is the standard manufacture disclosures
* In the bottom left is the NVME SSD

#### All the Unboxed Things

<figure><img src=".gitbook/assets/IMG_4504 Large.jpeg" alt=""><figcaption><p>All of our unboxed components: NVME SSD, two sticks of RAM, the Intel NUC, and it's power supply</p></figcaption></figure>

### Assemble the Things

#### Opening Up the NUC

The first step in assembling our node is to unscrew the bottom cover of the NUC. Pictured below is the bottom of the NUC with the four screws we need to unscrew highlighted by the red squares:

{% hint style="info" %}
**Note:** The four screw are _captured,_ meaning they're not going to come out of their holes no matter how much you unscrew them. When they become loose and you can move the screw up and down, that's how you'll know it's completely unscrewed
{% endhint %}

<figure><img src=".gitbook/assets/IMG_4505 Large.jpeg" alt=""><figcaption><p>Unscrew the four highlighted screws to remove the bottom cover of the NUC</p></figcaption></figure>

{% hint style="info" %}
**Note:** We're going to remove the bottom cover of the NUC, but **be careful** when you do so because there is a _ribbon cable_ attached to the bottom cover (see the below image to see what this ribbon cable looks like) that you don't want to accidentally rip apart if you remove the bottom cover a bit too vigorously 💪&#x20;

The first time you remove this bottom cover, it might be _a bit_ stiff so it might require just a _little bit_ of _umph -_ You'll figure it out though, I believe in you 🙂 (plus we don't use the ribbon cable, so if you accidentally damage it, it's not the end of your node)
{% endhint %}

Next we're going to open up the NUC by removing the bottom cover. To do so, hold onto the NUC with one hand and pull up using one of the screw with the other hand. Once you seperate the bottom cover from the rest of the NUC, carefully place it off to the side like so:

<figure><img src=".gitbook/assets/IMG_4506 Large.jpeg" alt=""><figcaption><p>An opened up NUC</p></figcaption></figure>

#### Installing the RAM

<figure><img src=".gitbook/assets/IMG_4507 Large.jpeg" alt=""><figcaption><p>The RAM slots highlighted by a red rectangle</p></figcaption></figure>

Highlighted in the above image are the slots we're going to insert our RAM into. This part is going to _feel_ like you're going to break something, but it does require _a little bit_ of effort to full push the RAM into it's slot. You're also going to be inserting the RAM at a _slight_ angle and then you'll push it down into the silver bracket (highlighted in the below image) that'll hold the stick of RAM on it's sides

Insert the **gold side** of the first stick (or your only stick if you only have one stick) of RAM into the **bottom** slot. The **gold side** of the RAM will have a small section missing from it, this gap lines up with a solid piece in the slot we're sticking the RAM into. Make sure your stick of RAM is correctly orientated and the gap in the stick lines up with the solid piece in the slot before trying to push the stick into the slot (otherwise you'll damage the stick of RAM)

Once you've inserted the stick of RAM, it'll look like:

<figure><img src=".gitbook/assets/IMG_4508 Large.jpeg" alt=""><figcaption><p>The first slotted stick of RAM, highlighted is the bracket that holds the stick of RAM by it's sides</p></figcaption></figure>

If you have a second stick of RAM, insert it in the top slot same as you did the first one (also making sure to push down slightly on the stick to push in into the bracket):

<figure><img src=".gitbook/assets/IMG_4509 Large.jpeg" alt=""><figcaption><p>The second stick of RAM slotted into it's place</p></figcaption></figure>

#### Installing the SSD

<figure><img src=".gitbook/assets/IMG_4510 Large.jpeg" alt=""><figcaption><p>The SSD slot highlighted by a red rectangle</p></figcaption></figure>

Next, and the last step before we close up the NUC, we're installing our SSD. To do so, there's a small screw we need to remove first - I've highlighted the screw in the above image, please completely unscrew it and set it off to the side

After completely removing the screw, insert your SSD **gold side** first into it's slot. Like the RAM, there's a small gap in the **gold side** that aligns with a solid piece in the slot. Please make sure you're lining up the gap with the solid piece before trying to insert the SSD

<figure><img src=".gitbook/assets/IMG_4511 Large.jpeg" alt=""><figcaption><p>The SSD inserted into it's slot</p></figcaption></figure>

As you can see in the above picture, the SSD is going to be at a weird angle after inserting and that's completely fine. The tiny screw we removed is going to hold down the SSD

Please reinsert the tiny screw into it's hole, making sure it's holding down the SSD by the **gold half circle** that lines up with the screw hole. After reinserting the screw, it should look like:

<figure><img src=".gitbook/assets/IMG_4512 Large.jpeg" alt=""><figcaption><p>A NUC with the RAM and SSD slotted into their places</p></figcaption></figure>

#### Batten Down the Hatches

Now that we've installed the RAM and the SSD, it's time to screw the bottom cover back on, completing our assembly of our node, congrats 🎉

## Phase 2: Operating System

Now that we've assembled the hardware, it's time to finish turning it into a computer by installing an operating system (sometimes abbreviated as OS). As is, if you purchased the barebones model, your NUC doesn't have an operating system. If you're unfamiliar with the term, the operating system is what you're most likely heard as "Windows", "MacOS", or maybe you've even heard of "Linux". Your OS is what allows you to use software with your hardware, without it your NUC is just a box that doesn't do much besides turn on

### Gather More Things

To install your OS, you're going to need the following

* A computer (aside from our NUC 😉)
* A USB with at least 16 GB of space
  * **Note:** All of the data on the USB is going to be erased, please use a new USB or one that doesn't contain **any** data you care about
* A display to connect your NUC to
* An HDMI cable
* A keyboard

### Downloading the OS

For our NUC, we're going to be using a Linux operating system, specifically we're going to be using the Ubuntu Server [distribution](https://www.suse.com/suse-defines/definition/linux-distribution/) (for an explainer on why we're choosing Linux, please refer to [this](https://www.logicmonitor.com/blog/9-reasons-linux-is-a-popular-choice-for-servers), or feel free to search "Why use Linux for servers")

Because Linux is open source software, it's actually free to download and free to use :tada: We're going to download a file called an [ISO](https://www.geeksforgeeks.org/iso-full-form/) from the official Ubuntu website's [download page](https://ubuntu.com/download/server):

{% hint style="info" %}
Depending on when you are viewing this guide, the Ubuntu download page make look different from what's pictured below, regardless, there should be a big download button somewhere\
\
It's also okay if the version number when you download Ubuntu Server is different from what's shown below (version `22.04.3`)
{% endhint %}

<figure><img src=".gitbook/assets/ubuntu-download.png" alt=""><figcaption><p>The Ubuntu Server download page</p></figcaption></figure>

If you haven't already, go ahead and click the big green button to download the Ubuntu Server ISO (it may take a while to download)

### Flashing Our USB

In order to install the operating system onto our NUC, we're going to need a way to install the Ubuntu Server ISO you just downloaded onto our NUC - this is where that USB comes in

Now just transferring the Ubuntu Server ISO file onto the USB isn't enough, we need to _flash_ the ISO onto the USB so that when we plug it into our NUC, it can recognize it as an operating system it can run on it's hardware

#### Installing Etcher

To do this, we're going to download a program called [balenaEtcher](https://etcher.balena.io/#download-etcher), another free piece of useful software. Once again, go ahead and click the big green button to download it

<figure><img src=".gitbook/assets/balena-etcher.png" alt=""><figcaption><p>The balenaEtcher download page</p></figcaption></figure>

After clicking the download button if you see the below screen:

<figure><img src=".gitbook/assets/downloadEtcher.png" alt=""><figcaption><p>The download section for Etcher</p></figcaption></figure>

Go ahead and click the `Download` link that corresponds to the operating system of the computer you're currently using. If you're using Windows, it'll be the very first `Download`, if you're using MacOS it'll be the 4th from the top, and for Linux the 2nd to last

Depending on your OS, installing Etcher is going to look a little different. I'm writing this guide on a macbook, so below is the installation process for MacOS, but regardless the installation process should be pretty similar

#### Installing Etcher on MacOS

When you clicked the `Download` button for Etcher, you downloaded a `.dmg` file. You've probably already gone through the process of installing apps downloaded from the web on your Mac already, but just incase you haven't, double click the downloaded file and you should see the screen:

<figure><img src=".gitbook/assets/etcher-installer.png" alt=""><figcaption><p>The balenaEtcher installer</p></figcaption></figure>

Then click on the balenaEtcher app and drag it into the `Applications` folder as depicted by the arrow, then you can close this screen

Next, launch the balenaEtcher app by opening up `Spotlight search` by pressing and holding the `⌘` key on your keyboard and the `Space bar`. Then type in `etcher` like so and press the `return` key to launch the app:

<figure><img src=".gitbook/assets/spotlight-search-etcher.png" alt=""><figcaption><p>Spolight search for Etcher</p></figcaption></figure>

If you see the following pop-up, click `Open`:

<figure><img src=".gitbook/assets/security-warning-etcher.png" alt=""><figcaption><p>MacOs security warning</p></figcaption></figure>

#### The Balena Etcher App

Regardless of your OS, you should after installing Etcher and opening the app, you should something similar to:

<figure><img src=".gitbook/assets/balena-etcher-app.png" alt=""><figcaption><p>The Balena Etcher app</p></figcaption></figure>

Now we're going to _flash_ our downloaded ISO file onto our USB by clicking the blue `Flash from file` button. Upon clicking, your OS's file picker should popup:

<figure><img src=".gitbook/assets/etcher-file-picker.png" alt=""><figcaption></figcaption></figure>

Go ahead and navigate to where you downloaded the Ubuntu Server ISO file (mostly likely this will be your OS's `Downloads` folder), click the ISO file, and click the `open` button in the bottom right. Afterwards you should see the `Select Target` button turn to blue:

<figure><img src=".gitbook/assets/etcher-select-target.png" alt=""><figcaption><p>Etcher select target</p></figcaption></figure>

Before continuing, plug in the USB you want flash the OS onto into your computer. Afterwards, click the blue `Select target` button and you should see a screen similar to:

<figure><img src=".gitbook/assets/etcher-target-picker.png" alt=""><figcaption><p>Etcher target picker</p></figcaption></figure>

{% hint style="danger" %}
It is **very** important you take your time to verify you're selecting the USB you intended to **completely erase all data on** to flash the OS on this screen. Even if you only see one device listed (as pictured above), try unplugging the USB from your computer and verify the device disappears from the selection screen, then plug the device back in and verify the device that reappears is the USB you intend on using
{% endhint %}

<figure><img src=".gitbook/assets/etcher-target-picker-empty.png" alt=""><figcaption><p>An empty target picker because I unplugged my USB</p></figcaption></figure>

<figure><img src=".gitbook/assets/etcher-target-picker.png" alt=""><figcaption><p>My USB reappearing in the target picker after plugging it back in</p></figcaption></figure>

Once you're 100% sure you know which target on this screen is the USB you'd like to use, go ahead and select it:

<figure><img src=".gitbook/assets/etcher-target-selected.png" alt=""><figcaption><p>Etcher with the USB selected</p></figcaption></figure>

Then click the blue `Select 1` button and you should see:

<figure><img src=".gitbook/assets/etcher-ready-to-flash.png" alt=""><figcaption><p>Etcher ready to flash our USB</p></figcaption></figure>

{% hint style="danger" %}
Before clicking the blue `Flash!` button, be 100% sure you're ready to **erase all the data on your USB**. Once you click the blue `Flash!`button, all of the data on the USB will be permanetly erased
{% endhint %}

Once you're ready, click the blue `Flash!`button to begin flashing the Ubuntu Server ISO onto your USB

#### If you're on MacOS, you may see the following popups:

This first one is just MacOS asking you to verify you want to give balenaEtcher access to write to your USB. Enter your password and click the `Ok` button

<figure><img src=".gitbook/assets/enter-password.png" alt=""><figcaption><p>balenaEtcher asking for permission to write to your USB</p></figcaption></figure>

The next popup is also confirming you want to give balenaEtcher access to write to your USB. Click the `OK` button

<figure><img src=".gitbook/assets/etcher-wants-access.png" alt=""><figcaption><p>balenaEtcher asking for permission to access your USB</p></figcaption></figure>

{% hint style="warning" %}
You _may_ see the following scren if you're using a USB with a lot of storage. If you sure you want to erase everything on your USB, click the `Yes, I'm sure` text to continue
{% endhint %}

<figure><img src=".gitbook/assets/etcher-large-drive-warning.png" alt=""><figcaption><p>Etcher larger target confirmation</p></figcaption></figure>

You should see Etcher begin to flash the ISO onto your USB:

<figure><img src=".gitbook/assets/etcher-flashing.png" alt=""><figcaption><p>Etcher flashing ISO onto USB</p></figcaption></figure>

When the flashing process reaches 100%, Etcher will begin to validate the ISO was flashed correctly onto your USB:

<figure><img src=".gitbook/assets/etcher-validating.png" alt=""><figcaption><p>Etcher validating ISO was flashed correctly</p></figcaption></figure>

When you see this screen, you have successfully flashed the Ubuntu Server ISO onto your USB :tada::

<figure><img src=".gitbook/assets/etcher-flash-completed.png" alt=""><figcaption><p>Successful flashing of the USB</p></figcaption></figure>

### Installing the OS

At this point we've assembled the hardware and flashed Ubuntu Server onto our USB. Now we're going to install Ubuntu Server onto our NUC. So go ahead and plug your HDMI cable into the back of your display and connect the HDMI cable, your keyboard, and the USB to the NUC. At this point we're ready to plug in the power supply and power on the NUC by pressing the power button on the front

It may take a second, but with your USB plugged into the NUC, you NUC connected to your display, and both the NUC and your display powered on, you should see:

<figure><img src=".gitbook/assets/grub-selection.png" alt=""><figcaption><p>The Ubuntu Grub installer</p></figcaption></figure>

Go ahead and press `Enter` on your keyboard to select `Try or Install Ubuntu Server`

Eventually you'll see this screen, go ahead and select the language you're comfortable using (you can move the green selection bar up and down using the `up` and `down` arrow keys on your keyboard) by pressing the `Enter` key:

<figure><img src=".gitbook/assets/language-selection.png" alt=""><figcaption><p>Ubuntu language selection</p></figcaption></figure>

If you see something similar to the following screen, go ahead and select `Update to the new installer`:

<figure><img src=".gitbook/assets/installer-update.png" alt=""><figcaption><p>Ubuntu installer updater</p></figcaption></figure>

Next is the `Keyboard configuration` screen, press `Enter` to select `Done`:

<figure><img src=".gitbook/assets/keyboard-config.png" alt=""><figcaption><p>Keyboard configuration</p></figcaption></figure>

On this next screen, we're going to press the `up` arrow on your keyboard to highlight the bottom box for `Search for third-party drivers`:

<figure><img src=".gitbook/assets/search-for-third-party-drivers.png" alt=""><figcaption><p>Selecting <code>Search for third-party drivers</code></p></figcaption></figure>

To select, press the `space bar` your screen should look like:

<figure><img src=".gitbook/assets/selected-third-part-drivers.png" alt=""><figcaption><p>Selected <code>Search for third-party drivers</code></p></figcaption></figure>

Press the `down` arrow on your keyboard to re-highlight `Done`, and then press `Enter` to select it:

<figure><img src=".gitbook/assets/type-of-install-ready.png" alt=""><figcaption><p>Type of install <code>Done</code></p></figcaption></figure>

Next is the `Network connections` screen, this is where we connect our NUC to the internet. I'm not 100% sure what'll see if your NUC is connected to the internet via ethernet cable, but your NUC should also have a built-in WiFi antenna, so for this guide, that's how we'll connect your NUC to the internet

Your view of this screen may be slightly different, but the process of connecting to WiFi using should be the same. We're going to select the NUC's WiFi antenna (the line with `wlan)`  by pressing `up` twice to highlight the antenna like so:

<figure><img src=".gitbook/assets/wifi-highlighted.jpeg" alt=""><figcaption><p>Our wifi antenna highlighted</p></figcaption></figure>

Then press `space bar` to open this menu:

<figure><img src=".gitbook/assets/open-wifi-config.jpeg" alt=""><figcaption><p>Opened WiFi config menu</p></figcaption></figure>

Press `down` twice to highlight `Edit Wifi` andpress `space bar`:

<figure><img src=".gitbook/assets/edit-wifi.jpeg" alt=""><figcaption><p>Edit Wifi highlighted</p></figcaption></figure>

You should see:

<figure><img src=".gitbook/assets/network-info-empty.jpeg" alt=""><figcaption><p>Empty WiFi config</p></figcaption></figure>

Now you can either type in the name of your network if you know what it is, or you can `down` to highlight `Choose a visible network`, press `space bar` to open the menu, press `down` until you get to your network, then press `space bar` to select it. Afterwards, press `down` three types to highlight the `Password` input field and type in your network password. Your screen should look similar to:

<figure><img src=".gitbook/assets/network-info-filled.jpeg" alt=""><figcaption><p>Filled in WiFi config</p></figcaption></figure>

Press `down` to highlight `Save` and press `space bar`. Give your NUC some time to connect to your WiFi to verify everything you entered your password correctly. Once your NUC is connected to WiFi, you screen should look similar to:

<figure><img src=".gitbook/assets/connected-wifi.jpeg" alt=""><figcaption><p>WiFi connected</p></figcaption></figure>

Press `down` twice to select `Done` and press `space bar` to move onto the next screen. This next screen is to configure a proxy, if you don't know what that is, you probably don't need to do it, so you can just press `space bar` to move on:

<figure><img src=".gitbook/assets/proxy-config.png" alt=""><figcaption><p>Configure a proxy</p></figcaption></figure>

&#x20;On the next screen, your NUC is automatically going to test that it can connect to the Ubuntu mirror servers to be able to install software. Let it do it's thing, and when it's done you should see `This mirror location passed tests.` like so:

<figure><img src=".gitbook/assets/ubuntu-mirror-config.png" alt=""><figcaption><p>Passed Ubuntu mirror connection test</p></figcaption></figure>

Go ahead and press `space bar` to move onto the next screen. If you didn't see it before, you may see the `Installer update` screen mentioned above when we started installing Ubuntu. If you do, just select `Update to the new installer`

Now you should see the `Guided storage configuration screen`:

<figure><img src=".gitbook/assets/guided-storage-config.png" alt=""><figcaption><p>Guided storage configuration</p></figcaption></figure>

Everything we need selected, should already selected, but verify `Use an entire disk` is selected, and `Set up this disk as an LVM group`. Then press `down`5 times to highlight `Done` and press `space bar`

Next you'll see a summary of how the operating system is going to install itself onto our SSD:

<figure><img src=".gitbook/assets/storage-config-confirmation.png" alt=""><figcaption><p>Storage configuration summary</p></figcaption></figure>

&#x20;We don't need to change anything here, so go ahead and press `space bar` to continue on. A popup will appear asking you to confirm you'd like to perform a destructive action:

<figure><img src=".gitbook/assets/confirm-destructive-action.png" alt=""><figcaption><p>Confirm destructive action popup</p></figcaption></figure>

This popup is just telling us that we're about to completely erase all data on our SSD, which is fine because the SSD is empty. Press `down` to highlight `Continue` and press `space bar` to confirm.

This next screen is where we setup our user profile:

<figure><img src=".gitbook/assets/profile-setup.png" alt=""><figcaption><p>Profile setup</p></figcaption></figure>

Enter whatever your prefer for the `Your name` section. For `Your server's name` this should be something recognizable like `ethnode` or whatever you prefer, because this is the name that'll show up when you look at what devices are connected to your WiFi router. Enter whatever you'd like in `Pick a username`, but I recommend keeping it short so it's easier to type when we login to the NUC. Lastly, set whatever you like for the password, but it should be sufficiently secure (12 or more characters with some symbols and numbers). When you're all done, press `down` to highlight `Done` and press `space bar` to continue

Next you'll be asked if you'd like Ubuntu Pro security updates, I'm pretty sure this is a paid service and we'll be managing updates ourselves anyways, so just press `space bar` to continue:

<figure><img src=".gitbook/assets/upgrade-to-pro.png" alt=""><figcaption><p>Upgrade to Ubuntu Pro</p></figcaption></figure>

Now you'll be asked to set up SSH, press `space bar` to select `Install OpenSSH server` like so:

<figure><img src=".gitbook/assets/install-ssh-server.png" alt=""><figcaption><p>Install SSH server</p></figcaption></figure>

Then press `down` twice to highlight `Done` and press `space bar` to continue. If you see this next screen, just press `space bar` to continue:

<figure><img src=".gitbook/assets/no-third-party-drivers.png" alt=""><figcaption><p>No third-party drivers</p></figcaption></figure>

Next Ubuntu is asking if we want to pre-install any other software on our node, right now we don't, so just press `down` until `Done` is highlighted, and press `space bar` to continue:

<figure><img src=".gitbook/assets/featured-server-snaps.png" alt=""><figcaption><p>Install snaps</p></figcaption></figure>

On this screen Ubuntu is finalizing the installation process:&#x20;

<figure><img src=".gitbook/assets/ubuntu-install-complete.png" alt=""><figcaption><p>Ubuntu finishing install</p></figcaption></figure>

When the last item on the screen changes from `Cancel update and reboot` to `Reboot Now`, Ubuntu is finished installing:

<figure><img src=".gitbook/assets/ubuntu-install-finished.png" alt=""><figcaption><p>Ubuntu installation complete</p></figcaption></figure>

Press `down` twice to select `Reboot Now`, then press `space bar` to reboot. Next you'll see the last screen of the installation process:

<figure><img src=".gitbook/assets/remove-installation-media.png" alt=""><figcaption><p>Remove media installation</p></figcaption></figure>

The screen is telling us to unplug our USB from the NUC, so that when the NUC reboots we don't go back into the installation menu. So just unplug the USB from the NUC and press `enter`

The NUC will reboot itself and it may a take a while, but eventually you should see:

<figure><img src=".gitbook/assets/first-log-in.png" alt=""><figcaption><p>First Ubuntu log in</p></figcaption></figure>

You don't really need to worry about any of the info on the screen right, however, everything in the section labeled `BEGIN SSH HOST KEY KEYS` should **not** be shared with anyone as this info can be used to remotely access you intel NUC. To clear all this info from your screen, press and hold the `control` key and press `c`. This should clear your console like so:

<figure><img src=".gitbook/assets/clear-log-in-console.png" alt=""><figcaption><p>Cleared console</p></figcaption></figure>

Type in the username you configured, press `enter`, type in your password, then press `enter`. You should have logged into your NUC and see:

<figure><img src=".gitbook/assets/logged-in.png" alt=""><figcaption><p>Logged into our NUC</p></figcaption></figure>

Congratulations :tada:You've successfully installed Ubuntu Server onto your NUC and logged in successfully!
