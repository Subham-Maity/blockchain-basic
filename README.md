# BlockChain A-Z
## You Can Follow My Own All Research About Blockchain If You Are A Complete Beginner  

# Writer Intro
I am **Subham Maity**
I love Programming. One of the aims I had when I started ```CodeXam``` was to make learning programming easy.

Actually, I was working on this project then I did research and made many projects and then I thought why not make a detailed documentary on it then I started making the documentary which is completely free .
## Help us improve this guide - **Fork, Pull Requests, Shares and Likes are recommended**!



![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/BlockChainXam.jpg)




# **1.Blockchain Intuition:**

## **a.What is Blockchain ?**

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

## **b.SHA256 - Hash**

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

## **c.Immutable Ledger**

Now we are moving on Immutable Ledger

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.f54a9039-572f-468f-8d8e-8c126da38dee.001.jpeg)

Immutable ledger in blockchain refers to any records that have the ability to remain unchanged. It cannot be altered and hence the data cannot be changed with ease, thereby making sure that the security is quite tight. Immutability means that it is very difficult to make changes without collusion

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.f54a9039-572f-468f-8d8e-8c126da38dee.002.jpeg)

How can you prove to someone else that that's your home?

Like why can't you just go up to any house on the street and say that that's your home.Well because in exchange for that money what you get is a **deed** a title deed to the house and whoever has the deed as the owner of the home.So what you need to do the deed is you need to take it to a government authority such as a local council or the city council or some other authority to them they might differ.So there it is.You take the deed there and you register your ownership. You show them the deed and you say this is nowI paid money for it.And I would like to register that it is my home.

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.f54a9039-572f-468f-8d8e-8c126da38dee.003.png)

If that building burns down or what if somebody steals that book or what if somebody wants to come

along and hack that book. And we don't even have to use the word hack because it's a book.They just go in and they're about the page and they glue in a different page where everything is the same except for your entry which they changed.

And then what does that mean?Well that means that all of a sudden you don't have the house anymore like physically you might still be living in the house and you might think it's yours. But in reality just because that one line of information has been erased from a book somewhere in the government authority all of a sudden you don't actually have the house and it's even if it's not a book even if it's an electronic document like an Excel spreadsheet.How difficult is it for somebody to go into an Excel spreadsheet and just change one line.

So it's still very easy.

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.f54a9039-572f-468f-8d8e-8c126da38dee.004.png)

Let's say we have them so every single title every time somebody buys something or sells a house it's a new blog that's added to this chain and it's even OK that we're not even talking about distributing decentralise.And so every time you can see like we've really there's already been some transactions in this block chain and then it's your turn.

You buy a house.And so you add in each transaction and then a couple of months pass by or a couple of years pass by and then somebody comes along and decides to take your home away from you by tampering with the data in the block.

And they also realize that home and they want to report that page of the book but they get into the facility and they see that it's actually not a book.It's a whole block chain.people bought properties or sold properties and all of those are also record in the ledger.And now so if this person tries to tamper with the data in that specific block then what happens is that will change the hash of this block.

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.f54a9039-572f-468f-8d8e-8c126da38dee.005.jpeg)

that will change the hash of this block.to the hash recorded here for the previous block so we have the previous year the field previous hash it will no longer match this one.So this person would have to change this lock as well.

![](https://github.com/Subham-Maity/Blockchain-Research-A-Z/blob/master/Images/Aspose.Words.f54a9039-572f-468f-8d8e-8c126da38dee.006.jpeg)

It would be very easy to tell that very hard for the person to tamper with the record.So unlike in the book where they can just change one entry here they would have to change the all of the entries following yours.And that's what we mean when we say that it's an immutable nature because you cannot change data as soon as data has gone into the box.

