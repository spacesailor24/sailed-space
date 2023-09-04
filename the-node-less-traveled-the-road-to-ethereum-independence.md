# 🛣 The Node Less Traveled: The Road to Ethereum Independence

* Unboxing Your New Intel NUC and Components
* Flashing Ubuntu Server onto a USB
  * Downloading Ubuntu Server ISO
  * Installing Balena Etcher

## Phase 1: Hardware

### Gather All the Things

<figure><img src=".gitbook/assets/everything-rotated.png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/IMG_4496.png" alt=""><figcaption></figcaption></figure>

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

<figure><img src=".gitbook/assets/screwDriveAndUsb.png" alt=""><figcaption></figcaption></figure>

### Unbox All the Things

#### The Intel NUC

<figure><img src=".gitbook/assets/IMG_4497.png" alt=""><figcaption><p>This is everything included in the box</p></figcaption></figure>

Starting with the Intel NUC, let's go over everything included in the box (ignoring the actual box 😉):

* All the way to the left is a black metal plate
  * This plate is would allow you to mount the Intel NUC onto the back of a computer monitor that supports [VESA mounting](https://www.ergotron.com/en-us/support/vesa-standard)
* In the middle is our Intel NUC
* To the top right of the NUC is what I believe is a standoff screw, but it's not mentioned in the included manual and I'm not sure where it even goes. It's okay though, we're not going to use it 🙂
* To the bottom right of the NUC are some extra screw that I believe are for mounting the NUC to the back of a computer monitor using the included metal plate
* In the top right is our power supply used to power the NUC
* And below it is our standard instruction manual and safety precautions

For this guide you can ignore everything but the NUC and the power supply:

<figure><img src=".gitbook/assets/IMG_4499.png" alt=""><figcaption><p>Our Intel NUC and our power supply</p></figcaption></figure>

#### The RAM

<figure><img src=".gitbook/assets/IMG_4500.png" alt=""><figcaption><p>Our RAM (a.k.a. memory)</p></figcaption></figure>

Your exact RAM packaging may differ, but this one is pretty nonsense and only contains two RAM sticks

{% hint style="info" %}
You may only have a single RAM stick and that's fine. Pictured below are two 16 GB sticks of RAM, but they come in various configurations e.g. one stick that's 32 GB, one stick that's 64 GB, etc.
{% endhint %}

<figure><img src=".gitbook/assets/IMG_4501.png" alt=""><figcaption><p>Two 16 GB sticks of RAM</p></figcaption></figure>

#### The SSD

<figure><img src=".gitbook/assets/IMG_4502.png" alt=""><figcaption><p>Our NVME SSD</p></figcaption></figure>

Your SSD packaging may also differ, but it's probably going to contain the same as pictured below:

<figure><img src=".gitbook/assets/IMG_4503.png" alt=""><figcaption><p>Our opened NVME SSD</p></figcaption></figure>

Included in the box is:

* In the top left is the standard manufacture disclosures
* In the bottom left is the NVME SSD

#### All the Unboxed Things

<figure><img src=".gitbook/assets/IMG_4504.png" alt=""><figcaption><p>All of our unboxed components: NVME SSD, two sticks of RAM, the Intel NUC, and it's power supply</p></figcaption></figure>

### Assemble All the Things

## Unboxing Your Node

* Screws won't come completely out of NUC
* Be careful when removing the bottom plate of the NUC
  * Will require a little bit of force to pull off the plate, but there's a ribbon cable attached to both the plate and the motherboard of the NUC, so don't pull too hard
* Installing the RAM might feel like you're going to snap it or something, but just push the gold side into the slot until it snaps in, and then push the RAM down in the bracket
* Installing the SSD involves removing a small screw, slot the gold side into the slot, and then lightly push down on the SSD so you can screw the screw back in to hold the SSD
