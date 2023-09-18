# 🛣 The Node Less Traveled By: The Road to Ethereum Independence

## Phase 1: Hardware

### Gather All the Things

<figure><img src=".gitbook/assets/everything-rotated Large.jpeg" alt=""><figcaption><p>All of our boxed components</p></figcaption></figure>

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

{% hint style="info" %}
**Note:** All of the data on the USB is going to be erased, please use a new USB or one that doesn't contain **any** data you care about
{% endhint %}

<figure><img src=".gitbook/assets/screwDriveAndUsb Large.jpeg" alt=""><figcaption><p>A USB and a small screwdriver</p></figcaption></figure>

### Unbox All the Things

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

### Assemble All the Things

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
