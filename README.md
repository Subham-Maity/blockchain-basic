# BlockChain A-Z
## You Can Follow My Own All Research About Blockchain If You Are A Complete Beginner  

# Writer Intro
I am **Subham Maity**
I love Programming. One of the aims I had when I started ```CodeXam``` was to make learning programming easy.
## Help us improve this guide - **Fork, Pull Requests, Shares and Likes are recommended**!

### [Complete Research Documentary is Here with Animated Pictures For Better Experience](https://docs.google.com/document/d/1yB6Hkohe-y_NbCcozgvQXRgCS3fUvq03pM2vzaQxnSk/edit?usp=sharing)

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/BlockChainXam.jpg)
![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/BlockChainXam2.gif)

# **Blockchain Intuition:**

**a.What is Blockchain ?**

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.001.jpeg)

Digital hash is like a fingerprint of some amount of data. So the block here has its own hash and then the previous hash which is contained within the block as  a reference is actually the hash of the block that came before it.

**1.Basic Of Genesis Block**

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.002.png)

This block is always going to be the first one assuming there's some data it doesn't have a previous hash inside this block because this is the jettisons block is the only block that will

have a previous hash. So we're just going to present them all zeros and then it will have its own hash again.For now let's think of hash as a fingerprint.

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.003.png)

There is block number two and a book on Mattoo also has some data.This time it does have a previous hash and it has its own hash again.

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.004.jpeg)

And as you can see the block is the previous hash of block number two is exactly identical or is exactly block number ones hash and that is where the link comes.That is why abortion is called a chain or a block chain because the blocks are cryptographically linked with each other through these

hashes.And again more of that not to come.

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.005.jpeg)

**Conclusion:**

But this is conceptually hard work: every brought block has its own fingerprint and it also references the fingerprints of the previous block.So if anything were to change and block number one it's fingerprint would change.So if anything were to change here

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.006.jpeg)

anything would change in the data.So somebody were to tamper with the data.This fingerprint would change and it would no longer match this fingerprint.So this block would know or we would know by looking at this block that somebody tampered with this block.

**Why Cryptographically Linked**

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.007.jpeg)

And then again looking at the three data it's got the previous hash it's got its own hash and it's linked to the so on and so on.So again Conceptually we can see that if anybody were to tamper with any block this one and this one then the fingerprints would no longer match up and the chain would be invalid the chain would show that there's something wrong.

**That's why we say that blocks are cryptographically linked together.**

**2.Concept of Blockchain**

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.008.jpeg)

**b.SHA256 - Hash**

**(Secure Hash Algorithm 256)**

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.009.jpeg)

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.010.jpeg)

**1.SHA256**

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.011.jpeg)

So there's our map and we're starting with hash cryptography.

So let's look at a person. There is a person who could be me or you.And we have a fingerprint and different people have different fingerprints so if you look at many different.People they're all going to have different fingerprints to us it is there is a possibility that there'll be somebody with the same fingerprint.But it is very unlikely the ability of that is about one in 60 million.So in a way you can say that a fingerprint is an identifier of a person and that's a very powerful concept which is used by forensics departments in the police where they can identify criminals just by their fingerprints and take that as evidence to court.Now what if we could take the same principle and apply it to digital documents.

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.012.jpeg)

But if we could come up with a sort of fingerprint that would identify these documents for us and such a fingerprint exists called Sha256 hash and looks like this.So the algorithm behind Sha256 was developed by the NSA.

And I know what you're going to say.You've probably heard the NSA in the news in the past couple of years and you might have you know someYou know, like a great opinion about them or the opposite you might not like them or you might be indifferent to them regardless of what is said in the news about the NSA and all those things.One thing they did really well is this sha256 algorithm.It works well.It's very secure. And a lot of places in World War applications used to store passwords.Check digital documents too. And in fact in blotching it is used like one of the core things core principles building blocks of block chain as we will see further down in this section and the code for the algorithm for Sha256 is not secret.It's completely open.Anybody can learn it.

**2.Why Sha256 ?**

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.013.jpeg)

Now this hash is called Sha56 because Sha stands for secure hash algorithm and 256 is the number of bits it takes up in memory.The hash is always 64 characters long and it consists as you can see if not just from digits but actually

from letters as well.That's because it's a hexadecimal hash. It has numbers from 0 to 9 and the letters A B C D E F.So there's a total of 16 of them there.So that means each character in the resulting hash takes up four bits because for the power of two 16 and 4 16 64 is turning 256.That's how these numbers are all linked up together 64 times 4 which is the size of any bit.Basically

any one of these is 256.

And the important thing to note here is that this algorithm works not just for word documents or text documents.It works for any digital document or any digital just anything digital.So you could put a video into the algorithm you could put like text you could put an audio you could put an executable file you could put a whole operating system in there whatever you put in there it will spit out a fingerprint which is a shot of hash.

**3.Kit for Blockchain(SHA256)**

[Click here(link)](https://tools.superdatascience.com/blockchain/hash/)

You will see that there's a whole toolkit over here set up so you can go to log blotching in distribution and so on.And so here what you can do is you can input some data and you will see that you'll come up with.

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.014.jpeg)

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.015.jpeg)

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.016.jpeg)

**Lets Try Some**

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.017.jpeg)

If I delete the text and put the exact text back again the hash will not change that will remain same

Now if we add something symbol like that

**Avalanche effect ?**

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.018.jpeg)

The hash will completely change .That is called the **avalanche effect**.

**Small Fact(64 always) :**

If i put a paragraph over the data the hash will same 64 character

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.019.jpeg)

**4. The 5 requirements for Hash Algorithms:**

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.020.jpeg)

**Number one**

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.021.jpeg)Number one is it has to be one way.So basically what that means is that you cannot go backwards.You cannot go from the hash to the documents so you cannot restore or reverse engineer the document based on the hash.It has to be like a fingerprint like for a human.If you have the fingerprints you cannot restore what the person looks like.You cannot understand you know what color eyes they had or anything else about them.But at the same time you have if you have a person you can always get the fingerprints.There's only one way.

**Number Two**

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.022.jpeg)

Number two is it has to be deterministic meaning that if I take the same document exactly the same document later on and I run the same apply the hash algorithm again I'll get exactly the same result as we saw with that illustration.

**Number three**

Third requirement is that it has to have fast computation and we'll see throughout the documentation why that's important.

**Number Four**

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.023.jpeg)

The fourth requirement is the avalanche effect.And I specifically put an image here because I too like to ingrain this in our memory so we remember that we saw this avalanche on the image.It is an ultra important requirement of the hash algorithm.So let's see what it implies.

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.024.jpeg)

The average effect means that if I take exactly the same document and I change it like make a tiny oil change even one bit of data change in the document for instance we've got a plus one over there here.So if we do that you'll change any change then the hash will be absolutely different.So we really saw that in the demonstration where when we were adding an X or exclamation mark or making some other small changes though the reason is called the avalanche effect is because of how that is implemented inside the algorithm.

We're not going to go into detail now but you'll be able to check that in the paper if you like but it is basically that one change triggers a few changes and they in turn trigger more changes and there are more changes.So it's very smart how it's caused and it's very similar to an avalanche where like one tiny like wrong

step can cause snow to start moving and then more snow moves and snow more snow more and you get an

**avalanche**.

So that's what the avalanche effect is and it's very very important in the application of block chain.

And we'll see why when we're talking about mining in the mining tutorials in this section in this module .You'll see why the avalanche expectation is so important.

**Number Five**

Part five it must withstand collisions.

So what does that mean?

What does static collisions mean?

Well it means like what as we saw with with people that sometimes one in 60 million that you're going

to have to people who have the same thing to print and same thing for the hashing algorithm because

I got the pictures on the screen already.

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.025.jpeg)

I'll explain what the pigeons are doing there.

So with the hash algorithm as you can see it's 64 bits.

Right so it's very limited.Even though there's a lot of different variations as you can have it's still limited, it's not infinite.

And yet the quantity of different digital documents that we can create is unlimited is enormous.We can like there's tons and tons of books tons of different photos being created every single day videos all this stuff.So in essence the amount of digital data we have is much much greater than we can possibly have is much greater than the difference the number of variations of a 64 character representation.And so that means that there is a principle called the **pigeonhole principle**.That means if you have for instance in this case 10 pigeons and only nine holes you're gonna have to put two pigeons into one of those holes.There's no way around that.Right so if you have more of a quantity a then there is slots and quantity B.Then inevitably there will be what we call collisions in quanta in that representation when you try to move from quantity which is much greater to quantity. So naturally

they will be collusions and you can do anything about it just pigeonhole principle and that's OK.The thing with that is that it is so unlikely it is so rare that that will happen that we can deal with it.It's OK it's not going to ruin the whole room.The problem just like with humans and fingerprints we can tolerate that.That's a very rare instance and it's pretty much a very very unlikely to happen.And like it's not going to affect anything if it does happen somewhere sometime.But we must have some collisions what that does mean is that we need the algorithm needs to be able to withstand artificial collisions that for instance pirates can create.And that's a problem.So

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.345f490b-4e64-4bc7-b0ac-d556caf0ba83.026.jpeg)

if you can find a way to create these collisions to make two different documents purposefully have the same hash that's a problem because then you can forged documents then you might have an important document that for instance is who's who this house belongs to.Like ownership document.And it might have a name in there.And if you know if there's a way to forge collisions to create artificial collisions then you will be able to change the name on the documents and the hash will be the same.So the person checking the document by the hash will think that you are the owner of the house.And so that's what we mean by withstand

collisions.So collisions should not be possible.

**Conclusion:**

So there we go, those are the five requirements for secure and safe hash algorithms.They have to be one way deterministic, a fast computation of the avalanche effect and must withstand collisions.

[Read more here:](http://www.staff.science.uu.nl/~tel00101/liter/Books/CrypCont.pdf)