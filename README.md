# thenobelizer

A small tool for everyone who feels the need to get a Nobel Prize in literature

* __scrapper.ipynb__ is a tool for web scrapping Bob Dylan song lyrics. I haven't use scrapy, but biuld a simple une using the class __Song__ from [Sebastian Raschka's github](https://github.com/rasbt/datacollect/tree/master/collect_lyrics)

* __TheNobelizer.ipynb__ is the lyrics generator consisting of a Recurrent Neural Network that predicts the next character in a sequence after it has been trained on Bob Dylan's songs. LTSM type of Recurrent Neural Networks seem to be the trend in sequence-to-sequence problemns, see, for example, [this article](https://arxiv.org/abs/1409.3215)

Some examples of the generated lyrics:

> Knock, knock, knockin' on heaven's door,
> One
> Saying "death, you're right now, you know someone must be losing something"

> I was a-sayin' all the golden light of mirrors
> But no one left to talk to look so long, i'm going
> To tell that
> The hot blowing in the heads
> Flowin' around for silver, lookin' to get it down or never turn about anything you could find the pray

> I think about a highway
> I was high where my heart is ready
> And we can't stand on the crime
> When my stage was still in their highway
> Oh, the highway is out of real?

> It’s all after night, i just saw all the music that we went on what my heart is gone
> Yes, just like pearls shining like you
> What are you flyin'
> In the dividing tree, oh yeah!
> Underneath that tree
> There's only one time bones

> Is it sure is sick of nothing
> To take that way to love with you

> There's no drug that's just the way things shadow or because he don't have to put a price on me
> And he lay down a heavy load.
> I pondered the truth when i see the most.
> Unlearned her fame
> And some high the law like gates of eden



We have also tried a hybrid between Bob Dylan and marilyn Manson, here are some of the generated lyrics:

> Knock, knock, knockin' on heaven's door
> Knock, knock, knockin' on heaven's looking for pain?
> Do you love your guns? (yeah)
> God? (yeah)
> The gambler of gibraltar

* __Disclaimer:__ The act of awarding a Nobel Prize is subjective and reflects the presonal prefferences of the jury. This software cannot guarantee that the user will obtain a Nobel prize.
